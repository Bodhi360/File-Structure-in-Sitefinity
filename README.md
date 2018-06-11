Here we are going to discuss the file structure of Sitefinity and also some basic tips to keep in mind.<br>
We create the template without Thunder to create the file structure must match:
In App_Data there is folder name Sitefinity > in Sitefinity folder create WebsiteTemplates > Project name > under project name create two folders App_Master and App_Themes > in App_Themes again create project name > this folder contains assets like images, JavaScript, custom CSS, etc.

<b>App_Master</b> contains the html file with .master extension.<br>
App_Themes contains the assets of the project.<br>
Global folder contains CSS and link the file by default to the project.<br>
 
We don’t use the form tag multiple time in .master page, because it hides the publish button on the page.<br>
We use meta data page in App_Master to clean the head tag of master and sometimes head tag does not load the JavaScript file.<br>
In Sitefinity webform technology, use the hybrid template default, but MVC development does not support the webform technology in the project.<br>
Thunder tool help to create web templates, forms designs, etc. It reduces the writing of code.<br>
Try to run the debugger - without debugging, it takes less time to compile the code.<br>
We are trying to create the multiple page so we can change any time without touching another page.<br>
We try to put most of the code in modules, so that we do not need Visual Studio for editing in future.<br>
Sometimes, jQuery files give problem because Sitefinity already has jQuery files so, we put jQuery file in metadata file.<br>


<img src="https://github.com/Bodhi360/File-Structure-in-Sitefinity/blob/master/%20File%20Structure.png">
<a href="http://www.bodhi360.cloud/">Bodhi360</a>
