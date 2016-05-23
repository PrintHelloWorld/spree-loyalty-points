source 'https://rubygems.org'

gem 'sqlite3'

group :assets do
  gem 'coffee-rails'
  gem 'sass-rails'
end

# Provides basic authentication functionality for testing parts of your engine
gem 'solidus_auth_devise', github: 'solidusio/solidus_auth_devise', branch: 'master'

# Provides basic frontend and backend functionalities for testing purposes
gem 'solidus_backend', '~> 1.0'
gem 'solidus_frontend', '~> 1.0'

group :test do
  gem 'shoulda-matchers'
  gem 'capybara', '~> 2.1'
  gem 'database_cleaner'
  gem 'factory_girl', '~> 4.2'
  gem 'ffaker'
  gem 'rspec-rails',  '~> 2.13'
  gem 'simplecov'
  gem 'selenium-webdriver'
end

gemspec
