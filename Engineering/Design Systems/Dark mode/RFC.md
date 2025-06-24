# H1

Body text.

## H2

Body text.

### H3

Body text.

#### H4

Body text.

##### H5

Body text.

###### H6

Body text.

## Text Styling

**Bold**  
*Italic*  
~~Strikethrough~~  
<ins>Underline (HTML)</ins>  
<sub>Subscript</sub>  
<sup>Superscript</sup>

## Lists

- Unordered item
  - Nested unordered item
    - Deep nested unordered item

1. Ordered item
2. Another ordered item
   1. Nested ordered item
   2. Another nested ordered item
      1. Deep nested ordered item
      2. Another deep nested ordered item

- [ ] Task list item
  - Nested unordered item
    1. Deep nested ordered item
  - [ ] Nested task list item

## Links

[Inline link](https://github.com)  
[Section link to H6 heading](#h6)  
[Reference-style link][ref]

[ref]: https://github.com

## Code

Example of inline `code`

### Code block examples

```bash
# Code block with bash
brew install git
```

```js
// JavaScript code block
function hi() {
  console.log("Hello!");
}
```

```diff
- Deletion
+ Addition
! Warning
@@ Diff hunk header @@
# Comment
```

## Blockquotes

> Block quotes are written like so.
>
> > They can be nested and span multiple paragraphs.
> > If you like.

## Tables

| Feature   | Supported |
| --------- | --------- |
| Lists     | ✅         |
| Tables    | ✅         |
| Task list | ✅         |

## Emoji

:shipit:

## Mentions and References

Mention: @octocat
Issue referenced by number: #1
Pull request referenced by URL: https://github.com/wesbos/dad-jokes/pull/224

- When an issue or PR reference is featured within a list item the full title gets rendered: https://github.com/left-pad/left-pad/issues/30

## Footnotes

Here is a simple footnote. Zoom to the bottom to see the reference [^1].

A footnote can also have multiple lines [^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

## Alerts 

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Details

<details>
  <summary>Click to expand!</summary>

This is hidden content revealed on click.

</details>

## Images

![A lovely kitten](http://bit.ly/1RXe87U)

## Color modes

The background color is `#ffffff` for light mode and `#000000` for dark mode.

## Horizontal Rule

---

## Line breaks

In a markdown file, this example 
won't span two lines (in a comment it will)

In a markdown file, this example\
Will span two lines

## Escaping

\*Literal asterisks\*  
\# Not a heading  
\> Not a blockquote  

## HTML Elements

<p>This is a raw HTML paragraph in Markdown.</p>
<kbd>⌘+C</kbd> is the copy shortcut on macOS.

<!-- This comment won't render -->

</br>
</br>
</br>
