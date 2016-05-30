source 'https://rubygems.org'

ruby '2.3.0'

gem 'rails', '4.2.6'
gem 'actionpack'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'


gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'spree', '~> 3.1.0.rc1'
gem 'spree_auth_devise', '~> 3.1.0.rc1'
gem 'spree_gateway', '~> 3.1.0.rc1'
gem 'spree_reviews', github: 'spree-contrib/spree_reviews', branch: '3-1-stable'
gem "spree_product_zoom", :git => "git://github.com/spree/spree_product_zoom.git"

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  gem 'sqlite3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'mail'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
  gem 'aws-sdk', '< 2.0'
  gem 'mailgun_rails'
  gem 'braintree'
end
