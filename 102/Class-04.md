

LAB 04 Html notes page not finished

HTML? is used to mark up documents so that the page is basically readable even if no explicit styling is specified by the author of the page.

For instance h1- the same way we use h1 in markdown we can use within HTML
*heading 1* will be used to make the heading larger than the rest of the text on the page. Followed by H2, H3 etc. All these headings vary in sizes. Paragraphs ```<p>``` break the text up onto a new line and have spaces between them so the text is easily readable. 

**How should each element or html be nester? **
Examples of non-semantic elements: 
```<div>``` and ```<span>```- Tells nothing about its content.
Examples of semantic elements: ```<form>```, ```<table>``` and ```<article>```- Clearly defines its content.

- The ```<article>``` element specifies independent, self-contained content.
An article should make sense on its own, and it should be possible to distribute it independently from the rest of the web site.
- The ```<section>``` element defines a section in a document.
According to W3C's HTML documentation: "A section is a thematic grouping of content, typically with a heading.
-The ```<header>``` element represents a container for introductory content or a set of navigational links.
example of header
```<article>
  <header>
    <h1>This is a header example?</h1>
    <p>To learn Headers</p>
  </header>
  <p>Headers are an introduction, you can have several header elements in one HTML document, but the header cannot be placed within a footer, address, or another header element.</p>
</article>```
 
 
<h2>LAB exercise </h2>
To embrace the next level, set up a html site, 
1.we partner up with and decide on a topic, each person designs one page, design a really simple wireframe on figma , identify the general content area.
2.apply html to a structure. Label with the html on the wireframe

3.write out the key content for each area . 
each person works on their own repository to work from. 

**How do we get a new repository on our local computer from git hub?**

**terminal**
```
-cd ..
projects folder git clone - link 
ls
cd html page
code .
VS
settings pages github 
refresh save 
go to VS 
change something, - width
save
check website has changed
terminal 
git status (modified)
git add style.css. (adding changes of the file to commited)
git status (green- Ready)
git commit -m " update message"
git status
(on branch main ) 
git push
(to git hub to see the change.
//open github , refresh
```

For the demo.

each person codes their own index.html
each person should end up with their own index.html file containing basically the same html tags in the same order but with different content.
we have to create jamboard on google to present our work
we have cerated a site on singing lightbulbs, with a title, about me, with 3 testimonals, one main testimonal Agnes, we wanted to create a funny website. 
lighting and music - lightbulbs flickers to music 
rave bulb - rave bulb desciption - a mix of a vriety of rave songs, throughout the entire journey of rave culture, do you remember of opening of cream and and fabric, we give you this experience.
classic bulb - relax, and sit back to the most soothing sounds to touch your sense, at the touch of a button or the flick of a switch.
limited edition - one song - sponsored by Michael 'buble' 
the way you get it to be live is open git hub, copy code

