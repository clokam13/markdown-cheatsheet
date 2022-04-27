# Using Markdown in Git Repositories | Tutorial and Samples 

This repository contains snippets of markdown that will help guide you for creating beautiful, clear and concise README files for your projects and repositories. 

## What is a README.md file?

A README file is usually the first content that any developer will read when opening up a repository. So, what is it?

A **README** is  markdown file that will allow users to understands what a project is and usually defines how you can setup the repository locally for further development. Services such as Github and Gitlab showcase the README file right after you open the repository. 

![Example README in Github](images/readme.png)

## What is markdown?

Markdown is a light-weight markup language that you can use to add formatting for plain-text files. 

## Markdown Cheatsheet for README files 

### Headings 

You can use the # symbol to denote headings. 

# Heading 1
## Heading 2 
### Heading 3

```
# Heading 1
## Heading 2
### Heading 3
```

### Formatting 

- Bold(**) - **Bold Text**
- Italics(*) - *Italics Text*
- Bold Italics(***) - ***Bold and Italics Text***

### Quotes 

You can add text into quotes by using the > symbol. 

> Do or Do Not. There is no try. - Yoda

### Code Blocks

You can add code snippets within sentences using (backticks - \`). Here is an example with `git init`. 

You can add code blocks as well and specify the language to get code syntax highlighting. 

**\```javascript** will be use to start the block and end with **\```**. 


```javascript
console.log("This is a code snippet!");
```

### Hyperlinks 

You can add Hyperlinks to external websites (or) to files within your Git Repository. Relative links can be added using the file path within the repository. 

Link to [**Chanakya's Youtube Channel**](https://www.youtube.com/channel/UCfBG6pX9AvKfTBAX0EHLYzQ). 

Format will be **\[Text for Hyperlink](Link to resource)**

### Images 

You can add images like the above using the \![Alt Text for Image](Image Link). 

Here is an image of **Happy the Golden Retriever**

![Happy the Golden Retriever](images/happy.jpeg)

### Regular List

You can create lists by just adding the - symbol in front of the list item. 

- Item #1
- Item #2 
- Item #3

### Numbered List 

You can create numbered lists by just adding the number ahead of the list item. 

1. Item 1
2. Item 2
3. Item 3

### Emojis 

Markdown in Github supports adding Emojis like :smiley: as well!

Just use the smiley name in between colons(:) like \:smiley:

You can find a Emoji cheatsheet [**here**](emoji.md).



