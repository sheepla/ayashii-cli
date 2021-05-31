# ayashii-cli

通常ゐ亍キヌ卜を怪レい日本语に変换レまず.

## Usage

```
ayashii -- AYASHII NIHONGO cli

USAGE
    ayashii TEXT   # Convert from normal Japanese text to AYASHII NIHONGO.
    ayashii --help # Show this help.

EXAMPLE
    $ ayashii これは正しい日本語です！
    これは正レい日本语てず！

DEPENDENCE
    - curl  Required for API calls.
API
    This tool using this API. thanks!:       https://cjp.sbmr.in/api/raw
    To see more info about this API, visit:  https://cjp.sbmr.in/about/

REPO
    Repository:      https://github.com/sheepla/ayashii-cli
    Author: sheepla  https://github.com/sheepla
    Licence:         MIT
```

## Installation

### Depandences

The following command is required.

- curl : Required for API calls
- [nkf](https://osdn.net/projects/nkf/) : *Network Kanji Filter* Required for URL encoding.

### Install ayashii-cli

Just download and add execution permission.

```bash
curl -O https://raw.githubusercontent.com/sheepla/ayashii-cli/master/ayashii && chmod +x ayashii
```

### One Liner Edition

```bash
curl -s -X GET https://cjp.sbmr.in/api/raw/$(nkf -WwMQ <<< 'これは正しい日本語です' | sed 's/=$//g' | tr = % | tr -d \\n)
```

## Thanks

This tool using this API. Thanks! 🥳 `https://cjp.sbmr.in/api/raw/{TEXT}`

To see more info about this API, visit: [https://cjp.sbmr.in/about/](https://cjp.sbmr.in/about/)
