# README

Relay/GraphQL/React on Rails 4 starter-kit.

## Goals

Make it easy to:
* Start a Relay/GraphQL React project on Rails
* Follow the official Facebook Relay/RelayJS [tutorial](https://facebook.github.io/relay/docs/tutorial.html)

## Resource

* For additional info, please refer to the accompanying article [Relay/RelayJS  on Rails](https://medium.com/@khor/relay-facebook-on-rails-8b4af2057152)

## Instructions

* npm install
* bundle install
* rails s

Access the sample app at http://localhost:3000/static_pages/board.html

## Changing the schema

* Modify app/graph files
* rake graphql:update_schema_json
* rake tmp:clear
* rails s

MIT License

