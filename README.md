Hi!
Here you could find the result set of Udemy Advanced CSS and SASS Courses (Second Project, Trillo)
You can find a demo via the next url:
[https://glareone.github.io/Nexter-FrontEnd-Portfolio-Project-CssGrid-Design/]

CssGrid properties:
![alt text](img/cssGrid_properties.jpg)

Codepen demos, ordering by lectures:
 
a. Lecture 1:
* Basics: [https://codepen.io/Glareone/pen/bXBzMx]

b. Lecture 2, ordering:
* stage 1: [https://codepen.io/Glareone/pen/PMbvye]
* stage 2: [https://codepen.io/Glareone/pen/bXByPz]

c. Lecture 3, spanning items (number of column\row, span, -1):
* stage 1: [https://codepen.io/Glareone/pen/eqBwNJ]
* stage 2: [https://codepen.io/Glareone/pen/QeGXye]
* stage 3: [https://codepen.io/Glareone/pen/zgoVKN]

To start project you could do the next:
1. npm install
2. npm run start

To build the production version of this site you have to use the next script:
1. npm run build:css

Also there are several scripts which are used by "build:css" and "start":
1. "watch:sass" - watch changes in sass files and update their css result file. Used for development purposes
2. "compile:sass": - creates a sass compile file. Used as a start point of build process.
3. "prefix:css": - uses autoprefixer to support different browsers. It works with compiled file from the beginning.
4. "compress:css": - compressing the result file and compilation and prefixing
