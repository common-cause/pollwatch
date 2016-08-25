source "https://rubygems.org"

gem "rails" 
gem 'normalize-rails'
gem 'haml-rails'
gem "uglifier", ">= 1.3.0"
gem "coffee-rails"

gem "turbolinks"
gem "sass-rails"
gem "sprockets"
gem "pg"
gem "devise"
gem 'jquery-rails'
gem "jquery-turbolinks"
gem "react-rails"
gem "bootstrap-sass"
gem "font-awesome-rails"
gem "rack-cors", require: "rack/cors"
gem "kaminari"
gem "active_model_serializers"
gem "newrelic_rpm"
gem "figaro"
gem "pg_search"
gem "ancestry"
gem "friendly_id"
gem "faker"
gem "pundit", github: "elabs/pundit"
gem "rest-client"
gem "seed-fu"
gem "enumerize"
gem "bootstrap_form"
gem "activerecord-postgis-adapter"
gem "geocoder"
gem "i18n-js"
gem "localeapp"
group :production, :staging do
  gem "rails_12factor"
  gem "rack-cache", require: "rack/cache"
  gem "dalli", "~> 2.7.1"
  gem "memcachier"
  gem "kgio"
  gem "rollbar"
  gem "thin"
  gem "rack-timeout"
end

group :test, :development do
  gem "rspec-rails"
  gem "rspec-collection_matchers"
  gem "factory_girl_rails"
  gem "bullet"
  gem "ruby-progressbar"
  gem "pry-rails"
end

group :test do
  gem "database_cleaner", ">= 1.0.0.RC1"
  gem "capybara"
  gem "poltergeist"
  gem "shoulda-matchers", require: false
  gem "rubocop"
end

group :development do
  gem "quiet_assets", ">= 1.0.2"


  gem "binding_of_caller", ">= 0.7.1", platforms: [:mri_19, :rbx]
  gem "spring-commands-rspec"
  gem "listen"
  gem "guard-bundler"
  gem "rack-livereload"
  gem "guard-rspec", require: false, github: "guard/guard-rspec"
  gem "activerecord-import"
  gem "metric_fu", ">= 4.11.0"
  gem "mailcatcher"
  gem "spring"
end
