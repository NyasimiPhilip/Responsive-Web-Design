  <h1>Nutrition Label Website</h1>  
  <code><h2>Index.html:</h2></code>
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
    <li>Within the <code>&lt;div class="label"&gt;</code><li>
    <ul>
      <li>Header content grouped using <code>&lt;header&gt;</code> element.</li>
      <li>Nutrition label title displayed as an M&lt;h1&gt; element with the class "bold".</li>
      <li>Horizontal line divider created with &lt;div&gt; element having the class "divider".</li>
      <li>Information about servings per container displayed using &lt;p&gt; element.</li>
      <li>Serving size emphasized using a &lt;p&gt; element containing a &lt;span&gt; element.</li>
      <li>Another horizontal line divider added with &lt;div&gt; element having the class "divider large".</li>
      <li>The "Calories" information structured in &lt;div class="calories-info"&gt;:</li>
      <ul>
        <li>Left part containing &lt;h2&gt; element with classes "bold" and "small-text".</li>
        <li>Descriptive &lt;p&gt; element conveying calorie information.</li>
        <li>Calorie count (230) displayed with &lt;span&gt; element.</li>
        <li>Additional horizontal line dividers with &lt;div&gt; elements of classes "divider medium" and "divider".</li>
      </ul>
      <li>Nutritional information with daily values structured within &lt;div class="daily-value small-text"&gt;:</li>
      <ul>
        <li>&lt;p&gt; element displaying bold "Total Fat" value with amount (8g) and percentage (10%) using nested &lt;span&gt; element.</li>
        <li>Additional nutrient values and corresponding percentages listed in &lt;ul&gt; element with each value as &lt;li&gt; element.</li>
      </ul>
      <li>Nutrition label information ends with horizontal line divider created with &lt;div&gt; element having the class "divider medium".</li>
      <li>A note about the daily value's significance presented using &lt;p&gt; element with class "note".</li>
    </ul>
  </ul>
