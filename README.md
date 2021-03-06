# CSS Cascading Style Sheets

## CSS affects html Elements

```
Selector
	|
	p { 
	    font-family: Arial;}                 
	    |_________________|
	             |
	       declaration
             	       
	    font-family: Arial;
	    |___________|_____|
	          |        |  
	     property:   value;
	          |        |
	        color:  yellow;
	        
	  p {
	     font-family: sans-serif;
	    }     
     
```
The CSS selector ```p``` will affect paragraphs in HTML.


## CSS Terms

### Internal
```
<style>
</style>
```
* style

### External
```
<link href="style.css" rel="stylesheet" type="text/css">
```

[Alternative Style Sheets](https://developer.mozilla.org/en-US/docs/Web/CSS/Alternative_style_sheets):
```
<link href="style.css" rel="alternate stylesheet" type="text/css">
```


* link 
	* rel
	* type
	* href

### Selectors
* [universal](https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors)
* [type](https://developer.mozilla.org/en-US/docs/Web/CSS/Type_selectors)
* [class](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors)
* [id](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors)
* [child](https://developer.mozilla.org/en-US/docs/Web/CSS/Child_selectors)
* [descendant](https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_selectors)
* [adjacent sibling](https://developer.mozilla.org/en-US/docs/Web/CSS/Adjacent_sibling_selectors)
* [general sibling](https://developer.mozilla.org/en-US/docs/Web/CSS/General_sibling_selectors)

### Cascading terms
* Last rule
* specificity
* important

### Inheritance
* inherit

### Browser Quirks

### comments
* ```/* This is a css comment */```

### Color

* color: The color property is applied to text inside an element. 
* background-color: html elements are treated as if they are in boxes. By default these are white. This property affects the background color of the box.
* opacity, rgba
* hsl, hsla

CSS syntax for Red, Green and Blue
```
rgb(#,#,#)
```

## Websites we will look at in class for investigating color:
* [147 Named CSS colors](http://www.colors.commutercreative.com/)
* [Free online SVG editor](http://editor.method.ac/) *Works best with Chrome Browser*
* [Hexidecimal Color Picker](https://www.mathsisfun.com/hexadecimal-decimal-colors.html)

## [Fundamental Text and Font Styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

### Text
* serif
* sans-serif
* monospace
* weight
* style
* stretch
* cursive 
* fantasy
* font-family
* font-size
	* pixels
	* percentages
	* ems

### More Fonts
* @font-face
 	* font-family
 	* src
 	* format
 		* eot
 		* woff
 		* ttf/otf
 		* svg
* font-weight
 	* bold
 	* normal 
 	* font-style
 	* normal
 	* italic
 	* oblique
* text-transform
 	* uppercase
 	* lowercase
 	* capitalize
* text-decoration
 	* none
 	* underline
 	* overline
 	* line-through
 	* blink
* line-height
* letter-spacing
* word-spacing
* text-align
* vertical-align
 	* baseline
 	* sub
 	* super
 	* top 
 	* text-top
 	* middle
 	* botton
 	* text-bottom
* text-indent
* text-shadow 
