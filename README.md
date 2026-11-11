# 🛠️ 6 سيستمز بـ Claude تقدر تبنيها الويكند ده

<p align="center">
  <a href="#prompt"><img src="https://img.shields.io/badge/%E2%9A%A1%20GET%20THE%20PROMPT-COPY%20%26%20PASTE-F97316?style=for-the-badge" alt="خد الـ Prompt على طول" height="44"></a>
  <a href="#fill"><img src="https://img.shields.io/badge/%F0%9F%93%9D%20FILL%20YOUR%20DETAILS-NAME%20%C2%B7%20NICHE%20%C2%B7%20TEXT-2563EB?style=for-the-badge" alt="املا بياناتك" height="44"></a>
</p>

<p align="center"><b>👆 دوس على الزرار البرتقاني وهتروح للـ Prompt على طول — املا الخانات والصقه في Claude.</b></p>

الناس كلها بتتكلم عن الـ AI، بس قليل اللي بيبني بيه **سيستم شغال فعلاً** بيوفر وقت أو بيجيب فلوس.
هنا الـ 6 سيستمز اللي في الريل، كل واحد معاه: بيعمل إيه، الأدوات، الخطوات، والـ **Prompt** اللي تبدأ بيه مع Claude أو Claude Code.

> 💡 انسخ الـ Prompt زي ما هو، وغيّر بس الحاجات اللي بين `[ ]`.
> اختار **سيستم واحد بس** وابنيه الأسبوع ده. متبدأش الـ 6 مع بعض.

| # | السيستم | بيعمل إيه في سطر | الأدوات |
|---|---|---|---|
| 1 | WhatsApp agent | بيرد على العملاء في 30 ثانية ويحجزلهم | Claude + skill + GoHighLevel / n8n |
| 2 | Website builder | لينك Google Maps ← website جاهز live | Claude Code + أمر واحد + Netlify |
| 3 | Comment → DM | كلمة في الكومنتات ← DM فيه الملف | n8n + Instagram API + Facebook Pages |
| 4 | Facebook ads engine | يحلل إعلان ناجح ويعمل 4 نسخ جديدة | Ads Library + Claude + أداة صور AI |
| 5 | Video editor | يقطّع الفيديو ويحط captions و graphics | Claude Code + ffmpeg + Remotion |
| 6 | Personal assistant | ملخص الإيميل والكالندر كل يوم الصبح | Claude + Gmail/Calendar connectors |

---

## 🔌 الأول: جهّز الأدوات الأساسية

1. اعمل حساب على [Claude](https://claude.ai) — وللسيستمز 2 و 5 نزّل **Claude Code** ([الشرح الرسمي](https://docs.claude.com/en/docs/claude-code/overview)).
2. للسيستمز 1 و 3 هتحتاج **n8n** (Cloud أو على سيرفرك) وحساب **Meta for Developers** للـ WhatsApp / Instagram API.
3. لسيستم 6 وصّل Gmail و Calendar من الـ Connectors في Claude ([مساعدة Claude](https://support.claude.com)).

---

<a id="fill"></a>

## 📝 املا بياناتك الأول (مرة واحدة بس)

كل الـ Prompts تحت بتستخدم نفس الخانات دي، املاها مرة وانسخ.

| الخانة | تكتب فيها إيه | مثال |
|---|---|---|
| `[YOUR NAME]` | اسمك | Ahmed |
| `[BUSINESS NAME]` | اسم البيزنس | Serenoil |
| `[CONTENT TYPE]` | نوع البيزنس / النيش بتاعك | cold-pressed oils e-commerce |
| `[AUDIENCE]` | مين العملاء | women 25–45 in Egypt and the Gulf |
| `[LANGUAGE]` | لغة الردود والمحتوى | Egyptian Arabic |
| `[SYSTEM NUMBER]` | رقم السيستم اللي اخترته من الجدول | 3 |
| `[GOOGLE MAPS LINK]` | لينك المحل على Google Maps (سيستم 2) | https://maps.app.goo.gl/... |
| `[COMMENT KEYWORD]` | الكلمة اللي الناس تكتبها في الكومنتات (سيستم 3) | BUILD |
| `[RESOURCE LINK]` | اللينك اللي هيتبعت في الـ DM (سيستم 3) | https://github.com/... |
| `[COMPETITOR]` | براند منافس أو في نفس النيش (سيستم 4) | Brand X |
| `[VIDEO FILE]` | مسار الفيديو الخام (سيستم 5) | C:\videos\raw.mp4 |
| `[TIMEZONE]` | المنطقة الزمنية (سيستم 6) | Africa/Cairo |

<a id="prompt"></a>

### ⚡ Prompt واحد شامل — املا والصق

املا الخانات، الصقه في Claude Code (أو Claude)، وهو هيمشي معاك في بناء السيستم اللي اخترته خطوة بخطوة.

```
You are my senior AI automation engineer. Help me build ONE system this weekend.

Here are my details:
- Name: [YOUR NAME]
- Business: [BUSINESS NAME] — [CONTENT TYPE]
- Customers: [AUDIENCE]
- Language for anything customer-facing: [LANGUAGE]
- System I picked (number from the list below): [SYSTEM NUMBER]

The 6 systems:
1. WhatsApp agent — replies to every WhatsApp Business message in under 30 seconds and books the customer.
2. Website builder — takes a Google Maps link and builds a full website, ready to deploy on Netlify.
3. Comment → DM — when someone comments a keyword on my reel, they get a DM with a link automatically (n8n + Instagram API).
4. Facebook ads engine — finds a long-running ad in the Meta Ads Library, explains why it works, and writes 4 new ad variations.
5. Video editor — cuts silences, adds captions and simple graphics, exports a vertical reel.
6. Personal assistant — reads my inbox and calendar every morning and sends me a short daily brief.

Do this in order:
1. Explain in 3 lines what the system does for MY business specifically.
2. List every tool and account I need, marking which are free and which are paid.
3. Give me a numbered build plan (max 8 steps), smallest working version first.
4. Walk me through step 1 only, then wait for me to say "done" before the next step.
5. At the end, give me a test checklist.

Rules: never send messages, emails, posts or ads to real people without asking me first — use drafts and test accounts. Never put API keys inside code I might share; use environment variables. Keep explanations short and practical.
```

**بيعمل إيه؟** بيحوّل Claude لمهندس أتمتة جنبك: يفهم البيزنس بتاعك، يقولك الأدوات، ويبنيه معاك خطوة خطوة من غير ما يبعت أي حاجة لعملاء حقيقيين.

---

## 💬 السيستمز خطوة بخطوة

## 💬 1. WhatsApp agent

**بيعمل إيه:** بيرد على كل رسالة على WhatsApp البيزنس في أقل من 30 ثانية، يجاوب على الأسئلة المتكررة، ويحجز للعميل أو ياخد الأوردر.
**الأدوات:** Claude + skill فيها معلومات البيزنس + GoHighLevel. ولو عايز حاجة أرخص ومناسبة لمصر: **n8n + WhatsApp Cloud API**.

1. اكتب ملف معلومات البيزنس: المنتجات، الأسعار، المواعيد، الأسئلة المتكررة.
2. حوّله لـ skill أو System Prompt (الـ Prompt تحت).
3. اربط رقم الـ WhatsApp Business بالـ API (من Meta أو من GoHighLevel).
4. في n8n: Webhook ← AI Agent (Claude) ← رد على WhatsApp.
5. جرّب من رقم تاني قبل ما تفتحه للعملاء.

```
Write a system prompt for a WhatsApp customer-service agent for [BUSINESS NAME], a [CONTENT TYPE] business serving [AUDIENCE].

Requirements:
- Reply in [LANGUAGE], short and friendly, max 3 sentences per message.
- Answer only from the business info I paste below. If the answer isn't there, say a human will reply soon and tag the chat "NEEDS_HUMAN".
- When the customer wants to book or order, collect: name, phone, product/service, preferred time/address. Then output a JSON block {name, phone, item, time_or_address} for my automation to save.
- Never invent prices, discounts or delivery times.

Business info:
[paste your products, prices, hours, FAQ here]
```

**نصيحة:** خلّي أي حاجة فيها فلوس أو شكوى تتحول لإنسان. الـ Agent يرد ويجمع البيانات، وإنت تقفل البيعة.

---

## 🌐 2. Website builder

**بيعمل إيه:** تحط لينك Google Maps بتاع أي محل، يرجعلك website كامل ليه جاهز ينزل live.
**الأدوات:** Claude Code + أمر واحد + Netlify.

1. افتح فولدر فاضي وشغّل Claude Code فيه.
2. الصق الـ Prompt تحت بلينك المحل.
3. افتح `index.html` في المتصفح وراجع البيانات.
4. ارفع الفولدر على Netlify (Drag & drop في Netlify Drop، أو `netlify deploy`).

```
Build a complete one-page website for this business: [GOOGLE MAPS LINK]

Steps:
1. Ask me to paste the business name, address, phone, hours, category and 3–5 reviews from the Maps listing (don't guess anything you can't verify).
2. Build index.html + styles.css (no framework): hero with name and one-line promise, services/menu, reviews section, hours, a map embed, and a big WhatsApp/call button.
3. Write the copy in [LANGUAGE], for [AUDIENCE]. Mobile-first, fast, clean.
4. Use placeholder images from the business category only, clearly marked for replacement.
5. When done, tell me the exact steps to deploy the folder on Netlify.
```

**نصيحة:** ده سيستم بيتباع: اعمل website لمحل قريب منك ببلاش، ابعتهوله، واعرض عليه يخليه live بمبلغ بسيط.

---

## 📩 3. Comment → DM

**بيعمل إيه:** أي حد يكتب كلمة معينة تحت الريل، يوصله DM فيه الملف أو اللينك في ثانية… وإنت نايم. (ده نفس السيستم اللي هيبعتلك الرسالة دي 😉)
**الأدوات:** n8n + Instagram Graph API + Facebook Pages API.

1. حوّل حساب Instagram لـ Business/Creator واربطه بصفحة Facebook.
2. اعمل App على Meta for Developers واشترك في webhook الـ `comments`.
3. في n8n: Webhook ← IF (الكومنت فيه الكلمة) ← رد على الكومنت ← Private Reply بالـ DM.
4. جرّب بحساب تاني، مش بحسابك.

```
Help me build an Instagram "comment keyword → DM" automation in n8n.

- Keyword: [COMMENT KEYWORD] (also match lowercase and the Arabic spelling).
- When someone comments it on any of my reels: reply publicly to the comment with a short thank-you in [LANGUAGE], then send them a private reply (DM) with this link: [RESOURCE LINK].
- Ignore comments from my own account so it doesn't loop.

Give me: the Meta app permissions and webhook fields I need, the n8n node chain with each node's settings, the exact Graph API request for the private reply, and how to test it safely with a second account. Don't hard-code tokens; use n8n credentials.
```

**نصيحة:** الملف اللي في الـ DM لازم يكون مفيد بجد، لو الناس حسّت إنه فاضي مش هيكتبوا تاني.

---

## 📈 4. Facebook ads engine

**بيعمل إيه:** يلاقي إعلان شغال وكسبان بقاله شهور، يفهم ليه ناجح، ويعمل 4 إعلانات جديدة لبيزنسك.
**الأدوات:** [Meta Ads Library](https://www.facebook.com/ads/library) + Claude + Higgsfield (أو أي أداة صور/فيديو بالـ AI).

1. افتح الـ Ads Library ودوّر على [COMPETITOR] أو كلمة في نيشك.
2. اختار إعلانات **شغالة بقالها أكتر من شهرين** (الإعلان الخسران بيتقفل بسرعة).
3. خد screenshot أو انسخ النص وابعته لـ Claude بالـ Prompt تحت.
4. استخدم الـ Image prompts في أداة الصور، وارفع الإعلانات **كمسودة** في Meta Ads.

```
I'm attaching ads from [COMPETITOR] that have been running for 2+ months in the Meta Ads Library.

1. For each ad, explain in 3 bullets why it probably works: hook, offer, visual, emotion.
2. Find the common pattern across them.
3. Write 4 new ad variations for [BUSINESS NAME] ([CONTENT TYPE]) targeting [AUDIENCE], in [LANGUAGE]. Each with: primary text (max 125 characters), headline, CTA button, and an image/video prompt I can paste into an AI image tool.
4. Do NOT copy their wording — keep the pattern, change everything else.

These are drafts for me to review; don't publish anything.
```

**نصيحة:** متنسخش الإعلان، انسخ **الفكرة**: نوع الـ hook وشكل العرض.

---

## 🎬 5. Video editor

**بيعمل إيه:** بيقطّع السكتات من الفيديو، يحط captions و graphics، ويطلّعلك reel جاهز للنشر.
**الأدوات:** Claude Code + ffmpeg + Remotion (و Whisper للـ captions).

1. نزّل ffmpeg و Node.js على جهازك.
2. افتح فولدر فيه الفيديو وشغّل Claude Code.
3. الصق الـ Prompt، وخليه يعمل الخطوات واحدة واحدة.
4. راجع الـ preview قبل الـ render النهائي.

```
I want a reusable video-editing pipeline for my reels. Input: [VIDEO FILE] (talking head, vertical).

1. Use ffmpeg to detect and cut silences longer than 0.4s; keep a short padding so words aren't clipped.
2. Transcribe the cut video (Whisper or similar) and save word-level timestamps. The speech is in [LANGUAGE].
3. Build a Remotion project that plays the cut video with big, word-by-word captions (max 3 words on screen, safe area for Instagram UI) and simple pop-up text graphics for key numbers.
4. Render 1080x1920, 30fps, MP4.
5. Make it a single command I can rerun on any new video.

Show me the plan first, then build step by step. Don't delete my original file.
```

**نصيحة:** أول مرة هتاخد وقت، بس بعد كده كل reel جديد هياخد أمر واحد.

---

## ☀️ 6. Personal assistant

**بيعمل إيه:** يمسك الـ inbox بتاعك، يشيك على الكالندر، ويسلّمك ملخص يومك كل يوم الصبح قبل ما تصحى.
**الأدوات:** Claude + Gmail و Calendar connectors + شوية skills.

1. وصّل Gmail و Google Calendar من الـ Connectors في Claude.
2. الصق الـ Prompt تحت وجرّبه يدوي كام يوم.
3. لما يعجبك، اعمله Scheduled task (أو workflow في n8n) يشتغل كل يوم الساعة 7 الصبح ويبعتلك على Telegram أو الإيميل.

```
You are my personal assistant. My name is [YOUR NAME], I run [BUSINESS NAME]. Timezone: [TIMEZONE].

Every morning:
1. Read my Gmail from the last 24 hours. Group emails into: 🔴 needs my reply today, 🟡 can wait, ⚪ newsletters/noise. For each 🔴 email: sender, one-line summary, and what they need from me.
2. Check my Google Calendar for today and tomorrow: list meetings with time, who, and one prep note each. Flag any clashes.
3. Give me the top 3 things to focus on today.
4. For each 🔴 email, write a short reply as a DRAFT in Gmail. Do NOT send anything.

Write the brief in [LANGUAGE], max 15 lines, scannable.
```

**نصيحة:** خليه **Draft only** دايماً. إنت اللي تدوس Send.

---

## 🇪🇬 تقدر تكتبله بالمصري كمان

```
إنت مهندس أتمتة شاطر وهتساعدني أبني سيستم واحد الويكند ده.
أنا اسمي [اسمك]، وعندي بيزنس [اسم البيزنس] شغال في [نوع البيزنس]، والعملاء بتوعي [مين العملاء].
عايز أبني سيستم رقم [رقم السيستم] من الـ 6 سيستمز.
اشرحلي الأول هيفيدني بإيه، وقولي الأدوات اللي محتاجها ببلاش ولا بفلوس، وبعدين امشي معايا خطوة خطوة، ومتبعتش أي حاجة لعملاء حقيقيين من غير ما تسألني.
```

---

## ⚠️ نصايح مهمة

- **Draft only**: أي سيستم بيبعت رسايل أو إيميلات أو إعلانات، خليه يعمل مسودة الأول لحد ما تثق فيه.
- **جرّب بحساب تاني**: الـ WhatsApp و Instagram جرّبهم من رقم أو حساب تاني، مش على العملاء.
- **المفاتيح سرّ**: متحطش الـ API keys أو الـ tokens في كود بتشاركه أو في screenshot.
- **ابدأ صغير**: أصغر نسخة شغالة الأول، وبعدين زوّد.
- **لو هتصوّر**: اعمل blur على أسماء العملاء والإيميلات وأرقام التليفون.

---

## 🚀 الخلاصة

| قبل | بعد |
|---|---|
| بترد على WhatsApp بإيدك طول اليوم | Agent بيرد في 30 ثانية ويحجز |
| بتبعت الملفات للناس واحد واحد | كلمة في الكومنتات ← DM أوتوماتيك |
| بتقعد ساعات تقطّع فيديو | أمر واحد ← reel جاهز |
| بتصحى على 50 إيميل | ملخص 15 سطر فيه المهم بس |

---
لو استفدت، تابعني عشان فيه سيستمز وأتمتة أكتر جاية 🔥

**Steven Ayman — Vida AI**
