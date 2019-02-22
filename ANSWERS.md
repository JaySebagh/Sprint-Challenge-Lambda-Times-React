What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

PropTypes validates the data being passed as props when your component is being built. For example, this allows you to make sure your components are receiving a number instead of a string.
If your components gets passed in data that it doesn't anticipate, it can create problems.





 Describe a life-cycle event in React?

A lif-cycle refers to a component. The three parts are:
Mounting = birth --> constructor, props/state, render, componentDidMount
Updating = growth --> new props in parent updates to the child, mutate the state with this.setState, componentDidUpdate
Unmounting = death --> clean up stuff from DOM that doesn't need to be there once component is done

The mounting is when the component is built, the updating is when something gets changed, and the unmounting is when it gets removed from the page.





 Explain the details of a Higher Order Component?
 
HOC takes in a component as an argument and returns a new component. This lets you reuse functionality from components without repeating yourself. Good for large scale projects with a bunch of components to manipulate.





 What are three different ways to style components in React? Explain some of the benefits of each.

- CSS Stylesheet
Separate file for CSS that you can import. Everything is stored in a unique file, then brought in.

- Inline Styling
Quick/basic styling

- Styled Components
Uses JavaScript and CSS to create CSS directly in Javascript. Reusable.