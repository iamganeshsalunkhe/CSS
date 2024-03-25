# CSS
"If your website were a party, this CSS repo would be the DJ - spinning the tunes of style and sophistication."
### CSS is the language we use to style a Web page.
CSS stands for Cascading Style Sheets.


CSS describes how HTML elements are to be displayed on screen, paper, or in other media.


CSS saves a lot of work. It can control the layout of multiple web pages all at once.


External stylesheets are stored in CSS files.

### Why Use CSS?
CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.


<img width="609" alt="Screenshot 2024-03-25 114725" src="https://github.com/iamganeshsalunkhe/CSS/assets/143490640/72ea7892-72b4-4f3d-819f-4831f6807d6e">


### CSS Synatx 

<img width="451" alt="Screenshot 2024-03-25 115803" src="https://github.com/iamganeshsalunkhe/CSS/assets/143490640/3c919783-5fe4-4831-b5fc-da7f6b584e95">

The declaration block contains one or more declarations separated by semicolons.

Each declaration includes a CSS property name and a value, separated by a colon.

Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

CSS Selectors
CSS selectors are used to "find" (or select) the HTML elements you want to style.

#### We can divide CSS selectors into five categories:

Simple selectors (select elements based on name, id, class).


Combinator selectors (select elements based on a specific relationship between them).


Pseudo-class selectors (select elements based on a certain state).


Pseudo-elements selectors (select and style a part of an element).


Attribute selectors (select elements based on an attribute or attribute value).

<img width="422" alt="Screenshot 2024-03-25 120204" src="https://github.com/iamganeshsalunkhe/CSS/assets/143490640/909c8101-45d0-4fc7-9742-d0c5759fe682">

### How To Add CSS


There are three ways of inserting a style sheet:

#### External CSS


#### Internal CSS


#### Inline CSS


#### External CSS
With an external style sheet, you can change the look of an entire website by changing just one file!

External styles are defined within the <link> element, inside the <head> section of an HTML page:

<img width="416" alt="Screenshot 2024-03-25 120546" src="https://github.com/iamganeshsalunkhe/CSS/assets/143490640/5c77916d-00db-44eb-822d-f5e4a348cd5e">

An external style sheet can be written in any text editor, and must be saved with a .css extension.


The external .css file should not contain any HTML tags.


Here is how the "mystyle.css" file looks:


<img width="453" alt="Screenshot 2024-03-25 120613" src="https://github.com/iamganeshsalunkhe/CSS/assets/143490640/6064024b-b4db-4ef3-878a-e6da25d6d0e1">



#### Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section.

<img width="205" alt="Screenshot 2024-03-25 121104" src="https://github.com/iamganeshsalunkhe/CSS/assets/143490640/cd9b235c-5d4a-4426-ac18-04cb193b90a1">


#### Inline CSS


An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.


<img width="422" alt="Screenshot 2024-03-25 121252" src="https://github.com/iamganeshsalunkhe/CSS/assets/143490640/552cc9b7-09e2-40b8-8246-660ce86a1a85">

#### The CSS Box Model
In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: content, padding, borders and margins. The image below illustrates the box model:


<img width="587" alt="Screenshot 2024-03-25 121620" src="https://github.com/iamganeshsalunkhe/CSS/assets/143490640/f4517de0-9655-4b55-8548-eeae1c14a0bc">


Explanation of the different parts:

Content - The content of the box, where text and images appear.

Padding - Clears an area around the content. The padding is transparent.

Border - A border that goes around the padding and content.

Margin - Clears an area outside the border. The margin is transparent.

The box model allows us to add a border around elements, and to define space between elements. 

### The position Property
The position property specifies the type of positioning method used for an element.

There are five different position values:

static

relative

fixed

absolute

sticky

Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the position property is set first. They also work differently depending on the position value.

#### position: static
##### HTML elements are positioned static by default.

Static positioned elements are not affected by the top, bottom, left, and right properties.

An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page.

#### position: relative
##### An element with position: relative; is positioned relative to its normal position.

Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.

#### position: fixed
##### An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.

A fixed element does not leave a gap in the page where it would normally have been located.

#### position: absolute
##### An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

Note: Absolute positioned elements are removed from the normal flow, and can overlap elements.

#### position: sticky
##### An element with position: sticky; is positioned based on the user's scroll position.

A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).

