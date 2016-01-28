# [react-redux-starter-kit](https://github.com/cloudmu/react-redux-starter-kit)

Yet another React and Redux based web application starter kit. [Demo](http://ec2-52-10-209-45.us-west-2.compute.amazonaws.com/)

### Overview

This is yet another React and Redux based web application starter kit. However, this one attempts to go beyond the typical simple boilerplates, by showcasing several great technologies (such as [React](https://github.com/facebook/react), [Redux](https://github.com/gaearon/redux), [React-Router](https://github.com/rackt/react-router), [Fixed-Data-Table](https://github.com/facebook/fixed-data-table), [Bootstrap](https://github.com/twbs/bootstrap), [Babel](http://babeljs.io), [Webpack](http://webpack.github.io)) and [JWT](https://jwt.io)) used together to develop a more complex web application, with features such as authentication, navigation, asynchronous data fetching, error handling, caching and pagination, etc.

### Install and Run the Dev Server

```
npm install
npm start
```
Then open http://localhost:3000

### Build and Run the Production Server

```
npm run build
NODE_ENV=production PORT=80 npm start
```
Then open http://localhost


### Demo
A demo of this web application is running on a free [Amazon EC2 Micro Instance](http://ec2-52-10-209-45.us-west-2.compute.amazonaws.com/), with very limited resources.


### Feature highlights

* Best React practice by [separating "smart" and "dumb" components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
* Async Data fetching with caching and pagination
* Data fetching error handling
* Authentication and Page Restrictions (based on JWT)

### Dependencies

* React
* Redux
* React Router
* JSON Web Tokens (JWT)
* Fixed-Data-Table
* style-loader
* Bootstrap
* Express
* Babel
* Webpack

### Credits

As a long-time backend developer (who writes obscure number-crunching "optimzation" and "analytics" algorithms in Java), I would never have thought of developing (let alone posting) a web application using javascript on Github, were it not for the fateful summer 2015 when I stumbled upon a 30 minutes [video](https://www.youtube.com/watch?v=xsSnOQynTHs) by [Dan Abramov](https://twitter.com/dan_abramov), and his inspiring work on [Redux](https://github.com/rackt/redux).

Thank you! 
