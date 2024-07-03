# Learn To use GitHub Wiki:

## Introduction To GitHub Wiki:

A wiki file, in the context of GitHub, refers to a Markdown file that is part of a project's wiki. GitHub Wikis provide a way to document your project in an organized manner using Markdown, a lightweight markup language. A wiki is often used to provide information such as installation guides, usage instructions, API documentation, and more.

## Key Features of a GitHub Wiki:

- **Markdown Syntax**: Wikis use Markdown syntax to format text, making it easy to write and read documentation.

- **Version Control**: Like the main repository, the wiki is version-controlled. You can track changes, revert to previous versions, and collaborate with others.

- **Separate Repository**: Each GitHub wiki is a separate Git repository, allowing for independent management.

- **Ease of Access**: Wikis are easily accessible from the repository's main page under the "Wiki" tab.

## Creating and Managing Wiki Pages:

## 1. Accessing the Wiki:

- **Navigate to Your Repository**: Go to your GitHub repository.
- **Click on the "Wiki" Tab**: This tab is located near the top of the repository page.

## 2. Creating a New Page:

- **Click "New Page"**: You can find this button within the wiki section.

- **Write Your Content**: Use Markdown to format your content. Here’s a brief overview of some common Markdown syntax:

## 3. Basic Markdown Syntax:

Headers: # Header 1, ## Header 2, etc.
Bold: **bold text**
Italic: _italicized text_

### Headers:

# Heading 1

hash(#) is used to create heading 1

## Heading 2

hash(##) is used to create heading 2

### Heading 3

hash(###) is used to create heading 3

#### Heading 4

hash(####) is used to create heading 4

##### Heading 5

hash(#####) is used to create heading 5

###### Heading 6

hash(######) is used to create heading 6

### Emphasis:

_Italic_ or _Italic_: `*italic*` or `_italic_`

**Bold** or **Bold**: `**bold**` or `_bold_`

**_Bold and Italic_** or **_Bold and Italic_**: `***Bold and Italic*** or ___Bold and Italic___`

### Lists:

**Unordered List**:

- Item 1
- Item 2

  - Subitem 1
  - Subitem 2

### Ordered List:

1. Item 1
2. Item 2
   1. Subitem 1
   2. Subitem 2

### Links and Images:

**Link**:
[Link text](http://example.com)

**Image**:
![Alt text](http://example.com/image.jpg)

### Code Blocks:

**nline Code**:
`inline code`

**Block of Code**:

```javascript
console.log("Hello, world!");
```

### Tables:

| Header 1 | Header 2 |
| -------- | -------- |
| Row 1    | Data 1   |
| Row 2    | Data 2   |

## 4. Use VS Code Commands and Shortcuts

### Markdown Preview:

1: Open Preview: Ctrl+Shift+V (Windows/Linux) or Cmd+Shift+V (Mac).
2: Toggle Preview Side-by-Side: Ctrl+K V (Windows/Linux) or Cmd+K V (Mac).

### Markdown All in One Commands:

- **Create Table of Contents**: **`Ctrl+Shift+P`** (Windows/Linux) or **`Cmd+Shift+P`** (Mac), then type **`Markdown All in One: Create Table of Contents`**.
  - **Toggle List**: Automatically format lists.
  - **Toggle Task List**: Convert list items to checkboxes.

**Format Document**:
**Format Document**: **`Shift+Alt+F`** (Windows/Linux) or **`Shift+Option+F`** (Mac).

## 5. Advanced Formatting and Features:

### Task Lists:

- [ ] Task 1
- [x] Task 2 (completed)

### Footnotes:

Here is a footnote reference[^1].

[^1]: Here is the footnote.

### Blockquotes:

> This is a blockquote.

### Horizontal Rule:

---

## 6. Preview and Export:

- **Preview**: Use the Markdown Preview Enhanced extension for a more feature-rich preview.
- **Export**: You can export your Markdown to various formats (e.g., HTML, PDF) using extensions like Markdown PDF.
