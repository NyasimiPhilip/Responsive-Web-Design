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
  <li><code>span[class~="sr-only"]:</code> This selector targets <code>&lt;span&gt;</code> elements with a <code>class</code> attribute containing the class name <code>"sr-only"</code>. It is often used for accessibility purposes to hide elements visually while still making them available to screen readers. The styles applied to these elements make them effectively invisible by reducing their size, positioning, and other properties.</li>
  <ul>
    <li><code>border: 0 !important;</code>: Removes any borders.</li>
    <li><code>clip: rect(1px, 1px, 1px, 1px) !important;</code>: Clips the element to a 1x1 pixel area, effectively hiding it.</li>
    <li><code>clip-path: inset(50%) !important;</code>: Uses a clip path to hide the element.</li>
    <li><code>height: 1px !important;</code>: Sets the height to 1 pixel.</li>
    <li><code>width: 1px !important;</code>: Sets the width to 1 pixel.</li>
    <li><code>position: absolute !important;</code>: Positions the element absolutely.</li>
    <li><code>overflow: hidden !important;</code>: Hides any overflowing content.</li>
    <li><code>white-space: nowrap !important;</code>: Prevents wrapping of text.</li>
    <li><code>padding: 0 !important;</code>: Removes padding.</li>
    <li><code>margin: -1px !important;</code>: Sets a negative margin to further hide the element.</li>
  </ul>
</ul>

<ul>
  <li><code>html:</code> This selector targets the HTML root element and sets the <code>box-sizing</code> property to <code>"border-box."</code> This ensures that padding and borders are included in the element's total width and height.</li>
</ul>

<ul>
  <li><code>body:</code> This selector targets the <code>&lt;body&gt;</code> element and defines styles for the entire page. It sets the font family to a sans-serif font and the text color to a specific shade of blue.</li>
</ul>

<ul>
  <li><code>h1:</code> This selector targets all <code>&lt;h1&gt;</code> elements and sets their maximum width, margin, and padding.</li>
</ul>

<ul>
  <li><code>h1 .flex:</code> This selector targets elements with the class <code>"flex"</code> that are descendants of <code>&lt;h1&gt;</code> elements. It defines a flexbox container for these elements with a column-reverse flex direction and gap.</li>
</ul>

<ul>
  <li><code>h1 .flex span:first-of-type:</code> This selector targets the first <code>&lt;span&gt;</code> element that is a child of elements with the class <code>"flex"</code> inside <code>&lt;h1&gt;</code>. It sets the font size for this element.</li>
</ul>

<ul>
  <li><code>h1 .flex span:last-of-type:</code> This selector targets the last <code>&lt;span&gt;</code> element that is a child of elements with the class <code>"flex"</code> inside <code>&lt;h1&gt;</code>. It sets the font size for this element.</li>
</ul>

<ul>
  <li><code>section:</code> This selector targets all <code>&lt;section&gt;</code> elements and sets their maximum width, margin, and adds a border.</li>
</ul>

<ul>
  <li><code>#years:</code> This selector targets an element with the ID <code>"years,"</code> which is expected to be unique on the page. It defines styles for this element, including display as flex, justification, positioning, background color, and padding.</li>
</ul>

<ul>
  <li><code>#years span[class]:</code> This selector targets <code>&lt;span&gt;</code> elements within the element with the ID <code>"years"</code> that have a <code>class</code> attribute. It sets font-weight, width, and text alignment for these elements.</li>
</ul>

<ul>
  <li><code>.table-wrap:</code> This selector targets elements with the class <code>"table-wrap"</code> and adds padding to them.</li>
</ul>

<ul>
  <li><code>table:</code> This selector targets all <code>&lt;table&gt;</code> elements and sets various styles for tables, including border-collapse, width, position, and margin.</li>
</ul>

<ul>
  <li><code>table caption:</code> This selector targets <code>&lt;caption&gt;</code> elements within tables and sets styles for the table captions, including color, font size, font weight, and positioning.</li>
</ul>

<ul>
  <li><code>tbody td:</code> This selector targets table data cells within the <code>&lt;tbody&gt;</code> section and sets their width and min/max width.</li>
</ul>

<ul>
  <li><code>tbody th:</code> This selector targets table header cells within the <code>&lt;tbody&gt;</code> section and sets their width.</li>
</ul>

<ul>
  <li><code>tr[class="total"]:</code> This selector targets table rows with a specific <code>class</code> attribute value <code>"total"</code> and adds a double border and font weight.</li>
</ul>

<ul>
  <li><code>tr.total td:</code> This selector targets table data cells within rows with the class <code>"total"</code> and sets text alignment and padding.</li>
</ul>

<ul>
  <li><code>tr.total td:nth-of-type(3):</code> This selector targets the third table data cell within rows with the class <code>"total"</code> and adds padding to the right.</li>
</ul>

<ul>
  <li><code>tr.total:hover:</code> This selector targets rows with the class <code>"total"</code> when hovered over and changes their background color.</li>
</ul>

<ul>
  <li><code>td.current:</code> This selector targets table data cells with the class <code>"current"</code> and sets their font style to italic.</li>
</ul>

<ul>
  <li><code>tr.data:</code> This selector targets table rows with the class <code>"data"</code> and applies a background gradient.</li>
</ul>

<ul>
  <li><code>tr.data th:</code> This selector targets table header cells within rows with the class <code>"data"</code> and sets text alignment, padding, and top padding.</li>
</ul>

<ul>
  <li><code>tr.data th .
