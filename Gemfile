source 'https://rubygems.org'

gem 'rails', github: 'rails/rails'

gem 'sqlite3'
gem 'sass'
gem 'coffee-script'
gem 'uglifier'
gem 'jquery-rails'
gem 'overcommit'

group :development do
  gem 'dawnscanner', require: false
end

group :test, :development do
  gem 'rspec-rails', '3.5.0.beta2' # RAILS 5

  gem 'rb-inotify' if /linux/ =~ RUBY_PLATFORM
  gem 'capybara'
  gem 'launchy'
end
