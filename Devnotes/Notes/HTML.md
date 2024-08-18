# HTML Notes

## Formating
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
