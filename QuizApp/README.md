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
