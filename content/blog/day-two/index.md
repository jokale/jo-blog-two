---
title: Day 2!
date: "2020-09-29"
---

This coding challenge is showing me that sometimes going over ‘basic’ concepts is very important.
Today I was able to look over more things is all about Components, props and styling
For those who don't know, a component is a reusable piece that lives on our user interface or as I like to think of it as :

>a house where all our logic for that specific element on our SPA lives.

Despite having learnt about props I had completely forgotten what props were and if you were like me. A prop is literally short for a property. We can look at a property as if it were an attribute that we pass along to an element however with props were are passing data from a parent component to a child component in order to be able to change the property of the child.
Below is an example a parent component passing a prop to a child component


```class Joanna extends React.Component {
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

```
More is available here: [React compenents](https://reactjs.org/docs/components-and-props.html).

Despite having been taught javascript object styling whereby you create a variable that contains styling elements with JS syntax that can be applied to whatever element is on the page. I found that I prefer styling my SPA with standard CSS. Either or works!
Today was quite simple but the fundamentals of React and good to refresh.

[Medium](https://medium.com/@kalemajoanna).
[LinkedIn](https://www.linkedin.com/in/joanna-e-kalema-a5a5b4136/)
[Portfolio](https://joannathedeveloper.netlify.app/)