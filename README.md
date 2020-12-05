# GraphQL Tutorial

## Purpose

I started this project to help me better understand GraphQL.

## Set-up

If you're interested in using this application, follow the following environmental set-up requirements...<br><br>

1. Make sure you have the correct Ruby version installed (2.6.3). To check your Ruby version, from your command line, run `ruby -v`
  - If you do not have the correct version, follow the instructions to install 2.5.3: from the command line, run `rbenv install 2.6.3`
2. Make sure you have the correct Rails version installed (6.0.2.1). To check your Rails version, from your command line, run `rails -v`
  - If you do not have the correct Rails version, [follow these instructions to install 2.5.4.3](https://github.com/turingschool-examples/task_manager_rails/blob/master/rails_uninstall.md)
3. Fork and Clone the repo
4. Install gem packages: `bundle install`
5. Setup the database: `rails db:create`
6. Seed your local database: `rails db:seed`

## Using the app

In order to use the app, you must navigate to inside the directory of the project. Then, run your local server (`rails s` in the terminal). Then navigate to your web browser (preferrably Chrome or FireFox, the updated versions) and search for "http://localhost:3000/graphiql". This should open up a GraphiQL webpage where you can do the following; 

1. View one note
2. View all notes (there should be 5)
3. Add a note

## Future of this app

In the future I'd like to add the function of being able to edit a note as well as delete a note. Eventually I'd like to build a separate application which makes queries to this backend and displays the notes on a frontend styled webpage that one can visit.
