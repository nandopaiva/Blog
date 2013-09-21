source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

gem 'will_paginate'     # paginação
gem 'devise'            # autenticação
gem 'redcarpet'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'capybara'
  gem "database_cleaner"
  gem 'factory_girl_rails'
  gem 'simplecov'
end

group :production do
  gem 'pg'
  gem 'rufus-scheduler'
end

gem 'sendgrid'

###
# Server
###
# Use unicorn as the app server
gem 'unicorn',                '4.6.2'
gem 'unicorn-worker-killer',  '0.4.1'
gem 'rack-canonical-host',    '0.0.8'
gem "rack-timeout"