<h1> Html explanation</h1>
<ul>
  <li>
    The code begins with the HTML5 doctype declaration, indicating that it is an HTML document.
  </li>
  <li>
    Inside the <code>&lt;html&gt;</code> tag, the <code>&lt;head&gt;</code> element is present, containing metadata information for the webpage.
  </li>
  <li>
    Within the <code>&lt;head&gt;</code> section, a <code>&lt;meta&gt;</code> element sets the character encoding to UTF-8 for proper text encoding.
  </li>
  <li>
    The <code>&lt;title&gt;</code> element specifies the title of the webpage, which will be displayed in the browser tab.
  </li>
  <li>
    A <code>&lt;link&gt;</code> element is used to link an external CSS stylesheet named "styles.css" to the HTML document, enabling the application of styles to the content.
  </li>
  <li>
    The <code>&lt;body&gt;</code> element encloses the visible content of the webpage.
  </li>
  <li>
    Inside the <code>&lt;body&gt;</code> element, there is a <code>&lt;div&gt;</code> with the class "frame." This represents the frame or border of the virtual painting.
  </li>
  <li>
    Within the "frame" <code>&lt;div&gt;</code>, there is another nested <code>&lt;div&gt;</code> with the class "canvas." This <code>&lt;div&gt;</code> represents the canvas area where the painting is displayed.
  </li>
  <li>
    Inside the "canvas" <code>&lt;div&gt;</code>, there are three additional nested <code>&lt;div&gt;</code> elements. These elements with classes "one," "two," and "three" are used to represent different parts or elements of the virtual painting.
  </li>
</ul>



<h1>Css Styling</h1>
CSS Styling
<ul>
  <li>
    <code>.canvas</code>: This class styles the container representing the canvas of the painting.
    <ul>
      <li>Sets the width to 500 pixels and the height to 600 pixels.</li>
      <li>Applies a background color of #4d0f00.</li>
      <li>Uses <code>overflow: hidden;</code> to ensure content doesn't overflow the container.</li>
      <li>Applies a <code>filter: blur(2px);</code> to add a subtle blur effect.</li>
    </ul>
  </li>
  <li>
    <code>.frame</code>: This class styles the frame or border of the painting.
    <ul>
      <li>Defines a black border with a width of 50 pixels.</li>
      <li>Sets the width to 500 pixels and adds 50 pixels of padding.</li>
      <li>Centers the frame horizontally using <code>margin: 20px auto;</code>.</li>
    </ul>
  </li>
  <li>
    <code>.one</code> and <code>.two</code>: These classes style the first and second visual elements within the canvas.
    <ul>
      <li><code>.one</code>:
        <ul>
          <li>Sets the width to 425 pixels and the height to 150 pixels.</li>
          <li>Applies a background color of #efb762.</li>
          <li>Adjusts margins and adds a box shadow with color #efb762.</li>
          <li>Uses <code>border-radius: 9px;</code> for rounded corners.</li>
          <li>Applies a slight rotation with <code>transform: rotate(-0.6deg);</code>.</li>
        </ul>
      </li>
      <li><code>.two</code>:
        <ul>
          <li>Sets the width to 475 pixels and the height to 200 pixels.</li>
          <li>Applies a background color of #8f0401.</li>
          <li>Adjusts margins, adds a box shadow with color #8f0401.</li>
          <li>Uses <code>border-radius: 8px 10px;</code> for different rounded corners.</li>
          <li>Applies a slight rotation with <code>transform: rotate(0.4deg);</code>.</li>
        </ul>
      </li>
      <li>Both <code>.one</code> and <code>.two</code>:
        <ul>
          <li>Apply a <code>filter: blur(1px);</code> for a slightly blurred appearance.</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>
    <code>.three</code>: This class styles the third visual element.
    <ul>
      <li>Sets the width to 91% and the height to 28% of its parent's dimensions.</li>
      <li>Applies a background color of #b20403.</li>
      <li>Centers the element horizontally using <code>margin: auto;</code>.</li>
      <li>Applies a <code>filter: blur(2px);</code> and adds a box shadow with color #b20403.</li>
      <li>Uses <code>border-radius: 30px 25px 60px 12px;</code> for varied rounded corners.</li>
    </ul>
  </li>
</ul>
