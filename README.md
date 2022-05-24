# DOM-JqueryClone
  a simple dom manipulation similar to jquery
  
## Installation 
     npm i @kushii/dom
     
## Getting Started
  1) Start by importing/requiring @kushii/dom as dom
  2) Call dom(selector/dom_element) similar to a query selector

## Added/Simplified Functions
  ### dom()
  the same usecase as jquery $ but can accept dom elements as well
  ### x(cpbm, tblr) and y(cpbm, tblr) 
  as axis with string parameters and returns a number.
      1) cbpm (Size) \
          includes Content Size | Content | Padding | Border | Margin |
      2) tblr (Position) \
          starting at middle of the element (0,0) calculates | Top | Bottom | Left | Right |
  ### css() and animate()
    - works similar to jquery, but added transform functions such as translateX, scale, etc. that accepts a string unit, number, and array of string or number
    - returns a string of style property

## Example Projects
  ### TodoList (GoForIt)
    https://todolist-goforit.herokuapp.com/
    https://github.com/u-Kuro/ToDoList-GoForIt
