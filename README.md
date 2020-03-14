# Myapp

Welcome to your new Hanami project!

## Setup

Build image:

```sh
$ docker-compose build
```

How to run the development server:

```sh
$ docker-compose up
```

How to run tests:

```sh
$ docker-compose run --rm app bundle exec rake
```

How to run the development console:

```sh
$ docker-compose run --rm app bundle exec hanami console
```

How to prepare (create and migrate) DB for `development` and `test` environments:

```sh
$ docker-compose run --rm app bundle exec hanami db prepare

$ docker-compose run --rm -e HANAMI_ENV=test app bundle exec hanami db prepare
```

Explore Hanami [guides](https://guides.hanamirb.org/), [API docs](http://docs.hanamirb.org/1.3.3/), or jump in [chat](http://chat.hanamirb.org) for help. Enjoy! 🌸
