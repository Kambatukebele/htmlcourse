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
=> HTML stands for Hyper Text Markup Language. 
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

### Example Explained
. <!DOCTYPE html> is a declaration that defines that this document is an HTML document
. <html> is the root element of an HTML page
. <head> is the element that contains meta information about the HTML page (ex: specify the language, SEO tags, Facebook tags, google tags, etc)
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

*** Nexted HTML element ***
HTML element can be nested (this means that elements can contain other elements).

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
The HTML <pre> element defines preformattsed text.
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









