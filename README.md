# AR Exercise Repo

## Instructions

### Setup

1. Create a new PG database on heroku.
2. Grab (copy) it's connection information ([but this time for ActiveRecord](http://d.pr/i/tjta/1qrbx7p9))
3. Paste the information into the `establish_connection` method call in `setup.rb` so that AR can connect to *your* database. (Note: the format that heroku gives you needs to be modified a bit: add quotes, commas etc to make it into a hash format)
4. Run `bundle install` (using Bundler)
5. Run the first exercise file to make sure the database connection is working: `ruby exercises/exercise_1.rb`

### Running Exercises

Complete the exercises by modify the appropriate `exercises/exercise_*.rb` file and run the exercise using the `ruby` command.

Example:
    ruby exercises/exercise_1.rb

Follow the instructions to work on the exercises within the `exercises` folder.

Remember to commit at logical steps (like at the end of every exercise).

**Note:** You do not need to / should not comment out your code in each exercise as you move on to the next one. The exercises in this assignment are meant to build on and continue from the previous ones. That's why you see them requiring the previous ones.