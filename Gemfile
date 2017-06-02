source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7.1'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby
gem 'responders', '~> 2.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'jquery-turbolinks'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
# for reading pdfs
gem 'pdf-reader', '1.4.0'
gem 'afm', '0.2.1'
# for creating pdfs
gem 'pdfkit', '0.5.3'
gem 'wicked_pdf', '0.11.0'

#Create a Development Architect
#Authentication gem
gem 'devise', '~> 3.4.0'
gem 'devise-bootstrapped'

#Bootstrap design
gem 'bootstrap-generators', '~> 3.3.4'

#View template slim
gem 'slim-rails', '~> 3.1', '>= 3.1.1'
gem 'html2slim'

#Continuous integration tool
gem 'travis'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'puma'
  gem 'pry-rails'
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

end

group :production do
  gem "heroku"
  gem "pg"
  gem 'rails_12factor'
  gem 'puma'
end

group :test do
  #Integrational testing framework
  gem 'rspec-rails'
  #It is just like a jerkin language
  gem 'turnip'
  #Trigger a browser
  gem 'selenium-webdriver', '2.53.4'
  #Find element on the page
  gem 'capybara'
  #Fixture Replacement library
  gem "factory_girl_rails"
end
