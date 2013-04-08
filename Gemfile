source 'http://rubygems.org'
ruby '1.9.3'

# Use the last stable version of Ruby on Rails...
gem 'rails', '3.2.13'

#--------------
# Dependancies
#--------------
gem 'haml-rails'                                 # Use HAML instead of ERB to generate html files
gem 'jquery-rails'                               # Use jQuery (and not Prototype) as JS framework
gem 'rails-i18n'                                 # Translations for ruby on rails
gem 'http_accept_language'                       # Extract the accepted language from http request
gem 'mongoid', '~> 3.0.0'                        # NoSQL Database (mongodb)
gem 'mongoid_spacial'                            # Geo special extension for mongoid
gem 'gmaps4rails'                                # Google Maps for ruby on rails

# Gems used only in **PRODUCTION** !
group :production do
  gem 'pg'                                       # Database (PostGre sql)
  gem 'thin'                                     # Fast & evented webserver for rails
  gem 'therubyracer'                             # Google V8 javascript engine (embeded)
  gem 'foreman'                                  # Process manager for heroku (cedar stack)
end

# Gems used only for **DEV** !
group :development do
  gem 'sqlite3'                                  # Database (SQLite)
  gem 'heroku'                                   # Tools for hosting on heroku PAAS platform
  gem 'translate-rails3', :require => 'translate'# Add a web interface for easy translations
end

# Gems used only for **CODE TESTS** !
group :test do
  gem 'turn', :require => false                  # Pretty printed test output
end

# [[ Assets rails pipeline ]]
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

