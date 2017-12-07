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

## Blockquotes
To create a block quote, you can preface a line with the "greater than" caret ( > ):

> "With great power comes great responsibility. -- Lu Xun"

You can also place a caret sign on each line of the quote. This is particularly useful if your quote spans multiple paragraphs. Notice that even blank lines must contain the caret sign, this ensures that the entire blockquote is grouped together:
>
> "I agree. -- Su Dong Bo"
>
> "+1. -- Lee Bai"
>
> "I don't remember I have said such thing. -- Lu Xun"

Block quotes can contain other Markdown elements, such as italics, images, or links:

> "I'm **Lovin'** it!"

## Lists
To create an unordered list, you can preface each item in the list with an asterisk ( * ):

* Milk
* Eggs
* Salmon
* Butter

To create an ordered list, you can preface each item in the list with numbers, instead of asterisks:

1. Pizza
2. Hot Dog
3. Pasta
4. Burger

To nest one list within another, you can indent each asterisk _two space more_ than the preceding item:

* iOS Phones
  * iPhone X
  * iPhone 8
  * iPhone 7
* Android Phones
  * Huawei Mate10
  * LG G7
  * Sony XZ
 
## Paragraphs
From previous section, we learn how to break paragraphs by inserting a new line, this method is known as _hard break_; there is another method to break paragraphs without breaking the togetherness, which is _soft break_:

Remember me  
Though I have to say goodbye  
Remember me  
Don't let it make you cry  
For even if I'm far away I hold you in my heart  
I sing a secret song to you each night we are apart

Remember me  
Though I have to travel far  
Remember me  
Each time you hear a sad guitar  
Know that I'm with you the only way that I can be  
Until you're in my arms again  
Remember me
