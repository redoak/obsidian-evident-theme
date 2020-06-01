# Evident dark theme for Obsidian

The intention of this theme is to make the exact formatting of documents *evident* at a glance when viewed in the editor. To accomplish this, among other things, line height, margins, padding and indention has been homogenized, different text elements have been given distinct colors, and characters used purely in formatting have been given a consistent, muted color.

## Heading levels and horizontal line

# Heading 1 indended for document title
## Heading 2 for top-level sections
### Heading 3 for main sub-sections
#### Heading 4 for further sub-sections
##### Heading 5 for more granular sub-sections
###### Heading 6 for even more granular sub-sections

---

## Links, hashtags, embedding and footnotes

- Hashtag search queries as #hash-tag.
- External link with inline https://url or as [named link](https://url). External media embedded as ![External embed](https://upload.wikimedia.org/wikipedia/commons/1/16/1f642.png).
- Internal link as [[document name]], [[document name|named link]] or [[document name#Heading link]].
- Footnote references are numbered[^1] or given unique identifiers[^second] that are converted to numbers in preview.

[^1]: Footnotes can be placed anywhere.
[^second]: In preview they are always be placed in the right order at the end of the document.

![[Internal embedding]]

## Text formatting

Formatting characters used to make text **bold**, *italic*, ***bold italic***, ~~strike-through~~, ==highlighted== etc. are muted. *<u>HTML tags</u>* and their content is not affected by formatting <em>in the editor</em>. Inline `code`, #hash-tags and [links](https://url) can be ==~~***formatted `and` are #displayed like [this](https://url)***~~==. Backslash can \*escape\* formatting characters.

## Lists

When adding new lines in list items a string of guide symbols are displayed to indicate the indention level, and the text is vertically aligned with the item text at its indention level.

- Level 1
  - Level 2
    Indented line

### Checkboxes

- [x] Checked and unchecked checkboxes are of equal width.
- [ ] As a result the text that follows the checkboxes are vertically aligned.

### Indention distance

1. In preview...
   1. lists are indented less than the default...
      1. to allow for deeper nesting...
         1. without breaking page formatting.

## Tables

&nbsp;|Column A|Column B|Column C
---|---|:---:|---:
**Row 1**|1A|1B|1C
**Row 2**|2A|2B|2C

## Code blocks

```js
function code_block(arg) { if(arg) { $.facebox({div:'#foo'}) } }
```

    Tab indented narrow code block
    without syntax coloring.

## Quotes

> First paragraph in quote.
> 
> Second paragraph.
> 
>> Nested quote.

## Math

$$\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ad-bc$$
