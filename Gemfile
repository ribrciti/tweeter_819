source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.0'

gem 'rails', '~> 5.2.3'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'



gem 'bootsnap', '>= 1.1.0', require: false

# Project Specific Gems*****************************************************

gem 'bulma-rails', '~> 0.7.5'     # CSS
gem 'simple_form', '~> 4.1'
gem 'gravatar_image_tag', '~> 1.2'
gem 'devise', '~> 4.7'


group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  # Project Specific Gems***********************************************
  gem 'better_errors', '~> 2.5', '>= 2.5.1'
  gem "binding_of_caller"
  gem 'guard', '~> 2.15'                                           
	gem 'guard-livereload', '~> 2.5', '>= 2.5.2', require: false    
end


gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
