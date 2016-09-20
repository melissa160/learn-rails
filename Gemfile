source 'https://rubygems.org'
ruby '2.3.1'

#Rails Defaults
gem 'rails', '4.2.5'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'#comprimir codigo javascript
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'#crear app single page app sin necesidad de usar algun framework como angular o react
gem 'jbuilder', '~> 2.0'#crear respuestas json para generar apis
group :development, :test do
	gem 'byebug'#hacer debuggin detener el fluo de la aplicacion
  gem 'web-console', '~> 2.0'#se abre una consola cuando entramos a una excepcion en ruby
	gem 'spring'#el servidor se apaga y enciende por default tras los cambios
end

#learn-rails
gem 'foundation-rails', '~> 5.5'
gem 'gibbon'#gema para la Mailchimp API
gem 'high_voltage'#gema para crear paginas con contenido estatico que no esten en public. trae un controlador para enrutamiendo de las paginas
gem 'simple_form'#gema para hacer los formularios
group :development do
  gem 'better_errors'
  gem 'quiet_assets'
  gem 'rails_layout'
  gem 'sqlite3'
end
group :production do
  gem 'pg' #PostgreSQL gem Heroku doesn’t support the SQLite database; the company provides a PostgreSQL database.
  gem 'rails_12factor'#logging and static assets
end


