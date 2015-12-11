# Visualize
JS library that utilizes ThreeJS to create audio visualizations that react to the music

*Please excuse my appearance during construction*

~ this version is currently working with pre-set specifications

~ the editable areas will soon be fully functional

1.)  In order to get started with Visualize fork this repo and add it to your project

2.)  In your application's view, add a div with an id called "landingPageAnimationContainer" which will house your audio visualization, a script tag pointing to where the Visualize.js file is located in your project and then another script that calls the Visualize.init() function which takes a string that points to the source of the audio file you want to play.

```
<body>
    <div id='landingPageAnimationContainer'></div>
    <script src="/Visualize/Visualize.js"></script>
    <script>Visualize.init('/audio/V.mp3')</script>
</body>
```

3.) Lastly, you may then call the different "formation functions" which will determine how your audio visualization will look
```
    <script>Visualize.quarterFormation()</script>
```
- squareFormation
- armyFormation
- quarterFormation
- circleFormation
- doubleCircleFormation
