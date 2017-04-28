# sublime-build-systems
These are my sublime build systems to convert Markdown to Word/Tex/PDF using Pandoc on a Mac (> 10.10.x) or a Windows 10 Machine.

# Features
- creates PDF and Word with or without Table of Contents 
- creates an html output using a "git-style" with the git-hub.css 

# Prerequisites 
- A working installation of a TeX distribution (MacTeX, MiKTeX, BasicTeX etc.) for PDF output
- Pandoc [see here for installing instructions](http://pandoc.org/installing.html)
- Sublime Text (I am running Version 3, but theoretically 2 should work as well)

# Does it work on ?
Honestly, I don’t know. Maybe. It works for me on my mac and for my colleague on Windows 10. 
For macOS the location of pdflatex has changed due to some reasons [more on this and update options here](https://tug.org/mactex/UpdatingForElCapitan.pdf), but using a current TeX distribution should not produce errors.  
On Windows, they seem to work fine, but both Pandoc and Latex need to be executable from the Path. 

# How to use them:
- Open the Sublime Text Settings folder via the Menu (Sublime Text -> Preferences -> Browse Packages) and place them into the `User` directory.
- Write/Open a MD file in Sublime Text
- decide which way you want to process your MD file
- select the build system
- Press <kbd>CMD</kbd> + <kbd>B</kbd> on macOS or <kbd>Ctrl</kbd> + <kbd>B</kbd> on Windows

# Thanks to: 
@tim06927 for adopting the build systems for Windows  
markdown-pandoc.css from [Alberto Leal](https://gist.github.com/dashed/6714393)  
buttondown.css from [Ryan Gray](https://gist.github.com/ryangray/1882525/)  



