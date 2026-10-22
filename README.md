# Hugo မြန်မာ Blog

Hugo နှင့် GitHub Pages ကို အသုံးပြုသော မြန်မာဘာသာ Blog ဖြစ်သည်။

## Content တင်နည်း

1. `content/posts/` ထဲတွင် `.md` ဖိုင်အသစ် ဖန်တီးပါ။
2. GitHub Website သို့မဟုတ် Mobile Browser မှ Markdown ကို ပြင်ဆင်ပြီး `main` branch သို့ Commit လုပ်ပါ။
3. GitHub Actions သည် Hugo ကို runner ပေါ်တွင် Build လုပ်ပြီး GitHub Pages သို့ Deploy လုပ်ပါမည်။

**သင့် Computer၊ Phone သို့မဟုတ် Tablet တွင် Hugo/SSG Compiler Install လုပ်ရန် မလိုအပ်ပါ။**

## GitHub Pages Setup

1. ဖိုင်များကို GitHub Repository အသစ်တစ်ခုသို့ တင်ပါ။
2. `hugo.toml` ထဲရှိ `baseURL` ကို သင့် Pages URL အတိုင်း ပြင်ပါ။
   - Project site: `https://USERNAME.github.io/REPOSITORY/`
   - User site: `https://USERNAME.github.io/`
3. Repository → Settings → Pages → Source တွင် `GitHub Actions` ကို ရွေးပါ။
4. `main` သို့ Commit လုပ်ပြီး Actions tab မှ Build/Deploy ကို စစ်ပါ။

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

## ဖိုင်ဖွဲ့စည်းပုံ

- `content/posts/` — Blog posts
- `layouts/` — Hugo templates
- `static/css/` — Design
- `.github/workflows/deploy.yml` — Build/Deploy
- `hugo.toml` — Hugo configuration

Design သည် Soft Paper `#F7F7F5`, surface `#FFFFFF`, text `#111111`, border `#E5E5E3` နှင့် Ice BLUE Aura accent ကို အခြေခံထားသည်။
