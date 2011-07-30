source 'http://rubygems.org'

gem 'rails', '= 3.1.0.rc5'

gem 'clearance', '~> 0.12.0'
gem 'fog'
gem 'gchartrb', :require => 'google_chart'
gem 'gravtastic'
gem 'high_voltage'
gem 'hoptoad_notifier'
gem 'mail'
gem 'newrelic_rpm'
gem 'paul_revere', :git => 'git@github.com:cmeiklejohn/paul_revere.git', :branch => 'fix_tests_to_run_in_1_9_and_ree_1_8'
gem 'pg'
gem 'rack'
gem 'rack-maintenance', :require => 'rack/maintenance'
gem 'rdoc'
gem 'redis'
gem 'rest-client', :require => 'rest_client'
gem 'sinatra'
gem 'will_paginate', '~> 3.0.pre2'
gem 'xml-simple'
gem 'yajl-ruby', :require => 'yajl/json_gem'

gem 'json'
gem 'sass'
gem 'coffee-script'
gem 'uglifier'
gem 'jquery-rails'
gem 'execjs'
gem 'therubyracer'

platforms :ruby_18 do
  gem 'system_timer'
  group :test do
    gem 'redgreen'
  end
end

platforms :jruby do
  gem 'jruby-openssl'
end

# These gems suck and do stupid things when in maintenance mode
group :development, :test, :staging, :production do
  gem 'delayed_job'
  gem 'validates_url_format_of'
end

group :development, :test do
  gem 'silent-postgres'
end

group :test do
  gem 'cucumber-rails'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'launchy'
  gem 'nokogiri'
  gem 'rack-test', :require => 'rack/test'
  gem 'rr'
  gem 'shoulda'
  gem 'timecop'
  gem 'webmock'
end
