# JavaScript30
Course created by  [Wes Bos](https://github.com/wesbos). Here's the challenge 👉 [JavaScript30](https://courses.wesbos.com/account), you can join it for free!
<image src="https://camo.githubusercontent.com/07ca65497065dd926bd889c53b7b7652f8ef3cbc4320739cf7ebed3c4d34cb2d/68747470733a2f2f6a61766173637269707433302e636f6d2f696d616765732f4a53332d736f6369616c2d73686172652e706e67">
  
  Hi there 👋

I created this repository in order to keep track of my progress in the JavaScript 30 Day Challenge and to commit and log what I have learned every day.
  
  # What is JavaScript 30 Day Challenge ? <br>
  It's a 30-day vanilla JavaScript coding challenge. You will build 30 unique projects in 30 days using fun and easy video tutorials.
  You should already know some JavaScript to take on this challenge.
  
 
   # JavaScript 30-Day 1 
  ## Javascript Drum Kit 🥁
  ### ✍️ My learnings from this project:
   - key event 
   - transitionend event 
   - ES6 template strings
   
   Methods Learnt:<br>
  ```
  1. addEventListener()
  2. querySelectorAll()
  3. remove()
  4. play()
  ```
  
   ✦```classList``` proprty=>The classList property returns the CSS classnames of an element. It returns a DOMTokenList.<br>
   **Found a very useful tool for finding JavaScript events Keycodes at [keycodes.info](https://keycode.info/)**.<br>
  
   # JavaScript 30-Day 2 
   ## CSS + JS clock 🕓 
  ### ✍️ My learnings from this mini-project:
   - I have learnet about CSS transitions and transform
   - The ES6 **'const'** keyword
   - Live UI update after few seconds
   - **Element.style** for inline styling

   # JavaScript 30-Day 3 
   ## Update CSS Variables with JS☑️
   ✦The goal today was to create an Image editor to control the spacing, color, and blur by modifying CSS variables with JavaScript.
  
   CSS variables explained:
   - spacing
   - base 
   - blur
   ### ✍️ My learnings from this project:
   - How to declare variables in css
   ```
      :root{
      --base: yellow;<br>
      }
      img{
      background-color: var(--base);
  }
   ```
   - Code snippet to select all inputs on the page=> ```const inputs = document.querySelectorAll('.controls input');```
   - **querySelector** gives you a **NodeList**
   - Learnet about **'change'** and **'mousemove'** events
   ```
    Example code:
 
    inputs.forEach(input => input.addEventListener('change', handleUpdate));
    inputs.forEach(input => input.addEventListener('mousemove', handleUpdate));
  ```
   - Learnet about **'dataset'** that can be used to access all data attributes.
    
    
    
   # JavaScript 30-Day 4 
   ## Array Cardio Day 1 💪
    
    ✦This lesson is all about Fundamentals of JavaScript(Array methods).
   ### ✍️ My learnings from this project:
   - Worked with ES6 Arrow functions.
   - Learned about JavaScript array methods:
     - filter() *is like you give 10 things and it return 2.*
     - map() *returns exact same amount of elements as you give it.*
     - sort() *used for sorting elements in some order.*
     - reduce() *allow you to sort of build something on every single one.*
  
    
    
   # JavaScript 30-Day 5 
   ## Flex Panels Gallery 💪
    ✦The image will expand when you click on it and then shrink when you click it off.
    ✦Today's lesson was about making a photo gallery
   ### ✍️My learnings from this project:
   - Primarily focused on CSS flex property.
   - Transitioned on **flex-grow** and **font-size** to expand images. 
   - Used Funtions:
     - toggleOpen
     - toggleActive
 
✦***Best resourse to learn CSS Flexbox:[Flexbox](https://flexbox.io/)***
  
    
   # JavaScript 30-Day 6 
   ## Type Ahead 👀
   ### ✍️My learnings from this project:
   - Fetch API 
   - Getting .json() from fetch response
   - Array spread operator
   - Match() function
                    
   # JavaScript 30-Day 7
   ## Array Cardio 💪💪
   ### ✍️My learnings from this project:
   - Learnet some more Array methods 
     - some()
     - every()
     - find()
     - slice()
     - findIndex()
    
   # JavaScript 30-Day 8
   ## Fun with HTML5 Canvas🎨
   ### ✍️My learnings from this project:
   - Learnet the fundamentals of HTML5 canvas.
   - Build a painting canvas where if you hold down the mouse button and drag, you can paint on it. Something like Microsoft Paint👀
  
   # JavaScript 30-Day 9
   ## 14 Must Know Dev Tools Tricks💡
   ### ✍️My learnings from this project:
   - Learnet how to use developer tools in your browser effectively. 
   - Wes shared some amazing tips and tricks for using the developer tools in your browser.

  All methods explained today👇
  <table style=" background-repeat:no-repeat; width:100%;margin:0;" cellpadding="0" cellspacing="0" border="0">
   <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
        Regular
     </td>
     <td style="height:40px; width:10px; margin:0;">console.log('text')        
     </td>
   </tr>
    <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
        Interpolated
     </td>
     <td style="height:40px; width:10px; margin:0;">console.log('text with a %s', 'placeholder')        
     </td>
   </tr>
   <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
        Styled
     </td>
     <td style="height:40px; width:10px; margin:0;">console.log( '%c text styling', background:red)       
     </td>
   </tr>   
    <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         warning!
     </td>
     <td style="height:40px; width:10px; margin:0;">console.warn('warning message')       
     </td>
   </tr>
        <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         Error
     </td>
     <td style="height:40px; width:10px; margin:0;">console.error('error message')
     </td>
   </tr>
      <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         Info
     </td>
     <td style="height:40px; width:10px; margin:0;">console.info('message info')
     </td>
   </tr>
          <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         Testing
     </td>
     <td style="height:40px; width:10px; margin:0;">console.assert(false, 'the word is %s', 'foo')
     </td>
   </tr>
              <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         clearing
     </td>
     <td style="height:40px; width:10px; margin:0;">console.clear()
     </td>
   </tr>
                  <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         clearing
     </td>
     <td style="height:40px; width:10px; margin:0;">console.log(p)<br>     console.dir(p)
     </td>
   </tr>
                      <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         Grouping together
     </td>
     <td style="height:40px; width:10px; margin:0;">console.group()<br>console.groupCollapsed()<br> console.groupEnd()
     </td>
   </tr>
                          <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         counting
     </td>
     <td style="height:40px; width:10px; margin:0;">console.count('Count')
     </td>
   </tr>
                              <tr style="height:40px; width:450px; margin:0;">
     <td style="height:40px; width:40px; margin:0;">
         timing
     </td>
     <td style="height:40px; width:10px; margin:0;">console.time('fetching data')
     </td>
   </tr>
    
</table>
  
  
 # JavaScript 30-Day 10
 ## Hold Shift to Check Multiple Checkboxes 
 ###  ✍️My learnings from this project: 
  Code Example:
   ```const checkboxes = document.querySelectorAll('.inbox input[type="checkbox"]');```
 - Check if they had the shift key down
 - AND check that they are checking it
  ``` let inBetween = false;
      inBetween = !inBetween;
      checkboxes.forEach(checkbox => checkbox.addEventListener('click', handleCheck));
  ```
  
***✦ How it works:***
 - When you click a checkbox, hold Shift, and click another checkbox a few rows down or up, all the checkboxes in between those two are checked.
   BOOM!! Wes style :D
  
    
    
  # JavaScript 30-Day 11
  ## HTML Video Player 
  ### ✍️My learnings from this project: 
  - learnet some useful tips on customizing HTML5 video player controls. 
 
    
  # JavaScript 30-Day 11
  ##Key Detection
  ### ✍️My learnings from this project:
  - Learnet about Key sequence detection.
  
    
    
  # JavaScript 30-Day 13 
  ## Slide in on Scroll
  ✦ Today we used Javascript to add the Slide-In-On-Scroll functionality to a pre-built page.
  ✦ As you scroll down, images slide in from the right or left sides of the page.
  ### ✍️ My learnings from this project:
  - Learnet about JavaScript ```debounce`` fuction
    - The overhead of a function can be reduced by preventing it from being called repeatedly. This will help to speed up the website.
  
  Sample Code:
  ```
      function debounce(func, wait = 20, immediate = true) {
      var timeout;
      return function() {
        var context = this, args = arguments;
        var later = function() {
          timeout = null;
          if (!immediate) func.apply(context, args);
        };
        var callNow = immediate && !timeout;
        clearTimeout(timeout);
        timeout = setTimeout(later, wait);
        if (callNow) func.apply(context, args);
      };
    };
  ```
    
    
  
  # JavaScript 30-Day 14 
  ##
  ### ✍️My learnings from this project:⤵️ 
  
  # JavaScript 30-Day 15 
  ##
   Today's Challenge is about 2 main things:
         1.Local Storage
         2.Event Deligation

   ### ✍️My learnings from this project:⤵️ 
      =>e.preventDefault(); // stops the page from reloading.<br>
      =>JSON.stringify(items) // When you pass items it's going to convert your objects and arrays into a JSON string.<br>
      =>JSON.parse() // take items from the string and put it back into form whatever it was initially.<br>
      =>If you addEventListner() on something that doesn't't exist, you'll know that in future it won't be clicked.<br>
  
  # JavaScript 30-Day 16 
  ##
    Day-16 is about adding shadow with <code>'mousemove'</code>.
  ### ✍️My learnings from this project:⤵️ 
    

  # JavaScript 30-Day 17 
    Day-17 is about using 'array.sort()' to sort a list of band names without 'Articles'.
  ##
  ###  ✍️My learnings from this project:⤵️ 
  
    
  # JavaScript 30-Day 18 
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 19
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 20 
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 21 
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 22 
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 23 
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 24
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 25 
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 26 
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 27
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 28 
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 29
  ##
  ### ✍️My learnings from this project:⤵️ 
    
    
  # JavaScript 30-Day 30 
  ##
  ### ✍️My learnings from this project:⤵️ 



  
