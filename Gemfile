source 'https://rubygems.org'
# source 'http://ruby.taobao.org'

gem 'rails', '~> 3.2.8'

# Site map
# gem 'sitemap' # seems not suitable chinese site

# User
gem 'devise'
gem 'devise-async'
gem 'devise-encryptable'
gem 'omniauth'
gem 'omniauth-weibo-oauth2'
gem 'omniauth-xiaonei'
gem 'omniauth-douban-oauth2'
gem 'omniauth-tqq-oauth2'
gem 'weibo_2', :git => 'https://github.com/jonnyzheng/weibo_2.git' # weibo api
gem 'renren', :git => 'https://github.com/jasl/renren.git' # renren api
gem 'cancan' # access control

# Acts as something
gem 'acts-as-messageable'
gem 'acts-as-taggable-on'
gem 'acts_as_commentable'

# Attachments
gem 'carrierwave'
# gem 'mini_magick' # when using upyun, this is no need
gem 'carrierwave-upyun'
gem "rest-client" # for up yun

# UI
gem 'jquery-rails'
gem "social-share-button"
# gem 'cells'

# Pagination
gem 'kaminari'

# Base administrator's frontend
# gem 'rails_admin'

# Application server
gem 'unicorn'

# Memcached
gem 'dalli'

# Deploy
gem 'capistrano'
gem 'rvm-capistrano'
gem 'sushi'
gem 'capistrano_colors'
gem 'foreman' # very cool... but... fuk upstart cannot use on production

# Task queue
gem 'resque'
gem 'resque_mailer'
gem 'resque-cleaner'
gem 'resque-scheduler'
# gem 'resque-status' # can show progress

# WYSIWYG editor
# gem 'rails_kindeditor' # attachments part not suit for real world

# Misc
gem 'settingslogic'
gem 'rails-i18n'
gem 'turbo-sprockets-rails3'

group :production do
  gem 'mysql2'

  # Server monitoring service. see http://www.newrelic.com about sign up and configuration
  # gem 'newrelic_rpm'
  # Exception reporting service, see more on http://www.airbrake.io
  # gem 'airbrake'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>= 1.0.3'

  # UI
  gem 'bootstrap-sass'
  gem 'compass-rails'
  gem 'jquery-ui-rails'
end

group :development, :test do
  # Generate table definations
  gem 'annotate'

  # Debugger
  gem "pry"
  gem 'pry-rails'

  # Disabled assets log
  gem 'quiet_assets'

  # Using thin in devlopment
  gem 'thin'

  gem 'sqlite3'
end

group :development, :test do
  gem "letter_opener" # send mail to broswer, not really send

  gem "rspec-rails"
  gem "capybara"
  gem "awesome_print"
  gem "database_cleaner"
  gem "launchy"
  gem 'factory_girl'
end

group :test do
  gem 'cucumber-rails', :require => false
  gem "turn", :require => false
  gem "simplecov", :require => false
  gem "shoulda-matchers"
  gem 'email_spec'
  gem 'resque_spec'
  gem "webmock"
end