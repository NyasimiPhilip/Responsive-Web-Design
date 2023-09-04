<h1>HTML (Balance Sheet)</h1>

<code>&lt;!DOCTYPE html&gt;</code> - The document begins with the HTML5 doctype declaration, specifying that this is an HTML5 document.
<code>&lt;html lang="en"&gt;</code> - The root element of the HTML document, specifying the document's language as English.
<code>&lt;head&gt;</code> - The head section of the document, which contains metadata and links to external resources.
<code>&lt;meta charset="UTF-8"&gt;</code> - Specifies the character encoding for the document as UTF-8, ensuring proper text encoding.
<code>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</code> - Sets the viewport meta tag, ensuring proper rendering on various devices and screen sizes.
<code>&lt;title&gt;Balance Sheet&lt;/title&gt;</code> - Defines the title of the webpage, which appears in the browser's title bar or tab.
<code>&lt;link rel="stylesheet" href="./styles.css"&gt;</code> - Links to an external stylesheet named "styles.css" to apply CSS styles to the HTML content.
<code>&lt;body&gt;</code> - The main content of the webpage is contained within the body element.
<code>&lt;main&gt;</code> - A semantic HTML5 element used to define the main content of the document. It contains the entire balance sheet.
<code>&lt;section&gt;</code> - A section element that wraps the balance sheet content.
<code>&lt;h1&gt;</code> - The main heading of the balance sheet, which includes the company name ("AcmeWidgetCorp") and the title ("Balance Sheet"). It uses a nested span structure for styling purposes.
<code>&lt;div id="years" aria-hidden="true"&gt;</code> - A container for displaying the years. It includes spans for each year (2019, 2020, 2021) with the "year" class.
<code>&lt;div class="table-wrap"&gt;</code> - A container for wrapping the tables in the balance sheet.
<code>&lt;table&gt;</code> - A table element for displaying the assets section of the balance sheet.
<code>&lt;caption&gt;</code> - A caption for the table, indicating that this table represents "Assets."
<code>&lt;thead&gt;</code> - The table header section.
<code>&lt;tr&gt;</code> - A table row containing headers for each column. It includes empty td for alignment and th elements for each year.
<code>&lt;tbody&gt;</code> - The table body section for data rows.
<code>&lt;tr class="data"&gt;</code> - A data row with a th element for the asset name and td elements for the financial data (e.g., cash, checking, savings). Each row includes a description within a span element with the "description" class.
<code>&lt;tr class="total"&gt;</code> - A total row summarizing the asset totals. It includes a th element for the total and td elements for each year's total. The "sr-only" class is used for screen reader accessibility.
