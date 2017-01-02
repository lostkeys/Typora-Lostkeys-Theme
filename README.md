# Typora Lostkeys Theme

_This theme is work in progress _

Currently it is only tested on the MacOS version of Typora and it uses some bleeding edge CSS like variables which I have no idea if they work im Typora for other platforms. It is still plenty of work left before it is a complete theme.

Useful Links

* [Markdown syntax documentation](https://daringfireball.net/projects/markdown/syntax)
* [Documentation for writing custom Typora themes](http://theme.typora.io/doc/Write-Custom-Theme/)

## Inline elements

This is a standard paragraph. **To make a test bold**, I prefer to use asterixes. And to emphasis a text _underscores makes most sense_. [Links are colored and underlined](http://lostkeys.se).I rarely use ~~strikethrough~~ but it also works. Inline code is  `formatted in a monospace font`.

## Block elements

Unordered lists:

* I prefer using asterix as bullets
* Instead of dashes. But both works

Ordered lists

1. Apples
2. Oranges
3. Bananas

Codeblock

```css
/* blockquote & Pre */
blockquote, pre {
  margin: 1rem 0;
  padding-left: 4ch;
  position: relative;
  overflow: hidden;
}
```

Blockquote

> The third-rate mind is only happy when it is thinking with the majority. The second-rate mind is only happy when it is thinking with the minority. The first-rate mind is only happy when it is thinking.
> —A. A. Milne

Task list

-[ ] This task is just waiting to be completed
-[ ] Completed task!

### Headers

H1, H2 and H3 headers are styled to stand out. I rarely use more than three levels of headers. Therefore, headers level 4-6 looks like bolded text.

#### Header 4

##### Header 5

###### Header 6

## Caveats

Tables are not styled

Math blocks are not tested. Assuming it looks terrible

Outline panel is not styled and causes the writing area to expand

## Todo

Style codeblocks

Style task list