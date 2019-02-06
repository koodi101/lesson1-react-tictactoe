# React Tic-Tac-Toe

Facebook has written a very good introduction for the [React](https://reactjs.org/) library. You can find it from [React Tutorial](https://reactjs.org/tutorial/tutorial.html).

## Do the tutorial in Browser

The tutorial can be run through without any installations by starting from [this code template in codepen](https://codepen.io/gaearon/pen/oWWQNa?editors=0010). And following the tutorial through [starting here](https://reactjs.org/tutorial/tutorial.html#overview).

## Run the tutorial locally

Once you have the application running in your local environment ([nodejs](https://nodejs.org/en/download/package-manager/) or [docker](https://docs.docker.com/install/)) you can edit the files in your editor and see the changes immediately in the browser window here [http://localhost:8000](http://localhost:8000).

### Prerequisites

* [Git](https://www.atlassian.com/git/tutorials/install-git)
* [nodejs](https://nodejs.org/en/download/package-manager/) or [docker](https://docs.docker.com/install/)
* Any shell, console or terminal.
* Any editor. We recommend [sublime](https://www.sublimetext.com/), [atom](https://atom.io/) or [vscode](https://code.visualstudio.com/).

You are going to have to sign up to github to clone code. If you want to avoid that, you can always just download the code (By clicking the green **Clone or download** -button).

### Using Node

* Install [nodejs](https://nodejs.org/en/download/package-manager/).
* Open your favorite shell.
* Clone this repository: `git clone https://github.com/koodi101/lesson1-react-tictactoe.git`
* Go to the cloned directory: `cd react-tictactoe`.
* Install dependencies `npm install`
* Run the app `npm start`
* Open browser in [http://localhost:8000](http://localhost:8000)


### Using Docker

* Install [docker](https://docs.docker.com/install/).
* Open your favorite shell.
* Clone this repository: `git clone https://github.com/koodi101/lesson1-react-tictactoe.git`
* Go to the cloned directory: `cd lesson1-react-tictactoe`
* Run the app `docker-compose up`
* Open browser in [http://localhost:8000](http://localhost:8000)

### Using Heroku
* Install [heroku cli](https://devcenter.heroku.com/articles/heroku-cli)
* [Create new app in Heroku](https://dashboard.heroku.com/new-app)
* Clone the repository `git clone https://github.com/koodi101/react-tictactoe.git`
* Go to the cloned directory: `cd lesson1-react-tictactoe`
* Login to heroku on command line `heroku login`
* Add heroku remote to git configuration `heroku git:remote -a \<app name\>`
* Tell heroku to also install dependencies for development use `heroku config:set NPM_CONFIG_PRODUCTION=false`
* Tell the application to use port 80 instead of 8080 `heroku config:set PORT=80`
* Push the code to heroku `git push heroku master`
