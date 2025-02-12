# Updating content

If you want to update any of the sections on the homepage, you will be
editing the files in this folder.

# Adding a new section

If you'd like to add a new section to the page, you will do that by creating a
new `.md` file in this folder. You do not need to update any files other than
your new one in order to include it on the page.

# Structure of a page file

All of the page files in this directory MUST have names ending in the `.md`
extension. This indicates that they are
[markdown](https://www.markdownguide.org/basic-syntax/) files. Below is a basic
outline on the structure of one of these files, the section at the beginning
between the three dashes is required for every file. Below the dashes is the
main content of the page.

```
---
title: "title of your section"
weight: number that controls sort order - higher number means lower on the page
header_menu: true
---

Your content goes here. Normal text does not need any special formatting.

# To make a heading, put a # at the beginning of the line

- To make a list, put each element on a new line with a - at the beginning of it
- Just
- Like
- This

> To make a blockquote, put a greater-than sign at the beginning of the line

To _italicise_ text, wrap it with underscores.

To **bold** text, wrap it with double asterisks.

Links have square brackets around the title and parenthesis around the URL [like this](https://google.com)
```

The above markdown would look like this on the website:

---

Your content goes here. Normal text does not need any special formatting.

# To make a heading, put a # at the beginning of the line

- To make a list, put each element on a new line with a - at the beginning of it
- Just
- Like
- This

> To make a blockquote, put a greater-than sign at the beginning of the line

To _italicise_ text, wrap it with underscores.

To **bold** text, wrap it with double asterisks.

Links have square brackets around the title and parenthesis around the URL [like this](https://google.com)
