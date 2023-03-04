source "https://rubygems.org"

gem "rails", git: "https://github.com/rails/rails", branch: "main"

gem "sqlite3"
gem "sassc-rails"
gem "uglifier"
gem "jquery-rails"
gem "overcommit"
gem "ruby_audit"

group :development do
  gem "dawnscanner", require: false
end

group :test, :development do
  gem "rspec-rails"
  gem "rb-inotify" if /linux/.match?(RUBY_PLATFORM)
  gem "capybara"
  gem "launchy"
  gem 'simplecov'
  gem "standard"
  gem "spektr"
end
