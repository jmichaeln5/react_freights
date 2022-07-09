source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Specify your gem's dependencies in react_freights.gemspec.
gemspec

gem "pg"
gem "puma"
gem "sprockets-rails"

group :development, :test do
  gem "appraisal"
  gem "byebug"
  gem "factory_bot_rails"
end

group :test do
  gem "capybara"
  gem "database_cleaner"
  gem "selenium-webdriver"
  gem "webdrivers"
end
