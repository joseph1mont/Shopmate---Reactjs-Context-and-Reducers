# Shopmate (REACTJS - Context and Reducers):

### Screenshot:

![Shopmate1](src/assets/sc1.jpg "Shopmate-Ecommerce1")

## Overview:

useContext: Global State Management use to save state globally (state available globally in our application)
useReducers: Perform actions on Globale state, allow us to manage complex state logic.

![Shopmate2](src/assets/sc2.jpg "Shopmate-Ecommerce2")

### Key Features:

- context = An API given to us by React, allowing for the passing on information to chaild components without the use of Props (see CartContext.js)

- reducer = A pure function, accepting a state & action, and returning a new state (see cartReducer.js)

- action = An object literal, which descrbes a change to state

- useContext = A real hook, allowing functional components to take advantage of the context API (see CartContext.js)

- useReducer = A real hook, used iin place of (useState), generally for more complex state

- dspatch = A function return to us by (useReducer), which sends acton objects to the reducer function
