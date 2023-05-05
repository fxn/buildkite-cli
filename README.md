# Bk

CLI for poking around Buildkite, like `gh` for GitHub

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/bk`. To experiment with that code, run `bin/console` for an interactive prompt.

## Installation

See Development section while in release

## Usage

Display annoations from a specific build:

    $ bk https://buildkite.com/your-org/your-pipeline/builds/1234

Display annotations from the most recent build (requires `gh`):


    $ bk

More to come?

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment. You can run the command from this checkout with:

    bk $ bundle exec exe/bk [args]

To install this gem onto your local machine, run `bundle exec rake install`. If you want to use `bk` in different ruby versions, you'll need to use your version manager to switch and install it. You might find this snippet useful:

    bk $ rake build
    bk 0.1.0 built to pkg/bk-0.1.0.gem.

    bk $ cd ~/workspace/some-project
    some-project $ gem install ~/workspace/bk/bk-0.1.0.gem

To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/technicalpickles/bk.
