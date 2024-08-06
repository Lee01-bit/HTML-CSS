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
