source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.2', '>= 6.0.2.2'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.3'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'

#Devise for user authentictaion
gem 'devise'
gem 'omniauth'
gem 'omniauth-google-oauth2'
gem 'omniauth-facebook'


# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# Backend
gem 'friendly_id', '~> 5.2.4'
gem 'raygun4ruby'
gem 'rack-canonical-host'
gem 'sitemap_generator'
gem 'sidekiq'
gem 'strong_migrations'
gem 'valid_email2'
gem 'pundit'
gem 'paper_trail'
gem 'strong_password'
gem 'acts_as_paranoid'

gem 'activeadmin'
gem 'activeadmin_addons'
gem 'pretender'


# Frontend
gem 'haml-rails', '~> 2.0'
gem 'high_voltage', '~> 3.1'
gem 'simple_form'
gem 'kaminari'
gem 'bootstrap4-kaminari-views'
gem 'meta-tags'


group :production do
  gem 'rack-timeout'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]

  gem 'rspec-rails', '~> 4.0.0'
  gem 'faker'
  gem 'shoulda-matchers'
  gem 'factory_bot_rails'
  gem 'capybara'

  gem 'bullet'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'awesome_print'

  gem 'annotate'
  gem 'letter_opener'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
