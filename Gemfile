source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.8'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.4', '>= 5.2.4.5'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Inicio de gemas personalizadas

# Autenticacion a los usuarios
gem 'devise', '~> 4.7', '>= 4.7.3'
gem 'devise-i18n', '~> 1.9', '>= 1.9.2'
gem 'devise-security', '~> 0.15.0'

# Roles
gem "rolify"

# Permisos
gem "pundit"

# Select2
gem 'select2-rails', '~> 4.0', '>= 4.0.13'

# Gema de estilos
gem 'bootstrap', '~> 4.5.0'

# Gema de iconos
gem 'font_awesome5_rails'

# Gema de formularios
gem 'simple_form'

# Jquery
gem 'jquery-rails', '~> 4.4'

# mensajes Flash Toastr
gem 'toastr-rails', '~> 1.0', '>= 1.0.3'

# URL amigables
gem 'friendly_id', '~> 5.4', '>= 5.4.2'

# Procesos en 2do plano
gem 'delayed_job_active_record', '~> 4.1', '>= 4.1.5'

# Gema de excel
gem 'caxlsx_rails', '~> 0.6.2'

# Fin de gemas personalizadas

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Metodos de ayudas para rails
  gem 'shoulda-matchers', '~> 4.5', '>= 4.5.1'
  # Crear objestos para la DB
  gem 'factory_bot_rails', '~> 6.1'
  gem 'rspec-rails', '~> 5.0'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # Documentar los modelos
  gem 'annotate', '~> 3.1', '>= 3.1.1'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
