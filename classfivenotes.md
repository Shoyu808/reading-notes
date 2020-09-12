# Reading Notes 5

## ***Introduction to CSS***

### ***What is CSS?***
- The key to understand how CSS works is to imagine that there is an invisible box around every HTML element.
- *CSS* allows you to create rules that control the way that each individual box (and the contents of that box) is presented.
```
* The <body> element creates the first box, the the <h1>, <h2>, <p>, and <a> elements each create their own boxes within it.
```
#### Example ***Styles***

##### **Boxes**
- Width and height
- Borders (color, width, and style)
- Background color and images
- Position in the browser window

##### **Text**
- Typeface
- Size
- Color
- Italics, bold, uppercase, lowercase, small-caps

##### **Specific**
- There are also specific ways in which you can style certain elements such as lists, tables, and forms.

### ***CSS rules with HTML Elements***
- CSS works by associating rules with HTML elements.
- These rules govern how the content of specified elements should be displayed.
- A CSS rule contains **two parts:** *Selector* and *Declaration.*

##### ***Selector***
- *Selectors* indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.

##### ***Declarations***
- *Declarations* indicate how the elements referred to in the selector should be styled.
- *Declarations* are split into two parts (a property and a value), and are separated by a colon.