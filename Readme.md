This ia barebones setup one could use for hosting static Heroku sites.  It's based on the advice here:

http://anti-pattern.com/2012/6/2/static-sites-on-heroku

More information can be found from Heroku themselves here:

https://devcenter.heroku.com/articles/static-sites-on-heroku

Use
===

Using this stubbed out setup is easy, just run the following from your terminal (assuming your have Ruby and git installed):

	$ gem install heroku
	$ git clone https://github.com/jimjkelly/StaticHeroku.git
	$ cd StaticHeroku
	$ heroku create
	$ git push heroku master

And you are done!

