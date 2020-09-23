# Github desktop installation
using the program github desktop is easy as fuck as I recommend this to start with at least, 
cli you can swap to later, when you are feeling confident with the concepts or you need to do something complicated
```
https://desktop.github.com/
```

# Cloning the code
use this link and clone the repository into your github desktop
```
https://github.com/Axeign/jdp
```

# Packages
go to the package.json file and then everything inside the dependancies needs to be installed via npm, example of how it probably looks below
```
{
"name": "jdp",
"version": "0.1.0",
"private": true,
"dependencies": {
"babel": "^6.23.0",
"bootstrap": "^4.1.3",
"cors": "^2.8.5",
"react": "^16.6.0",
"react-dom": "^16.6.0",
"react-redux": "^5.1.0",
"react-scripts": "2.1.1",
"react-tilt": "^0.1.4",
"redux": "^4.0.1",
"scss": "^0.2.4",
"tachyons": "^4.11.1"
},
"scripts": {
"start": "react-scripts start",
"build": "react-scripts build",
"test": "react-scripts test",
"eject": "react-scripts eject"
},
"eslintConfig": {
"extends": "react-app"
},
"browserslist": [
">0.2%",
"not dead",
"not ie <= 11",
"not op_mini all"
]
}
```

## Node.js installation
If you havent installed node.js use this link 
`https://nodejs.org/dist/v12.16.0/node-v12.16.0-x64.msi`
More info found here: `https://www.npmjs.com/get-npm`
This allows you to use npm package manager

## Installing the packages
In the command line (press the windows key and type cmd then enter) and then type `cd <your directory (folder) where the cloned files were saved into>` and press enter
Foreach "dependancy" you need to type `npm install <dependancy name>`
An easier way to install all at once is `npm install`

Afterwards `npm audit fix`, this allows you to fix the security issues of the packages/libraries which you have installed, since the npm install only installs the basic version

(There is a quicker and better way of doing this, but its good practise and doesnt take so long)

## Configuration
- if you choose to install things like extensions for your ide, thats cool, but it makes helping harder sometimes
- its better if you have something like brackets or vsc or phpstorm, so I can see your issues in the ide directly to help

## Running
type `npm start`
and allow the node.js to access the program
you will get information like 

```
Compiled successfully!

You can now view jdp in the browser.

Local: http://localhost:3000/
On Your Network: http://192.168.178.66:3000/

Note that the development build is not optimized.
To create a production build, use npm run build.
```

## Server lag
Copy and paste the local url into chrome (lets all use chrome plz)
username john@gmail.com
password cake
n.b. you have to click on the sign in button, pressing enter wont work

This can take a few seconds because the server needs to start, its not always online atm

## Any questions
Hit me up

