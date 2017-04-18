# RailsHealthChecker

A simple gem which adds endpoints to be used by monitoring apps like Nagios, Pingdom, NewRelic etc.

# Usage

In Gemfile:

```ruby
  gem 'rails_health_checker'
```

In /config/routes.rb

```ruby
  mount RailsHealthChecker::Engine, at: "/health_checker"
```

it will add `/health_checker/health` route to your app which responds with "OK"

# Contributing

## Tests

Run tests with `rspec`.
