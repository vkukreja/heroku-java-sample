Example of Java on Heroku
=========================

mvn package 

Run it locally using:
java -cp "target\classes;target\dependency\*" HelloWorld

Deploy on Heroku
----------------
heroku create
git push heroku master

References
----------
https://devcenter.heroku.com/articles/java

