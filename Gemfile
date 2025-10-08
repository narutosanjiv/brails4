source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.5'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 2.5.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.1.1'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 4.0.1'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
#gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

gem 'simple_form', '>= 3.2.1'
gem 'mongoid', git: 'git://github.com/mongoid/mongoid.git'
gem 'devise', '>= 4.0.0'
gem 'devise_invitable', '>= 1.6.0'
gem 'cancancan', '~> 1.7'
gem 'coveralls', require: false
gem "mongoid-paperclip", :require => "mongoid_paperclip"
gem "haml", ">= 3.0.0"
gem "haml-rails", ">= 0.5.3"
gem "nested_form"
gem "erb2haml", :group => :development
gem 'mongoid_slug', '3.2.0'
gem 'country_select'


group :development, :test do
  gem 'mongoid-rspec'
  gem "rspec-rails", ">= 2.14.1"
  gem "factory_girl_rails", "~> 4.3", ">= 4.3.0"
  gem 'faker'
  gem 'capybara', '>= 2.2.0'
  gem 'rails_layout'
  gem 'mina'
end

group :test do
  gem 'database_cleaner'
  gem 'simplecov', :require => false
  gem 'shoulda-matchers'
end


group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
#gem 'debugger', group: [:development, :test]
