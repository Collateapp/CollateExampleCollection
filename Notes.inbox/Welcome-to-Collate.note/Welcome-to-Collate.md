---
title: Welcome to Collate!
tags:
  - Collate
  - New Tag
---
# Hi, thanks for trying out Collate!
## Collate is a note taking application that takes your data seriously.
It does this by making sure all your files are stored and organized in simple folders with plain text files holding your note data.  This means that even if you don't have access to Collate, your notes can be looked through, opened and read as easily as looking through documents on your computer.  Your notes are also stored locally, which gives you the option of using any number of services to sync your data.  Collate will never send or receive your data without permission.

### Collection
A `Collection` is simply a folder on your computer where Collate creates notebooks and notes.  Nothing fancy about it!

### Notebooks
A `Notebook` is just a folder inside a `Collection` with a file name that ends in `.notebook`.  This is just an easy way to tell what the folder is when looking at your files in a file browser.

### Notes
Notes are pretty simple things.  They are simply folders with a `.note` ending which is a handy way of remembering what the folder is.  Inside this note folder you'll find a `.md` file which is text that uses [Markdown](http://kirkstrobeck.github.io/whatismarkdown.com/) formatting.  Markdown is a way to format plain text in a way that keeps it readable.

**If you click the preview button in the bar above (the eye icon), you can see how markdown looks when rendered. **

Markdown is great because it gives you the simplicity of keeping notes in plain text with the option of addng some flair.

#### Markdown files
A quick note on how the Markdown files are actually stored. If you open this note up with a text editing program, you'll see a small section on top that looks like this:

```
---
title: Welcome to Collate!
tags: []
---
```

This tiny block is call front matter! It's formatted in a way that both humans and machines can read and is used to store data like tags.  Everything underneath this block is saved as-is and is what you see here in the editor.

#### Attachments
Each note can have a folder named `attachments` in it.  This attachment folder will hold any files you attach to the note.  You can attach anything!  Documents, pictures, media clips, etc.  If you want to remember it, create a note, attach the file and write a short description.

