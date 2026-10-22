+++
title = "ဖုန်းတစ်လုံးနဲ့ Blog ကို Update လုပ်နိုင်တဲ့ Workflow"
date = 2026-10-20T09:00:00+06:30
description = "Hugo ကို ဖုန်းမှာ install မလုပ်ဘဲ Markdown နဲ့ GitHub Actions သုံးပြီး Blog အသစ်ထုတ်ဝေပုံ။"
tags = ["Hugo", "GitHub", "Workflow"]
draft = false
+++

Static Site Generator တစ်ခုကို အသုံးပြုတယ်ဆိုတာ Content ရေးတဲ့ Device မှာ Build Tool ကို မဖြစ်မနေ install လုပ်ရမယ်လို့ မဆိုလိုပါဘူး။

ဒီ Project မှာ Content ရေးသားခြင်းနဲ့ Website build လုပ်ခြင်းကို သီးခြားခွဲထားပါတယ်။

```text
01  Write Markdown
        |
        v
02  Commit to GitHub
        |
        v
03  GitHub Actions runs Hugo
        |
        v
04  Deploy to GitHub Pages
```

## လုပ်ဆောင်ရမည့် အဆင့်များ

- GitHub မှာ `content/posts/` directory ကို ဖွင့်ပါ။
- `.md` ဖိုင်အသစ် ဖန်တီးပါ၊ သို့မဟုတ် ရှိပြီးသားဖိုင်ကို ပြင်ပါ။
- Front Matter မှာ `draft = false` သတ်မှတ်ပါ။
- `main` branch သို့ Commit လုပ်ပါ။
- GitHub ရဲ့ **Actions** tab မှ Build/Deploy ရလဒ်ကို ကြည့်ပါ။

## အားသာချက်များ

- Phone/Tablet တွင် Hugo install လုပ်စရာမလိုပါ။
- Content သည် Markdown အဖြစ် သိမ်းဆည်းထားနိုင်သည်။
- Git history မှ ပြောင်းလဲမှုများကို ပြန်ကြည့်နိုင်သည်။
- Build failure ဖြစ်ပါက Action log မှ အကြောင်းရင်းကို စစ်ဆေးနိုင်သည်။

GitHub Pages မှာ Website ကို Public လုပ်မည့်အခါ Repository ရဲ့ **Settings → Pages → Source: GitHub Actions** ကို သတ်မှတ်ထားဖို့ မမေ့ပါနှင့်။
