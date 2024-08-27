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

<details>
<summary> Class 03 (HTML) </summary>

## Class 03 Topics:
- HTML Tags & Attribute
- Image
- Video

    ### **Document Structure**
    
    ```html
    <!DOCTYPE html>
    <html lang="en">
    ```
    
    - This declares the document type as HTML5 and sets the language of the document to English.
    - The `<!DOCTYPE html>` declares the document type, telling the browser that this is an HTML5 document.
    - The `<html>` element is the root element of the HTML document.
    - The `lang="en"` attribute specifies that the language of the document is English.
    
    ### **Head Section**
    
    ```html
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Class 03 Practise</title>
    </head>
    
    ```
    
    - The `<head>` element contains meta-information about the document, like the character encoding (`<meta charset="UTF-8">`) and the viewport settings (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`), which help make the website responsive.
    - The `<title>` element sets the title of the webpage, which is displayed on the browser tab. Here, it is "Class 03 Practise."
    
    ### Body Section
    
    The body section of an HTML document is where all the content that users see on the webpage is placed. It includes text, images, videos, forms, tables, and any other elements that make up the webpage's visual and interactive components. Such as:
    
    1. **Lists**:
        - You can create bullet points using an unordered list (`<ul>`) and numbered items using an ordered list (`<ol>`). For example, you might list hobbies like "Reading" or tasks like "Working."
    2. **Tables**:
        - Tables (`<table>`) are used to organize data in rows and columns. You can label each column with headers and fill in data for things like student names and their roll numbers.
    3. **Forms**:
        - Forms (`<form>`) are used to collect user input. You can create text fields for usernames and passwords, radio buttons for choosing one option from a list (like HTML or CSS), and checkboxes for selecting multiple options (like hobbies).
    4. **Text Areas and Dropdowns**:
        - A text area (`<textarea>`) allows users to enter longer text, like feedback. Dropdown menus (`<select>`) let users choose one option from a list, such as selecting a city from Dhaka, Chittagong, or Barisal.
    5. **Multimedia**:
        - You can embed videos using the `<video>` tag or display another webpage within your webpage using an `<iframe>`.
    6. **Styling and Divisions**:
        - Divs (`<div>`) are containers that group different elements together. You can style these elements directly in the HTML with inline styles or with a `<style>` tag that controls how the content looks, such as changing the text color.
    
    The body section is like the main part of a book, where all the stories, images, and interactive elements are displayed for the reader to experience.
    
    ### Lists
    
    ```html
    <ul>
        <li>Reading</li>
        <li>Writing</li>
    </ul>
    ```
    
    - This creates a bulleted list with items "Reading" and "Writing."
    - **Unordered List (`<ul>`)**: This creates a simple list where each item is marked with a bullet point. In this code, the unordered list contains two items: "Reading" and "Writing." These items are displayed with a small dot (bullet) next to each one, making it easy to see the list of activities.
    
    ```html
    <ol>
        <li>Traveling</li>
        <li>Working</li>
    </ol>
    ```
    
    - This creates a numbered list with items "Traveling" and "Working."
    - **Ordered List (`<ol>`)**: This creates a list where each item is numbered. In this code, the ordered list contains two items: "Traveling" and "Working." These items are displayed with numbers next to them, like "1. Traveling" and "2. Working," which shows a clear sequence or order for the list.
    
    ### **Table**
    
    ```html
    <table>
        <caption>Student</caption>
        <thead>
            <th colspan="2">Data</th>
        </thead>
        <thead>
            <th>Name</th>
            <th>Roll</th>
        </thead>
        <tbody>
            <tr>
                <td>A</td>
                <td>028</td>
            </tr>
            <tr>
                <td>B</td>
                <td>029</td>
            </tr>
        </tbody>
    </table>
    ```
    
    - This table displays student information with a caption "Student," headers "Name" and "Roll," and two rows of data.
    - A table is created with the `<table>` element.
    - The `<caption>` tag in HTML is used to provide a title or description for a table. This title is usually displayed above the table, giving context to the data within the table.
    - The first `<thead>` contains a header row that spans two columns (`colspan="2"`) with the title "Data."
    - The second `<thead>` contains the actual headers "Name" and "Roll."
    - The `<tbody>` contains the table's body with two rows of data: "A, 028" and "B, 029."
    
    ### **Form**
    
    In HTML, a `<form>` is used to collect user input. The data from the form can then be sent to a server for processing. A form typically includes elements like text fields, checkboxes, radio buttons, and submit buttons.
    
    ### **Basic Structure of a Form:**
    
    ```html
    <form action="/submit-form" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name">
    
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email">
    
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password">
    
        <input type="submit" value="Submit">
    </form>
    ```
    
    - **`<form>` Tag:**
        - The `<form>` tag creates a form for user input.
        - **`action`:** The URL where the form data will be sent for processing.
        - **`method`:** Specifies how to send form data. Common methods are `get` (appends data to the URL) and `post` (sends data as a package in the body of the request).
    - **`<label>` Tag:**
        - Labels are linked to form elements via the `for` attribute, which matches the `id` of the input field. This makes the form more accessible, allowing users to click the label to focus on the input field.
    - **`<input>` Tag:**
        - The `<input>` tag is used to create various form controls.
        - **`type="text"`:** Creates a single-line text input.
        - **`type="email"`:** Creates an input field specifically for email addresses.
        - **`type="password"`:** Creates a password field that hides the input text.
        - **`type="submit"`:** Creates a button that submits the form.
    - **`placeholder`:** Provides a hint to the user about what to enter in the input field.
    
    ### **Example of a Complete Form:**
    
    ```html
    <form action="/submit-form" method="post">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" placeholder="Enter your username">
    
        <label for="age">Age:</label>
        <input type="number" id="age" name="age" placeholder="Enter your age">
    
        <label for="gender">Gender:</label>
        <select id="gender" name="gender">
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select>
    
        <label for="bio">Biography:</label>
        <textarea id="bio" name="bio" placeholder="Tell us about yourself"></textarea>
    
        <input type="submit" value="Register">
    </form>
    ```
    
    - **`type="number"`:** Creates a field for numeric input.
    - **`<select>`:** Creates a dropdown menu with options.
    - **`<textarea>`:** Creates a multi-line text input for longer text, such as a biography.
    
    ### Key Points:
    
    - **Forms are essential** for collecting user data on websites.
    - **Different input types** allow for various kinds of user input, making the form versatile.
    - **Labels and placeholders** improve usability and accessibility by guiding users on what information to enter.
    
    Forms are a fundamental part of web development, enabling interaction between users and web applications.
    
    ### **Radio Buttons**
    
    ```html
    <form>
        <input type="radio" id="html" name="fav" value="HTML">
    		<label for="html">HTML</label>
    		
    		<input type="radio" id="css" name="fav" value="CSS">
    		<label for="css">CSS</label>
    </form>
    ```
    
    In HTML, a radio button is a form element that allows users to select one option from a set of predefined choices. Radio buttons are useful when you want users to make a single selection from a list.
    
    ### Basic Structure of Radio Buttons:
    
    - **`<input type="radio">`**: This creates a radio button.
        - **`name` attribute**: All radio buttons with the same `name` are grouped together. Only one radio button in the group can be selected at a time.
        - **`value` attribute**: Specifies the value sent to the server when the form is submitted.
    - **`<label>`**: The `<label>` tag is used to provide a label for the radio button. Clicking the label will select the associated radio button, which improves usability.
    
    ### Example:
    
    ```html
    <form>
        <fieldset>
            <legend>Choose your favorite fruit:</legend>
    
            <label>
                <input type="radio" name="fruit" value="apple"> Apple
            </label>
            <br>
            <label>
                <input type="radio" name="fruit" value="banana"> Banana
            </label>
            <br>
            <label>
                <input type="radio" name="fruit" value="orange"> Orange
            </label>
        </fieldset>
    </form>
    ```
    
    - **`<fieldset>`**: Groups related form elements together. It is often used with `<legend>` to provide a caption for the group.
    - **`<legend>`**: Provides a heading for the group of radio buttons, making the form more understandable.
    
    ### Key Points:
    
    - **Single Selection**: Only one radio button from a group can be selected at a time.
    - **Grouping**: Use the same `name` attribute for all radio buttons in a group to ensure mutual exclusivity.
    - **Labels**: Always use labels for radio buttons to improve form accessibility and user experience.
    
    Radio buttons are commonly used in forms where the user needs to select one option out of several, such as choosing a preference or answering a question with predefined answers.
    
    ### **Checkboxes**
    
    ```html
    <input type="checkbox" name="class" id="1" value="Sleeping">
    <label for="1">Sleeping</label>
    <br>
    <input type="checkbox" name="class" id="2" value="Working">
    <label for="2">Working</label>
    <br>
    <input type="checkbox" name="class" id="3" value="Traveling">
    <label for="3">Traveling</label>
    ```
    
    - The `<input type="checkbox">` elements allow users to select multiple options from a list, which includes "Sleeping," "Working," and "Traveling." (Note: IDs should be unique.)
    
    ### **Textarea**
    
    ```html
    <label for="10">Feedback</label>
    <br>
    <textarea name="feedback" id="10" placeholder="enter your feedback" rows="5"></textarea
    ```
    
    - A `<textarea>` element is provided for users to enter feedback. The placeholder text says "enter your feedback," and the area has a specified number of rows.
    
    ### **Dropdown Menu**
    
    ```html
    <label for="11">City</label>
    <select name="city" id="11">
        <option value="Dhaka">Dhaka</option>
        <option value="Chittagong">Chittagong</option>
        <option value="Barishal">Barishal</option>
    </select>
    ```
    
    - The `<select>` element creates a dropdown menu for selecting a city. The options provided are "Dhaka," "Chittagong," and "Barishal."
    
    ### **Iframe**
    
    ```html
    <iframe src="https://www.wikipedia.org/" frameborder="0"></iframe>
    ```
    
    - The `<iframe>` element is used to embed another webpage (in this case, Wikipedia) within the current page.
    
    ### **Video**
    
    ```html
    <video src="0824.mp4" height="100px" controls="autoplay">My Video</video>
    ```
    
    This video element embeds a video ("0824.mp4") with a height of 100px and controls for play/pause. The `autoplay` attribute automatically starts the video.
    
    In HTML, the `<video>` tag is used to embed video content directly into a webpage. It allows users to view videos without needing additional plugins or software. The `<video>` tag provides built-in controls for playing, pausing, and adjusting the volume of the video.
    
    ### Basic Structure of the `<video>` Tag:
    
    ```html
    <video src="video.mp4" controls>
        Your browser does not support the video tag.
    </video>
    ```
    
    - **`<video>` Tag**: This tag is used to embed video content.
        - **`src` attribute**: Specifies the path to the video file. In this example, it’s `"video.mp4"`.
        - **`controls` attribute**: Adds play, pause, and volume controls to the video player. Without this attribute, the video will play automatically without user controls.
    - **Fallback Content**: The text "Your browser does not support the video tag." is displayed if the browser cannot play the video. This provides a fallback message for users with older browsers.
    
    ### Additional Attributes:
    
    - **`autoplay`**: Makes the video start playing automatically when the page loads.
        
        ```html
        htmlCopy code
        <video src="video.mp4" controls autoplay>
        
        ```
        
    - **`loop`**: Makes the video restart automatically after it finishes.
        
        ```html
        htmlCopy code
        <video src="video.mp4" controls loop>
        
        ```
        
    - **`muted`**: Mutes the audio of the video.
        
        ```html
        htmlCopy code
        <video src="video.mp4" controls muted>
        
        ```
        
    - **`poster`**: Specifies an image to show while the video is downloading or before the video starts playing.
        
        ```html
        htmlCopy code
        <video src="video.mp4" controls poster="thumbnail.jpg">
        ```
        
    
    ### Key Points:
    
    - **Formats**: Common video formats include MP4, WebM, and Ogg. MP4 is widely supported across modern browsers.
    - **Controls**: The `controls` attribute provides basic video player controls.
    - **Attributes**: Customize video behaviour with attributes like `autoplay`, `loop`, and `muted`.
    
    ### **Preformatted Text (`<pre>`)**
    
    ```html
    <pre>
    <div class="class" style="color: red">
        I am a Bangladeshi
        <p id="1" style="color: green">I am a Bangladeshi</p>
        <p>I am a Bangladeshi</p>
    </div>
    </pre>
    ```
    
    - The `<pre>` tag preserves whitespace and line breaks. Inside it, a `<div>` is styled with inline CSS to display text in red, with one paragraph in green.
    - The `<pre>` element is used to display text with preserved whitespace and line breaks.
    
    ### **Div Elements and Inline Styling**
    
    ```html
    <div class="class">
        <p id="one">Hello World</p>
        <p id="two">Hello World</p>
        <p id="three">Hello World</p>
        <style>
            .class {
                color: red;
            }
            #one {
                color: blue;
            }
            #three {
                color: violet;
            }
        </style>
    </div>
    ```
    
    - The `<div>` elements are containers used to group together HTML elements. Inline CSS styles (e.g., `style="color: red"`) are used to add specific styling to elements.
    - The second `<div>` includes a style block `<style>` that defines specific styles for elements with the `class` and `id` attributes.
    - Within the `<style>` tag, CSS is used to define the color of text for different classes and IDs. For example, the class `class` turns the text red, and the ID `one` changes the text color to blue.
    
    ### **Paragraphs**
    
    - The `<p>` elements are used to define paragraphs of text, with each paragraph being a separate block of content.
    
    ### Class Summary
    
    - **Lists**
    - **Table**
    - **Form**
    - **Radio Buttons**
    - **Checkboxes**
    - **Textarea**
    - **Dropdown Menu**
    - **Iframe**
    - **Video**
    - **Div & CSS Styles**
    
    ### Class Task:
    
    - [x]  Assignment 02

</details>