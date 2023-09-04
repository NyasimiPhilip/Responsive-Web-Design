<h1>HTML (Balance Sheet)</h1>

<ul>
<li>: <!DOCTYPE html> - The document begins with the HTML5 doctype declaration, specifying that this is an HTML5 document.
<li>: <html lang="en"> - The root element of the HTML document, specifying the document's language as English.
<li>: <head> - The head section of the document, which contains metadata and links to external resources.
<ul>
<li>: <meta charset="UTF-8"> - Specifies the character encoding for the document as UTF-8, ensuring proper text encoding.
<li>: <meta name="viewport" content="width=device-width, initial-scale=1.0"> - Sets the viewport meta tag, ensuring proper rendering on various devices and screen sizes.
<li>: <title>Balance Sheet</title> - Defines the title of the webpage, which appears in the browser's title bar or tab.
<li>: <link rel="stylesheet" href="./styles.css"> - Links to an external stylesheet named "styles.css" to apply CSS styles to the HTML content.
</ul>
<li>: <body> - The main content of the webpage is contained within the body element.
<ul>
<li>: <main> - A semantic HTML5 element used to define the main content of the document. It contains the entire balance sheet.
<ul>
<li>: <section> - A section element that wraps the balance sheet content.
<ul>
<li>: <h1> - The main heading of the balance sheet, which includes the company name ("AcmeWidgetCorp") and the title ("Balance Sheet"). It uses a nested span structure for styling purposes.
<li>: <div id="years" aria-hidden="true"> - A container for displaying the years. It includes spans for each year (2019, 2020, 2021) with the "year" class.
<li>: <div class="table-wrap"> - A container for wrapping the tables in the balance sheet.
<ul>
<li>: <table> - A table element for displaying the assets section of the balance sheet.
<ul>
<li>: <caption> - A caption for the table, indicating that this table represents "Assets."
<li>: <thead> - The table header section.
<ul>
<li>: <tr> - A table row containing headers for each column. It includes empty td for alignment and th elements for each year.
</ul>
<li>: <tbody> - The table body section for data rows.
<ul>
<li>: <tr class="data"> - A data row with a th element for the asset name and td elements for the financial data (e.g., cash, checking, savings). Each row includes a description within a span element with the "description" class.
<li>: <tr class="total"> - A total row summarizing the asset totals. It includes a th element for the total and td elements for each year's total. The "sr-only" class is used for screen reader accessibility.
</ul>
</ul>
Similar table structures exist for the "Liabilities" and "Net Worth" sections, each with its own table, caption, thead, tbody, data rows, and total row.
</ul>
</ul>
</ul>
</li>
</ul>
</li>
</ul>
