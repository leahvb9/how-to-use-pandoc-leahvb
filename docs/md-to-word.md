# Converting Markdown to Word

This guide will allow you to change Markdown files to Word documents using Pandoc. 
## Tools 
- Pandoc 
- Terminal
- Finder
- Markdown File 

## Directions 
1. Save your Markdown file in a document folder on your computer. Your document must have at least one sentence of text.
   -  `NOTE:` Your Markdown file cannot have any spaces. An example could be "markdown-file-1.md"
2. Using the Finder application, locate your document folder. 
   <figure>
   <img src="images/md-file-in-folder-to-convert.png"> </img>
    <figcaption> Image of file in file folder. </figcaption> </figure>

3. Select 'View' on Finder's control panel, then click 'Show Path Bar.' This will reveal a path bar at the bottom of the Finder screen. 
   <figure> <img src="images/file-path-md-to-word.png"> </img>
   <figcaption> Image of Path Bar at the bottom of the Finder application. </figcaption> </figure>
4. Open the Terminal app. 
5. Type "cd " into the Terminal, then drag your folder from the Path Bar into the terminal.
   - `NOTE:` "cd " **must have a space after it** and must be lowercase or the command will not work. 
6. Click enter. Terminal is now "inside" that folder in your computer. 
   <figure> <img src="images/cd-example-md-to-word.png"> </img>
    <figcaption> Image of the Terminal after the command "cd" is inputted. </figcaption> </figure>
7. Type "pandoc (your file name).md -o (your file name).docx.
   - `NOTE:` An example using the file example above would be: "pandoc markdown-file-1.md -o markdown-file-1.docx"
    <figure> <img src="images/pandoc-code-md-to-word.png"> </img>
    <figcaption> Image of the Terminal after the Pandoc command is inputted. </figcaption> </figure>

8. Click enter. Your Doc file will appear within your orgininal document folder. 
   <figure> <img src="images/word-created-by-pandoc.png"> </img>
    <figcaption> Image of the Word Document created using the Pandoc code. </figcaption> </figure>

Back to [the home page](../index.html)


