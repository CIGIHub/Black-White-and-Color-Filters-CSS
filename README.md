# Black, White and Colour CSS Filters
Quickly apply coloured CSS filters to an HTML element with a hover effect.

## Example Implementations

Assign the class `colour-filter` to an element and its contents filter to that colour. Specify the colour by adding a class like `pink` or `blue`.  

```html
<div class="colour-filter pink"> ... </div>
```

Assign the class `colour-filter none` to an element to remove the colour filters while retaining the hover effect. 

```html
<div class="colour-filter none"> ... </div>
```


### Filter List:

If no colour class is specified, the colours will cycle through the following order:

```
.pink 
.blue 
.cyan 
.green 
.yellow 
.purple 
.orange
.grey

.none // removes colouring
```
