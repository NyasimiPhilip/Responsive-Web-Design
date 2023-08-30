<u><code><h1>index.html</h1></code></u>
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
<u><code><h1>index.html</h1></code></u>
<p><code>@media (prefers-reduced-motion: no-preference)</code>: This is a media query that targets devices or user preferences that do not have a preference for reduced motion. In this case, it applies styles when the user doesn't prefer reduced motion effects.</p>
<p><code>*</code> { <code>scroll-behavior: smooth;</code> }: This rule selects all elements on the page (indicated by <code>*</code>) and sets the <code>scroll-behavior</code> property to smooth, resulting in smooth scrolling behavior when navigating to anchor links.</p>
<p><code>body</code>: Styles for the entire body of the webpage.</p>
<ul>
    <li><code>background</code>, <code>color</code>, <code>font-family</code>, and <code>margin</code> define the background color, text color, font family, and margin of the entire body.</li>
</ul>
<p><code>header</code>: Styles for the header section of the webpage.</p>
<ul>
    <li><code>width</code>, <code>height</code>, <code>background-color</code>, <code>display</code>, <code>justify-content</code>, <code>align-items</code>, <code>position</code>, and <code>top</code> define the dimensions, background color, display properties, and positioning of the header. It's set to be fixed at the top of the viewport.</li>
</ul>
<p><code>#logo</code>: Styles for the logo element.</p>
<ul>
    <li><code>width</code>, <code>background-color</code>, <code>aspect-ratio</code>, and <code>padding</code> define the logo's width, background color, aspect ratio (width-to-height ratio), and padding.</li>
</ul>
<p><code>h1</code>: Styles for level 1 headings.</p>
<ul>
    <li><code>color</code>, <code>font-size</code>, and <code>text-align</code> define the text color, font size, and text alignment of level 1 headings.</li>
</ul>
<p><code>nav</code>: Styles for the navigation element.</p>
<ul>
    <li><code>width</code> and <code>max-width</code> set the width of the navigation and limit its maximum width.</li>
</ul>
<p><code>nav &gt; ul</code>: Styles for the unordered list within the navigation.</p>
<ul>
    <li><code>display</code>, <code>justify-content</code>, <code>flex-wrap</code>, <code>align-items</code>, <code>padding-inline-start</code>, <code>margin-block</code>, and <code>height</code> control the layout, alignment, padding, and height of the list items within the navigation.</li>
</ul>
<p><code>nav &gt; ul &gt; li</code>: Styles for the list items within the navigation.</p>
<ul>
    <li><code>color</code>, <code>margin</code>, <code>padding</code>, and <code>display</code> define the text color, margin, padding, and display property of the list items.</li>
</ul>
<p><code>nav &gt; ul &gt; li:hover</code>: Styles for list items on hover.</p>
<ul>
    <li>These styles define the appearance of list items when they are hovered over.</li>
</ul>
<p><code>li &gt; a</code>: Styles for links within list items.</p>
<ul>
    <li><code>color</code> and <code>text-decoration</code> define the text color and text decoration (underline) for links.</li>
</ul>
<p><code>main</code>: Styles for the main content area.</p>
<ul>
    <li><code>padding-top</code> creates space at the top of the content to avoid overlap with the fixed header.</li>
</ul>
<p><code>section</code>: Styles for sections within the main content.</p>
<ul>
    <li><code>width</code>, <code>margin</code>, and <code>max-width</code> define the width and margin of the sections, controlling their appearance.</li>
</ul>


