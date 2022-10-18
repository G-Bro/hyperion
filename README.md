# Hyperion

Hyperion is an Elixir based event tracking system

## Getting Started

### Requirements

* You must have Elixir v1.12 or above installed https://elixir-lang.org/install.html#gnulinux

1. install hex
`mix local.hex`

2. install dependencies
`cd src && mix deps.get`

3. initialise the database
`docker-compose run phoenix bash`
`mix ecto.setup`

4. install node dependencies
`docker-compose run phoenix bash`
`cd assets && npm install`

5. run the app
`docker-compose up`