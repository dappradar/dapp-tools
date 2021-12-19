# Dapp tools

---

A collection of dapp tools that are displayed on DappRadar dapp pages

[![Defi Kingdom tools](https://i.imgur.com/zKIA7YA.png "Defi Kingdom tools")](https://dappradar.com/harmony/games/defi-kingdoms)

## How to submit a tool

---

1. Fork this repository
2. Add tools to `tools.json`
3. Make a pull request

## Editing `tools.json`

---

#### Variables

---
### Dapp 
* `slug` *(required)* - slug of the dapp on DappRadar. 
  * Example: slug for `https://dappradar.com/harmony/games/defi-kingdoms` is `defi-kingdoms`

### Tool
* `name` *(required)*
* `url` *(required)*
* `description` *(required)*
* `image`
* `authorName`
* `social` (array)
  * `type` (Website, Twitter, etc.)
  * `url`

#### Example
```
{
    "slug": "defi-kingdoms",    
    "tools": [
        {
            "title": "Freak's Axie Extension",
            "url": "http://url-to-extension.com",
            "image": "http://image-url.com",
            "description": "An extension to help you play Axie Infinity. It shows number of breeds, HP, speed, purity, and pending exp",
            "social": [
                {
                    "type": "Website",
                    "url": "https://freakitties.github.io/axie/"
                }
            ],
            "authorName": "freak#0001"
        }
        {
            "title": "...",
        }
    ]
}
```

## Help

---

Our community is here to help! Ask around:
* [Discord](https://discord.gg/4ybbssrHkm)
* [Telegram](https://t.me/joinchat/GdhNjQ8PMhCZ_a0CZutmXg)
* [Twitter](https://twitter.com/dappradar)

