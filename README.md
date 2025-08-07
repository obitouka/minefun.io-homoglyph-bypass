# Homoglyph Chat Filter Bypass (MineFun.io)
![Topic](https://img.shields.io/badge/Topic-Bug_Bounty-ff0004?style=plastic)
![Type](https://img.shields.io/badge/Type-Chat_Filter_Bypass-blue?style=plastic)
![Method](https://img.shields.io/badge/Method-Homoglyph-9300FF?style=plastic)
![Target](https://img.shields.io/badge/Target-MineFun.io-D3FF00?style=plastic)


## ✅ Expected Behavior:
When a user writes a offensive word in [MineFun.io](https://minefun.io) in-game chat, the system blocks it and shows error: `"it's not appropriate for the game."`

## ❌ Actual Behavior:
Using [Homoglyph Attack Generator](https://www.irongeek.com/homoglyph-attack-generator.php), I changed the word `idiot` into `idioΤ`(Unicode U+03A4 at the end) and it bypassed  the profanity filter in the in-game chat and showed it publicly

---

## ✅ Proof & Reward
Screenshot of the acknowledgment:  
<img src="https://github.com/obitouka/minefun.io-homoglyph-bypass/blob/main/img/proof.png" width="700" />

**Video proof** showing the exact steps to bypass that was shared in the Discord [bugs](https://discord.com/channels/1242473396818935859/1402164667966558310/1402171100846227577) channel.  
<a href="https://github.com/obitouka/minefun.io-homoglyph-bypass/blob/main/video/homoglyph.mp4">
  <img src="https://github.com/obitouka/minefun.io-homoglyph-bypass/blob/main/img/demo-preview.png" width="200" />
</a>


## 📩 Disclosure
The issue was responsibly reported on **August 5, 2025** in MineFun.io’s official Discord `#bugs` channel.

- 🧾 **Public Report Thread:**  
  https://discord.com/channels/1242473396818935859/1402164667966558310/1402171100846227577
  
- 🏆 **Rewarded:** 300 Minebucks (≈ ₹500 as per the game's market value)  
  ([Severity: Critical](https://discord.com/channels/1242473396818935859/1319321791965040723/1319323191981637652))
