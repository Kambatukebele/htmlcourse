### Tools needed:
. Text Editor: Vs Code(or any): https://code.visualstudio.com/ or just google it
. Web Browser: Chrome, Firefox, Safari, Brave, etc

=> Why do we need a Text Editor? : A text editor is the tool we use to write and edit code. It is just like a notebook for developers. While you could technically use something like Notepad, a code editor like Vs code for example, makes your life a LOT easier because:
    * It highlights your code with colors
    * It helps you auto-complete tags, so you type less
    * It shows you errors as you type
    * It can even suggest code, like a smart assistant

In short, a good text editor helps you write cleaner, faster, and more organized code, especially as projects get bigger.
=> Why do we need a browser? : A Browser, like Chrome, Firefox, Safari, Brave, etc.. --- is what we use to view web pages. When we write HTML code, we are creating the structure of a webpage. But that code by itself in not very useful unless something can read it and display it visually. That's where the browser comes in.
The browser takes your HTML file and turns it into something beautiful and interactive --- like:
. Headings
. Images
. Buttons


### Essential extensions/apps for Vscode: 
. Live server (must have it): Live Server is a simple extension that makes building websites much smoother and faster. It runs your files through a local development server, which behaves more like a real websites. Every time you save your HTML file, Live server automatically reloads the browser so you see changes instantly -- no need to refresh manually. 
  
. Prettier (must have it): Prettier is a code formatting tool that helps keep your HTML (and other code) clean, consistent, and easy to read.

.   Elm Emmet: 
. Auto Close Tag (Optional)
. Auto Complete Tag (Optional)
. Auto Rename Tag (Optional)

### Let's create our first HTML file and open it in a browser-- super simple!
. Create a new file and save it as index.html. the ".html" extension tells the browser this is an HTML file. 
# What is a file extension?
A file extension is the part of a file name that comes after the dot. It tells your computer what kind of file it is, and what program should open it.
Example:
. index.html has the .html extension, witch means it's an HTML file -- a web page.
. A file like photo.jpg or somPhoto.png has the .jpg or png extension, meaning it's an image.
. A document like notes.docx is a word document.
. A document like someDocument.pdf is a pdf document.
So when we name our file "index.html", we are telling the browser: Hey, this is a webpage--render it like one!
*** If you forget the .html extension, your computer won't know what to do with the file and it might just open it as plain text.

### What is HTML?
=> HTML stands for Hyper Text Markup Language. It is not a programming language
=> HTML is the standard markup language for creating Web pages
=> HTML describes the structure of a Web page
=> HTML elements are the building blocks of HTML pages
=> HTML elements are represented by tags
=> HTML tags label pieces of content such as "heading", "paragraph", "table", and so much more
### Example of HTML document:
<!DOCTYPE html>
<html>
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <h1>This is a Heading</h1>
        <p>This is a paragraph.</p>
    </body>
</html>

==> Copy this boilerplate and paste it in the index.html we just created, and save it with ctrl + s for windows or command + s for mac.


### Example Explained
. <!DOCTYPE html> is a declaration that defines that this document is an HTML 5 document
. <html> is the root element of an HTML page (must have lang to specify the language)
. <head> is the element that contains meta information about the HTML page (ex: , SEO tags, Facebook tags, google tags, etc)
. <title> is the element that contains the title of the HTML page
. <body> is the element that contains the main content of the HTML page, and it is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, list, etc
. <h1> element defines a large heading
. <p> element defines a paragraph

# what is the root element? 
In HTML, the root is the very top-level element that contains everything on the page. That root element is the <html> tag. 
It looks like this:
<html>
    <!-- Everything else goes inside here -->
</html>
Think of it like a big box that holds all the other boxes inside it.
Every HTML document must have this <html> element --- it's where the browser starts reading your page.

# what is an element?
An HTML element is defined by a start tag, some content, and an end tag
Example
Full element => <tagname>content</tagname>
Open element => <tagname>
Content of the element => content
Close element => </tagname>

*** ==> Important Note: You can't just make up your own HTML elements. You have to use the elements that are already defined in the HTML standard, because the browser won't understand it and it is not a valid HTML element. <== ***

*** ==> Note: Some HTML element have no content. These elements are called empty elements. Empty elements do not have an end tag! <== ***

*** So we can say that HTML is a suite of elements, that come together to build the structure of a webpage ***


### Examples of some elements ###
*** Headings ***
==> HTML Headings are titles or subtitles that you want to display on a webpage.
==> HTML Headings are defined with the <h1> to <h6>.
==> The <h1> defines the most important heading. 
==> The <h6> defines the least important heading.

"Headings in HTML aren't just about making text big and bold.
They actually play a really important role in how your page is understood—by both users and search engines.

-> Search engines, like Google, use headings to figure out the structure and content of your page.
-> And real people? They often skim a page by scanning the headings to find what they’re looking for.

That’s why it’s super important to use headings properly—to show the outline or hierarchy of your content.

Let's see some example: 
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>

*** Paragraphs ***
The <p></p> tag in HTML stands for paragraph--- and it's used to group blocks of text together. It is perfect for writing articles, blog posts. descriptions, any body text on your site.
Whenever you want to write a sentence or a chunk of text, wrap it in a <p> element like this:
<p>This is a paragraph.</p>

*** HTML horizontal rules ***
The <hr> tag defines a thematic break in an HTML page, and is most often displayed as horizontal rule. It is used to separate content (or define a change) in an HTML page
ex: 
<h1>This is heading 1</h1>
<p>This is a paragraph.</p>
<hr>
<h1>This is heading 2</h1>
<p>This is a paragraph.</p</p>

*** ==> Important note: <hr> tag is an empty tag, which means that it has no end tag <== ***

*** HTML Line breaks ***
The HTML <br> element defines a line break.
Use <br> if you want a line break (a new line) without starting a new paragraph
ex: 
<p>This is <br> a paragraph <br> with line breaks. </p>

*** ==> Important note: <br> tag is an empty tag, which means that it has no end tag <== ***

*** HTML <pre> ***
The HTML <pre> element defines preformatted text.
The text inside a <pre> element is displayed in a fixed-width font(usually courier), and it preserves both paces and line breaks.

Let's see an example with the <p> tag and the <pre> tag:
<p>
    This is a paragraph one.
    This is a paragraph two.
    This is a paragraph three.
    This is a paragraph four.
</p>
<pre>
    This is a paragraph one.
    This is a paragraph two.
    This is a paragraph three.
    This is a paragraph four.
</pre>

*** Lists ***
HTML gives us two main types of lists: Ordered and unordered lists.
*** Unordered lists ***
An unordered list uses the <ul> tag, and it creates a list with bullet points.
Each item inside the list is written with an <li> tag
===> Important note:  Nexted HTML element: HTML element can be nested (this means that elements can contain other elements). <===
ex:
<ul>
    <li>This is a list item</li>
    <li>This is another list item</li>
    <li>This is a third list item</li>
</ul>
This show up as a bulleted list in the browser.
*** Ordered lists ***
An ordered list uses the <ol> tag, and it creates a list with numbers.
Each item inside the list is written with an <li> tag
ex: 
<ol>
    <li>Milk</li>
    <li>Bread</li>
    <li>Eggs</li>
</ol>
This is great for things like instructions or rankings--- any time where the order matters.

---- ------
Before we continue to learn other tags, we need to learn what is attributes and comments.
---- ------
Let's start with the comments.
### Comment:
Sometimes, you want to leave notes in your code --- either for yourself or for other developers. That's where HTML comments come in.
A comment won't show up on the webpage.
It's only visible in the code, and the browser completely ignores it.
To write a comment you need to open and close as any HTML tags; 
<!-- THis is the open
and here is the content or comment you want to leave or hide
--> THis the closing
ex: <!--  THis is a comment -->
*** ==> You can use comments to: 1. Explain your code 2. Leave reminders for yourself or other developers 3. Temporarily disable a piece of code without deleting it <== ***

### Attributes:
HTML attributes give extra information about an element.
They ALWAYS go inside the opening tag, and they always follow this format: name="value" or just name
Ex: <img src="image.jpg" alt="This is an image">
<input type="button" placeholder="Enter your name" required>
### ==>For the image:
    . src is an attribute that tells the browser where the image is located
    . alt is another attribute that describes the image--- for screen readers or if the image doesn't load

As we learn what is an attributes, let explore other tag elements. 
*** Images ***
The <img> tag is used to display images on a web page.
It's a self-closing tag, which means that it doesn't need an opening and closing tag.
ex: <img src="image.jpg" alt="This is an image">
    .src stands for source --- it tells the browser where to find the image file.
    .alt stands for alternative text --- this shows up if the image can't load, and it's also used by screen readers.
    You can also add extra attributes like width, height, or even style to control how the image looks on your page.

===> We will see how to use external image and local image. External images are images that does not reside on your server or local machine. You will just use link and add it to the source. The internal image is the image that you add first into your local server or local computer and then reference it.
*** HTML Links ***
In HTML, we use the <a> tag to create links---short for anchor.
ex: <a href="https://www.google.com">Visit google</a>
===> The href attribute stands for hyperlink reference(You do not need to memorize it)--- it tells the browser where the link should go.
===> The text between the tags is what the user clicks on
So in this case, when someone clicks "Visit google" in our example, it will take them to google.com
===> You can use links to:
    . Navigate to other websites
    . Link to other pages on your own website
    . Or even jump to specific sections on the same page inside your website

The <a> tag can as also a special attribute call "target". It specifies where to open the linked.
The target attribute can have one of the following values:
    . _self - Default. Opens the document in the same windows/tab as it was clicked
    . _blank - Opens the document in a new window or tab
    . _parent - Opens the document in the parent frame
    . _top - Opens the document in the full body of the window
Here are some examples: 
<a href="https://www.google.com" target="_blank">Visit google</a>
<a href="https://www.google.com" target="_parent">Visit google</a>
<a href="https://www.google.com" target="_top">Visit google</a>

The <link> tag is used to link external resources to your webpage--- not for clicking, but for connecting behind the scenes.
ex: <link rel="stylesheet" href="style.css">
This tells the browser: Hey, go grab that CSS file and apply the style to this page.
===> Note that css is a styling language, we will touch a little bit that later.

So what is the difference between the <a> and <link> tags?
 . <a> is for navigation --- used always in the <body> of your HTML, visible and clickable by users
 . <link> is for resources --- usually used inside the <head> of your HTML, used by the browser, and hidden to the user.

*** HTML div ***
The <div> tag in HTML stands for division --- and it's used to group content together.
You can think of a <div> like an empty box that you can fill with anything: text, images, headings, buttons --- whatever you want.
ex: 
<div>
  <h2>My Section</h2>
  <p>This is a paragraph inside a div.</p>
</div>
why is this useful?
    . it helps organize your layout
    . Makes it easier to style sections of your page using CSS
    . And let's you target specific parts of your content with JavaScript

*** HTML Semantic ELements ***
Semantic elements in HTML are tags that clearly describe their meaning --- both to the browser and to humans who reading your code.
For example, instead of using a plain <div> for everything, you can use semantic tags like:

 . <header> - for the top section of your page
 . <nav> - for the navigation menus
 . <main> - for the main content of your page
 . <section> - for grouping related content
 . <article> - for blog posts or news stories
 . <footer> - for the bottom section of your page

Ex:
<header>
  <h1>My Website</h1>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#">About</a>
</nav>

<main>
  <section>
    <h2>Welcome!</h2>
    <p>This is my homepage content.</p>
  </section>
</main>

<footer>
  <p>Copyright 2025</p>
</footer>

Semantic elements make your code:
 . Easier to read
 .  Better for SEO
 . And more accessible to screen readers

In short:
Semantic HTML gives your code structure and meaning—not just style."
 
===> Important Node: Semantic elements, <header>, <nav>, <main>, <section>, <article>, <footer> are container just like the <div>, the only key difference here is that semantic elements describe the purpose of the content, both for developers (readability) and for the browser (SEO) as already stated earlier.

*** HTML Block and Inline Elements ***
In HTML, every element is either a block or an inline element. --- and understanding the difference is key to building clean websites.

 # Block-level elements
 Block-level elements take up the full width available and always start on a new line. They kind of act like big building blocks that stack on top of each other.
    Ex:
    <div>, <p>, <h1> to <h6>, <section>, <footer>, <header>, <article>, <nav>, <aside>, <li>, <form>, <table>, <ul>, <ol>, <pre>
    When you use a block element, it pushes the next thing down to a new line.
    ex: 
    <div>First block element</div>
    <div>Second block element</div>

# Inline element
Inline elements, on the other hand, only take up as much space as they need. They stay in line with other content, like a words in a sentence.
    Ex:
    <span>, <a>, <small>, <em>, <img>, <strong>, <input>, <textarea>, <select>, <button>, <label>
    So if you use an inline tag, it won't break the flow of the text. ---it just fits right into it.
    Ex1:
    <span>Block element one</span>
    <span>Block element two</span>
    Ex2: 
    <p>This is a <strong>Strong</strong> word inside a paragraph</p>
    Here, <p> is block-level — it starts on a new line.
    But <strong> is inline — it just styles part of the text within the line.
    Knowing when to use block or inline elements helps you control how your content flows and how your layout behaves."

*** HTML Tables ***
HTML tables are used to display data in rows and columns, kind of like a spreadsheet.
To build a table, we use a few specific tags:
    . <table> - defines a table, the main container --- (block element)
    . <tr> - stands for table row --- (block element)
    . <th> - stands for table header --- (block element)
    . <td> - stands for table data --- (block element)

Ex: 
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>25</td>
  </tr>
  <tr>
    <td>Bob</td>
    <td>30</td>
  </tr>
</table>
This creates a table with two columns: one for names, and one for ages.
==> Use <th> when you want the top row to be bold and centered --- it shows that it's a header.
==> Use <td> for all your regular data cells.
Tables are great for showing things like:
. Price lists
. Schedules
. Stats and comparisons

*** HTML Forms ***
Forms in HTML are how we collect data input from users --- like names, emails, messages, or even login info.

At the core, we use the the <form> tag (block element) to wrap everything. Inside it, we add different types of form controls.
ex: 
. <input> (inline block element) --- use for text, email, password, checkboxes, radio buttons, etc.
. <textarea> (inline block element) --- use for longer text
. <button> (inline block element) --- use for buttons
. <select> (inline block element) --- use for dropdowns
. <label> (inline block element) --- to submit/send the form data

ex: 
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">

  <label for="email">Email:</label>
  <input type="email" id="email" name="email">

  <button type="submit">Submit</button>
</form>
 . The for attribute in the <label> connects it to the input by ID,
 . The type attribute in <input> defines what kind of data to expect (text, email, number, date, checkbox, radio, submit, button),
 . The name attribute gives the data a label when it's sent

 When the user clicks submit, the form can send their data to the server.

 ----- Awesome job ----
 Now that you have learned the essential tags, how to structure your page with semantic elements, how to use comments , and build tables and forms... plus you have seen how attributes work---
 It's time to take things a step further.
 Let's talk about two powerful tools in HTML:
 "class" and "id"
These aren't visual elements like <p> or <div>, but they helps us style and target parts of our HTML using CSS (Cascading Style Sheets) or JavaScript (Programming language use for interactivity and more).

So what's the difference between "class" and "id"?
How do they work?
And when do we use one over the other?

# "class"
A class is like a nickname you can give to one or multiple elements.
ex:
<p class="highlight">This is a highlighted paragraph.</p>
<p class="highlight">This is another highlighted paragraph.</p>

Now, in your CSS, you can style all elements with that class.
In your html create the css tag like this:
<style>
    .highlight {
  color: blue;
  font-weight: bold;
}

</style>









