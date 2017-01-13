# DevMtn-React-Introduction

## Setup
For this setup we will be using `create-react-app` to quickly create our base for our `react` task-manager project. To get started `npm install` or `yarn install` when in the root directory of the project. Be sure to also `sudo npm install -g create-react-app` to gain access to its CLI. Once everything is installed we're ready to create the project. 

In your terminal type in `create-react-app app` when in the root directory of the project. This process may take up to 5 minutes depending on your internet speed.
## Step 1 - Creating our main component
#### Summary
After `create-react-app` has finished, you'll notice we now have a folder named app in the root of our project. Change your directory, using your terminal, to inside of the app folder ( `cd app` ) so we can have access to the pre-defined scripts in the package.json. If we run `npm start` you should see your default browser pop-up and see the react landing page.

![alt text](https://github.com/devlemire/DevMtn-React-Introduction/blob/master/readme/initial-startup.png "Initial Startup")

We are going to start fresh and completely erase inside the return statement in App.js ( public -> src -> App.js ). Your code should look like this:

````jsx
import React, { Component } from 'react';
import logo from './logo.svg';
import './App.css';

class App extends Component {
	render() {
		return (
			<div id='App'>

			</div>
		);
	}
}

export default App;
````