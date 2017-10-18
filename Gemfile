source 'https://rubygems.org'

gem 'rails', git: 'https://github.com/rails/rails'
gem 'arel', git: 'https://github.com/rails/arel' # 7/26/2017: TEMP'LY ADDED.

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
  gem 'puma'

  gem 'rb-inotify' if /linux/ =~ RUBY_PLATFORM
  gem 'capybara'
  gem 'launchy'
end
