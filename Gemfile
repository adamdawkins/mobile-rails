source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.0"

# Full-stack web application framework. (https://rubyonrails.org)
gem "rails", "~> 6.1.3", ">= 6.1.3.2"
# Pg is the Ruby interface to the {PostgreSQL RDBMS}[http://www.postgresql.org/] (https://github.com/ged/ruby-pg)
gem "pg", "~> 1.1"
# Puma is a simple, fast, threaded, and highly concurrent HTTP 1.1 server for Ruby/Rack applications (https://puma.io)
gem "puma", "~> 5.0"
# Sass adapter for the Rails asset pipeline. (https://github.com/rails/sass-rails)
gem "sass-rails", ">= 6"
# Use webpack to manage app-like JavaScript modules in Rails (https://github.com/rails/webpacker)
gem "webpacker", "~> 5.0"
# Turbolinks makes navigating your web application faster (https://github.com/turbolinks/turbolinks)
gem "turbolinks", "~> 5"
# Create JSON structures via a Builder-style DSL (https://github.com/rails/jbuilder)
gem "jbuilder", "~> 2.7"

# Boot large ruby/rails apps faster (https://github.com/Shopify/bootsnap)
gem "bootsnap", ">= 1.4.4", require: false

group :development, :test do
  # Ruby fast debugger - base + CLI (https://github.com/deivid-rodriguez/byebug)
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Add comments to your Gemfile with each dependency's description. (https://github.com/ivantsepp/annotate_gem)
  gem "annotate_gem"
  # Alias for the standard gem, which has a standardrb binary (https://github.com/testdouble/standardrb)
  gem "standardrb"
  # A debugging tool for your Ruby on Rails applications. (https://github.com/rails/web-console)
  gem "web-console", ">= 4.1.0"
  # Profiles loading speed for rack applications. (https://miniprofiler.com)
  gem "rack-mini-profiler", "~> 2.0"
  # Listen to file modifications (https://github.com/guard/listen)
  gem "listen", "~> 3.3"
  # Rails application preloader (https://github.com/rails/spring)
  gem "spring"
end

group :test do
  # Capybara aims to simplify the process of integration testing Rack applications, such as Rails, Sinatra or Merb (https://github.com/teamcapybara/capybara)
  gem "capybara", ">= 3.26"
  # The next generation developer focused tool for automated testing of webapps (https://github.com/SeleniumHQ/selenium)
  gem "selenium-webdriver"
  # Easy download and use of browser drivers. (https://github.com/titusfortner/webdrivers)
  gem "webdrivers"
end

# Timezone Data for TZInfo (https://tzinfo.github.io)
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
