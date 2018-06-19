Rails-chat
------

#### Clone The Repository
`$ git clone git@github.com:tuansaker1412/rails-chat.git`


#### Change directory
`$ cd rails-chat`

#### Install dependencies
`$ bundle install`

#### Setup up database
`$ rails db:setup`
`$ rails db:migrate`

#### Setup up Figaro and Env variables
- Rename your `config/database.yml.eg` file to `config/database.yml` and replace the content.
- Rename your `config/application.yml.eg` file to `config/application.yml` and replace the content (if any) with the following:
```
PUSHER_APP_ID: 'your Pusher app ID'
PUSHER_KEY: 'your pusher kep'
PUSHER_SECRET: 'your pusher secret'
PUSHER_CLUSTER: 'your pusher cluster'
```

Prerequisites
------
A basic knowledge of Ruby, MySQL and CoffeeScript


Built With
------
- [Pusher](https://pusher.com) - A Ruby gem to interact with the Pusher REST API
