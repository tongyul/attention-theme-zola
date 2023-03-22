+++
title = "/"
template = "section.html"
+++

# Zola Attention Theme

***Attention** is a Zola theme dedicated to helping the reader focus their
attention.* I as the author of the **Attention** theme ~~definitely doesn't
personally experience absolutely bleak and crippling attention issues that
almost failed me a course in college-level writing~~ have some ideas about how
to combat attention issues via document formatting, such as enlarged character
spacing, font-choice, elimination of hard-to-read bolds, distinct styles for
text and listing… and that's the basis for the **Attention** theme. ~~(You
don't really need to pay full attention right now to my rambling as I'm just
testing the SASS).~~

## Second-Level Heading

I guess you might have been confused by all that you've just seen. What ~~the
fuck~~ are these colors? Where are the **bolds** and *italics*? **Attention**
avoid font variations in order to preserve readability, but instead exploit
color difference; unfortunately, this would also mean that the theme is not
usable if one has the particular color blindness—oh well, but the colors are
always customizable ~~actually not yet~~. (Here is some `\texttt{}` please
enjoy.) ([Links are de-emphasized.](/))

<button onclick="set_dark(false);">Light theme</button>
<button onclick="set_dark(true);">Dark theme</button>
<button onclick="document.body.classList.toggle('try-retina');">Toggle `try-retina`</button>
(Retina-resolution currently isn't any different.)

`just some code (still in-line tho)`

just some text

`just some very very very very very very very very very very very very very very very very long in-line code`

```bash
$ echo "Actual code that is not in-line"
$ echo "I haven't figured out how to make syntax highlighting not look nasty in light mode."
$ echo "Oh well, at least they're horizontally scrollable."
```

You can get italics from `<i></i>` if you *really* need to modify the font
style, but *do you*? EDIT: `<cite></cite>` has been unitalicized and given a
different color (<cite>Myself, 2023</cite>). This helps the reader skip
long-and-wordy citations as well as focus on them when necessary.

> Winners win, losers lose.
>
> —<cite>My high-school biology teacher</cite>

$${
\def\i {\mathbfit{i}}
\frac{-\hbar^2}{2m}\frac{\partial^2\Psi}{\partial x^2}+V(x)=\i\hbar\frac{\partial\Psi}{\partial t}
}$$

### Third-Level Heading

This is a stub-text paragraph that tries very hard to make itself look very long
and full of content yet still struggles to fill up even just three lines. But
actually, I don't want it long, so that I can fit more headings into the same
screenshot.

#### Fourth-Level Heading

This is a stub-text paragraph that tries very hard to make itself look very long
and full of content yet still struggles to fill up even just three lines. But
actually, I don't want it long, so that I can fit more headings into the same
screenshot.

##### Fifth-Level Heading

This is a stub-text paragraph that tries very hard to make itself look very long
and full of content yet still struggles to fill up even just three lines. But
actually, I don't want it long, so that I can fit more headings into the same
screenshot.

###### Sixth-Level Heading

This is a stub-text paragraph that tries very hard to make itself look very long
and full of content yet still struggles to fill up even just three lines. But
actually, I don't want it long, so that I can fit more headings into the same
screenshot.

## To-do

- [ ] Images
- [ ] Extended stuff like footnotes
- [ ] To-do lists
- [ ] Lists in general
- [ ] Tables
- [ ] Math(?)
