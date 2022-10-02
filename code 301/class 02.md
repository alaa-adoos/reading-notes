# React State and Props
## This class talks about the difference between props and state and how to use them

# React Lifecycle (Links to an external site.)
# Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
### Render happens first.
# What is the very first thing to happen in the lifecycle of React?
## The constructor
## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
## Constructor => Render => React Updates => componentDidMount => componentWillUnmount
# What does componentDidMount do?
## This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions.
## React State vs Props (Links to an external site.)
# What types of things can you pass in the props?
## Props can contain any data type in javascript(strings,objects,arrats….)
# What is the big difference between props and state?
## Props are handled outside the components and must be updated outside the components but state is handled inside the components and can be updated inside the components
# When do we re-render our application?
# When the state changes in the parent component.
# What are some examples of things that we could store in state?
## For a counter or inside a form(input,checkbox,selectbox), things that need to be updated continuously
# Things I want to know more about
## can we connect a React App with db?