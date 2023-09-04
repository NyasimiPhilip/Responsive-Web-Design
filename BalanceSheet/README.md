<code><h1>Index.html</h1></code><br>
<ul>
  <li><code>&lt;!DOCTYPE html&gt;</code> - The document begins with the HTML5 doctype declaration, specifying that this is an HTML5 document.</li>
</ul>
<ul>
  <li><code>&lt;html lang="en"&gt;</code> - The root element of the HTML document, specifying the document's language as English.</li>
</ul>
<ul>
  <li><code>&lt;head&gt;</code> - The head section of the document, which contains metadata and links to external resources.</li>
  <ul>
    <li><code>&lt;meta charset="UTF-8"&gt;</code> - Specifies the character encoding for the document as UTF-8, ensuring proper text encoding.</li>
    <li><code>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</code> - Sets the viewport meta tag, ensuring proper rendering on various devices and screen sizes.</li>
    <li><code>&lt;title&gt;Balance Sheet&lt;/title&gt;</code> - Defines the title of the webpage, which appears in the browser's title bar or tab.</li>
    <li><code>&lt;link rel="stylesheet" href="./styles.css"&gt;</code> - Links to an external stylesheet named "styles.css" to apply CSS styles to the HTML content.</li>
  </ul>
</ul>
<ul>
  <li><code>&lt;body&gt;</code> - The main content of the webpage is contained within the body element.</li>
  <ul>
    <li><code>&lt;main&gt;</code> - A semantic HTML5 element used to define the main content of the document. It contains the entire balance sheet.</li>
    <ul>
      <li><code>&lt;section&gt;</code> - A section element that wraps the balance sheet content.</li>
      <ul>
        <li><code>&lt;h1&gt;</code> - The main heading of the balance sheet, which includes the company name ("AcmeWidgetCorp") and the title ("Balance Sheet"). It uses a nested span structure for styling purposes.</li>
        <li><code>&lt;div id="years" aria-hidden="true"&gt;</code> - A container for displaying the years. It includes spans for each year (2019, 2020, 2021) with the "year" class.</li>
        <li><code>&lt;div class="table-wrap"&gt;</code> - A container for wrapping the tables in the balance sheet.</li>
        <ul>
          <li><code>&lt;table&gt;</code> - A table element for displaying the assets section of the balance sheet.</li>
          <ul>
            <li><code>&lt;caption&gt;</code> - A caption for the table, indicating that this table represents "Assets."</li>
            <li><code>&lt;thead&gt;</code> - The table header section.</li>
            <ul>
              <li><code>&lt;tr&gt;</code> - A table row containing headers for each column. It includes empty td for alignment and th elements for each year.</li>
            </ul>
            <li><code>&lt;tbody&gt;</code> - The table body section for data rows.</li>
            <ul>
              <li><code>&lt;tr class="data"&gt;</code> - A data row with a th element for the asset name and td elements for the financial data (e.g., cash, checking, savings). Each row includes a description within a span element with the "description" class.</li>
              <li><code>&lt;tr class="total"&gt;</code> - A total row summarizing the asset totals. It includes a th element for the total and td elements for each year's total. The "sr-only" class is used for screen reader accessibility.</li>
            </ul>
          </ul>
        </ul>
      </ul>
    </ul>
  </ul>
</ul>
<code><h1>styles.css</h1></code>

<ul>
  <li><code>Section Styles (section):</code></li>
  <ul>
    <li>Selects <code>&lt;section&gt;</code> elements and applies the following styles:</li>
    <li><code>max-width: 40rem;</code> - Sets the maximum width of <code>&lt;section&gt;</code> to 40 rem units.</li>
    <li><code>margin: 0 auto;</code> - Centers the <code>&lt;section&gt;</code> horizontally by setting left and right margins to "auto."</li>
    <li><code>border: 2px solid #d0d0d5;</code> - Adds a 2px solid border with a light gray color (#d0d0d5) around the <code>&lt;section&gt;</code>.</li>
  </ul>
</ul>

<ul>
  <li><code>Sticky Header Styles (#years):</code></li>
  <ul>
    <li>Selects the element with the "years" ID and applies the following styles:</li>
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
  <li><code>Year Indicator Styles (#years span[class]):</code></li>
  <ul>
    <li>Selects <code>&lt;span&gt;</code> elements with a "class" attribute that are descendants of the element with the "years" ID. These styles apply to the year indicators (2019, 2020, 2021) within the "years" element:</li>
    <li><code>font-weight: bold;</code> - Sets the font weight to bold for these year indicators.</li>
    <li><code>width: 4.5rem;</code> - Sets a fixed width of 4.5rem for each year indicator, aligning them properly.</li>
    <li><code>text-align: right;</code> - Right-aligns the text within each year indicator.</li>
  </ul>
</ul>

<ul>
  <li><code>Table Wrap Styles (.table-wrap):</code></li>
  <ul>
    <li>Selects elements with the "table-wrap" class and applies the following styles:</li>
    <li><code>padding: 0 0.75rem 1.5rem 0.75rem;</code> - Adds padding to the top (0), right (0.75rem), bottom (1.5rem), and left (0.75rem), creating space around the tables.</li>
  </ul>
</ul>

<ul>
  <li><code>Table Styles (table):</code></li>
  <ul>
    <li>Selects <code>&lt;table&gt;</code> elements and applies the following styles:</li>
    <li><code>border-collapse: collapse;</code> - Collapses the borders of table cells so that adjacent borders merge into a single border.</li>
    <li><code>border: 0;</code> - Removes the default border on tables.</li>
    <li><code>width: 100%;</code> - Sets the table width to 100% of its containing element.</li>
    <li><code>position: relative;</code> - Sets the position to relative, allowing absolute positioning of elements inside the table.</li>
    <li><code>margin-top: 3rem;</code> - Adds a top margin of 3rem, creating space between tables and the previous content.</li>
  </ul>
</ul>

<ul>
  <li><code>Table Caption Styles (table caption):</code></li>
  <ul>
    <li>Selects <code>&lt;caption&gt;</code> elements within tables and applies the following styles:</li>
    <li><code>color: #356eaf;</code> - Sets the text color of captions to a blueish color (#356eaf).</li>
    <li><code>font-size: 1.3em;</code> - Sets the font size to 1.3em for captions.</li>
    <li><code>font-weight: normal;</code> - Sets the font weight to normal for captions.</li>
    <li><code>position: absolute;</code> - Positions captions absolutely, allowing them to be placed above the table.</li>
    <li><code>top: -2.25rem;</code> - Shifts the caption 2.25rem above the top of the table.</li>
    <li><code>left: 0.5rem;</code> - Adds 0.5rem of left spacing to the caption.</li>
  </ul>
</ul>
