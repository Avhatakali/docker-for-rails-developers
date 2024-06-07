# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# ==== Core
ruby '3.2.2'

gem 'puma', '~> 6.4'
gem 'rails', '~> 7.1.3', '>= 7.1.3.3'

gem 'execjs'
gem 'therubyracer'

# ==== Database 
gem 'sqlite3', '~> 1.4'
# gem 'pg', '~> 1.2'
# gem 'pg_search'
# gem 'redis'

# ==== General
gem 'action_policy'
gem 'bootsnap', require: false
gem 'browser'
gem 'faker'
gem 'possessive'
gem 'rack-cors', require: 'rack/cors'
gem 'sprockets'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Utility
gem 'json-jwt'
gem 'nokogiri'
gem 'rexml'

# ==== ActionMailer
gem 'inky-rb', require: 'inky'

# ==== ActionView
gem 'active_link_to'
gem 'breadcrumbs_on_rails'
gem 'client_side_validations'
gem 'client_side_validations-simple_form'
gem 'meta-tags'
gem 'simple_form'
gem 'slim-rails'
gem 'view_component'

# ==== ActiveModel and ActiveRecord
gem 'active_model_serializers'
gem 'pagy'

# ==== ActiveJob
gem 'sidekiq'

# ==== ActiveStorage
gem 'image_processing'

# ------------------------------------------------------------------------------

# ==== Assets
gem 'premailer-rails'
gem 'propshaft'

# ==== Javascript
gem 'hotwire-rails'
gem 'i18n-js'
gem 'importmap-rails'
gem 'jsbundling-rails'
gem 'stimulus-rails'
gem 'turbo-rails'

# ==== Stylesheets
gem 'autoprefixer-rails'
gem 'cssbundling-rails'
gem 'tailwindcss-rails'

# ------------------------------------------------------------------------------

# ==== CSV related
gem 'csv'

# ==== Debugging
gem 'amazing_print', require: 'ap' # AmazingPrint is a fork of AwesomePrint which became stale.
gem 'pry-rails'

# ==== Profiling
gem 'rack-mini-profiler'

# ------------------------------------------------------------------------------

# ==== Rails groups

group :development, :test do
  gem 'brakeman'
  gem 'factory_bot_rails'
  gem 'letter_opener'
  gem 'rails-erd'
  gem 'rspec-rails'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
  gem 'shoulda-matchers'
  gem 'slim_lint'
end

group :development do
  gem 'i18n-tasks'
  gem 'listen'
  gem 'web-console'
end

group :test do
  gem 'climate_control'
  gem 'database_cleaner-active_record'
  gem 'rails-controller-testing'
  gem 'rspec-github', require: false
  gem 'rspec-html-matchers'
  gem 'simplecov', require: false
  gem 'single_cov', require: false
  gem 'vcr'
  gem 'webmock'
end

group :tools do
  gem 'ruby-lsp', require: false
  gem 'squasher', '>= 0.6.0'
end
