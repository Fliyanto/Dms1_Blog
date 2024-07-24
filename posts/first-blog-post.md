---
title: First Exploration & Adventure
published_at: 2024-07-24
snippet: Summing up our first week of university, welcoming opportunities for adventures and fun!
disable_html_sanitization: true
allow_math: true
---

# Scavanger Hunt Around RMIT

## An Explosive Cup Of Coffee
![Coffee](static/logo.svg)

Through insider knowledge, and bit of curiosity we head outside of RMIT building to stumble upon a small cafe, "Little bang". The unique logo of a steaming cup of joe inside a silhouette of a bomb creates an explosive cup of coffee suitable to tick this off the list

^ images are written like this: `![description](file_path/file_name.png)`

## A Book Containing Digital Media Wisdom, Found Amongst Many
![Books](static/Book.jpeg)

With a little help and a lot of patience, we followed instructions from the guardians of the library to follow a trail leading to the designated book that holds the key to all digital media wisdom.

## A Wide Net Strung Above, Bulging Under the weight of its flying paper cargo
![description](static/Cargo.jpeg) 




## A Curtain Of Roots, Delivered By A Winged Wisitor

## A Door For The Condemned

## A Study Space Fit For A Sith Lord

## The Disembodied Hands Of A Great Ape

## A Basement-dwelling Black Box, Bigger That You Might Think

## A Wide Machine, Dispensing Beverages From A Far Away Land

## A Golden Globe Atop A Tower Of Eights

*This is italic.*[^1]

[^1]: This is a footnote, *which can also be italic*.

**This is bold.**

Hyperlinks can be written like this: `[text](https://URL)`

You can find a markdown cheat-sheet [here](https://www.markdownguide.org/cheat-sheet/).

## Maths:

... which can be written inline, like this: $\{ x, y, z \} \in \N$

... or block, like this:

$$ x^2 + y^2 = z^2 $$

Visit [ $\KaTeX$ ](https://katex.org/docs/supported#fractions-and-binomials) for more information about writing maths.

## Embedding video:

<iframe id="coding_train_video" src="https://www.youtube.com/embed/rI_y2GAlQFM?si=RDgjkpunxk1mQzMI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<script type="module">

    console.log (`hello world! 🚀`)

    const iframe  = document.getElementById (`coding_train_video`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16

</script>

## Embedding p5 sketches:

<iframe id="falling_falling" src="https://editor.p5js.org/capogreco/full/Fkg05m7aA"></iframe>

<script type="module">

    const iframe  = document.getElementById (`falling_falling`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16 + 42

</script>

## Canvas API

<canvas id="canvas_example"></canvas>

<script type="module">
    const cnv = document.getElementById (`canvas_example`)
    cnv.width = cnv.parentNode.scrollWidth
    cnv.height = cnv.width * 9 / 16

    const ctx = cnv.getContext (`2d`)
    const pos = {
        x: -100,
        y: cnv.height / 2 - 50
    }
    
    function draw_frame () {
        ctx.fillStyle = `turquoise`
        ctx.fillRect (0, 0, cnv.width, cnv.height)

        ctx.fillStyle = `hotpink`
        ctx.fillRect (pos.x, pos.y, 100, 100)

        pos.x += 2

        if (pos.x > cnv.width) {
            pos.x = -100
        }

        requestAnimationFrame (draw_frame)
    }

    draw_frame ()
</script>


