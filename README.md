# 🗾 ayashii-cli

<div align="right">
    <img src="https://img.shields.io/static/v1?label=Language&message=shell&color=blue&style=flat-square"/>
    <img src="https://img.shields.io/static/v1?label=License&message=MIT&color=blue&style=flat-square"/>
</div>

通常ゐ亍キヌ卜を怪レい日本语に変换レまず.

## Usage

```bash
ayashii -- AYASHII NIHONGO CLI: Convert from normal Japanese text to AYASHII NIHONGO.

USAGE
    ayashii [OPTIONS] TEXT...
        ayashii TEXT        # read from arguments
        echo TEXT | ayashii # read from pipe
        ayashii -s <<< TEXT # read from stdin
        ayashii --help      # show this help

EXAMPLES
    $ ayashii これは正しい日本語です！
    これは正レい日本语てず！
    $ echo これは正しい日本語です！ | ayashii
    これは正レい日本语てず！

OPTIONS
    -s      read from stdin
    --help  show this help

REPO
    Repository:      https://github.com/sheepla/ayashii-cli
    Author:          sheepla (https://github.com/sheepla)
    Licence:         MIT

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

This tool utilises this dictionaries. Thanks! 🥳

[cjp.js/dict at master · Submarinonline/cjp.js](https://github.com/Submarinonline/cjp.js/tree/master/dict)
