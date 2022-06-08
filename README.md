# Markdown-Test-Repo
My first repository

# Headings
## Hello
### Hello
#### Hello
##### Hello
###### Hello  

```md
# Headings
# Hello
## Hello
### Hello
#### Hello
##### Hello
###### Hello
```
--------

# Line Breaks  
line breaks can be made using either HTML \<br> or by ending a line with a double space  

Markdown  
Line break

HTML <br> line break 

# Emphasis
**Bold**  
__Bold__

*italic*  
_italic_

***Bold/Italic***  
___Bold/Italic___  
**_Bold/Italic_**  
*__Bold/Italic__*

# Subscript and Superscript
using HTML \<sup> and \<sub>  

<sub>subscript</sub> and <sup>superscript</sup>

 <sub>subscript <sub>subscript level 2</sub></sub>
 <sup>superscript <sup>superscript level 2</sup></sup>  
 <sub>t<sup>e<sub>s<sub>t

# Block Quote

>This is how to make block quotes
>
>Aswell as adding empty lines  

>>Now for nested block quotes  
>> 
>>pretty cool
>
>back out to the parent quote

# Code

Enclose lines in backticks (```) to make code blocks   

```html
    <html>
     <body>
      <p>this HTML should be visible</p>
     </body>
    </html>
```
# Lists

### Unordered lists (ul)
* First entry
* Second entry
* Third entry

- First entry
- Second entry
- Third entry

### Ordered lists (ol)
1. First entry
2. Second entry
3. Third entry

# Horizontal Page Rule

(---)

---
(***)

***
(___)
___

# Links
Enclose a title for a link in [ ] then place your link in ( ).  
Append the link with " " to add a hover title to link  
[**Cat Video**](https://www.youtube.com/watch?v=p7YXXieghto "My cat video")  

# Images
To use an imaage in your README.md you need to upload them to your repository and then put its path in the markdown code  
this can also be achieved on GitHub by drag and drop



![Image](path to image)    
or if you prefer to be fancy use HTML to resize your image
```html
<img src="https://pbs.twimg.com/media/FTffnIdWYAAQFrX?format=jpg&name=medium" alt="Kanye" width="300"/>
```
<img src="https://pbs.twimg.com/media/FTffnIdWYAAQFrX?format=jpg&name=medium" alt="Kanye" width="300"/>

you can also add gifs using  
![Main](Link to gif)  
![Main](https://i.pinimg.com/originals/f7/85/7f/f7857f7dc8194d91da6b825d3ab90fce.gif)  


# Video
Drag and drop into your README.md on github

# Labels
Add labels to your README.md  
[More labels available here](https://shields.io)  
![GitHub all releases](https://img.shields.io/github/downloads/{username}/{repo-name}/total)
![GitHub language count](https://img.shields.io/github/languages/count/{username}/{repo-name})
![GitHub top language](https://img.shields.io/github/languages/top/{username}/{repo-name}?color=yellow)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/{username}/{repo-name})
![GitHub forks](https://img.shields.io/github/forks/{username}/{repo-name}?style=social)
![GitHub Repo stars](https://img.shields.io/github/stars/{username}/{repo-name}?style=social)
```
![GitHub all releases](https://img.shields.io/github/downloads/{username}/{repo-name}/total)

![GitHub language count](https://img.shields.io/github/languages/count/{username}/{repo-name})

![GitHub top language](https://img.shields.io/github/languages/top/{username}/{repo-name}?color=yellow)

![Bitbucket open issues](https://img.shields.io/bitbucket/issues/{username}/{repo-name})

![GitHub forks](https://img.shields.io/github/forks/{username}/{repo-name}?style=social)

![GitHub Repo stars](https://img.shields.io/github/stars/{username}/{repo-name}?style=social)
```  
# Tables
using pipes and hyphens you can create tables
```
|Header | Header | Header |
|---|---|---|
| 1 | 2 | 3 |
| a | b | c |
```
|Header | Header | Header |
|---|---|---|
| 1 | 2 | 3 |
| a | b | c |
### Align table
```
|Header | Header | Header |
|:---|:---:|---:|
| 1 | 2 | 3 |
| a | b | c |
```
|Header | Header | Header |
|:---|:---:|---:|
| 1 | 2 | 3 |
| a | b | c |

# Task Lists
combining lists from before (-) add [ ] after and fill with an  X to check 
off  
TODO    

- [x] Finish this markdown
- [ ] This shit is broken on VSCode 

# Colour hightlight within codeblock
```diff
- this is a red line
+ green line
@@ purple line @@ 
```
<sub><sub><sub>I hope it worked</sub></sub></sub>
# Code block
To segment code enclose lines in single backticks  
`hi`

# Zoomer Hieroglyphs
Go [here](https://emojipedia.org/) first and find an emoji you want to use  or if you're on windows (win + :)  
😎😊❤💕


