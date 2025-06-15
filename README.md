# Learn CSS (Cascading Style Sheets)       

## What is CSS?              
### CSS stands for Cascading Style Sheets.  It's a computer language specifically used to style and layout web pages.  Imagine CSS as the makeup for websites!  It allows you to change the fonts, colors, and layout to create a visually appealing website.


## Here are some familiar terms to get you comfortable before starting CSS:         

1. CSS (Cascading Style Sheets): A language used to describe the style of HTML documents.
2. Selector: The part of a CSS rule that specifies which HTML elements the styles apply to.
3. Property: An aspect of the HTML element you want to change, like color or font size.
4. Value: The setting you want to apply to the property, like "blue" or "16px".
5. Declaration: A combination of a property and a value.
6. Declaration Block: A group of declarations enclosed in curly braces.
7. Rule: A selector followed by a declaration block.
8. Inline Style: CSS written directly in the HTML element using the style attribute.
9. Internal Style Sheet: CSS written inside a `<style>` tag in the head of an HTML document.
10. External Style Sheet: CSS written in a separate .css file and linked to the HTML document.
11. Class Selector: A selector that targets elements with a specific class attribute, starting with a dot (.).
12. ID Selector: A selector that targets an element with a specific ID attribute, starting with a hash (#).
13. Element Selector: A selector that targets all instances of a specific HTML element.
14. Universal Selector: A selector that targets all elements, represented by an asterisk (*).
15. Attribute Selector: A selector that targets elements with a specific attribute.
16. Pseudo-class: A keyword added to selectors that specifies a special state of the selected elements, like :hover.
17. Pseudo-element: A keyword added to selectors that style a specific part of the selected elements, like ::before.
18. Inheritance: The mechanism by which some CSS properties applied to a parent element are inherited by its children.
19. Specificity: The rules that determine which CSS rule is applied when multiple rules match the same element.
20. Cascade: The order in which conflicting CSS rules are applied, based on specificity, origin, and importance.
21. Box Model: The model that describes the rectangular boxes generated for elements, including content, padding, border, and margin.
22. Content: The actual content of the HTML element.
23. Padding: The space between the content and the border of an element.
24. Border: The edge around the padding and content of an element.
25. Margin: The space outside the border of an element.
26. Width: The width of an element's content area.
27. Height: The height of an element's content area.
28. Max-width: The maximum width of an element's content area.
29. Max-height: The maximum height of an element's content area.
30. Min-width: The minimum width of an element's content area.
31. Min-height: The minimum height of an element's content area.
32. Display: Determines how an element is displayed on the page, like block, inline, or flex.
33. Inline: An element that does not start on a new line and only takes up as much width as necessary.
34. Block: An element that starts on a new line and takes up the full width available.
35. Inline-block: Like inline, but allows setting width and height.
36. Flexbox: A layout model for arranging elements in a flexible way.
37. Grid: A layout model for creating complex, responsive web layouts.
38. Float: A property that makes elements float to the left or right, allowing text to wrap around them.
39. Clear: A property used to control the behavior of floating elements.
40. Position: Specifies the positioning method for an element (static, relative, absolute, fixed, or sticky).
41. Static: The default positioning, where elements are positioned according to the normal flow of the document.
42. Relative: An element's position is adjusted relative to its normal position.
43. Absolute: An element is positioned relative to its nearest positioned ancestor or the initial containing block.
44. Fixed: An element is positioned relative to the viewport and stays in the same place when the page is scrolled.
45. Sticky: An element toggles between relative and fixed positioning, depending on the scroll position.
46. Z-index: Specifies the stack order of an element, with higher values appearing on top.
47. Overflow: Controls what happens when an element's content is too big to fit in its block (visible, hidden, scroll, auto).
48. Visibility: Controls the visibility of an element (visible, hidden, collapse).
49. Opacity: Controls the transparency level of an element.
50. Color: Sets the color of text in an element.
51. Background-color: Sets the background color of an element.
52. Background-image: Sets the background image of an element.
53. Background-repeat: Specifies if/how a background image is repeated.
54. Background-position: Sets the starting position of a background image.
55. Background-size: Specifies the size of the background image.
56. Font-family: Specifies a list of fonts for text in an element.
57. Font-size: Sets the size of the text.
58. Font-weight: Sets the weight (boldness) of the text.
59. Font-style: Specifies the style of the text (normal, italic, oblique).
60. Text-align: Sets the horizontal alignment of text.
61. Text-decoration: Specifies the decoration added to text (underline, overline, line-through, none).
62. Text-transform: Controls the capitalization of text (uppercase, lowercase, capitalize).
63. Line-height: Sets the amount of space between lines of text.
64. Letter-spacing: Controls the space between characters in text.
65. Word-spacing: Controls the space between words in text.
66. White-space: Controls how white space inside an element is handled.
67. Vertical-align: Sets the vertical alignment of an inline or table-cell element.
68. List-style: A shorthand property for setting list-style-type, list-style-position, and list-style-image.
69. List-style-type: Specifies the marker style for a list item.
70. List-style-position: Specifies the position of the list-item marker.
71. List-style-image: Specifies an image as the list-item marker.
72. Border-radius: Sets the rounded corners of an element's border.
73. Box-shadow: Adds shadow effects around an element's frame.
74. Transition: A shorthand property for defining the transition between two states of an element.
75. Transform: Applies a 2D or 3D transformation to an element.
76. Translate: Moves an element from its current position.
77. Rotate: Rotates an element.
78. Scale: Resizes an element.
79. Skew: Skews an element along the X and Y axes.
80. Animation: A shorthand property for animating elements.
81. Keyframes: Defines the intermediate steps in a CSS animation sequence.
82. Media Query: Applies styles based on the characteristics of the viewport or device.
83. Responsive Design: Designing web content to work on different devices and screen sizes.
84. Viewport: The user's visible area of a web page.
85. Rem Unit: A relative length unit equal to the font-size of the root element.
86. Em Unit: A relative length unit based on the font-size of the parent element.
87. Px Unit: A unit of length equal to one pixel of the display.
88. % Unit: A percentage value relative to another length property.
89. Vh Unit: A unit of length equal to 1% of the viewport height.
90. Vw Unit: A unit of length equal to 1% of the viewport width.
91. Calc() Function: Allows you to perform calculations to determine CSS property values.
92. Custom Properties (CSS Variables): Variables defined by the user for reusing values throughout a CSS document.
93. Import Rule: A rule to import an external stylesheet into another stylesheet.
94. Charset Rule: Specifies the character encoding used in the stylesheet.
95. Namespace Rule: Declares an XML namespace and associates it with a CSS prefix.
96. Supports Rule: Applies styles only if a browser supports a specific CSS feature.
97. Counter: Manages counters in CSS for ordered lists or custom numbering.
98. Counter-increment: Increments a counter value.
99. Counter-reset: Resets a counter value.
100. Content Property: Used with pseudo-elements to insert generated content.


## What does the CSS code look like?

        * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
        }
        
        body {
          background: #ededed;
          font-family: "IBM Plex Mono";
        }

        h1 {
          display: block;
          margin-bottom: 40px;
          color: #101010;
          position: relative;
          font-weight: 700;
        }
        input {
          border: none;
          background: #e0e0e0;
          padding: 10px 15px;
          font-size: 16px;
          font-weight: 500;
          font-family: "IBM Plex Mono";
          outline: none;
        }
        button {
          background: #fff;
          padding: 9px 25px;
          border: none;
          font-size: 18px;
          font-family: "IBM Plex Mono";
          font-weight: 700;
          cursor: pointer;
          box-shadow: 0px 15px 25px rgba(16,16,16,0.25);
        }



  
## How Does CSS Work?
CSS controls the visual appearance of HTML elements by associating CSS rules with HTML elements. A CSS rule typically consists of:

1. Selectors: Identify the HTML elements you want to style.

2. Properties: Specify the aspects of the element you want to style (like color, size, etc.).

3. Values: Define how the properties should look (e.g., red, 16px, etc.).


### Example:

        p {
          color: blue;
          font-size: 16px;
        }
This rule will style all p elements to have blue text and a font size of 16px.

CSS Syntax:

        selector {
          property: value;
        }


## A. Applying CSS to an HTML File
You can include CSS in three ways:

1. Inline CSS: Directly within an HTML tag using the style attribute.
2. Internal CSS: Inside a `<style>` tag within the `<head>` section of an HTML document.
3. External CSS: By linking to an external CSS file using the `<link>` tag. (Recommended)

*Example 1: Inline CSS*

          <p style="color: red; font-size: 20px;">This is a red paragraph.</p>
          
*Example 2: Internal CSS*

          <!DOCTYPE html>
          <html>
          <head>
            <style>
              p {
                color: green;
                font-size: 18px;
              }
            </style>
          </head>
          <body>
            <p>This is a green paragraph.</p>
          </body>
          </html>
          
*Example 3: External CSS*

          <!DOCTYPE html>
          <html>
          <head>
            <link rel="stylesheet" href="styles.css">
          </head>
          <body>
            <p>This is styled from an external CSS file.</p>
          </body>
          </html>
          
In the styles.css file:

          p {
            color: purple;
            font-size: 22px;
          }

## B. CSS Selectors
Selectors are used to target HTML elements to style them. Here are some common types of CSS selectors:

### Element Selector: Targets an element by its tag name.

    p {
      color: blue;
    }
This will style all <p> tags.

### Class Selector: Targets elements with a specific class.

      .my-class {
        color: red;
      }
      HTML:
      <p class="my-class">This text is red.</p>

      
### ID Selector: Targets an element with a specific ID.

      #my-id {
        color: green;
      }
      HTML:
      <p id="my-id">This text is green.</p>
Universal Selector: Targets all elements on the page.


      * {
        color: black;
      }
Grouping Selectors: Combine multiple selectors to apply the same styles.


      h1, h2, h3 {
        color: purple;
      }
Descendant Selector: Selects elements inside another element.


      div p {
        color: blue;
      }

## C: Box Model

Everything in HTML is a box, and CSS controls how these boxes are displayed. The box model consists of:

1. Content: The actual content of the element (text, image, etc.).

2. Padding: Space between the content and the border.

3. Border: The line surrounding the element.

4. Margin: Space between the border and adjacent elements.

    
Here’s a diagram of the box model:

![CSS Box Model](CSS-Box-Model-Images/css-box-model2.jpeg)


CSS Example with Box Model:

    div {
      width: 200px;
      height: 20px;
      padding: 10px;
      border: 5px solid red;
      margin: 10px;
    }



## D: Positioning Elements

CSS allows you to control the layout and positioning of elements with various properties.


Positioning Types:


  1. Static (default): Elements flow in the document as they normally would.
      
         div {
           position: static;
         }
  2. Relative: The element is positioned relative to its normal position.
   
         div {
           position: relative;
           top: 10px;
           left: 20px;
         }
  3. Absolute: The element is positioned relative to its closest positioned (non-static) ancestor.
    
           div {
             position: absolute;
             top: 50px;
             right: 30px;
           }
  4. Fixed: The element is positioned relative to the viewport (browser window).
     
           div {
             position: fixed;
             bottom: 0;
             right: 0;
           }
  5. Sticky: The element is treated as relative until it reaches a defined scroll position, after which it becomes fixed.
    
           div {
             position: sticky;
             top: 0;
           }


## E: Flexbox
Flexbox is a layout model that allows you to create flexible and responsive layouts. It works by assigning a container to use display: flex; and then controlling the alignment, direction, and spacing of items inside it.

Flexbox Basic Setup:

      .container {
        display: flex;
        justify-content: space-between; /* Align items horizontally */
        align-items: center; /* Align items vertically */
      }
      
      .item {
        flex: 1; /* Each item takes equal space */
      }

      
Example:

    <div class="container">
      <div class="item">Item 1</div>
      <div class="item">Item 2</div>
      <div class="item">Item 3</div>
    </div>



## F: Responsive Design with Media Queries
Responsive design adjusts the layout based on the device’s screen size. You can use media queries to apply different styles for different screen sizes.

Example:

        /* For devices with a max width of 600px */
        @media only screen and (max-width: 600px) {
          .container {
            flex-direction: column; /* Stacks the items vertically */
          }
        }



## G: CSS Grid: A two-dimensional layout system for creating complex layouts.

CSS Grid is a powerful layout system that allows you to create two-dimensional grids. You can define both rows and columns to structure your content.
Basic Setup:

    .container {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr; /* Three equal-width columns */
      grid-template-rows: 100px auto; /* First row is fixed at 100px, the second is auto */
      gap: 10px; /* Space between grid items */
    }
    
HTML:

      <div class="container">
        <div class="item">Item 1</div>
        <div class="item">Item 2</div>
        <div class="item">Item 3</div>
        <div class="item">Item 4</div>
        <div class="item">Item 5</div>
      </div>
      
Explanation:

  • grid-template-columns: Defines the columns, here it's 3 equal-width columns.
  
  • grid-template-rows: Defines the row sizes.
  
  • gap: Space between items in the grid.

    
### Advanced Grid Layout:
You can create more complex grid structures with different sizes for rows and columns, and control how items span across multiple rows or columns.

      .container {
        display: grid;
        grid-template-columns: 1fr 2fr 1fr;
        grid-template-rows: 100px 200px;
        gap: 15px;
      }

      .item1 {
        grid-column: span 2; /* Spans across two columns */
      }
      
      .item2 {
        grid-row: span 2; /* Spans across two rows */
      }

### CSS Flexbox vs. CSS Grid

  • Flexbox is ideal for one-dimensional layouts (either rows or columns).
  
  • CSS Grid is better suited for two-dimensional layouts (both rows and columns).
  
  
When to Use Flexbox:

  • When the layout direction is either horizontal (row) or vertical (column).
  
  • Responsive layouts where items adjust based on screen size.
  
    
When to Use Grid:

  • When you need to create complex layouts with both columns and rows.
  
  • For equal-sized or asymmetrical elements that align in both directions.
  
  
## H: Transitions and Animations: Add movement or changes over time.

### 1. CSS Transitions
   
CSS Transitions are used to create smooth changes between two states of an element. For example, you might want a button to change color when you hover over it, but you want the color change to happen gradually rather than instantly.

Basic Syntax of Transitions:

    selector {
      property: initial_value;
      transition: property duration timing-function delay;
    }
    
property: The CSS property that you want to animate.

duration: How long the transition takes (e.g., 1s for 1 second, 500ms for 500 milliseconds).

timing-function: Defines the speed curve of the transition (e.g., ease, linear, ease-in-out).

delay: The delay before the transition starts (optional).


Example: Button Hover Effect

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>CSS Transition</title>
      <style>
        .button {
          background-color: #008CBA;
          color: white;
          padding: 10px 20px;
          border: none;
          border-radius: 5px;
          cursor: pointer;
          transition: background-color 0.5s ease, transform 0.3s ease;
        }
    
        .button:hover {
          background-color: #005f73;
          transform: scale(1.1); /* Slightly enlarges the button */
        }
      </style>
    </head>
    <body>
      <button class="button">Hover me!</button>
    </body>
    </html>

    
Explanation:

When the button is hovered over, the background color transitions over 0.5s and the button grows slightly (scaled up by 1.1) with a 0.3s transition.
The transition property is used to define which properties are animated (in this case, background-color and transform).



### 2. CSS Animations
CSS Animations are more powerful than transitions, allowing for multiple keyframes, more complex animations, and looping effects. While transitions only work when a state changes (like hover), animations can run continuously or be triggered by events.

Basic Syntax of Animations:

    selector {
      animation: animation-name duration timing-function delay iteration-count direction;
    }
    
    @keyframes animation-name {
      0% {
        property: start_value;
      }
      50% {
        property: middle_value;
      }
      100% {
        property: end_value;
      }
    }

    
animation-name: The name of the animation (which corresponds to a @keyframes rule).

duration: The time the animation takes to complete.

timing-function: The speed curve of the animation.

delay: How long to wait before the animation starts.

iteration-count: How many times the animation runs (infinite for continuous loops).

direction: Defines whether the animation should alternate direction on each cycle (normal, reverse, alternate).


Example: Bouncing Ball Animation

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>CSS Animation</title>
      <style>
        .ball {
          width: 50px;
          height: 50px;
          background-color: #ff6347;
          border-radius: 50%;
          position: relative;
          animation: bounce 2s ease-in-out infinite;
        }
    
        @keyframes bounce {
          0%, 100% {
            transform: translateY(0);
          }
          50% {
            transform: translateY(-200px);
          }
        }
      </style>
    </head>
    <body>
      <div class="ball"></div>
    </body>
    </html>

    
Explanation:

The @keyframes rule defines the animation named bounce.

The ball moves up (translateY(-200px)) at the 50% point of the animation, and returns to its original position at 0% and 100% (end of the cycle).

The animation property applies the bounce animation to the ball, running continuously (infinite).



### differences between transitions and animations in CSS:

Transitions:

When: Happens when a property changes from one value to another (e.g., hovering over an element).

How: It only works on changes that are triggered by an event, like hovering or clicking.

Example: When you hover over a button, its background color changes smoothly.

Control: You can control the timing (duration) and easing (smoothness) but not much else.


Example:

    button {
      background-color: blue;
      transition: background-color 0.3s ease;
    }
    
    button:hover {
      background-color: green;
    }


    
Animations:

When: Can run continuously or trigger at any point, without needing an event.

How: More powerful, allows multiple steps or keyframes, and can animate multiple properties simultaneously.

Example: A bouncing ball, or a logo that moves across the screen.

Control: Full control over keyframes, durations, timing, delays, and more.


Example:

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }
    
    .ball {
      animation: bounce 1s infinite;
    }
    
Summary:

Transitions = Triggered by events (e.g., hover, focus), simple, only between two states.

Animations = More complex, runs on a timeline, can loop, and has more control over multiple states and properties.

### Combining Transitions and Animations

You can combine both transitions and animations on the same element for different effects.

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Combined Example</title>
      <style>
        .box {
          width: 100px;
          height: 100px;
          background-color: #008CBA;
          transition: background-color 0.5s ease; /* Transition for color change */
          animation: move 3s ease-in-out infinite; /* Animation for movement */
        }
    
        @keyframes move {
          0%, 100% {
            transform: translateX(0);
          }
          50% {
            transform: translateX(200px);
          }
        }
    
        .box:hover {
          background-color: #ff6347; /* Change color on hover */
        }
      </style>
    </head>
    <body>
      <div class="box"></div>
    </body>
    </html>

    
In this example:

  • The box moves horizontally in a loop (due to the @keyframes animation).
  
  • When the box is hovered over, its background color smoothly transitions to a different color.


## I: CSS Variables: Store reusable values for properties.

CSS variables, also known as custom properties, allow you to define reusable values in your CSS and make your stylesheets more flexible and easier to maintain. They are especially useful when you want to create a consistent design system, as they let you store values like colors, fonts, spacing, etc., in a central location and use them throughout your CSS.

### How to Define CSS Variables
CSS variables are defined inside a selector, typically the :root selector, which makes them globally available throughout the document.


    :root {
      --primary-color: #3498db;
      --secondary-color: #2ecc71;
      --font-size: 16px;
      --padding: 20px;
    }

    
Using CSS Variables
Once defined, you can use these variables anywhere in your CSS using the var() function.


        body {
          background-color: var(--primary-color);
          font-size: var(--font-size);
          padding: var(--padding);
        }
        
        h1 {
          color: var(--secondary-color);
        }


        
### Benefits of CSS Variables

Consistency: Centralize design values and reuse them across your styles.

Maintainability: Easily update multiple styles by changing the variable in one place.

Dynamic changes: CSS variables can be modified at runtime using JavaScript.


### Overriding CSS Variables

You can also override CSS variables within different parts of your document (e.g., within specific sections or elements).


    .button {
      --primary-color: #e74c3c;  /* Override for buttons */
      background-color: var(--primary-color);
      color: white;
    }


    
### Using CSS Variables with Media Queries

CSS variables can also be adapted based on breakpoints using media queries.


      :root {
        --font-size: 16px;
      }
      
      @media (min-width: 768px) {
        :root {
          --font-size: 18px;
        }
      }
      
      body {
        font-size: var(--font-size);
      }

      
### JavaScript Interaction

You can access and modify CSS variables with JavaScript for dynamic changes:


      document.documentElement.style.setProperty('--primary-color', '#e67e22');

      
Best Practices

Use meaningful names for your variables, like --primary-color, --font-size-base, etc.

Group variables together in your CSS for better organization.

Consider using variables for frequently used properties like colors, fonts, and spacing.



# deep dive into CSS?

### 1. [FreeCodeCamp](https://www.freecodecamp.org/)
### 2. [MDN Web Docs (Mozilla)](https://developer.mozilla.org/en-US/docs/Web/CSS)
### 3. [CSS-Tricks](https://css-tricks.com/)
### 4. [The Odin Project](https://www.theodinproject.com/lessons/foundations-intro-to-css)
### 5. [CSS Grid Garden](https://cssgridgarden.com/)
### 6. [Flexbox Froggy](https://flexboxfroggy.com/)
### 7. [W3Schools](https://www.w3schools.com/css/default.asp)
### 8. [YouTube: Traversy Media](https://www.youtube.com/watch?v=yfoY53QXEnI)
***There are plenty of great resources out there!
