source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '>= 5.0.0.beta2', '< 5.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# Action Cable dependencies for the Redis adapter
gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'haml-rails'
gem 'devise', github: "plataformatec/devise"
gem 'omniauth-facebook'
#Flexbox rb
gem 'flexbox_rb'
#Annotate
gem 'annotate'
#Best in place for better edit forms
gem "best_in_place", "~> 3.0.1"
#Papercli para subir archivos
gem "paperclip", "~> 5.0.0.beta1"
#Remotipart to upload files via AJAX
gem "remotipart",github:"urielhdz/remotipart"
#AASM para state machines
gem "aasm"
#Activemodel serializers xml to work with draper
gem 'activemodel-serializers-xml', github: 'rails/activemodel-serializers-xml'
#Draper para nuestros decorators
gem "draper",github:"audionerd/draper",branch:"rails5"

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
	gem 'shoulda-matchers' #Metodos de ayuda específicos
  gem 'rspec-rails',"~>  3.5.0.beta1" # Framework pruebas
  gem "factory_girl_rails", "~> 4.0" # Nos permite crear objetos de la BD para pruebas
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 3.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
