# HTML-Notes
The web consist of 3 types of programming languages 
-HTML 
-CSS
-Javascript

Definitions
Html
HTML grants access to a wide range of built-in-browser fuctionalities that can utuilize by incoprating specific html code
html is a language used to structure web pages
Html consist of tags;there is a closing tag <.p> and a opening tag</.p>

DOM tree - which stands Document Object Model ,it becomes important when you working with css or Javascript

HTMl Headlines <h1,2,3..>
used to create a headline , titles, headings and subheadings
these elements also convey a sense of heirarchy in ,showing what heading is more important and what is less important

HTML BOLD And Italics
there are 4 elements related to to this , 2 for bold and 2 for italics
italics
-first is to show how important the word is that is being emphasized
or it can be used to distinguish a phrase or title
- <.i> element is used to apply visual italics and the <em.> to add emphasis
BOLD
<strong.> element is used to show importance,seriousness or urgency
b is more generic and neutral

HTML List
there are 3 types of list: 
unordered list , ordered list and definition list

Unordered list - 
<li.> element, which represent a list item
a dot or a marker will appear before each item
to define the entire list and specify its type , we wrap it all in a <ul.> element ,which stand for unordered list

Ordered List

<ol.>- which stands for Ordered list , which shows there is a specific order to the items
mark each step in a (<li.>) element and then wrap the entire list in <ol.>

Definition List

<dt.> which represents a Definition list 
<dd.> which represent a Definiton Description , you can uses multiple <dd.> tags for each term
<dl.> the entire list will be wrapped in <dl.>tag
<hr>
HTML Quotes

<p.> for the paragraph
<cite.> to cite the author 
<blockquote.> wrap the whole thing in a <blockqoute.> element to make it Quote

the important thing is that elements should be nested within each other in a way that makes sense

<q.> element is used to make a quote 

<strong>,<b.>,<I.> and <em> are called inline , because they are meant to wrap around phares of text that are inline with the content

block-level elements like block quotes,paragraphs and unordered lists - it creates a seperate block on the page

HTML Attributes

It provides additional information to HTML elements,such as datetime attribute allows us to specify the date and time in a format that computers can understand.
it is written like <.time datetime=2025-05-08>May 8, 2025</.time>
<time.> element is used to mark anything that specifies a time of day,date or a duration for example:
<time.>May 8th</time> or <time.>May 8th 2025</.time>
you can also combine the date and time using the datetime attribute, first you would include the date and then the time.You can a couple of options to seperate them- you can use the T or simply leave a space.
it is not considered a global attribute

HTML code, pre and br
<(code></code.> )
element is used to showcase a snippet of code on a webpage without executing it
HTML entity="&It" typing this will show a less that sign and when yo u type "&gt"it will show a greater sign

BR element

it is used as a line break on a webpage,we can add a BR element to each line wihtout using a closing tag

pre element(needs a opening and closing tag)

Pre and code elements are often combined to display a code block with proper indentation
to preserve the formatting and spacing 

<hr>

HTML Superscripts,Subscripts and Small Text

Subscripts, superscripts, and small text can be used where you need to mark up certain bits of content as having a different meaning than the rest.

Subscripts

Subscripts are character that are set below the normal baseline for text-such has H20 the 2 is below the H and O <p.>H<.sub>2</.sub>0</.p>

Superscript

are characters that set above the normal baseline of text
such as square roots of numbers , or in the footnote in the example below
![image](https://github.com/user-attachments/assets/35492d4d-ae91-41f8-a560-251f798b0d47)

small 
![image](https://github.com/user-attachments/assets/6e99f7a1-6737-4196-973c-4a13c53c6451)

as seen in the image above the small elment can be used to make a text or phrase small so that it has less importance


HTML Attributes
note. that sonme attributes only work with some ,all dont work together

Class- it is used to assign a reusable name to any element, which can later be styled using CSS for all elments sharing that class

ID - the id is similiar to the class but we can only use unique names once an entire HTML page,IDs can be used for CSS targeting
the uniqueness of an ID name ensures that there will always just be one element with that ID,making it useful for javaScript or links.

content editable - allows interaction with the screen,keybaord and assistive devices
"lang" - allows us to specify the language of the content 
"Dir" - explicitly indicates the direction in which the text flows, using "LTR" for left-to-right scripts and "RTL" for right-to-left scripts

These attributes, "lang" and "dir," are considered Global Attributes and can be used on any HTML element.

<hr>

ARIA Roles
They are like extra attributes that we can add to HTML elements to make them more meaningful and help browser understand what they represent.
ARIA roles comes into play when we want to provide essential infromation ito assistive technologies like screen readers braille displays and magnifiers to ensure a website is fully accessible.

![image](https://github.com/user-attachments/assets/24e72fbe-a109-4a3d-b85b-d47405b7fda4)
<span> is used to mark up a part of text or part of a document

The accessibility tree is like a companion to the DOM tree, which the browser creates from the website's content.While the DOM tree represents the structure of the HTML, the accessibility tree is crucial for assistive devices like screen readers

To start, add an ARIA label to the HTML, which specifies the text that the screen reader will read. In this case, set the ARIA label to "hello world." Additionally, hide the individual letters by enclosing them within a div element and setting the ARIA hidden attribute to true. This removes the div and its contents from the accessibility tree while keeping them in the DOM tree. After reloading the page, the separate letter containers disappear, and we are left with a clear heading of "hello world."

<hr>

Formatting HTML
comments start <!--"...."> comments should be inside your html so that whoever reads your code understands why you did it like that

Self-closing elements 
most elements in HTMl has a opening and closing tag.

non-breaking spaces
this tells the browser not to break the line between two words. for example , if we want to keep "lebron" and "James"together in a setence we would use the code "&nbsp"

another use for it is if you want to create more than one space between a word 
Developer mode is used to access the debugging mode of a web page

<hr>

HTML NAVIGATION and Linking

when we want to create a link we use the A element , which stand for anchor. we then need to add the href attribute with the URL enclosed in a quote.

HTML URL Pathways
the slashes in a URL indicates that it should look further into the file structure.To create a relative URL, omit the domain name but include the initial slash at the beginning. This tells the browser to start from the root level of the file structure

![image](https://github.com/user-attachments/assets/c20e68c7-1a16-4a7f-b68e-e6cf5330098d)

in the example above...say we want to create a link for logo.gif which is located in the directory named styles,we would write the URL like such:

/images/logo.gif 
../images/logo.gif

The first version, /images/logo.gif, creates a URL that is relative to the root level. It means the browser will start looking for the file from the root of the website. On the other hand, the second version, ../images/logo.gif, creates a URL that is relative to the location of the file where the URL is written. The ".." followed by a slash means going up one level in the directory structure

One important thing to note is that it does not matter whether you include a trailing slash or not in a URL, both versions will take you to the same place.

<hr>

Relative and absolute URLs

when you see a URL like http://www.awesomedogs.com/people, it is looking for a file called index.html inside the folder called people.

Note. THIs only works for HTML files.

To summarize, URLs can be either relative or absolute. Relative URLs are based on the current file's location, while absolute URLs start from the root of the website. By using folders and index.html files, we can create clean and user-friendly URLs. 

Navigation
Menus and Navigation bars
to create a menu navigation , first you would create a NAV element to indicate that it is the sites navigation.next you would create a list using the LI element and a anchor element A to link each listed item with the correct URL

Breadcrumb trail menu

you would create it the same way but this time you would use a OL , since the order of the list matters

Footer Links
use a footer element and a A element to create a footer

HTML Working with Graphics and Images

<hr>

Images

when we want to use images in our webpages we simpliar need to use the element IMG.IMG element only has a clsoing tag

1.first we need to establish the source attribute,(SRC) it tells the browser which image file to load
2.then there is a the (ALT), which provides a text description of a image, it is also used incase the image does not load.ALT can be left blank as well 

3.then we have the width and height attributes , which determines the size of the image , Every image needs these 4 attributes.Dont forget to add the pixel as well to your sizes

<hr>

Image Formats
there are 4 main file formats such as: GIF,SVG,JPG,PNG

GIF- GIFs are great for compressing illusttraions that have large areas of the same color,but when it comes to photographs it falls short because it only supports 256 colors and images can en up looking pixelated

SVG- these formast are great for logos,icons and other types of illustrations.it is a vector file,which means it can be scaled to any size without losing quality and the file size remains small.

JPG-when using JPG it is important to resize and compress them appropriately.Avoid using big images because it will slow down the loading speed.

PNG-it is a newer format that works well when you need transparency in a photograph.

Resposive Images

HTML allows us to deliver different image files to screens of different sizes. We can create multiple image files and include them as options in our HTML code.Each entry includes a URL to the file, the resolution (e.g. 2X, 3X, 4X, 1.5X), and so on

Resposive Width

src set, where we can provide a set of images for different resolutions or let the browser choose based on density and viewport width.The sizes attribute allows us to specify how much of the viewport's width the image will take up at each breakpoint.

Figcaption and Figures

after you have inserted a imgage to your code , next you want to add a caption to it.Frist you would add a figcaption element to wrap the caption text you want and then wrap the whole image and caption in a Figure element

<hr>

Working with media 

Audio
audio controls src="audio file" and end with a closing tag 

just like the img element we have a source attribute

HTML Generic Elements,Div and Span
DIV were used to create sections,sidebars and evrything in between.Some developers even put their titles in divs and make spans pretend to be buttons.Div is a block-level element, while span is an inline element. They essentially do nothing until CSS or Javascript is applied to them

Div would be used to create a section and whatever you do inside that block element it only applies inside that

Span works the same way but only to a specifi line , the sentence wont break to the next line

<hr>

8 August 2024

Document Head

inside the document head you need to put important infromation that the browser needs to know about the website.The character set is not something you want your users to see, it is intended for the browser. To convey this, use the meta element.The Meta element should always be placed inside the head element as they provide the metadata about the webpage.

The HTML head serves as a central hub for connecting and setting up various components, ensuring that all assets are loaded and sharing page information with other sites and platforms

to define a character set you would use the 'meta charset="utf-8".

Title element will appear on the browser tab or bookmark when it is saved.

Link element -The link element is a crucial component used extensively within the head section. It serves to connect various assets that should load, such as CSS files, fonts, and favicons. To inform the browser about the type of asset, utilize the rel attribute.

Link rel="icon" href="icon_location" type="image/icon type" - this is used to create a icon for your website

![image](https://github.com/user-attachments/assets/a9712287-628f-4d60-84a9-72906c6e287e)
The script tag is a commonly used element in an HTML document's head. It instructs the browser to load a JavaScript file. Although it is typically placed at the end of the document, some also include it in the head. 

Content structure

Main , header , footer,article . section, aside

Main element - it is only used once per page,and tells the browser where the main content is

Header-Do not confuse header with head though. Head is where the file's metadata lives and is not displayed to users. Header is used for site headers, article headers, and headers within the content. A header is usually found at the top of most web pages and may include a logo, site name, and navigation.

Article-An article often starts with a title, subtitle, author's name, and publication date, which can also be considered a header. Many web pages end with a footer at the bottom, containing links, copyright information, and additional details about the company.The article element wraps around any type of content unit, whether it is a long written article, a short snippet, a teaser card, a tweet, or even an app element. It represents a standalone unit of content.

Sections - The section element is used to mark sections of content. For example, in a long essay with subheadings, each segment can be wrapped in a section element. It is also useful for dividing different topic zones on a website. Each section typically starts with its own headline.

Aside-Lastly, the aside element is for content that is off to the side, like sidebar information or additional details that accompany an article but are not part of its main flow.

Forms

To create a form, we start with the form element, which informs the browser about the presence of a form using opening and closing tags. In the newsletter signup form, there will be two fields: name and email. These field names can be turned into labels using the label element.Use the input element to provide places for users to input their name and email. Unlike other elements, the input element does not have a closing tag due to its older structure. It acts as a marker for the browser to bring in functionality and place it there.

Now, a button is needed for users to submit the form. Use the button element for this. The text on the button can be customized to whatever is required.To make it accessible to everyone, we need to address the issue of the label and input elements not being connected. There are two options to achieve this. Add a "for" attribute to the label that matches the "id" attribute of the input. 
Wrap the input with the label. 

in order for the text boxes to work properly we need to add a type attribute to specify which type of data we need to collect from a user.placeholders attribute gives the user a example on what to type.The value attribute is for including such data in the form. If both are included into the example, and the form is submitted to compare the results, the information that was displayed by placeholder is not submitted as real data. The information that was pre-populated by value is

HTML Tables

To create an HTML table, you use several different HTML elements in just the right combination. Table, TR, TH, and TD.The table element wraps around the whole table, around all our content and markup for that table, marking the beginning and end of the table itself. The TR element stands for table row and wraps around a set of elements, defining them as belonging to the same row. The TH element stands for table header and defines a header for a column. The TD element stands for table data and marks up the cells of data. 

![image](https://github.com/user-attachments/assets/60a692a7-8ae5-48e5-aac3-5ff98a3fee89)

use TD element for the data of the table and for the heading you should use TH and the TR is for the amount of rows you want enclose all the content in a TABLE element
