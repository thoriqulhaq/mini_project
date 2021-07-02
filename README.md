# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

`rails db:create`

* Database initialization


rails db:migrate
rails db:seed


* How to run the test suite

`rake run bundle exec rspec`

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

Before deploying to production, we need to compile the Front End assets
`rake assets:precompile` or `rake webpacker:compile`

After that, make sure that this config `RAILS_SERVE_STATIC_FILES` is set to true

If you are unable to compile the Front End assets on Heroku, run this
`heroku run rake assets:precompile`
