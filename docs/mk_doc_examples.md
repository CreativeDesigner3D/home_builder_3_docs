#MkDoc Examples

## Adding Text with Link

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Adding an Image

![Image title](https://github.com/CreativeDesigner3D/home_builder_3_docs/assets/34818078/f570ec79-264f-4e53-84f0-3e4e5d4dbe2c){ align=left }

## Adding an Image with a Caption

<figure markdown>
  ![Image title](https://github.com/CreativeDesigner3D/home_builder_3_docs/assets/34818078/f570ec79-264f-4e53-84f0-3e4e5d4dbe2c){ width="600" }
  <figcaption>Image caption</figcaption>
</figure>

## Adding a Table

First Header | Second Header | Third Header
:----------- |:-------------:| -----------:
Left         | Center        | Right
Left         | Center        | Right

## Highlighting Text

My `highlighted` text goes here.

## Code

A plain codeblock:

``` py
#Some code here
def my_function():
    value = 0
    return True
```

A codeblock with a title:

``` py title="my_script.py"
#Some code here
def my_function():
    value = 0
    return True
```

A codeblock with line numbers:

``` py linenums="1"
#Some code here
def my_function():
    value = 0
    return True
```

A codeblock with highlighted numbers:

``` py hl_lines="2 3 6"
#Some code here
def my_function():
    value = 0
    value = 1
    value = 2
    value = 3
    value = 4
    value = 0
    return True
```

## Icons and Emojs

:smile:

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }

## Admonition

Simple Admonition

!!! note
    This is an important bit of text

Admonition with Title

!!! note "Title"
    This is an important bit of text

Admonition Warning

!!! warning "Title"
    This is an important bit of text  

Admonition inline end with Title

!!! note inline end "Title"
    This is an important bit of text that will be displayed to the right of the text that you have below.

This text will be inline with the previous admonition. Remove the end keyword to make the admonition display before this text   

## Buttons

[This is a Button](https://www.mkdocs.org){ .md-button }
[This is a Button with an Icon :fontawesome-solid-paper-plane:](https://www.mkdocs.org){ .md-button }

## Tabs

Regular Tabs

=== "Unordered List 1"

    * Sed sagittis eleifend rutrum
    * Donec vitae suscipit est
    * Nulla tempor lobortis orci
    

=== "Ordered List 2"

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

Tabs in a admonition

!!! example

    === "Unordered List"

        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
        

    === "Ordered List"

        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci

## Adding Lines

Here is some text

---

Here is some more text

## Task List

- [x] This is a checked box
- [ ] This is an unchecked box

## Definition List

`Definition 1`

:   This is the text to add as the definition.

`Definition 2`

:   Aliquam metus eros, pretium sed nulla venenatis, faucibus auctor ex. Proin
    ut eros sed sapien ullamcorper consequat. Nunc ligula ante.

    Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
    Nam vulputate tincidunt fringilla.
    Nullam dignissim ultrices urna non auctor.