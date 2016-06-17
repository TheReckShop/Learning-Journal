#Learning Journal 201 Day 5
---

##Reviewed quiz 1

---

##Code Review (JS)
Better to write smallest functions possible. You want to write functions that are as small and as self-contained as possible for debugging purposes later. 

- The reason for this is that is you write a long 47 line piece of code you and its buggy you have a lot more lines of code to evaluate where the error is than if you had 20 or even 10 line function.

Global Variables vs local variables:
never use a variable that doesnt have a var declaration:

- Example: var correctAnswers = 0; correctAnswers= 0 
- always use the former not the later when DECLARING variables. it's fine when calling a variable but not DECLARING A VARIABLE! 

Order of JS flow;
1. declare vars (global)
2. declare functions
3. invoke functions 

---
##CSS and HTML

Divs vs. Sections 

Divs are bettter for internal sectioning 
Setions are better for outer containers 

ID="idName" vs class= "className"

1. ID is one unique item that is declared as idName and is not universal all but is the opposite

2. Class allows universiality to your different sections
 
-Try to use classes over ids when possibe 

Selectors in order of importance to the CSS mechanincs

1. ID (# in css)
2. class (.) in css
3. element (p, h1, h2, etc...)

###CSS BOX MODEL

Order of box model from inside to out

1. Content: images, html, actual visual content
2. Padding: Space between content and border
3. Border: The edge of the box (can be styled)
4. Margin: Space between one border of a div or section and another div or section 

Fixed Positioning vs Float Positioning

How to create something with a fixed postition: You can use top, right, bottom, and left, in relation to fixed postioning 

Floats: Original purpose to have text wrap around iamges, now we use floats to place boxes horizontally

Clear: left; when things start not working because floats are causing you problems

WHEN YOU HAVE FLOAT PROBLEMS PUT A CLEAR: FLOAT; on the box that is having trouble displaying so put in a 

< div class ="clearFix"> < /div>
.clearfix { clear:both; }  

between the two elements that are causing problems

---

##GITHUBS

branches: allows a time stamped version of your code the can be worked on without affecting the code before the new branch

git commands: 

1. git checkout branch-name : moves you to that branch, allows you to swtich between multiple  
2. git checkout -b new-branch-name : creates a new branch called new-branch-name and moves you to that branch 
3. Git pull origin disired-branch: Updates your code to whatever code you want to pull into your code
4. git checkout -b gh-pages : Puts code into deployment branch called gh-pages
5. git push origin gh-pages : deploys you page onto github and this sight's website is listed in your repor under github settings

---

##JS FUNCTIONS
To call a function: 

functionName();

you can call your functions from the console if you want. You can also call it as many times as you want
You can also assign the result of a function to a variable 

return functionToBeReturned; 

-This statement breaks you out of your function and 

   