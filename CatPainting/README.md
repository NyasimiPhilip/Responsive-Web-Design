<h1><code>Index.html</code></h1>
<ul>
  <li><code>&lt;!DOCTYPE html&gt;:</code> This line declares the document type and version of HTML being used, which is HTML5 in this case.</li>
  <li><code>&lt;html lang="en"&gt;</code>: This is the opening <code>&lt;html&gt;</code> tag and specifies that the document's primary language is English (en for English).</li>
  <li><code>&lt;head&gt;</code>: This is the start of the document's head section. The head section typically contains meta-information about the webpage, such as the character encoding, title, and links to external resources like stylesheets and scripts.
    <ul>
      <li><code>&lt;meta charset="UTF-8"&gt;</code>: This line specifies the character encoding for the document as UTF-8, which is a widely used encoding that supports various characters and symbols from different languages.</li>
      <li><code>&lt;title&gt;</code> fCC Cat Painting <code>&lt;/title&gt;</code>: This is the title of the webpage, which is displayed in the browser's title bar or tab.</li>
      <li><code>&lt;link rel="stylesheet" href="./styles.css"&gt;</code>: This line links an external CSS (Cascading Style Sheets) file named "styles.css" to the HTML document. The CSS file is used to define the styling and layout of the webpage's content.</li>
    </ul>
  </li>
  <li><code>&lt;/head&gt;</code>: This closes the head section of the HTML document.</li>
  <li><code>&lt;body&gt;</code>: This is the start of the document's body section, where the main content of the webpage is defined.
    <ul>
      <li><code>&lt;main&gt;</code>: This is a semantic HTML5 element used to define the main content area of the webpage.
        <ul>
          <li>Within the <code>&lt;main&gt;</code> element, there's a <code>&lt;div&gt;</code> with the class "cat-head." This <code>&lt;div&gt;</code> represents the main container for the cat's face.</li>
          <li>Inside the "cat-head" <code>&lt;div&gt;</code>, there are several nested <code>&lt;div&gt;</code> elements, each with specific classes to define different parts of the cat's face, such as ears, eyes, nose, mouth, and whiskers.</li>
          <li>The various nested <code>&lt;div&gt;</code> elements and their associated classes are used to create a visual representation of a cat's face using HTML and CSS.</li>
        </ul>
      </li>
      <li><code>&lt;/main&gt;</code>: This closes the main content section of the HTML document.</li>
    </ul>
  </li>
  <li><code>&lt;/body&gt;</code>: This closes the body section of the HTML document.</li>
  <li><code>&lt;/html&gt;</code>: This is the closing <code>&lt;/html&gt;</code> tag, which marks the end of the HTML document.</li>
</ul>
<code><h1>Styles.css</h1></code>
<ul>
  <li><strong>Selector: <code>*</code></strong></li>
  <ul>
    <li><code><code>box-sizing: border-box;</code></code>: This rule applies the <code>box-sizing</code> property with a value of <code>border-box</code> to all elements on the web page. It means that the width and height of elements will include the padding and border, not just the content.</li>
  </ul>
  <li><strong>Selector: <code>body</code></strong></li>
  <ul>
    <li><code><code>background-color: #c9d2fc;</code></code>: This sets the background color of the entire web page's body to a light blue color (<code>#c9d2fc</code>).</li>
  </ul>
  <li><strong>Selector: <code>.cat-head</code></strong></li>
  <ul>
    <li><code><code>position: absolute;</code></code>: Positions the cat's head absolutely within its containing element.</li>
    <li><code><code>right: 0; left: 0; top: 0; bottom: 0; margin: auto;</code></code>: Centers the cat's head both horizontally and vertically within its container.</li>
    <li><code><code>background: linear-gradient(#5e5e5e 85%, #45454f 100%);</code></code>: Applies a linear gradient background to the cat's head, transitioning from a darker gray (<code>#5e5e5e</code>) to a slightly lighter gray (<code>#45454f</code>).</li>
    <li><code><code>width: 205px; height: 180px;</code></code>: Sets the width and height of the cat's head.</li>
    <li><code><code>border: 1px solid #000;</code></code>: Adds a 1-pixel solid black border to the cat's head.</li>
    <li><code><code>border-radius: 46%;</code></code>: Applies a circular border radius to give the cat's head a rounded appearance.</li>
  </ul>
  <li><strong>Selector: <code>.cat-left-ear</code> and <code>.cat-right-ear</code></strong></li>
  <ul>
    <li>These styles define the appearance of the cat's left and right ears, respectively. They use CSS properties like <code>position</code>, <code>border-radius</code>, and <code>transform</code> to create triangular ears.</li>
  </ul>
  <li><strong>Selector: <code>.cat-left-inner-ear</code> and <code>.cat-right-inner-ear</code></strong></li>
  <ul>
    <li>These styles define the inner parts of the cat's ears, creating a layered effect.</li>
  </ul>
  <li><strong>Selector: <code>.cat-left-eye</code> and <code>.cat-right-eye</code></strong></li>
  <ul>
    <li>These styles define the left and right eyes of the cat, using CSS properties like <code>position</code>, <code>border-radius</code>, and <code>transform</code> to create the appearance of cat eyes.</li>
  </ul>
  <li><strong>Selector: <code>.cat-left-inner-eye</code> and <code>.cat-right-inner-eye</code></strong></li>
  <ul>
    <li>These styles define the inner parts of the cat's eyes, adding white highlights.</li>
  </ul>
  <li><strong>Selector: <code>.cat-nose</code></strong></li>
  <ul>
    <li>This style defines the cat's nose using a combination of CSS properties like <code>position</code>, <code>border-radius</code>, <code>transform</code>, and <code>border</code> to create a triangular-shaped nose.</li>
  </ul>
  <li><strong>Selector: <code>.cat-mouth div</code></strong></li>
  <ul>
    <li>This style defines the cat's mouth by creating two black lines that resemble a mouth.</li>
  </ul>
  <li><strong>Selector: <code>.cat-mouth-line-left</code> and <code>.cat-mouth-line-right</code></strong></li>
  <ul>
    <li>These styles position and rotate the mouth lines to give them a curved appearance.</li>
  </ul>
  <li><strong>Selector: <code>.cat-whiskers-left div</code> and <code>.cat-whiskers-right div</code></strong></li>
  <ul>
    <li>These styles define the whiskers of the cat using black horizontal lines.</li>
  </ul>
  <li><strong>Selector: <code>.cat-whisker-left-top</code>, <code>.cat-whisker-left-middle</code>, <code>.cat-whisker-left-bottom</code>, <code>.cat-whisker-right-top</code>, <code>.cat-whisker-right-middle</code>, <code>.cat-whisker-right-bottom</code></strong></li>
  <ul>
    <li>These styles position and rotate the whiskers to create a whisker pattern on the cat's face.</li>
  </ul>
</ul>

