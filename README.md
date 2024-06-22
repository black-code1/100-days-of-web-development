# Understanding HTML Elements

- HTML is a "Markup Language"
- `<h1>Hello World!</h1>` HTML Element is made up of HTML Tags and Element Content
- `<h1></h1>` Opening Tag and Closing Tag
- `h1` Element Name
- `Hello World!` Element Content

# Working with "font-size" and "px" - Day-04
- Absolute `px` A device-independent pixel on the screen
- Relative `rem`, `%`

# Styling the Image & Using the Body Tag
- `border-radius: 100px` makes a circle because it is half the width of `width:200px; height:200px`
- `text-align: center` align the content not the element

# A Word About File Name Conventions
There's also one important characteristic which you maybe noticed about all these filenames: They are all lowercase.

And that's important! Whilst it's technically not required, it is a very common convention that you name your files all-lowercase, with no special characters except for dashes (-). If your file name consists of multiple words, you should NOT separate them with blanks (whitespace) but instead use dashes. So use `online-shop.html` instead of `Online Shop.html`.

# Learning Check: More HTML & CSS Features
## What's a "pseudo-selector"?
- A CSS selector like :hover that allows you to set styles for an element that fulfils a certain condition (e.g. the mouse cursor hovers over it).
## Why is it called "Cascading Style Sheets"
- Because more than one CSS rule may apply to the same element.
## What's special about the <img> element?
- It has no content, it's configured with attributes only.
## Which of the following file names would be a good choice for a second HTML file that shows some contact details about the page owner?
- `contact.html`

# Assignment 1: Time to Practice - Your First Challenge! 
You already learned a lot about HTML and CSS - time to test your new knowledge in this assignment!

# Section 3: Diving Deeper Into HTML & CSS
## The Development Server & The Local Website Address
### What Is A "Development Web Server"?
It's a "local development web server" because it's a web server software that serves the website locally, on our machine.
This "web server software" (i.e. the "Live Server" extension in this case) is a software that does actually listen for incoming HTTP requests and send back appropriate responses (that contain the HTML code for example). 

### Understanding Cascading, Inheritance & Specificity
- `Inheritance` (Selected) container rules apply to descendants
- `Cascading` Multiple rules can be applied to the same element
- `Specificity` More specific selector's rule wins over less specific selector

## Theory: Selectors & Combinators
| Selectors                          | Combinators                                             |
|------------------------------------|---------------------------------------------------------|
| Type - element name                | Descendant - li p - All p with li as ancestor           |
| ID - #id                           | child - h2 > p - Only p which are direct children of h2 |
| Group - element name, element name |                                                         |
| Class - .class                     |                                                         |

## Block vs Inline Elements
