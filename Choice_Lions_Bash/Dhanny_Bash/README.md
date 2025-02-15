# Getting Started with Choice NFT

## 

This project was built with a web interface as a gui to ease users to create an NFT. 
The NFT given to the web interface is uploaded to pinata.cloud, an IPFS cloud server that enables us to host our image.
The code is separated into two.
1. The backend - server directory
2. The Frontend - client directory


## Installation on frontend
- Install dependencies with 
	```sh
	$ npm install
	```
	or 
	```sh
	yarn install
	```

- Add the following to the webpack.config.js in node-modules/react-scripts/config/webpack.config.js in the resolve list.  You can search for where fallback was mentioned there you will find the resolve list
	```
	fallback: {
		crypto: false
	},
	```
- After adding that, This is how it will look like 
	```
	resolve: {
		fallback: {
			crypto: false
		}
	}
	
	```
	
- After That run 
	```sh
	$ npm start
	```
	or 
	```sh
	yarn start
	```

## Installation on backend
- Install dependencies with 
	```sh
	$ npm install
	```

	```sh
	$ npm start
	```
	or
	```sh
	$ node app.js
	```



## Available Scripts

In the project directory, you can run:

## Video Preview
https://user-images.githubusercontent.com/33403043/151692597-c97e49a5-8bd0-4518-aef3-96fea4fe00af.mp4


### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.


The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
