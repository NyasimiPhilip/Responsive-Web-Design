<u><code><h1>index.css</h1></code></u>
<ul>
    <li><code>&lt;!DOCTYPE html&gt;</code>: This declaration defines the document type and version of HTML being used.</li>
    <li><code>&lt;html lang="en"&gt;</code>: The opening tag of the HTML document, with the <code>lang</code> attribute specifying the language of the content as English.</li>
    <li><code>&lt;head&gt;</code>: The head section of the HTML document, which contains meta information and links to external resources.</li>
    <ul>
        <li><code>&lt;meta charset="UTF-8"&gt;</code>: Specifies the character encoding of the document as UTF-8.</li>
        <li><code>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</code>: Sets the viewport settings for responsive design.</li>
        <li><code>&lt;meta name="description" content="freeCodeCamp Accessibility Quiz practice project"&gt;</code>: Provides a brief description of the page.</li>
        <li><code>&lt;title&gt;Accessibility Quiz&lt;/title&gt;</code>: Sets the title of the webpage.</li>
        <li><code>&lt;link rel="stylesheet" href="styles.css"&gt;</code>: Links an external CSS file for styling.</li>
    </ul>
    <li><code>&lt;body&gt;</code>: The main content of the webpage.</li>
    <ul>
        <li><code>&lt;header&gt;</code>: Contains the header section of the webpage.</li>
        <ul>
            <li><code>&lt;img id="logo" src="https://cdn.freecodecamp.org/platform/universal/fcc_primary.svg"&gt;</code>: Displays an image logo.</li>
            <li><code>&lt;h1&gt;HTML/CSS Quiz&lt;/h1&gt;</code>: Displays the title of the quiz.</li>
            <li><code>&lt;nav&gt;</code>: Contains navigation links.</li>
            <ul>
                <li><code>&lt;ul&gt;</code>: Unordered list for navigation links.</li>
                <li><code>&lt;li&gt;&lt;a href="#student-info"&gt;INFO&lt;/a&gt;&lt;/li&gt;</code>: Link to the "Student Info" section.</li>
                <li><code>&lt;li&gt;&lt;a href="#html-questions"&gt;HTML&lt;/a&gt;&lt;/li&gt;</code>: Link to the "HTML" section.</li>
                <li><code>&lt;li&gt;&lt;a href="#css-questions"&gt;CSS&lt;/a&gt;&lt;/li&gt;</code>: Link to the "CSS" section.</li>
            </ul>
        </ul>
        <li><code>&lt;main&gt;</code>: Contains the main content of the webpage.</li>
        <ul>
            <li><code>&lt;form&gt;</code>: A form element that allows users to submit data.</li>
            <li><code>&lt;section role="region" aria-labelledby="student-info"&gt;</code>: A section for the "Student Info" part of the quiz.</li>
            <ul>
                <li><code>&lt;h2 id="student-info"&gt;Student Info&lt;/h2&gt;</code>: Heading for the section.</li>
                <li>Several <code>&lt;div class="info"&gt;</code> elements: These contain form inputs for student information.</li>
                <li>Similar sections for HTML and CSS questions follow, each with a set of questions and options.</li>
            </ul>
            <li><code>&lt;button type="submit"&gt;Send&lt;/button&gt;</code>: A submit button for sending the form.</li>
        </ul>
        <li><code>&lt;footer&gt;</code>: The footer section of the webpage.</li>
        <ul>
            <li><code>&lt;address&gt;</code>: Contains contact information.</li>
            <ul>
                <li><code>&lt;a href="https://freecodecamp.org"&gt;freeCodeCamp&lt;/a&gt;</code>: A link to the freeCodeCamp website.</li>
                <li>Address information about the organization.</li>
            </ul>
        </ul>
    </ul>
</ul>
<u><code><h1>styles.css</h1></code></u>
<code>@media (prefers-reduced-motion: no-preference) {<br>* {<br>scroll-behavior: smooth;<br>}</code>

<p>This media query targets devices with a preference for no-reduced motion. Within this context, all elements (<code>*</code>) are styled to have smooth scrolling behavior using the <code>scroll-behavior</code> property. This property enables smooth scrolling when navigating through content, providing a more visually appealing and fluid user experience.</p>
<code>body {<br>/* ... */<br>}</code>

<p>This rule targets the <code>body</code> element, defining its background color as <code>#f5f6f7</code> and text color as <code>#1b1b32</code>. The font family is set to <code>Helvetica</code> for text consistency. Additionally, the <code>margin</code> is set to 0 to remove any default spacing around the body content.</p>
<code>header {<br>/* ... */<br>}</code>

<p>This rule targets the <code>header</code> element, establishing styling for a fixed header at the top of the page. It sets the header's background color to <code>#1b1b32</code>, and uses flex properties to align items within the header, including space-between justification and center alignment. The <code>position: fixed</code> property fixes the header's position at the top of the viewport.</p>
<code>#logo {<br>/* ... */<br>}</code>

<p>This rule targets the element with the ID <code>#logo</code>. It defines styling properties, including width using <code>max()</code> to ensure that the logo's width is at least 100px or 18% of the viewport width (whichever is larger). Background color, aspect ratio, and padding are also set for the logo container.</p>
<code>h1 {<br>/* ... */<br>}</code>

<p>This rule targets <code>h1</code> elements, specifying that they have a color of <code>#f1be32</code> (a shade of yellow), and the font size is responsive using <code>min()</code> to be either 5% of the viewport width or 1.2em (whichever is smaller). Text alignment is centered.</p>
<code>nav {<br>/* ... */<br>}</code>

<p>This rule targets the <code>nav</code> element, specifying its width as 50% and a maximum width of 300px. The height is set to 50px.</p>
<code>nav > ul {<br>/* ... */<br>}</code>

<p>This rule targets the unordered list within the navigation (<code>nav &gt; ul</code>). It uses flex properties to evenly distribute list items and wrap them in case of overflow. The list items are centered vertically using <code>align-items: center</code>.</p>
<code>nav > ul > li {<br>/* ... */<br>}</code>

<p>This rule targets list items within the navigation (<code>nav &gt; ul &gt; li</code>). It sets the text color to <code>#dfdfe2</code>, adds margin and padding, and displays the list items as blocks.</p>
<code>nav > ul > li:hover {<br>/* ... */<br>}</code>

<p>This rule targets list items within the navigation when hovered over. It changes the background color to <code>#dfdfe2</code>, the text color to <code>#1b1b32</code>, and changes the cursor to a pointer, indicating interactivity.</p>
<code>li > a {<br>/* ... */<br>}</code>

<p>This rule targets links within list items. It sets the link color to inherit from the parent element and removes text decoration.</p>
<code>main {<br>/* ... */<br>}</code>

<p>This rule targets the <code>main</code> element and adds padding at the top to prevent content from being covered by the fixed header.</p>
<code>section {<br>/* ... */<br>}</code>

<p>This rule targets <code>section</code> elements, specifying their width as 80%, centering them horizontally with auto margins, and setting a maximum width of 600px.</p>
<code>h2 {<br>/* ... */<br>}</code>

<p>This rule targets <code>h2</code> elements. It adds a border at the bottom with a 4px solid line of color <code>#dfdfe2</code>, and adjusts margin and padding to create a clean and visually pleasing heading appearance.</p>
<code>.info {<br>/* ... */<br>}</code>

<p>This rule targets elements with the class <code>"info"</code>. It adds padding to the top and left, creating a consistent spacing for information containers.</p>
<code>.formrow {<br>/* ... */<br>}</code>

<p>This rule targets elements with the class <code>"formrow"</code>. It adds margin at the top and horizontal padding, creating spacing around form elements.</p>
<code>input {<br>/* ... */<br>}</code>

<p>This rule targets all <code>input</code> elements, setting the font size to 16px for uniformity.</p>
<code>.info label, .info input {<br>/* ... */<br>}</code>

<p>This rule targets label and input elements within elements with the class <code>"info"</code>. It sets them to display as inline-block elements, ensuring they are on the same line within the container.</p>
<code>.info input {<br>/* ... */<br>}</code>

<p>This rule targets input elements within elements with the class <code>"info"</code>. It sets their width to 50% and aligns the text to the left, providing a consistent and visually appealing layout.</p>
<code>.info label {<br>/* ... */<br>}</code>

<p>This rule targets label elements within elements with the class <code>"info"</code>. It sets the width to 10% and a minimum width of 55px, aligning the text to the right for a label-like appearance.</p>
<code>.question-block {<br>/* ... */<br>}</code>

<p>This rule targets elements with the class <code>"question-block"</code>. It sets the text alignment to the left, creates block-level display, adjusts width to 100%, and adds margin at the top. Padding at the top provides spacing within the question block.</p>
<code>p {<br>/* ... */<br>}</code>

<p>This rule targets <code>p</code> elements, adjusting margin at the top and adding left padding. The font size is set to 20px, ensuring a consistent and readable text size.</p>
<code>p::before {<br>/* ... */<br>}</code>

<p>This rule targets the <code>::before</code> pseudo-element of <code>p</code> elements. It adds content "Question #" before each paragraph, serving as a label for questions.</p>
<code>.question {<br>/* ... */<br>}</code>

<p>This rule targets elements with the class <code>"question"</code>. It removes borders and padding at the bottom, maintaining a clean and unobtrusive appearance for question sections.</p>
<code>.answers-list {<br>/* ... */<br>}</code>

<p>This rule targets the list of answers. It removes default list styles by setting <code>list-style</code> to <code>none</code> and removes padding.</p>
<code>button {<br>/* ... */<br>}</code>

<p>This rule targets <code>button</code> elements, centering them using auto margins, setting a width of 40%, adding padding, and defining font size and background/border colors. This creates visually appealing and interactive buttons.</p>
<code>footer {<br>/* ... */<br>}</code>

<p>This rule targets the <code>footer</code> element, adding a background color of <code>#2a2a40</code> and using flex properties to horizontally center its contents.</p>
<code>footer, footer a {<br>/* ... */<br>}</code>

<p>This rule targets <code>footer</code> and <code>a</code> elements within the footer. It sets the color to <code>#dfdfe2</code>, maintaining a consistent link color within the footer.</p>
<code>address {<br>/* ... */<br>}</code>

<p>This rule targets <code>address</code> elements, adjusting text alignment to the center and adding padding for a visually balanced appearance.</p>
<code>.sr-only {<br>/* ... */<br>}</code>

<p>This rule targets elements with the class <code>"sr-only"</code> which are intended to be hidden from view while remaining accessible to screen readers. It applies styles to position the element off-screen using absolute positioning and <code>clip: rect(0, 0, 0, 0)</code>.</p>






