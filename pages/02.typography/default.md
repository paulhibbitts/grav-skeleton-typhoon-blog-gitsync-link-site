---
title: Typography
---

! Details on the full capabilities of Tailwind.css can be found in the [Official Tailwind Documentation](https://tailwindcss.com/)

[youtube]https://www.youtube.com/watch?v=COraGXFb1lo[/youtube]

The [Typhoon theme](https://github.com/trilbymedia/grav-theme-typhoon) is a new theme for Grav built with [Tailwind.css](https://tailwindcss.com//) a lightweight, responsive and modern **utility-based** CSS framework. Tailwind CSS is a highly customizable, low-level CSS framework that gives you all of the building blocks you need to build bespoke designs without any annoying opinionated styles you have to fight to override.

### Headings

# H1 Heading `36px`

## H2 Heading `24px`

### H3 Heading `20px`

#### H4 Heading `16px`

```html
# H1 Heading `36px`
## H2 Heading `24px`
```

### Paragraphs

Lorem ipsum dolor sit amet, consectetur [adipiscing elit. Praesent risus leo, dictum in vehicula sit amet](#), feugiat tempus tellus. Duis quis sodales risus. Etiam euismod ornare consequat.

Climb leg rub face on everything give attitude nap all day for under the bed. Chase mice attack feet but rub face on everything hopped up on goofballs.

### Markdown Semantic Text Elements

**Bold** `**Bold**`

*Italic* `_Italic_`

~~Deleted~~ `~~Deleted~~`

`Inline Code` `` `Inline Code` ``

### HTML Semantic Text Elements

I18N `<abbr>`

Citation `<cite>`

Ctrl + S `<kbd>`

TextSuperscripted `<sup>`

TextSubscripted `<sub>`

Underlined `<u>`

Highlighted `<mark>`

20:14 `<time>`

x = y + 2 `<var>`

### Blockquote

> The advance of technology is based on making it fit in so that you don't really even notice it,
> so it's part of everyday life.
>   
>  
> 
> *   Bill Gates

```
> The advance of technology is based on making it fit in so that you don't really even notice it,
> so it's part of everyday life.
>
> <cite>- Bill Gates</cite>
```

### Unordered List

*   list item 1
*   list item 2
    *   list item 2.1
    *   list item 2.2
    *   list item 2.3
*   list item 3

```
* list item 1
* list item 2
    * list item 2.1
    * list item 2.2
    * list item 2.3
* list item 3
```

### Ordered List

1.  list item 1
2.  list item 2
    1.  list item 2.1
    2.  list item 2.2
    3.  list item 2.3
3.  list item 3

```
1. list item 1
1. list item 2
    1. list item 2.1
    1. list item 2.2
    1. list item 2.3
1. list item 3
```

### Table

| Name | Genre | Release date |
| --- | :-: | --: |
| The Shawshank Redemption | Crime, Drama | 14 October 1994 |
| The Godfather | Crime, Drama | 24 March 1972 |
| Schindler's List | Biography, Drama, History | 4 February 1994 |
| Se7en | Crime, Drama, Mystery | 22 September 1995 |

```
| Name                        | Genre                         | Release date         |
| :-------------------------- | :---------------------------: | -------------------: |
| The Shawshank Redemption    | Crime, Drama                  | 14 October 1994      |
| The Godfather               | Crime, Drama                  | 24 March 1972        |
| Schindler's List            | Biography, Drama, History     | 4 February 1994      |
| Se7en                       | Crime, Drama, Mystery         | 22 September 1995    |
```

### Notices

The notices styles are actually provided by the `markdown-notices` plugin but are useful enough to include here:

! This is a warning notification

!! This is a error notification

!!! This is a default notification

!!!! This is a success notification

```
! This is a warning notification

!! This is a error notification

!!! This is a default notification

!!!! This is a success notification
```
