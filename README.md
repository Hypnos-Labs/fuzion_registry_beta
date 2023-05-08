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
└──
```

</br>

# **How to add your project's information**

### **Guidelines**
✔️ Feel comfortable [asking questions](https://discord.gg/juno) if you need help!

✔️ Add your awesome project!

❌ Do not edit anyone elses project

❌ Do not add more than 1 project per pull request


### **Video tutorial**
[Video Tutorial]

### **Quick Start**

- Fork this repo
- Add your project's info and logo
    - Follow the specified structures **exactly**
- Submit a pull request once your info has been added
- Your submission will be reviewed within 48 hours :tada:

---

## **CW20 Tokens**

### **Project Info**

This needs to be added to the end of `./cw20/info.json`

Check out the existing entries or video tutorial if you need some guidance

_Example Project_
```json
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

```json
{
    // Name of the project
    "name": "Juno Network",
    // Display name of the token
    "token_symbol": "JUNO",
    // Token Denom (This must match EXACTLY what is on chain!)
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

*PNG is currently the only file type supported*

Now simply add your logo to the `./native/logos` folder and you're good to go!

</br>

---

## **NFTs**

NFT submissions are not available yet, check back soon!