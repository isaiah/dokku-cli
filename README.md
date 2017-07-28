# Dokku CLI :anchor:

[![Gem Version](https://badge.fury.io/rb/dokku-cli.svg)](http://badge.fury.io/rb/dokku-cli)
[![Downloads](http://ruby-gem-downloads-badge.herokuapp.com/dokku-cli?type=total)](http://badge.fury.io/rb/dokku-cli)

Dokku CLI is a zero config command line tool for the official version of [Dokku](https://github.com/progrium/dokku).

## Installation
```
$ gem build dokku-cli && gem i dokku-cli-1.0.0.gem
```

## Usage

Dokku CLI reads the domain of your Dokku server from your git remote called dokku and requires no configuration. Change in your application directory and run ``dokku``


## Remote Commands

```
dokku run <cmd>   # Run a one-off command in the environment of the app
```

## All commands

```
$ dokku help --remote=staging

Options:
  [--remote=REMOTE]
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/dokku-cli/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
