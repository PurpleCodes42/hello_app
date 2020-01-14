source 'https://rubygems.org'

#didnt work, had to put rails as it is ~> 5.2
gem 'rails',        '~>5.2'
gem 'puma',         '3.12.2'
gem 'sass-rails',   '5.0.6'
gem 'uglifier',     '3.2.0'
gem 'coffee-rails', '4.2.2'
gem 'jquery-rails', '4.3.1'
gem 'turbolinks',   '5.0.1'
gem 'jbuilder',     '2.7.0'

group :development, :test do
  gem 'sqlite3', '1.3.13'
  gem 'byebug',  '9.0.6', platform: :mri
end

group :development do
  gem 'web-console',           '3.5.1'
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.0.2'
  gem 'spring-watcher-listen', '2.0.1'
end

#didnt work, here was the answer https://stackoverflow.com/questions/51493625/new-to-rails-rails-server-error-cannot-load-such-file-bootsnap-setup-load
# unabled bootsnap in confif/boot.rb
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]