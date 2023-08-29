 <h1>Nutrition Label Website</h1>
  
  <h2><code>index.html</code>:</h2>
  <p>The document structure is as follows:</p>
  <ul>
    <li>HTML doctype declaration.</li>
    <li>Language attribute set to "en" for English content.</li>
    <li>Metadata, including character encoding and the webpage title, in the <code>&lt;head&gt;</code> section.</li>
    <li>External resources linked:</li>
    <ul>
      <li>Google Fonts stylesheet for the "Open Sans" font family.</li>
      <li>External CSS stylesheet "styles.css" for styling.</li>
    </ul>
    <li>Main content enclosed within a <code>&lt;div&gt;</code> element with the class "label".</li>
    <li>Within the <code>&lt;div class="label"&gt;</code>:</li>
    <ul>
      <li>Header content grouped using <code>&lt;header&gt;</code> element.</li>
      <li>Nutrition label title displayed as an <code>&lt;h1&gt;</code> element with the class "bold".</li>
      <li>Horizontal line divider created with <code>&lt;div&gt;</code> element having the class "divider".</li>
      <li>Information about servings per container displayed using <code>&lt;p&gt;</code> element.</li>
      <li>Serving size emphasized using a <code>&lt;p&gt;</code> element containing a <code>&lt;span&gt;</code> element.</li>
      <li>Another horizontal line divider added with <code>&lt;div&gt;</code> element having the class "divider large".</li>
      <li>The "Calories" information structured in <code>&lt;div class="calories-info"&gt;</code>:</li>
      <ul>
        <li>Left part containing <code>&lt;h2&gt;</code> element with classes "bold" and "small-text".</li>
        <li>Descriptive <code>&lt;p&gt;</code> element conveying calorie information.</li>
        <li>Calorie count (230) displayed with <code>&lt;span&gt;</code> element.</li>
        <li>Additional horizontal line dividers with <code>&lt;div&gt;</code> elements of classes "divider medium" and "divider".</li>
      </ul>
      <li>Nutritional information with daily values structured within <code>&lt;div class="daily-value small-text"&gt;</code>:</li>
      <ul>
        <li><code>&lt;p&gt;</code> element displaying bold "Total Fat" value with amount (8g) and percentage (10%) using nested <code>&lt;span&gt;</code> element.</li>
        <li>Additional nutrient values and corresponding percentages listed in <code>&lt;ul&gt;</code> element with each value as <code>&lt;li&gt;</code> element.</li>
      </ul>
      <li>Nutrition label information ends with horizontal line divider created with <code>&lt;div&gt;</code> element having the class "divider medium".</li>
      <li>A note about the daily value's significance presented using <code>&lt;p&gt;</code> element with class "note".</li>
    </ul>
   
  <code><h2>styles.css</h2></code>
  
  <p>These CSS rules collectively define the styling for various elements in the HTML document</p>
  <ul>
    <li><code>* { box-sizing: border-box; }</code>:
      <p>This rule applies the CSS property <code>box-sizing</code> with a value of <code>border-box</code> to all elements on the page. It ensures that an element's total width and height includes its padding and border, rather than adding padding and border to the element's dimensions, which can cause unexpected layout issues.</p>
    </li>
    <li><code>html { font-size: 16px; }</code>:
      <p>This rule sets the base font size for the entire HTML document to 16 pixels. This size is used as a reference for relative font sizing throughout the rest of the document.</p>
    </li>
     <li><code>.divider { ... }</code>:
      <p>This rule styles elements with the class <code>"divider"</code>. It adds a horizontal line (border) of 1 pixel thickness with a light gray color (#888989). This creates a divider effect with spacing above and below, visually separating content.</p>
    </li>
    <li><code>.bold { ... }</code>:
      <p>This rule targets elements with the class <code>"bold"</code>. It increases the font weight to 800, creating bold text. This can be used to emphasize specific content.</p>
    </li>
    <li><code>.large</code> and <code>.medium</code> styling:
      <p>These rules target elements with the classes <code>"large"</code> and <code>"medium"</code>. They both provide a black background color and remove the default border. Additionally, the <code>"large"</code> class sets a height of 10 pixels, and the <code>"medium"</code> class sets a height of 5 pixels, creating distinct visual cues.</p>
    </li>
    <li><code>.small-text { ... }</code>:
      <p>This rule styles elements with the class <code>"small-text"</code>. It reduces the font size to 0.85rem, making the text slightly smaller than the default size.</p>
    </li>
    <li><code>.calories-info { ... }</code>:
      <p>This rule styles elements with the class <code>"calories-info"</code>. It arranges these elements as a flex container with space-between alignment for their child elements. The container also aligns its children at the bottom using <code>align-items: flex-end</code>.</p>
    </li>
    <li><code>.calories-info h2 { ... }</code>:
      <p>This rule targets <code>h2</code> headings within elements with the class <code>"calories-info"</code>. It removes any default margin, creating a cleaner layout for the headings.</p>
    </li>
    <li><code>.left-container p { ... }</code>:
      <p>This rule styles <code>p</code> elements within elements with the class <code>"left-container"</code>. It sets a negative top and bottom margin to slightly overlap adjacent elements, and increases the font size and weight for emphasis.</p>
    </li>
    <li><code>.calories-info span { ... }</code>:
      <p>This rule styles <code>span</code> elements within elements with the class <code>"calories-info"</code>. Similar to the previous rule, it adjusts the margin, font size, and font weight for aesthetic purposes.</p>
    </li>
    <li><code>.right { ... }</code>:
      <p>This rule targets elements with the class <code>"right"</code>. It changes the flex alignment to <code>justify-content: flex-end</code>, aligning its content to the right side of the container.</p>
    </li>
    <li><code>.indent</code> and <code>.double-indent { ... }</code>:
      <p>These rules target elements with the classes <code>"indent"</code> and <code>"double-indent"</code>. They provide left margin spacing, creating indentation effects. <code>.indent</code> adds 1em of margin, while <code>.double-indent</code> adds 2em of margin.</p>
    </li>
    <li><code>.daily-value p:not(.no-divider) { ... }</code>:
      <p>This rule targets <code>p</code> elements within elements with the class <code>"daily-value"</code> that do not have the class <code>"no-divider"</code>. It adds a bottom border of 1px solid color (#888989), creating a divider effect between these paragraphs.</p>
    </li>
    <li><code>.note { ... }</code>:
      <p>This rule targets elements with the class <code>"note"</code>. It reduces the font size to 0.6rem and provides a small margin above and below, creating a compact and subtle visual distinction for notes.</p>
    </li>
  </ul>
