# CSS Notes

## 8/18/24 

### from the HTML and CSS YT Tutorial
- W3 school is a great resource for CSS perameters
-One way to add a CSS file to an HTML page is to add a style opening and closing tag wrapped in the head tag. Within this style tag, you can enter all element styles, but this can get very long. So instead, we create a CSS file and link to style sheet. The link is self closing and doesn't show up on the site. The style sheet needs to be a file in the same folder as your HTML file.
-There is an amount of padding and margin, and it is good practice to reset it on every HTML document. We only need to do this once at the top of the style sheet.
- **Padding** is how much space on the inside
-**Margin** is the space on the outside of the container
- The asterik (*) tells the doc to apply that style to all elements on the page.
-The semicolon (:) means it's meant for all elements
- **min-height** means 100% of view port height or view height available
- **display** tells the container how to display it's content. A value of **flex** is a flexible container and the default container in a row (like we are stacking boxes into a truck, stacked horizontal)
- **align-items** is how the items w/in the row sit in respect to the container boundries (in vertical plane). We use center the most, or stretch. 
-**Justify Content** is similar to align items except it aligns on the horizontal plane. Thats assuming the direction of our flex display is a row (which is default). You'd have to input column, which is like a vertical list.