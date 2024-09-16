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