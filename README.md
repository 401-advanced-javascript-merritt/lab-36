# lab-36

[Part One Link](https://codesandbox.io/s/pw5klw4wvm)

[Part Two Link](https://codesandbox.io/s/ll6973k4n7)

### Components:
Part 1: 
* app-counter.js:
  * Render a h2 with the current count.
  
* incrementer.js:
  * Render a button that increases the count.

* decrementer.js:
  * Render a button that decreases the count.

* counter-context.js:
  * Render the context provider and give access to context to all children (App).

Part 2:
* counter-context.js:
  * Render the context provider and give access to context for all components.
  
* counter.js:
  * Render a h2 with the context of the counter.
  
* form.js: 
  * render a form that calls the context handleInput on change.
  
* if.js:
  * accept a condition and render depending on the children.
  
* list.js:
  * Render an unordered list that maps througyh the todolist context. Each item is a ist item and gets the specific value mapped to it.
  
* todo.js:
  * Render the form and list components.

### Modules:
Part 1:
* counter-context.js:
  * increaseCounter: increase the counter by 1.
  * decreaseCounter: decrease the counter by 1.

Part 2:
* counter-context.js:
  * increaseCounter:
    * increase the number of items in the list
  * decreaseCounter
    * decrease the number of items in the list
  * handleInputChange
    * when the input for value changes, set the state of the context to match.
  * addItem:
    * add a new item to the to do list array in the context state
  * updateItem:
    * when an item is updated, change the current value in the context state to match
  * toggleComplete:
    * if the user submits an edited form, save it.
  * saveItem:
    * save an item to the context state after it has been updated.
  * toggleEdit:
    * If the user is editing a form instead of creating a new item, change the state of editing.

### UML:
Collab with Billy Bunn

![UML](https://i.imgur.com/DbAPSgv.jpg)
