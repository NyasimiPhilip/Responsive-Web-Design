<code><h1>Index.html</h1></code>
 
  <li><strong>html lang="en"</strong>: The opening tag for the HTML document, specifying that the document is in English ("en"). The entire HTML content is contained within this element.</li>
  <li><strong>head</strong>: The head section of the document contains meta-information about the document and external resources. It doesn't display content on the web page itself.
    <ul>
      <li><code>meta charset="UTF-8"</code>: Specifies the character encoding of the document as UTF-8, which is a character encoding that supports a wide range of characters from different languages and scripts.</li>
      <li><code>title</code>: Sets the title of the web page to "Piano." This title appears in the browser's title bar or tab.</li>
      <li><code>meta name="viewport" content="width=device-width, initial-scale=1.0"</code>: This meta tag is often used for responsive web design. It tells the browser to set the viewport width to the device width and set the initial zoom level to 1.0, which helps in rendering the web page correctly on various devices.</li>
      <li><code>link rel="stylesheet" href="./styles.css"</code>: Links an external CSS stylesheet to the HTML document. The href attribute specifies the path to the CSS file, which is "./styles.css" in this case. This stylesheet will be used to style the content of the HTML page.</li>
    </ul>
  </li>
  <li><strong>body</strong>: The body section of the document contains the visible content of the web page.
    <ul>
      <li><code>div id="piano"</code>: This is a container div with the id "piano." It contains the entire piano interface.</li>
      <li><code>img class="logo" src="https://cdn.freecodecamp.org/platform/universal/fcc_primary.svg" alt="freeCodeCamp Logo"</code>: An image element with the class "logo." It displays the freeCodeCamp logo. The alt attribute provides alternative text for the image, which is displayed if the image cannot be loaded or for accessibility.</li>
      <li><code>div class="keys"</code>: This is a container div with the class "keys." It contains the piano keys.</li>
      <li>A series of <code>div</code> elements with the class "key" and "black--key" represent the individual piano keys. These elements are used to create the visual representation of the piano keys. The class "black--key" is likely used to style the black keys differently from the white keys.</li>
    </ul>
  </li>
</ul>
