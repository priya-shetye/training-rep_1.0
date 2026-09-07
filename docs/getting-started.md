
- [Topic title](#topic-title)
  - [Getting Started](#getting-started)
  - [Adding hyperlink](#adding-hyperlink)
  - [Adding code block](#adding-code-block)
  - [Basic table](#basic-table)
  - [Adding ordered lists](#adding-ordered-lists)
  - [Adding links to files](#adding-links-to-files)
      - [Heading 4](#heading-4)
    - [Add Image](#add-image)
    - [Working with images](#working-with-images)
  - [Adding annotations](#adding-annotations)
  - [Installation](#installation)
  - [Task list](#task-list)
  - [Footnote](#footnote)
  - [Collapsable content](#collapsable-content)
  - [Troubleshooting](#troubleshooting)


# Topic title (Make this heading 2)

## Getting Started
Welcome to our product documentation.

## Adding hyperlink
Make sure you have an active account. Add a hyperlink - For more information, see the guidelines at [BMC Website](https://www.bmc.com/).

## Adding code block
Continue with the installation guide.
We will also add a code block
```javascript
function greet(name) 
{
  return `Hello, ${name}.`;
}
console.log(greet("world"));
```

**Another code block**
```
This is for a code block 
```
## Basic table
A list of players
| Player | Sport | Country |
| --- | --- | --- |
| Player | Sport | Country |
| Player | Sport | Country |
| Player | Sport | Country |
| Player | Sport | Country |    

## Adding ordered lists
Includes a ordered list.
1. Step 1   
2. Step 2
3. Step 3
4. Step 4   
    Step 4 a    
    Step 4 b
5. Step 6   
    Step 6a    
    Step 6a  
    Step 6b
5. Step 7   
    7a. Sub step   
    7b. Sub step


This is the text under *Heading 3*. This is the first paragraph. **This is BOLD**. ***This is Bold and italized.***   

## Adding links to files
This is a second paragraph with a space between. 
Adding a link [Readme.md](/README.md)

Adding the link a different way using 
[Readme.md](/README.md)
Single dot, files at the same level
/ allows selection of folder 
This is a third attempted paragraph without a space in between. It merges into a single paragraph.

Adding an inline link [Adding Hyperlink](#adding-hyperlink)

#### Heading 4
Text with list
- Getting started Guide
    - Installation Guide
    > [!NOTE]
    **This is a bold note in the bulleted list**
    - Deployment Guide
- Next level
    - Sub list 1
    - Sub list 1
        - Sub-sub-list
        - Sub-sub-list

### Add Image
Check BMC before you AI   

![image](/Images/Screenshot%202026-04-06%20210003.png)

<img src="/Images/Screenshot 2026-04-06 210003.png" width="300" height="200"/>

Check the full path for this image file

**RND**____versionNumber___

***RND*versionNumber**x
`code text`

### Working with images
Text
Keep a space of one line whenever you add a style 

## Adding annotations
> [!NOTE]
This is a note

> [!Tip]
> This is a tip.

> [!Error]
> You can verify the installation by running `git --version`.
 
> [!WARNING]
> Do not close the terminal while the installation is running.

> [!Example]
> This is an example 

Note

## Installation
Follow the installation steps carefully.   

## Task list
Task list
 
- [x] Set up the editor
- [x] Write some markdown
- [ ] Connect a cloud service
- [ ] Export the finished document   
- [ ] Next item on the list   

## Footnote
[^1]: Markdown is designed to be easy to read and write.   

[^2]: GFM extends standard Markdown with additional features.  

## Collapsable content
<details>
<summary>Click to expand</summary>
 
This content is hidden by default.
 
You can include following types of content:
 
- Text
- Lists
- Code
- Links
- Images
 
</details>   

Opened collapsible
 
<details open>
<summary>Prerequisites</summary>
 
Before you begin, make sure you have:
 
- Git installed
- VS Code installed
- A GitHub account
 
</details>   

## Troubleshooting
 
<details>
<summary>Why can't I push my changes?</summary>
 
Make sure you:
 
1. Have committed your changes.
2. Are connected to the correct remote repository.
3. Have permission to push to the repository.
 

 
