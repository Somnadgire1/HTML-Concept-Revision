# HTML-Concept-Revision
1.What is HTML?
HTML stand for Hyper Text Markup Language which is used for creating web pages and web applications.
It is used to make a basic structure of any website.

2.What do you mean by a markup language?
It's a computer language that is used to apply layout and formating conventions to text document.
Can you share examples of other markup languages and how they differ from HTML?
a)Examples of other markup langauages - 
i)LaTex
ii)Extensible Markup Language (XML)
iii)Generalized Markup Language (GML)
iv)Standard Generalized Markup Language (SGML)
b)Differences - 
Tags are defined according to the developer's criteria.	
Is a markup language that serves as a standard for other markup languages.
SGML is that it does not support style sheets.
data interchanging is also complex in SGML.

3.What version of HTML do you use in your projects? How is HTML 5 different from HTML 4?
HTML5 is the next revision of the HTML standard superseding HTML 4.01. HTML5 is a standard for structuring and presenting content on the World Wide Web.

HTML4
It is 4th version of Html.
It is older version of Html5, so have less features compared to html5.
It does no provide better error handling like html5.
In Html4 these supported provided by third party Silverlight and flash.

HTML5
It is extension of html4. it is 5th version of html.
Html5 is very simple compared to html4.
Html5 provides consistency in malformed documents.
it has better error handling.
Multimedia support provided by Html5.

4.What are attributes in HTML?
HTML attributes are special words which provide additional information about the elements or attributes are the modifier of the HTML element.
Each element or tag can have attributes, which defines the behaviour of that element.
Attributes should always be applied with start tag.
The Attribute should always be applied with its name and value pair.
The Attributes name and values are case sensitive, and it is recommended by W3C that it should be written in Lowercase only.
You can add multiple attributes in one HTML element, but need to give space between two attributes.

5.What are data- attributes good for?
The syntax is simple. Any attribute on any element whose attribute name starts with data- is a data attribute. Say you have an article and you want to store some extra information that doesn't have any visual representation

6.Describe the difference between &<script>, <script async> and <script defer>.
a)Script-
Pause the document parser
Create a new request to download the script
Execute the script after it's downloaded completely
Continue parsing the document
b)Script async-
After an async script is downloaded, the browser will pause the document parser, execute the script and resume parsing the document.
c)Script defer-
The defer script, on the other hand, will be executed only when the parser has completed its job.

7.Why is it generally a good idea to position CSS <link>s between <head></head&> and JS <script>s just before </body>? Do you know any exceptions?
You usually put the <link> tags in between the <head> to prevent Flash of Unstyled Content which gives the user something to look at while the rest of the page is being parsed.
Since Javascript blocks rendering by default, and the DOM and CSSOM construction can be also be delayed, it is usually best to keep scripts at the bottom of the page.
Exceptions are if you grab the scripts asynchronously, or at least defer them to the end of the page.