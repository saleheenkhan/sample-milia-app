source 'https://rubygems.org'
ruby "2.0.0"   # heroku likes this at the head, as line 2

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.3'

# Use sqlite3 as the dev/test database for Active Record
gem 'sqlite3', :group => [:development, :test]

# Use pg as the production database for heroku
gem 'pg', :group => :production

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

  # =========================================================
  # sample-milia-app specific stuff
  # =========================================================
  # Bundle the extra gems:

  gem 'haml-rails'   
  gem 'html2haml', :git => 'git://github.com/haml/html2haml.git'  # "2.0.0.beta.2", 

  # stuff that heroku likes to have
  gem 'thin'
  gem "SystemTimer", :require => "system_timer", :platforms => :ruby_18
  gem "rack-timeout"
  gem 'rails_12factor'

  gem 'web-app-theme', :git => 'git://github.com/dsaronin/web-app-theme.git'
  gem 'devise', '~>3.2'
  gem 'milia', :git => 'git://github.com/dsaronin/milia.git', :branch => 'v1.0.1'

  # airbrake is optional and configured by config.use_airbrake in milia initializer
  # default is false; if you change it to true, uncomment out the line below
  # gem 'airbrake'   # uncomment this if you will use airbrake for exception notifications

  # recaptcha is optional and configured by config.use_recaptcha in milia initializer
  # default is true; if you change it to false, comment out the line below
  # gem 'recaptcha', :require => "recaptcha/rails"


gem "recaptcha", require: "recaptcha/rails"
gem "activerecord-session_store", github: "rails/activerecord-session_store"
