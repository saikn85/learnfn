# Text Fundamentals

- Most structured text consists of **headings** and **paragraphs**, whether you are reading a story, a newspaper, a college textbook, a magazine, etc.
- Structured content makes the reading experience easier and more enjoyable.

#### Headings and Paragraphs

There are six heading elements:
- ```<h1>``` - represents the main heading,
- ```<h2>``` - represents subheadings,
- ```<h3>``` - sub-subheadings,
- ```<h4>``` - so on,
- ```<h5>``` - so on, and
- ```<h6>```.

- It's really up to you what the elements involved represent, as long as the hierarchy makes sense. You just need to bear in mind a few best practices as you create such structures:
    - Preferably, you should use a single ```<h1>``` per page—this is the top level heading, and all others sit below this in the hierarchy.
    - Make sure you use the headings in the correct order in the hierarchy. Don't use ```<h3>``` elements to represent subheadings, followed by ```<h2>``` elements to represent sub-subheadings—that doesn't make sense and will lead to weird results.
    - Of the six heading levels available, you should aim to use no more than three per page, unless you feel it is necessary.
    - Documents with many levels (for example, a deep heading hierarchy) become unwieldy and difficult to navigate.
- ***Do we need to structure our documents?*** **Yes**, it's a must, else why make a document in first place! 
- And we write our content inside the ```<p>``` paragraph element.
- ***Do we need semantics?*** **Yes**, we do, so as to make sure we are using the correct elements, giving our content the correct meaning, function, or appearance.

#### Lists

Lists are everywhere in life—from your shopping list to the list of directions you subconsciously follow to get to your house every day, to the lists of instructions you are following in these tutorials! Lists are everywhere on the web, too, and we've got three different types to worry about.

- **Unordered**
    - Unordered lists are used to mark up lists of items for which the order of the items doesn't matter. Let's take a shopping list as an example: