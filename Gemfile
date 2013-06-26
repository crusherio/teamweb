source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'bourbon'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>= 1.0.3'
  gem 'compass-rails'
end

gem 'execjs'
gem 'jquery-rails'
gem "haml-rails"
gem "bootstrap-sass", ">= 2.3.0.0"

gem "rails-boilerplate"
gem "devise"

# To use Jbuilder templates for JSON
gem 'jbuilder'

gem "devise"
gem 'puma'

gem 'simple_form'

# Production for Heroku
group :production do
  gem 'pg'
  gem 'dalli'
end

group :development, :test do
	gem 'awesome_print' # OF COURSE!
	gem 'sqlite3'
  gem 'minitest-spec-rails'
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'interactive_editor' # able to vi from irb
  gem "quiet_assets", ">= 1.0.1"
  gem 'guard'
  gem 'guard-rails'
  gem 'guard-minitest'
  gem 'guard-annotate'
  gem 'guard-puma'
  gem 'guard-bundler', "~> 1.0.0"
  gem 'brakeman' # checks for security vulns
  gem 'guard-brakeman'
  #gem 'guard-test'
  gem "sextant" # adds route display info to /rails/routes
  gem "better_errors"
  gem "binding_of_caller"
  gem 'annotate'
  #gem "literate_randomizer"
  # Filesystem notifiers
  gem 'ruby_gntp' # Growl notification protocol
  #gem 'libnotify'
  gem 'rb-inotify', :require => false
  gem 'rb-fsevent', :require => false
  gem 'rb-fchange', :require => false
  # BDD
  gem 'capybara'
  gem 'database_cleaner'
  gem 'cucumber-rails', :require => false
  
  # Additions suggested by article 
  # http://www.codebeerstartups.com/2013/04/must-have-gems-for-development-machine-in-ruby-on-rails/
  gem 'bullet'
  gem 'localtunnel' #exposes site as needed ($ localtunnel-beta 8000)
  gem 'mailcatcher'
  gem 'lol_dba' # site optimization? ($ rake db:find_indexes > $ )
  gem 'reek' # check for code smells ($ reek -q .)
  gem 'rails_best_practices' # check for best practice fixes ($ rails_best_practices .)
  gem 'request-log-analyzer' # check out the live website request logs for performance issues/info 
  #                         ($ request-log-analyzer --parse-strategy assume-correct log/development.log)
  gem 'smusher' # optimize images ($ smusher app/assets/images)
end

