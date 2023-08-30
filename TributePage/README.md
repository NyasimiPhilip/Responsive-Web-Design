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

<p>The entire structure conforms to HTML's semantic elements, which help structure the webpage's content for better accessibility and SEO.</p>

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
