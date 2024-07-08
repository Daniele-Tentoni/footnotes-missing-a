# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

Here there is the first footnote[^1], correctly rendered.

<table>
<tr>
<td>
Here we are inside a table.
</td>
<td>I need to put a footnote here[^2].</td>
</tr>
<tr>
<td>
But it doesn't work.
</td>
<td>
It doesn't get parsed from HTML to Markdown if inside a HTML tag.
</td>
</tr>
<td>
The third works<sup id="fnref:3"><a class="footnote-ref" href="#fn:3">3</a></sup>.
</td>
<td>
Because I've rendered it manually.
</td>
</table>

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

I get more space.

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

[^1]: First footnote, correctly rendered.

[^2]: The second one footnote content is correctly rendered, but not the label.

[^3]: This one works.
