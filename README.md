# React Changing State

## Objectives

1. Practicing updating state in React
2. Practice passing state through props
3. Describe how React rerenders on state changes

## Overview

We want to continue to give students a ton of practice with state changes in
their components. In many ways, this lesson repeats stuff that (at least as the
course is currently laid out) students have already seen. The main focus is on
adding complexity — more nesting, more complicated components (dropdowns,
popovers, etc.) — and giving students a _ton_ of practice.

In this lesson, we could have students build a simple popover component (like
what Medium uses for logging in). It's fairly basic, but it should be easy to
trigger from a bunch of different places (but not as easy as, say, using Flux —
but that comes later).

The `Popover` component can take an `on` prop from its parent component, and the
parent is free to control that prop however it wants.

## Resources

- [React: Communicate Between Components](https://facebook.github.io/react/tips/communicate-between-components.html)
