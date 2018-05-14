# Kreuttal Development

## Requirements

* PHP >= 7.1.3
* Yarn

## Setup

1. Copy .env.example to .env

2. Generate application key `php artisan key:generate`

## Start simple PHP server or Vagrant server

* Run `php artisan serve`

* Start the Vagrant virtual machine by running `vagrant up` from your Vagrant folder (or `homestead up` if you've set up a shortcut). In this case, edit your `webpack.mix.js` proxy to `proxy: 'www.reiterzentrum-kreuttal.test`.

## Development

1. Start the dev proxy by running `yarn watch`.

2. Develop ;-)

3. Commit

## Deploy

1. Run `yarn production`

2. Push

## Go home!

1. Stop yarn (`ctrl + c`) and the local php server (`ctrl + c`)

2. Optionally, stop the Vagrant virtual machine with `vagrant halt` from your Vagrant folder (or `homestead halt`).
