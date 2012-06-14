# (Tower) on Rails Tutorial: third application

This is the sample application for 
[*Ruby on Rails Tutorial: Learn Rails by Example*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/). 

However, instead of using Ruby on Rails, I am following along but using Coffeescript, Node,
and particularly, the [*Tower.js*](http://towerjs.org/) framework, which was modeled quite closely on rails. It is my plan to not only learn Tower by doing so, but also to document the differences for those following in my footsteps. So far:

See https://github.com/edubkendo/firstApp for how I worked through the first chapter of the book, which includes information on getting a Tower.js app running on [Heroku](http://www.heroku.com/).

For chapter two, including examples of relationships (hasMany/belongsTo), validations and flash messages, check out https://github.com/edubkendo/demoApp .

## Setup

```
tower new sampleApp

cd sampleApp/

npm install .

git init

git add .

git commit -m "Initial commit"

git remote add origin git@github.com:username/sampleApp.git

git push -u origin master

```

So far only minor changes, all of which have been discussed in the previous app.