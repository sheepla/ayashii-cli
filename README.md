# πΎ ayashii-cli

<div align="right">
    <img src="https://img.shields.io/static/v1?label=Language&message=shell&color=blue&style=flat-square"/>
    <img src="https://img.shields.io/static/v1?label=License&message=MIT&color=blue&style=flat-square"/>
</div>

ιεΈΈγδΊγ­γεγζͺγ¬γζ₯ζ¬θ―­γ«ε€ζ’γ¬γΎγ.

## Usage

```
ayashii -- AYASHII NIHONGO CLI: Convert from normal Japanese text to AYASHII NIHONGO.

USAGE
    ayashii [OPTIONS] TEXT...
        ayashii TEXT        # read from arguments
        echo TEXT | ayashii # read from pipe
        ayashii -s <<< TEXT # read from stdin
        ayashii --help      # show this help

EXAMPLES
    $ ayashii γγγ―ζ­£γγζ₯ζ¬θͺγ§γοΌ
    γγγ―ζ­£γ¬γζ₯ζ¬θ―­γ¦γοΌ
    $ echo γγγ―ζ­£γγζ₯ζ¬θͺγ§γοΌ | ayashii
    γγγ―ζ­£γ¬γζ₯ζ¬θ―­γ¦γοΌ
    $ ayashii -s <<< γγγ―ζ­£γγζ₯ζ¬θͺγ§γοΌ
    γγγ―ζ­£γ¬γζ₯ζ¬θ―­γ¦γοΌ

OPTIONS
    -s --stdin  read from stdin
    --help      show this help

REPO
    Repository:      https://github.com/sheepla/ayashii-cli
    Authors:         sheepla (https://github.com/sheepla)
                     eggplants (https://github.com/eggplants)
    License:         MIT

DICT
    This tool utilises this dictionaries. thanks!
    https://github.com/Submarinonline/cjp.js/tree/master/dict
```

## Installation

### Local install

```bash
curl -L https://git.io/JcdpT -o ayashii && chmod +x ayashii
```

### Global install

To enables to run `ayashii` command anywhere.

```bash
curl -L https://git.io/JcdpT -o ayashii && sudo install -m 755 ayashii /usr/local/bin/ayashii
```

## Thanks

This tool utilises this dictionaries. Thanks! π₯³

[cjp.js/dict at master Β· Submarinonline/cjp.js](https://github.com/Submarinonline/cjp.js/tree/master/dict)

