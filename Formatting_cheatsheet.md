# Basic instruction for creating repository with an .md (markdown) file
Once you are in the GitHub account, click on the BioDiv icon in the upper right and "Your repositories".  A repository is basically a folder where we can keep files. To create a new repository, click on the upper right green icon which will then prompt you to name your new repository. This one is named "Intro_to_BioDiv_Github" for example. 

To make a markdown file, click on the "Add file" at the top right of the inner window. This will open a fresh file where you can compose your new file. This can be a markdown file, straight code, etc. 

A markdown file help to keep track of your pipeline and parameters you used so that it is reproducible. **It is only as good as the extent to which you document it.** To make a markdown file, name your file something descriptive with a `.md` end in the space at the top right. 

Before we get into formatting, the green Commit Changes button at the top right is key. Once you have written something in the window, click commit changes, click commit changes again. You will see the fruits of what you have written in html format and also essentially functions as a `Save` button. If you close the window with out commiting changes, you will lose whatever you just did before the most recent "Commit Changes". If you want to change anything click on the pen icon at the top right. 

# Formatting a Github .md file
For all formatting examples, if possible I will put what is typed into the codespace as well as what that looks like once we comit changes.

Normal text can be written, well, normally with no hash (#)

    Normal text can be written, well, normally with no hash (#)

To put anything in codespace window, you just indent those lines one or more tabs:

        To put anything in codespace window, you just indent those lines one or more tabs:
If you have many lines of code you want in codespace, highlight the whole block and tab it all at once.

To put filenames or short lines of code into `code font` you add ticks around it. This has to be the tick marks found on the same key as the tilda `~`. 

        To put `filenames` or short lines of code into `code font` you add ticks around it.

## Headers
    # H1
    ## H2
    ### H3
    #### H4
    ##### H5
    ###### H6
# H1
## H2
### H3
#### H4
##### H5
###### H6

### Emphasis

Italics with *asterisks* or _underscores_. \
Bold, with double **asterisks** or double __underscores__. \
Combine with **asterisks and _underscores_**. \
Strikethrough with two tildes. ~~Scratch this.~~

    Italics with *asterisks* or _underscores_.

    Bold, with double **asterisks** or double __underscores__.

    Combine with **asterisks and _underscores_**.

    Strikethrough with two tildes. ~~Scratch this.~~

## Lists and bullet points

1. First list item
2. Another item
      * Unordered sub-list.
      * Unordered list can use asterisks
           - Or minuses
           + Or pluses
           * All will be bullet points
1. Actual numbers don't matter, just that it's a number
      1. Ordered sub-list
      2. Second item
4. And another item.

   You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown). \
   To have a line break without a paragraph, you will need to use two trailing spaces or a `space \`.  
   Note that this line is separate, but within the same paragraph.  

        1. First ordered list item
        2. Another item
        [tab] * Unordered sub-list.
              * Unordered list can use asterisks
                    - Or minuses
                    + Or pluses
                    * All will be bullet points
        1. Actual numbers don't matter, just that it's a number
        [spaces]1. Ordered sub-list will change this 1 to i 
        [spaces]2. Ordered sub-list will change this 2 to ii
        4. Another item.
  
      [3spaces]You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown). \
      To have a line break without a paragraph, you will need to use two trailing spaces or a `space \`.[2spaces]
      Note that this line is separate, but within the same paragraph.[2spaces]
  
## Links

There are two ways to create links.
1. Hyperlinked text:
    [hyperlinked text to CCH2](https://www.cch2.org/portal/collections/search/index.php)
    [Reference to a repository](../path/to/repository) \
    [You can use numbers for reference-style link definitions](1:)

2. plain ol' URLs in angle brackets will automatically get turned into links. 
https://sbbotanicgarden.org/ or <https://sbbotanicgarden.org/>

1: https://peerj.com/preprints/3159v2/

## Table of contents
Similar to linking but within your doc. The format is:  
`[whatever text you want in table](#exact-text-you-want-to-link-to-no-caps-no-symbols-dash-separated)`

[1. Top of page to Basic instruction](#basic-instruction-for-creating-repository-with-an-md-markdown-file)
