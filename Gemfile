source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.5.1"

gem "devise"
gem "pg", ">= 0.18", "< 2.0"
gem "puma", "~> 3.11"
gem "pundit"
gem "rails", "~> 5.2.0"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"

gem "bootsnap", ">= 1.1.0", require: false
gem "coffee-rails", "~> 4.2"
gem "jbuilder", "~> 2.5"
gem "turbolinks", "~> 5"

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

group :development, :test do
  gem "pry-byebug"
  gem "rspec-rails", "~> 3.7"
  gem "rspec_junit_formatter"
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15", "< 4.0"
  gem "chromedriver-helper"
  gem "codecov", require: false
  gem "factory_bot_rails"
  gem "launchy"
  gem "selenium-webdriver"
  gem "simplecov", require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
