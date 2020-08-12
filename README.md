# Ruby on Rails Website

This website work as a management system for users and posts in a social media. You can check users and microposts under `/users` and `/microposts` respectively

[Check the live version here](https://secure-mesa-51925.herokuapp.com/)

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```
