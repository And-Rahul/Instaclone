source "https://rubygems.org"

ruby "3.2.2"
gem "rails", "~> 7.1.1"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "ransack"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false
#my custom gems
gem 'devise', '~> 4.9', '>= 4.9.3'
gem 'followability', github: 'nejdetkadir/followability', branch: 'main'
gem 'rails_admin'
group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
