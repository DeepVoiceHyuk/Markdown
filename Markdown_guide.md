![A Markdown Logo Image](./Markdown_logo_256x158.png "Markdown logo")



# What's Markdown?

A lightweight markup language that you can use to add formatting elements to plaintext documents.

When you create a Markdown-formatted file, you add Markdown syntax to the text to indicate which words and phrases should look different.

# Why Use Markdown?

- Markdown can be used for everything. People use it to create websites, documents, notes, books, presentations, email messages, and technical documentation.
  * Websites
    > Markdown was designed for the web, so it should come as no surprise that there are plenty of applications specifically designed for creating website content.
  * Documents
    > Markdown doesn’t have all the bells and whistles of word processors like Microsoft Word, but it’s good enough for creating basic documents like assignments and letters. You can use a Markdown document authoring application to create and export Markdown-formatted documents to PDF or HTML file format. The PDF part is key, because once you have a PDF document, you can do anything with it — print it, email it, or upload it to a website.
    > Here are some Markdown document authoring applications I recommend:
      * Mac: MacDown, iA Writer, or Marked
      * iOS / Android: iA Writer
      * Windows: ghostwriter or Markdown Monster
      * Linux: ReText or ghostwriter
      * Web: Dillinger or StackEdit

  * Notes
    > In nearly every way, Markdown is the ideal syntax for taking notes. Sadly, Evernote and OneNote, two of the most popular note applications, don’t currently support Markdown. The good news is that several other note applications do support Markdown:
    * Simplenote, Notable, Bear, Boostnote, etc.
  * Books
    > Looking to self-publish a novel? Try **Leanpub**, a service that takes your Markdown-formatted files and turns them into an electronic book. Leanpub outputs your book in PDF, EPUB, and MOBI file format. 
  * Presentations
    > Believe it or not, you can generate presentations from Markdown-formatted files. Creating presentations in Markdown takes a little getting used to, but once you get the hang of it, it’s a lot faster and easier than using an application like PowerPoint or Keynote. 
	* [Remark](https://remarkjs.com/) [(GitHub project)](https://github.com/gnab/remark) is a popular browser-based Markdown slideshow tool, as is [Cleaver](https://jdan.github.io/cleaver/) [(GitHub project)](https://github.com/jdan/cleaver). 
	* If you use a Mac and would prefer to use an application, check out [Deckset](https://www.decksetapp.com/) or [Marked](https://marked2app.com/).
  * Email
    > [Markdown Here](https://www.markdownguide.org/tools/markdown-here/) is a free and open-source browser extension that converts Markdown-formatted text into HTML that’s ready to send.
  * Documentation
   > Markdown is a natural fit for technical documentation. Companies like GitHub are increasingly switching to Markdown for their documentation — check out their blog post about how they migrated their Markdown-formatted documentation to [Jekyll](https://www.markdownguide.org/tools/jekyll/). If you write documentation for a product or service, take a look at these handy tools:
	*  [Read the Docs](https://readthedocs.org/) can generate a documentation website from your open source Markdown files. Just connect your GitHub repository to their service and push — Read the Docs does the rest. They also have a service for commercial entities.
	*  [MkDocs](https://www.mkdocs.org/) is a fast and simple static site generator that’s geared towards building project documentation. Documentation source files are written in Markdown and configured with a single YAML configuration file. MkDocs has several built in themes, including a port of the Read the Docs documentation theme for use with MkDocs. One of the newest themes is MkDocs Material.
	*  [Docusaurus](https://www.markdownguide.org/tools/docusaurus/) is a static site generator designed exclusively for creating documentation websites. It supports translations, search, and versioning.
	*  [VuePress](https://vuepress.vuejs.org/) is a static site generator powered by Vue and optimized for writing technical documentation.
	*  [Jekyll](https://www.markdownguide.org/tools/jekyll/) was mentioned earlier in the section on websites, but it’s also a good option for generating a documentation website from Markdown files. If you go this route, be sure to check out the Jekyll documentation theme.

  
- Markdown is portable. Files containing Markdown-formatted text can be opened using virtually any application. (MS word와 같은 특정 app의 고유 파일 포맷이 아님.)

- Markdown is platform independent. You can create Markdown-formatted text on any device running any operating system.

- Markdown is future proof. Even if the application you’re using stops working at some point in the future, you’ll still be able to read your Markdown-formatted text using a text editing application.

- Markdown is everywhere. Websites like Reddit and GitHub support Markdown, and lots of desktop and web-based applications support it.

# How to Use Markdown?

- **notepad++** 에 마크다운 설치
   * http://www.guidingtech.com/31357/notepad-plus-plugins/

- **StackEdit**를 이용해서 웹으로 마크 다운 형식으로 저장한 텍스트 파일을 html로 변환해서 볼 수 있음
  *  https://stackedit.io

# How Does StackEdit Work?

The short answer is that you need a **Markdown application** capable of processing the Markdown file. There are lots of applications available — everything from simple scripts to desktop applications that look like Microsoft Word. Despite their visual differences, all of the applications do the same thing. Like Dillinger, they all convert **Markdown-formatted text** to **HTML** so it can be displayed in web browsers.

To summarize, this is a four-part process:

1. Create a Markdown file using a text editor or a dedicated Markdown application. The file should have an .md or .markdown extension.
2. Open the Markdown file in a Markdown application.
3. Use the Markdown application to convert the Markdown file to an HTML document.
4. View the HTML file in a web browser or use the Markdown application to convert it to another file format, like PDF.


# Kicking The Tires
The best way to get started with Markdown is to use it.


*Italic text with asterisk*




markup n. 문서의 활자, 조판 지정 표시
kick the tires - test the quality of something; see if something is suitable for you






![A Helpful Tips Image](https://lh3.googleusercontent.com/UqJaOqKmyGZ2z0jNF8v5Yb1pXozG3jlkDjQeVgV77iA3i5oTQ2MENzPH6fGn9Z5rOQNAwvi6en0u "Helpful Tips")


Markdown Formatting
--

# Heading

# This is an H1 tag  
## This is an H2 tag  
### This is an H3 tag  
#### This is an H4 tag  
##### This is an H5 tag  
###### This is an H6 tag

## Heading - Alternate Syntax

Heading level 1
===============

Heading level 2
---------------

# Paragraphs

To create paragraphs, use **a blank line** to separate one or more lines of text. **You should not indent paragraphs with spaces or tabs.**

  > I really like using Markdown.
  >
  > I think I'll use it to format all of my documents from now on. 

# Line Breaks

To create a line break (<br>), end a line with **two or more spaces**, and then type **return**.

  > This is the first line.  
  > And this is the second line.

# Emphasis 

*Italic text with asterisk*
_Italic text with underscore_
**Bold text with double asterisk**
__Italic text with double underscore__
***Bold Italic Text***
~~deleted words~~

# Lists

## Unordered

* Item 1
* Item 2
*  Item 3
*  Item 4 
    *  Item 4a 
    *  Item 4b

## Ordered

1. Item 1
1. Item 2
1. Item 3 
	1. Item 3a 
	1. Item 3b

---------------------

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item 

## Adding Elements in Lists

To add another element in a list while preserving the continuity of the list, indent the element **four spaces* or **one tab**, as shown in the following examples.

### Paragraphs

> *   This is the first list item.
> *   Here's the second list item.
>
>     I need to add another paragraph below the second list item.
>
> *   And here's the third list item.
>     > A blockquote would look great below the second list item.

## Images
![GitHub Logo](/images/logo.png “Optional Title”)

## Links

http://github.com-automatic!

[GitHub](http://github.com)

### Adding Titles in Links

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.

    > My favorite search engine is [Duck Duck Go](https://duckduckgo.com **"The best search engine for privacy"**).

# URLs and Email Addresses

To quickly turn a URL or email address into a link, enclose it in **angle brackets**.

  > <https://www.markdownguide.org>
  > <fake@example.com>

# Disabling Automatic URL Linking

If you don’t want a URL to be automatically linked, you can remove the link by denoting the URL as code with tick marks.

  > `http://www.example.com`

## Formatting Links

To emphasize links, add asterisks before and after the brackets and parentheses.

  > I love supporting the **[EFF](https://eff.org)**.
  > This is the *[Markdown Guide](https://www.markdownguide.org)*.

## Blockquotes

As Mustafa Kemal Atatürk said:

>One day my mortal body will turn to dust, but the Turkish Republic will stand forever.

## Blockquotes with Multiple Paragraphs

Add a **>** on the **blank lines** between the paragraphs.

  > > Dorothy followed her through many of the beautiful rooms in her castle.
  >
  > > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
  
## Nested Blockquotes

Add a **>>** in front of the paragraph you want to nest.

  > > Dorothy followed her through many of the beautiful rooms in her castle.
  >
  > >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Blockquotes with Other Elements

Blockquotes can contain other Markdown formatted elements. *Not all elements can be used — you’ll need to experiment to see which ones work.*

  > #### The quarterly results look great!
  >
  > - Revenue was off the chart.
  > - Profits were higher than ever.
  >
  >  *Everything* is going according to **plan**.

## Code Syntax

Code blocks are normally indented **four spaces** or **one tab**. When they’re in a list, indent them **eight spaces** or **two tabs**.

1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.

### Fenced Code Blocks

The basic Markdown syntax allows you to create code blocks by indenting lines by four spaces or one tab. If you find that inconvenient, try using **fenced code blocks**. Depending on your Markdown processor or editor, you’ll use **three tick marks (```)** or **three tildes (~~~)** on the lines **before** and **after** the code block. The best part? You don’t have to indent any lines!

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

#### Syntax Highlighting

Many Markdown processors support syntax highlighting for fenced code blocks. This feature allows you to add color highlighting for whatever language your code was written in. To add syntax highlighting, **specify a language** next to the tick marks before the fenced code block.

Use your language name with **```**.
```javascript
function alertMarkdown(){
alert(‘Hello Markdown’);
}
```

## Task Lists

- [x] update login UI
- [ ] dashboard UI design.

## Tables

To add a table, use **three or more hyphens (---)** to create each column’s header, and use **pipes (|)** to separate each column. You can optionally add pipes on either end of the table.

First Header|Second Header
---------------|-------------
Content from cell 1 | Content from cell 2
Content in the first column|Content in the second column

### Alignment

You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

## Definition Lists

Jekyll
: is a blog-aware, static site generator in Ruby.

## Footnotes

This articles has many references.[^1]
[^1]: Linus Torvals.

# Escaping Tick Marks (` `)

If the word or phrase you want to denote as code includes one or more tick marks, you can escape it by enclosing the word or phrase in double tick marks (``).

  > ``Use `code` in your Markdown file.``

## Horizontal Rules

***
* * * * *
---
- - - 

# Escaping Characters

To display a literal character that would otherwise be used to format text in a Markdown document, add a **backslash (\)** in front of the character.

  > \* Without the backslash, this would be a bullet in an unordered list.

## Characters You Can Escape

Character |Name
----------|-----------
\\        | backslash
\`        | tick mark
\*        | asterisk
\_        | underscore
\{}       | curly braces
\[]       | brackets
\()       | parenthesis
\#        | pound sign
\+        | plus sign
\-        | minus sign (hyphen)
\.        | dot
\!        | exclamation mark
\|        | pipe

# Markdown with HTML&CSS

## Images

If you use markdown image load format **![Alt Text](**imageURL or Path**)**, this image will not center on the page. This will always show on the left side. You can use html change image align.

You can use **\<img>** to load image from url or path. Also set **width, height and align**.

### left alignment

<img align=”left” width=”100" height=”100" src=”http://www.fetchlogos.com/wp-content/uploads/2015/12/Superman-Logo.jpg">

### center alignment

<p align=”center”>

<img width=”200" height=”200" src=”http://www.fetchlogos.com/wp-content/uploads/2015/12/Superman-Logo.jpg">

</p>

### Collapse Sections

Collapsing large sections of text can make your plain text much easier to read.

<details>
<summary>”Click Here to expand”</summary>
this is hidden text block.
</details>

### Using CSS

Also you can use CSS stylesheet in your markdown plain text. You can do that two way. One of these is a write **`<style>`** in your markdown file and then use them in html tags.

<style>
.pclass{
background-color: yellow;
color: blue;
}
</style>
<p class=”pclass”>
Hello Markdown….
</p>
<button >
Markdown Button
</button>


# Reference

https://medium.com/echohub/write-simple-and-effective-markdown-tips-8e01fdddd70

https://www.markdownguide.org/getting-started/

https://www.markdownguide.org/basic-syntax/

https://www.markdownguide.org/extended-syntax/
































