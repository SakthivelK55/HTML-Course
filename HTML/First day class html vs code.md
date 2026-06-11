#### HTML:                                              ### No Limits
----------

What is HTML?
	* HTML stands for hypertext Markup Language.
	* It is used for creating the structure of webpages.
	* The structure we want to create for that we have many html tags.

what is Hypertext?
	* Any text that contains link of an other webpages is called as hypertext.

what it is called as markup language?
	* Because of using html we are not writting any logics, only we are creating the structure.

what is tags?
	* Tag is the predefined word enclosed with angular braces.
	* In html we are having 2 types of tags.
		1) Paired tag
		2)Unpaired tag (or)	 self closing tag

paired tag:
	* Any tag which has a opening tag & closing tag is called paired tag
	Example:
			<h1> Welcome </h1>
	syntax:
			<tagname> Content </tagname>

unpaired tag:
	* Any tag that only the openning tag there no closing tag is called as Unpaired tag.
	syntax:
			<br>,<hr>,<img>,<meta>

## Structure of the html:
<!DOCTYPE html>
<html>
	<head>
		<title> </title>
	</head>
	<body>
	</body>
</html>



<!DOCTYPE html>
	* It is used to tell the browser which version of html we are using.
	* Currently we are using html version 5.

<html> </html>
	* It is the root tag of html structure.
	* All the content should be inside this root tag.

<head> </head>
	* It is used to provide the meta information.

<title> </title>
	* It is used to give the name of the tag.

<body> </body>
	* The content we want to display in the browser, everything should be written inside the tag.

#### Comment line in html:
--------------------------
		* We can use <!---- at the starting point and  ---> at the ending point to comment the lines.

#### Heading tag:
----------------
	* In html for proving head lines (heading/subheading) we need heading tag.
	* there are 6 heading tag in html.
	        <h1> </h1> to <h6> </h6>
	* Heading tag ar ePaired tag.
	* Heading tag are block level element.

	Example:

		<body>
				<h1> This is heading 1 </h1>
				<h2> This is heading 2 </h2>
				<h3> This is heading 3 </h3>
				<h4> This is heading 4 </h4>
				<h5> This is heading 5 </h5>
				<h6> This is heading 6 </h6>

		</body>

	NOTE:
		* <h1> </h1> tag is the biigest and <h6> </h6> is the smallest.
		* the default size of <h1> </h1> tag is 32 pixel.
	
#### Paragraph tag:
		* In html if we want towrite any text content that should be written by usong paragraph tags.
		* Paragraph tag is denoted by <p> </p>.
		* This is paired tag.
		* It is block level element.
		* The default size of <p> </p> tag is 16 pixel.
	

#### Formatting tags:
-------------------

* It is used to change the appearance/ format of the text content.
  
Example
<b> </b>
		* this is used to make the content bold.
   	
<strong> </strong>
		* it is also used to  make the content bold but this tag having " higher priority" compare to <b> </b> tag.
	
<i> </i>
		* it is used to make the content italic.

<em> </em>
		* this tag is used to make the content italic. like <input> tag.

<u> </u>
		* this tag is used to provide underline for the text.

<ins> </ins>
		* it is used to provide underline for the text.

<mark> </mark>
		* it is used to provide highlight for the text.

<sup> </sup>
		* it is used to write any content to the power.
	
<sub> </sub>
		*it is used to write the content in the base.

<q> </q>
		* it is used to provide double quotes around the tabs.

<prev> </prev>
		* it is pre formatter tag inside the tag how we will write the content it will display as it is.

<del> </del>
        * it is used to give strike through the text.
        
...................................................................................................
<br>
        * this tag id used to brake the line .
        * it helps to move the content in the next line.
        * it is unpaired tag.
<hr>
        * it is used to provide horizontal line.
        * it is unpaired tag.



### Elements:
-------------
		* elements is the combination of the tag and the content inside the tag.

## types of elements:
		we have 3 types

		1)Block level element
		2)Inline level element
        3)Inline block level element
	
## 1)Block level element
		* this elements will be taking full width of its parent and all of them will be displayed in next line.
		* we can provide "height and width"  for these elements

		Example:
			heading tags, <p></p>, <div></div>

## 2) Inline level element
		*these elements will be displaying in the same line.
		*we  can't provide height and width for these.
		* it is occupying  the content area.

		Example:
			<b></b>. <i></i>, <u> </u>, <span> </span>

## 3)Inline block level element
		* it is the combination of inline and block level elements
		*these elements will display in same line but we can provide height and width.

		Example:
			<button> </button>, <input> </input>, <img>

#### Attribute:

What is attributes?
		* Attributes are used to provide additional information to the tags.
		* Attributes should be written in the openning tags.

	Syntax:
		<tagname attributename= "value" > </tagname>

<img> tag
		* It is used to add the image in the webpage.
		* In this tag we have 4 attributes.
			1)source -- src :
				* It is used to provide the path of the image.

			2)Alternative name --- alt:
				* It is used to provide alternate message.
				* If the image is not displaying, that time this alt message will display on the page.

			3) Height, Weigth:
				* These are used for resizing the image.
				   ( give any one at a time height or weight)

		* <img> tag is self-closing / unpaired tag.
		* It is one "inline-block"  level element.


<marque> </marque>
		* It is used to make any content scrollable on the web page.
		* By default the content will scroll from left to right side.
	
### Attributes of marque tag:

	 1) Scroll amount:
	 	* It is used to determine the speed of the scrolling context.
		* By default value is "6".

	2) Direction:
		* It is used to detemine the direction of the scrolling content.
		* Value: => 'left','right','up','down'.

	3) Behaviour:
		* It is used to determine how the scrolling content will behave.
		* Value => 'Scroll','Slide','alternate'.
	
	4) Loop:
		* It determine how many times the content should scroll.

	5) Height / Width:
		* Used to resize the marque tag area.

#### List:
		* In HTML, a list is used to display a group of related items in an organized way.
		(or)
		* List is used to group the related elements together.

### types of list:
		1) Ordered list <ol>
		2) Unordered list <ul>
		3) Description list <dl>


### Ordered list tag:
---------------------
		* Ordered list is usedto group and arrange the elements in parrticular order
		* For creating this we need <ol> </ol> tag.
		* Inside <ol> </ol> tag for writting the items we need <li> </li> tag.
		* These tags are  "block level" element.

### Attributes in <ol> </ol> tag:
	1) Type Attribute:
		* This Attrinbute is used to change the list Style.
		 values are => 1, a, A, i, I
		 by default it takes number(1)

	2) start:
		* This is used to specify the starting value of the list-style.

	3) Reversed:
		* It is used to display the list-style in reverse order.

## Example:
		< ol> type="1" start="50" Reversed> 
		<li> Java </li>
		<li> python </li>
		<li> c++ </li>
	
	output:
		50. Java
		49. python
		48. c++

## Another example:

</head>
<body>
    <h1>list in html</h1>

<h1>ordered list</h1>
    
<h3>movie name</h3>
<ol>
        <li>MOM</li>
        <li>Van helsing</li>
        <li>Harry potter</li>
    </ol>
<h3>web series</h3>
    <ol Type="A">
        <li>Money heist</li>
        <li>From</li>
        <li>Dark</li>
    </ol>
<h3>Football players:</h3>
    <ol Type ="I">
        <li>Mbappe</li>
        <li>Cristiano Ronaldo</li>
        <li> Bellingham</li>
    </ol>
    
<h3>mobile brands:</h3>
    <ol Type="a" Start="7">
        <li>Apple</li>
        <li>Samsung</li>
        <li>Google</li>
    </ol>
<h3>Songs</h3>
    <ol start="100" Reversed>
        <li>First Class</li>
        <li>Mast Magan</li>
        <li>Deva Deva</li>
    </ol>

### Unordered list tag:
-----------------------
		* Unordered list is used to  crreated by using <ul> </ul>
		* Here we are grouping the elements together but they are not arranged in specific order.
		*Inside <ul> </ul> tag for writing the items we need <li> </li> tag.
		* By default it display the list-style as disc or bullet point.
		* Here we can provide only "Type attribute".
		* We can give 'disc','square','circle' etc...
		
## Example:
		<ul> type="circle" </ul>
		<li> sql </li>
		<li> selenium </li>
		<li> data </li>

## Another example:

<h1>Unordered list</h1>
<h3>Sports</h3>
    <ul>
        <li>Football</li>
        <li> Basketball</li>
        <li> Base Ball</li>
    </ul>
<h3>Cars</h3>
    <ul Type="square">
        <li>Toyota</li>
        <li>Maybach</li>
        <li>volkswagen</li>
    </ul>
<h3>Fruits</h3>
    <ul Type="None">
        <li>Apple</li>
        <li>Banana</li>
        <li>Grapes</li>
    </ul>

### Description list:
---------------------
		* For creating description list we need <dl> </dl> tag.
		* Inside that we have to use <dt> </dt> and <dd> </dd> tag.
		* <dt> </dt> tag is used to provide the  description term.
		* <dd> </dd> tag is uesd to provide then descriptipn definition for that term.

## Example:
		
<h2> Description list</h2>
<dl>
    <dt>HTML</dt>
        <dd>Hyper Text Markup Language</dd>
        <dt>CSS</dt>
        <dd>Cascading Style Sheet</dd>
        <dt>JS</dt>
        <dd>JavaScript</dd>


### <audio> </audio> tag:
-------------------------

		* This tag is used to add audio / music in our webpages.

### Attributes for audio tag:
	
* src 
		* It is used to provide the path of the audio.

* controls 
		* If we give this atttribute the =n only audio will be visible in webpage and we can control (play, pause, skip) the audio.

* autoplay
		* For this attribute music will start automatically whenever our page will be loading.

* Muted
		* It makes the audio mute.

* Loop
		* This attribute helps to play the audio infinite time in a loop.


### <video> </video> tag:
-------------------------
		* This tag is used to display the video on the webpage.

### Attributes for video tag:

* src, controls, loop, autoplay, muted * these attributes are  same as <audio> </audio> tag.

* poster
		* This attribute is used to provide image / thumbnail for the video.
		* In this attribute we have to provide the path of the image.

* Height, width
		* Used for resizing of the video.

### <iframe> </iframe> tag:
---------------------------
		* <iframe> </iframe> tag is used to add different webpages in our current webpage.
		* It is a inline block level element

### Attributes if <iframe> tag:
* src
		* In this attribute we have to provide the path of the webpage we want to add in our webpage.
		
* frameborder
		* It is used th provide outline/border around the content.
		* By default value is 0.

* Height & width
		* Used to provide the size of the content.


### Anchor tag :
----------------

		* anchor tag is denoted by <a></a> tag.
		* It is used to create hyperlink. ---------> image,video, etc.....
		* It is "inline level" element

### Attributes of anchor tag:
* href * 
		* It is used to take the path where we want to navigate.
		* It hepls to navigate / re-direct from one page to another page or in the same page one section to another section.

* target*
		* By default if we click any hyperlink it opens in the same tab., if we want to open in the different tab we need "target"  attribute.

		(target="_blank") is used to open in the next tab.

* title *
		* when we hover(keeping mouse cursor on the element) then "title" attribute helps to display some message.

# how to navigate in tha same page??
	Step 1: In which tag we want to navigate there we have to give "id" attribute.
	Step 2: which value we are giving for the id attribute, that same value we have to provide in the "href" attribute with "#"   symbol.
	
## Example:
-----------
	 
<a href="#myself" > About me</a>             ----------> this #myself is id, so we can move from the same page
    <a href="#projects"> MY project </a>      ----------> in this we use # for define the id
    <a href="#my works"> works</a>

<h3 id="myself"> About me</h3>
	<p>lorem400</p>        ---------------------> <p> large para is there </p>


### Selecting the lines in html:
--------------------------------
		* press the ALT tab at the line of tag and then select, which all the lines we want to change we select on it.



#### Table in HTML:
-------------------
		* Table is combination of rows and column.
		* For creating the table in html, we need <table> </table>   table tag.
		* Inside the table if we want to create the row, we need <tr></tr> tag.
		* Inside the row for giving the date, we need <td></td> tag.
		* For providing the heading data in table we ned <th></th> tag.
		* For giving the caption/title/name of the table we need <caption> </caption>    caption tag.

#### Attribute in table tag:
----------------------------
1) border:
	* It is used to provide border/outlinr around the total table.

2) Height and width:
	* Used to resize the table length.

3) cellspacing:
	* It is used to provide the space between the cells.

4) cellpadding:
	* It is used to provide the space inside the cell between the content and border.


#### Attribute for <td></td> and <th></th>:
-------------------------------------------
* rowspan:
	* this attribute is used to combine two or more than two rows.

* colspan:
	* this is used to combine two or more than two columns.

## Note:
--------
	* we have some extra tags in the table like
	<thread></thread>
	<tbody></tbody>
	<tfoot></tfoot>


### <div></div> tag:
--------------------
	* It is one block level element used to make the division.
	* inside this tag we can write inline / block and inline-block level elements.
	* we can provide height and width.

### <span></span> tag:
----------------------
	* it is one "inline level" element, used to select some part of block level element.
	* we can't provide height and width.


	