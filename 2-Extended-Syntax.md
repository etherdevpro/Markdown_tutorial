## Table
To add a table, use three or more hyphens (---) to create each column’s header, and use pipes (|) to separate each column. For compatibility, you should also add a pipe on either end of the row.

Markdown

    | Syntax      | Description |
    | ----------- | ----------- |
    | Header      | Title       |
    | Paragraph   | Text        |

Result

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Alignment
You can align text in the columns to the left, right, or center by adding a colon (\:) to the left, right, or on both side of the hyphens within the header row.

Markdown

    | Syntax      | Description | Test Text     |
    | :---        |    :----:   |          ---: |
    | Header      | Title       | Here's this   |
    | Paragraph   | Text        | And more      |

Result

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

## Fenced Code Blocks
The basic Markdown syntax allows you to create code blocks by indenting lines by four spaces or one tab. If you find that inconvenient, try using fenced code blocks. Depending on your Markdown processor or editor, you’ll use three backticks (```) or three tildes (~~~) on the lines before and after the code block. The best part? You don’t have to indent any lines!

Markdown

    ```
    {
    "firstName": "John",
    "lastName": "Smith",
    "age": 25
    }
    ```
Result

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Footnotes
Footnotes allow you to add notes and references without cluttering the body of the document. When you create a footnote, a superscript number with a link appears where you added the footnote reference. Readers can click the link to jump to the content of the footnote at the bottom of the page.

To create a footnote reference, add a caret and an identifier inside brackets ([^1]). Identifiers can be numbers or words, but they can’t contain spaces or tabs. Identifiers only correlate the footnote reference with the footnote itself — in the output, footnotes are numbered sequentially.

Add the footnote using another caret and number inside brackets with a colon and text ([^1]: My footnote.). You don’t have to put footnotes at the end of the document. You can put them anywhere except inside other elements like lists, block quotes, and tables.

Markdown

    Here's a simple footnote,[^1] and here's a longer one.[^bignote]

    [^1]: This is the first footnote.

    [^bignote]: Here's one with multiple paragraphs and code.

        Indent paragraphs to include them in the footnote.

        `{ my code }`

        Add as many paragraphs as you like.

Result

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.


## Heading IDs
You can link to headings with custom IDs in the file by creating a standard link with a number sign (#) followed by the custom heading ID. These are commonly referred to as anchor links.

Markdown

    [Heading IDs](#heading-ids)

Result

[Heading IDs](#heading-ids)

## Definition Lists
Some Markdown processors allow you to create definition lists of terms and their corresponding definitions. To create a definition list, type the term on the first line. On the next line, type a colon followed by a space and the definition.

Markdown

    First Term
    : This is the definition of the first term.

    Second Term
    : This is one definition of the second term.
    : This is another definition of the second term.

Result

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

## Strikethrough
You can strikethrough words by putting a horizontal line through the center of them. The result looks like this. This feature allows you to indicate that certain words are a mistake not meant for inclusion in the document. To strikethrough words, use two tilde symbols (~~) before and after the words.

Markdown

    ~~The world is flat.~~ We now know that the world is round.

Result

~~The world is flat.~~ We now know that the world is round.

## Task Lists
Task lists (also referred to as checklists and todo lists) allow you to create a list of items with checkboxes. In Markdown applications that support task lists, checkboxes will be displayed next to the content. To create a task list, add dashes (-) and brackets with a space ([ ]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).

Markdown

    - [x] Write the press release
    - [ ] Update the website
    - [ ] Contact the media

Result

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## Emoji
There are two ways to add emoji to Markdown files: copy and paste the emoji into your Markdown-formatted text, or type emoji shortcodes.

- Copy and Paste
  In most cases, you can simply copy an emoji from a source like [Emojipedia](https://emojipedia.org/) and paste it into your document. Many Markdown applications will automatically display the emoji in the Markdown-formatted text. The HTML and PDF files you export from your Markdown application should display the emoji.

- Type emoji shortcodes
  
    Markdown

        Gone camping! :tent: Be back soon.

        That is so funny! :joy:

  Result

    Gone camping! :tent: Be back soon.

    That is so funny! :joy:

## Highlight
This isn’t common, but some Markdown processors allow you to highlight text. The result looks like this. To highlight words, use two equal signs (==) before and after the words.

Markdown

    I need to highlight these ==very important words==.

Result

I need to highlight these ==very important words==.

## Subscript
This isn’t common, but some Markdown processors allow you to use subscript to position one or more characters slightly below the normal line of type. To create a subscript, use one tilde symbol (~) before and after the characters.

Markdown

    H~2~O

Result

H~2~O

## Superscript
This isn’t common, but some Markdown processors allow you to use superscript to position one or more characters slightly above the normal line of type. To create a superscript, use one caret symbol (^) before and after the characters.

Markdown

    X^2^

Result

X^2^

## Automatic URL Linking
Many Markdown processors automatically turn URLs into links. That means if you type http://www.example.com, your Markdown processor will automatically turn it into a link even though you haven’t used brackets.

Markdown

    http://www.example.com

Result

http://www.example.com