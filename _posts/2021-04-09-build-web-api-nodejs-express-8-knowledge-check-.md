---
    layout: post
    title: Build a web API with Node.js and Express 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/build-web-api-nodejs-express/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/build-web-api-nodejs-express.svg">
####  1. What steps must you go through in constructing a Web application with Express?


<i class='far fa-square'></i> &nbsp;&nbsp;Instantiate an app, configure routes, set up middleware, set up error handlers, listen to the server

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Instantiate an app, listen to the server

<i class='far fa-square'></i> &nbsp;&nbsp;Instantiate an app, configure routes, listen to the server

<i class='far fa-square'></i> &nbsp;&nbsp;Instantiate an app, configure routes, set up middleware, listen to the server
<br />
<br />
<br />

####  2. What is the preferred way to send a JSON response from an Express app?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Call the json() helper method on the response object like so: res.json({ content: '' })

<i class='far fa-square'></i> &nbsp;&nbsp;Call res.send({ content: '' })

<i class='far fa-square'></i> &nbsp;&nbsp;Call res.send(JSON.stringify({ content: '' }))

<i class='far fa-square'></i> &nbsp;&nbsp;Use any of these ways: res.type('json'), res.type('application/json'), res.contentType('application/json'), res.format({ 'application/json': function() { res.send({}) } })
<br />
<br />
<br />

####  3. How would set up Express to handle a post request with JSON data?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Call app.use(bodyParser.json()) at the top, register a route by using the post method as in app.post(, () =>{}), read from req.body

<i class='far fa-square'></i> &nbsp;&nbsp;Register a route by using the post method as in app.post(, () =>{}), read from req.body

<i class='far fa-square'></i> &nbsp;&nbsp;Configure body parsing middleware, register a route by using the post method as in app.post(, () =>{}), read from req.data

<i class='far fa-square'></i> &nbsp;&nbsp;Call app.use(bodyParser.urlencoded({ extended: false })) at the top, register a route by using the post method as in app.post(, () =>{}), read from req.body
<br />
<br />
<br />
