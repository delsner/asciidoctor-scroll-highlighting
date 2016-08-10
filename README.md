# asciidoctor-scroll-highlighting
A short script which enables highlighting the current position in your table of contents as you scroll through the document.

![alt-tag](https://delsner.github.io/ScrollingBehavior.gif)

## Instructions
Add code snippet in [script](script.html) either anywhere in your `.adoc`-files and wrap it with `++++` or in the `<head>`-section of the generated html.

### Note:
In order to have a toc and sect anchors you must set some properties correctly in the beginning of your `.adoc`-file:
````
:toc: left
:sectanchors: true
:sectlinks: true
:sectnums: true
````
