# Rooster Grin Widget Test
Your mission, should you choose to accept it, is to write a simple little widget.   
This widget needs to be deployable as a snippet of code to many different websites that you do not have access to.    
You've been supplied with three separate html files. This widget should work equally well on all three.

### Requirements:
1. This widget should render into the `div` with `id="__schedule"`. 
2. On page load, a small call-to-action button in the bottom left hand corner of the screen, saying something like, 'click me!' is rendered.
3. When the button is clicked, it disappears and a div is rendered on top of the website in the center of the page that says something like, 'I've been clicked!'   
4. Make certain the js you write in widget.js won't conflict with any js that may be written on the site.
5. Deal with edge cases that you are likely to run into, including but not limited:
⋅⋅* Malformed HTML.
⋅⋅* Conflicting javascript
⋅⋅* Old jQuery

Things to think about:
* DO NOT edit the index.html file directly. Feel free to change it programmatically from widget.js, but be gentle.
* Feel free to use jQuery but don't assume it's already loaded on the target website.
* You're welcome to add a stylesheet to style your widget and modal if you like.

This assignment is open ended. Feel free to go beyond the requirements listed but take no longer than 3 hours to complete it.
