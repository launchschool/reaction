# Rails + Webpack + React + Heroku

This starter app provides you with all you need to get started on the full-stack trello clone we call reaction. The project uses rails with webpacker gem that provides the tooling a modern full-stack workflow needs. The webpacker gem provides the following functionality:

1. Bundle all your front-end code into one file
2. Compile JSX to JavaScript
3. Compile ES6 code to ES5

## Directory Structure
The directory 


## Where code should live

* Ruby/Rails code should continue to live in its appropriate directory within
  `app`.
* React code should live in `app/javascript/components/`.
* React component unit tests should use the `.test.js` extension and live next
  to the components being tested within `app/javascript/components/`.

## Useful commands

Run JS unit tests:

```
$ bin/yarn run test
```

Run eslint on files in `app/javascript/`:

```
$ bin/yarn run lint
```

## Deployment hints ([source](https://medium.com/@hpux/rails-5-1-loves-javascript-a1d84d5318b))

1. Add the nodejs and ruby buildpacks:

    ```
    $ heroku create
    $ heroku buildpacks:add --index 1 heroku/nodejs
    $ heroku buildpacks:add --index 2 heroku/ruby
    ```
