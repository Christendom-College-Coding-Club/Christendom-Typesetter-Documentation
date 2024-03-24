# Formatting Guide
### Block Quotes
To create a block quote, suround the quoted text with \[\[\[ and \]\]\]. E.g.,
```
[[[ 
We're no strangers to love  
You know the rules and so do I
]]]
```
Cdomtex usually ignores the line breaks in your files and just inserts
its own when needed, but it will respect line breaks in block quotes,
in case you're quoting a genre where line breaks are important, like poetry.
### Italics
To italicize a word or phrase, surround it in underscores. E.g., 
```
_The Odyssey_
```
will produce: _The Odyssey_.
### Footnotes
To create a footnote, type ^ and then a name for the footnote.
That name should ideally be symbolic of the footnote's contents, 
but it can be pretty much anything. E.g., 
```
Homer says "Sing."^ody1.1
```
will produce: Homer says "Sing."<sup>1</sup>
You will then be able to edit the text of the footnote in the cdomtex window -
it be labelled with the name you gave it.
(In the example used, you would look for the box labelled "ody1.1").
### Bibliography/Works Cited
To begin the Bibliography/Works Cited section,
type BIBLIOGRAPHY or WORKS CITED on a line by itself -
it will be centered and put on a new page. To add an entry,
simply precede it with three underscores. 
```
___Seuss, Dr. Green Eggs and Ham.
```
NOTE: the preview does not show you the hanging indent, but don't worry -
in the final PDF it will be there.
### Anything Else
Cdomtex will accept any LaTeX commands - you just won't get a preview of them.
If you need to do something simple, like adding or removing vertical space,
you can just look up "how to add vertical space in LaTeX,"
and you should find something that works, e.g., the \vspace command.
For more complex formatting, like a different title page format,
you can email the project lead,
at [lewis.thornberry@christendom.edu], and they will show you how to do what you want.
Don't be afraid to ask: any questions
will help us make this app better.
### Modifying the LaTeX templates
If you look in the "!cdomtex" folder in your paper's directory, 
you will find all of the LaTeX styling that is automatically applied 
to your document, in the files "metadata.tex," which contains the title
section, and "style.tex," which formats the body of the paper. Changes
to these files will be applied to that paper only. If you make a mistake
and want to revert to the default, simply delete those two files and restart the app.
