# Latex Template for Bachelor/Master thesis

Due to popular request, I stripped down my [master's thesis](https://github.com/wumpf/masterthesis) into this template. I left the general structure (which might not be applicable for your work at all!) and a few of the trickier things in.

This is meant as a shortcut for any student who isn't quite sure how to get started. Obviously you will need to change the structure & style to whatever your needs are and your supervisor asks from you.

## Notes on Usage

### General Structure
[latex/thesis.tex](latex/thesis.tex) is where everything comes together. It defines style, packages, a few custom commands and includes all the other files. You can find a few comments explaining things sparsely.

Every other tex file can be compiled on its own. Each chapter or segment in the thesis has its own tex file. 
I kept most of my original chapter structure here - you will almost certainly want to change this!

All images should go to [pictures](pictures/). 

### "Statement of Authorship"
This is what worked on my university (Magdeburg). You almost certainly need something like this, but it may very well look completely different.

### Tools of my Choice
Back in the day I worked with [TeXstudio](http://www.texstudio.org/) which I enjoyed using a lot.
To organize the [bibliography](latex/bibliography.bib) I used [JabRef](http://www.jabref.org/) which was a great help to get an overview and cleanup the references.

## Q & A

### What is glsl.tex?
A language highlighting definition for glsl code blocks. Left it in there because I thought you might need it or at least could use an example for custom language definition.

### Why \subfile and not XY?
\subfile has the amazing advantage that you can compile parts of the thesis interpedently. Once you get more images in this increases your improves time tremendously!

## Licensing
It's public domain, so do what you want with it! Of course I'd be happy if you give my github repository a star or even mention me in your thesis' acknowledgements ;-)

![Public Domain Logo](https://licensebuttons.net/p/zero/1.0/88x31.png)
