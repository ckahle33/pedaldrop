require "capistrano/setup"

require "capistrano/deploy"

require "capistrano/scm/git"
install_plugin Capistrano::SCM::Git

require "capistrano/chruby"
require "capistrano/bundler"
require "capistrano/rails"
require "capistrano/rails/migrations"
require "capistrano/passenger"
require "capistrano/sidekiq"

# Load custom tasks from `lib/capistrano/tasks` if you have any defined
Dir.glob("lib/capistrano/tasks/*.rake").each { |r| import r }
