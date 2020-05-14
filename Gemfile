source "https://rubygems.org"
ruby "2.3.1"

gem "rails", "5.0.0"
gem 'responders', '~> 2.2', '>= 2.2.0'
gem "pg"
gem "figaro"
gem "simple_form", ">= 3.2.1"
gem "rest-client"
gem 'meetup_client'
gem "redis"

# After Rails official release, just keep 'redis-rails'
gem 'redis-rack', github: 'redis-store/redis-rack', branch: 'master'
gem 'redis-actionpack', github: 'redis-store/redis-actionpack', branch: 'master'
gem 'redis-rails', github: 'redis-store/redis-rails', branch: 'master'

gem "jquery-rails", ">= 4.1.1"
gem "sass-rails", "~> 5.0", ">= 5.0.5"
gem "uglifier"
gem "email_validator"
gem "rails-i18n", ">= 4.0.2"
gem 'pygmentize'
gem 'redcarpet'
gem "bootstrap-sass"
gem "font-awesome-sass"
gem "react-rails", "1.6.0"
gem 'react-bootstrap-rails', '>= 0.28.3'
gem "lodash-rails", ">= 4.6.1"
gem 'js-routes', '>= 1.2.5'
gem 'autoprefixer-rails'
gem "jquery-slick-rails", ">= 1.6.0.2"
gem 'money-rails', '>= 1.6.0'
gem 'gibbon'
gem 'ruby-trello'
gem 'raygun4ruby', github: 'ssaunier/raygun4ruby', branch: 'rails-5-deprecation-warnings'
gem 'sitemap_generator'
gem 'builder'
gem 'rack-utf8_sanitizer', '>= 1.3.2'

source "https://rails-assets.org" do
  gem 'rails-assets-mdi'
  gem 'rails-assets-classnames'
  gem 'rails-assets-pubsub-js'
  gem 'rails-assets-devicons'
  gem 'rails-assets-headroom.js'
end

group :development, :test do
  gem "spring"
  gem "letter_opener"

  # After Raisl 5 official release, just keep "rspec-rails"
  gem "rspec-rails", git: "https://github.com/rspec/rspec-rails.git", branch: "master"
  gem "rspec-core", git: "https://github.com/rspec/rspec-core.git", branch: "master"
  gem "rspec-support", git: "https://github.com/rspec/rspec-support.git", branch: "master"
  gem "rspec-expectations", git: "https://github.com/rspec/rspec-expectations.git", branch: "master"
  gem "rspec-mocks", git: "https://github.com/rspec/rspec-mocks.git", branch: "master"
end

group :development do
  gem "pry-byebug"
  gem "pry-rails"
  gem "quiet_assets"
  gem "annotate"
  gem "binding_of_caller"
  gem "better_errors", ">= 2.1.1"
  gem 'rack-mini-profiler', '>= 0.9.9.2'
end

group :test do
  gem "capybara", ">= 2.7.0"
end

group :production do
  gem "rails_12factor"
  gem "puma"
end
