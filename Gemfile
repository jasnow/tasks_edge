source 'https://rubygems.org'

gem 'rails', '5.0.0.beta1'
gem 'capybara', github: 'jnicklas/capybara', branch: 'master'

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
  gem 'launchy'
end
