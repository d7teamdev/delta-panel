<p align="center"><img src="https://d7team.com/icon-512.png" width="88" alt="Delta Seven"></p>
<h1 align="center">Delta Panel</h1>
<p align="center"><b>FiveM Admin Panel for QBCore, QBox & CFW Servers</b></p>
<p align="center"><a href="#english">English</a> · <a href="#arabic">العربية</a></p>

<p align="center"><a href="https://d7team.com/products/delta-panel"><img src="https://d7team.com/product-previews/delta-panel.webp" alt="Delta Panel" width="860"></a></p>

<a id="english"></a>

## Delta Panel — FiveM Admin Panel for QBCore, QBox & CFW Servers

FiveM admin panel for QBCore, QBox & CFW: manage online and offline players, inventories, vehicles, bans and Live Screens from the browser or in game.

Delta Panel gives your staff one place to run the server: who is online, every character and vehicle, inventories and stashes, bans, the priority queue, and a full log of who did what. They can watch a player's screen while it happens, and act on what they see. It opens in a browser, and since 2.1 it opens in the game too — your admins type /delta and get the same pages with the same permissions, without leaving the server.

> This repository is documentation only. The resource is sold on our store and downloaded from the Client Area after you redeem your code.

[Website](https://d7team.com/products/delta-panel) · [Installation guide](https://d7team.com/guides/delta-panel) · [Live demo](https://d7team.com/demo-panel) · [Store](https://store.d7team.com) · [Discord](https://discord.gg/d-7)

### At a glance

| | |
|---|---|
| **Works with** | QBCore and QBox servers, CFW included |
| **Inventories** | ox_inventory, qb-inventory, qs-inventory, ps-inventory and lj-inventory |
| **Where it runs** | In the browser, and in the game with /delta |
| **Players** | Online and offline |
| **Sign-in** | Discord — no passwords to hand out |
| **Languages** | Arabic and English |

### Features

#### Players and characters

- Search every character on the server — by name, citizen ID or licence — not only the first page.
- A full profile for each character: money, job and grade, gang and rank, identity, vehicles and inventory.
- Set, give or take cash and bank money.
- Change job, gang and grade from lists read from your own server.
- Edit identity: first and last name, birth date, gender, nationality and phone.
- Edit character metadata key by key, with the right control for each value.
- Change License — move a character to the Rockstar licence it should load with.
- Change a character's citizen ID across every table that references it.
- Delete a character, with a typed confirmation.
- Set a connected player's permission level: user, mod, admin or god.

#### Quick actions on connected players

- Revive, feed and give armour.
- Teleport to a saved location or to exact coordinates.
- Open the clothing menu on the player's screen.
- Cuff and uncuff, and release from jail.
- Kick with a reason the player sees.
- Direct message a player, or send an announcement to the whole server.
- Every action reports back only once the change has really happened on the server.

#### Inventories and stashes

- Read any player's inventory with item images and labels.
- Give, remove or clear items for a connected player.
- Move items between slots while the player is offline.
- Browse every stash on the server, search its items, add, remove or clear.
- Open a vehicle's trunk and glovebox from its page.

#### Vehicles

- Search every vehicle on the server by plate, model, owner or state.
- Give a vehicle, transfer ownership or change the plate.
- Change a vehicle's stored state, or delete it.
- Repair the vehicle a connected player is sitting in.

#### Live Screens

- Watch a connected player's game view live in your browser.
- Several players side by side, and one expanded to full size.
- It streams only while somebody is watching and stops on its own when you leave.
- No audio, no recording, nothing stored.

#### Moderation and protection

- Bans with a duration and a reason, editing, unbanning and search across every ban.
- Connection protection: require Discord, Steam or Xbox, block a duplicate licence, block VPNs.
- Name rules: block colour codes, symbols and unsafe markup in player names.
- A refused player sees a clear card with the reason and a link to your Discord.
- Dupe Scanner: finds duplicated weapons across inventories and stashes and removes them.
- Investigator: one search across characters, vehicles, stashes and logs.

#### Server overview

- Dashboard: who is online now, activity over the day and the last players to join.
- Online players with their characters, one click from each profile.
- Priority and queue: grant or remove priority, move a player in the queue, or remove them.
- Gangs and their members.
- Leaderboards your players can open in their browser, with weekly and all-time boards.

#### Staff, permissions and logs

- Admins and roles with per-permission control over every page and action.
- A member can hold more than one role.
- Audit log of every admin action — who, what, to whom and when — with Discord webhooks.
- Several servers under one account, each with its own admins and settings.
- FiveM Config page: appearance resource, the in-game command, and your own cuff, uncuff, revive and clothing events.
- In-game menu on /delta with the same pages and the same permissions.

### Online and offline players

**Online and offline**

- Money, job, gang and grade
- Identity and metadata
- Change License and Change Citizen ID
- Delete a character
- Vehicles: give, transfer, plate, stored state, delete
- Stashes, bans and queue priority

**Player connected**

- Revive, feed, armour and teleport
- Kick, direct message and announcement
- Permission level, clothing menu, cuff and unjail
- Give, remove or clear inventory items
- Repair the vehicle the player is in
- Live Screens

**Player offline**

- Move items between inventory slots

### Delta Panel vs txAdmin

**Both have**

- Bans, kicks and messages
- An in-game admin menu
- Staff permissions

**Only in Delta Panel**

- Advanced player control, online and offline
- Full control of the character
- Live screens from the site and the menu
- Detailed logs on the site and Discord

[See the full comparison](https://d7team.com/delta-panel-vs-txadmin)

### Video

[![Delta Panel](https://img.youtube.com/vi/ESAoESPsrB8/hqdefault.jpg)](https://www.youtube.com/watch?v=ESAoESPsrB8)

### Requirements

- A QBCore or QBox server, CFW included
- oxmysql
- ox_inventory, qb-inventory, qs-inventory, ps-inventory or lj-inventory
- A Delta Panel licence and a Discord account

### Installation

1. Buy Delta Panel on our store.
2. Sign in at panel.d7team.com with Discord.
3. Client Area → Redeem Code: enter the code and your server's public IP.
4. Download DeltaPanel from the Client Area.
5. Put the DeltaPanel folder in resources. Keep its name.
6. In server.cfg, start it after your database, framework and inventory:

   ```cfg
   ensure oxmysql
   ensure qb-core
   ensure qb-inventory
   ensure DeltaPanel
   ```

7. Restart the server.

Configuration, first start, updates and every console message explained: [Installation guide](https://d7team.com/guides/delta-panel)

### Pricing

- **$7.99 / month** — Delta Panel Premium

[Store](https://store.d7team.com)

### FAQ

<details>
<summary><b>Can I manage players who are offline?</b></summary>

Yes. Money, job, gang, identity, metadata, vehicles, stashes, bans, licence and citizen ID all work whether the player is connected or not. Actions that happen inside the game — revive, teleport, kick, messages — need the player connected, and moving items between inventory slots is done while they are offline.

</details>

<details>
<summary><b>Does Delta Panel work on QBCore, QBox and CFW?</b></summary>

Yes. It detects your server's framework and inventory on its own, with ox_inventory, qb-inventory, qs-inventory, ps-inventory and lj-inventory. There is no framework setting to get wrong.

</details>

<details>
<summary><b>Can my admins use it from inside the game?</b></summary>

Yes. Typing /delta opens the same pages with the same permissions, without leaving the server.

</details>

<details>
<summary><b>Can I limit what each admin can do?</b></summary>

Yes. Every page and every action has its own permission. Build roles from them, give a member one or more roles, and every action they take is written to the audit log.

</details>

<details>
<summary><b>How do Live Screens work?</b></summary>

The player's game view streams to your browser while you are watching it and stops when you close it. There is no audio and nothing is recorded or saved.

</details>

<details>
<summary><b>How many servers does one licence cover?</b></summary>

One. A licence is tied to one server IP. One account can manage several servers, each with its own licence.

</details>

<details>
<summary><b>How much does it cost?</b></summary>

Premium is $7.99 a month. Buy it on our store and redeem the code on panel.d7team.com.

</details>

### Support

Support is on our Discord: [discord.gg/d-7](https://discord.gg/d-7). Issues are closed on this repository so no request waits unread.

### More from Delta Seven

- [Advanced MDT](https://github.com/d7teamdev/advanced-mdt) — FiveM Police MDT for QBCore, QBox & CFW
- [Advanced BossMenu](https://github.com/d7teamdev/advanced-bossmenu) — FiveM Boss Menu for QBCore, QBox & CFW
- [Add-on FiveM cars](https://d7team.com/cars)

---

<a id="arabic"></a>

<div dir="rtl">

## لوحة تحكم دلتا — لوحة تحكم سيرفرات فايف ام لـ QBCore و QBox و CFW

لوحة تحكم سيرفر فايف ام لـ QBCore و QBox و CFW: تحكم بالاعبين المتصلين وغير المتصلين، الإنفنتري، المركبات، الحظر والشاشات المباشرة من المتصفح أو داخل اللعبة.

Delta Panel تجمع لطاقمك كل شي بمكان واحد: مين متصل، كل الشخصيات والمركبات، الإنفنتري والمخازن، البانات، قائمة الأولوية، وسجل كامل لمين سوّى وش. يقدرون يشوفون شاشة اللاعب لحظة بلحظة وياخذون إجراء على الي شافوه. تفتح بالمتصفح، ومن تحديث 2.1 تفتح جوّه اللعبة بعد — الإداري يكتب ⁦/delta⁩ وتجيه نفس الصفحات بنفس الصلاحيات، بدون ما يطلع من السيرفر.

> هذا المستودع للتعريف والشرح فقط. الريسورس يُباع في متجرنا، وتحمّله من منطقة العميل بعد ما تفعّل الكود

[الموقع](https://d7team.com/ar/products/delta-panel) · [شرح التثبيت](https://d7team.com/ar/guides/delta-panel) · [تجربة مباشرة](https://d7team.com/ar/demo-panel) · [المتجر](https://store.d7team.com) · [الدسكورد](https://discord.gg/d-7)

### نظرة سريعة

| | |
|---|---|
| **يشتغل مع** | سيرفرات QBCore و QBox، ومعها CFW |
| **الإنفنتري** | ox_inventory و qb-inventory و qs-inventory و ps-inventory و lj-inventory |
| **وين تشتغل** | بالمتصفح، وداخل اللعبة بأمر ⁦/delta⁩ |
| **الاعبين** | المتصلين وغير المتصلين |
| **تسجيل الدخول** | دسكورد — بدون باسووردات توزعها |
| **اللغات** | العربي والإنجليزي |

### المميزات

#### الاعبين والشخصيات

- ابحث في كل شخصيات السيرفر — بالاسم أو رقم المواطن أو اللايسنس — مو بس أول صفحة
- ملف كامل لكل شخصية: الفلوس، الوظيفة والرتبة، العصابة ورتبتها، الهوية، المركبات والإنفنتري
- تعديل الكاش والبنك: تحديد، إعطاء، أو سحب
- تغيير الوظيفة والعصابة والرتبة من قوائم مقروءة من سيرفرك نفسه
- تعديل الهوية: الاسم الأول والأخير، تاريخ الميلاد، الجنس، الجنسية ورقم الجوال
- تعديل الميتاداتا مفتاح مفتاح، مع الأداة المناسبة لكل قيمة
- تغيير اللايسنس — تنقل الشخصية للايسنس روكستار الي المفروض تنفتح عليه
- تغيير رقم المواطن للشخصية في كل الجداول المرتبطة فيه
- حذف شخصية، مع تأكيد مكتوب
- تحديد صلاحية الاعب المتصل: user أو mod أو admin أو god

#### إجراءات سريعة على الاعبين المتصلين

- إنعاش، إطعام، وإعطاء درع
- نقل الاعب لموقع محفوظ أو لإحداثيات محددة
- فتح منيو الملابس على شاشة الاعب
- تكبيل وفك تكبيل، وإخراج من السجن
- طرد مع سبب يشوفه الاعب
- رسالة خاصة للاعب، أو إعلان لكل السيرفر
- كل إجراء يرجّع لك النتيجة بعد ما يتأكد إن التغيير صار فعلاً بالسيرفر

#### الإنفنتري والمخازن

- تشوف إنفنتري أي لاعب مع صور الأغراض وأسمائها
- إعطاء أو سحب أو تنظيف الأغراض للاعب المتصل
- نقل الأغراض بين الخانات والاعب غير متصل
- تصفح كل مخازن السيرفر، ابحث بأغراضها، أضف أو اسحب أو نظّف
- فتح شنطة المركبة والدرج من صفحتها

#### المركبات

- ابحث في كل مركبات السيرفر باللوحة أو الموديل أو المالك أو الحالة
- إعطاء مركبة، نقل ملكيتها، أو تغيير لوحتها
- تغيير حالة تخزين المركبة، أو حذفها
- تصليح المركبة الي راكبها الاعب المتصل

#### الشاشات المباشرة

- شاهد شاشة الاعب المتصل مباشرة من متصفحك
- أكثر من لاعب جنب بعض، وتقدر تكبّر واحد بالحجم الكامل
- البث يشتغل بس وأنت تتابع، ويوقف لحاله أول ما تطلع
- بدون صوت، بدون تسجيل، وما ينحفظ شي

#### الإدارة والحماية

- الحظر بمدة وسبب، مع التعديل وفك الحظر والبحث في كل البانات
- حماية الدخول: اشتراط دسكورد أو ستيم أو إكس بوكس، منع اللايسنس المكرر، ومنع الـ VPN
- قواعد الأسماء: منع أكواد الألوان والرموز والأكواد الخطرة بأسماء الاعبين
- الاعب المرفوض يشوف بطاقة واضحة فيها السبب ورابط دسكوردك
- فحص التدبيل: يلقى الأسلحة المكررة في الإنفنتري والمخازن ويحذفها
- البحث المتقدم: بحث واحد يغطي الشخصيات والمركبات والمخازن واللوقات

#### نظرة على السيرفر

- لوحة المعلومات: مين متصل الحين، نشاط السيرفر خلال اليوم، وآخر الي دخلوا
- الاعبين المتصلين مع شخصياتهم، وكل ملف على بعد ضغطة
- الأولوية والانتظار: إعطاء أو سحب أولوية، تحريك لاعب بالطابور، أو إخراجه منه
- العصابات وأعضاؤها
- صفحات صدارة يفتحها لاعبينك من المتصفح، أسبوعية وعلى طول الوقت

#### الطاقم والصلاحيات واللوقات

- إداريين ورتب مع تحكم بكل صلاحية على حدة لكل صفحة وإجراء
- العضو يقدر يكون عنده أكثر من رتبة
- سجل لكل إجراء إداري — مين، وش سوّى، على مين ومتى — مع ويب هوك دسكورد
- أكثر من سيرفر تحت حساب واحد، وكل سيرفر له إدارييه وإعداداته
- صفحة FiveM Config: ريسورس الملابس، أمر اللعبة، وأحداث التكبيل وفكه والإنعاش والملابس الخاصة بسيرفرك
- منيو داخل اللعبة على ⁦/delta⁩ بنفس الصفحات ونفس الصلاحيات

### الاعبين المتصلين وغير المتصلين

**متصل وغير متصل**

- الفلوس والوظيفة والعصابة والرتبة
- الهوية والميتاداتا
- تغيير اللايسنس ورقم المواطن
- حذف الشخصية
- المركبات: إعطاء، نقل، لوحة، حالة التخزين، حذف
- المخازن والحظر وأولوية الطابور

**الاعب متصل**

- الإنعاش والإطعام والدرع والنقل
- الطرد والرسائل والإعلان
- الصلاحية ومنيو الملابس والتكبيل والإخراج من السجن
- إعطاء وسحب وتنظيف أغراض الإنفنتري
- تصليح مركبة الاعب
- الشاشات المباشرة

**الاعب غير متصل**

- نقل الأغراض بين خانات الإنفنتري

### لوحة دلتا مقابل txAdmin

**موجود بالاثنين**

- الحظر والطرد والرسائل
- منيو إدارة داخل اللعبة
- صلاحيات الطاقم

**بس في لوحة دلتا**

- تحكم متطور بالاعب، متصل وغير متصل
- تحكم كامل بالشخصية
- شاشات مباشرة من الموقع والمنيو
- لوقات مفصّلة بالموقع والدسكورد

[شوف المقارنة كاملة](https://d7team.com/ar/delta-panel-vs-txadmin)

### الفيديو

[![Delta Panel](https://img.youtube.com/vi/ESAoESPsrB8/hqdefault.jpg)](https://www.youtube.com/watch?v=ESAoESPsrB8)

### المتطلبات

- سيرفر QBCore أو QBox، ومعها CFW
- oxmysql
- ox_inventory أو qb-inventory أو qs-inventory أو ps-inventory أو lj-inventory
- ترخيص لوحة دلتا وحساب دسكورد

### التثبيت

1. اشترِ لوحة دلتا من متجرنا.
2. سجّل دخولك في panel.d7team.com عن طريق دسكورد.
3. منطقة العميل ← تفعيل كود: اكتب الكود وآيبي سيرفرك العام.
4. حمّل DeltaPanel من منطقة العميل.
5. حط مجلد DeltaPanel في resources. لا تغيّر اسمه.
6. في server.cfg، شغّله بعد قاعدة البيانات والفريم وورك والإنفنتري:

</div>

```cfg
ensure oxmysql
ensure qb-core
ensure qb-inventory
ensure DeltaPanel
```

<div dir="rtl">

7. سوّ ريستارت للسيرفر.

الإعدادات، أول تشغيل، التحديثات، وشرح كل رسالة بالكونسول: [شرح التثبيت](https://d7team.com/ar/guides/delta-panel)

### الأسعار

- **⁦$7.99⁩ بالشهر** — لوحة دلتا بريميوم

[المتجر](https://store.d7team.com)

### الأسئلة الشائعة

<details>
<summary><b>أقدر أتحكم بالاعبين وهم غير متصلين؟</b></summary>

إيه. الفلوس والوظيفة والعصابة والهوية والميتاداتا والمركبات والمخازن والحظر واللايسنس ورقم المواطن كلها تشتغل سواء الاعب متصل أو لا. الإجراءات الي تصير داخل اللعبة — الإنعاش والنقل والطرد والرسائل — تحتاج الاعب يكون متصل، ونقل الأغراض بين خانات الإنفنتري يكون وهو غير متصل.

</details>

<details>
<summary><b>لوحة دلتا تشتغل على QBCore و QBox و CFW؟</b></summary>

إيه. تتعرف على الفريم وورك والإنفنتري بسيرفرك لحالها، مع ox_inventory و qb-inventory و qs-inventory و ps-inventory و lj-inventory. ما فيه إعداد فريم وورك تغلط فيه.

</details>

<details>
<summary><b>الإداريين يقدرون يستخدمونها من داخل اللعبة؟</b></summary>

إيه. يكتب ⁦/delta⁩ وتفتح له نفس الصفحات بنفس الصلاحيات، بدون ما يطلع من السيرفر.

</details>

<details>
<summary><b>أقدر أحدد وش يسوي كل إداري؟</b></summary>

إيه. كل صفحة وكل إجراء له صلاحية خاصة. تسوي رتب منها، تعطي العضو رتبة أو أكثر، وكل إجراء يسويه ينكتب بسجل اللوق.

</details>

<details>
<summary><b>كيف تشتغل الشاشات المباشرة؟</b></summary>

شاشة الاعب تنبث لمتصفحك وأنت تتابعها، وتوقف أول ما تقفلها. بدون صوت، وما ينسجل ولا ينحفظ شي.

</details>

<details>
<summary><b>كم سيرفر يغطي الترخيص الواحد؟</b></summary>

سيرفر واحد. الترخيص مربوط بآيبي سيرفر واحد، وحساب واحد يقدر يدير أكثر من سيرفر وكل واحد بترخيصه.

</details>

<details>
<summary><b>كم سعرها؟</b></summary>

باقة بريميوم بـ ⁦$7.99⁩ بالشهر. تشتريها من متجرنا وتفعّل الكود في panel.d7team.com

</details>

### الدعم

الدعم على الدسكورد حقنا: [discord.gg/d-7](https://discord.gg/d-7). الـ Issues مقفلة بهذا المستودع عشان ما يضيع أي طلب بدون رد

### منتجات ثانية من دلتا سفن

- [Advanced MDT](https://github.com/d7teamdev/advanced-mdt) — سكربت MDT للشرطة في فايف ام لـ QBCore و QBox و CFW
- [Advanced BossMenu](https://github.com/d7teamdev/advanced-bossmenu) — سكربت بوس منيو فايف ام لـ QBCore و QBox و CFW
- [سيارات فايف ام مضافة](https://d7team.com/ar/cars)

</div>

---

<p align="center">© Delta Seven (D7 Team) · <a href="https://d7team.com">d7team.com</a></p>
