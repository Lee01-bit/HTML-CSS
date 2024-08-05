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
<b> is more generic and neutral

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
you can also combine the date adn time using the datetime attribute, first you would include the date and then the time.You can a couple of options to seperate them- you can use the T or simply leave a space.

HTML code, pre and br
<(code></code.> )
element is used to showcase a snippet of code on a webpage without executing it
HTML entity="&It" typing this will show a less that sign and when yo u type "&gt"it will show a greater sign

BR element

it is used as a line break on a webpage,we can add a BR element to each line wihtout using a closing tag

pre element(needs a opening and closing tag)

Pre and code elements are often combined to display a code block with proper indentation
to preserve the formatting and spacing 

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
note. thta sonme attributes only work with some ,all dont work together

Class- it is used to assign a reusable naem to any element, which can later be styled using CSS for all elments sharing that class

ID - the id is similiar to the class but we can only use unique names once an entire HTML page,IDs can be used for CSS targeting
the uniqueness of an ID name ensures that there will always just be one element with that ID,making it useful for javaScript or links.

content editable - allows interaction with the screen,keybaord and assistive devices
"lang" - allows us to specify the language of the content 
"Dir" - 

