source 'https://rubygems.org'

gem 'rails', github: 'rails/rails'
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
  # Rails 5
  gem 'rspec-rails'       , github: 'rspec/rspec-rails'
  gem 'rspec-core'        , github: 'rspec/rspec-core'
  gem 'rspec-expectations', github: 'rspec/rspec-expectations'
  gem 'rspec-mocks'       , github: 'rspec/rspec-mocks'
  gem 'rspec-support'     , github: 'rspec/rspec-support'

  gem 'rb-inotify' if /linux/ =~ RUBY_PLATFORM
  gem 'launchy'
end
