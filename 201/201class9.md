# HTML Forms and JS events 

## HTML Forms
[Your First Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)         
[How to Structure a Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

1. Forms are important for web development becasue it is the main way we can communicate and recieve information from the user.
2. An important thing to consider when designing a form is the UI experience. If it is too long or asks for too much it can be offputting. Only ask for the things required.
3. 5 elements of a web form:
  - form: form is the element used to actually create the form
  - label: label is used to , you guessed it, label it
  - input: input is used to define what the input should be (i.e. email)
  - text-area: text area gives a larger area for an input
  - button: button is used for many things, for forms it can be used to submit data by the user.

## JS Events
[Intro to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

1. An even is kind of like your website communicating with your js code. So like when a user hits a button, your website can communicate that to your js.
2. when using an addeventlistener() you must have 2 things, the name of the element, and a function to handle it.
3. the event object can make your code apply to specific items on your page. as in the example given it can make it from the background, to the button color.
4. and event bubble is when you have an event listener on all the elements surrounding the one youre working with and a capture is whenw the browser looks to see if the parent element has any event listeners on it. Mozilla explains it better here:![image](https://user-images.githubusercontent.com/108432978/195640212-1ced8d02-c87d-4df0-91e2-1a228608cd62.png)
