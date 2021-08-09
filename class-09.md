#  html
## Chapter 7: Forms

HTML borrows the concept of a form to refer to different 
elements that allow you to collect information from visitors to 
your site 


HTML forms give you a set of elements to collect data from 
your users. In this chapter you will learn


### Form Controls
There are several types of form controls that 
you can use to collect information from visitors 
to your site
#### For add text
1.Text input (single-line)
Used for a single line of text such 
as email addresses and names.

2.Password input
Like a single line text box but it 
masks the characters entered

3.Text area (multi-line)
For longer areas of text, such as 
messages and comments

#### For Making Choices
1.Radio buttons
For use when a user must select 
one of a number of options.

2.Checkboxes
When a user can select and 
unselect one or more options

3.Drop-down boxes 
When a user must pick one of a 
number of options from a list

#### For Submitting Forms
1.Submit buttons
To submit data from your form 
to another web page

2.Image buttons
Similar to submit buttons but 
they allow you to use an image.

3.File upload
Allows users to upload files 
(e.g. images) to a website


### How Forms Work
1.A user fills in a form and then presses a button 
to submit the information to the server
2.The name of each form 
control is sent to the 
server along with the 
value the user enters or 
selects
3.The server processes 
the information using a 
programming language 
such as PHP, C#, VB.net, 
or Java. It may also store 
the information in a 
database

4.The server creates a new 
page to send back to the 
browser based on the 
information received

#### Form Structure
`<form>`
Form controls live inside a 
`<form>` element. This element 
should always carry the action
attribute and will usually have a 
`method` and id attribute too.
`action`
Every `<form>` element requires 
an action attribute. Its value
is the URL for the page on the 
server that will receive the 
information in the form when it 
is submitted.
method
Forms can be sent using one of 
two methods: get or post.
With the get method, the values 
from the form are added to 
the end of the URL specified in 


#### The input Element 
#### The input element

The `<input>` element is used to create various form controls. The value of the type attribute determines what kind of input they will be creating.

 `type="text"` -When the type attribute has a value of text, it creates a singleline text input.
 `type="password"` - single-line text input, except the characters are blocked out. They are hidden out.
 
 `<textarea>`- element is used to create a mutli-line text input. Unlike other input elements this is not an empty element. 
`type="radio"` - Radio buttons allow users to pick 
just one of a number of options.
 



 # Chapter 14: Lists, Tables , Forms
 
 ### List Style 
 ##### Unordered Lists
For an unordered list you can use 
the following values:
- none
- disc
- circle
- square
###### Ordered List 
For an ordered (numbered) list 
you can use the following values:
- decimal
1 2 3
- decimal-leading-zero
01 02 03
- lower-alpha
a b c
- upper-alpha
A B C
- lower-roman
i. ii. iii.
- upper-roman 
I II II


### Table style

#### Table Properties

- width to set the width of the table
- padding to set the space between the border of each table cell and its content
- text-transform to convert the content of the table headers to 
- uppercase
- letter-spacing, font-size to add additional styling to the content of the table headers
- border-top, border-bottom to set borders above and below the table headers
- text-align to align the writing to the left of some table cells and to the right 
- background-color to chan

# Chapter 6 Event 
### Event handling.
1.Select t he element 
node(s) you want the 
script to respond to.

2-Indicate which event on 
the selected node(s) will 
trigger the response. 

3-State the code you want 
to run when the event 
occurs.


### THREE WAYS TO BIND AN EVENT TO AN ELEM ENT

#### TRADITIONAL DOM EVENT HANDLERS 
All modern browsers understand this way of creating an event handler, 
but you can only attach one function to each event handler.

`element.onevent = functionName;`

#### EVENT LISTENERS 
Event listeners are a more recent approach to handling events. 
They can deal with more than one function at a time 
but they are not supported in older browsers.
`element.addEventlistener('event', functionName, Boolean)` 