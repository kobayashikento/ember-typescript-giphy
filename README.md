# ember-typescript-giphy

## Outline of the project 
1. Query the giphy API and return a listing of the first page of trending gifs.
2. Include information for the gifs you think would be useful
3. Make sure what you build is extensible, you might be asked to change it.
4. The specific UI is up to you. Bonus points for awesome stuff you bake into the app.
5. Provide specific instructions for installing. For example, if you are using a library,
please call that out, so we know to install them.
6. Build it using a JavaScript Framework of your choice.
7. Testing is something SoapBox takes seriously. You should too.


## Ember Notes 
Firstly, development using ember is speed up using templates via the ember cli. 
### Routes 
**The Generate Route command**
By generating a route using the cli, ember craetes a file in the "/templates" and "/routes" folder. The cli command is i.e. (ember generate route scientists) which generates a file in scientists in both folders. 
1) Routes contains data that is used in the templates file and it is exported as a model. (This file is a js file) 
2) Templates contains the html code which is responsible for populating the dom using the model passed from the routes (This is a hbs file) 


**The Generate Component command**
This command generates a file in the components folder ( hbs file ) which is then passed into the file created in the template. A good practice would probably be having multiple components which are then imported as components in the template file. You would pass the model that from the templates file to the component file which was originally passed from the routes files. 
