# JST Markdown

This has examples of more advanced techniques that aren't easily found.

## Whitespace

Sometimes you want to have blank lines within the text, perhaps to seperate some text.
<br/><br/>
So you can add a

```<br/><br/>```

to create a break in the text that will be honored by HTML.  The first break tag will make the next line of text not be on the same line as the above text, then adding a second one will actually create the blank line.  So you can add two lines by adding 3 break tags (N = # lines - 1)

## Collapsable Areas

Sometimes it's handy to have a section of text that is initially hidden, but able to be expanded.  So you can do
<details><summary>Some Hidden Text</summary><p>
## Some Header

And them some secret text
</p></details>