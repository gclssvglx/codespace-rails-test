source "https://rubygems.org"

ruby "3.2.2"

gem "rails", "~> 7.1.2"
gem "sprockets-rails"
gem "puma"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false

group :production do
  gem "pg"
  gem "redis"
end

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  gem "web-console"
end

group :test do
  gem "sqlite3"
  gem "capybara"
  gem "selenium-webdriver"
end
