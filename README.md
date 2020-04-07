# MAASL-scriptinglanguage Project Readme
 Marnix Adaptive All-around Scripting Language, MAASL (pronounce: maasél) for short.

## This readme.md file contains:

[The MAASL project status and planning](#the-maasl-project-status-and-planning)

[What is MAASL?](#what-is-maasl)

[How it will work](#how-it-will-work)

## The MAASL project status and planning

 **Writing documentation (step <font color="aqua">1</font>/7)**

Instead of beginning to write code for the processor, I'll start writing example scripts and a proper documentation and then start creating something that understands them, this will make the idea and workflow more clear.

The process of creating MAASL:

<font color="aqua">1</font>. Creating documentation. (Started)

<font color="red">2</font>. Writing example scripts. (Started)

<font color="purple">3</font>. Creating a system that enables databases and makes locating and downloading modes. (Not started)

<font color="green">4</font>. Start designing and building a terminal that will accept MAASL commands. (Not started)

<font color="brown">5</font>. Create and document a concept of how MAASL will look/be in detail. (Not started)

<font color="gold">6</font>. Create and release a first release of MAASL. (Not started)

<font color="lime">7</font>. Start writing a learning guide. (Not started)


## What is MAASL?

Okay, so I was working on something and got a little out of my focus, so being distracted I started browsing a bit and I landed upon [a Reddit post on r/ZeroNet](https://www.reddit.com/r/zeronet/comments/fklzbv/how_to_translate_zeronet_to_another_language/), the post was titled '*How to translate ZeroNet to another language?*', an easy to answer question, just go to the GitHub repository and add the documentary files for your language, but the question made me have this huge idea:

A scripting language that can do (human)language translations automatically, and can be used in different ways, like, it can be a real (programming) script, but also a markup language. Not like PHP, but actually like itself.

## How it will work

Instead of loading or installing modules like for example [Python](https://docs.python.org/3/tutorial/modules.html), MAASL will have multiple modes, allowing to change how the code processor reads the code, and possible to download and run modes. It might even be possible for MAASL to transfer these modes over decentralized networks.

### Internals

MAASL will have some internals that are handled before the modes can read them, these internals will be listed in [INTERNALS.MD](docs/INTERNALS/index.md).
