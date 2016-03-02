require 'capistrano/setup'
require 'capistrano/deploy'

require 'capistrano/rvm'
require 'capistrano/bundler'
require 'capistrano/rails/assets'
require 'capistrano/puma'
require 'capistrano/puma/monit'

Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }
