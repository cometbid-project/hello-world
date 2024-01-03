Hi there,
---

# Basic Syntax


## Headers  

# h1 Heading  
## h2 Heading  
### h3 Heading  
#### h4 Heading  
##### h5 Heading  
###### h6 Heading  

Or 

Another form of header h1
==
And another h2
--

# Paragraphs  
I really like using Markdown.  
I think I'll use it from now on.

# Line Breaks  
This is the first line.  
And this is the second line.  

# Emphasis  
### Bold

**This is bold text**  
I love **bold text**. And another __bold text__.  
Love**is**bold

### Italic  
_This is italic text_  
The *cat's meow*. or The _cat's meow_.  
A*cat*meow

### Bold and Italic  
***Important*** text.  
___Important___ text.  
__*Important*__ text.  
**_Important_** text.  

### Strike-Through
~~Strikethrough~~  
The world is ~~flat~~ round.

## Blockquotes

> Blockquotes can also be nested...
>
> And this is second paragraph
> 
> > ...by using additional greater-than signs right next to each other...
> >
> > > ...or with spaces between arrows.

## Blockquotes with other Elements
> ##### The quarterly results look great!
>
>  - Revenue was off the chart.
>  - Profits were higher than ever.
>
> *Everything* is going **well**.

## Lists  

###  Ordered
1. First item
2. Second item
3. Third item
4. Fourth item

1. First item
1. Second item
1. Third item
1. Fourth item

1. First item
8. Second item
3. Third item
5. Fourth item

### Indented Lists 
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

###  Unordered  

- First item
- Second item
- Third item
- Fourth item

* First item with Asterisks
* Second item with Asterisks
* Third item with Asterisks
* Fourth item with Asterisks

+ First item with plus signs
* Second item with Asterisks
- Third item with dash

###  Nested List Items
- Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    - Ac tristique libero volutpat at
    * Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

###  Adding Elements in lists
**Paragraphs**

* This is the first list item.  
* Here's the second list item.  
I need to add another paragraph below the second list item.
* And here's the third list item.

**Blockquotes**

* This is the first list item.  
* Here's the second list item.  
    > I need to add another paragraph below the second list item.
* And here's the third list item.

**Code Blocks**  
1. Open the file
2. Find the following code block on line 21:

           <html>
              <head>
                <title>Test</title>
              </head>
           </html>
    
3. Update the title to match the name of your website.

**Images**
1. Open the file containing Tux, the Linux mascot.
2. Marvel at its beauty.
   
   ![Tux](https://github.com/cometbid-project/hello-world/assets/20684020/b16e4d95-d4c7-4737-af04-532b055fe529)

4. Close the file.


## Code

At the command prompt, type `nano`.

###  Escaping Tick Marks

``Use `code` in your Markdown file.``

### Indented Code Blocks

            <html>
              <head>
              </head>
            </html>

###  Block code "fences"

```
Sample html tags below...

<html>
  <head>
  </head>
</html>
```

### Syntax highlighting

```js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Horizontal Rules

Use three asterisks(***), dashes (---), or underscores(___) on a line by themselves
***
---
___

## Links

Use [Duck Duck Go](https://duckduckgo.com "My search engine!").

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)

### Turn URLs and Email Addresses to links

<https://eff.org>  

<fake@example.com>

### Formatting Links  

I love supporting **[Apache Software Foundation](https://apache.org)**.  

This is **[Apache Software Foundation](https://apache.org)**.

### Reference Style Links 

[hobbit-hole][1]  
[hobbit-hole-title][2]  
[hobbit-hole-lowercase][a]  
[hobbit-hole-bracket][A]  


[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 
[2]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"  
[a]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'  
[A]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to eat: it was a [hobbit-hole][3], and that means comfort.

[3]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles" 


## Images

![Minion](https://octodex.github.com/images/minion.png)  

![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")  

### Like links, Images also have a footnote style syntax

![The Dojocat][id]

[id]: https://octodex.github.com/images/dojocat.jpg "The Dojocat"


### Escaping Characters

\* Without the backlash, this would be a bullet in an unordered list.

You can use a backlash to escape the following characters.
``\ ` * _ {} [] () # + - . !``

## Emojis
To get any Emoji, start by typing a colon and the first letter of a word to get a dropdown of suggestions.

Grinning:   :grinning:  🙂    
Laughing or Satisfied:  :laughing: or :satisfied:    
Rolling on the floor:   :rofl:      
Smiling face:   🙂 :slightly_smiling_face:    
Wink:  :wink 😉    
Innocent: :innocent:  😇  
Smiley face:  :smiley:    😁  😃  
Sweat Smile:  	😅  :sweat_smile:  
Joy:  :joy:  😂  
Upside Down:    :upside_down_face:  🙃  
Blushing:   :blush:  😊  

 
# Extended Syntax 
Extended syntx isn't available in all Markdown applications..

## Tables

| Option | Description                                                               |
| ------ | ------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files. 


Right aligned columns

| Option |                                                               Description |
| -----: | ------------------------------------------------------------------------: |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |

Left aligned columns

| Option |                                                               Description |
| :----- | :------------------------------------------------------------------------ |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |

_Formatting text in Tables_  
You can add links, code(words or phrases in tick marks (`) only, not code blocks), and emphasis.  
Headings, blockquotes, list, horizontal rules, images, or HTML tags not allowed.  

To display a pipe(|) character in a table, use it's HTML character code (&#124;).


## Fenced Code blocks
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Footnotes           
Here's a simple footnote,[^1] and here's another footnote with longer text.[^bignote]   
Footnote 1 link[^first]. 
Footnote 2 link[^second].  
Inline footnote^[Text of inline footnote] definition.  
Duplicated footnote reference[^second].  


[^1]: This is the first footnote.
[^bignote]: Here's one with multiple paragraphs and code.  
      Indent paragraphs to include them in the footnote.  
      `{my code}`  
      Add as many paragraphs as you like.  
[^first]: Footnote **can have markup**
    and multiple paragraphs.
[^second]: Footnote text.


## Custom IDs
### [My Anchor Link](#anchor-link)

## My Linked Header <a id="linked-heading"></a>


## Definition Lists (Does not work as expected)
First Term   
    : This is the definition of the first term.

Second Term   
    : This is one definition of the second term.   
    : This is another definition of the second term.  

Term 1  
: Definition 1
with lazy continuation.

Term 2 with _inline markup_  
: Definition 2

        { some code, part of Definition 2 }

Third paragraph of definition 2.

_Compact style:_  
Term 1  
~ Definition 1  

Term 2  
~ Definition 2a  
~ Definition 2b  

## Task Lists
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## Automatic URL linking
https://www.apache.org

Disable automatic link
`https://www.apache.org`




### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

\*[HTML]: Hyper Text Markup Language

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning  
_here be dragons_  
:::


<br>

##  Anchor Link <a id="anchor-link"></a>

Where is my [heading](#linked-heading)
 
<br>













































