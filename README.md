# Heroku Buildpack for Ruby with the GNU Scientific Library

Heroku Ruby GSL Buildpack is a fork of Heroku's [official Ruby buildpack](https://github.com/heroku/heroku-buildpack-ruby) with added support for the GNU Scientific Library.

## Usage

### Ruby

Example Usage:

    $ ls
    Gemfile Gemfile.lock

    $ heroku create --buildpack git://github.com/gregory/heroku-gsl-buildpack.git#gsl-1.16-ruby

    $ git push heroku master
