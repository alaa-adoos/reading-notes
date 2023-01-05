# Building Your Own Hooks

## Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class

## Extracting a Custom Hook
### When we want to share logic between two JavaScript functions, we extract it to a third function. Both components and Hooks are functions, so this works for them too!

### A custom Hook is a JavaScript function whose name starts with ”use” and that may call other Hooks. For example, useFriendStatus below is our first custom Hook:

## Using a Custom Hook
### In the beginning, our stated goal was to remove the duplicated logic from the FriendStatus and FriendListItem components. Both of them want to know whether a friend is online.
### Now that we’ve extracted this logic to a useFriendStatus hook, we can just use it:
