source "https://rubygems.org"

ruby "2.1.0"

gem "airbrake"
gem "bourbon"
gem "coffee-rails"
gem "delayed_job_active_record", ">= 4.0.0"
gem "email_validator"
gem "flutie"
gem "high_voltage"
gem "jquery-rails"
gem "neat"
gem "bitters"
gem "pg"
gem "rack-timeout"
gem "rails", ">= 4.0.0"
gem "recipient_interceptor"
gem "sass-rails"
gem "simple_form"
gem "title"
gem "uglifier"
gem "unicorn"
gem "devise", "~> 3.2.3"
gem "apartment", "~> 0.24.2"
gem "pikaday-gem", "~> 1.1.0.0"
gem "momentjs-rails"
gem "gravatar_image_tag"
gem "hashtel", "~> 0.0.1"

group :development do
  gem "better_errors"
  gem "binding_of_caller"
  gem "foreman"
  gem "spring"
  gem "spring-commands-rspec"
end

group :development, :test do
  gem "dotenv-rails"
  gem "factory_girl_rails"
  gem "pry-rails"
  gem "rspec-rails", ">= 2.14"
  gem "annotate"
end

group :test do
  gem "capybara-webkit", ">= 1.0.0"
  gem "database_cleaner"
  gem "launchy"
  gem "shoulda-matchers"
  gem "simplecov", require: false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "newrelic_rpm", ">= 3.6.7"
end
