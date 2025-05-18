### Italic and Bold

_itatlic here_ : italic
<br>
**Bold here** : Bold
<br>
**_Bold and Italic here_** : Bold and Italic no matter the order
<br><br>

### Headers

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

<br>

### Links

There are two types of links in Markdown. The first is a standard link, which is a link to an external website. Here's an example:
[Search for it](https://www.google.com)<br>
The other link type is called a reference link. As the name implies, the link is actually a reference to another place in the document. Here's an example of what we mean: <br>
Do you want to [see something fun][a fun place]?<br>
Well, do I have [the website for you][another fun place]!

[a fun place]: www.zombo.com
[another fun place]: www.stumbleupon.com

<br><br>

### Images

If you know how to create links in Markdown, you can create images, too. The syntax is nearly the same.

Images also have two styles, just like links, and both of them render the exact same way. The difference between links and images is that images are prefaced with an exclamation point ( ! ).

The first image style is called an inline image link. To create an inline image link, enter an exclamation point ( ! ), wrap the alt text in brackets ( [ ] ), and then wrap the link in parentheses ( ( ) ). (Alt text is a phrase or sentence that describes the image for the visually impaired.)
![Alt text](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)
<br>
The second image style is called a reference image link. To create a reference image link, enter an exclamation point ( ! ), wrap the alt text in brackets ( [ ] ), and then wrap the reference link in brackets ( [ ] ). The reference link is defined elsewhere in the document.

![Black cat][Black]

![Orange cat][Orange]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
[Orange]: https://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

<br>
<br>

### Blockquotes

Blockquotes are used to quote text from another source. To create a blockquote, enter a greater than sign ( > ) before the text. You can also nest blockquotes by adding additional greater than signs ( >> ) before the text.

> This is a blockquote. It can be used to quote text from another source.

<br>

### Lists

There are two types of lists in Markdown: ordered and unordered. <br>

-   An ordered list is a numbered list, while an unordered list is a bulleted list.

    -   Milk
    -   Eggs
    -   Salmon
    -   Butter

-   An unordered list is a bulleted list, while an ordered list is a numbered list.

    1. Milk
    2. Eggs
    3. Salmon
    4. Butter

-   The third type of list is called a definition list. A definition list is a list of terms and their definitions. To create a definition list, enter the term, followed by a colon ( : ), and then the definition.
    -   Milk: A liquid produced by mammals to feed their young.
    -   Eggs: A reproductive structure produced by

<br><br>

### Paragraphs

Paragraphs are created by entering a blank line between two lines of text. You can also create a new paragraph by entering two spaces at the end of a line and then pressing Enter.

-   hard break (\<br\>):

    This is a paragraph. It can be used to create a new paragraph by entering a blank line between two lines of text.

-   soft break  
    This is a paragraph. It can be used to create a new paragraph by entering two spaces at the end of a line and then pressing Enter.
