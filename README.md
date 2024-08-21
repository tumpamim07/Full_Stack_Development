 <div align="center">
<h1>Full Stack Development</h1>
</div>

<details>
<summary>Class 01 (Software Installation & Course Roadmap)</summary>

## Class 01 Topics:    
- Course Roadmap and Guideline
- Software Installation(Node.js & VS Code)

</details>

<details>
<summary>Class 02 (Internet & HTML)</summary>
   
## Class 02 Topics:
    
- Basic Knowledge about Internet
- Difference between HTML , CSS and JavaScript
- Metadata, Attributes
- Elements
- HTML Tags
    
### Difference between HTML , CSS and JavaScript
    
- **HTML (HyperText Markup Language)**: Structures the content on a webpage. Think of it as the building blocks, like headings, paragraphs, and lists.
- **CSS (Cascading Style Sheets)**: Styles the content created by HTML. It controls the look and feel, such as colors, fonts, and layout.
- **JavaScript**: Adds interactivity and functionality to a webpage. It allows you to create dynamic effects like animations, form validations, and interactive elements.
    
**In Short**:
- HTML builds the structure,
- CSS designs the appearance,
- JavaScript makes it interactive.
    
### 1. `<!DOCTYPE html>`
    
    This line declares the document type. It tells the browser that this is an HTML5 document. It ensures that the webpage is rendered in the standard way across different browsers.
    
### 2. `<html lang="en">`
    
    This tag starts the HTML document. The `lang="en"` attribute specifies that the language of the content in this document is English. This is helpful for search engines and browsers in understanding the language used on the page.
    
### 3. `<head>`
    
    The `<head>` section contains metadata and information about the document that isn’t directly displayed on the page. This includes the page title, character encoding, viewport settings, and more.
    
### 4. `<meta charset="UTF-8">`
    
    This meta tag defines the character encoding for the document as UTF-8. UTF-8 is a standard character encoding that supports almost all characters from all languages, ensuring that the text on your webpage displays correctly.
    
### 5. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
    
    This tag controls the layout on mobile browsers. It ensures that the webpage is displayed correctly on different devices by setting the viewport width to match the device's width and scaling the page initially at 100% (no zoom).
    
### 6. `<title>Project</title>`
    
    This tag sets the title of the webpage, which appears in the browser tab. In this case, the title is "Project."
    
### 7. `<body>`
    
    The `<body>` tag contains all the content that will be displayed on the webpage, such as text, images, and other elements. Currently, the body is empty, meaning no content will be shown on the page.
    
### 8. `</body>`
    
    This tag closes the body section.
    
### 9. `</html>`
    
    This tag closes the entire HTML document.
    
### **Metadata**

- **Definition**: Metadata is data about data. In the context of a webpage, metadata provides information about the HTML document that isn't displayed directly on the page but is essential for the browser, search engines, and other systems.
    - **Examples in HTML**:
        - `<meta charset="UTF-8">`: Specifies the character encoding.
        - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Provides instructions for responsive design.
        - `<title>Tumpa</title>`: Defines the title of the page that appears in the browser tab.
- **Purpose**: Metadata helps browsers display content correctly, assists search engines in indexing pages, and provides information that can be used by other tools and systems.
    
### **Attribute**
    
- **Definition**: An attribute in HTML is a modifier of an HTML element. It provides additional information about an element and usually comes in name-value pairs.
    - **Structure**: An attribute is written within the opening tag of an element.
        - **Example**: In `<html lang="en">`, `lang` is the attribute name, and `"en"` is the attribute value.
    - **Common Attributes**:
        - `id`: Uniquely identifies an element.
        - `class`: Assigns one or more class names to an element for styling or scripting.
        - `src`: Specifies the source of an image in an `<img>` tag.
        - `href`: Specifies the URL in an anchor `<a>` tag.
    
**In Short:**
    
- **Metadata** provides essential information about a webpage that is not visible to users.
- **Attributes** modify HTML elements by adding extra information or defining specific characteristics.
    
### Element
    
    An HTML element is a building block of a webpage, consisting of a start tag, content, and an end tag. Elements define the structure and content of a webpage.
    
### Example:
    
    ```html
    <p>This is a paragraph.</p>
    
    ```
    
- **Start Tag (`<p>`)**: Indicates the beginning of the element.
- **Content (`This is a paragraph.`)**: The text or other elements contained within the tags.
- **End Tag (`</p>`)**: Indicates the end of the element.
    
#### Key Points:
    
- Elements can also contain other elements, creating a nested structure.
- Some elements are self-closing, like `<img />` for images.
    
    ### Example of Different Elements:
    
    - **Heading**: `<h1>Title</h1>`
    - **Paragraph**: `<p>Text</p>`
    - **Link**: `<a href="<https://example.com>">Click here</a>`
    - **Image**: `<img src="image.jpg" alt="Description" />`
    
    Each element serves a specific purpose in creating the content, layout, and functionality of a webpage.
    
### HTML Tags
    
### 1. **Paragraph Tag (`<p>`)**
    
- **Description**: The `<p>` tag is used to define a paragraph in HTML. It groups together text into blocks, making the content easier to read and understand.
    - **Example**: `<p>This is a paragraph of text.</p>`
    
### 2. **Comment Out Tag (`<!-- -->`)**
    
- **Description**: Comments are used to add notes or explanations within your HTML code without them being displayed on the webpage. Comments are ignored by the browser.
    - **Example**: `<!-- This is a comment that won't appear on the webpage -->`
    
### 3. **HTML Attribute**
    
- **Description**: Attributes provide additional information about HTML elements. They usually appear within the opening tag and consist of a name and a value.
    - **Example**: In `<a href="<https://example.com>">Link</a>`, `href` is an attribute that specifies the URL the link points to.
    
### 4. **Heading Tag (`<h1>` to `<h6>`)**
    
- **Description**: Heading tags define headings or titles on a webpage. There are six levels of headings, from `<h1>` (most important) to `<h6>` (least important).
    - **Example**:
        - `<h1>Main Title</h1>`
        - `<h2>Subheading</h2>`
    
### 5. **Case Sensitivity in HTML**
    
- **Description**: HTML is not case-sensitive, which means you can write tags, attributes, and values in uppercase, lowercase, or a mix. However, it is good practice to write in lowercase for consistency.
    - **Example**: `<P>` and `<p>` are both valid, but `<p>` is preferred.
    
### 6. **Anchor Tag Types (`<a>`)**
    
- **Description**: The `<a>` tag is used to create hyperlinks. There are two main types:
        - **Internal Links**: Link to another page within the same website.
        - **External Links**: Link to a page on a different website.
    - **Example**:
        - Internal: `<a href="about.html">About Us</a>`
        - External: `<a href="<https://example.com>">Visit Example</a>`
    
### 7. **Relative URL**
    
- **Description**: A relative URL is a link that points to a file or page within the same website. It doesn’t include the full website address (domain name).
    - **Example**: `href="about.html"` assumes the "about.html" file is in the same directory as the current page.
    
### 8. **Absolute URL**
    
- **Description**: An absolute URL is a full web address that includes the domain name, pointing to a specific page or file on the internet.
    - **Example**: `href="<https://example.com/about.html>"`
    
### 9. **Break Tag (`<br>`)**
    
- **Description**: The `<br>` tag creates a line break, which moves the content following it to the next line. It’s often used to separate lines of text within a paragraph.
    - **Example**:
        
        ```html
        one.<br>
        two.
        
        ```
### 10. **Preformatted Text Tag (`<pre>`)**
    
- **Description**: The `<pre>` tag preserves both spaces and line breaks in the text, displaying it exactly as written in the HTML code. It’s useful for showing code or text where formatting matters.
    - **Example**:
        
        ```html
        <pre>
        This is
        Life     .
        </pre>
        
        ```
### 11. **Bold Tag (`<b>`)**
    
- **Description**: The `<b>` tag makes text bold, which can be used to emphasize words or phrases.
    - **Example**: `<b>This text is bold.</b>`
    
### 12. **Italic Tag (`<i>`)**
    
- **Description**: The `<i>` tag makes text italic, often used for emphasis or to denote titles of works.
    - **Example**: `<i>This text is italic.</i>`
    
### 13. **Underline Tag (`<u>`)**
    
- **Description**: The `<u>` tag underlines text. Underlined text can be used for emphasis, though it’s less common due to underlines being associated with links.
    - **Example**: `<u>This text is underlined.</u>`
    
### 14. **Big Tag (`<big>`)**
    
- **Description**: The `<big>` tag increases the size of the text slightly above the normal size.
    - **Example**: `<big>This text is slightly bigger.</big>`
    
### 15. **Small Tag (`<small>`)**
    
- **Description**: The `<small>` tag reduces the size of the text slightly below the normal size. It’s often used for fine print or disclaimers.
    - **Example**: `<small>This text is slightly smaller.</small>`
    
### 16. **Horizontal Rule Tag (`<hr>`)**
    
- **Description**: The `<hr>` tag creates a horizontal line across the webpage, often used to separate sections of content.
    - **Example**: `<hr>` creates a line.
    
### 17. **Subscript Tag (`<sub>`)**
    
- **Description**: The `<sub>` tag is used to display text as subscript, which appears slightly below the normal text line. It’s commonly used in chemical formulas or mathematical expressions.
    - **Example**: `H<sub>2</sub>O` displays as H₂O.
    
### 18. **Superscript Tag (`<sup>`)**
    
- **Description**: The `<sup>` tag is used to display text as superscript, which appears slightly above the normal text line. It’s often used for exponents or footnotes.
    - **Example**: `E = mc<sup>2</sup>` displays as E = mc².
    
### **Ordered List (`<ol>`)**
    
- **Description**: The `<ol>` tag is used to create an ordered list, where each item is numbered. This is useful when you want to present items in a specific sequence.
    - **Example**:
        
        ```html
        <ol>
            <li>First item</li>
            <li>Second item</li>
            <li>Third item</li>
        </ol>
        
        ```   
        - This will display:
            1. First item
            2. Second item
            3. Third item
    
### **Unordered List (`<ul>`)**
    
- **Description**: The `<ul>` tag is used to create an unordered list, where each item is marked with a bullet point. This is suitable for lists where the order of items doesn’t matter.
    - **Example**:
        
        ```html
        <ul>
            <li>Item one</li>
            <li>Item two</li>
            <li>Item three</li>
        </ul>
        
        ```
        - This will display:
            - Item one
            - Item two
            - Item three
    
### **List Item (`<li>`)**
    
- **Description**: The `<li>` tag is used to define each item within both ordered (`<ol>`) and unordered (`<ul>`) lists. It represents an individual list item.
    - **Example**:
        
        ```html
        <ul>
            <li>Apple</li>
            <li>Banana</li>
            <li>Cherry</li>
        </ul>
        
        ```
        - This will display:
            - Apple
            - Banana
            - Cherry
    
### **Table (`<table>`)**
    
- **Description**: The `<table>` tag is used to create a table in HTML, which allows you to organize data into rows and columns.
    - **Example**:
        
        ```html
        <table>
            <tr>
                <td>Row 1, Cell 1</td>
                <td>Row 1, Cell 2</td>
            </tr>
            <tr>
                <td>Row 2, Cell 1</td>
                <td>Row 2, Cell 2</td>
            </tr>
        </table>
        
        ``` 
        - This will display a table with two rows and two columns.
    
### **Table Row (`<tr>`)**
    
- **Description**: The `<tr>` tag is used to define a row in a table. Each row is a horizontal line of cells in the table.
    - **Example**:
        
        ```html
        <tr>
            <td>Cell 1</td>
            <td>Cell 2</td>
        </tr>
        
        ```
        
        - This defines a single row with two cells.
    
### **Table Data (`<td>`)**
    
- **Description**: The `<td>` tag is used to define a cell within a table row. Each `<td>` represents a single piece of data within the row.
    - **Example**:
        
        ```html
        <td>Data</td>
        
        ```  
        - This defines one cell in a table that contains the word "Data."
    
### **Ordered List with Starting Number (`<ol start="5">`)**
    
- **Description**: The `start` attribute within an `<ol>` tag allows you to set the starting number of the list items. Instead of starting from 1, the list can start from any number you specify.
    - **Example**:
        
        ```html
        <ol start="5">
            <li>First item</li>
            <li>Second item</li>
        </ol>
        
        ```  
        - This will display:
        5. First item
        6. Second item
    
    **In Short:**
    
    - **`<ol>`**: Creates an ordered (numbered) list.
    - **`<ul>`**: Creates an unordered (bulleted) list.
    - **`<li>`**: Defines each item within the list.
    - **`<table>`**: Creates a table to organize data into rows and columns.
    - **`<tr>`**: Defines a row in a table.
    - **`<td>`**: Defines a cell within a table row.
    - **`<ol start="5">`**: Starts an ordered list at a specific number, such as 5.
    
    These elements are essential for organizing content on a webpage, whether you're listing items, creating tables, or customizing list numbering.
    
## Assignment: Solve the 5 given problems

</details>