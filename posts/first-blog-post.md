---
title: SCAVENGER HUNT
published_at: 2024-07-24
snippet: first day of class
disable_html_sanitization: true
allow_math: true
---

# 
## An Exploding Coffee
![test](IMG_7490.jpg)

We immediately went to one of the coffee shops in campus because to our understanding, there was nothing else or no other place that made sense.

## A basement-dwelling black box, bigger than you might think
![image](pic2.jpg)

This one was really confusing and we didn't manage to find a black box but we saw this study space that looked like a big black box. 

## A book containing digital media wisdom, found amongst many 
![image](pic3.jpg)
This was quite challenging for us as we were all new to campus and we didn't know our way around the library but we tried our best to find a book that was somewhat related to digital media.

## A wide net strung above, bulging under the weight of its flying paper cargo
![image](pic4.jpg)
We actually had to get a librarian's help to find this because we didn't understand this task at all.

## The disembodied hands of a great ape
![image](pic5.jpg)
We actually saw another group from our class take a picture here and we found that it made the most sense to the "hands of a great ape"

## A study space fit for a Sith Lord 
![image](pic6.jpg)
One of our group members actually knew this place so she led us directly to this study space which was pretty cool.

## A door for the condemned 
![image](pic7.jpg)
Another group actually helped us with this one because we didn't have any clue on what this meant.

## A golden globe atop of tower of eights
![image](pic8.jpg)
This one was really funny because we were looking everywhere for a golden globe but never found it and we saw this golden oval shaped thingy on top so we decided to just go with it.

## A wide machine, dispensing beverages from a far away land
![image](pic9.jpg)
When we saw "dispensing beverages" we immediately thought of the vending machine.

## A curtain of roots, delivered by a winged visitor
![image](pic10.jpg)
We were very confused with this and we had to rush back to class so we found this place that had roots.


![a drippy lemon](logo.svg)

^ images are written like this: `![description](file_path/file_name.png)`

## This is h2

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


