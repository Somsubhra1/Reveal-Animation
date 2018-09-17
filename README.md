# Reveal Animation
CSS & JavaScript files to help you add revealing animations to your website.
## How do I use it?
Just link the reveal.css and script.js files to your index.html page
```html
<link rel="stylesheet" href="path/to/reveal.css">
<script src="path/to/script.js"></script>
```
then add this wrap your contents (which you want to Reveal animate) in a div tag like this and change the delay to your preference:
```html
<div class="animated animation-LtoR" data-delay="10">
    <h1 class="text-center heading">HEADING</h1>
</div>
```
then change the background-color property of CSS in reveal.css file as shown below: 
```html
.animated.animate-in:before {
    background-color: #d4bd0d; /* Change in-flow color here */
}

.animated.animate-in:after {
    background-color: #202020; /* Change out-flow color here */    
}
 ```
 ## Demo
Click [here](https://rawgit.com/Somsubhra1/Reveal-Animation/master/demo/index.html) for demo.
