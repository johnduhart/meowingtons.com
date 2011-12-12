require 'rubygems'
require 'railsless-deploy'

set :application, "johnduhart.me"
set :repository, "git://github.com/johnduhart/meowingtons.com.git"

set :scm, :git
set :branch, "master"

set :deploy_to, "/var/www/meowingtons.com"

default_run_options[:pty] = true

role :web, "kiwi.compwhizii.net"

set :user, "root"
set :use_sudo, false
