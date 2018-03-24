source 'https://rubygems.org'

gem 'rails', git: 'https://github.com/rails/rails'
gem 'arel'

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
  gem 'rspec-rails'
  gem 'rb-inotify' if /linux/ =~ RUBY_PLATFORM
  gem 'capybara', '3.0.0.rc2'
  gem 'launchy'
end
