# Standard Notes Syncing Server

You can run your own Standard Notes server and use it with any Standard Notes app. This allows you to have 100% control of your data. This server is built with Ruby on Rails and can be deployed in minutes.

**Requirements**

- Ruby 2.3+
- Rails 5
- Postgresql

### Getting started

1. Clone the project:

	```
	git clone https://github.com/standardnotes/syncing-server.git
	```

1. Create a `.env` file in the project's root directory. See [env.sample](env.sample) for required values.

1. Initialize the project:

	```
	bundle install
	bundle exec rails db:create db:migrate
	```

1. Start the server:

	```
	bundle exec rails server
	```
