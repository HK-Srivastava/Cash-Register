# Cash-Register
A beginner level JavaScript project to calculate change due (in coins and bills) based on the available cash in drawer, price of item and payment recieved.

## Task
Design a cash register drawer function that accepts purchase price as the first argument (price), payment as the second argument (cash), and cash-in-drawer (cid) as the third argument, where cid is a 2D array listing available currency. The checkCashRegister() function should always return an object with a status key and a change key.
  - Return {status: "INSUFFICIENT_FUNDS", change: []} if cash-in-drawer is less than the change due, or if you cannot return the exact change.
  - Return {status: "CLOSED", change: [...]} with cash-in-drawer as the value for the key change if it is equal to the change due.
  - Otherwise, return {status: "OPEN", change: [...]}, with the change due in coins and bills, sorted in highest to lowest order, as the value of the change key.

## Programing concepts utilized
  * ES6
  * Data Structures 
  * Object Wrappers for String & Array
  * Functional Programming
  * Object-oriented Programming
  * Debugging
  
## Technologies used
  * JavaScript
