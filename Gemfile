source 'http://rubygems.org'

gem 'rails', '3.0.0.beta4'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

gem 'haml', '>=3.0.12'
gem 'devise','>= 1.1.rc1'

# Bundle gems for certain environments:
#
# group :production do
#   gem 'mysql'
# end

group :development, :test do
  gem 'sqlite3-ruby', :require => 'sqlite3'
end

group :test do
  gem 'test-unit'  #Cucumber needs it
  gem 'mocha'
  gem 'rspec-rails', '>= 2.0.0.beta.11'
  gem 'capybara',         :git => 'git://github.com/jnicklas/capybara.git'
  gem 'database_cleaner', :git => 'git://github.com/bmabey/database_cleaner.git'
  gem 'cucumber-rails',   :git => 'git://github.com/aslakhellesoy/cucumber-rails.git'
end
