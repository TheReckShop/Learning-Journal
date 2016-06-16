#LJ Code 201 - Day 3		

## Rules for Naming Variablies in JS
1. Varaibles MUST NOT START WITH A NUMBER. ALWAYS START WIH A LOWER CASE LETTER
2. The name cannot contain (-) or (.) but uderscores are ok, best practice is to use cammelCase. 
3. You cannot use key words like var, toLowerCase, and others, (list loacted here: http://www.w3schools.com/js/js_reserved.asp)
4. All variables are case sensitive, never start with a capital letter. ALWAYS USE cammelCase 
5. Use descriptive names
6. ALWAYS USE fuckingCammelCase


---
##DATA TYPES
1. Numerica Data Type (numbers)
2. Strings (anything between quations ' ' )
3. boolean (true or flase) ((ture returns as 1 false returns as 2))
4. Arrays: arrayName['sam', 'brian', 'nick', 'nadia'] (namethe the array then use [] and separate each array element is separated by a (,) and then a space)
5. To access an array element type arrayName[element number] (arrays start their element count at 0. So 'nick' is element 2 of arrayName)
5. You can put array within an array, for example array1[1, 2, 3, array2[a, b, c,], 4, 5,] To access element called b of array2 you would do arrayName[3][1]

---
##JS for loops
1.for (counting contidtions) {do these things}
-always seperate counting conditions with (;) not (,)

-example: for (var i = 0; i < varName.length; i++) {
	console.log(varName[i]);
	}  
(varName++ adds 1 to the varName every time the loop is run) 

---
##JS Basics

- basic control flow for JS script: 

mechanism (conditions) {
	do this;
	do that;
	do somemore;
	}
	
example: 

if (3 > 5) {
	console.log('WTF') }
	
- parseInt: takes a string and turn it into a number, if string does not have a number assigned to it, console will return NaN (not a number
	

	
