# Links and Menus

We will be exploring hyperlinks and how they can be used to navigate a website
* creating hyperlinks
* organizing a website as a collection of webpages
* creating and styling menus

## How is a webpage different from a website?
https://www.javatpoint.com/webpage-vs-website  
TLDR:  
A webpage is a single html document.  A webpage is multiple related html documents intended to break up the content into organized sections

## Hyperlinks
A special kind of html tag is an *html anchor*.  It uses the "a" tag.  And appears like this:
```
<a href="https://web.deltaschools.ca">Go to the main index page at a website</a>
<a href="http://www.deltsd.bc.ca/agenda.html">Insecure link to the agenda.html file on a webserver</a>
<a href="example.html">Link to a document on this site</a>
```
All hypertext links contain an ***href*** attribute.  This is the reference document that the link points to.  When the link points to a document on another webserver, we need to include the *http* or *https* protocol.  The difference between these is that secure links are verified and encrypted to ensure that sensitive information (like credit card or personal information) cannot be intercepted and stolen.  If the link points to a document on the same server as the original html, then the http/https protocol is not needed.  

The content contained between the beginning and ending of the tag is what you can click on to follow the link.  Look at the *basic.html* page to see how this tag can be used with text or images.

## Modern Hyperlinks and Menus
It is quite common now for websites to organize their content with a menu system.  This allows rapid navigation of a site in an organized manner.  A popular way of creating menus now is to use the li element that used to be reserved for bulleted lists.  Note how these are included in the example documents.  
Menus and links can be created in vertical, or horizontal menus.  

Note that for horizontal menus, a parent element needs to be created with a style that includes the following (although you can use any container, not just div)
```
  div { display: flex;}
```

## Transitions
What really adds some flare is the use of the **transition** style property, which allows the style to be briefly changed and animated/tweened to go from one look to another, and then back.  This can be an easy way to make your selected navigation stand out.  Some examples can be seen in the other example html documents.

# Assignment
Plan and Create a website  
You will need to have multiple pages that you can navigate.  Plan on having a landing page (often called the index.html) with pictures and an introduction.  Your content can be on other pages.  We will have multiple classes to work on this assignment.

Tips:
* Gather all of your information first. This will often dicate how you will organize your page contents.  
* Plan out how your page will look.  This can be done with pencil and paper to bloc out some rough layouts.
* Use an image editor to adjust/resize any images you want to use.  You can also get some exact sizes of the image this way.
