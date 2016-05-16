Move code from Controller to Model

* Move finder to named-scope (rails2 only)
* Use model association
* Use scope access
* Add model virtual attribute
* Replace complex creation with factory method
* Move model logic into the Model
* Check return value of “save!”

RESTful Conventions

* Overuse route customizations
* Needless deep nesting
* Not use default route
* Restrict auto-generated routes

Model

* Keep finders on their own model (rails2 only)
* The law of demeter
* Use observer
* Use query attribute
* Remove unused methods in models
* Protect mass assignment

Mailer

* Use multipart/alternative as content-type of email

Migration

* Isolating seed data
* Always add database index
* Use say with time in migrations

Controller

* Use before-filter (disabled by default)
* Simplify render in controllers
* Remove unused methods in controllers

Helper

* Remove empty helpers
* Remove unused methods in helpers

View

* Move code into controller
* Move code into model
* Move code into helper
* Replace instance variable with local variable
* Simplify render in views
* Not use time-ago-in-words

Deployment

* Dry bundler in Capistrano
* Speed up assets precompilation with turbo-sprockets-rails3

Other

* Remove trailing whitespace
* Remove tab (disabled by default)
* Hash syntax (disabled by default)
* Use parentheses in method definition (disabled by default)
* Long line (disabled by default)
* Not rescue exception
