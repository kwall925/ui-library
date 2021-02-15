use this as a guideline of how to build docs:
http://getskeleton.com/

create all components in seperate files.

container: make repsponisve similar to bootstrap.
-define color, hover, and border-radius

h1-h6 : define color

Begin Documentation:
-write exactly what must happen for a user
to use a component

example
  https://blissful-carson-ae867f.netlify.app/

Bootstrap components
https://getbootstrap.com/docs/4.5/components/alerts/

import font in css; cannot be used in html in this
scenario

view class

navs
- To use a nav bar, call the .mo-nav class. The navbar uses
flexbox to automatically space content evenly, and the width
will adjust based on the amount of content inside.
-calling .nav-red will format the links to be red to provide
an alternate look

dropdowns
-wrap all dropdown code inside of .dropdown class
-call .dropbtn on the link where the dropdown items will begin
-add a div with class .dropdown-content, and include links inside

<embed code snippet>

cards
-start by calling the .card-main class, which will
constitute the entire card
-the image goes next, and should have an attached
.card-img class to ensure proper fitting
-for the text content, call .card-conatiner to
hold it, and .card-sub for any small text within

<embed code snippet>

buttons
-use .main-btn or btn-red

<embed code snippet>

forms
-call .main-form. Labels and
inputs will be styled by default.
-the form container will grow to
accomodate content
-custom checkboxes and radio buttons
will be coming soon.
