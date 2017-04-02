# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
  1. rails 5.0.2 
  2. ruby 2.3.3

* System dependencies
check this 
 http://www.htmltohaml.com/
* Configuration

 1. add below line to # config/environments/development.rb
    * to reduce the final code by removing the spaces and line breaks
 ```
Rails . application . configure do
  # ...
    Haml::Template.options[:remove_whitespace ] = true
end

 ```
* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
