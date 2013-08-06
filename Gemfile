source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# use sql3 only as local
group :development, :test do
  gem 'sqlite3'
  # gem 'rspec-rails', '2.13.1'
  gem 'rspec-rails'
end

# and pg for heroku
group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end

# RSpec library
group :test do
  # gem 'selenium-webdriver', '2.0.0'
  gem 'selenium-webdriver'
  # gem 'capybara', '2.1.0'
  gem 'capybara'
end

gem 'sass-rails',   '~> 3.2.3'
gem 'coffee-rails', '~> 3.2.1'
gem 'uglifier', '>= 1.0.3'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

gem 'jquery-rails'