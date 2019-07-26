# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

gem "react_on_rails", "11.1.4" # Update to the current version
gem "webpacker", "~> 3" # Newer versions might be supported


bundle exec rails webpacker:install
bundle exec rails webpacker:install:react

rails generate react_on_rails:install

gem install foreman

foreman start -f Procfile.dev

start rails server then hit on browser

 localhost:3000/hello_world

./bin/webpacker-dev-server