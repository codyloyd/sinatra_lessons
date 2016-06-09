# Projects: Sinatra

*Don't forget to use Git to save your projects!*

## Project 1: A simple online game.

You've seen how simple it can be to get something up and running using Sinatra, in this project you'll be following a tutorial to create a simple number guessing game.

The tutorial leave most of the ruby code to you and just tells you how to do the new Sinatra stuff.  By this point the ruby code required should be pretty simple for you.

### Your Task

1. [Do this project/tutorial from Jumpstart Lab](http://tutorials.jumpstartlab.com/projects/web_guesser.html). Be sure to try out some of the Extensions at the end of the tutorial, that's the fun stuff!  
2.  Now might be a good time to remind yourself how HTML and CSS work, so take a _little_ time to make it look pretty before moving on.
3.  Deploying a Sinatra app to Heroku takes a little bit more work but the process is fairly straightforward. Instructions can be found [here](https://devcenter.heroku.com/articles/rack#sinatra)
	1. your `config.ru` file should require your main application file (it's probably `web_guesser.rb`)
	2. if you are using `sinatra/reloader`, you need to remove or comment out that line before pushing to Heroku.
	3. after you create your Gemfile, you need to run `bundle install` and add/commit the files to git before pushing to Heroku.

## Student Solutions

*Send us your solution so we can show others! Submit a link to the Github repo with your files in it here using any of the methods listed on the [contributing page](http://github.com/TheOdinProject/curriculum/blob/master/contributing.md).  Please include your partner's github handle somewhere in the description if they would like attribution.*

* codyloyd's solution [github](https://github.com/codyloyd/sinatra_web_guesser) / [see it on the web](https://limitless-lake-17561.herokuapp.com/)

## Project 2: Ceasar Cipher _reloaded_

Revisit the ceasar cipher ruby script that you created during [Ruby Building Blocks](http://www.theodinproject.com/ruby-programming/building-blocks) and use Sinatra to create a simple front-end for it.

### Your Task

1. Start a new sinatra project (you can begin by doing a simple hello world as in the previous example)
2. You should be able to do this with only one view, and a couple of routes, but feel free to be as fancy as you like.
3. [Deploy to Heroku!](https://devcenter.heroku.com/articles/rack#sinatra)

## Student Solutions

*Send us your solution so we can show others! Submit a link to the Github repo with your files in it here using any of the methods listed on the [contributing page](http://github.com/TheOdinProject/curriculum/blob/master/contributing.md).  Please include your partner's github handle somewhere in the description if they would like attribution.*

* codyloyd's solution [github](https://github.com/codyloyd/sinatra-translator) / [see it on the web](https://cryptic-reaches-55962.herokuapp.com/)

## Project 3: Another Web-Game

Pick either Mastermind or Hangman and build a front end for it.  This one might take a little more work, but it should be well within your grasp at this point.  Have fun!

### Your Task

1. The UI-implementation is up to you this time.  Keeping them text-based is acceptable, but now that we're on the web you can branch out with images to make something a little nicer.
2. You can use your [jQuery skills](http://www.theodinproject.com/web-development-101/jquery-basics) to create animation and effects.
3. _Extra Credit_ The free Heroku account only allows a limited number of projects, unless you add a credit card to your account. If you _do_ add your information, you can have unlimited projects, but they still limit how many of them can be "awake" at one time. You might consider using sinatra to make yourself a simple web-portfolio so that you can store all of these apps in one project.

## Student Solutions

*Send us your solution so we can show others! Submit a link to the Github repo with your files in it here using any of the methods listed on the [contributing page](http://github.com/TheOdinProject/curriculum/blob/master/contributing.md).  Please include your partner's github handle somewhere in the description if they would like attribution.*

* codyloyd's solution MasterMind: [github](https://github.com/codyloyd/sinatra-codebreaker) / [see it on the web](https://crafty-breaker-4567.herokuapp.com/)