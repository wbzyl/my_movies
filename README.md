## README

RSpec documentation:

* [rspec-rails](https://github.com/rspec/rspec-rails)
* [rspec-collection_matchers](https://github.com/rspec/rspec-collection_matchers)
* [rspec-expectations](https://github.com/rspec/rspec-expectations)

### Baby steps

```sh
cat ~/.railsrc
  --skip-bundle
  --no-test-framework
  --skip-test-unit
rails new my_movies
cd my_movies/
# add rspec-rails, capybara, database_cleaner to Gemfile
gem list rspec
bundle install
mv README.rdoc README.md
rails g rspec:install
```

# The Movie Database API

* [Movie & TV API Overview](https://www.themoviedb.org/documentation/api)
* [wrappers libraries](https://www.themoviedb.org/documentation/api/wrappers-libraries)
* [themoviedb](https://github.com/ahmetabdi/themoviedb) –
  a Ruby wrapper for the [The Movie Database API](http://docs.themoviedb.apiary.io/)
* [ruby-tmdb](https://github.com/Irio/ruby-tmdb/)
  – an ActiveRecord-style API wrapper for TheMovieDB.org compatible with API v3



### Things you may want to cover

This README would normally document whatever steps are necessary to
get the application up and running:

* Ruby version
* System dependencies
* Configuration
* Database creation
* Database initialization
* How to run the test suite
* Services (job queues, cache servers, search engines, etc.)
* Deployment instructions
