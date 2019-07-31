Hi!
Here you could find the result set of Udemy Advanced CSS and SASS Courses (Third Project, Nexter)
And also here you could find a lot of simple examples which was made in codepen.
You can find a demo via the next url:
[https://glareone.github.io/Nexter-FrontEnd-Portfolio-Project-CssGrid-Design/]

CssGrid properties:
![alt text](img/cssGrid_properties.jpg)

<details>
<summary><b>Here you could find Codepen demos, ordering by lectures:</b></summary>
a. Lecture 1:
* Basics: [https://codepen.io/Glareone/pen/bXBzMx]

b. Lecture 2, ordering:
* stage 1: [https://codepen.io/Glareone/pen/PMbvye]
* stage 2: [https://codepen.io/Glareone/pen/bXByPz]

c. Lecture 3, spanning items (number of column\row, span, -1):
* stage 1: [https://codepen.io/Glareone/pen/eqBwNJ]
* stage 2: [https://codepen.io/Glareone/pen/QeGXye]
* stage 3: [https://codepen.io/Glareone/pen/zgoVKN]

d. Lecture 4, Grid Challenge:
* Method 1, Line numbers: [https://codepen.io/Glareone/pen/QeGXrj]
* Method 2, Line naming: [https://codepen.io/Glareone/pen/qeRBjV]
* Method 3, Naming Grid Areas:  [https://codepen.io/Glareone/pen/rXjNrm] and with some experiments [https://codepen.io/Glareone/pen/bXgGZd]

e. Lecture 5, Implicit vs Explicit Grids:
* [https://codepen.io/Glareone/pen/wVgBvK]

f. Lecture 6, Align Grid Items:
* [https://codepen.io/Glareone/pen/gVgbmp]

g. Lecture 7, Align Tracks (Grid in container):
*  Stage 1 [https://codepen.io/Glareone/pen/MNJYqG]
* Stage 2, grid-auto-flow: row dense; [https://codepen.io/Glareone/pen/ZgLYZq] 
(to change grid order algorithm and occupy some free space, "NO HOLES")

h. Lecture 8, min-content, max-content:
* Stage 1, min-content and max-content example: [https://codepen.io/Glareone/pen/QedbaZ]
* Stage 2, minmax function with rows: [https://codepen.io/Glareone/pen/BXpNqP]
* Stage 3, minmax function also with columns: [https://codepen.io/Glareone/pen/Xvpbyb]

i. Lecture 9, auto-fit, auto-fill:
* Stage 1, auto-fit and auto-fill: [https://codepen.io/Glareone/pen/EqZjqy?editors=1100]
* Stage 2, replacing elements if all tracks can't be placed in one row: [https://codepen.io/Glareone/pen/MNJaww]
</details>

***To start project you could do the next:***
1. npm install
2. npm run start

To build the production version of this site you have to use the next script:
1. npm run build:css

Also there are several scripts which are used by "build:css" and "start":
1. "watch:sass" - watch changes in sass files and update their css result file. Used for development purposes
2. "compile:sass": - creates a sass compile file. Used as a start point of build process.
3. "prefix:css": - uses autoprefixer to support different browsers. It works with compiled file from the beginning.
4. "compress:css": - compressing the result file and compilation and prefixing