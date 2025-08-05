# Homoglyph Chat Filter Bypass – Responsible Disclosure (MineFun.io)
![Topic](https://img.shields.io/badge/Topic-Bug_Bounty-ff0004?style=plastic)
![Type](https://img.shields.io/badge/Type-Chat_Filter_Bypass-blue?style=plastic)
![Method](https://img.shields.io/badge/Method-Homoglyph-9300FF?style=plastic)
![Target](https://img.shields.io/badge/Target-MineFun.io-D3FF00?style=plastic)


## 🔍 Summary
Found a bug in [MineFun.io](https://minefun.io) where offensive words could bypass the chat filter using homoglyphs

## 🧠 What Happened
Using [Homoglyph Attack Generator](https://www.irongeek.com/homoglyph-attack-generator.php), I changed the word `idiot` into `idioΤ` (Greek capital tau at the end).

Result: `idioΤ` successfully bypassed the profanity filter and was shown publicly in the in-game chat.

---
## ✅ Proof & Reward
Below is a screenshot of the acknowledgment:
<img src="https://github.com/obitouka/minefun.io-homoglyph-bypass/blob/main/img/proof.png" width="700" />

A **video proof showing the exact steps** that was shared in the [bugs](https://discord.com/channels/1242473396818935859/1402164667966558310/1402171100846227577) channel.  
<a href="https://github.com/obitouka/minefun.io-homoglyph-bypass/blob/main/video/homoglyph.mp4">
  <img src="https://github.com/obitouka/minefun.io-homoglyph-bypass/blob/main/img/demo-preview.png" width="200" />
</a>


## 📩 Disclosure
The issue was responsibly reported on **August 5, 2025** in MineFun.io’s official Discord `#bugs` channel.

- 🧾 **Public Report Thread:**  
  https://discord.com/channels/1242473396818935859/1402164667966558310/1402171100846227577
  
- 🏆 **Rewarded:** 300 Minebucks (≈ ₹500 as per the game's market value)  
  ([Severity: Critical](https://discord.com/channels/1242473396818935859/1319321791965040723/1319323191981637652))
