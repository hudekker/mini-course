# Mini Crash Course on Web Development

## Overview

- Web pages have three parts
  - HTML
  - CSS
  - Javascript (JS)
- HTML is the structure of the web page
  - Similar to an outline which has many items at different hierarchy levels
  - Hierarchy levels allow you to control items together for styling
  - HTML is the core of the web page and links to the CSS and JS files
  - HTML stands for "Hyper-Text Markup Language" but everyone just says HTML
- CSS is the styling of the web page
  - Colors
  - Spacing
  - Size
  - Dynamically scale for small to large screens
  - CSS stands for "Cascading Style Sheet" but everyone says CSS
- Javascript (JS) is the programmed action of the web page
  - Button clicks create an event which can trigger a javascript function
  - Keyboard clicks are also events which can trigger a response
  - A page initial startup is also an event which can trigger a function
  - Functions are sections of code that receive a parameters as an input and can generate an output
  - When speaking we say "Javascript" but when writing we often abbreviate it "JS"
  - CSS and HTML are not programming languages but JS is.

## VS Code

- Code editor
- Free
- Many functions such as code completion and code snippets
- Extensions can enhance functionality such as simulating a web page
  - Live Server
  - Material Icon Theme
  - Prettier
- Code completion: finishes the code for you. Example: log, document, selectionQuery
- Snippets: automatically write custom code for you. Example: if2, if3
- Keyboard shortcuts: Saves time and effort. Examples: move line up / down, copy line up / down, multiple cursor

## HTML

- The central controlling document of the web page.
- The HTML page will link to your CSS and JS files
- CSS changes styling on the HTML page
- JS responds to events (clicks as an example) on the HTML page
- Most common tags: h, div, button, ul, ol, li, a, p, img
- Emmet: helps write your html based on simple abbreviations and combinations (div.btn-group > 3\*button.btn)
- Inspect browser to verify your elements

## CSS

- Style your web page by HTML tags, ids, or classes
- Most of the styling is done by classes
- Each line of the HTML can have an ID and a Class but neither is required
- Classes can be used many times on a web page but IDs are unique
- Make a selection and then give it a style
- Most common selection: id, class, tag, combinations: div.class-name, div > p, div p, button:hover
- Most common styles: display, margin, padding, font, color, position
- Inspect browser to fine tune your css

## Javascript

- JS programming is all event-response driven. Example of an event is a click
- JS can read the items on the HTML document and change their class and content
- Example is click on an button and the response is a calculation which gives you an answer.
- Another example is a click which changes the class of an html element (changes color)
- Select an html element, listen for an event on that element, and define a function that executes when that event is triggered
- Most common js terms: selection html element, change html element's class, logic flows (if-else, for loop), functions, variables, log
- Inspect browser to debug your web page

## Project - poppycat

- Create html structure of tags: h, div, img, buttons
- Create css styling: color, display, animation
- Create js actions to work with buttons and clicks, add / removee styling, change text, variable counter
