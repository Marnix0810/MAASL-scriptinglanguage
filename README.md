# MAASL-scriptinglanguage Project Readme
 Marnix Adaptive All-around Scripting Language, MAASL (pronounce: maa-sél) for short.

## This readme.md file contains:

[What is MAASL?](#What-is-MAASL?)

[How to start writing the processor?](#How-to-start-writing-the processor?)

[How it will work]()

## What is MAASL?

Okay, so I was working on something and got a little out of my focus, so being distracted I started browsing a bit and I landed upon [a Reddit post on r/ZeroNet](https://www.reddit.com/r/zeronet/comments/fklzbv/how_to_translate_zeronet_to_another_language/), the post was titled '*How to translate ZeroNet to another language?*', an easy to answer question, just go to the GitHub repository and add the documentary files for your language, but the question made me have this huge idea:

A scripting language that can do (human)language translations automatically, and can be used in different ways, like, it can be a real (programming) script, but also a markup language. Not like PHP, but actually like itself.

## How to start writing the processor?

Instead of beginning to write code for the processor, I'll start writing example scripts and a proper documentation and then start creating something that understands them, this will make the idea and workflow more clear.

## How it will work

Instead of loading or installing modules like for example [Python](https://docs.python.org/3/tutorial/modules.html), MAASL will have multiple modes, allowing to change how the code processor reads the code, and possible to download and run modes. It might even be possible for MAASL to transfer these modes over decentralized networks.

### Internals

MAASL will have some internals that are handled before the modes can read them, these internals will be listed in [INTERNALS.MD](docs/INTERNALS.MD)