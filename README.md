## Introduction

This repository contains an interactive timers game written in React and intialised using Vite. You must start the timer and aim to stop it at exactly the target time. However, if you fail to stop the timer before the time runs out and you score nothing!

## Initial set up

- Run `npm install` to install dependencies.
- Run `npm run dev` to run the development server.

## Concepts used

- `useRef` - track and interact with DOM elements where state is not involved
- `forwardRef` - share a ref between a parent and a child component
- `useImperativeHandle` - expose chosen properties to outside of a component
- `createPortal` - move an element, such as a Modal, to a more convenient place in the DOM
