Inline CoffeeScript allows you to embed CoffeeScript code directly in your HTML. 

CoffeeScripts may be included directly within the browser using <script type="text/coffeescript"> tags. Next, simply include coffee-script.js, and you're all set!  Including the script also gives you access to CoffeeScript.compile() so you can pop open Firebug or any other JS console and try compiling some strings. 

The usual caveats about CoffeeScript apply — your inline scripts will run within a closure wrapper, so if you want to expose global variables or functions, attach them to the window object. 