source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.3.8'

# Rails: Latest stable version for compatibility with Ruby 3.3
gem 'rails', '~> 7.0.6'

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem 'sprockets-rails', '~> 4.0'

# Use PostgreSQL as the database for Active Record
gem 'pg', '~> 1.4'

gem 'devise', '~> 4.8'  # Devise version supporting Rails 7.x

# Use Puma as the web server [https://github.com/puma/puma]
gem 'puma', '~> 6.1'  # Latest stable version

# Use JavaScript with ESM import maps
gem 'importmap-rails', '~> 1.0'

# Hotwire's SPA-like page accelerator
gem 'turbo-rails', '~> 1.0'

# Hotwire's modest JavaScript framework
gem 'stimulus-rails', '~> 1.0'

# JSON APIs with ease [https://github.com/rails/jbuilder]
gem 'jbuilder', '~> 2.0'

# Authorization gem for controlling user access
gem 'cancancan', '~> 3.0'  # Latest stable version

# Optional: Redis adapter to run Action Cable in production
# gem "redis", "~> 4.0"

# Optional: Kredis for higher-level data types in Redis
# gem "kredis"

# Use Active Model has_secure_password (for handling passwords securely)
# gem "bcrypt", "~> 3.1.7"

# Windows compatibility for tzinfo-data
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false, '~> 1.7'

# Font Awesome for icons
gem 'font-awesome-sass', '~> 5.15'

# Optional: Sass for CSS processing (comment out if not used)
# gem "sassc-rails", "~> 2.0"

# Active Storage image transformations (comment out if not needed)
# gem "image_processing", "~> 1.2"

group :development, :test do
  # Debugging gem
  gem 'database_cleaner', '~> 2.0'

  # Debugging gem for development
  gem 'debug', platforms: %i[mri mingw x64_mingw]

  # Testing: RSpec for Rails
  gem 'rspec-rails', '~> 5.0'

  # Optional: Controller testing for RSpec
  # gem 'rails-controller-testing', '~> 1.0'
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem 'web-console', '~> 4.2'

  # Speed up commands on slow machines / big apps
  # gem "spring", "~> 3.1"
end

group :test do
  # System testing
  gem 'capybara', '~> 3.36'

  # Selenium WebDriver for browser automation
  gem 'selenium-webdriver', '~> 4.0'

  # Webdrivers for managing browser drivers
  gem 'webdrivers', '~> 5.0'
end
