---
title: Day 1!
date: "2020-09-28"
---

As I had learnt React during my time at the coding boot camp I was pretty aware of the basic functionality of what React was. For those who are at a loss as to what React is. Simply put [React](https://reactjs.org/) is a JavaScript library for building user interfaces. However, I like to think of it as a frontend framework as it is solely focused on building the view in our MVC model and solely that. The good thing with React.js is that it is pretty quick and easy to use and many of the applications we use are using React. Day 1 is reminding me of how powerful yet effective React is for building SPA(single page applications)!
Below is a simple component I created :

```<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Hello React</title>
<script src="https://unpkg.com/react@16/umd/react.development.js" crossorigin></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js" crossorigin></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
<style>
#container {
padding: 78px;
background-color: blueviolet;
}
#container h1 {
font-size: 72px;
font-family: cursive;
color: coral;
}
</style>
</head>
<body>
<div id="container"></div>
<script type="text/babel">
var destination = document.querySelector("#container");
class Joanna extends React.Component {
render(){
return <h1> Yo, {this.props.nameTarget}</h1>
}
}
ReactDOM.render(
<div>
<Joanna nameTarget="Steph"/>
<Joanna nameTarget="Diaz"/>
<Joanna nameTarget="Lulu "/>
<Joanna nameTarget="Sam "/>
<Joanna nameTarget="Jeni"/>
</div>,
destination
);
</script>
</body>
</html>

```



