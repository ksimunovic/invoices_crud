# frozen_string_literal: true

source 'https://rubygems.org'

ruby '3.3.5' # Specify a compatible Ruby version

gem 'acts_as_paranoid'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false
gem 'faker' # To setup data on Heroku
gem 'hotwire-rails'
gem 'importmap-rails'
gem 'ostruct'
gem 'pg'
gem 'propshaft'
gem 'puma', '>= 5.0'
gem 'rails', '~> 7.2.2'
gem 'stimulus-rails'
gem 'turbo-rails'

group :development do
  gem 'standard'
  gem 'standard-rails'

  gem 'rubocop'
  gem 'rubocop-rails'
  gem 'rubocop-rspec'
  gem 'rubocop-rspec_rails'
end

group :development, :test do
  gem 'brakeman'
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'debug', platforms: %i[mri windows], require: 'debug/prelude'
  gem 'dotenv-rails'
  gem 'rails-controller-testing'
  gem 'rspec-rails'
end
