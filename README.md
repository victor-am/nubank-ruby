# Nubank::Ruby

This gem provides a wrapper to Nubank's public API.

It does not have any official support from Nubank nor is endorsed by them. This code is provided as is, I can't give you any guarantee that Nubank won't change the API calls in the future or you block your access accidentaly by overloading their API.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'nubank-ruby'
```

And then execute:

```sh
$ bundle
```

Or install it yourself as:

```sh
$ gem install nubank-ruby
```

## Usage

```ruby
require 'nubank-ruby'
nunank = Nubank.new('<CPF></CPF>', '<PASSWORD>')
nubank.events
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/alfakini/nubank-ruby. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Nubank::Ruby project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/alfakini/nubank-ruby/blob/master/CODE_OF_CONDUCT.md).