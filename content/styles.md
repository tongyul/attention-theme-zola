+++
title = "Bold, Italics, and More"
date = "2024-05-01"
+++

# **Bold**, *Italics*, and More

{{ tocAnchor(label="Contents :3") }}

## IMPORTANT

**Bolds** and *italics* by default changes the color of the text instead of the
style. Click the `BI` [^mono] button to toggle.

[^mono]: There's ```monospace``` text right before the footnote!!!

[^bquo]: Likewise, there's a `> blockquote` below that doesn't mention itself
    as a block quote.

And yeah… because Zola supports it, I also made it so that you can add more
content after footnotes.

[Link](https://www.youtube.com/watch?v=dQw4w9WgXcQ) colors follow the headings,
~~but as a check of consistency, they should always be underlined. If they're
not, that's treated as a
[bug](https://github.com/tongyul/attention-theme-zola/issues).~~ I think this
is solved now that I realized Safari refuses to support
`text-decoration-thickness` shorthand.

> You can insert table-of-contents anywhere using the shortcode `{{ tocAnchor()
> }}` (and for section contents, use `{{ pagesAnchor()
> }}`); these support a `label` string argument that becomes, yes, a label.
>
> Currently, `label` is very restricted and can't have styling or HTML yet.

{{ tocAnchor(label="Contents Again :33") }}
