# Ruby-Sinatra-PostgreSQL Todolist Webapp

This app uses Sinatra to create a Todolist webapp. The todolist data is stored on a PostgreSQL database, with the `pg` gem used to send queries to the database.

Data received is passed to the Ruby file `todo.rb`, which manipulates this data and relays it to the views. Views are written in `.erb`, which parses embedded Ruby syntax into browser-ready HTML.
