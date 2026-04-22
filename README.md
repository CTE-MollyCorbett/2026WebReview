# README
-------------------------- HTML Review --------------------------
Q. What does HTML stand for?
A. HyperText Markup Language
Q. What is the difference between <head> and <body>?
A. <head> - Metadata, read by the browser.
   <body> - Content DISPLAYED.
Q. Name THREE semantic HTML elements.
A. <header></header>, <footer></footer>, <main></main>, <nav></nav>
   <article></article>, <aside></aside>, <section></section>.
Q. What attribute does an <a> tag need to create a link?
A. <a> needs <a href="https://google.com">
Q. What is a self-closing HTML tag? Give an example.
A. <br>, <img>, <link>, <meta>.
Q. What does <!DOCTYPE html> do?
A. It tells the browser this is an HTML file.

Every HTML file has the same SKELETON (Boilerplate, template, whatever) structure:
<!DOCTYPE html>
<html lang="en">
<head>
    <title></title>
    <link>
    <style></style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width", initial-scale="1.0">
        - Makes the page RESPONSIVE.
</head>
<body>
    <header>
        <nav>Contains any Navigation Bar elements</nav>
    </header>
    <h1>Largest heading/most important heading. ONLY ONCE per page!</h1>
    <!-- ALL VISIBLE ELEMENTS fo inside the body. -->
</body>
</html>

----------------------- PART 2: Core HTML Elements ----------------------------
Headings 1 - 6
<h1> - There should be only 1 <h1> tag per page.
<h2> - Section titles, subtitles.
<h3> - Subsections.
<h4> - Same size as default text, but boldfaced.
<h5> - Fine print.
<h6> - Finest print (Copyright statements, ect).

Text Elements
<p> - Paragraph tag.
<strong> - Bold/Important text, semantic weight.
<em> - Italic/Emphasized tezt, semantic weight.
<br> - Line break (void element).
<u> - Underline.
<hr> - Horizontal row ---------------------------------------------------------
<span> - Inline element. Does not create a line break.
<mark> - Highlights text.

------------------------------- HTML Lists ------------------------------------
Unordered List - Bulleted list.
<ul>
    <li></li>
    <li></li>
    <li></li>
</ul>
Ordered List - Numbered or alphabetized list. Used fpr steps, ranking, sequences, etc.
<ol>
    <li></li>
    <li></li>
    <li></li>
</ol>
Nested List - A list within a list. 
<ol>
    <li></li>
    <li>
        <ul>
            <li></li>
            <li></li>
            <li></li>
        </ul>
    </li>
    <li></li>
</ol>

------------------------------- Links & Images ----------------------------------
Q. How do I create a link to sllboces.org?
A. <a href="https://sllboces.org" target="_blank">SLL BOCES</a>
Q. How do I create a link to about.html - relative path (page in the same directory)?
A. <a href="about.html">About</a>
Q. Link to a file in the content folder?
A. <a href="content/page.html"></a>
Q. Link to another section of the page?
A. <a href="#about">Jump to the About section</a>
Q. Link to send an email?
A. <a href="mailto:student@sllboces.org">Email Me</a>

Images
Q. What are the two required attributes for <img> tags?
A. alt - accessibility text, src - file path to the image.
<img src="images/hero.jpg" alt="Adirondack Mountains in fall">
<img src="images/logo.png" alt="SLL BOCES Logo">
Q. What is hot-linking an image?
A. Linking to an image somewhere on the internet.
Q. When should you use hot-linking?
A. When you are using a placeholder for design purposes.
Q. When should you remove hot-linked images?
A. Before publishing the site.
Q. Why?
A. If the hot-linked image is moved, it will break your design.
<img src="https://google.com/2/abc/files/images/myGoogleImage.png" alt="My hotlinked image">

----------------------------- PART 3: HTML Semantic Elements -----------------------------
Q. What is a semantic HTML element?
A. Semantic elements describe the meaning of the content inside of the element, not just the way it looks.
Q. Reasons why we use semantic elements?
A. Oraganization, teamwork - allows other developers to more easily read and understand your code.
   Affects the Document Object Model - How the browser reads or understands the content.
   Accessibility - allows screen readers to understand the structure and meaning behind content.
   SEO - Search Engine Optimization - How search engines rank well-structured pages - moves them higher in the search results.
Semantic tags replaced the use of <div> tags:
    <div class="header"> vs <header>
Layout Semantic Elements: header, nav, main, section, aside, footer.
Content Semantic Elements:
<figure></figure> - Image with a caption.
<figcaption> - Caption for a figure image.
<time> - A date or time value.
<address> - Contact address info.
<mark> - Highlighted text.
<details>/<summary> - Expand and collapse more details.
<div></div> - Non-semantic container.