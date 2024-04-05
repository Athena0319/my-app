source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.3'

gem 'bcrypt'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'http'
gem 'jbuilder', '~> 2.7'
gem 'puma', '~> 4.1'
gem "nokogiri", ">= 1.15.6"
gem 'rails', '~> 7.0.8', '>= 7.0.8.1'
gem 'sprockets', '>= 3.7.3', '< 4'
gem 'sassc-rails'
gem 'faker'

group :development do
  gem 'htmlbeautifier'
  gem 'listen', '~> 3.2'
  gem 'rufo'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'spring'
  gem 'web-console', '>= 4.2.1'
end

group :development, :test do
  gem 'amazing_print'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'dotenv-rails', '>= 2.8.0'
  gem 'grade_runner', github: 'firstdraft/grade_runner'
  gem 'pry-rails'
  gem 'sqlite3', '~> 1.4.1'
  gem 'table_print'
  gem 'web_git', github: 'firstdraft/web_git'
end

group :development do
  gem 'annotate'
  gem 'better_errors', '2.7.0'
  gem 'binding_of_caller'
  gem 'draft_generators', github: 'firstdraft/draft_generators', branch: 'winter-2020'
  gem 'rails_db', '2.4.0'

end

group :test do
  gem 'capybara', '>= 3.38.0'
  gem 'factory_bot_rails', '>= 6.3.0'
  gem 'rspec-html-matchers', '>= 0.10.0'
  gem 'rspec-rails', '>= 6.0.0'
  gem 'webmock'
end

group :production do
  gem 'pg'
end
