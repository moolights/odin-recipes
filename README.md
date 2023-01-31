# odin-recipes

For this project, three bare-bones recipe pages have been created and linked to a main page. 
From the main page, users are able to select a link that will direct them to the corresponding 
recipe.

During this project I encountered a few bugs:

1. When creating the omelette.html and chicken-parm.html, they were intitally placed in the main file directory not the recipes directory. After directing to the page from index.html, I was face with a blank webpage after edits. This was due to duplicate .html files and pointing to an unedited file.

2. On the omlette.html webpage, I wrote the image src as "..images/omlette.jpeg". This was creating a broken image link on the webpage when loaded. The error come from a missing back slash ("..images" is not a directory).
The fix was "../images/omlett.jpeg".