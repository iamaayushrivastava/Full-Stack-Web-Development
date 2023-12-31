## Overview

In HTML, the way text is displayed (whether it appears on a new line or on the same line) depends on the HTML element being used and the default rendering behaviour of browsers.

Here are some common scenarios:

1. **Block-Level Elements:** Block-level elements typically start on a new line and take up the full width available. They create a "block" of content. Examples of block-level elements include `<div>`, `<p>`, `<h1>` to `<h6>`, and `<ul>`/`<ol>` with their list items `<li>`.

   ```html
   <div>This is a block-level element.</div>
   <p>This is another block-level element.</p>
   <ul>
       <li>List item 1</li>
       <li>List item 2</li>
   </ul>
   ```

2. **Inline Elements:** Inline elements, on the other hand, do not start on a new line and only take up as much width as necessary. They flow within the text and can appear on the same line as other content. Examples of inline elements include `<span>`, `<a>`, `<strong>`, and `<em>`.

   ```html
   <span>This is an inline element.</span>
   <a href="#">This is another inline element.</a>
   ```

3. **Line Breaks:** You can force text to appear on a new line within a block-level element using the `<br>` element. This creates a line break.

   ```html
   <p>This is some text.<br>
   This text will be on a new line.</p>
   ```

4. **Whitespaces:** By default, spaces and line breaks in the HTML code itself are often ignored when rendering the page. This means multiple spaces or line breaks will be collapsed into a single space when displayed.

   ```html
   <p>This text       has      spaces      between words.</p>
   <p>Line 1<br>Line 2</p>
   ```

**Note:** Remember that CSS can also influence how elements are displayed. CSS properties like display and whitespaces can affect whether elements are displayed on the same line or on separate lines. Additionally, CSS can be used to control spacing, alignment, and layout, allowing you to achieve specific visual effects for your content.
