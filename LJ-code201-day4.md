#LJ Code 201 - Day 4

##Testing different cases
When testing you code you should always test for 3 cases that we should always test for.

1. Null Value (no input)
2. Single answer (corrrect answer) input
3. Infinite Value (basically every answer that could be wrong)

---
##CSS box model

-boxes are the main core of CSS

-a contatiner is a box that contains another box

-always be careful of the relationship between html and CSS.

- for example declaring which box is the container of the other is laid out in the html and then css is applied accordingly

-content should dicatate the height of the box: if I have 5 lines of text it will be 5 lines high unless I give it a max height, a min height, 

- main point CONTENT DICTATES BOX HEIGHT

-A box has 4 main structures

1. Content: what the box holds.

2. Border: The styling of the edge of the box. 

3. Padding: space between content and border. How you balloon (expands) the size of the element
4. Margin: space between other boxes borders. How you move boxes around

-outline feature: shows you the outline of each border of each box * { outline: 1px;} the * is the select all selector other examples of selectors are p, body, h1, h2, and so on.
- only use this feature to show yourself where your layout is currently at

-Centering content: 

- example: p { text-align: center;}
- example: img { margin 0px auto;}
- margin: 0 px auto is a way the go to way to center content

-Change inline/block:

- p {display: inline;} this would display the p tags side by side instead of above and below



---

##CSS Layout terminology

1. block: this lays out boxes or elements vertically
2. inline: this lays out selected elements horizontally
3. 3 main postioning schemes:

4. normal (static): every element appears on a new line lower down the page than the previous one.

5. relative: moves element out of normal flow either up down left or right of where it would have been placed normally (used more rarely)

6. absolute: out of normal flow, allows you to overlay things on other things VERY DIFFERENT FROM NORMAL & RELATIVE. Used to take something and postition it in relation to it's parent. SO if you have relative parent and then apply an absolute value to its child element, the element will always be where it is declared to be absolutely 

---

##HTML CSS JS Formating Placement
- < head> CSS GOES HERE < /head> 
- < body> STUFF then JS goes VERY LAST < /body> 

---

##JS Functions
- start with function keyword then function name then () then {}
- example: function logNums() { code } 
- functions are just a wrapper around sepcific code that we want to be able to call over and over again
