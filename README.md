First steps:

Let's create a new project.

mkdir es6-intro 
cd es6-intro 
npm init -y

npm i webpack-cli webpack webpack-dev-server --save-dev

Note if this fails: 
https://github.com/schnerd/d3-scale-cluster/issues/7
Update your Xcode tools on Mac, kind of a bug.  

Also make sure you have perms to write to your usr/local/lib/node_modules folder (chown -R $USER)

mkdir src (all your js files live here)
touch src/index.js

touch webpack.config.js 

npm i babel-loader @babel/core --save-dev

npm i @babel/preset-env --save-dev

touch .babelrc

https://www.sitepoint.com/javascript-decorators-what-they-are/
