source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.2.rc1'

# bootstrap
gem 'bootstrap-sass', '2.3.2.0'

# paginate
gem 'will_paginate', '3.0.4'
gem 'bootstrap-will_paginate', '0.0.9'

#самая новомодная хэш функция, называемая bcrypt для необратимого шифрования пароля в виде хэша пароля
gem 'bcrypt-ruby', '>=3.1.2'

#делать образцы пользователей с полу-реалистичными именами и адресами электронной почты
gem 'faker', '1.1.2'

#Всегда используем PostgreSQL
#gem 'pg', '>=0.15.1'

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  #получаем доступ к RSpec-специфичным генераторам и это включает его в test mode где он нужен для запуска тестов
  gem 'rspec-rails', '~> 2.13.1'
  gem 'factory_girl_rails', '~> 4.2.1'
end

group :test do
#включили гем Capybara, который позволит нам симулировать взаимодействие пользователя с нашим примером приложения используя понятный Англоподобный синтаксис, совместно с Selenium, одной из зависимостей Capybara
  gem 'selenium-webdriver', '~> 2.35.1'
  gem 'capybara', '~> 2.1.0'

#cucumber
  gem 'cucumber-rails', '1.4.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'

end

#pg и rails_12factor гемы в production для развертывания на Heroku
group :production do
  gem 'rails_12factor', '0.0.2'
end

#Фиксит предупреждения при запуске тестов
gem 'minitest'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'


# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc
# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

