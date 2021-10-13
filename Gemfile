# source 'https://rubygems.org'
# source 'https://gems.ruby-china.com/'
source 'https://mirrors.tuna.tsinghua.edu.cn/rubygems/'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.4', '>= 6.1.4.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'

# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

# 上传组件
gem 'carrierwave'

# Aliyun / Upyun / Qiniu 可选项
# gem "carrierwave-aliyun"
# gem "carrierwave-upyun"
gem 'carrierwave-qiniu'

# Lazy load
gem 'mini_magick', require: false

# 验证码，头像
gem 'letter_avatar'
# gem "rucaptcha"
gem 'recaptcha'

# 用户系统
gem 'devise'
gem 'devise-encryptable'
# gem 'devise_token_auth', '~> 1.1.4'
gem 'devise_token_auth', github: "lynndylanhurley/devise_token_auth"

# 通知系统
gem 'notifications'
gem 'ruby-push-notifications'

# 分页
gem 'kaminari'

# Permission
gem 'cancancan'

# Redis
gem 'hiredis'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
gem 'redis-namespace'
gem 'redis-objects'


# Cache
gem 'second_level_cache'

# Setting
gem 'rails-settings-cached'

# 队列
gem 'sidekiq'
gem 'sidekiq-scheduler'

# Audited (previously acts_as_audited) is an ORM extension that logs all changes to your models
gem 'audited', '~> 4.9'


# Rails环境中集成微信公众平台、企业微信和小程序
gem 'wechat'


# Sentry gems
gem 'sentry-ruby'
gem 'sentry-rails'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]

  
  # rspec 复杂度较高，使用 minitest 代替
  # gem "capybara"
  # gem "database_cleaner"
  # gem "factory_bot_rails"
  # gem "letter_opener"
  # gem "rspec-rails"
  # RuboCop is a Ruby static code analyzer (a.k.a. linter) and code formatter
  # gem 'rubocop', '~> 1.9', require: false
  gem 'rubocop', require: false

  # gem 'rubocop', '>= 0.49.0', require: false
  #
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'sdoc'
  gem 'codecov', require: false

end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  # gem 'spring-commands-rspec'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'derailed'

  # 部署相关内容
  gem 'capistrano', '~> 3.8.2'
  gem 'capistrano-rvm'
  gem 'capistrano-rails', '~> 1.1'
  gem 'capistrano3-puma'
  gem 'capistrano-yarn', require: false

end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
