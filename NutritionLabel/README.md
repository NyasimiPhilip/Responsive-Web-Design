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
  </ul>
