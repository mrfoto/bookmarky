source 'https://rubygems.org'

ruby '2.1.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.4'

# Use postgres as the database for Active Record
gem 'pg'

# Use SCSS for stylesheets
gem 'sass-rails'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# HAML
gem 'haml'
gem 'haml-rails'

# Forms
gem 'simple_form'

# Tags
gem 'acts-as-taggable-on'

# Navigation links
gem 'active_link_to'

# Simple scraper
gem 'metainspector'

# Newrelic
gem 'newrelic_rpm'

group :production do
  gem 'unicorn'
  gem 'rails_12factor'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'quiet_assets'
  gem 'sprockets_better_errors'
end

group :test do
  gem 'webmock'
  gem 'vcr'
  gem 'guard-rspec'
  gem 'terminal-notifier-guard'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  # App preloading
  gem 'spring-commands-rspec'
  # Pry stuff
  gem 'pry'
  gem 'pry-coolline'
  gem 'pry-stack_explorer'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'awesome_print'
  gem 'hirb'
end
