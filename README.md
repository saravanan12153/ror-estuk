== README

This is code for ESTUK => a simple 2 sided bookstore where you can buy and sell books
This app is created in Ruby 2.2.1 and Rails 4.2.0

** [eStuk test website](http://estuk.sulman.me) **

To make it your own...

* Copy whole repo

* Make a file `.env` in main directory and put environment variable for Google Cloud Storage & Stripe keys.

* Run in terminal `bundle install`

* Run in terminal `rake db:migrate`

* Run in terminal `run server`

* Run in browser `localhost:3000`

Main Gems:

* Ruby version 2.2.1

* Rails 4.2.0

* twitter-bootstrap-rails

* simple-form

* devise

* auto_html

* sqlite3

* paperclip

* fog

* friendly_id

* stripe

* aasm

* dotenv-rails `for development`

* pg `for heroku`

* rails_12factor `for heroku`
