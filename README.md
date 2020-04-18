# redmine_plugins

## Install
Copy redmine_agile plugin to {REDMINE_ROOT}/plugins
Run bundle install –without development test RAILS_ENV=production
Run bundle exec rake redmine:plugins [NAME=redmine_agile] RAILS_ENV=production

## Uninstall
bundle exec rake redmine:plugins NAME=redmine_xxx VERSION=0 RAILS_ENV=production rm -r plugins/redmine_xxx
