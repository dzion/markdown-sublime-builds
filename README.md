# sublime-build-systems
These are my sublime build systems to convert Markdown to Word/Tex/PDF using Pandoc on a Mac.

# Features
- creates PDF and Word with or without Table of Contents 
- creates an html output using a "git-style" with the git-hub.css 

# Prerequisites 
- A working installation of a TeX distribution (MacTeX, MiKTeX, BasicTeX etc) for PDF output
- Pandoc [see here for installing instructions](http://pandoc.org/installing.html)
- Sublime Text (I am running Version 3, but theoretically 2 should work as well)

# Does it work on ?
Honestly, I don’t know. Maybe. It works for me on my mac. However the location of pdflatex has changed due to some reasons [more on this and update options here](https://tug.org/mactex/UpdatingForElCapitan.pdf), but using a current TeX distribution should not produce errors.  
On Windows, they probably do not work at all and need some adjustment for the path

# How to use them:
- place them into your `~/Library/Application Support/Sublime Text 3/Packages/User` directory. 
- Write/Open a MD file in Sublime Text
- decide which way you want to process your MD file
- select the build system
- Press <kbd>CMD</kbd> + <kbd>B</kbd>


