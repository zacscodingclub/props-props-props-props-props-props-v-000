# Props Props Props Props Props Props

## Objectives

1. Explain the role that props play in a React application
2. Explain why props are preferable to state
3. Explain how we can design components with minimal complexity using props

## Overview

This lesson hopes to really get students on the props train. It's not that state
is bad — state in React lets us do a lot of things quickly in ways that are
still easy to understand and reason about. But state adds a little conceptual
overhead inside of each component.

Props are purely declarative. So if we can move state to the edges of our
application — say, only updating a parent view and passing the state down as
props to child components — we can greatly reduce that complexity (and make
our components dead-simple to test).

This is one of the main ideas behind `connect()` (previously, `@connect()`)
in Redux: we can abstract away state management so that we're only dealing
with props. We still don't quite want to introduce students to flux or Redux
quite yet, but we want to get them a bit closer.

We can code-along a simple abstraction layer that achieves the above-described
functionality with callbacks (or actions, since students know about those).

## Resources

- [Thinking in React](https://facebook.github.io/react/docs/thinking-in-react.html)
- [Props vs. State](https://github.com/uberVU/react-guide/blob/master/props-vs-state.md)
