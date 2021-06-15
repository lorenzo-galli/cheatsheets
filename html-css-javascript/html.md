# HTML
Html is a programming language used to program websites
### Basic HTML Structure	
```html
<html>
 <head>
  <title>website title</title>
 </head>
 <body>
  content of website ...
 </body>
</html>
```


### Common Tags for Blogs	
```html
<h?> heading </h?>                        Heading (h1 for largest to h6 for smallest)
<p> paragraph </p>                        Paragraph of Text
<b> bold </b>                             Make text between tags bold
<i> italic </i>	                          Make text between tags italic
<a href="url"> link name </a>             Create a link to another page or website
<div> ... </div>                          Divide up page content into sections, and applying styles
<img src="filename.jpg">                  Show an image
<ul> <li> list </li> </ul>                Unordered, bullet-point list
<br>                                      Line Break (force a new line)
<span style="color:red"> red </span>      Use CSS style to change text colour
```


### Text Formatting	
```html
<h?> ... </h?>	Heading (?= 1 for largest to 6 for smallest, eg h1)
<b> ... </b>	Bold Text
<i> ... </i>	Italic Text
<u> ... </u>	Underline Text
<strike> ... </strike>	Strikeout
<sup> ... </sup>	Superscript - Smaller text placed below normal text
<sub> ... </sub>	Subscript - Smaller text placed below normal text
<small> ... </small>	Small - Fineprint size text
<tt> ... </tt>	Typewriter Text
<pre> ... </pre>	Pre-formatted Text
<blockquote> ... </blockquote>	Text Block Quote
<strong> ... </strong>	Strong - Shown as Bold in most browsers
<em> ... </em>	Emphasis - Shown as Italics in most browsers
<font> ... </font>	Font tag obsolete, use CSS. (*)
```


### Section division	
```html
<div> ... </div>	Division or Section of Page Content
<span> ... </span>	Section of text within other content
<p> ... </p>	Paragraph of Text
<br>	Line Break
<hr>	Basic Horizontal Line
<hr> Tag Attributes:	 
size="?"	Line Thickness in pixels
width="?"	Line Width in pixels
width="??%"	Line Width as a percentage
color="#??????"	Line Colour (*)
align="?"	Horizontal Alignment: left, center, right (*)
noshade	No 3D cut-out
<nobr> ... </nobr>	Line Break
```


### Images	
```html
<img src="url" alt="text">	Basic Image
```
#### <img> Tag Attributes:
```html	 
src="url"	URL or filename of image (required!)
alt="text"	Alternate Text (required!)
align="?"	Image alignment within surrounding text (*)
width="??"	Image width (in pixels or %)
height="??"	Image height (in pixels or %)
border="??"	Border thickness (in pixels) (*)
vspace="??"	Space above and below image (in pixels) (*)
hspace="??"	Space on either side of image (in pixels) (*)
```


### Linking Tags	
```html
<a href="url"> link text </a>	Basic Link
```
#### <a> Tag Attributes:
```html	 
href="url"	Location (url) of page to link to.
name="??"	Name of link (name of anchor, or name of bookmark)
target="?"	Link target location: _self, _blank, _top, _parent.
href="url#bookmark"	Link to a bookmark (defined with name attribute).
href="mailto:email"	Link which initiates an email (dependant on user's email client).
```

### Lists	
```html
<ol> ... </ol>	Ordered List
<ul> ... </ul>	Un-ordered List
<li> ... </li>	List Item (within ordered or unordered)
<ol type="?">	Ordered list type: A, a, I, i, 1
<ol start="??">	Ordered list starting value
<ul type="?">	Unordered list bullet type: disc, circle, square
<li value="??">	List Item Value (changes current and subsequent items)
<li type="??">	List Item Type (changes only current item)
<dl> ... </dl>	Definition List
<dt> ... </dt>	Term or phrase being defined
<dd> ... </dd>	Detailed Definition of term
```

### Tables	
```html
<table> ... </table>	Define a Table
<table> 
```
#### Table Attributes:
```html	 
border="?"	Thickness of outside border
bordercolor="#??????"	Border Colour
cellspacing="?"	Space between cells (pixels)
cellpadding="?"	Space between cell wall and content
align="??"	Horizontal Alignment: left, center, right (*)
bgcolor="#??????"	Background Colour (*)
width="??"	Table Width (pixels or %) (*)
height="??"	Table Height (pixels or %) (*)
<tr> ... </tr>	Table Row within table
<th> ... </th>	Header Cell within table row
<td> ... </td>	Table Cell within table row
```
#### <td> Tag Attributes:
```html	
colspan="?"	Number of columns the cell spans across (cell merge)
rowspan="?"	Number of row a cell spans across (cell merge)
width="??"	Cell Width (pixels or %) (*)
height="??"	Cell Height (pixels or %) (*)
bgcolor="#??????"	Background Colour (*)
align="??"	Horizontal Alignment: left, center, right (*)
valign="??"	Vertical Alignment: top, middle, bottom (*)
nowrap	Force no line breaks in a particular cell
```

### Tables	
```html
<frameset> ... </frameset>	Define the set of Frames
<frameset> 
```
#### Tag Attributes:
```html		 
rows="??,??, ..."	Define row sizes & number of rows (size in pixels or %)
cols="??,??, ..."	Define column sizes & number of columns (size in pixels or %)
noresize="noresize"	User cannot resize any frames in frameset
<frame> ... </frame>	Define a frame within the frameset
```
#### <frame> Tag Attributes:
```html	
src="url"	Location of HTML File for a frame
name="***"	Unique name of frame window
marginwidth="?"	Horizontal margin spacing inside frame (pixels)
marginheight="?"	Vertical margin spacing inside frame (pixels)
noresize="noresize"	Declare all frameset sizes as fixed
scrolling="***"	Can the user scroll inside the frame: yes, no, auto
frameborder="?"	Frame Border: (1=yes, 2=no)
bordercolor="#??????"	Border Colour (*)
<noframes> ... </noframes>	Unframed content (for browsers not supporting frames)
```


### Tables	
```html
<form> ... </form>	Form input group decleration
```
#### <form> Tag Attributes::
```html	 
action="url"	URL of Form Script
method="***"	Method of Form: get, post
enctype="***"	For File Upload: enctype="multipart/form-data"
<input> ... </input>	Input field within form
```
#### <input> Tag Attributes::
```html	
type="***"	Input Field Type: text, password, checkbox, submit etc.
name="***"	Form Field Name (for form processing script)
value="***"	Value of Input Field
size="***"	Field Size
maxlength="?"	Maximum Length of Input Field Data
checked	Mark selected field in radio button group or checkbox
<select> ... </select>	Select options from drop down list
```
#### <select> Tag Attributes:
```html	 
name="***"	Drop Down Combo-Box Name (for form processing script)
size="?"	Number of selectable options
multiple	Allow multiple selections
<option> ... </option>	Option (item) within drop down list
```
#### <option> Tag Attributes:
```html	
value="***"	Option Value
selected	Set option as default selected option
<textarea> ... </textarea>	Large area for text input
```
#### <textarea> Tag Attributes:
```html	 
name="***"	Text Area Name (for form processing script)
rows="?"	Number of rows of text shown
cols="?"	Number of columns (characters per rows)
wrap="***"	Word Wrapping: off, hard, soft
```


### Special Characters	
```html
&lt;	< - Less-Than Symbol
&gt;	> - Greater-Than Symbol
&amp;	& - Ampersand, or 'and' sign
&quot;	" - Quotation Mark
&copy;	© - Copyright Symbol
&trade;	™ - Trademark Symbol
&nbsp;	  - A space (non-breaking space)
&#??;	ISO 8859-1 character - replace ?? with the iso code
```


### Miscellaneous Tags
```html
<!-- ... -->	Comment within HTML source code
<!DOCTYPE html ... >	Document Type Definition (wiki)
<meta> ... </meta>	META information tag
```
#### <meta> Tag Attributes:
```html	 
name="***"	Meta name: description, keywords, author
http-equiv="***"	HTTP Equivalent Info: title, etc.
content="***"	Information content
<link>	LINK content relationship tag
```
#### <link> Tag Attributes:
```html	
rel="***"	Type of forward relationship
http="url"	Location (URL) of object or file being linked
type="***"	Type of object or file, eg: text/css
title="***"	Link title (optional)
```


### Body Background & Colours
#### <body> Tag Attributes:	 
```html
background="url"	Background Image (*)
bgcolor="#??????"	Background Colour (*)
text="#??????"	Document Text Colour (*)
link="#??????"	Link Colour (*)
vlink="#??????"	Visited Link Colour (*)
alink="#??????"	Active Link Colour (*)
bgproperties="fixed"	Background Properties - "Fixed" = non-scrolling watermark (*)
leftmargin="?"	Side Margin Size in Pixels (Internet Explorer) (*)
topmargin="?"	Top Margin Size in Pixels (Internet Explorer) (*)
```
