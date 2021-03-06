source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'
# Use ActiveModel has_secure_password
gem 'bcrypt','3.1.11'
# Use Puma as the app server
gem 'puma', '~> 3.8.2'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'sprockets-rails', '~> 3.2'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem 'listen',                '3.0.8'
  gem 'spring',                '1.7.2'
  gem 'spring-watcher-listen', '2.0.0'
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'

  gem 'tzinfo-data' if Gem.win_platform?
  gem 'wdm', '>= 0.1.0' if Gem.win_platform?
  gem 'win32console', '~> 1.3', '>= 1.3.2' if Gem.win_platform?
  gem 'coffee-script-source', '1.8.0' if Gem.win_platform?
end

group :development do
  gem 'web-console', '>= 3.1.1'
  gem 'capistrano', '~> 3.10'
  gem 'capistrano-rails', '~> 1.3'
  gem 'capistrano3-puma', '~> 3.1', '>= 3.1.1'
  gem 'capistrano-rbenv', '~> 2.1', '>= 2.1.2'
  gem 'capistrano-nginx', '~> 1.0'
  gem 'capistrano-rails-db', '~> 0.0.2'
  gem 'capistrano-rails-console', '~> 2.2', '>= 2.2.1'
  gem 'sshkit-sudo'
end

group :test do
  gem 'rails-controller-testing', '0.1.1'
  gem 'minitest-reporters',       '1.1.9'
  gem 'guard',                    '2.13.0'
  gem 'guard-minitest',           '2.4.4'
end

group :production do
  gem 'pg'
end
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
