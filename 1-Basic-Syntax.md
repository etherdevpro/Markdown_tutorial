## 1. Headings
To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (\<h3>), use three number signs.

Markdown

    # Heading1   
    ## Heading2
    ### Heading3 
    #### Heading4   
    ##### Heading5   
    
Result
# Heading1
## Heading2
### Heading3
#### Heading4
##### Heading5

## 2. Emphasis
### 2.1. Bold
To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

Markdown

    This is **Bold** Text.
    This is __Bold__ Text.
Result

This is **Bold** Text.
This is __Bold__ Text.

### 2.2. Italic
To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

Markdown

    This is *Italic* text.
    This is _Italic_ text.
Result

This is *Italic* text.
This is _Italic_ text.

### 2.3. Bold and Italic
To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase.

Markdown

    ***Bold and Italic*** Text
    ___Bold and Italic___ Text
    __*Bold and Italic*__ Text
    **_Bold and Italic_** Text
Result

***Bold and Italic*** Text
___Bold and Italic___ Text
__*Bold and Italic*__ Text
**_Bold and Italic_** Text

## 3. Lists
### 3.1. Ordered List
To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

Markdown

    1. First item
    2. Second item
    3. Third item

    1. First item
    1. Second item
    1. Third item
   
    1. First item
    8.  Second item
    3.  Third item 

Result
1. First item
2. Second item
3. Third item

1. First item
1. Second item
1. Third item

2. First item
3.  Second item
4.  Third item    
### 3.2. Nesting List
To nest line items in an ordered list, indent the items four spaces or one tab.

Markdown

    1. First item
    2. Second item
    3. Third item
       1. Nested item
       2. Nested item
    4. Fourth item
Result
 1. First item
 2. Second item
 3. Third item
    1. Nested item
    2. Nested item
 4. Fourth item
   
### 3.3. Unordered List
To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items.

Markdown

    - First item
    - Second item
    - Third item

    * First item
    * Second item
    * Third item

    + First item
    * Second item
    - Third item
    + Fourth item

Result
- First item
- Second item
- Third item
- Fourth item

* First item
* Second item
* Third item
* Fourth item

+ First item
* Second item
- Third item
+ Fourth item
  
### 3.4. Nesting List Items
To nest line items in an unordered list, indent the items four spaces or one tab.

Markdown

    - First item
    - Second item
    - Third item
        - Indented item
        - Indented item
    - Fourth item

Result
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

## 4. Links
To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

Markdown

    Use [Duck Duck Go](https://duckduckgo.com)
    // Adding Title
    Use [Duck Duck Go](https://duckduckgo.com "My search engine!").

Result

Use [Duck Duck Go](https://duckduckgo.com)
Use [Duck Duck Go](https://duckduckgo.com "My search engine!").

## 5. URLs and Email Addresses
To quickly turn a URL or email address into a link, enclose it in angle brackets.

Markdown

    <https://www.google.com>
    <info@example.com>
Result

<https://www.google.com>
<info@example.com>

## 6. Images
Markdown

    "![Alt Text](imageUrl)"  

Result

![Alt Text](imageUrl)

## 7. Code Blocks
Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

Markdown
    
    [4 spaces or Tab]This is code block.
Result

    This is code block

## 8. Code
To denote a word or phrase as code, enclose it in tick marks (`).

Markdown

    At the command prompt, type `nano`
Result

At the command prompt, type `nano`

## 9. Blockquotes
To create a blockquote, add a > in front of a paragraph.

Markdown

    > This is Blockquotes 
Result
> This is Blockquotes
### 9.1. Blockquotes with Multiple Paragraphs
Blockquotes can contain multiple paragraphs. Add a > on the blank lines between the paragraphs.

Markdown

    > This is first line.
    >
    > This is second line.

Result
> This is first line.
>
> This is second line.
### 9.2. Nested Blockquotes
Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.

Markdown

    > This is first paragraph.
    >
    >> This is the nested paragraph.
Result
> This is first paragraph.
>
>> This is the nested paragraph.

## 10. Horizontal Rules
To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

Markdown

    ***
    ---
    ___

Result

***
---
___