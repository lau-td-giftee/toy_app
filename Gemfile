source "https://rubygems.org"

ruby "3.1.2"

gem "rails", "~> 7.1.0"
gem "sassc-rails",     "2.1.2"
gem "sprockets-rails"
gem "importmap-rails", "1.1.0"
gem "turbo-rails",     "1.1.1"
gem "stimulus-rails",  "1.0.4"
gem "jbuilder",        "2.11.5"
gem "puma", ">= 5.0"
gem "sqlite3", "~> 1.4"




gem "tzinfo-data", platforms: %i[ mswin mswin64 mingw x64_mingw jruby ]

gem "bootsnap", require: false


group :development, :test do
  gem "debug", platforms: %i[ mri mswin mswin64 mingw x64_mingw ]
end

group :development do
  gem "web-console"



  gem "error_highlight", ">= 0.4.0", platforms: [:ruby]
end

group :test do
  gem "capybara",           "3.37.1"
  gem "selenium-webdriver", "4.2.0"
  gem "webdrivers",         "5.0.0"
end

group :production do
  gem "pg"
end