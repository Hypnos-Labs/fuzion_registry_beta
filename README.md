# **Fuzion Market Registry**

```
├─ fuzion_registry_beta
│   ├─ cw20
│   │   ├─ info.json
│   │   ├─ logos
│   │   |   ├─ x.png
│   │   |   ├─ ...
│   ├─ native
│   │   ├─ info.json
│   │   ├─ logos
│   │   |   ├─ y.png
│   │   |   ├─ ...
│   ├─ nft
│   │   ├─ info.json
│   │   ├─ logos_banners
│   │   |   ├─ z_logo.png
│   │   |   ├─ z_banner.png
│   │   |   ├─ ...
└──
```

# **How to add your project's information**

### **Guidelines**
✔️ Feel comfortable [asking questions](https://discord.gg/juno) if you need help!

✔️ Add your awesome project!

❌ Do not edit anyone elses project

❌ Do not add more than 1 project per pull request


### [Video tutorial](https://youtu.be/8BDJMUDS3gU)


### **Quick Start**

- Fork this repo
- Add your project's info and logo
    - Follow the specified structures **exactly**
- Submit a pull request once your info has been added
- Your submission will be reviewed as soon as possible! :tada:

---

## **CW20 Tokens**

### **Project Info**

This needs to be added to the end of `./cw20/info.json`

Check out the existing entries or video tutorial if you need some guidance

_Example Project_
```js
{
    // Contract address of the CW20 token
    "contract_address": "juno1xyz...",
    // Name of the project
    "name": "Good Project DAO",
    // Display name of the token
    "token_symbol": "GPDAO",
    // Token Decimals (typically 6)
    "decimals": 6,
    // OPTIONAL: Website Link (use "NONE" for no link)
    "website": "https://beta.fuzion.market",
    // OPTIONAL: Howl Social Link (use "NONE" for no link)
    "howl_link": "NONE",
    // OPTIONAL: Twitter Page Link (use "NONE" for no link)
    "twitter_link": "https://twitter.com/FuzionMarket"
}
```

### **Project Logo**

Your logo image should be a 500x500 PNG that is named **exactly** the same as your `contract_address`

For exampe, if your cw20 contract address is `juno1xyz`, then the name of your logo needs to be `juno1xyz.png`

*PNG is currently the only file type supported*

Now simply add your logo to the `./cw20/logos` folder and you're good to go!

</br>

---

## **Native Tokens**

### **Project Info**

This needs to be added to the end of `./native/info.json`

Check out the existing entries or video tutorial if you need some guidance

_Example Project_

```js
{
    // Name of the project
    "name": "Juno Network",
    // Display name of the token
    "token_symbol": "JUNO",
    // Token Denom (If this is an IBC denom, use the IBC hash: ibc/AB123...)
    "token_denom": "ujuno",
    // Token Decimals (typically 6)
    "decimals": 6,
    // OPTIONAL: Website Link (use "NONE" for no link)
    "website": "NONE",
    // OPTIONAL: Howl Social Link (use "NONE" for no link)
    "howl_link": "NONE",
    // OPTIONAL: Twitter Page Link (use "NONE" for no link)
    "twitter_link": "https://twitter.com/JunoNetwork"
}
```

### **Project Logo**

Your logo image should be a 500x500 PNG that is named **exactly** the same as your `token_denom`

For exampe, if your token denom is `ujuno`, then the name of your logo needs to be `ujuno.png`

**Note:** If you are adding an IBC denom, your logo file should be named the name of the IBC hash *excluding* the `ibc/` prefix. So `ibc/ABC123` would be named `ABC123.png` 

*PNG is currently the only file type supported*

Now simply add your logo to the `./native/logos` folder and you're good to go!

</br>

---

## **NFTs**

### **Project Info**

This needs to be added to the end of `./nft/info.json`

Check out the existing entries or video tutorial if you need some guidance

_Example Project_
```js
{
    // Contract address of the NFT collection
    "contract_address": "juno1zhe5k4hwh56ql09g05en9nj6gc9cr3hz2xvd8xpg3zaattkeflpqt90yp7",
    // Name of the project
    "name": "Neon Peepz",
    // Short description for the project, maximum 200 characters
    "description": "Little neon dudes with weapons",
    // 0-3 Keywords for the project, see "Tag List" below for available Keywords
    // Use an empty array for None (are you sure you don't want to add some tags?)
    // "tags": [],
    "tags": [
        "Gaming",
        "Metaverse"
    ],
    // Symbol for the collection
    "symbol": "NEONPEEPZ",
    // OPTIONAL: Website Link (use "NONE" for no link)
    "website": "https://beta.fuzion.market/",
    // OPTIONAL: Howl Social Link (use "NONE" for no link)
    "howl_link": "NONE",
    // OPTIONAL: Twitter Page Link (use "NONE" for no link)
    "twitter_link": "https://twitter.com/FuzionMarket"
}
```

### Tag List

Choose 0-3 Tags that best describe what your project is all about. This will help with Search optimization and let potential collectors know what you're building!

If you think we're missing a Tag, feel free to make a PR and let us know

<details>
<summary>Available Tags</summary>
<br>
- "Art"
- "Charity"
- "Comics"
- "Fashion"
- "Fitness"
- "Gambling"
- "Gaming"
- "Literature"
- "Memes"
- "Metaverse"
- "Music"
- "Nature"
- "NSFW"
- "Photography"
- "Real Estate"
- "Sports"
</details>

### **Project Logo**

Your logo image should be a 500x500 PNG that is named **exactly** the same as your `contract_address`, followed by `_logo`

For example, if your collection's contract address is `juno1xyz`, then the name of your logo needs to be `juno1xyz_logo.png`

*PNG is currently the only file type supported*

Now simply add your logo to the `./nft/logos_banners` folder and you're good to go!

### **Project Banner**

Adding your project banner is very similar to your logo. The banner image should be a 1500x500 PNG that is named **exactly** the same as your `contract_address`, followed by `_banner`

For example, if your collection's contract address is `juno1xyz`, then the name of your logo needs to be `juno1xyz_banner.png`

*PNG is currently the only file type supported*

Now simply add your logo to the `./nft/logos_banners` folder and you're good to go!