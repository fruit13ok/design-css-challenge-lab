# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) CSS Design Challenge Lab (90 mins)

## Learning Objectives
- Use flexbox to set up a grid system.

## Exercise
Pretend you've been hired as a junior developer to update a site with an old layout built with floats. The HTML can stay exactly the same, but the CSS must be changed to meet the requirements below. Be sure to reference the mockups in the 'Deliverables' section for guidance.

#### Requirements
- Change the layout from float to flex.
- Remove any unnecessary CSS without jeopardizing the layout.
- Add media queries to adjust the layout for smaller screens, per the images below.
- Fix any errors (formatting or otherwise) in the HTML and CSS.

#### Starter code
There are two sets of starter code provided: [one with errors](starter-code/with-errors) and [one without errors](starter-code/without-errors). If you're up for a debugging challenge, use the error-based starter code; if you want to focus on the differences between float and flex, choose the starter code without errors. You can always experiment with the error-based code if you finish early!

#### Deliverables
Here are the mockups you should reference while building your site. If you're using the code with errors, this will be a helpful reference for you! The design and layout of the site should not change once you've corrected all code errors and converted from float to flex.

![mockup](assets/mockup.png)

#way 1 change html add a div to wrap main and aside, the big picture is this div only have 2 elements to flex
##1
use without-error
##2
comment out all float (leave the :first-letter float).
comment out clear too
now everything stack on top of each other.
##3
make flex for main and aside.
in html create <div id="mainAsideFlex"> to contain main and aside
    display: flex;
    justify-content: space-between;
in css create #mainAsideFlex
    display: flex;
#way 2 (correct way) only add 3 line to wrapper class, and flex the nav
##1
in wrapper
display: flex;
justify-content: space-between;
flex-wrap: wrap;
