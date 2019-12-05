# React Tic-Tac-Toe

Facebook has written a very good introduction for the [React](https://reactjs.org/) library. You can find it from [React Tutorial](https://reactjs.org/tutorial/tutorial.html).

Alternatively, in case you found the above tutorial too hard, please try the [step-by-step](https://reactjs.org/docs/hello-world.html) introduction to React first.

## Do the Tutorial

The tutorial can be done either in your own internet browser (1) using the CodePen service or (2) locally on your computer. If you're unfamiliar with any software development, it's recommended to use CodePen as it's more straightforward.

### (1) In Your Own Browser

The tutorial can be run through without any installations by starting from [this code template in codepen](https://codepen.io/gaearon/pen/oWWQNa?editors=0010). And following the tutorial through [starting here](https://reactjs.org/tutorial/tutorial.html#overview).

### (2) Run the tutorial locally

Once you have the application running in your local environment ([Node.js](https://nodejs.org/en/download/package-manager/) **or** [Docker](https://docs.docker.com/install/)) you can edit the files in your editor and see the changes immediately in the browser window here [http://localhost:8000](http://localhost:8000).

#### Prerequisites

* [Git](https://www.atlassian.com/git/tutorials/install-git)
* [nodejs](https://nodejs.org/en/download/package-manager/) or [docker](https://docs.docker.com/install/)
* Any shell, console or terminal.
* Any editor. We recommend [Sublime Text](https://www.sublimetext.com/), [Atom](https://atom.io/) or [Visual Studio Code](https://code.visualstudio.com/).

You are going to have to sign up to GitHub to clone code. If you want to avoid that, you can always just download the code (by clicking the green **Clone or download** -button).

#### Using Node.js

1. Install [Node.js](https://nodejs.org/en/download/package-manager/).
1. Open your favorite shell.
1. Clone this repository:

        git clone https://github.com/koodi101/lesson1-react-tictactoe.git

1. Go to the cloned directory:

        cd lesson1-react-tictactoe

1. Install dependencies:

        npm install

1. Run the app:

        npm start

1. Open browser in [http://localhost:8000](http://localhost:8000)

#### Using Docker

1. Install [Docker](https://docs.docker.com/install/) ([download link for mac](https://download.docker.com/mac/stable/Docker.dmg)).
1. Open your favorite shell.

1. Clone this repository:

        git clone https://github.com/koodi101/lesson1-react-tictactoe.git

1. Go to the cloned directory:

        cd lesson1-react-tictactoe

1. Run the app:

        docker-compose up

1. Open browser in [http://localhost:8000](http://localhost:8000)

#### Using Heroku

1. Install [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
1. [Create new app in Heroku](https://dashboard.heroku.com/new-app)
1. Clone this repository:

        git clone https://github.com/koodi101/react-tictactoe.git

1. Go to the cloned directory:

        cd lesson1-react-tictactoe

1. Login to Heroku on command line:

        heroku login

1. Add Heroku remote to git configuration:

        heroku git:remote -a \<app name\>

1. Tell Heroku to also install dependencies for development use:

        heroku config:set NPM_CONFIG_PRODUCTION=false

1. Tell the application to use port 80 instead of 8080:

        heroku config:set PORT=80

1. Push the code to Heroku:

        git push heroku master
