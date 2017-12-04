# Markdown Tutorial

## Italics and Bold
To make a phrase _italic_ in Markdown, you can surround words with and underscore ( _ ).

To make a phrase **bold** in Markdown, you can surround words with two asterisks ( ** ).

You can use both italics and bold in the **_same_** line. You can also span them **_across multiple words_**.

## Headers
To make headers in Markdown, you preface the phrase with a has mark ( # ). You place the same number of hash marks as the size of the header you want. There are 6 header sizes:

# Header One
## Header Two
### Header Three
#### Header Four
##### Header Five
###### Header Six

You can't really make a header bold, but you can italicize certain words:

#### This is a header _four_

## Links
There are two different link types in Markdown, but both of them render the exact same way.

The first link type is called an _inline link_. To create an inline link, you wrap the link text in brackets ( [ ] ), and then you wrap the link in parenthesis ( ( ) ):

Let's [google it](www.google.com).

You can also add emphasis to link texts:

Let's [**really** google it](www.google.com).

You can make links within headings, too:

#### The Latest News from [Google](www.google.com).

The second link type is called a _reference link_, it is actually a reference to another place in the document:

How do I [find][google] information on the Internet?

[google]: www.google.com

## Images
The syntax to create images in Markdown is nearly the same as to create links. The diference between links and images is that images are prefaced with an exclamation point ( ! ).

The first image style is called an _inline image link_. To create an inline image link, enter an exclamation point ( ! ), wrap the **alt** text in brackets ( [ ] ), and then wrap the link in parenthesis ( ( ) ). (**Alt** text is a phrase or sentence that describes the image for the visually impaired.)

![A representation of Megaman](https://octodex.github.com/images/megacat-2.png)

The second image style called a _reference image_, it is actually a reference to another place in the document:

![The first Megaman][First Megaman]

[First Megaman]: https://octodex.github.com/images/megacat.jpg
