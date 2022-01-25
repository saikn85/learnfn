# What’s in the head? Metadata in HTML

[Metadata](Metadata.html)

## Head

- The **head** of an HTML document is the part that is not displayed in the web browser when the page is loaded.
- It contains information such as:
    - the page ```<title>```,
    - links to CSS (if you choose to style your HTML content with CSS),
    - links to custom favicons, and
    - other metadata (such as the author, and important keywords that describe the document.)

### Major Elements that you'll want to include in the head

#### Adding a title

- The ```<title>``` element is metadata that represents the title of the overall HTML document  and not the document's content.
- Also, it's not to be confused with **page title**, they are marked using the **```<h1>``` through ```<h6>```** tags.
- The ```<title>``` element contents are also used in other ways:
    - Bookmarking the page
    - Optimize search results

#### Metadata: the ```<meta>``` element

- Metadata is data that describes data.
- It is used in the following ways
    - Specifying your document's character encoding, for example ```<meta charset="utf-8">```
    - Adding an author and description:
        - **```name```**: specifies the type of meta element it is; what type of information it contains.
        - **```content```**: specifies the actual meta content.
- [Learn more using this link](https://www.w3schools.com/tags/tag_meta.asp)

#### Linking Icons, Style Sheets, and JavaScript files
- The **```<link>```** element should always go inside the head of your document.
    - This takes two attributes:
    - **```rel="stylesheet"```**, which indicates that it is the document's stylesheet, and
    - **```href```**, which contains the path to the stylesheet/favicon file:
        - The favicon using the code snippet ```<link rel="icon" href="favicon.ico" type="image/x-icon">```
        - Style sheets using ```<link rel="stylesheet" href="my-css-file.css">```
- The **```<script>```** element should also go into the head, and should include a **```src```** attribute containing the path to the JavaScript you want to load, and **```defer```**, which basically instructs the browser to load the JavaScript after the page has finished parsing the HTML.