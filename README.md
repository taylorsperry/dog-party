# Dog Party
This is the first project I completed at Turing, after the first week of Mod 1. The goal was to match the provided comp as closely as possible and try out a few extensions that incorporated media queries and JavaScript. 

A few challenges I ran into: 

I wrapped "Some Dogs" in a strong tag in the h1, and gave the strong element a fontweight: bold property/value in the CSS, but it doesn't look much "bolder." I tried "boldest" too, as well as a value of 900, but it didn't get any bolder. My guess is that the font-family just doesn't support those values. 

I also struggled with the JavaScript extension. I used querySelector to query the elements "h1" and "button" (with a class of "name-this-dog-button") and store them in variables. Then I added the addEventListener to the button and passed in two arguments: "click" (the event to listen for) and a function that would change the h1 from "A Site About Some Dogs" to "Fido." I see in my Dev Tools that I'm getting an error: "Uncaught TypeError: Cannot read property 'addEventListener' of null at main.js:4" I can't figure out why this is happening, but I guess I at least linked my main.js to my index.html properly!

## Built With:
1. HTML
2. CSS
3. JavaScript

## Screenshot and Comp
Here's the comp we were asked to match: 
<img width="583" alt="dog-party-comp" src="https://user-images.githubusercontent.com/43555476/49345363-ef6c6b80-f640-11e8-9566-1cb04b67aea6.png">

And here's a screenshot of my finished project:
<img width="495" alt="dog-party-screenshot" src="https://user-images.githubusercontent.com/43555476/49345301-255d2000-f640-11e8-964b-95adc9d2c039.png">
