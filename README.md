# JavaScript30
Course created by  [Wes Bos](https://github.com/wesbos). Here's the challenge 👉 [JavaScript30](https://courses.wesbos.com/account), you can join it for free!
<image src="https://camo.githubusercontent.com/07ca65497065dd926bd889c53b7b7652f8ef3cbc4320739cf7ebed3c4d34cb2d/68747470733a2f2f6a61766173637269707433302e636f6d2f696d616765732f4a53332d736f6369616c2d73686172652e706e67">
  
  Hi there 👋

I created this repository in order to keep track of my progress in the JavaScript 30 Day Challenge and to commit and log what I have learned every day.
  
  # What is JavaScript 30 Day Challenge ? <br>
  It's a 30-day vanilla JavaScript coding challenge. You will build 30 unique projects in 30 days using fun and easy video tutorials.
  You should already know some JavaScript to take on this challenge.
  
 
   # JavaScript 30-Day 1 
   # JavaScript 30-Day 2 
   # JavaScript 30-Day 3 
   # JavaScript 30-Day 4 
   # JavaScript 30-Day 5 
  
   # JavaScript 30-Day 6 

Type Ahead Eyes👀
 
Today I learned about: 
Fetch API 
Getting .json() from fetch response
Array spread operator
Match() function

   # JavaScript 30-Day 7
   # JavaScript 30-Day 8
   # JavaScript 30-Day 9
  14 Must Know Dev Tools Tricks<br>
    // Regular<br>
  <code> console.log('text'); </code><br>
    // Interpolated<br>
    <code>console.log('text with a %s', 'placeholder');</code><br>
    // Styled<br>
    <code>console.log( '%c text styling', background:red);</code><br>
    // warning!<br>
    <code>console.warn('warning message');</code><br>
    // Error <br>
    <code>console.error('error message');</code><br>
    // Info<br>
    <code>console.info('message info');</code><br>
    // Testing<br>
    <code>console.assert(false, 'the word is %s', 'foo');</code><br>
    // clearing<br>
    <code>console.clear();</code><br>
    // Viewing DOM Elements<br>
    <code>console.log(p);
    console.dir(p);</code><br>
    // Grouping together<br>
    <code>console.group();
    console.groupCollapsed()
    console.groupEnd();</code><br>
    // counting<br>
    <code>console.count('Count');</code><br>
    // timing<br>
    <code>console.time('fetching data');</code>
  
 # JavaScript 30-Day 10

   Hold Shift to Check Multiple Checkboxes ☑️

   How it works 👇<br>
   When you click a checkbox, hold Shift, and click another checkbox a few rows down or up, all the checkboxes in between those two are checked.
   BOOM💥😅 Wes style 😉 
  
  TILT:
    
<code>const checkboxes = document.querySelectorAll('.inbox input[type="checkbox"]');</code><br>
   
    
  // Check if they had the shift key down<br>
  // AND check that they are checking it<br>
  <code>let inBetween = false;</code><br>
  <code>inBetween = !inBetween;</code><br>

<code>checkboxes.forEach(checkbox => checkbox.addEventListener('click', handleCheck));</code><br>

  
