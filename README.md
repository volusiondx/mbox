# Mbox

Mbox is a collection of Compass extensions and NPM packages for Mozu.

See the full [style guide](http://mbox.netlify.com/).


## Usage with Compass

### Installation

Add this line to your application's Gemfile:

```ruby
gem 'mbox', :git => 'https://github.com/volusiondx/mbox.git'
```

And then execute:

    $ bundle

<!--
Or install it yourself as:

    $ gem install mbox
-->

### Integration

Add this to your config.rb:

    require 'mbox'

Add this to your base scss file:

    @import 'mbox/mbox';

### Compiling

The mbox styles will be compiled into your css the next time you run:

    $ compass watch or bundle exec compass watch

Congratulations! Now you can start using the mbox classes and variables!

### Updating

To update the mbox gem and get the latest changes, run:

    $ bundle update ––source mbox

## Usage with npm

Add this your package.json file:

    "mbox": "https://github.com/volusiondx/mbox"

Add this to your base scss file:

    @import './node_modules/mbox/mbox/stylesheets/_mbox.scss’;

Compile with your build tool of choice


## Development

1. Check out the repo

1. Fork it

2. Create your feature branch `git checkout -b my-new-feature`

3. Commit your changes `git commit -m 'Add some feature'`

4. Push to the branch `git push origin my-new-feature`

5. Create new Pull Request

As you develop locally, it may be helpful to point the gemfile of your application to a local copy of mbox with this:

    gem 'mbox', :path => '/local/path/to/your/mbox/'



<!-- After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake false` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org). -->

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/volusiondx/mbox.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
