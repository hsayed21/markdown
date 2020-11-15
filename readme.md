## Heading
```
# Header 1 - 6 
```
## Bold
```
**Bold**
__Bold__
```
## Italic
```
*Italics*
_Italics_ 
```
## Strike
```
~~Strike~~
```
## Blockquotes

```
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 
```

## Lists
```
1. First ordered list item
2. Another item
    * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
4. And another item.  
    Some text that should be aligned with the above item.
* Unordered list can use asterisks
- Or minuses
+ Or pluses

Task List
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

```
## Code and Syntax Highlighting


Inline \``code`\` has \``back-ticks around`\` it.

block-code  ```     ````  

```
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```
```python
s = "Python syntax highlighting"
print s
```
 
 ```

No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

## Horizontal Rule

```
---
***
___
```

## Line Breaks
```
[Enter]
<br>
```

## Escape char
```
\* test \*
```
Markdown provides backslash escapes for the following characters:

\ backslash <br> 
() parentheses <br>
\` backtick <br>
\# hash mark <br>
\* asterisk <br>
\+ plus sign <br>
\_ underscore <br>
\- minus sign (hyphen) <br>
\{} curly braces <br>
\. dot <br>
[] square brackets ! exclamation mark

## Links
```
[title](https://www.example.com)

[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```
## Images
```
![alt text](image.jpg)

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
```

## Table
```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| :---          |    :----:     |  ---: |
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```
## Inline HTML
```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```
## YouTube Videos
```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Or, in pure Markdown, but losing the image sizing and border:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```
## sample structure readme
https://github.com/alMohamady/README-file-sample-

## emoji
https://github.com/ikatyang/emoji-cheat-sheet

## Githum readme stats
https://github.com/anuraghazra/github-readme-stats

## creative profile readme
https://github.com/coderjojo/creative-profile-readme

## js sequenece diagrams like hand-writing
https://bramp.github.io/js-sequence-diagrams/