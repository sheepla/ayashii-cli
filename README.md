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

DEPENDENCE
    - curl  Required for API calls.

API
    Using this API. thanks!: https://cjp.sbmr.in/api/raw
    To see more info about this API, visit: https://cjp.sbmr.in/about/

REPO
    Repository:      https://github.com/sheepla/ayashii-cli
    Author: sheepla  https://github.com/sheepla
    Licence:         MIT
```

## Installation

### Depandences

The following command is required.

- `curl` : Required for API calls

### Install ayashii-cli

Just download and add execution permission.

```bash
curl -O https://raw.githubusercontent.com/sheepla/ayashii-cli/master/ayashii && chmod +x ayashii
```

### One Liner Edition

```bash
curl -s -X GET https://cjp.sbmr.in/api/raw/$(od -tx1 -An <<< "これは正しい日本語です！" | tr ' ' % | tr -d \\n )

```

## Thanks

This tool using this API. Thanks! 🥳 `https://cjp.sbmr.in/api/raw/{TEXT}`

To see more info about this API, visit: [https://cjp.sbmr.in/about/](https://cjp.sbmr.in/about/)
