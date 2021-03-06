[![Build Status](https://travis-ci.org/joejknowles/chitter-challenge.svg?branch=master)](https://travis-ci.org/joejknowles/chitter-challenge)

Chitter Challenge
=================

Technologies
------------
Ruby, HTML, CSS, Cucumber, Sinatra, Postgres, DataMapper.

Instructions
------------
To run tests clone repo, navigate to directory. Run command `bundle install`, then run `rake`. App can be found on Heroku at: http://thechitter.herokuapp.com
Features
--------
Want to see exclusive updates from the likes of Barack Obama and Kim Kardashian? They've been cheeping HOURLY, so join us quick before all the usernames run out.

Sign up and send a 'cheep' out into the world. Click any username to go to their profile. Follow other users to see their cheeps without the noise of the enormous global user base. Want to show your appreciation of a post? Show it some 'applause', that's what the 'applaud' button is for. Now with exclusive trending feature. See what's most important to our vast user base thanks to our unique sorting algorithm; you'll only see what really matters.


<br>
<br>
<br>

Challenge:
-------

As usual please start by

* Filling out your learning plan self review for the week: https://github.com/makersacademy/learning_plan (if you haven't already)
* Forking this repo

We are going to write a little Twitter clone that will allow the users to post messages to a public stream.

Features:
-------

```sh
As a Maker
So that I can post messages on Chitter as me
I want to sign up for Chitter

As a Maker
So that I can post messages on Chitter as me
I want to log in to Chitter

As a Maker
So that I can avoid others posting messages on Chitter as me
I want to log out of Chitter

As a maker
So that I can let people know what I am doing
I want to post a message (peep) to chitter

As a maker
So that I can see what others are saying
I want to see all peeps in reverse chronological order
```

Notes on functionality:
------

* Drive the creation of your app using tests - either cucumber or rspec as you prefer
* Makers sign up to chitter with their email, password, name and a user name (e.g. sam@makersacademy.com, s3cr3t, Samuel Russell Hampden Joseph, tansaku).
* The username and email are unique.
* Peeps (posts to chitter) have the name of the maker and their user handle.
* Use bcrypt to secure the passwords.
* Use data mapper and postgres to save the data.
* You don't have to be logged in to see the peeps.
* You only can peep if you are logged in.
* Please ensure that you update your README to indicate the technologies used, and give instructions on how to install and run the tests
* Finally submit a pull request before Monday at 9am with your solution or partial solution.  However much or little amount of code you wrote please please please submit a pull request before Monday at 9am

Bonus:
-----

If you have time you can implement the following:

* In order to start a conversation as a maker I want to reply to a peep from another maker.

And/Or:

* Work on the css to make it look good (we all like beautiful things).

Good luck and let the chitter begin!
