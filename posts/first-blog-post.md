---
title: First Exploration & Adventure
published_at: 2024-07-24
snippet: Summing up our first week of university, welcoming opportunities for adventures and fun!
disable_html_sanitization: true
allow_math: true
---

# Scavanger Hunt Around RMIT

## An Explosive Cup Of Coffee
![Coffee](Coffee.jpeg)

Through insider knowledge, and bit of curiosity we head outside of RMIT building to stumble upon a small cafe, "Little bang". The unique logo of a steaming cup of joe inside a silhouette of a bomb creates an explosive cup of coffee suitable to tick this off the list.

^ images are written like this: `![description](file_path/file_name.png)`

## A Book Containing Digital Media Wisdom, Found Amongst Many
![Books](Book.jpeg)

With a little help and a lot of patience, we followed instructions from the guardians of the library to follow a trail leading to the designated book that holds the key to all digital media wisdom.

## A Wide Net Strung Above, Bulging Under the weight of its flying paper cargo
![Cargo](Cargo.jpeg) 

Hanging right above our heads all these times, stealthy watching over everyone passing by, you will only notice it when you look up or when you see things from a higher perspective... *Hint from the library window*


## A Curtain Of Roots, Delivered By A Winged Wisitor
![Roots](Roots.jpeg)

A random pop up wall, covered with growing tree roots, amost magnificent to look at, something you wouldn't expect a small tiny space corner with no much reason behind it's growth... Well sometimes its better to keep your nose away and enjoy the beauty of nature.

## A Door For The Condemned
![Gateway](Gate.jpeg)

A majestic gateway to put the condemned behind... Walking out of the gateway give you a taste of freedom, with the lights shining upon you as if the gods are giving you a permission to be free once again from all your responsibilities...

## A Study Space Fit For A Sith Lord
![Sith Lord](Sith.jpeg)

A daunting place of study, enveloped by futuristic seat and table design making you feel as if you are Darth Vader emerging from his meditation chamber... *Spookyyy*

## The Disembodied Hands Of A Great Ape
![Gorilla](Gorilla.jpeg)

Is it an ape? or a gorilla? Well we never got the answers to that during the scavanger hunt, thougt it made a great comfy seat for Dash!

## A Basement-dwelling Black Box, Bigger That You Might Think
![Black Box](Box.jpeg)

Honestly, at first we are kinda looking for a "*physical box*" but at a ridiculouse size... But we are told by some fellow students that the Black Box we are looking for is the room right behind us... Sooo... YEEPIE!


## A Wide Machine, Dispensing Beverages From A Far Away Land
![Vending Machine](Vending.jpeg)

A seemingly unlimited source of beverages... still wondering where those drinks come from?

## A Golden Globe Atop A Tower Of Eights
![Golden Globe](Globe.jpeg)

Wasn't The Golden Globe I had in mind when first hearing about it(*Was thinking of the Korean Golden Globe Awards*)...But let me tell you it is A "GRAND STATUE OF THE GOLDEN GLOBE" it is majestic in the clear sky and sunlight reflecting of it... *P.S To the person who made this scavanger hunt it's very cheeky of you this one is tough... But aint enough for us*

# Footage Of Morning Rush In A Highrise Environment:

# Cheeky Selfie Edit

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


