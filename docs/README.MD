# MAASL-scriptinglanguage documentary

## What is MAASL how does it work and differ from other languages?

Okay, so I was working on something and got a little out of my focus, so being distracted I started browsing a bit and I landed upon [a Reddit post on r/ZeroNet](https://www.reddit.com/r/zeronet/comments/fklzbv/how_to_translate_zeronet_to_another_language/), the post was titled '*How to translate ZeroNet to another language?*', an easy to answer question, just go to the GitHub repository and add the documentary files for your language, but the question made me have this huge idea:

A scripting language that can do (human)language translations automatically, and can be used in different ways, like, it can be a real (programming) script, but also a markup language. Not like PHP, but actually like itself.

Instead of loading or installing modules like for example [Python](https://docs.python.org/3/tutorial/modules.html), MAASL will have multiple modes, allowing to change how the code processor reads the code, and possible to download and run modes. It might even be possible for MAASL to transfer these modes over decentralized networks like for example [ZeroNet](https://zeronet.io/) using the [081Zeronet communications plugin](https://github.com/0810-Software/0810Zeronet-plugin-win).

## Scripting in MAASL

Since MAASL is not alike other languages, the syntax and commands are not definable, they change per mode. But they can still be documented here ​​😉.

### [Internals](./INTERNALS/)

Okay, the internals are an exception, the internals are pre-processed without the mode to get in between, which means they are predefined and necessary to learn as a basis.

