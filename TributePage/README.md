<code><h1>index.html</h1></code>

<ul>
  <li>
    <code>&lt;!DOCTYPE html&gt;</code>:
    <p>This declaration defines the document type and version of HTML being used.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;html&gt;</code>:
    <p>The root element of the HTML document, containing all other elements.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;head&gt;</code>:
    <p>Contains metadata about the document, including the title of the webpage and links to external resources like stylesheets.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;title&gt;</code>:
    <p>Sets the title that appears in the browser's title bar or tab.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;link&gt;</code>:
    <p>Specifies an external stylesheet (<code>styles.css</code>) to be applied to the HTML content.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;style&gt;</code>:
    <p>Contains inline CSS rules. In this case, it defines styling for an element with the <code>#image</code> id.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;body&gt;</code>:
    <p>The main content of the webpage is contained within this element.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;main&gt;</code>:
    <p>A semantic element used to define the main content of the document.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;h1&gt;</code>:
    <p>A level 1 heading element displaying the text "Dr. Norman Borlaug".</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;div id="img-div"&gt;</code>:
    <p>A container for the image and its caption.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;img&gt;</code>:
    <p>Displays an image of Dr. Norman Borlaug. The <code>src</code> attribute contains a base64-encoded image.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;figcaption&gt;</code>:
    <p>Provides a caption for the image.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;div id="tribute-info"&gt;</code>:
    <p>A container for the tribute information.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;p&gt;</code>:
    <p>Paragraph elements containing information about Dr. Norman Borlaug and his contributions.</p>
  </li>
</ul>

<ul>
  <li>
    <code>&lt;a id="tribute-link"&gt;</code>:
    <p>A hyperlink element that links to an external website (<a href="https://example.com" target="_blank">https://example.com</a>) about Dr. Norman Borlaug. It opens in a new tab due to the <code>target="_blank"</code> attribute.</p>
  </li>
</ul>

<code><h1>styles.css</h1></code>
<ul>
  <li>
    <code>body, h1, p</code>:
    <p>This rule resets the <code>margin</code> and <code>padding</code> properties of the <code>body</code>, <code>h1</code>, and <code>p</code> elements to 0. This ensures a consistent starting point for these elements and eliminates any default spacing.</p>
  </li>
  <li>
    <code>body</code>:
    <p>This rule targets the <code>body</code> element and sets its <code>font-family</code> to <code>Arial</code> or a generic sans-serif font. It also defines a background color of <code>#f5f5f5</code>, text color of <code>#333</code>, and a line height of <code>1.6</code> for improved readability and spacing.</p>
  </li>
  <li>
    <code>#main</code>:
    <p>This rule targets the element with the ID <code>#main</code>, which is likely the main content container of the webpage. It sets the maximum width to <code>800px</code>, centers it horizontally using <code>margin: 0 auto</code>, adds padding of <code>20px</code>, a white background color, and a subtle box shadow for a card-like appearance.</p>
  </li>
  <li>
    <code>#title</code>:
    <p>This rule targets the element with the ID <code>#title</code>, presumably the title of the content. It centers the text using <code>text-align: center</code>, adds a margin at the bottom for spacing, and sets the text color to <code>#333</code>.</p>
  </li>
  <li>
    <code>#img-div</code>:
    <p>This rule targets <code>#img-div</code>, which is likely a container for an image. It centers the content using <code>text-align: center</code> and adds a margin at the bottom for spacing.</p>
  </li>
  <li>
    <code>#image</code>:
    <p>This rule targets the element with the ID <code>#image</code>, representing an image within the container. It ensures that the image resizes responsively by setting <code>max-width: 100%</code> and <code>height: auto</code>. A border of <code>2px</code> is applied with a color of <code>#ddd</code>, and the image has a slight border radius and box shadow for a subtle visual effect.</p>
  </li>
  <li>
    <code>#img-caption</code>:
    <p>This rule targets the element with the ID <code>#img-caption</code>, presumably providing a caption for the image. It adds margin at the top, sets the font style to italic using <code>font-style: italic</code>, and changes the color to <code>#777</code> for a subdued appearance.</p>
  </li>
  <li>
    <code>#tribute-info</code>:
    <p>This rule targets the element with the ID <code>#tribute-info</code>, which likely contains information or a description. It sets the font size to <code>18px</code>, adds margin at the bottom for spacing, and aligns the text to justify, creating a neat and even text layout.</p>
  </li>
  <li>
    <code>#tribute-link</code>:
    <p>This rule targets the element with the ID <code>#tribute-link</code>, likely representing a link. It displays the link as a block element for better spacing, centers the text using <code>text-align: center</code>, sets the font size and color, and removes the default text decoration. It also adds a margin at the top for spacing.</p>
  </li>
  <li>
    <code>#tribute-link:hover</code>:
    <p>This rule targets the <code>:hover</code> state of the link. When the link is hovered over, it underlines the link text to indicate interactivity, enhancing user feedback.</p>
  </li>
</ul>
<ul>
  <li><code>section</code> - Selects <code>&lt;section&gt;</code> elements and applies the following styles:</li>
  <ul>
    <li><code>max-width: 40rem;</code> - Sets the maximum width of <code>&lt;section&gt;</code> to 40 rem units.</li>
    <li><code>margin: 0 auto;</code> - Centers the <code>&lt;section&gt;</code> horizontally by setting left and right margins to "auto."</li>
    <li><code>border: 2px solid #d0d0d5;</code> - Adds a 2px solid border with a light gray color (#d0d0d5) around the <code>&lt;section&gt;</code>.</li>
  </ul>
</ul>

<ul>
  <li><code>#years</code> - Selects the element with the "years" ID and applies the following styles:</li>
  <ul>
    <li><code>display: flex;</code> - Turns the element into a flex container.</li>
    <li><code>justify-content: flex-end;</code> - Aligns flex items to the end of the container (right-aligned).</li>
    <li><code>position: sticky;</code> - Makes the element position sticky within its containing context.</li>
    <li><code>z-index: 999;</code> - Sets the z-index to 999, ensuring it appears above other elements.</li>
    <li><code>top: 0;</code> - Sticks the element to the top of the viewport.</li>
    <li><code>background: #0a0a23;</code> - Sets the background color to a dark blueish color (#0a0a23).</li>
    <li><code>color: #fff;</code> - Sets the text color to white (#fff).</li>
    <li><code>padding: 0.5rem calc(1.25rem + 2px) 0.5rem 0;</code> - Adds padding to the top (0.5rem), right (calc(1.25rem + 2px)), and bottom (0.5rem), effectively creating spacing.</li>
    <li><code>margin: 0 -2px;</code> - Sets negative margins on the left and right sides, ensuring the element aligns with the border of its parent.</li>
  </ul>
</ul>

<ul>
  <li><code>#years span[class]</code> - Selects <code>&lt;span&gt;</code> elements with a "class" attribute that are descendants of the element with the "years" ID. These styles apply to the year indicators (2019, 2020, 2021) within the "years" element:</li>
  <ul>
    <li><code>font-weight: bold;</code> - Sets the font weight to bold for these year indicators.</li>
    <li><code>width: 4.5rem;</code> - Sets a fixed width of 4.5rem for each year indicator, aligning them properly.</li>
    <li><code>text-align: right;</code> - Right-aligns the text within each year indicator.</li>
  </ul>
</ul>
