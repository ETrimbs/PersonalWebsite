source 'https://rubygems.org'

gem 'rails',          '~> 5.1.7'
gem 'bootstrap-sass', '3.4.1'
gem 'bcrypt',         '3.1.12'
gem 'puma',           '~> 3.7'
gem 'sass-rails',     '~> 5.0'
gem 'uglifier',       '>= 1.3.0'
gem 'coffee-rails',   '~> 4.2'
gem 'jquery-rails',   '4.3.1'
gem 'turbolinks',     '~> 5'
gem 'jbuilder',       '~> 2.5'
gem 'byebug'

group :development, :test do
  gem 'sqlite3', '1.3.13'
end

group :development do
  gem 'solargraph',            '>0.32.5'
  gem 'web-console',           '3.5.1'
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.0.2'
  gem 'spring-watcher-listen', '2.0.1'
end

group :test do
  gem 'rails-controller-testing', '1.0.2'
  gem 'minitest',                 '5.10.3'
  gem 'minitest-reporters',       '1.1.14'
  gem 'guard',                    '2.13.0'
  gem 'guard-minitest',           '2.4.4'
  gem 'wdm',                      '>= 0.1.0' if Gem.win_platform?
end

group :production do
  gem 'pg', '0.20.0'
end

# Windows does not include zoneinfo files, so git the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]