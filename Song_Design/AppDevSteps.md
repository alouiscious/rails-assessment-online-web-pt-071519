# App Dev Process

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
    Ruby 2.6.0  

* System dependencies
  gems:
    faker
    
    omniauth
    for devise
      bcrypt ~> 3.0
      orm_adapter ~> 0.1
      railties >= 4.1.0
      responders >= 0
      warden ~> 1.2.3

     
* Configuration
  rails new app used for Song Design app
  rails g resource utilized for MVC and migration files creation.
  model modifications include has_many, many_to_many, strftime formating, validations, optionals, partials, view helpers, and scope.

* Database creation
  besides the rails generator user to create the intital migration table, a seeds file and faker gem was utilized to create smple database content


* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)
  Counter caches set for songs, musicians, song_notes.

* Deployment instructions

* ...
