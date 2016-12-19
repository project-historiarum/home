![logo](initial-logo.png)
# Project Historiarum

Project Historiarum is an endeavor to bring historical pedagogy out from the 18th century, into the 21st. The intent is to create
better methods of teaching history and consuming historical content with the simplest and most powerful of tools out there: 
*code.*

## How did this start?

Web and mobile tech's being used to create newer pedagogical methods for natural sciences, language learning and more. But all along, historical learning has stayed the way it was two centuries ago - rote learning with absolutely **no** emphasis on a deeper understanding of historical events. This leads to a natural underappreciation for history's meaning in society, and its power as a dialectic tool - in many instances, it leads to a general distaste for all matters historical.

On a subliminal level, this project is all about exploring the deepest, darkest recesses of history, using more interactive methods as our flashlights. It's also about investigating the power and price of scholarly obsession with historial interests, and at what point historical content can be "democratized" without sacrificing its scholarly tones.

## What does this project entail?

At this point, Historiarum will be all about creating long-form writeups around very specific historical periods or themes, with interactive elements interspaced throughout the narrative, complementing it where needed. For now, these elements are limited to:

1. Timelines, allowing the reader to zoom into particular events with supporting rich media: images, audio/visual clips, documents.
2. Visualizations, which the reader can use to look at events with supporting datasets. Nothing like a data-backed story!

As can be inferred, Historiarum's an evolving experiment. Maybe at some point, standalone timelines and visualizations make a lot of sense. Maybe at some point, something else seems like **the thing** to work with. And that's the beauty of it - discovering what kind of tool enables scholarly history consumption with minimal barriers.

## What tech will be used?

This site is built using [docute](https://docute.js.org/), which was originaly intended for building quick documentation sites without builds. All the content here is written in Github-style Markdown, with a couple of extensions.

Timelines will be constructed using [TimelineJS3](https://github.com/NUKnightLab/TimelineJS3), which was built by the amazing folks at Northwestern University's [Knight Lab](https://knightlab.northwestern.edu/). Another tool that would be used heavily is the [OWID Grapher](https://github.com/OurWorldInData/owid-grapher), from [Our World In Data](https://ourworldindata.org/). In all fairness, this initial push behind Historiarum wouldn't be possible, if it weren't for these brilliant open source projects to back it all up.

From here, the next step would be to write a fair bit of code that can tie up all these pieces together for a more coherent narrative. This goal is a bit far off, and would take a few months to conceptualize and build. In all probability, Python would be the main language used, to build servers that would analyze datasets, and bring all the afore-mentioned tools together. And maybe some Javascript.

## Is there a timeline for this?

There's two roadmaps at play here: content and tech. These roadmaps don't have dates/deadlines attached to them, simply because it makes more sense to see what kind of effort goes into producing this kind of content and the technology to power it, before coming up with more concrete timelines.

### Content Roadmap

| Title  	|   Status	|
|---	|---	|
|  Germany after WWII - 1945 - 1955	|   Research	|
|   The Berlin Blockade & Airlift - 1948 - 1949	|   Research	|
|   The Berlin Wall - 1961 - 1989   |   Proposed    |
|   The Soviet invasion of Hungary - 1956	|   Proposed	|
|   The Prague Spring and subsequent Soviet invasion - 1967-1968 |   Proposed   |
|   Soviet Russia & Afghanistan - 1975 - 1989   |   Proposed   |
|   The collapse of the Soviet bloc - 1980 - 1991   |   Proposed   |

As can be gleaned from the plan above, the roadmap currently focuses on Cold War history. This is bound to change in the future, and if you have ideas to contribute, please do!

---

### Tech Roadmap

The tech roadmap is pretty simple. Since the current focus is on producing the right kind of content, tech is going to involve making use of whatever's open source, and suits the purpose. Gradually, a more custom platform will emerge, with anyone being able to contribute to it.

## Can I contribute?

Yes, please! If history and its intersection with tech excites you, please do ping me: rudraksh.mk@gmail.com.
