# landing-page
This project makes use of Flexbox and HTML to build the layout of a landing page

## Pseudo code
1 The first step is to set up the html structure using the boiler plate
2 The project has five sections and therefore the basic structure of the body must contain five divs which will also be flex containers

## 1 Section 1- Navigation bar
* The navigation bar has 6 links- 3 on the right and 3 on the left.
* The first container contains two divisions; one for the left side of the nav and one for the ride side
### Main container
1. display:flex
2. flex-direction:row- to arrange the two containers horizontally along the main axis
3. justify-content -space between: To create space between the two navigation containers
4. height||background-color||font styles|| -the font styles will be inherited by the children
### The mini containers
* Contains the list items. 
* The first one is for links on the right side and the second one for the links on the right side. 
* This section will use the grouping selector since the two containers share the same properties. The next two sections will be used to apply the styles which are specific to the right and left items.
