source 'https://rubygems.org'

gemspec

group :tools do
  gem 'hotch'
  gem 'pry-byebug', platform: :mri
end

group :test do
  gem "rack", ">= 2.0.6"

  gem "erbse"
  gem "cells-erb", git: "https://github.com/trailblazer/cells-erb", branch: "master"
  gem "erubi"
  gem "hamlit"
  gem "hamlit-block"
  gem 'slim', "~> 4.0"

  gem 'simplecov'
  gem 'codeclimate-test-reporter'
end

group :benchmarks do
  gem 'benchmark-ips'
  gem 'actionview'
  gem 'actionpack'
end
