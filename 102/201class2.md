# Basics of HTML, CSS, and JS pt.2

## HTML
[Intro to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)     
[HTML text Fundementals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)          
[HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)           
1. Semantics are important in HTML to give meaning to the code we are working on and the contents within. It also helps other devs be able to more easily read it.
2. There are 6 headings levels H1-H6 decreasing in size as the # gets higher
3. Subscript and Superscript are used for things like chemical equations and dates. Subscript brings letters or numbers down for things like chemicals and superscript brings it up for things like dates.
4. the abbr  tag or abbreviation tag is used for screenreaders and such to be able to define a term. To full expand the definition you must use a Title attribute.

  
## CSS
[How CSS is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured) 
1. CSS can be applied to HTML documents by linking the .css file using the <link  tag, inline styling, or using the <style  tag inside the html doc
2. In general, best practice is to use a seperate .css file. It keeps the css code contained and better organized and also keeps the html doc as simple and clutter free as possible. Ultimately it makes things easier to find and fix.
3. Using the example given:		   
	   h2 {
     color: black;
     padding: 5px;
   }
	
	1. the selector here is the H2 element
	2. the declarations are the properties combined with the value
	3. the properties are the color: and padding:
	
## JS
[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
1. A string is data enclosed in (I think) single OR double quote marks. These can be used together to keep things from breaking (i.e. Quotes *INSIDE* quotes)
2. There are many operators. the main ones are 
	1. + for addition, - for subtraction * for multiplying, and / for division
	2. + means assignment
	3. === means strictly true
	4. !== means Not or Does not equal
3. Functions would be critical for programming a calculator.
	### Conditionals
[Making decisions in your code- conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)																																																													 
![image](https://user-images.githubusercontent.com/108432978/193743294-7a5b86e0-2cca-46bb-a3c6-b227208daf37.png)		      
1 isnt even raising a question? Its just a blanket statement?	          				  				  		  
2. else if is an extention of if else but it allows for more than 1 other outcome. 
3. List of comparison operators
		1. === strictly equals
		2. !== does not equal
		3. < less than
		4. > greater than
		5. <= less than or equal to
		6. >= greater than or equal to
4. && returns true if both operands are true and || returns false if both are false
