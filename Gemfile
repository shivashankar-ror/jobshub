ruby "2.4.0"
source 'https://rubygems.org'
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end
gem 'rails', '~> 5.0'
gem 'pg', '~> 0.20'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '~> 3.2'
gem 'coffee-rails', '~> 4.2'
gem 'therubyracer', "~> 0.12", platforms: :ruby
gem 'puma', '~> 3.8'

gem 'jquery-rails', "~> 4.3"
gem 'turbolinks', '~> 5.0'
gem 'jbuilder', '~> 2.6'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', "~> 9.0", platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '~> 3.5'
  gem 'listen', '~> 3.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', "~> 2.0"
  gem 'spring-watcher-listen', '~> 2.0'
end
