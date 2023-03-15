
# Discord Tracker

Hello World Initial Project

## Ideas on what to do

- Maybe like a bot that records everything in every channel that happens in a discord server and log it into a db. we can then use this information to make a graph db and display like connections on how many times someone has talked to someone else or something? I was thinking about putting this bot into a server passively to collect data and create a graph on lol.

- Since we are thinking about doing a scalable application using container management software I would recommend for us to use [kubernetes](https://kubernetes.io/) at first to get our feet wet. If there is opposition to using kubernetes there are other alternatives that do not have as much overhead to learn to get started. Other options include [Docker Swarm](https://docs.docker.com/engine/swarm/), or [nomad](https://www.nomadproject.io/) and prob more but I just didnt look them
  up yet

- We should try looking into when setting up the pipeline for when a code change occurs on github it kicks off the pipeline process and lets kubernetes know to update all of the build files in each of the containers that it manages. This is should be able to be done since it is able to be done in AWS with [ECS](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html). That is just what I am used to. ECS is like AWS version of kubernetes so we should be able to do this in
  kubernetes.

## Installation

Go to this website to install rust

``
https://www.rust-lang.org/tools/install
``

## Authors

- [@JarrodCarson](https://github.com/JarrodCarson)

- [@mamaluigie](https://github.com/mamaluigie)

- [@ToddScroggins](https://github.com/Toddgs)


## Documentation

- Library that we use
https://docs.rs/serenity/latest/serenity/


## Running Tests

- tbd

## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

## FAQ

- tbd
