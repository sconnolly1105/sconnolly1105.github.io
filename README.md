# sconnolly1105.github.io
List of cool Javascript snippets

<!doctype html>

<html lang="en">

<head>

<meta charset="utf-8">

<title></title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="author" content="S, Connolly" />
<meta name="description" content="" />

<!-- Use Iconifyer to generate all the favicons and touch icons you need: http://iconifier.net -->
<!--
<link rel="shortcut icon" href="favicon.ico" />
-->

<!-- add in any locally defined css file(s)
<link rel="stylesheet" href="css/styles.css">
-->

<!-- add in any locally defined js file(s)
<script src="js/scripts.js"></script>
-->

<!-- locate the following file and include it to stop having to use those annoying vendor prefixes
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
-->

<!-- load Modernizr if required
<script src="https://cdnjs.cloudflare.com/ajax/libs/modernizr/2.8.3/modernizr.min.js"></script>
-->

<!-- local filed
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.2/jquery.min.js"></script>
<script src="http://code.jquery.com/ui/1.11.4/jquery-ui.js"></script>
<link rel="stylesheet" href="http://code.jquery.com/ui/1.11.4/themes/smoothness/jquery-ui.min.css">
-->


<!--
<link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
-->

<script>

function countLines() {
    // var el = document.getElementById("content");
    // var divHeight = el.offsetHeight;
    // var lineHeight = parseInt(el.style.lineHeight);
    // var lines = divHeight / lineHeight;
    var lines = document.links.length;
//    alert (`Line height: ${lineHeight}`)
//    alert (`Number of lines: ${lines}`)
    if (lines > 100) {
      const content = document.querySelector("main");
      content.setAttribute("style", "width: 90%; column-count: 3; column-gap: 27px");
//      content.style.columnCount = "2";
    } else if (lines > 30) {
      const content = document.querySelector("main");
      content.setAttribute("style", "width: 90%; column-count: 2; column-gap: 27px");
//      content.style.columnCount = "2";
    }
}

</script>

</head>

<body onload="countLines();">

<h2 style="text-align: center;">List of items</h2>

<main style="width: 40%">
  <div id="content" style="line-height: 18px;">
    <a href="file:///Users/seanconnolly/HTML%20Examples/Accordian/accordian.html" target="_blank">Jquery-ui Accordian</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/vanilla-accordian.html" target="_blank">Vanilla Accordian</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/alert_box.html" target="_blank">Alert box</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/modal.html" target="_blank">Modal</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/full-modal.html" target="_blank">Full Modal project</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/modal1.html" target="_blank">Modal with no clickable background - fro W3schools.com</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/inheritanceExample.html" target="_blank">Creating Student Objects using Inheritance</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/Cars.html" target="_blank">JS Training - Demo to Voltron about Cars</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/Slider.html" target="_blank">Slider</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/Tabs.html" target="_blank">Tabs</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/twoDimensionarArray.html" target="_blank">Two dimensionsl array</a>
    <a href="/Users/seanconnolly/Desktop/HTML/sets.html" target="_blank">Sets - array that do not include duplicates</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/anchor-to-bottom.html" target="_blank">Anchor text to bottom of HTML page</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/bind.html" target="_blank">Bind</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/chaining.html" target="_blank">Chanining</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/console.log_styling.html" target="_blank">Console styling</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/five-star.html" target="_blank">Create a star using CSS</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/chart.html" target="_blank">Chart software - for Zendesk project</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/list.html" target="_blank">Another version of the chart software - for Zendesk project</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/tables.html" target="_blank">Aliging an image and text in a table</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/telephones.html" target="_blank">Showing the HTML input type="tel"</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/validate-numbers.html"target="_blank">Validate an HTML input fueld to only show numbers</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/testing-undefined.html" target="_blank">Testing undefined - how to test it</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/horserace/index.html" target="_blank">Horseracing game</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/elapsed_time.html" target="_blank">Elapset time</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/Transition.html" target="_blank">Transition effect using CSS</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/HTML_File.html" target="_blank">Guru Curriculum - Samlple HTML file</a>
    <a href="file:///Users/seanconnolly/Documents/Guru%20Curriculum/HTML_Fule_Bare_Bones.html" target="_blank">Guru Curriculium - Bare bonnes HTML file</a>
    <a href="file:///Users/seanconnolly/Documents/Guru%20Curriculum/rooms.html" target="_blank">Guru curriculum - Rooms</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/calcAge.html" target="_blank">Calculate age using javascript</a>
    <a href="file:///Users/seanconnolly/Desktop/Coding/epalsed_time.html" target="_blank">Calculate elapsed time</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/custom-error.html" target="_blank">Throwing a custom error</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/event_bubbling.html" target="_blank">Event bubbling - also called Event propogation</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/safe_code.html"  target="_blank">Safe code - Making code in included files safe do that vatiables don't get stamped on</a>
    <a href="file:///Users/seanconnolly/Downloads/dangerous.html" target="_blank">Dangerous code </a>
    <a href="file:///Users/seanconnolly/Downloads/scope.html" target="_blank">Variable scope - Nested funcions</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/console_table.html"  target="_blank">Console table - Objects using Sean, mairead and kids as objects</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/Objects.html" target="_blank">Objects - This is the something like cars example that I gave to Voltron - Seem to be a copy of Cars below</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/Cars.html"  target="_blank">Cars - This is the example of the session that I went through with Voltron</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/Inheritance.html"  target="_blank">Inheritance - Dogs, Cats, bats, Cheetahs, Humans</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/More%20Objects.html" target="_blank">Another way of creating objects - Create an object within a function and return the object from the function</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/frames.html" target="_blank">Frames - Old technology but this is how they work. frames.html contains frama.html, frameb.html, framec.html</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/closeicon.html"target="_blank">Creating and styling a Button with a close icon</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/line-clamp.html"target="_blank">Truncating a HTML element to x number of lines using <code>-webkit-line-clamp: x;</code></a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/show-image-coordinates/Ireland.html"target="_blank">Showing Coordinates of an image</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/calculate-image-coordinates/calculate-coordinates.html"target="_blank">Calculate the Coordinates of an image</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/image-overlay/image-overlay.html"target="_blank">Add a dark overlay on an image</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/transform.html"target="_blank">Transform - rotating, skewing and scaling elements</a>
    <a href="https://css-tricks.com/almanac/properties/t/transform/"target="_blank">See this site for some good info on the HTML transform tags</a>
    <p>W3schools page explaining all can be found <a href="https://www.w3schools.com/css/css3_animations.asp" target="_blank">here</a></p>
    <a href="file:///Users/seanconnolly/Desktop/HTML/find-index.html"target="_blank">Change the quantity in a line and automatically change the total price</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/jquery-modal.html"target="_blank">jQuery modal examples</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/alert-custom.html"target="_blank">Create a custom alert box with HTML/CSS/JS</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/count-lines.html"target="_blank">Count the lines in a HTML element</a>
    <a href="https://www.youtube.com/watch?v=0hqhAIjE_8I"target="_blank">Youtube video on Accessability - ARIA controls</a>
    <a href="https://www.youtube.com/watch?v=0hqhAIjE_8I"target="_blank">Youtube video on Accessability - ARIA controls</a>
    <a href="https://drive.google.com/drive/u/0/folders/1JI-kQ-wjDEdq6Q7D_UtBEZEjRRf7w_Go"target="_blank">Shopify video on accessibility - Knowlify</a>    
    <a href="file:///Users/seanconnolly/Desktop/HTML/emmet.html"target="_blank">Emmet Shortcuts with videos & Cheatsheets</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/css-grid.html"target="_blank">CSS Grid videos - Wes Boss and another one</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/BeforeAfterPseudoElements.html"target="_blank">::before and ::after CSS Selectors - Cool</a> 
    <a href="file:///Users/seanconnolly/Desktop/HTML/background-image-overlay.html"target="_blank">Add an overlay to a background image</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/red-triangle.html"target="_blank">Add a triangle using only CSS</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/using-unsplash.html"target="_blank">Using Unsplash - Also using ::before and ::after to frame an image</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/font-awesome.html"target="_blank">Using font-awesome - Also box shadows an pulsing elements</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/HTML%20images%20-%20using%20srcset.html"target="_blank">HTML images - using srcset to display difefrent images on desktop and mobile</a>
    <a href="/Users/seanconnolly/Desktop/HTML/validate-form.html"target="_blank">Validate form elements</a> 
    <a href="file:///Users/seanconnolly/Desktop/HTML/aspect-ratio.html"target="_blank">Aspect ratio - new to CSS</a> 
    <a href="file:///Users/seanconnolly/Desktop/HTML/responsive%20header.html"target="_blank">Responsive header and menu - no JS, CSS only</a> 
    <a href="file:///Users/seanconnolly/Desktop/HTML/image-overlay/image-overlay.html"target="_blank">Adding text overlay on an image - Text is centred both horizontally and vertically</a> 
    <a href="file:///Users/seanconnolly/Desktop/HTML/testing_tabnine.html" target="_blank">Testing Tabnine autocompletion in VSCode - also some javascript selectors and event listeners</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/DOM-components-1.html" target="_blank">Web Components & Custom Elements - Card</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/DOM-components-2.html" target="_blank">Web Components & Custom Elements - Word Count</a>
    <a href="/Users/seanconnolly/Desktop/HTML/fetch2.html" target="_blank">Fetch data from external API and display in table</a>
    <a href="/Users/seanconnolly/Desktop/HTML/fetch3.html" target="_blank">Fetch data from a JSON file and insert into table</a>
    <a href="/Users/seanconnolly/Desktop/HTML/trigger.html" target="_blank">Triggering clicks in jQuery and Javascript</a>
    <a href="/Users/seanconnolly/Desktop/HTML/covid-fetch.html" target="_blank">Fetch Covid figures for Ireland</a>
    <a href="/Users/seanconnolly/Desktop/HTML/grid1.html" target="_blank">Grid1 example - basic</a>
    <a href="/Users/seanconnolly/Desktop/HTML/grid2.html" target="_blank">Grid2 example - basic</a>
    <a href="/Users/seanconnolly/Desktop/HTML/grid4.html" target="_blank">Grid4 example - advanced</a>
    <a href="/Users/seanconnolly/Desktop/HTML/grid3.html" target="_blank">Grid3 example - basic</a>
    <p>The Youtube video for this can be found <a href="https://www.youtube.com/watch?v=moBhzSC455o" target="_blank">here</a></p>
    <a href="file:///Users/seanconnolly/Desktop/HTML/invert-colors.html" target="_blank">Invert colours - Find the compliment of a colour</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/css-variables-in-javascript.html" target="_blank">Access CSS variables in javascript</a>
    <p>The Youtube videos for this can be found <a href="https://www.youtube.com/watch?v=HpZbIGFZlwE&t=635s" target="_blank">here</a> and <a href="https://www.youtube.com/watch?v=cZ0yt67A7OM&t=315s" target="_blank">here</a></p>
    <a href="file:///Users/seanconnolly/Desktop/HTML/car_game_original/dataset.html" target="_blank">Accessing an elements dataset</a>
    <a href="/Users/seanconnolly/Desktop/HTML/WesBoss/03-css-vaariables-in-js.html" target="_blank">Wes Bos 03 - Accessing variables in js</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/card-flipping.html" target="_blank">Flipping a card using CSS</a>
    <p>The Youtube video for this can be found <a href="https://www.youtube.com/watch?v=FeJEEE3zc4U" target="_blank">here</a></p>
    <a href="file:///Users/seanconnolly/Desktop/HTML/WesBoss/JavaScript30-master/13%20-%20Slide%20in%20on%20Scroll/css-columns.html" target="_blank">CSS columns</a>
    <p>The Youtube video for this can be found <a href="https://www.youtube.com/watch?v=nJfrThH92WU" target="_blank">here</a></p>
    <a href="/Users/seanconnolly/Desktop/HTML/google-maps.html" target="_blank">Insert a Google Map into a web page</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/tooltip.html" target="_blank">Add a tooltip using ::after pseudo element</a>
    <a href="file:///Users/seanconnolly/Desktop/HTML/recursive-bubble-sort.html" target="_blank">Recursive bubble sort</a>
  </div>

</main>


<style>
main {
  width: 40%;
  margin: auto;
  font-family: Arial;
  font-size: 18px;
}
a {
  display: block;
  padding: 2px 0;
}
p {
  font-size: .85rem;
  font-style: italic;
  margin: 0;
}
p a {
  display: inline;
}
</style>

</body>

</html>
