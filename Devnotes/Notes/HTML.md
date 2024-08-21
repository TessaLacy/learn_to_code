# HTML Notes

## 8/18/24 

### Formating
- You can look at HTML like a word document with a header, start of the main, end of the main, which wraps all of our main content, and the footer. all of that together is refferred to as **The Body**
- The Head of the body contains Meta information about the body, such as the title.
- So essentialy, you can build out an HTML website like a word document.
- However, unlike a word document, an HTML document has responsivity such as resizing. It also can be more dynamic, with buttons, inputs, etc. And if you start to incorporate Jave Script, you can add a lot more interaction. Finally, construction of an HTML document is different in that a word document is formatted and created using the toolbar and pull down menus, while as an HTML document is created with HTML tags to tell the page what to do.
- The way that tags work is similar to the way that quotations work. In a word document words wrapped in quotation marks is something someone said, or a quote and it is distinguishable from the rest of the information on the page. HTML works similarly, in that we create meaning by wraping words in tags.
- The opening tag is the keyword wrapped in < and > and the closing tag is the keyword with a slash in front of it wrapped in < and >
- To create a quote <q>this is a quote</q> for a quote
- To create a title <title>Intro to Webdev</title>
- Text Tags include:
1. Header Tags <h1></h1> <hs, h3, h4, h5, h6
2. paragraph tag <p></p>
- Container Tags include:
1. Head tag <head></head>
2. Body tag <body>
3. navigation tag <nav>
4. Section <section></section>
5. Division <div></div>
6. span <span></span> **Note: you can't have container tags that contain information inside of a paragraph, so instead we use span.
7. Form Tag <form></form> If we have a lot of inputs, we usually wrap them in a form tag
- Utility tags include:
1. img src=(link to the file) alt="this is an image of a 1974 Landcruiser"/> **Note: this is self closing, so we don't need an open and close tag and instead it requires a source. **Another Note: It doesn't have an open and close tag, so it can't contain any information in between the tags. So the information needs to be in the **attribute** (src) and the **value** is whatever is on the other side of the equal (=). (alt) is the **secondary attribute** in this case and is used to explain what the image is to seeing impared people.
2. Input Tag <input value=""placeholder=""/> *Note: Also self closing and contains a value attribute and a placeholder attribute
3. Buton Tag <Button>
4. Form Tag <form></form>
5. Anchor Tag <a></a>  
- example of some of these tags below;
<head>
  <title></title>
</head>
<body>
  <header>
  <h2>title #1</h2>
  <nav>
    
  </nav>
</header>
<main>
  <section>
<div>
    <h3>Subheader</h3>
</div>
<div>
  <img src=(link to file) alt="this is an image of a 1974 Landcruiser"/>
  <form>
    <inputvalue=""placeholder=""/>
    <button>  
    </form>
    <a>click here</a>   
<div>
    <p>This is the<span></span> paragrph</p>
    <p>This is the paragrph</p>
    <p>This is the paragrph</p>
 </div>
  </section> 
</main>
<footer>
  
</footer>
</body>

### HTML & CSS YT Tutorial
-Pressing ! and then tab, will bring up the HTMLboiler plate code- this creates the basic HTML format required to create a basic HTML website.
-lang="en" lets the browser know the default language is English
-Comments in an HTML doc are created with the tag <!--words-->. This allows me to keep the comments near the code, but it won't show up on the website. I still need to practice this though...
-When creating headers, make sure to stay consistent. I can have multiple h2 and beyond headers, but there should only be one h1 header in a doc.
- **Span** is the in line space continer. It's the only spacing tag we are allowed to have within a paragraph.
-Every HTML tag allows you to add a style attribute. This is known as an inline style, but it is not best practice. The biggest downside is it will only apply the style to that particular element. So if you wanted all of the buttons styled the same, you would have to do a lot of copy paste.
- Add a **class** - it allows CSS and Javascript to select and access specific elements. It is added after the "add a link" attributes, but then you also need it to the CSS sheet. Start a new line and begin with a period (.), then enter the class (it should automatically pop up).
- Since we added a flex display to the parent container, which is the body, all direct "children" can have a flex set to 1, which will allow them to be as space greedy as possible.
- When you use the center perameter for the align-items and justify content, it aligns both the vertical and horizontal, respectively, to center in the middle of the page.
-When I tried to create a consistent gap in between all body elements, it didn't work for me, but it was because I had an open division without a close. When I added the close, it all spaced correctly.
- The only h1 I had in this doc was Google so we added a class to stylize. We added a secondary attribute called **ID**, which is a unique ID in the doc. Can't make another, but since we only have one h1, it works as long as you add it to the CSS file beginning with a period (.)

## 8/19/24
### Continuing with HTML and CSS YT Tutorial
- To add an **Emoji** click the curser where you want to add it, press the window and the period (.) key at the same time to open up the panel where you can choose the emoji you want
- add icons to doc from **Famous Icons** website. Just click the code to copy and then pop it in where you want it.
- It is best practice to create a folder to add all images to called public, if you need to put an image in your doc. Then use the img tag, with the source, then the alt (description) and then it is a self closing tag. 
- **Font Awesome CDN** offers exterior packages that we can incorporate into our code (cdnjs.com). Just copy the link tag and paste into the head.


