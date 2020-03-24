# getting_started

## Team Chat on Matrix
We use Matrix to communicate (https://matrix.org/). Riot is the standard client for Matrix (https://about.riot.im/)

How to get started:
- Download Riot or start the web app: https://about.riot.im/downloads
- Create an account on the free matrix.org homeserver
- send us your username (something like @myusername:matrix.org)


## public graph database
The database is hosted on covid.petesis.com with a public read only user.

The schema for the data can be seen [here](https://www.yworks.com/yed-live/?file=https://gist.githubusercontent.com/yGuy/27c2412bbf0724464c396fe2dc2a6851/raw/CovidGraphSchemaCleaned).

Currently there is an issue with Chrome/Chromium and the SSL certificate. You cannot access the Neo4j Browser via HTTPS in Chrome.

- Neo4j browser: https://covid.petesis.com:7473
- Bolt URL: bolt://covid.petesis.com:7687

- user: public
- password: corona
