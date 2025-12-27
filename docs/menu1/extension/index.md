# Extension

[TOC]

<https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown/>

<https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/>

## Abbreviations

The HTML specification
is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium

## Definitions

Apple
:   Pomaceous fruit of plants of the genus Malus in
    the family Rosaceae.

Orange
:   The fruit of an evergreen tree of the genus Citrus.

## Footnotes

Footnotes have a name, a reference[^1], and a definition[^word].

[^1]: This is a footnote definition.
[^word]: A footnote with the name "word".

## Task List

- [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
- [ ] Vestibulum convallis sit amet nisi a tincidunt
    * [x] In hac habitasse platea dictumst
    * [x] In scelerisque nibh non dolor mollis congue sed et metus
    * [ ] Praesent sed risus massa
- [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque

## Tables

| Method      | Description                          |
| ----------- | ------------------------------------ |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |

## Caption

Fruit      | Amount
---------- | ------
Apple      | 20
Peach      | 10
Banana     | 3
Watermelon | 1

/// caption
Fruit Count
///

## Detail

??? optional-class "Summary"
    Here's some content.

??? multiple optional-class "Summary"
    Here's some content.

???+ note "Open styled details"

    ??? danger "Nested details!"
        And more content again.

## Admonitions

!!! note

    This is note

!!! note "Custom title"

    This is note with custom title

!!! note "Outer Note"

    This is the outer note

    !!! note "Inner Note"

        This is the inner note

!!! note ""

    This is the note without title

??? note

    This is the collapsible note which is closed by default


???+ note

    This is the collapsible note which is open by default


!!! note

    note


!!! abstract

    abstract

!!! info

    info

!!! tip

    tip

!!! success

    success

!!! question

    question

!!! warning

    warning

!!! failure

    failure

!!! danger

    danger

!!! bug

    bug

!!! example

    example

!!! quote

    quote

## emoji

:smile: :heart: :thumbsup:

## Keys

++ctrl+alt+delete++

## Tabbed

=== "Tab 1"
    Markdown **content**.

    Multiple paragraphs.

=== "Tab 2"
    More Markdown **content**.

    - list item a
    - list item b

## Grids

<div class="grid cards" markdown>

- Card 1
- Card 2
- Card 3

</div>

<div class="grid cards" markdown>

-   Title 1

    ---

    Card 1

-   Title 2

    ---

    Card 2

-   Title 3

    ---

    Card 3

</div>

<div class="grid" markdown>

=== "Unordered list"

    * item 1
    * item 2
    * item 3

=== "Ordered list"

    1. item 1
    2. item 2
    3. item 3

``` title="Content tabs"
=== "Unordered list"

    * item 1
    * item 2
    * item 3

=== "Ordered list"

    1. item 1
    2. item 2
    3. item 3
```

</div>
