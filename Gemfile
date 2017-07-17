source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = '#{repo_name}/#{repo_name}' unless repo_name.include?('/')
  'https://github.com/#{repo_name}.git'
end

gem 'bcrypt', '3.1.11'
gem 'bootstrap-sass', '3.3.7'
gem 'carrierwave', '~> 1.1.0'
gem 'coffee-rails', '~> 4.2'
gem 'i18n-js'
gem 'sqlite3'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'mini_magick', '~> 4.7.0'
gem 'puma', '~> 3.0'
gem 'rails', '~> 5.0.4'
gem 'sass-rails', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'autoprefixer-rails'
  gem 'better_errors'
  gem 'brakeman', require: false
  gem 'bundler-audit'
  gem 'byebug', platform: :mri
  gem 'database_cleaner'
  gem 'eslint-rails', git: 'https://github.com/octoberstorm/eslint-rails', require: false
  gem 'factory_girl_rails'
  gem 'guard-rspec', require: false
  gem 'jshint'
  gem 'railroady'
  gem 'rails_best_practices'
  gem 'reek'
  gem 'rspec'
  gem 'rspec-collection_matchers'
  gem 'rspec-rails'
  gem 'rubocop', '~> 0.35.0', require: false
  gem 'rubocop-checkstyle_formatter', require: false
  gem 'scss_lint', require: false
  gem 'scss_lint_reporter_checkstyle', require: false
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :production do
  gem 'rails_12factor', '0.0.2'
  gem 'pg', '0.18.4'
end
