## Queuebie
Queuebie is an Ruby on Rails application that helps you conveniently track the location of your assets across the globe.


## Requirements
* git
* ruby 2.3.1 or higher
* postgresql
* Google Maps API key


## Setup Guide
* pull the repo locally by `git clone https://github.com/SheepD/queuebie.git`
* run `bundle install -j4` at the root of the directory location
* run `mv config/application.yml.example config/application.yml`
* populate `application.yml` with the required api keys and credentials
* run `rails db:setup`
* run `rails server`, you can then visit `htpp://localhost:3000`


## Contributing
* Fork this repository
* create a new branch `feature/sone-new-feature` or `bugfix/some-bug-fix`
* create a pull request
