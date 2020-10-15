

---
title: Day 15!
date: "2020-10-12"
--

It is the beginning of week 3!
Today I will be focusing on React and going over some basics :


With the aim of looking over this things over the week and building a Q&A app over the weekend 

 Use Default Props 
Whereby within React I am able to assign default props to a component meaning I don't have to assign the prop a value when it intially instiate it however I can set the value later as I have done in the code example

``` const ShoppingCart = (props) => {
  return (
    <div>
      <h1>Shopping Cart Component</h1>
    </div>
  )
};
// Change code below this line

ShoppingCart.defaultProps = {
  items: 0
}
`




- Override Default Props
Props can also be overridden if we want to change their value 

``` const Items = (props) => {
  return <h1>Current Quantity of Items in Cart: {props.quantity}</h1>
}

Items.defaultProps = {
  quantity: 0
}

class ShoppingCart extends React.Component {
  constructor(props) {
    super(props);
  }
  render() {
    return <Items quantity ={10} />
  }
};
`

- Use PropTypes to Define the Props You Expect
We can also use proptypes to gauge what type of props we expect whether its a number, a boolean or a string and we can ensure that if we are getting data from an API we can require that the data we are obtaining from the api is only a number or a string or a boolean.

``` itemName.propTypes = {
  props: PropTypes.dataType.isRequired
};
`

- Access Props Using this.props
- Review Using Props with Stateless Functional Components
- Create a Stateful Component
- Render State in the User Interface
- Render State in the User Interface Another Way
- Set State with this.setState
- Bind ‘this’ to a Class Method
- Use State to Toggle an Element
- Write a Simple Counter
- Create a Controlled Input
- Create a Controlled Form
- Pass State as Props to Child Components


[Medium](https://medium.com/@kalemajoanna).
[LinkedIn](https://www.linkedin.com/in/joanna-e-kalema-a5a5b4136/)
[Portfolio](https://joannathedeveloper.netlify.app/)

