# HTML: The Structure

* HTML is the language used to build the the structure or framework of a website. It does not contain any pretty styling but just the basic formatted text and images of a page. 
* HTML consists of a title, a header or heading, a body of the page and sometimes a footer. It also contains paragraph texts and different font sizes utilizing heading tags.
* HTML tags look like this: <p></p> -- which is an opening and closing tag. The first tag <> contains whatever the element is whether thats paragraph(p), body(body) or more.   The closing tag </> contains a back slash in order to complete the HTML tag and allow it to show.
* Attributes: attributes are used inside of an HTML tag in order to decribe and give more information about an HTML. You have ID and Class attributes that can give more meaning to a tag.
* Elements: You have block elements and inline elements. Block elements take up an entire page and dont allow other information on the page to be shared in the same area. This includes:<h1>, <p>, <ul>, and <li> tags. Inline elements allow information to be shared side by side on the same line of a webpage. This includes: <a>, <b>, <em> and <img> tags.
* Here is more info on each tag/attribute and element:

 Line Break Element
The <br> line break element will create a line break in text and is especially useful where a division of text is required, like in a postal address. The line break element requires only an opening tag and must not have a closing tag.

 Image Element
HTML image <img> elements embed images in documents. The src attribute contains the image URL and is mandatory. <img> is an empty element meaning it should not have a closing tag.

<h1>-<h6> Heading Elements
HTML can use six different levels of heading elements. The heading elements are ordered from the highest level <h1> to the lowest level <h6>.

 Paragraph Element
The <p> paragraph element contains and displays a block of text.

HTML Attributes
HTML attributes are values added to the opening tag of an element to configure the element or change the element’s default behavior. In the provided example, we are giving the <p> (paragraph) element a unique identifier using the id attribute and changing the color of the default text using the style attribute.


oUnordered List Element
The <ul> unordered list element is used to create a list of items in no particular order. Each individual list item will have a bullet point by default.

alt Attribute
An <img> element can have alternative text via the alt attribute. The alternative text will be displayed if an image fails to render due to an incorrect URL, if the image format is not supported by the browser, if the image is blocked from being displayed, or if the image has not been received from the URL.

The text will be read aloud if screen reading software is used and helps support visually impaired users by providing a text descriptor for the image content on a webpage.


Unique ID Attributes
In HTML, specific and unique id attributes can be assigned to different elements in order to differentiate between them.

When needed, the id value can be called upon by CSS and JavaScript to manipulate, format, and perform specific instructions on that element and that element only. Valid id attributes should begin with a letter and should only contain letters (a-Z), digits (0-9), hyphens (-), underscores (_), and periods (.).

<body> Body Element
The <body> element represents the content of an HTML document. Content inside <body> tags are rendered on the web browsers.

Note: There can be only one <body> element in a document.
Span Element
The <span> element is an inline container for text and can be used to group text for styling purposes. However, as <span> is a generic container to separate pieces of text from a larger body of text, its use should be avoided if a more semantic element is available.

 Strong Element
The <strong> element highlights important, serious, or urgent text and browsers will normally render this highlighted text in bold by default.

HTML Element
An HTML element is a piece of content in an HTML document and uses the following syntax: opening tag + content + closing tag. In the code provided:


HTML Tag
The syntax for a single HTML tag is an opening angle bracket < followed by the element name and a closing angle bracket >. Here is an example of an opening <div> tag.


Anchor Element
The <a> anchor element is used to create hyperlinks in an HTML document. The hyperlinks can point to other webpages, files on the same server, a location on the same page, or any other URL via the hyperlink reference attribute, href. The href determines the location the anchor element points to.


Head Element
The <head> element contains general information about an HTML page that isn’t displayed on the page itself. This information is called metadata and includes things like the title of the HTML document and links to stylesheets.
