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

# 13_HTML Forms  

This HTML file demonstrates the use of **forms and form elements** in HTML.  
## Key Features:  

- **`<form action="submit.html" method="get">`**  
  - Creates a form that submits data to `submit.html` using the `GET` method.  

- **Input Fields**  
  - `<input type="text" name="Dilakshan">`: Text input field.  
  - `<input type="text" autofocus>`: Automatically focuses when the page loads.  
  - `<input type="text" required id="user">`: A required text input with a label.  
  - `<input type="password">`: Password input field.  
  - `<input type="email">`: Email input field.  
  - `<input type="tel">`: Telephone input field.  
  - `<input type="url">`: URL input field.  
  - `<input type="number" min="10" max="15">`: Number input with a range.  
  - `<input type="file">`: File upload input.  
  - `<input type="color">`: Color picker input.  
  - `<input type="date">`: Date picker input.  
  - `<input type="datetime-local">`: Date & time picker input.  
  - `<input type="month">`: Month selector input.  
  - `<input type="week">`: Week selector input.  
  - `<input type="time">`: Time picker input.  

- **Buttons & Controls**  
  - `<button type="submit">`: Submit button.  
  - `<button type="submit" disabled>`: Disabled submit button.  
  - `<input type="button">`: Button input field.  
  - `<input type="reset" value="submit">`: Reset button.  
  - `<input type="checkbox">`: Checkbox input.  

- **Select & Textarea Elements**  
  - `<select multiple>`: Dropdown selection with multiple options.  
  - `<option selected>`: Pre-selected option in the dropdown.  
  - `<textarea cols="30" rows="10">`: Multi-line text input.  

- **Fieldset & Legend**  
  - `<fieldset>`: Groups related form elements.  
  - `<legend>`: Provides a title for the fieldset.  

- **Datalist for Auto-Suggestions**  
  - `<datalist>`: Provides predefined suggestions for input.  

- **Form Submission**  
  - The form submits to `submit.html`, displaying `"Your form has been submitted successfully."`  

This file demonstrates the structure and functionality of HTML forms with various input types.  

---------------------------------------------------------------------------

# 14_HTML Semantic Elements

This HTML file demonstrates the use of **semantic elements** to improve the structure and readability of a webpage.  
## Key Features:  

- **`<header>`**  
  - Contains the **navigation bar** (`<nav>`) with a list of links (`<ul>` & `<li>`).  

- **`<nav>`**  
  - Provides a **navigation menu** with links: Home, About, Service, and Contact.  

- **`<main>`**  
  - Represents the **main content** of the webpage.  

- **`<article>` & `<section>`**  
  - `<article>`: Groups independent, self-contained content.  
  - `<section>`: Contains a heading (`<h1>About us`) and a paragraph.  

- **`<aside>`**  
  - Represents **sidebar content** (Latest News section).  

- **`<footer>`**  
  - Contains **copyright information** (`© 2025`).  

This file demonstrates how **semantic elements** improve HTML document structure, accessibility, and SEO.  

---------------------------------------------------------------------------

# 15_HTML Accessibility Example  

This HTML file demonstrates the use of **ARIA (Accessible Rich Internet Applications) attributes** to improve web accessibility.  
## Key Features:  

- **`aria-label="close"`**  
  - Provides an accessible label for the button without visible text.  

- **`aria-labelledby="box"`**  
  - Links the button to the text inside the `<div id="box">` for better screen reader support.  

- **`aria-hidden="true"`**  
  - Hides the paragraph from assistive technologies.  

- **`aria-expanded="false"` & `aria-controls="section"`**  
  - Indicates whether a collapsible section (`#section`) is expanded or collapsed.  

- **`aria-checked="true"`**  
  - Used on both a button and a checkbox to indicate a checked state.  

- **`role="listbox"` & `role="option"`**  
  - Defines a listbox containing selectable options.  
  - `aria-selected="true/false"`: Marks which list items are selected.  

This file demonstrates how **ARIA attributes** improve web accessibility for users with disabilities.  

---------------------------------------------------------------------------

# 16_HTML Multimedia  

This HTML file demonstrates the use of **multimedia elements** such as **audio** and **video**, including support for media controls and subtitles.
## Key Features:

- **Audio Element**:
  - The `<audio>` element is used to embed sound content in the webpage. It includes the `controls` attribute to allow users to play, pause, and adjust the volume of the audio.
  - The `<source>` tag specifies the audio file (`Audio sample.mp3`) and its type (`audio/mp3`).

- **Video Element**:
  - The `<video>` element is used to embed a video on the webpage, with controls for play, pause, and volume adjustment.
  - The `<source>` tag specifies the video file (`Video sample.mp4`) and its type (`video/mp4`).
  - The `<track>` tag is used to add subtitles (`Subtitle Sample.vtt`) for the video. The `srclang="en"` specifies that the subtitles are in English, and `kind="subtitles"` defines their role.

This file demonstrates how to use HTML5 multimedia features to enhance user experience by embedding audio and video with accessible options.

## Files:
- **Audio sample.mp3**: The audio file for playback.
- **Video sample.mp4**: The video file with playback controls.
- **Subtitle Sample.vtt**: Subtitles in WebVTT format for the video.

Ensure these files are in the same directory for proper functionality.

---------------------------------------------------------------------------

Congratulations on completing the HTML Basics Section! 🎉
We learned the fundamental building blocks of HTML, including:
covered the essentials:
✅ Structure & formatting
✅ Links, images, media
✅ Forms, tables & accessibility
✅ Semantic elements for better HTML

With this solid foundation, you’re ready to level up! 🚀

What’s next?
🔹 Add style with CSS 🎨
🔹 Make it interactive with JavaScript ⚡
🔹 Build fun projects & keep practicing!

Keep coding & stay curious! 💻✨
