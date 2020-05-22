source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails', '~> 6.0.1'
gem 'bcrypt', '3.1.13'
gem 'bootstrap-sass', '3.4.1'
gem 'faker', '1.7.3'
gem 'carrierwave'
gem 'mini_magick'
gem 'will_paginate',           '3.2.1'
gem 'bootstrap-will_paginate', '1.0.0'
gem 'puma', '~> 4.3.5'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 4.0'
gem 'turbolinks', '~> 5'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.7'
# gem 'redis', '~> 4.0'
# gem 'image_processing', '~> 1.2'
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'sqlite3'    #gem to use in development environment
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end

group :production do
  gem 'pg'         #gem to use in production environment
  gem 'fog'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
  gem 'guard'
  gem 'guard-minitest'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
gem "rails-controller-testing"