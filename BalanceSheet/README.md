<h1>HTML (Balance Sheet)</h1>

<ul>
  <li><strong>&lt;!DOCTYPE html&gt;</strong> - The document begins with the HTML5 doctype declaration, specifying that this is an HTML5 document.</li>
  <li><strong>&lt;html lang="en"&gt;</strong> - The root element of the HTML document, specifying the document's language as English.</li>
  <li><strong>&lt;head&gt;</strong> - The head section of the document, which contains metadata and links to external resources.
    <ul>
      <li><strong>&lt;meta charset="UTF-8"&gt;</strong> - Specifies the character encoding for the document as UTF-8, ensuring proper text encoding.</li>
      <li><strong>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</strong> - Sets the viewport meta tag, ensuring proper rendering on various devices and screen sizes.</li>
      <li><strong>&lt;title&gt;Balance Sheet&lt;/title&gt;</strong> - Defines the title of the webpage, which appears in the browser's title bar or tab.</li>
      <li><strong>&lt;link rel="stylesheet" href="./styles.css"&gt;</strong> - Links to an external stylesheet named "styles.css" to apply CSS styles to the HTML content.</li>
    </ul>
  </li>
  <li><strong>&lt;body&gt;</strong> - The main content of the webpage is contained within the body element.
    <ul>
      <li><strong>&lt;main&gt;</strong> - A semantic HTML5 element used to define the main content of the document. It contains the entire balance sheet.
        <ul>
          <li><strong>&lt;section&gt;</strong> - A section element that wraps the balance sheet content.
            <ul>
              <li><strong>&lt;h1&gt;</strong> - The main heading of the balance sheet, which includes the company name ("AcmeWidgetCorp") and the title ("Balance Sheet"). It uses a nested span structure for styling purposes.</li>
              <li><strong>&lt;div id="years" aria-hidden="true"&gt;</strong> - A container for displaying the years. It includes spans for each year (2019, 2020, 2021) with the "year" class.</li>
              <li><strong>&lt;div class="table-wrap"&gt;</strong> - A container for wrapping the tables in the balance sheet.
                <ul>
                  <li><strong>&lt;table&gt;</strong> - A table element for displaying the assets section of the balance sheet.
                    <ul>
                      <li><strong>&lt;caption&gt;</strong> - A caption for the table, indicating that this table represents "Assets."</li>
                      <li><strong>&lt;thead&gt;</strong> - The table header section.
                        <ul>
                          <li><strong>&lt;tr&gt;</strong> - A table row containing headers for each column. It includes empty td for alignment and th elements for each year.</li>
                        </ul>
                      </li>
                      <li><strong>&lt;tbody&gt;</strong> - The table body section for data rows.
                        <ul>
                          <li><strong>&lt;tr class="data"&gt;</strong> - A data row with a th element for the asset name and td elements for the financial data (e.g., cash, checking, savings). Each row includes a description within a span element with the "description" class.</li>
                          <li><strong>&lt;tr class="total"&gt;</strong> - A total row summarizing the asset totals. It includes a th element for the total and td elements for each year's total. The "sr-only" class is used for screen reader accessibility.</li>
                        </ul>
                      </li>
                    </ul>
                  </li>
                </ul>
              </li>
            </ul>
          </li>
        </ul>
      </li>
    </ul>
  </li>
</ul>
