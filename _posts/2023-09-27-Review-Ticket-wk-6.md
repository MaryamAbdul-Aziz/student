---
layout: post
title: Review Ticket (JS Basics Test)
description: Review ticket (week 6)
type: tangibles
courses: { compsci: {week: 6} }
---


### Summary of Accomplishments

Wednesday:

> Completed HTML Basics 
- Easily created buttons but found button text was yellow
    - Experimented with this and could not change text color no matter what
    - Eventually realized that this was the midnights theme color for links and would not change without changing entire theme 
    - Decided to leave button text as yellow

> Completed JS Basics: Data Types
- Created var 'person' (type: object)
    - Modified as per instructions, changed interests and classes to none
- Did different arithmetic functions with variable numbers
    - Wrote code that I quickly realized was very repetitive and unwieldy. Asked ChatGPT to fix it for me
        - Read through the code and was able to understand every part of the code. However I did not want to be disingenuous so I left my code as the unwieldly code it was
- Wrote 'typeof' code
    - Utilized ChatGPT code from previous task and modified it to my purposes
        - Recognized `var i=0` as the number of the string of the `listofVariables` variable
        - Recognized `i++` as i being increased with each case
        - Made changes to code so that it would print the variable and then `variable + "is a " + typeof variable`

Thursday:

> Completed JS Basics with HTML (DOM)
- Worked a little with ChatGPT in class to come up with basic structure of the code
    - Set variables for link href
    - Wrote a function to switch link href upon clicking a button
    - Fixed function to remove `onclick` and instead moved function to button attributes
- Added some additional features to button
    - Switched both link text and link href
    - Changed button text to say  `Working...` while function was running
    - Tried using import.time to add a delay to make the change look human
        - Used ChatGPT's advice and instead used function within a function, `setTimeout()`
