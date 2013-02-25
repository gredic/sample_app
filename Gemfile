source 'https://rubygems.org'

gem 'rails', '3.2.11'
gem 'gravatar_image_tag', '0.1.0'
gem 'will_paginate', '3.0.pre4'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'spork'

group :production, :staging do
  gem "pg"
end

group :development, :test do
	gem "sqlite3-ruby", :require => "sqlite3"
	gem 'rspec-rails'
end

group :development do
# gem 'rspec-rails'
gem 'annotate'
gem 'faker'
end
group :test do
#gem 'rspec'
gem 'webrat', '0.7.3'
gem 'factory_girl_rails', '1.0'
end


gem 'json'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug'
