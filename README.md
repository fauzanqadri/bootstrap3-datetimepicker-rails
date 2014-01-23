# Bootstrap v3 datetimepicker plugin for rails

wraps [bootstrap-datetimepicker](https://github.com/Eonasdan/bootstrap-datetimepicker) in a rails

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'bootstrap3-datetimepicker-rails', git: "git@github.com:fauzanqadri/bootstrap3-datetimepicker-rails.git"
gem 'momentjs-rails'
```

why???, because i don't know how to test this properly, so i don't wanna publish this gem before it tested

And then execute:

    $ bundle install

## Usage
You have to require bootstrap-datetimepicker in your application.css after requiring bootstrap

```html
*= require bootstrap-datetimepicker.min
```

and in your application.js after requiring bootstrap

```html
//= require moment
//= require bootstrap-datetimepicker.min
```

see [doc](http://eonasdan.github.io/bootstrap-datetimepicker) and [moment.js](http://momentjs.com/) for more details

## Dependency

* [momentjs-rail](https://github.com/derekprior/momentjs-rails)

## Contributing

1. Fork it ( http://github.com/fauzanqadri/bootstrap3-datetimepicker-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
