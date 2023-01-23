<h1>**Markdown**</h1>

<h2> Understanding Markdown </h2> 

Markdown is a lightweight markup language that describes how text should look on a page. HTML is another example of a markup language. Markdown is really simple to learn and is an easy html conversion - this means it is considered as a text-to-html conversion software in addition to being a markup language.

The first syntax to learn is how to add headings with a ```#```.
Although seemingly backwards in logic (I may be alone there). The more hashtags the *smaller* the headings will be. For the largest heading or the h1 heading, we add one hashtag. For the h2 heading, we add two hashtags, and so on. Given below is an example program to add headings in Markdown.

```
# h1 heading
## h2 heading
#### h4 heading
###### h6 heading
```

Here is an example of the output.. 
# h1 heading
## h2 heading
#### h4 heading
###### h6 heading

**Font Styling** 

*ITALICS*

To make text *italics*, we would use either single asterisks or use single underscores. I personally like to use astericks but it is a personal preference.

```*Is it just me or does text look great in italics*
_Is it just me or does text look great in italics_```

o u t p u t 

*Is it just me or does text look great in italics*
_Is it just me or does text look great in italics_

**BOLD**

If we want some '''<strong>''' text (or ```**bold**``` text), we can use double asterisks or we can also use double underscores which will make it bold as well.

```**This text is a strong text it likes to be bold**
__This text is a strong text it likes to be bold__```

o u t p u t

**This text is a strong text it likes to be bold**
__This text is a strong text it likes to be bold__

***BOLD + ITALICS***

To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. 

```
***This text is really important***
```

***This text is really important***

~~STRIKETHROUGH~~
For strikethrough we can use the double tilde sign.


A horizontal line acts like a separator, and for that, we use triple hyphens or triple underscores. You can use this to separate your content. 

```This is some text to prove the point of a horizontal line.
___

This is the text after that horizontal line.```

o u t p u t 

This is some text to prove the point of a horizontal line.
___

This is the text after that horizontal line.

LINE BREAKS

We can use two or more spaces (commonly referred to as “trailing whitespace”) for line breaks in nearly every Markdown application.

*If your Markdown application supports HTML, you can use the ```<br>``` HTML tag.*

First line with two spaces  
and the next line


HYPERLINK 

Text which we want to use for the hyperlink goes in square brackets, and the link will go in round brackets. 

```<!-- Adding Link with sample text -->
[link](https://www.linkme.com/)```

o u t p u t

<!-- Adding Link with sample text -->
[link](https://www.linkme.com/)

>BLOCKQUOTES

As seen in the title above To create a blockquote, add a > in front of a paragraph.

If you want to *Nest* blockquotes simply add a >> in front of the paragraph you want to nest.

o u t p u t 
>nesting blockquotes.
>can look like this 
>>Nesting looks like this

```
```QUOTING CODE```
```

To quote code that you are using like Ive done on this page. You use triple backticks `````````
