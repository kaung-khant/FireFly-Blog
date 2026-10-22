# FireFly — IoT & Embedded Systems

**Author / Pen name:** K4H  
**Copyright owner for this personal project:** KAUNG KHANT KO KO HAN

FireFly သည် IoT, Embedded Systems, Control Systems နှင့် Engineering Projects များအကြောင်း လေ့လာမှတ်စု၊ Tutorial နှင့် နည်းပညာဆောင်းပါးများကို မျှဝေရန် တည်ဆောက်ထားသော Blog ဖြစ်သည်။

## Content တင်နည်း

1. `content/posts/` ထဲတွင် `.md` ဖိုင်အသစ် ဖန်တီးပါ။
2. GitHub Website သို့မဟုတ် Mobile Browser မှ Markdown ကို ပြင်ဆင်ပြီး `main` branch သို့ Commit လုပ်ပါ။
3. GitHub Actions သည် Hugo ကို runner ပေါ်တွင် Build လုပ်ပြီး GitHub Pages သို့ Deploy လုပ်ပါမည်။

**Computer၊ Phone သို့မဟုတ် Tablet တွင် Hugo compiler ကို ကိုယ်တိုင် install လုပ်ရန် မလိုအပ်ပါ။**

## GitHub Pages Setup

1. ဖိုင်များကို GitHub Repository အသစ်တစ်ခုသို့ တင်ပါ။
2. `hugo.toml` ထဲရှိ `baseURL` ကို သင့် Pages URL အတိုင်း ပြင်ပါ။
   - Project site: `https://USERNAME.github.io/REPOSITORY/`
   - User site: `https://USERNAME.github.io/`
3. Repository → Settings → Pages → Build and deployment မှ Source ကို `GitHub Actions` ရွေးပါ။
4. `main` သို့ Commit လုပ်ပြီး Actions tab မှ Build/Deploy အခြေအနေကို စစ်ပါ။

## Post အသစ်ရေးနည်း

`content/posts/` ထဲတွင် `.md` ဖိုင်ဖန်တီးပြီး အောက်ပါ Front Matter ကို သုံးပါ။

```toml
+++
title = "ဆောင်းပါးခေါင်းစဉ်"
date = 2026-10-22T09:00:00+06:30
description = "အကြောင်းအရာ အကျဉ်းချုပ်"
tags = ["နည်းပညာ"]
draft = false
+++

# ဆောင်းပါးခေါင်းစဉ်

ဆောင်းပါးကို မြန်မာဘာသာဖြင့် ရေးပါ။
```

`draft = false` ဖြစ်မှ Public site တွင် ပေါ်မည်။ Commit လုပ်လိုက်သည်နှင့် GitHub Actions က Update လုပ်မည်။

## Brand နှင့် Author

- **FireFly** — လက်ရှိ Blog နှင့် IoT / Embedded Systems အကြောင်းအရာများ၏ အဓိက Brand။
- **K4H** — KAUNG KHANT KO KO HAN ၏ ကလောင်အမည်။
- **CSE-MM** — ယခု Blog ၏ Header/Primary Brand တွင် မသုံးထားပါ။ နောင် Community, Engineering Education သို့မဟုတ် CSR initiatives များအတွက် သီးခြားစဉ်းစားနိုင်သည်။

CSE-MM သည် လက်ရှိတွင် ဤ Blog ၏ တရားဝင်ကုမ္ပဏီပိုင်ရှင်ဟု မဆိုလိုပါ။ ကုမ္ပဏီအမည်/Trademark အခြေအနေကို သီးခြားစစ်ဆေးပြီးမှ တရားဝင်အသုံးပြုပါ။

## ဖိုင်ဖွဲ့စည်းပုံ

- `content/posts/` — Blog posts
- `layouts/` — Hugo templates
- `static/css/` — Responsive design
- `static/images/` — Logo assets
- `.github/workflows/deploy.yml` — Build/Deploy
- `hugo.toml` — Hugo configuration
- `LICENSE-MIT` — Code license
- `LICENSE-CONTENT.md` — Original articles license

Design သည် Soft Paper `#F7F7F5`, surface `#FFFFFF`, text `#111111`, border `#E5E5E3` နှင့် Ice BLUE accent ကို အခြေခံထားပြီး mobile/tablet များတွင် ဖတ်ရလွယ်အောင် ရည်ရွယ်ထားသည်။

## Licenses and Copyright

- **Code and software:** MIT License — see [`LICENSE-MIT`](./LICENSE-MIT).
- **Original articles and written educational content in `content/`:** Creative Commons Attribution 4.0 International (CC BY 4.0) — see [`LICENSE-CONTENT.md`](./LICENSE-CONTENT.md) and the [official license](https://creativecommons.org/licenses/by/4.0/).
- **Copyright owner for this personal project:** KAUNG KHANT KO KO HAN.
- **Author / pen name:** K4H.

CC BY 4.0 content reuse requires appropriate attribution, a link to the license, and an indication of changes made. The licenses above do not automatically cover logos, trademarks, third-party fonts, libraries, images, or other assets; check their individual notices and licenses.
