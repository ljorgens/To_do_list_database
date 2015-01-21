Database Structure is as follows:

todo_database
Tables    |   tasks    |    lists

tasks(fields)
1. id (int - id serial PRIMARY KEY)
2. description (varchar)
3. list_id (int)
4. due_date (timestamp)

lists(fields)
1. id (int - id serial PRIMARY KEY)
2. name (varchar)

to_do_test (Create this db off of template for todo_database)
