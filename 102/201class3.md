# HTML lists, Control FLow with JS, and the CSS Box Model

## HTML Lists
[Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)       
[Ordered and Unordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

1. Unordered lists should be used when making lists that you dont want numbers in. Additionally you can use it to make menus
2. You can change the bullet style of an unordered list by using css or by giving it different styled attributes.
3. Using an ordered list or an unordered list really depends on which youd prefer. They for the most part can be used interchangeably.
4. similiar to how you change the symbol used in an unordered list, you give it a type attribute. It can be roman numerals etc...

## CSS and the Box Model
[The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
1. Margins push other content away from the content inside the box and can have negative numbers and interact with other margins while padding is used to push the content insdie the box away from the outside and cannot have negative numbers. Im not going to write a story when this is supposed to be my notes to reference in the future.  
2. The outer most element to the box model is the margin. Inside the margin is the border. Inside the broder is the padding. And inside the padding is the content of the box. I think of it as the margin is outside the border and the padding protects the content like a shipping box. 

## JS
[Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)      
[Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators) (this is where the table is from)       
[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)      
[loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)      

1. An array is a single OBJECT that can store multiple VALUES. You can store strings, numbers, objects, and other arrays (oof) inside of arrays. 
2. To access an item in an array you have to use the items index. The index is the number value given in order to the item in an array ex.
array BREAD would be 1 MILK would be 2 CHEESE would be 3 etc.. you can access the array inside another by using another set of brakcets next to the original. Think of it like how our file system is folders in other folders and you have to work down to the one you want. From what I can see the example given is a multidemensional array!
3. There are many shorthand operators. I'm gonna steal the chart from Mozilla because its too good not to.
 ![image](https://user-images.githubusercontent.com/108432978/193985652-cdec6a45-b56f-4e7f-81ec-4aed66a43bbf.png)
4. the result of the example code is the expression (10 + false) + dog
5. A real world example of  conditional like if else would be like how we set up our questions in 102 so that if someone didnt answer the question, or if they answered wrong, it would throw them back to the question again. Could be similar to quizes or tests that give you multiple attempts to do them.
6. Loops are useful for the same example I gave above but an extra layer. If they contrinue to not answer we can keep throwing them back until they get it right instead of just the one time. 
