source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# --- defaults gems --- #
gem 'rails', '~> 5.2.0'
gem 'mysql2', '>= 0.4.4', '< 0.6.0'
gem 'puma', '~> 3.11'
gem 'uglifier', '>= 1.3.0'
gem 'turbolinks', '~> 5'
gem 'sass-rails', '~> 5.0'
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'redis', '~> 4.0'
gem 'bcrypt', '~> 3.1.7'
gem 'capistrano-rails', group: :development
gem 'bootsnap', '>= 1.1.0', require: false

# --- self add gems --- #
# jquery
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'
# awesome font
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.4'
# sass bootstrap
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'pry-doc'
end

group :test do
  gem 'capybara', '>= 2.15', '< 4.0'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
