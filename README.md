### mariannna_website

A personal website created with the awesome [Alchemy CMS](http://alchemy-cms.com/about).
This is my first project with it so I'm in the learning curve: work in progress!


### Setup

    $ bundle install --without production
    $ bundle exec rake db:create db:migrate db:seed


### Upgrading Alchemy CMS

Set new stable branch name into `Gemfile` for `alchemy_cms` and `alchemy-devise` gems, then remove `Gemfile.lock` and run:

    $ bundle install --without production
    $ bundle exec rake alchemy:upgrade
