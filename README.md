# 🗾 ayashii-cli

<div align="right">
    <img src="https://img.shields.io/static/v1?label=Language&message=shell&color=blue&style=flat-square"/>
    <img src="https://img.shields.io/static/v1?label=License&message=MIT&color=blue&style=flat-square"/>
</div>

通常ゐ亍キヌ卜を怪レい日本语に変换レまず.

## Usage

```
ayashii -- AYASHII NIHONGO CLI: Convert from normal Japanese text to AYASHII NIHONGO.

USAGE
    ayashii TEXT        # from arguments
    echo TEXT | ayashii # from stdin
    ayashii --help      # Show this help.

EXAMPLE
    $ ayashii これは正しい日本語です！
    これは正レい日本语てず！
    $ echo これは正しい日本語です！ | ayashii
    これは正レい日本语てず！

REPO
    Repository:      https://github.com/sheepla/ayashii-cli
    Author: sheepla  https://github.com/sheepla
    Licence:         MIT
```

## Installation

### Install ayashii-cli

Just download and add execution permission.

```bash
curl -L https://git.io/JcdpT -o ayashii && chmod +x ayashii
```

## Thanks

This tool using this dictionaries. Thanks! 🥳 [cjp.js/dict at master · Submarinonline/cjp.js](https://github.com/Submarinonline/cjp.js/tree/master/dict)
