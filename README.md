# Deprecated

Please use the official [ruby alpine](https://hub.docker.com/_/ruby/) Docker images, e.g.:

```shell
$ docker pull ruby:2.4-alpine
$ docker run --rm ruby:2.4-alpine ruby -e 'puts "Hello World"'
```

Also see [this post](https://www.chrisblunt.com/rails-on-docker-getting-started-docker-ruby-rails/) for a tutorial on getting started with Docker and Ruby on Rails.

---

`ruby 2.3.1` *[Dockerfile](https://github.com/cblunt/alpine-linux-ruby-dockerfile/blob/master/2.3.1/Dockerfile)*

`ruby 2.3.0` *[Dockerfile](https://github.com/cblunt/alpine-linux-ruby-dockerfile/blob/master/2.3.0/Dockerfile)*

Based on [alpine:3.3](https://hub.docker.com/_/alpine/), ruby installed using [ruby-install](https://github.com/postmodern/ruby-install)

## Tools

`bundler` and `git` are installed as basic requirements.

## Usage

To use this image (with Ruby 2.3.1):

    docker run --rm cblunt/alpine-linux-ruby:2.3.1 ruby -e 'puts "Hello World"'
