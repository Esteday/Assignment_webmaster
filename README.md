### Documentation ###

Development documentation is available at https://easetemplate.com/html/coach/docs/index.html.

Template documentation can be found at https://themes.getbootstrap.com/preview/?theme_id=47394

### Getting Started ###

The steps to compile and get started with development are covered in detail in documentation mentioned above, but the summary is:

- npm install -g gulp-cli
- npm install
- gulp

gulp runs a local development server for you to work on. To compile your final code run <i> gulp build </i>
 
### pointers ###
The images can be found in the src/assets/images folder, the new images in the Multimodaal_webmaster_input folder
In order to make changes in the bootstrap theme you can use the sccs framework which can be found in src/assets/scss/_user-variabels. For tips read the documentation.


### The Assignment ###

1. Buttons in header (ik gooi ze weg, ik breng ze terug etc.) can be removed.
2. Update header image to function as a carousel. You can use the new and old picture to do this.
3. Create a news section with : https://www.youtube.com/watch?v=OyhEUIKNgbI and https://www.youtube.com/watch?v=OKfqZZ2uxB0. News section should look like the one
from the visual design located at zorg_landingspagina_medicatieretouren_01.pdf
4. Replace theme color (now yellow) with multimodaal color and style elements. 

5. Create a section where users can book a container as illustrated in aanvraagcontainer.pdf. You may decide on the look and feel.
  There should be a form (presented in a popover or modal) where users can input their information. The form should contain:
   1. Terminal name -> prefill based on selected row.
   2. Company name
   3. Contact person
   4. Phone number 
   5. email adress

   Normally this data would be posted to a backend. For now console.log() the post object on submit. We would like to see you use JQuery to accomplish this. 
6. As the page is a single page scrolling website we would like to scroll to specific sections by using the menu. 
