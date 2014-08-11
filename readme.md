##Flux-React MVC
Flux applications have three major parts: the dispatcher, the stores, and the views (React components). These should not be confused with Model-View-Controller. Controllers do exist in a Flux application, but they are controller-views -- views often found at the top of the hierarchy that retrieve data from the stores and pass this data down to their children. Additionally, actions — dispatcher helper methods — are often used to support a semantic dispatcher API. It can be useful to think of them as a fourth part of the Flux update cycle.



## Clone this Project from GIT
## Running
    npm install
    npm install -g grunt-cli
    grunt

Then visit: [http://localhost:3000/](http://localhost:3000/)


## Facebook's slides
![Overall](http://getshao.files.wordpress.com/2014/05/screen-shot-2014-05-13-at-11-10-37-pm.png?w=696&h=362)
![Flux](http://i.imgur.com/DeR0tIZ.png?2)
![React](http://getshao.files.wordpress.com/2014/05/screen-shot-2014-05-13-at-11-09-26-pm.png?w=696&h=358)

## Credit

The TodoMVC application was original created by Bill Fisher /  Jing Chen and Shaohua (BackboneJS Implementation) Please visit the [original repo here](https://github.com/facebook/react/tree/master/examples/todomvc-flux):
