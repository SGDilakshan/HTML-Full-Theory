# HTML Full Theory  

Here, you can learn HTML Full Theory with structured examples and explanations.  

## 01 - Introduction to HTML  

This is a basic HTML document that displays "Hello world!" on a webpage.  
### Structure:  
- `<DOCTYPE html>` Declares the document as HTML5.  
- `<html>` The root element of the document.  
- `<head>` Contains meta-information, including the title and description.  
- `<title>` Sets the webpage title (shown in the browser tab).  
- `<meta>` Provides a description of the webpage for search engines.  
- `<body>` Contains the visible content of the webpage.  
- `<h1>` Displays the main heading on the page.  

---------------------------------------------------------------------------

## 02 - HTML Tags and Elements Basics  

This HTML file demonstrates basic tags and elements.  
### Key Features:  
- `<h1>` Displays Sivanathan Dilakshan with a red color.  
- `<span>` Used inside the heading for styling purposes.  
- `<p>` Currently empty.  
- `<a>` A clickable link to Google.  
- `<style>` Changes the heading color to red.  

---------------------------------------------------------------------------

## 03 - Formatting Text in HTML  

This HTML file demonstrates basic text formatting tags.  
### Key Features:  
- `<h1>` to `<h6>` Different levels of headings.  
- `<p>` Contains styled text.  
- `<b>` and `<strong>` Highlights important text.  
- `<em>` Emphasized text.  
- `<u>` Underlined text.  
- `<mark>` Highlights text.  
- `<ins>` and `<del>` Shows text modifications.  
- `<sub>` and `<sup>` Displays small text above or below.  
- `<dfn>` Defines a term.  
- `<kbd>` Represents keyboard input.  
- `<pre>` Maintains text formatting.  
- `<time>` Displays a timestamp.  
- `<q>` Adds inline quotes.  

This file showcases various text formatting styles in HTML.  

---------------------------------------------------------------------------

## 04 - Line Breaks and Comments in HTML  

This HTML file demonstrates line breaks and comments in HTML.  
### Key Features:  
- `<!-- -->` Adds comments inside the HTML code.  
- `<p>` Defines a paragraph.  
- `<br>` Inserts a line break within text.  
- `<br/>` Another way to add a line break (self-closing).  
- `<hr>` Creates a horizontal line.  

This file showcases how to use line breaks and comments in HTML.  

---------------------------------------------------------------------------

## 05 - HTML Quotation and Citation Elements  

This HTML file demonstrates quotation and citation tags.  
### Key Features:  
- `<blockquote>` Defines a block of text for a quote, with a citation link.  
- `<abbr>` Represents an abbreviation, with an optional title attribute for full form.  
- `<address>` Represents contact information for the author or owner of the document.  
- `<cite>` Cites a reference or source of the quote.  
- `<bdo>` Controls the text direction (in this example, right-to-left).  

This file showcases how to use various quotation and citation elements in HTML.  

---------------------------------------------------------------------------

## 06_HTML links
This HTML file demonstrates the use of links and the `mailto` feature.

## Key Features:
- **`<a href="new.html">Click here</a>`**: A clickable link that redirects to `new.html`.
- **`<p id="this">Lorem ipsum dolor sit, amet consectetur adipisicing elit...`**: A paragraph with some placeholder text.
- **`<a href="mailto:test@gmail.com">Send mail</a>`**: A link that opens the default mail client to send an email to `test@gmail.com`.

---------------------------------------------------------------------------

# 07_HTML images

This HTML file demonstrates how to use images and image maps in HTML.  

## Key Features:  
- **`<img>`**: Displays an image with attributes:  
  - `src="./falls-nature.jpg"`: Sets the image source.  
  - `width="300" height="300"`: Defines the image size.  
  - `alt="Fall nature"`: Provides alternative text for accessibility.  
  - `usemap="#map_name"`: Links the image to a map.  

- **`<map name="map_name">`**: Defines an image map with clickable areas.  

- **`<area>`**: Creates clickable areas on the image:  
  - `shape="rect" coords="0,0,100,100"`: Defines a rectangular clickable area linking to [Google](https://google.com).  
  - `shape="circle" coords="150,150,50"`: Defines a circular clickable area linking to [YouTube](https://youtube.com).    

---------------------------------------------------------------------------

# 08_HTML Entities 

This HTML file demonstrates the use of **HTML entities** to display special characters.  
## Key Features:  

- **`&amp;`**: Displays `&` (ampersand).  
- **`&nbsp;`**: Adds a non-breaking space.  
- **`&copy;`**: Displays `©` (copyright symbol).  
- **`&quot;`**: Displays `"` (double quotation mark).  
- **`&lt;h3&gt;`**: Displays `<h3>` as text instead of rendering it as an HTML element.  

This file is useful for displaying reserved characters in HTML without affecting the document structure.  

---------------------------------------------------------------------------

# 09_Generic HTML Elements  

This HTML file demonstrates the use of **generic container elements** in HTML.  
## Key Features:  

- **`<div>`**:  
  - A block-level container used for grouping elements.  
  - Styled with `border: 1px solid black;` to show its boundaries.  

- **`<span>`**:  
  - An inline container used for styling specific portions of text.  
  - Styled with `border: 1px solid black;` to show its boundaries.  

This file highlights the difference between **block-level (`<div>`)** and **inline (`<span>`)** elements in HTML.  

---------------------------------------------------------------------------

# 10_HTML Lists

This HTML file demonstrates different types of lists in HTML, including unordered lists, ordered lists, nested lists, description lists, and list items with links.  
## Key Features:  

- **`<ul>` (Unordered List)**  
  - Displays a bulleted list.  
  - Example: Days of the week in an unordered list.  

- **`<ol>` (Ordered List)**  
  - Displays a numbered list.  
  - Example: Days of the week in an ordered list.  
  - Supports attributes like `type="I"` and `start="10"`.  

- **Nested Lists**  
  - Unordered list inside another unordered list.  
  - Ordered list inside another ordered list.  

- **List Items with Links**  
  - `<a href="https://www.google.com" target="_blank">`: Opens a link in a new tab.  

- **`<dl>` (Description List)**  
  - `<dt>` (Definition Term): Represents the term.  
  - `<dd>` (Definition Description): Provides the definition.  

This file showcases various ways to structure and format lists in HTML.  

---------------------------------------------------------------------------

# 11_HTML iFrames

This HTML file demonstrates the use of **iFrames** to embed external content and link navigation within an iframe.  
## Key Features:  

- **`<iframe src="new.html" frameborder="10" width="300" height="300" name="iframe">`**  
  - Embeds an external page (`new.html`) within the current page.  
  - `frameborder="10"`: Adds a border around the iframe.  
  - `width="300" height="300"`: Defines iframe dimensions.  
  - `name="iframe"`: Allows targeting from links.  

- **`<a href="new1.html" target="iframe">Click here</a>`**  
  - Opens `new1.html` inside the iframe instead of a new page.  

- **YouTube Video Embed**  
  - `<iframe src="https://www.youtube.com/embed/E5CG7PUyBk0"... allowfullscreen>`  
  - Embeds a YouTube video within the page.  
  - Supports attributes like `allowfullscreen` for full-screen playback.  

This file demonstrates how to embed external pages and videos using iFrames in HTML.  

---------------------------------------------------------------------------

# 12_HTML Tables  

This HTML file demonstrates the creation and styling of **tables** in HTML.  
## Key Features:  

- **`<table>`**  
  - Defines a table with structured rows and columns.  

- **`<caption>`**  
  - Adds a title to the table (`Personal Data`).  

- **`<thead>` and `<tbody>`**  
  - `<thead>`: Defines the table header.  
  - `<tbody>`: Contains the main table data.  

- **`<tr>` (Table Row) & `<th>` / `<td>` (Table Headers / Data Cells)**  
  - `<th>`: Defines column headers (`Name`, `Age`, `Occupations`).  
  - `<td>`: Represents individual data cells (`Dilakshan`, `25`, `Software Engineer`, etc.).  

- **`<colgroup>`**  
  - Groups columns together for styling purposes.  
  - Example: `visibility: collapse;` hides a specific column.  

- **CSS Styling**  
  - `border: 1px solid black;`: Adds a border to the table, headers, and cells.  
  - `border-collapse: collapse;`: Merges table borders for a cleaner look.  

This file demonstrates how to structure and style tables effectively using HTML and CSS.  

---------------------------------------------------------------------------


## More to Learn  
This is just the beginning! Stay tuned for more HTML topics.  
