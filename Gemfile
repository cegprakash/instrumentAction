source 'https://rubygems.org'
gem 'rails', '3.2.3'
gem 'mongo_mapper'

gem "bson_ext", "~> 1.6.4"
gem "scaffold"
gem "puppet"
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'coffee-script'
end

group :test do
  gem "rspec"
  gem "factory_girl"
  # Pretty printed test output
  gem 'turn', :require => false
end

group :development, :test do
  gem "cucumber-rails", ">= 1.3.0"
  gem 'rspec-rails',      ">= 2.0.0.beta"
  gem 'sqlite3'
end


group :production do
  gem 'thin'
  gem 'pg'
end

gem 'jquery-rails'
gem "haml", ">= 3.1.4"
gem "haml-rails", ">= 0.3.4", :group => :development
gem "email_spec", ">= 1.2.1", :group => :test
gem "capybara", ">= 1.1.2", :group => :test
gem "database_cleaner", ">= 0.7.2", :group => :test
gem "launchy", ">= 2.1.0", :group => :test
gem "devise", ">= 2.1.0.rc"
gem "twitter-bootstrap-rails", ">= 2.0.3", :group => :assets
gem "simple_form"
gem "rest-client"
gem "google_drive"


