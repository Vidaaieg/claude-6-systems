# 🛠️ 6 سيستمز بـ Claude تقدر تبنيها الويكند ده

<a id="top"></a>

<p align="center">
  <a href="#s1"><img src="https://img.shields.io/badge/%F0%9F%92%AC%201.%20WHATSAPP%20AGENT-GET%20THE%20PROMPT-25D366?style=for-the-badge" alt="1. WhatsApp agent" height="40"></a>
  <a href="#s2"><img src="https://img.shields.io/badge/%F0%9F%8C%90%202.%20WEBSITE%20BUILDER-GET%20THE%20PROMPT-0EA5E9?style=for-the-badge" alt="2. Website builder" height="40"></a>
</p>
<p align="center">
  <a href="#s3"><img src="https://img.shields.io/badge/%F0%9F%93%A9%203.%20INSTAGRAM%20COMMENT%20TO%20DM-GET%20THE%20PROMPT-DD2A7B?style=for-the-badge" alt="3. Instagram Comment to DM" height="40"></a>
  <a href="#s4"><img src="https://img.shields.io/badge/%F0%9F%93%88%204.%20FACEBOOK%20ADS%20ENGINE-GET%20THE%20PROMPT-1877F2?style=for-the-badge" alt="4. Facebook ads engine" height="40"></a>
</p>
<p align="center">
  <a href="#s5"><img src="https://img.shields.io/badge/%F0%9F%8E%AC%205.%20VIDEO%20EDITOR-GET%20THE%20PROMPT-7C4DFF?style=for-the-badge" alt="5. Video editor" height="40"></a>
  <a href="#s6"><img src="https://img.shields.io/badge/%E2%98%80%EF%B8%8F%206.%20PERSONAL%20ASSISTANT-GET%20THE%20PROMPT-EA4335?style=for-the-badge" alt="6. Personal assistant" height="40"></a>
</p>
<p align="center">
  <a href="#prompt"><img src="https://img.shields.io/badge/%E2%9A%A1%20NOT%20SURE%3F-ALL%20IN%20ONE%20PROMPT-F97316?style=for-the-badge" alt="مش عارف تختار؟ الـ Prompt الشامل" height="40"></a>
</p>

<p align="center"><b>👆 دوس على زرار السيستم اللي عايزه وهتروح لخطواته والـ Prompt بتاعه على طول — الصقه في Claude، وهو هيسألك وإنت تجاوب.<br>مش عارف تختار؟ دوس على البرتقاني وClaude هيختارلك.</b></p>

الناس كلها بتتكلم عن الـ AI، بس قليل اللي بيبني بيه **سيستم شغال فعلاً** بيوفر وقت أو بيجيب فلوس.
هنا الـ 6 سيستمز اللي في الريل، وكل سيستم معاه: تفتح إيه، تلصق إيه، وClaude **هيسألك أسئلة عن البيزنس بتاعك** الأول، وبعدين يبنيه معاك خطوة بخطوة.

> 💡 **مفيش خانات تملاها.** انسخ الـ Prompt زي ما هو والصقه. Claude هو اللي هيسألك عن اسمك والبيزنس والعملاء، ولو مش عارف إجابة قوله "مش عارف" وهو هيقترح عليك الأنسب.
> اختار **سيستم واحد بس** وابنيه الأسبوع ده. متبدأش الـ 6 مع بعض.

---

## 🧠 إزاي كل Prompt هنا شغال؟

كل Prompt مقسوم لـ 3 مراحل، عشان Claude ميبنيش حاجة عامة مش مناسبة ليك:

| المرحلة | Claude بيعمل إيه | إنت بتعمل إيه |
|---|---|---|
| 1️⃣ Interview | يسألك 2–3 أسئلة في كل رسالة عن البيزنس والأدوات اللي عندك | تجاوب بالمصري عادي |
| 2️⃣ Plan | يلخّص إجاباتك في جدول ويقولك خطة البناء | تراجع وتكتب **go** |
| 3️⃣ Build | يبني خطوة واحدة، ويقولك تجربها إزاي، ويستنى | تجرّب وتكتب **done** |

---

## 🔌 الأول: افتح Claude Code صح (للسيستمز 1، 2، 3، 5)

1. نزّل **Claude Code** من [الشرح الرسمي](https://docs.claude.com/en/docs/claude-code/overview) (محتاج اشتراك Claude Pro أو أعلى، أو API key).
2. افتح الـ Terminal واعمل فولدر جديد للسيستم:
   ```bash
   mkdir my-system
   cd my-system
   claude
   ```
3. الصق الـ Prompt بتاع السيستم ودوس Enter.

> 🛡️ **نصيحة:** لو عايز Claude يوريك الخطة الأول من غير ما يعدّل أي ملف، دوس `Shift + Tab` لحد ما يظهر **plan mode** تحت.

السيستمز 4 و 6 مش محتاجين Claude Code، بيشتغلوا على [claude.ai](https://claude.ai) عادي.

---

<a id="fill"></a>

## 🧭 اختار السيستم بتاعك

| # | السيستم | بيعمل إيه في سطر | الأدوات اللي في الفيديو | تفتح فين |
|---|---|---|---|---|
| 1 | [💬 WhatsApp agent](#s1) | بيرد على العملاء في 30 ثانية ويحجزلهم | Claude + a skill + GoHighLevel | Claude Code |
| 2 | [🌐 Website builder](#s2) | لينك Google Maps ← website جاهز live | Claude Code + one command + Netlify | Claude Code |
| 3 | [📩 Comment → DM](#s3) | كلمة في الكومنتات ← DM فيه الملف | n8n + Instagram API + Facebook Pages | Claude Code |
| 4 | [📈 Facebook ads engine](#s4) | إعلان ناجح ← 4 إعلانات جديدة ليك | Ads Library + Claude + Higgsfield | claude.ai |
| 5 | [🎬 Video editor](#s5) | فيديو خام ← reel جاهز بالـ captions | Claude Code + ffmpeg + Remotion | Claude Code |
| 6 | [☀️ Personal assistant](#s6) | ملخص الإيميل والكالندر كل يوم الصبح | Claude + Gmail/Calendar connectors + skills | claude.ai |

مش عارف تختار؟ خد الـ Prompt الشامل اللي تحت، وClaude هيسألك ويختارلك.

---

<a id="prompt"></a>

## ⚡ Prompt واحد شامل — Claude يختارلك ويبنيه معاك

**▶️ الخطوات:**
1. افتح Claude Code في فولدر جديد (زي ما فوق)، أو [claude.ai](https://claude.ai) لو لسه مش عارف هتبني إيه.
2. الصق الـ Prompt ده.
3. جاوب على أسئلته، وهو هيرشحلك سيستم واحد ويبدأ يبنيه.

```
You are my senior AI automation engineer and a patient teacher. I'm not a developer. Your job: help me pick ONE of the 6 systems below and build a working first version this weekend.

The 6 systems:
1. WhatsApp agent: replies to every message on my real WhatsApp Business number in under 30 seconds, answers FAQs, and books the customer. (Claude + a skill + GoHighLevel, or n8n + WhatsApp Cloud API)
2. Website builder: I give a Google Maps link of any business, I get a full website ready to go live. (Claude Code + one custom command + Netlify)
3. Comment to DM: anyone who comments a keyword under my reel gets a DM with a file or link automatically. (n8n + Instagram API + Facebook Pages)
4. Facebook ads engine: find an ad that has been running for months in the Meta Ads Library, explain why it wins, and create 4 new ads for my business. (Ads Library + Claude + an AI image tool)
5. Video editor: cut silences from my raw video, add captions and simple graphics, export a vertical reel. (Claude Code + ffmpeg + Remotion)
6. Personal assistant: read my inbox and calendar and give me a short brief every morning. (Claude + Gmail/Calendar connectors + a skill)

PHASE 1: INTERVIEW (do not build anything yet)
Ask me questions in small groups (max 3 per message) and wait for my answers. Cover:
- My name, my business, what I sell, and who my customers are.
- Where I lose the most time every week, and where I lose sales or leads.
- Which tools and accounts I already have (WhatsApp Business, Instagram Business, Facebook Page, Gmail, n8n, Netlify, a computer that can run Claude Code).
- My budget for paid tools (zero is a valid answer).
- What language my customers speak (for anything customer-facing).
If I answer "I don't know", recommend the best option for a small business in Egypt or the Gulf and explain why in one line.

PHASE 2: RECOMMEND AND PLAN
Recommend the ONE system that gives me the biggest win for the least setup, and say why in 3 lines. Then show:
- A table of my answers.
- Every tool I need, marked free or paid.
- A build plan of max 8 steps, smallest working version first.
Wait for me to type "go".

PHASE 3: BUILD STEP BY STEP
Do one step at a time. After each step tell me: what you did, how I test it, and what I should see. Then wait for me to type "done". If something fails, ask me to paste the exact error.

RULES
- Talk to me in Egyptian Arabic, keep tool names and tech terms in English.
- Never send messages, emails, posts or ads to real people without asking me first. Use drafts, test numbers and test accounts.
- Never put API keys or tokens inside files I might share. Use environment variables or the tool's credentials manager, and tell me where to paste them myself.
- Don't invent facts about my business. Ask.
- Finish with a test checklist and the 3 next improvements.
```

**بيعمل إيه؟** بيحوّل Claude لمهندس أتمتة قاعد جنبك: يسألك عن البيزنس، يختارلك أكتر سيستم هيفرق معاك، ويبنيه معاك خطوة خطوة من غير ما يبعت حاجة لعملاء حقيقيين.

---

## 💬 السيستمز واحد واحد

<a id="s1"></a>

## 💬 1. WhatsApp agent

**بيعمل إيه:** بيرد على كل رسالة على WhatsApp البيزنس الحقيقي في 30 ثانية، وبعدين يحجز للعميل.
**الأدوات (زي الفيديو):** Claude + skill فيها كل معلومات البيزنس + GoHighLevel متوصل بالـ WhatsApp.
**بديل أرخص ومناسب لمصر:** n8n + WhatsApp Cloud API من Meta. Claude هيسألك إنت عندك إيه ويمشي على الأنسب.

**▶️ الخطوات:**
1. جهّز في ملف أو في دماغك: المنتجات أو الخدمات، الأسعار، المواعيد، العنوان، وأكتر 10 أسئلة العملاء بيسألوها.
2. افتح Claude Code في فولدر جديد اسمه `whatsapp-agent`.
3. الصق الـ Prompt تحت وجاوب على أسئلته.
4. هيعملك الـ skill، ويجرّب معاك 10 محادثات وهمية **قبل** ما يتوصل بأي رقم حقيقي.
5. بعد ما الردود تعجبك، يمشي معاك في التوصيل بـ GoHighLevel أو n8n، وتجرّب من رقم تاني.

```
You are a senior conversational-AI engineer. Together we'll build a WhatsApp agent for my business: it replies to every customer message on my real WhatsApp Business number in under 30 seconds, answers questions, and books the customer.
Stack from the video: Claude + a skill that holds my business knowledge + GoHighLevel connected to WhatsApp. Cheaper alternative if I don't have GoHighLevel: n8n + WhatsApp Cloud API.

PHASE 1: INTERVIEW (do not build yet)
Ask me in small groups (max 3 questions per message) and wait for my answers:
1. Business name, what I sell, city/area, and who my customers are.
2. What does "booking" mean for me: appointment, table reservation, order with delivery, or a call with sales? What details must you collect (name, phone, date/time, address, product, quantity)?
3. My prices, opening hours, delivery areas and fees, and payment methods (ask me to paste them, or paste my menu/price list).
4. The 10 questions customers ask most, and my usual answers.
5. Tone: formal or friendly? Which dialect (Egyptian, Gulf)? Emojis yes or no?
6. When must the bot hand over to a human (complaints, discounts, custom orders, angry customers)? Who gets notified and how?
7. Do I already have GoHighLevel, n8n, or a WhatsApp Business API number? If not, recommend the simplest path for Egypt/the Gulf and explain the cost in one line.

PHASE 2: PLAN
Summarise my answers in a table and confirm them with me. Then show the build plan. Wait for "go".

PHASE 3: BUILD
1. Create a skill folder (SKILL.md) with my business knowledge, tone rules, booking flow and handover rules. Keep it under 500 lines and easy for me to edit.
2. Write the agent's system prompt: answer only from the skill; never invent prices, discounts or delivery times; max 3 short sentences per reply; when a booking is complete, output a JSON block {name, phone, item_or_service, date_time_or_address, notes}.
3. Role-play 10 test conversations with me playing the customer: 5 normal, 2 bookings, 1 angry customer, 1 question that's not in the skill, 1 customer asking for a discount. Fix the skill after each problem.
4. Only after I approve the test conversations: walk me through connecting it to WhatsApp with the stack I chose (GoHighLevel, or an n8n workflow I can import: Webhook > AI Agent with Claude > send WhatsApp reply > save booking). One step at a time, wait for "done".
5. Final test from a second phone number, plus a checklist before going live.

RULES
Talk to me in Egyptian Arabic, tech terms in English. Never message real customers during testing. Never write API keys into files; tell me where to paste them in the tool's credentials. Don't guess menu paths you're not sure of; tell me what to look for instead.
```

**نصيحة:** خلّي أي حاجة فيها فلوس أو شكوى تتحول لإنسان. الـ Agent يرد ويجمع البيانات، وإنت تقفل البيعة.

<p align="center"><a href="#top">⬆️ رجوع لزراير السيستمز</a></p>

---

<a id="s2"></a>

## 🌐 2. Website builder

**بيعمل إيه:** تحط لينك Google Maps بتاع أي بيزنس، يرجعلك website كامل ليه، جاهز ينزل live.
**الأدوات (زي الفيديو):** Claude Code + **أمر واحد** (هنعمله custom command اسمه `/website`) + Netlify.

**▶️ الخطوات:**
1. افتح Claude Code في فولدر جديد اسمه `website-builder`.
2. الصق الـ Prompt تحت. هيسألك كام سؤال عن الستايل اللي بتحبه، وبعدين يعملك الأمر `/website`.
3. من هنا ورايح: اكتب `/website` وبعده لينك Google Maps لأي محل، وجاوب على أسئلته عن المحل.
4. افتح `index.html` في المتصفح وراجع كل معلومة.
5. انشره على Netlify: اسحب الفولدر على [Netlify Drop](https://app.netlify.com/drop)، أو خلّي Claude يمشي معاك في `netlify deploy`.

```
You are a senior web developer. Build me a reusable "one command" website builder inside Claude Code: I type /website followed by a Google Maps link of any business, and I get a complete, mobile-first website ready to deploy on Netlify.

PHASE 1: INTERVIEW ME ABOUT MY DEFAULTS (do not build yet)
Ask me in small groups (max 3 questions per message) and wait:
1. Who will I build sites for: my own business, or local shops I want to sell websites to?
2. Default language of the sites (Arabic, English, or both) and dialect for the copy.
3. Style I like: minimal, bold, luxury, or playful? Any website I like as a reference?
4. Main call-to-action button: WhatsApp, phone call, booking form, or directions?
5. Do I have a Netlify account? Is Node.js installed? (Check Node yourself with a command and tell me.)

PHASE 2: PLAN
Summarise my defaults, show the file structure, and wait for "go".

PHASE 3: BUILD
1. Create a custom command at .claude/commands/website.md that takes the Maps link as $ARGUMENTS.
2. The command must:
   a. Try to read the business details from the link. Anything it can't verify (name, category, address, phone, hours, rating, 3-5 real reviews, services or menu), it must ASK me to paste. Never invent reviews, prices or phone numbers.
   b. Ask me 3 quick questions about this specific business: the one thing they're best at, their WhatsApp number, and any photos I have.
   c. Build a new folder sites/<business-name>/ with index.html + styles.css, no framework: hero with name and one-line promise, services/menu, real reviews, hours, map embed, and a sticky CTA button. RTL layout if the language is Arabic. Fast and clean on mobile.
   d. Use clearly marked placeholder images where I have no photos.
   e. Finish with a checklist of what I must verify and the exact steps to deploy that folder on Netlify (Netlify Drop and Netlify CLI).
3. Test the command once with a business I give you, and fix anything that looks off.

RULES
Talk to me in Egyptian Arabic, tech terms in English. Don't deploy anything without asking me. Don't put any account tokens in files.
```

**نصيحة:** ده سيستم بيتباع: اعمل website لمحل قريب منك ببلاش، ابعتهوله، واعرض عليه يخليه live بمبلغ بسيط.

<p align="center"><a href="#top">⬆️ رجوع لزراير السيستمز</a></p>

---

<a id="s3"></a>

## 📩 3. Comment → DM

**بيعمل إيه:** أي حد يكتب كلمة تحت الريل، يوصله DM فيه الملف في ثانية… وإنت نايم. (ده نفس السيستم اللي بعتلك الرسالة دي 😉)
**الأدوات (زي الفيديو):** n8n + Instagram API + Facebook Pages.

**▶️ الخطوات:**
1. لازم يكون حساب Instagram بتاعك **Business أو Creator** ومربوط بصفحة Facebook.
2. افتح Claude Code في فولدر جديد اسمه `comment-to-dm`.
3. الصق الـ Prompt تحت وجاوب على أسئلته.
4. هيمشي معاك في إعداد Meta App، ويعملك ملف workflow تعمله **Import** في n8n.
5. جرّب بحساب Instagram تاني، مش بحسابك.

```
You are a senior n8n and Meta Graph API engineer. Together we'll build a "comment keyword to DM" automation: when someone comments a keyword under my reel, they get a public reply and a private DM with a link, automatically. Stack: n8n + Instagram Graph API + Facebook Pages API.

PHASE 1: INTERVIEW (do not build yet)
Ask me in small groups (max 3 questions per message) and wait:
1. Is my Instagram a Business or Creator account, and is it linked to a Facebook Page? (If I don't know, tell me how to check.)
2. Do I want this on Instagram only, or Facebook Page comments too?
3. Do I use n8n Cloud or self-hosted? Do I already have a Meta Developer app?
4. The keyword(s), in English and how Arabs would type them in Arabic. Should it work on all my reels or specific ones?
5. What to send in the DM: the link and the exact message. And the short public reply under the comment.
6. Language and tone of the replies.

PHASE 2: PLAN
Summarise my answers, list the Meta app permissions and webhook fields needed, and show the node chain. Wait for "go".

PHASE 3: BUILD STEP BY STEP (wait for "done" after each)
1. Meta setup: walk me through the developer app, the permissions, the access token, and subscribing to comment webhooks. Tell me what to look for on each screen instead of guessing exact menu paths.
2. Generate an n8n workflow JSON file I can import: Webhook (with the verification handshake) > IF the comment contains a keyword (case-insensitive, Arabic spelling too) > IF the commenter is not my own account (so it never loops) > reply to the comment > send a private reply with the DM text and link.
3. Tell me where to paste my token in n8n credentials. Never put it inside the JSON file.
4. Test plan using a second Instagram account, and what to check in n8n executions if no DM arrives.

RULES
Talk to me in Egyptian Arabic, tech terms in English. Don't message real followers during testing.
```

**نصيحة:** الملف اللي في الـ DM لازم يكون مفيد بجد، لو الناس حسّت إنه فاضي مش هيكتبوا تاني.

<p align="center"><a href="#top">⬆️ رجوع لزراير السيستمز</a></p>

---

<a id="s4"></a>

## 📈 4. Facebook ads engine

**بيعمل إيه:** يلاقي إعلان شغال وكسبان بقاله شهور، يفهم ليه ناجح، ويعمل 4 إعلانات جديدة لبيزنسك.
**الأدوات (زي الفيديو):** [Meta Ads Library](https://www.facebook.com/ads/library) + Claude + Higgsfield. لو مفيش عندك Higgsfield متوصل بـ Claude، Claude هيكتبلك الـ image prompts وإنت تحطها في أي أداة صور AI.

**▶️ الخطوات:**
1. افتح الـ [Ads Library](https://www.facebook.com/ads/library)، اختار البلد، ودوّر باسم منافس أو كلمة في نيشك.
2. اختار 3–5 إعلانات **شغالة بقالها أكتر من شهرين** (مكتوب تحت كل إعلان من امتى شغال). الإعلان الخسران بيتقفل بسرعة.
3. خد screenshot لكل إعلان.
4. افتح شات جديد على [claude.ai](https://claude.ai)، ارفع الصور، والصق الـ Prompt.
5. جاوب على أسئلته، وخد الـ 4 إعلانات وارفعهم **كمسودة** في Meta Ads Manager.

```
You are a senior performance marketer who has managed Meta ads for small businesses in Egypt and the Gulf. I'm attaching screenshots of ads from the Meta Ads Library that have been running for 2+ months (long-running ads are usually profitable).

PHASE 1: INTERVIEW (do this before writing any ad)
Ask me in small groups (max 3 questions per message) and wait:
1. My business, what I sell, and my price range.
2. My target customer: age, city or country, and the problem they want solved.
3. What makes me different from the brands in the screenshots?
4. My current offer (discount, free delivery, bundle, free trial) or none.
5. Ad format: image, short video, or carousel? Language and dialect of the ad copy?
6. Have I run ads before? What worked or flopped?

PHASE 2: ANALYSE THE WINNING ADS
For each screenshot: 3 bullets on why it probably works (hook, offer, visual, emotion). Then the one pattern they share. Wait for "go".

PHASE 3: CREATE 4 NEW ADS FOR MY BUSINESS
Each ad uses a different angle (pain, result, social proof, offer). For each one give me:
- Primary text (max 125 characters before "See more"), headline, and CTA button.
- A ready image or video prompt. If an image-generation connector is available in this chat, offer to generate the visual; otherwise give me a prompt I can paste into any AI image tool.
- Who to target and one line on why this angle fits my customer.
Then tell me which ad to test first and how to read the results after 3 days.

RULES
Talk to me in Egyptian Arabic. Keep the pattern of the winning ads, never copy their wording, brand or images. Don't make claims I can't prove. These are drafts; don't publish anything.
```

**نصيحة:** متنسخش الإعلان، انسخ **الفكرة**: نوع الـ hook وشكل العرض.

<p align="center"><a href="#top">⬆️ رجوع لزراير السيستمز</a></p>

---

<a id="s5"></a>

## 🎬 5. Video editor

**بيعمل إيه:** بيقطّع الفيديو، يحط captions و graphics، ويطلّعهولك reel جاهز للنشر.
**الأدوات (زي الفيديو):** Claude Code + ffmpeg + Remotion (و Whisper للـ captions).

**▶️ الخطوات:**
1. حط فيديو خام (talking head، طولي) في فولدر جديد اسمه `video-editor`.
2. افتح Claude Code في الفولدر ده والصق الـ Prompt.
3. هيسألك عن ستايل الـ captions والألوان، ويشيك بنفسه إيه المتنزّل على جهازك وإيه ناقص (ويستأذنك قبل ما ينزّل حاجة).
4. راجع الـ preview قبل الـ render النهائي.
5. بعد كده أي فيديو جديد = أمر واحد.

```
You are a senior video-automation engineer. Build me a reusable reel-editing pipeline: raw talking-head video in, a ready vertical reel with captions and simple graphics out. Stack: Claude Code + ffmpeg + Remotion + a speech-to-text model (Whisper or similar) for captions.

PHASE 1: INTERVIEW (do not build yet)
First check my machine yourself: OS, and whether ffmpeg, Node.js and Python are installed. Report what's missing. Then ask me in small groups (max 3 questions per message) and wait:
1. What language and dialect do I speak in the videos? (This decides the transcription model and caption font. Arabic needs an RTL-friendly font.)
2. Caption style: word-by-word highlight, 2-3 words at a time, or full sentences? Colours or brand colours? Position on screen?
3. Graphics: pop-up text for numbers and key words, emojis, a logo, a progress bar?
4. How aggressive should silence cutting be? (Default: cut pauses longer than 0.4s, keep a small padding so words aren't clipped.)
5. Background music: none, or a file I'll provide (at what volume)?
6. Typical length and the name of my first test video file.

PHASE 2: PLAN
Summarise my answers, show the pipeline steps and folder structure. Ask before installing anything. Wait for "go".

PHASE 3: BUILD STEP BY STEP (wait for "done" after each)
1. Silence cutting with ffmpeg into a new file. Never touch my original.
2. Transcription with word-level timestamps, saved to JSON. Let me fix typos in that file before captions are rendered.
3. A Remotion project that plays the cut video with my caption style and graphics, inside the Instagram safe area (nothing important in the bottom 20% or behind the right-side buttons).
4. A preview I can check in the browser, then a render at 1080x1920, 30fps, MP4.
5. Wrap everything in one command I can rerun on any new video, and a short README of how to use it.

RULES
Talk to me in Egyptian Arabic, tech terms in English. Ask before installing packages or deleting anything.
```

**نصيحة:** أول مرة هتاخد وقت، بس بعد كده كل reel جديد هياخد أمر واحد.

<p align="center"><a href="#top">⬆️ رجوع لزراير السيستمز</a></p>

---

<a id="s6"></a>

## ☀️ 6. Personal assistant

**بيعمل إيه:** يمسك الـ inbox بتاعك، يشيك على الكالندر، ويسلّمك ملخص كل يوم الصبح قبل ما تصحى.
**الأدوات (زي الفيديو):** Claude + Gmail و Calendar connectors + شوية skills.

**▶️ الخطوات:**
1. على [claude.ai](https://claude.ai) وصّل **Gmail** و **Google Calendar** من الـ Connectors ([مساعدة Claude](https://support.claude.com)).
2. افتح شات جديد والصق الـ Prompt.
3. هيسألك مين المهمين عندك وإيه اللي يعتبر "مستعجل"، وبعدين يجرّب يعملك أول ملخص.
4. لما الملخص يعجبك، هيكتبلك skill اسمه `morning-brief` ترفعها في Claude، فتكتب "morning brief" بس كل يوم.
5. عايزه يوصلك لوحده كل يوم 7 الصبح؟ استخدم الـ scheduled tasks في Claude لو متاحة عندك، أو workflow في n8n يبعتلك على Telegram.

```
You are my chief of staff. Together we'll build my daily morning brief using my connected Gmail and Google Calendar, then save it as a reusable skill.

PHASE 1: INTERVIEW (don't read my email yet)
Ask me in small groups (max 3 questions per message) and wait:
1. My name, my job or business, and my timezone.
2. Who are my VIPs (clients, partners, family) whose emails always matter? Any senders or newsletters to always ignore?
3. What counts as urgent for me (money, clients, deadlines, legal)?
4. My working hours, and anything I want protected (gym, family time)?
5. How do I want the brief: language, max length, and format (bullets, table)?
6. Should you draft replies to urgent emails? (Drafts only, never sent.)

PHASE 2: FIRST BRIEF
Confirm my answers in a short table. Then check that Gmail and Calendar are connected and create my first brief:
1. Emails from the last 24 hours grouped into: 🔴 needs my reply today, 🟡 can wait, ⚪ noise. For each 🔴: sender, one-line summary, what they need from me.
2. Today and tomorrow on my calendar: time, who, and one prep note per meeting. Flag clashes and back-to-back meetings.
3. The top 3 things I should focus on today.
4. If I said yes: a short draft reply for each 🔴 email, saved as a Gmail draft. Do NOT send anything.
Ask me what to change, and adjust until I say it's perfect.

PHASE 3: MAKE IT REUSABLE
Write a skill named morning-brief (a SKILL.md with a clear description and my rules from Phase 1) so I only type "morning brief" each day. Tell me how to add it to Claude. Then tell me my options to run it automatically every morning and send it to me (scheduled tasks if available in my plan, or an n8n workflow to Telegram), and ask which one I want.

RULES
Talk to me in Egyptian Arabic. Never send, delete or archive emails, and never accept or decline meetings. Read and draft only.
```

**نصيحة:** خليه **Draft only** دايماً. إنت اللي تدوس Send.

<p align="center"><a href="#top">⬆️ رجوع لزراير السيستمز</a></p>

---

## 🇪🇬 تقدر تكتبله بالمصري كمان

مش مرتاح للإنجليزي؟ الصق ده وهو هيفهمك عادي:

```
إنت مهندس أتمتة شاطر وصبور، وأنا مش مبرمج. عايزك تساعدني أبني سيستم واحد من الـ 6 سيستمز دول الويكند ده:
1. WhatsApp agent بيرد على العملاء ويحجزلهم
2. Website builder من لينك Google Maps
3. Comment → DM على Instagram
4. Facebook ads engine من الإعلانات الناجحة
5. Video editor بيطلّع reel جاهز
6. Personal assistant بيلخصلي الإيميل والكالندر كل يوم

متبنيش حاجة دلوقتي. اسألني الأول عن البيزنس بتاعي والعملاء والأدوات اللي عندي، سؤالين أو تلاتة في كل رسالة، واستنى ردي.
لو قلتلك "مش عارف"، اقترح عليا الأنسب لبيزنس صغير في مصر وقولي ليه.
بعدين رشّحلي سيستم واحد، وقولي الأدوات اللي محتاجها ببلاش ولا بفلوس، واعرض الخطة واستنى لما أقول "يلا".
وبعدها امشي معايا خطوة خطوة، وبعد كل خطوة قولي أجربها إزاي واستنى لما أقول "تمام".
ومتبعتش أي حاجة لعملاء حقيقيين من غير ما تسألني.
```

---

## ⚠️ نصايح مهمة

- **جاوب بالتفصيل**: كل ما إجاباتك على أسئلة Claude تكون أوضح، السيستم بيطلع مظبوط على بيزنسك أكتر.
- **Draft only**: أي سيستم بيبعت رسايل أو إيميلات أو إعلانات، خليه يعمل مسودة الأول لحد ما تثق فيه.
- **جرّب بحساب تاني**: الـ WhatsApp و Instagram جرّبهم من رقم أو حساب تاني، مش على العملاء.
- **المفاتيح سرّ**: متحطش الـ API keys أو الـ tokens في كود بتشاركه أو في screenshot، ومتلصقهاش في الشات.
- **لو حاجة وقعت**: الصق الـ error زي ما هو لـ Claude، متوصفهوش بكلامك.
- **لو هتصوّر**: اعمل blur على أسماء العملاء والإيميلات وأرقام التليفون.

---

## 🚀 الخلاصة

| قبل | بعد |
|---|---|
| بترد على WhatsApp بإيدك طول اليوم | Agent بيرد في 30 ثانية ويحجز |
| بتبعت الملفات للناس واحد واحد | كلمة في الكومنتات ← DM أوتوماتيك |
| بتقعد ساعات تقطّع فيديو | أمر واحد ← reel جاهز |
| بتصحى على 50 إيميل | ملخص قصير فيه المهم بس |

---
لو استفدت، تابعني عشان فيه سيستمز وأتمتة أكتر جاية 🔥

**Steven Ayman — Vida AI**
