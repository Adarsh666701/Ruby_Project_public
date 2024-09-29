# README
* Adarsh Singh
Things you may want to cover:

* Ruby version
`3.2.2`

* Configuration
Add your env variables to the `config/credentials.yml.enc` file. You can do this by running `bin/rails credentials:edit`

* Database creation
Locally we use sqlite3 as our database. This is already set up for you. In production make sure your `DATABASE_URL` env variable is set. We use PostgreSQL in production.

* Database initialization
run `bin/rails db:migrate` to create the tables
