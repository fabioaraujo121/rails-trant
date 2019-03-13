# Rails-Treant

This is a gem to integrate the [Treant.js](http://fperucic.github.io/treant-js/) library with Ruby on Rails. This is a simple gem. Tested with Ruby on Rails 5.2.0.  

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'rails-treant'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rails-treant

## Usage

1. Add to your **application.js** (/app/assets/javascripts/application.js)
 ```//= require jquery.easing```  
 ```//= require jquery.mousewheel```  
 ```//= require perfect-scrollbar```  
 ```//= require raphael```  
 ```//= require Treant ```  

2. Add to your **aplication.css** (/app/assets/stylesheets/application.css)  
 ```*= require perfect-scrollbar```  
 ```*= require Treant```  

3. Be happy using it!

#### To use just see the examples at [Treant.js](http://fperucic.github.io/treant-js/) and github [examples](https://github.com/fperucic/treant-js/tree/master/examples)

 


## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/fabioaraujo121/rails-treant. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Rails::Treant project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/fabioaraujo121/rails-treant/blob/master/CODE_OF_CONDUCT.md).
