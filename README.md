# Daily Vitals — App Store Connect

Paste each field as is. Limits are App Store Connect's; `Scripts/check-metadata.py` checks them.

## Українська (uk)

### Назва (≤ 30)
Daily Vitals

### Підзаголовок (≤ 30)
Щоденник саморефлексії

### Рекламний текст (≤ 170)
Кілька хвилин на день про себе: як почуваєтесь, що думаєте, скільки важите. З часом видно, як ваш стан, вага й вчинки пов’язані між собою.

### Опис (≤ 4000)
Daily Vitals — щоденник для саморефлексії. Він допомагає наприкінці дня зупинитися, чесно подивитися на свій стан і з часом зрозуміти, що на нього впливає.

ЗАПИСУЙТЕ ДЕНЬ
• Самопочуття від «погано» до «чудово» і теги настрою
• Думки — що крутилось у голові
• Що вдалось і що ні: звички, вчинки, рішення
• Вагу — з різницею з попереднім зважуванням

ПОМІЧАЙТЕ ЗВ’ЯЗКИ
• Календар, де колір дня — ваш стан, а поруч — вага
• Баланс «добре / погано» за місяць
• Тренд ваги за 7 днів замість щоденних коливань — за місяць, 3 місяці чи рік

РУХАЙТЕСЬ ДО МЕТИ
• Мета для схуднення чи набору маси
• Привітання й позначка в календарі в день, коли мету досягнуто

DAILY VITALS PRO — ОДНА ПОКУПКА, БЕЗ ПІДПИСОК
• Які звички, настрої та зміни ваги пов’язані з кращими і гіршими днями
• Що впливає на вагу: звички й самопочуття, після яких вага частіше росте чи знижується
• Прогноз, коли ви досягнете мети
• Експорт аналітики в PDF та Excel

НЕ ЗАКИДАЙТЕ
• Нагадування — лише якщо день ще не записано
• Apple Health: вага з розумних ваг з’являється сама, а ваша — зберігається в «Здоров’ї»
• Резервна копія, кілограми або фунти, українська та англійська

ТІЛЬКИ ДЛЯ ВАС
Щоденник — це особисте. Усе зберігається лише на цьому iPhone у зашифрованому файлі: без реєстрації, мережі, реклами й аналітики. Застосунок можна закрити Face ID або кодом.

### Ключові слова (≤ 100)
саморефлексія,самопочуття,настрій,вага,схуднення,думки,звички,рефлексія,стан,журнал,мета,трекер

### Що нового (перша версія)
Перша версія Daily Vitals.

## English (en-US)

### Name (≤ 30)
Daily Vitals: Mood & Weight

### Subtitle (≤ 30)
A journal for self-reflection

### Promotional text (≤ 170)
A few minutes a day about yourself: how you feel, what you think, what you weigh. Over time you see how your mood, weight and choices go together.

### Description (≤ 4000)
Daily Vitals is a journal for self-reflection. It helps you pause at the end of the day, take an honest look at how you are, and over time understand what shapes it.

LOG YOUR DAY
• Mood from “bad” to “great”, with mood tags
• Thoughts — what was on your mind
• What went well and what didn't: habits, choices, decisions
• Weight — with the change since your last weigh-in

NOTICE THE CONNECTIONS
• A calendar coloured by how you felt, with your weight alongside
• Your good / bad balance for the month
• A 7-day weight trend instead of daily ups and downs — over a month, 3 months or a year

WORK TOWARDS A GOAL
• A goal for losing or gaining weight
• A congratulation and a mark in the calendar on the day you reach it

DAILY VITALS PRO — ONE PURCHASE, NO SUBSCRIPTION
• Which habits, moods and weight changes go with your better and worse days
• What affects your weight: the habits and moods after which it tends to go up or down
• A forecast of when you'll reach your goal
• Export analytics to PDF and Excel

KEEP IT GOING
• A reminder — only if the day isn't logged yet
• Apple Health: weigh-ins from a smart scale appear on their own, and yours are saved to Health
• Backups, kilograms or pounds, English and Ukrainian

JUST FOR YOU
A journal is personal. Everything stays on this iPhone in an encrypted file: no account, network, ads or analytics. Lock it with Face ID or your passcode.

### Keywords (≤ 100)
diary,loss,thoughts,habits,wellbeing,tracker,goal,log,emotions,feelings,health,diet,scale,self-care

### What's New (first version)
The first version of Daily Vitals.

## Other App Store Connect answers

- **Category:** Health & Fitness (secondary: Lifestyle).
- **Privacy Policy URL:** where `AppStore/privacy-policy.html` is hosted.
- **App Privacy:** Data Not Collected — nothing leaves the device; Apple Health data is read and written on the device only.
- **Age rating:** answer «None» to every content question → 4+.
- **Export compliance:** the build declares `ITSAppUsesNonExemptEncryption = NO`, so TestFlight won't ask.
- **HealthKit review note:** “Weight is read from and saved to Apple Health only after the user turns it on in Settings or onboarding. Health data stays on the device: the app has no servers, iCloud or CloudKit storage of its own and makes no network requests. The journal is a local file with complete data protection; like other app data, it is part of the user's own device backup (iCloud Backup or an encrypted computer backup) when they have that turned on in iOS, so they don't lose their journal when moving to a new iPhone. The privacy policy says so.”
- **Screenshots:** `AppStore/screenshots/{uk,en}/` — 6.9" display, 1320 × 2868.
- **Version / build:** 1.0 (1). Raise the build number (`CURRENT_PROJECT_VERSION`) for every upload.

## In-App Purchase — Daily Vitals Pro

One **Non-Consumable** product with Family Sharing on. Needs the Paid Apps Agreement, banking and tax info; join the Small Business Program for a 15% commission. The same product is in `StoreKit/Products.storekit` for testing in the simulator (Run uses it via the scheme).

| Product ID | Reference name | Price | Display name (uk / en, ≤ 30) | Description (uk / en, ≤ 45) |
|---|---|---|---|---|
| `pro.unlock` | Pro – Lifetime | $4.99 | Daily Vitals Pro / Daily Vitals Pro | Зв'язки самопочуття й ваги, прогноз, експорт / Mood and weight insights, forecast, export |

- **Review screenshot:** `AppStore/review/pro-en.png` (Settings → «Daily Vitals Pro»; `pro-uk.png` is the Ukrainian one), 1320 × 2868.
- **Review note:** “Pro is a one-time purchase that unlocks the mood and weight insights on the dashboard, the goal forecast and exporting analytics to PDF and Excel. Settings → Daily Vitals Pro has the purchase and Restore Purchase. To review it, add 10 or more days with mood and weight; the locked cards then appear on the dashboard.”
- **App Privacy:** stays Data Not Collected — purchases are handled by StoreKit and the app sends nothing anywhere.
- Add the products to the version before submitting it for review — the first IAPs must go in with a new app version.
