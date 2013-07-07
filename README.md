Example of Java on Heroku
=========================
Any java app that uses maven as build tool can be run on heroku.

mvn package 

Run it locally using:
set PORT=5000 (or export PORT=5000)
java -cp "target\classes;target\dependency\*" HelloWorld

Deploy on Heroku
----------------
heroku create
git push heroku master

References
----------
https://devcenter.heroku.com/articles/java

