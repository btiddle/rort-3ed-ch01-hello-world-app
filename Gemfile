source 'https://rubygems.org'

gem 'rails',        '4.1.5'
gem 'sass-rails',   '4.0.3'
gem 'uglifier',     '2.5.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.1.1'
gem 'turbolinks',   '2.2.2'
gem 'jbuilder',     '2.1.3'
gem 'sdoc',         '0.4.0', group: :doc
gem 'thin'

group :development, :test do
  gem 'sqlite3', '1.3.9'
  gem 'spring',  '1.1.3'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'hirb'
  gem 'rails-footnotes', '>= 4.0.0', '<5' 
end

group :production do
    # Include 'rails_12factor' gem to enable all platform features on Heroku.
    gem 'rails_12factor'
    # This means in the producion environment, use postgress as you DB
    gem 'pg'
end