# ember-typescript-giphy

## Outline of the project
Pre: Build a page that returns the trending gifs on giphy.
<pre>
This page will have different "modes" 
    Modes 
  1) Grid 
     This is the default view that the api examples shows 
  2) Carousel Mode 
     Probably using webgl
 </pre>
 
**Components**
Breaking the components into smallest elements ensures extensisbility. 
<pre>
  1) Image Content
  2) Grid 
</pre>

## Ember Notes 
Firstly, development using ember is speed up using templates via the ember cli. 
### Routes 
**The Generate Route command**
By generating a route using the cli, ember craetes a file in the "/templates" and "/routes" folder. The cli command is i.e. (ember generate route scientists) which generates a file in scientists in both folders. 
1) Routes contains data that is used in the templates file and it is exported as a model. (This file is a js file) 
2) Templates contains the html code which is responsible for populating the dom using the model passed from the routes (This is a hbs file) 


**The Generate Component command**
This command generates a file in the components folder ( hbs file ) which is then passed into the file created in the template. A good practice would probably be having multiple components which are then imported as components in the template file. You would pass the model that from the templates file to the component file which was originally passed from the routes files. 
<pre> 
  {{yield}} takes in child props passed from the parent 
</pre>

**Auto-testing with ember**
<pre>
1) Acceptance test 
   a) "We can put our automated test into motion by running the test server using the ember test --server command, or ember t -s for short."
</pre>
