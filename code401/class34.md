# global state with React

## Role of the global state
### In React, originally, the state is held and modified within the same React component. In most applications, different components may need to access and update the same state. This is achieved by introducing the global states in your app. The main purpose of the global state is to share a state among multiple components.

### There are three ways this communication can happen:

- With a child component
- With a parent component
- With a sibling component
- State traveling down
- State traveling down through the hierarchy is best managed using the mutable state at the highest level to determine immutable properties that define the lower-level components. Even when these properties are updated, the lower-level component is updated rather than fully recreated.

## Context
### Context provides a way to pass data through the component tree without having to pass props down manually at every level.

### In a typical React application, data is passed top-down (parent to child) via props, but such usage can be cumbersome for certain types of props (e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.
