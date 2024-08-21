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
- **Justify Content** is similar to align items except it aligns on the horizontal plane. Thats assuming the direction of our flex display is a row (which is default). You'd have to input column, which is like a vertical list.
- Justify-content: space-between pushes it to ends of page
- **If code doesn't work as expected on the preview page, fix it then and there. Ususally it is a missing closing tag**
- A comma (,) after navallows us to set 2 with the same set of styles
- **Gap** creates a gap between columns
- **Class** can be added to any element as an attribute on the HTML doc, and then move to the CSS doc, add a period (.) followed by the class. Now it will style all elements with that class on the HTML doc. Gives us the ability to be specific.
- **Text-decoration** the automatic underline from a link is called a decoration. To get rid of this default feature, use **unset**
- set font family and add a backup with a comma (,)
- There is a font family heirarchy ID takes priority over class which takes priority over tag which takes priority over parents. You can override the hierarchy with the important flag which is !important;
- To design responsive webpages, you need to design for the mobile screen first. To see the mobile screen on a website right click, inspect, and toggle to mobile view icon
- The searchbar by default reaches across the page and is responsive, so the 100% width is a good way to make sure a child element only occupies the maximum compared to the parent, instead of the entire page. But there is an issue, as you upsize, the width is going to get wider and wider. So we need to set a cap on the width with max-width. So our width will then increase to the max only.
- Typically, if we set max width w/ a flex display, everything will be left justified, so then we need a margin.
- margin set to auto, auto centers the element 
- first perameter defines vertical and second defines horizontal. If there is only one perameter, it applies to all sides.
-The colon (:) after an anchor allows it to apply to all anchor elements on the page.

## 8/19/24

### Still from the HTML and CSS YT Tutorial
- Inputs come with a lot of default styling so be aware of that, you will probably need to get rid of them all
- Border radious creates curved corners
- Box shadow 0 0 3px rgba(0,0,0,0.2) created a shadow on the search bar w/ 0 horizontal and vertical effect, 3px size, gray color with 20% opacity
- If there is movement when hoovering over a button, take away the unset border and replace it with transparent. When it is unset, it will "add" a border that doesn't exist, whoch cause resizing. So creating a border but making it transparent will provide the same effect but without any "resizing" movement.
- You can turn the curser into a pointer with curser:pointer!
- To select the sections that exist w/in the footer and select only the direct decendents or 2 children, use the greater than (>)
-To turn off code, yet still see it add /*words*/
- **Font Awesome Icons** have icon tags like  camera, microphones, etc (fontawesome.com). So cool. They will have default styling, that can be unset with a class.
- Make sure links in footer are responsive to page resizing. If not then use **Media Query** with min-width. This should always be at the bottom of the page and means that the style will take over as soon as the min width is met. It will turn it into a row, which makes it responsive to smaller screens.