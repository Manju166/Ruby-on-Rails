source "https://rubygems.org"

gem "rails", "~> 7.2.0.beta2"
gem "sprockets-rails"
gem "sqlite3", ">= 1.4"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]

gem "bootsnap", require: false

# my custom gem
gem 'devise', '~> 4.9', '>= 4.9.4'

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  gem "brakeman", require: false

  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
