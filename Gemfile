source 'https://rubygems.org'

ruby '2.6.2'

gem 'rails', '~> 5.2'

# Core and middleware
gem 'bootsnap'
gem 'daemons'
gem 'delayed_job_active_record'
# Forked so we could hide PHI from the interface.
gem 'delayed_job_web', git: "https://github.com/shifthealthparadigms/delayed_job_web", branch: :hide_handler_arguements
gem 'http'
gem 'json'
gem 'json-schema'
gem 'jsonpath'
gem 'pg'
gem 'rack'
gem 'rack-attack'
gem 'rack-cors'
gem 'whenever'

# App layer
gem 'active_model_serializers'
gem 'authlogic'
gem 'aws-sdk-sns'
gem 'aws-sdk-sqs'
gem 'colorize'
gem 'countries'
gem 'default_value_for'
gem 'draper'
gem 'filterrific'
gem 'geocoder'
gem 'hashie'
gem 'hiredis'
gem 'icalendar'
gem 'jsonb_accessor'
gem 'jwt'
gem 'kaminari'
gem 'language_list'
gem 'nokogiri'
gem 'premailer-rails'
gem 'redis'
gem 'rswag-api'
gem 'rswag-ui'
gem 'ruby-saml'
gem 'sanitize'
gem 'scrypt'
gem 'will_paginate'
gem 'zoom_rb'

# View layer
gem 'cocoon'
gem 'compass'
gem 'compass-blueprint'
gem 'compass-rails', ">= 3.1.0"
gem 'demoji'
gem 'font-awesome-rails'
gem 'formtastic'
gem 'haml'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'js_cookie_rails'
gem 'sass-rails'
gem 'select2-rails'
gem 'selectivizr-rails'
gem 'uglifier'
gem 'yui-compressor'
gem 'zeroclipboard-rails'

# Deployment and logging
gem 'appsignal'
gem 'awesome_print'
gem 'lograge'
gem 'puma'
gem 'remote_syslog_logger'
gem 'slack-notifier'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'letter_opener'
  gem 'parallel_tests'
  gem 'pry-byebug'
  gem 'rb-fsevent'
  gem 'rspec-rails'
  gem 'rspec_junit_formatter', require: false
  gem 'rswag-specs'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'brakeman'
  gem 'bullet'
  gem 'guard-rspec', require: false
  gem 'listen'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails'
  gem 'rubocop-rspec'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'web-console'
end

group :test do
  gem 'capybara'
  gem 'capybara-json'
  gem 'capybara-screenshot'
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'method_source'
  gem 'mocha'
  gem 'poltergeist'
  gem 'rails-controller-testing'
  gem 'simplecov', '~> 0.17.1', require: false #Downgraded due to https://github.com/codeclimate/test-reporter/issues/413
  gem 'timecop'
  gem 'webmock'
  gem 'whenever-test'
end
