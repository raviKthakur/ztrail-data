# ztrail-data
The backend initialiser for ztrail data.

Backend support for ztrail data. Uses Google's News API to gather
all trending stories >> Gets feed from trends.csv

Relates stories over multiple sources that the API provides.

A "Trail" is defined as an event in the timeline of a story. A story can have mutliple passing trails.
All trail data is stored in MongoDB identifiable by the mongo default id.

An end trail is stored per story identifier in Postgres.

The versions will be updated as the project proceeds.
