+++
title = "Control System မှတ်စုများကို စနစ်တကျ ရေးသားခြင်း"
date = 2026-10-21T09:00:00+06:30
description = "Technical notes တွေကို Markdown၊ equation နဲ့ table တွေသုံးပြီး ပြန်လည်ရှာဖွေရလွယ်ကူအောင် စီမံပုံ။"
tags = ["Control System", "နည်းပညာ", "မှတ်စု"]
draft = false
math = true
+++

Control System ဆိုင်ရာ လေ့လာမှုတွေမှာ equation တစ်ခုတည်းထက် အဲဒီ equation ရဲ့ ယူဆချက်၊ parameter အဓိပ္ပာယ်နဲ့ အသုံးချနိုင်တဲ့ အခြေအနေတွေကိုပါ မှတ်တမ်းတင်ထားဖို့ လိုပါတယ်။

## State-space model

Linear time-invariant system တစ်ခုကို အောက်ပါပုံစံဖြင့် ဖော်ပြနိုင်ပါတယ်။

$$
\\dot{x}(t) = Ax(t) + Bu(t)
$$

$$
y(t) = Cx(t) + Du(t)
$$

ဒီနေရာမှာ \(x(t)\) သည် state vector၊ \(u(t)\) သည် control input၊ \(y(t)\) သည် output ဖြစ်ပါတယ်။ \(A\), \(B\), \(C\), \(D\) တို့က system matrices များဖြစ်ပါတယ်။

## Parameter များ

| သင်္ကေတ | အဓိပ္ပာယ် | မှတ်ချက် |
|---|---|---|
| \(x\) | State vector | စနစ်၏ အတွင်းအခြေအနေကို ဖော်ပြသည် |
| \(u\) | Control input | စနစ်ထဲသို့ ထည့်သွင်းသော input |
| \(y\) | Output | တိုင်းတာလိုသော output |
| \(A\) | State matrix | State dynamics ကို ဖော်ပြသည် |
| \(B\) | Input matrix | Input သည် state ကို မည်သို့ သက်ရောက်သည်ကို ဖော်ပြသည် |

## မှတ်စုရေးသားရာတွင် လိုက်နာရန်

1. Equation တစ်ခုချင်းစီအတွက် symbol များကို ရှင်းပြပါ။
2. Unit နှင့် sign convention ကို မှတ်တမ်းတင်ပါ။
3. Assumption များကို သီးခြားဖော်ပြပါ။
4. Simulation result သို့မဟုတ် diagram ထည့်ပါက caption နှင့် alt text ပါဝင်စေပါ။
5. Source/reference ရှိပါက သက်ဆိုင်ရာ link ကို ထည့်ပါ။

> မှတ်ချက် — ဒီစာမျက်နှာမှာ `math = true` ဟု သတ်မှတ်ထားသောကြောင့် MathJax ကို load လုပ်ရန် ပြင်ဆင်ထားသည်။
