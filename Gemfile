source "https://rubygems.org"

ruby '2.5.1'

gem 'sinatra', require: 'sinatra/base'
gem 'puma'
gem 'rake'
gem 'bundler'
gem 'activesupport'
gem 'rack'
gem 'faraday'
gem 'redis'

group :test, :development do
  gem 'pry'
  gem 'rack-test'
  gem 'rspec'
  gem 'dotenv'
  gem 'simplecov'
end

group :test do
  gem 'webmock'
  gem 'vcr'
end
