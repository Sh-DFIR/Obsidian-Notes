# HTML

### Learning Resources

[Learn HTML for Web Development - Studytonight](https://www.studytonight.com/code/html-course/)

> [!NOTE] Reminder
> 💡 Different Between HTML elements and tag HTML Tags refer to the name surrounded by open and closing bracket. E.g. `<body>`. HTML elements on the other hand is nothing but a HTML tag along  with its content. HTML elements are like this `<p> Content </p>.`



# What is HTML?

HTML stands for Hypertext Markup Language and is used to for the website’s content and structure. HTML is the **language in which most websites are written**. HTML is used to create pages and make them functional.

### History of HTML
HTML was first created by Tim <u>Berners-Lee</u>, <u>Robert Cailliau</u>, and others starting in *1989*. It stands for Hyper Text Markup Language.

Hypertext means that the document contains **links that allow the reader to jump to other places** in the document or to another document altogether. The latest version is known as [HTML5](https://html.com/html5/).

A **Markup Language** is a way that computers speak to each other to control how text is processed and presented. To do this HTML uses two things: tags and **attributes**.

### HTML Tags and Attributes

[Tags](https://html.com/tags/) are used to **mark up the start of an HTML element** and they are usually enclosed in angle brackets. An example of a tag is: `<h1>`.

[Attributes](https://html.com/attributes/) contain **additional pieces of information**. Attributes take the form of an opening tag and additional info is **placed inside**. An example of an attribute is:

`<img src="mydog.jpg" alt="A photo of my dog.">`

### Golden Rules to Remember

1. The vast majority of tags must be **opened** (`<tag>`) and **closed** (`</tag>`) with the element information such as a title or text resting between the tags.
2. When using multiple tags, the tags must be **closed in the order in which they were opened**. For example:`<strong><em>This is really important!</em></strong>`

### Tags
- **Body Tag** - This is is where we add the content which is designed for viewing by human eyes. <body></body>
- **Title Tag** — This is where we **insert the page name** as it will appear at the top of the browser window or tab. <title></title>
- **Meta Tag** — This is where information *about* the document is stored: character encoding, name (page context), description. Syntax: `<meta>`
- **Heading Tags** — These are tags to create heading. It automatically adds one line before and after the tag
    - Syntax: `<h1>, <h2>, <h3>, <h4>, <h5>...`
- **Paragraph Tag** — This tag is used to create paragraphs. Syntax: `<p>`
- **Break Tag** — The break tag inserts a single line break and this tag has to closing tag. Whenever you want to change lines add this tag and the text after this tag will come on the next line. This is a good tag because manually spacing content does not work  in html because html ignores spaces.Syntax `<br>`
- **Horizontal Tag** — This tag inserts a horizontal line and this tag also doesn’t have a closing tag. Syntax: `<hr>`
- **Comments** — This tag is ignored and are not displayed in the browser. This can be used to add comments in the HTML document. Syntax: `<!-- comment goes in here -->`

#### Formatting Text

- **Bold Tag** — words or sentences between these tag will appear bold. Syntax: `<b>`
- **Strong Tag** — This works similarly with the bold tag but semantic wise this has an importance set to it, like when someone uses a screen reader the dialogue will say is with more emphasis. Syntax: `<strong>`
- **Italics Tag **— This tag is used to give italics style. Syntax: `<i>`
- **Emphasis Tag** — This tag is used to also give an italic look but just like the strong tag it gives more importance to the information semantically. Syntax: `<em>`
- **Underline Tag **— This tag is used to underline text. Syntax: `<u>`
- **Small Tag** — This tag is used to make text small as compared to others around it. Syntax: `<small>`

**Creating Hyperlink** - It is a link to another resource and the link behind the hypertext

- **Anchor Element** — This used to create a link to another resource (webpage, specific part of the website, file, etc.). Syntax: `<a>`
    - *href attribute* - This attribute unlike other attributes associated with the anchor tag is mandatory. This is used to put/create the hyperlink. <u>href</u> is short for hypertext reference.
- **Image Tag** — This tag is used to add images to your website. This tag is an empty tag like break line and horizontal line tags. Syntax: `<img>`
    - *src* — the source attribute is used to specify the location of the image to be added.
    - *alt* — the alt attribute meas alternatives, this is used to replace the image with text, usually text describing the image, when the an error occurs relating the image that disallows it to be displayed.

Table of elements and their purpose

| Element  | Meaning | Purpose |
| --- | --- | --- |
| `<b>` | Bold | Highlight important information |
| `<strong>` | Strong | Similarly to bold, to highlight key text |
| `<i>` | Italic | To denote text |
| `<em>` | Emphasized Text | Usually used as image captions |
| `<mark>` | Marked Text | Highlight the background of the text |
| `<small>` | Small Text | To shrink the text |
| `<strike>` | Strike Out Text | To place a horizontal line across the text |
| `<u>` | Underlined Text | Used for links or text highlights |
| `<ins>` | Inserted Text | Displayed with an underline to show an inserted text |
| `<sub>` | Subscript Text | Typographical stylistic choice |
| `<sup>` | Superscript Text | Another typographical presentation style |

#### HTML Lists
**Ordered List** — This creates an ordered list in html meaning it has numbers or any other hierarchical system like letters. Syntax: `<ol></ol>`.
There are three attributes for ordered list:
1. reversed
2. start
3. type

Adding **reversed** attribute to the `ol` tag specifies that the list order should be descending.
```html
<ol reversed>
</ol>
```
Adding **start** attribute with a value,specifies the start value for an ordered list.
```html
<ol start="10">
</ol>
```
Adding **type** attribute specifies the type of marker to use for the list items.
```html
<ol type="A">
<ol>
```

**Unordered List** — This is the opposite of the ordered list, this list has symbols that denote no order like bullet points, star, etc. Syntax ```<ul></ul>```

**List item** — This tag is always nested within list, this specify the items in a list. Syntax: `<li></li>`

**Description List** — This tag represents the description of the list. The description list allows you to create a list of terms and then provide one or more descriptions for each term. Syntax: `<dl></dl>` 

---
## Working with Images
You can include pictures in your web page using HTML `<img>` tag. This is an empty tag and it has `/` just before the closing angular bracket. E.g. 
```html
<img src="Path/to/image" />
```
---

## Introduction to Tables
Tables are used on webpages for two major purposes mentioned below:
- The obvious purpose of arranging information in a tabular form.
- The less obvious, but widely used, purpose of creating the pages layout with the use of hidden tables.

The use of tables for creating a page layout is not recommended since the advent of CSS.

Opening and closing `<table>` tag is used to represent data intabular form.

### Rows 
In HTML rows are added into the table using the opening and closing `<tr>` tag.

In the case of Tables, adding just the rows is not enough, we must include columns too, to create tabular cells. You can add `border = "1"` in the table tag, so that you can see the border.

### Columns in a Row
To add columns into any row inside the table, we have to include the opening and closing `<td>` tag, between the opening and closing `<tr>` tag, and the data will come inside the column.

Hence the table structuer becomes like this,
```html
<table>
	<tr>
		<td> 
			Hello
		</td>
	</tr>
</table>	
```

The `<td>` tag will display on each column within its row.

### Body and Head of Table
Like we have the body section of an HTML page, similarly everythin inside a Table is table body.

It is not mandatory, but good practice to specify the Table body, by using the opening and closing `<tbody>` tag. All the rows holding data to be represented in tabular form, must be inside the table body using the `<tbody>` tag.

When we create a table with multiple rows and columns of data, we also provide headings to specify what type of data does each column contains. These headings are enclosed inside the table head, which is specified using opening and closing `<thead>` tag.

The Head section of the table can be specified using the `<thead>`

Inside the opening and closing `<thead>` tag, we will have a row in which we can add multiple columns, to hold the headings. This row is created using the `<tr>` tag, but the columns inside the row, which will be holding the headings, are created using the `<th>` tag.

###### The `<th>` tag
`<th>` tag is used to specify the Header cell in a table row, whereas the `<td>` tag is used for standard data cells. The `<th>` tag can be used anywhere inside the table, but it should be used only where you need to provide headings.

### Customizing the Table
There are many ways in which you can modify the strucutre of your columns as per your requirements. 

Following are two very important attributes that are very useful while creating complex tables.
1. **colspan**
2. **rowspan**

##### Colspan
This attribute allows you to increase the width of a column, making it equal to 2 columns or 3 columns or n columns depending upon the value given to this attribute.

Check out the illustration below for example syntax:
![[Pasted image 20220531214942.png]]

##### Rowspan
`rowspan` attribute allows you to increase the height of a column, making it equal to 2 rows or 3 rows or n rows depending upon the value given to this attribute. 

Check out the illustration below for example and syntax:
![[Pasted image 20220531215106.png]]

Both the attributes, namely `colspan` and `rowspan` can be used with both, the standard data cells created using `<td>` tag and the Header cells created using `<td>` tag.

## Div and Span
`div` tag used to divide an HTML page into sections of content. It is usually used as a container for other HTML tags. It is one of the most widely used tag.

### Block-level Elements
- Block-level elements start on new line.
- If no width is set, it takes the full width available.
**NOTE: Tags are also called Elements**

`div` tag is a block level element
`style` attribute can be added to `div` tag to style it.
