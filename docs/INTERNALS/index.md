# Documentation > MAASL-internals

## What are internals?

Instead of loading or installing modules like for example [*Python*](https://docs.python.org/3/tutorial/modules.html), MAASL will have multiple modes, allowing to change how the code processor reads the code, and possible to download and run modes. It might even be possible for MAASL to transfer these modes over decentralized networks.

MAASL will have some internals that are handled before the modes can read them, *these work in **all** modes*.

## List of MAASL-internals

| internal name or command | function of internal                                    |
| ------------------------ | ------------------------------------------------------- |
| [. (the dot)](./dot/)    | The dot is used to switch modes or working directories. |
| [var](./var/)            | Set variables or change mode settings.                  |

