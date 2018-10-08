source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.1'

gem 'rails', '~> 5.2.0' # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
# gem 'sqlite3' # Use sqlite3 as the database for Active Record
gem 'puma', '~> 3.11' # Use Puma as the app server
gem 'sass-rails', '~> 5.0' # Use SCSS for stylesheets
gem 'uglifier', '>= 1.3.0' # Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails', '~> 4.2' # Use CoffeeScript for .coffee assets and views
gem 'turbolinks', '~> 5' # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'jbuilder', '~> 2.5' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'bootsnap', '>= 1.1.0', require: false # Reduces boot times through caching; required in config/boot.rb
gem 'sdoc', '~> 0.4.0', group: :doc

# custom theme requirements
gem 'therubyracer'
gem 'less-rails-bootstrap'
gem 'jquery-easing-rails'
gem "font-awesome-rails"

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw] # Call 'byebug' anywhere in the code to stop execution and get a debugger console
end

group :development do
  gem 'web-console', '>= 3.3.0' # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring' # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15', '< 4.0' # Adds support for Capybara system testing and selenium driver
  gem 'selenium-webdriver'
  gem 'chromedriver-helper' # Easy installation and use of chromedriver to run system tests with Chrome
end