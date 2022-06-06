# DOM - JqueryClone
  A simple dom manipulation similar to jquery ( [DOM NPMJS](https://www.npmjs.com/package/@kushii/dom) )
  
## Installation 

     npm i @kushii/dom
     
## Getting Started

  1) Start by importing/requiring @kushii/dom as dom
  
  2) Call dom( Selector / Element ) similar to a query selector

## Added/Simplified Functions
    
### 1) x( cpbm, tblr ) and y( cpbm, tblr )

    > As axis with string parameters and returns a number
    
    Parameters    
     1) cbpm ( Size )
     
         > Includes Sizes | Content | Padding | Border | Margin | 
         
     2) tblr ( Position ) 
     
         > Starting at middle of the element ( 0, 0 ) calculates | Top | Bottom | Left | Right | 
         
### 2) css( ) and animate( ) 

    > Works similar to jquery, but added transform functions such as translateX, 
    
      scale, etc. that accepts a string unit, number, and array of string or number
      
      
    > Returns a string of style property  
    
## Example Project

  #### [TodoList (GoForIt)](https://todolist-goforit.herokuapp.com/) - [Repo](https://github.com/u-Kuro/ToDoList-GoForIt)
  
    
