source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"
gem "rails", "~> 7.0.4"

gem "sprockets-rails"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

gem "puma", "~> 5.0"

gem "importmap-rails"

gem "turbo-rails"


gem "stimulus-rails"

gem "jbuilder"

gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false


group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end
group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"


end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
