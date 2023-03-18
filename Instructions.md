# Steps to create a simple website on Github using .md file.
Go to github. com. Login and create nw repository. Choose the name as your given username followed by'.github.io'. Fir example "mywebpage.github.io"

# Github Markdown

# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
##### h6 Heading

## Horizontal line

-----

## Emphasis

**This is bold text**

*This is Italic text*

~Strikethrough~

## Blockquotes

> Blockquotes can also be nested ...
>> ...by using additional greater-tan signs right next to each other...
> > > ... or with spaces between arraows.

## Lists

Unordered

+Create a list by starting a line with '+', '-', or '*'.
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Some random characters
    + Some random characters
    - Some random characters
+ very easy!

Ordered

1. Your sentence one.
2. Your sentence two.
3. Your sentence three.

## Code

Inline 'code'

Indented code

    // some comments
    Line 1 of code
    Line 2 of code
    Line 3 of code

Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5))
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extensions to be used for dest files. |

## Links

[link text](https://github.com/makeabhishek) 
[link with title](https://github.com/makeabhishek/ "title text")

## Images

![Minion](https://github.com/makeabhishek.png)

## Web-themes
To apply a theme or template
1. Go to github setting -> Github Pages. There is a tab to 'Choose a theme'. This is a 'Jekyll' theme.

2. Another option is to upload an entire static website to your Github repository. For this you should have static website containing all data including images, html, css, java script file. Go to your github repository, click on 'Add file' and choose 'Upload files'. Github can recursively upload the files. 'commit changes'. 
It will take some time to cache the website. What you can do is to type your webpage name followed by /index.html and it will serve the website. For example example.github.io/index.html

3. If there is no theme of your choise on github 'Jekyll' theme. You can find different themes at [link with title](jekyllrb.com/resources/ "Jekyll Themes")

## Add additional subdirectory
we can add additional websites with a subdirectory. 
1. Lets assume we have a subdirectory name 'test'. Go to Settings, Github Pages. You can see that there is no website. Change the source from None to main and save it. 
2. Go to you main webpage on Github pages. Setup your page and theme. Follow the same procedure as follows.
3. Wait for some time to upload the website. Serch the url For example: mywebpage.github.io/demo/

## the End!
