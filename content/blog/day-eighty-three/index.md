---
title: Day 83!
date: "2020-12-23"
---

Today I will be going over : 
- React Testing Cookbook (which is quite fitting as I stumbled upon it yesterday)
- Add routing to React apps using React Router v4
- Recap Container components

I have decided to stay away from hooks (I know they can be used sometimes) but I prefer my class set up. If it isn't broken don't fix it unless its super quick and easy! 
I will also still continue to build my landing page fix it up with some styling and pick a new font!

#### Updates:

###### Testing

Up until now I didn't realise how important testing was, I thought I could just code away (even the fun projects) and not have any tests and the code be fully functional with no errors popping up. Great code or so I thought. I have actually been writing legacy code which is simply code that doesn't have any tests, code that cannot be refactored but simply changed which is exactly what I have been doing where I thought I was refactoring :(. 

###### Why testing your code is actually important?

In order to have the best, clean and efficient code you need to test that everything works as it should layer deep and not just the superficial level. I am guilty of writing ugly code that works on a superficial level but deep down it isn't the most effecient way of fixing an issue. In addition to this it teaches you how to debug your own code and find a multitude of ways to solve a problem.
Heres a [great article] (https://dev.to/flippedcoding/its-important-to-test-your-code-3lid) outlining the importance of testing.

###### Different test runners 
A test runner is basically something that allows you to build test suites and run them. 
There are different test runners for whatever lanaguage/framework you are using.
Below are a few test runners that work hand in hand with React like:
- Jest (which is actually built into Create React App which makes React 1000x better)
- mocha
- ava
- expect

Moving forward I will try my hand at writing tests in Jest line by line and I wonder if its better practice to write tests before writing up your code or afterwards?


[React testing](https://reactjs.org/docs/testing.html)


###### What is React Router 

 React Router is the standard routing library for React which basically means it allows us to create different routes to different routes in our project 

 ```

export default function BasicExample() {
  return (
    <Router>
      <div>
        <ul>
          <li>
            <Link to="/">Home</Link>
          </li>
          <li>
            <Link to="/about">About</Link>
          </li>
          <li>
            <Link to="/dashboard">Dashboard</Link>
          </li>
        </ul>

        <hr />

        {/*
          A <Switch> looks through all its children <Route>
          elements and renders the first one whose path
          matches the current URL. Use a <Switch> any time
          you have multiple routes, but you want only one
          of them to render at a time
        */}
        <Switch>
          <Route exact path="/">
            <Home />
          </Route>
          <Route path="/about">
            <About />
          </Route>
          <Route path="/dashboard">
            <Dashboard />
          </Route>
        </Switch>
      </div>
    </Router>
  );
  ```

  Above is an example of how it looks courtesy of [React Router example](https://reactrouter.com/web/example/basic)!


  To get a better understanding of Routing check below out [React Router philosophy](https://reactrouter.com/web/guides/philosophy)






##### My links 
[Medium](https://medium.com/@kalemajoanna).

[LinkedIn](https://www.linkedin.com/in/joanna-e-kalema-a5a5b4136/)

[Portfolio](https://joannathedeveloper.netlify.app/)


