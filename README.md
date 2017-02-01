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
<link rel="stylesheet" type="text/css" href="site/templates/css/app.css"/>
```

* link 
	* rel
	* type
	* href

### Selectors
* universal
* type
* class
* id
* child
* descendant
* adjacent sibling
* general sibling

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
* color
* background-color
* opacity, rgba
* hsl, hsla

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
