# frozen_string_literal: true

source 'https://rubygems.org'

platform :ruby do
  ruby File.read('.ruby-version')[/\d+(?:\.\d+)+/]
end

# Specify your gem's dependencies in locomotivecms_common.gemspec
gemspec

group :development do
  gem 'rubocop', '>= 1.75', require: false
end

group :test do
  gem 'coveralls', '~> 0.8.21', require: false
  gem 'rspec', '~> 3.13'
end
