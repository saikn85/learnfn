# Getting started with HTML

## Learning Goals
- How HTML elements are structured?
- how a typical HTML page is structured?

### HTML
- Hypertext Markup Language is not a programming language.
- It is a markup language that tells web browsers how to structure the web pages you visit.
- It can be as complicated or as simple as the web developer wants it to be.
- HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of content to make it appear or act in a certain way.

#### HTML Elements

[First HTML Document](FirstHTML.html)

The anatomy of our element is:
- **The opening tag**: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
- **The content**: This is the content of the element. In this example, it is the paragraph te**xt.
- **The closing tag**: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.
The element is the opening tag, followed by content, followed by the closing tag.


##### Nesting of Elements

[Nesting of Elements](MyGrumpyCat.html)

- Elements can be placed within other elements. This is called nesting.
- If we wanted to state that our cat is very grumpy, we could wrap the word very in a ```<strong>``` element, which means that the word is to have strong(er) text formatting:
- There is a right and wrong way to do nesting.
- **The tags have to open and close in a way that they are inside or outside one another.**
- It'll become impossible for the browser has to guess at your intent and this kind of guessing can result in unexpected results.

##### Block vs Inline Elements

[Block vs Inline](BlockVsInline.html)

There are two important categories of elements to know in HTML:
- block-level elements, and
- inline elements.

- **Block-level** elements form a visible block on a page.
    - A block-level element appears on a new line following the content that precedes it.
    - Any content that follows a block-level element also appears on a new line.
    - Block-level elements are usually **structural elements** on the page.
    - For example, a block-level element might represent headings, paragraphs, lists, navigation menus, or footers.
    - A block-level element **wouldn't be nested inside an inline element**, but it might be nested inside another block-level element.
- **Inline** elements are contained within block-level elements, and surround only small parts of the document’s content (not entire paragraphs or groupings of content).
    - An inline element will not cause a new line to appear in the document.
    - It is typically used with text, for example an ```<a>``` element creates a hyperlink, and elements such as ```<em>```or ```<strong>``` create emphasis.


##### Empty Elements

[Empty Elements](EmptyElements.html)

- Not all elements follow the pattern of an opening tag, content, and a closing tag.
- Some elements consist of a single tag, which is typically used to insert/embed something in the document.     
    - For example, the ```<img>```element embeds an image file onto a page.

##### HTML Element Attributes

[HTML Element Attributes](ElementAttributes.html)

- Attributes contain extra information about the element that won't appear in the content.
- An attribute should have:
    - A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
    - The attribute name, followed by an equal sign.
    - An attribute value, wrapped with opening and closing quote marks.
- **Boolean Attribute**:
    - These are those that are written without values.
    - Boolean attributes **can only have one value**, which is generally the **same as the attribute name**.
    - For example, consider the **disabled** attribute, which you can assign to form input elements. You use this to disable the form input elements so the user can't make entries.
- **Omitting Quotes** around attribute values is allowed under certain circumstances, however, can break your markup. Thus it is better to always quote your attributes.
    - Single or Double quotes are a choice preference. Ensure that they are not mixed as it can break the markup.
    - Use [HTML Entities](https://www.w3schools.com/html/html_entities.asp) when trying to insert special characters into attribute's values.

##### Anatomy of an HTML Document

[First HTML Document](FirstHTML.html)

- ```<!DOCTYPE html>```:
    - When HTML was young (1991-1992), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML.
    - Doctypes used to look something like this:
    ```
        <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
        "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
    ```
    - More recently, the doctype is a historical artifact that needs to be included for everything else to work right.
    - ```<!DOCTYPE html>``` is the shortest string of characters that counts as a valid doctype.
- ```<html></html>```: This element wraps all the content on the page. It is sometimes known as the **root** element.
- ```<head></head>```:
    - This element acts as a container for everything you want to include on the HTML page, that isn't the content the page will show to viewers.
    - This includes keywords and a page description that would appear in search results, CSS to style content, character set declarations, and more. 
- ```<meta charset="utf-8">```:
    - This element specifies the character set for your document to UTF-8, which includes most characters from the vast majority of human written languages. With this setting, the page can now handle any textual content it might contain, but is completely **Optional**.
- ```<title></title>```:
    - This sets the title of the page, which is the title that appears in the browser tab the page is loaded in. The page title is also used to describe the page when it is bookmarked.
- ```<body></body>```: This contains all the content that displays on the page, including text, images, videos, games, playable audio tracks, or whatever else.