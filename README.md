# raceday

raceday is an event management system designed to manage race events, participants, categories, enrolments, results and routes.

## project structure

- docs/raceday_database.sql - sql server database script
- docs/raceday_erd.png - entity relationship diagram
- docs/api_endpoint_plan.pdf - planned api endpoints
- .github/workflows/ci.yml - github actions workflow

## database

the database is implemented using sql server. it includes users, events, categories, event categories, enrolments, results and routes.

## api

the api endpoint plan defines the http methods, routes, roles, request bodies and expected responses required by the system.

## ci/cd

github actions is used to validate the required project files whenever changes are pushed to the main branch.
