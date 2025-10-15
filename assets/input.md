# Enhanced Markdown Document

This is an **enhanced** markdown document for Round 2 testing. It contains more content and various elements:

## Features

- **Tabs**: Switch between HTML and Markdown view
- **URL Loading**: Load markdown from external URLs
- **Word Count**: Live word count with formatting

## Code Example

```javascript
function updateWordCount(text) {
    const words = text.split(/\s+/).filter(word => word.length > 0);
    const count = words.length;
    const formatted = new Intl.NumberFormat().format(count);
    document.getElementById('markdown-word-count').textContent = formatted;
}
```

## More Content

This document has additional content to test the word counting functionality. Each word counts toward the total.

1. Numbered list item 1
2. Numbered list item 2
3. Numbered list item 3

> This is a blockquote that adds more words to the document for testing purposes.

### Subsection

**Bold text** and *italic text* are also included to ensure proper rendering and word counting.