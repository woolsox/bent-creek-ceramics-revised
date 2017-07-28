# Week One Project
- HTML
- CSS

To Do:

<!-- titles -->

-Home: The home page layout belongs in index.html.
The title for the home page is "Bent Creek Ceramics".
-About: The about page layout belongs in about.html.
The title for the about page is "Bent Creek Ceramics - About".
-Newsletter: The newsletter page layout belongs in newsletter.html.
The title for the newsletter page is "Bent Creek Ceramics - Newsletter".

<!-- considerations -->

-The header/navigation component is always fixed to the top. Contents should scroll behind this component.
-Navigation links at the top should link to the corresponding pages in your project directory (paths may vary for each .html document).
-The currently visited page's navigation link should have an "active" state.
-Use flexbox for grid level layout.
-The text "dedicated environment" in the first paragraph of the about page is an inline link. It should link a user to the "Facilities" section below when clicked.
-The newsletter signup page has a minimum height of the viewport's height.
-The newsletter signup module is centered horizontally and vertically on the page.
-The "Name" input field on the newsletter page should have the type text.
-The "Email" input field on the newsletter page should have the type email.

<!-- bonus -->

-Create and apply a favicon.
-Use CSS only to make navigation links all caps.
-Apply a subtle drop shadow to the bottom of the header.
-Apply a subtle transition duration to hover and focus states
-Apply parallax scrolling to the background image in the "Room to Grow" section on the about page. When scrolled the image appears to stay stationary while the sections above and below scroll over. This can be done with with the css background and background-size properties.
-Add the id nameInput to the name input field in the newsletter page.
-Add the id emailInput to the email input field in the newsletter page.
-Add the id signupButton to the "Submit" button in the newsletter page.
-Include the following code snippet just before the closing body tag (body) in newsletter/index.html:

<!-- PHP SCRIPT FOR FORM
<script type="text/javascript">
  var nameInput = document.getElementById('nameInput');
  var emailInput = document.getElementById('emailInput');
  var signupButton = document.getElementById('signupButton');
  signupButton.addEventListener('click', function(e) {
    var nameVal = nameInput.value;
    var emailVal = emailInput.value;
    if (nameVal && emailVal) {
      alert('Thanks for signing up, ' + nameVal + '. Newsletters will be sent to ' + emailVal);
      nameInput.value = "";
      emailInput.value = "";
    } else {
      alert('We would love for you to sign up, please provide both your name and email address.');
    }
  });
</script> 
-->
