# מחקר שוק: מודיעין עסקי מבוסס רשתות חברתיות (Social Intelligence)
**תאריך:** ספטמבר 2026 | **נכתב לפי:** סקיל `market-research` (מבנה), סקיל `market-sizing` (חישוב גודל שוק)
**קבצים נלווים:** `competitors.csv` (36 שחקנים), `research/notes.md` (יומן מקורות), `research/market.json` (הנחות החישוב)

> **מקרא:** **[עובדה]** טענה עם מקור מקושר · **[פרשנות]** הסקה שלי מהעובדות · **[הערכה]** מספר או טענה בלי מקור, הנחת עבודה שצריך לאמת.
> זה לא ייעוץ משפטי. בפרק המשפטי יש מיפוי ראשוני, ולפני השקה צריך לבדוק אותו מול עו"ד פרטיות.

---

## 1. תקציר מנהלים

**השורה התחתונה:** ההשערה המובילה **מחזיקה חלקית**. יש פער אמיתי בשוק, אבל השוק הישראלי לבדו קטן מדי כדי לבנות עליו חברה. לכן כדאי לצאת לדרך עם ההשערה, בשני תיקונים: להגדיר את הלקוח כ"ארגון ישראלי או יהודי שחשוף לנרטיב עוין **גם בחו"ל**", ולהגיע ללקוחות בעיקר דרך סוכנויות יח"צ.

**עיקרי הממצאים:**
1. **השוק הכללי גדול ובוגר, ויש בו התכנסות.** [עובדה] הערכות לשוק ה-social listening ב-2026 נעות בין [$10.9B](https://www.mordorintelligence.com/industry-reports/social-media-listening-market) ל-[$12.15B](https://www.thebusinessresearchcompany.com/report/social-media-listening-global-market-report), עם צמיחה של 11-17% בשנה. [עובדה] הענקיות קונות אחת את השנייה: [Hootsuite קנתה את Talkwalker](https://www.hootsuite.com/newsroom/press-releases/hootsuite-agrees-to-acquire-talkwalker), ו-[Sprout Social קנתה את NewsWhip ב-$55M](https://investors.sproutsocial.com/news/news-details/2025/Sprout-Social-Acquires-NewsWhip-Enhancing-Predictive-Intelligence-Capabilities-and-Accelerating-AI-Roadmap/default.aspx).
2. **הכסף הגדול זורם למודיעין סיכונים ונרטיב.** [עובדה] ב-2025: [Signal AI גייסה $165M](https://signal-ai.com/insights/press_release/signal-ai-announces-165-million-investment-round-led-by-battery-ventures-to-redefine-risk-and-reputation-intelligence/), [Dataminr גייסה $300M וקנתה את ThreatConnect ב-$290M](https://www.securityweek.com/dataminr-to-acquire-threatconnect-for-290-million/), ו-[Blackbird.AI גייסה $28M](https://www.securityweek.com/blackbird-ai-raises-28-million-for-narrative-intelligence-platform/). [עובדה] ב-2026 הונפקה Cyabra הישראלית בנאסד"ק, עם [ARR של כ-$8.1M](https://www.nasdaq.com/press-release/cyabra-delivers-record-second-quarter-revenue-39-year-over-year-growth-2026-08-13).
3. **כל שחקני הנרטיב מוכרים לארגונים גדולים ולממשלות.** [עובדה] Cyabra מדווחת על עסקאות בהיקף של [שש ספרות](https://www.cbinsights.com/company/cyabra), ו-Blackbird ו-Alethea לא מפרסמות מחיר. [פרשנות] ארגונים בינוניים נשארים בלי פתרון: יש להם כלי ניטור זולים (Brand24 מ-[$199 לחודש](https://www.trustradius.com/products/brand24/pricing)), אבל אין להם ניתוח נרטיב ואין אנליסט.
4. **בעברית ובערבית מקומית הפער אמיתי, אבל לא ריק.** [עובדה] Buzzilla/Ifat מכסה עברית, פורומים וטוקבקים. [עובדה] בערבית פועלות [Lucidya ($30M ב-2025)](https://www.middleeastainews.com/p/lucidya-biggest-saudi-ai-funding) ו-[Crowd Analyzer (13+ ניבים)](https://crowdanalyzer.com/), אבל הן ממוקדות במפרץ ובחוויית לקוח, לא בסיכוני נרטיב.
5. **גודל השוק בישראל:** [הערכה, חישוב בשתי שיטות] ה-TAM הוא $52-60M בשנה, ה-SAM $13-18M, וה-SOM הריאלי $0.65-0.9M ARR (כ-60 לקוחות). זה מספיק לעסק רווחי קטן, אבל לא לחברת סטארטאפ שנבנית לגיוס הון.
6. **הסיכון המבני:** [עובדה] [Logically קרסה ב-2025](https://sifted.eu/articles/logically-ai-fact-check-misinformation-trump-tiktok-meta) אחרי שאיבדה את החוזים עם Meta וטיקטוק. [פרשנות] תלות בלקוח או בפלטפורמה אחת יכולה להרוג חברה בתחום.
7. **משפטית:** איסוף נתונים ציבוריים בלי התחברות (logged-off) קיבל גיבוי בארה"ב ([Meta נגד Bright Data](https://www.fbm.com/publications/major-decision-affects-law-of-scraping-and-online-data-collection-meta-platforms-v-bright-data/), [X נגד Bright Data](https://www.mofo.com/resources/insights/240604-california-federal-court-holds-x-s-claims)). **אבל** דיני הפרטיות, GDPR ו[תיקון 13](https://iapp.org/news/a/israel-marks-a-new-era-in-privacy-law-amendment-13-ushers-in-sweeping-reform), חלים בנפרד. לכן המוצר צריך לנתח נרטיבים ורשתות, ולא לבנות פרופילים של אנשים פרטיים.

**ההמלצה, לפי סדר עדיפות:**
1. **מודיעין סיכוני נרטיב לארגונים ישראליים בינוניים שחשופים לחו"ל** (מותגי צריכה, יצואנים, מוסדות), כשירות מנוהל בריטיינר חודשי.
2. **שירות white-label לסוכנויות יח"צ וניהול משברים בישראל**, כערוץ הפצה שמקצר את הזמן עד לקוח ראשון.
3. **ניטור נרטיבים עוינים לארגונים יהודיים ופרו-ישראליים בחו"ל**, בעברית, אנגלית וערבית. זה כיוון התרחבות שנותן גודל שוק.

**לא מומלץ כרגע:** טרנדים באופנה (תחרות מבוססת ותלות גבוהה באינסטגרם ובטיקטוק) ו"אותות מוקדמים לסיכון עסקי" כללי (Dataminr ו-Signal AI שולטות בו עם מאות מיליוני דולרים).

---

## 2. סקירת השוק והגדרתו

**גבולות השוק:** כלים ושירותים שאוספים תוכן ציבורי מרשתות חברתיות ומפורומים, ומפיקים ממנו תובנה עסקית. השוק מתחלק לשלוש שכבות:

| שכבה | דוגמאות | מה נמכר |
|---|---|---|
| תשתית נתונים | Bright Data, Apify, EnsembleData, Webz.io | רשומות גולמיות, API |
| פלטפורמות listening | Brandwatch, Meltwater, Talkwalker, Brand24 | דשבורד, התראות, סנטימנט |
| מודיעין ושירות | Blackbird, Cyabra, Alethea, Signal AI, Dataminr | ניתוח נרטיב, סיכון, התרעה, לפעמים אנליסט |

[פרשנות] ככל שעולים בשכבות, המחיר והמרווח עולים, וגם התלות בידע אנושי. ההשערה שלך ממוקמת בשכבה העליונה, אבל במחיר של השכבה האמצעית.

**אירוע מכונן:** [עובדה] Meta [סגרה את CrowdTangle ב-14.8.2024](https://www.cjr.org/tow_center/meta-is-getting-rid-of-crowdtangle.php), ו-Meta Content Library שהחליף אותו פתוח רק לחוקרים מאושרים. [עובדה] ה-Research API של טיקטוק [אוסר שימוש מסחרי](https://www.tiktok.com/legal/page/global/terms-of-service-research-api/en). [פרשנות] לכן אין מסלול רשמי לנתונים מסחריים מ-Meta ומטיקטוק, ושחקנים קטנים חייבים לעבוד עם ספקי צד-שלישי.

---

## 3. גודל השוק וצמיחה

### 3.1 השוק הגלובלי: המקורות לא מסכימים
| מקור | 2025 | 2026 | תחזית | CAGR |
|---|---|---|---|---|
| [The Business Research Co.](https://www.thebusinessresearchcompany.com/report/social-media-listening-global-market-report) | $10.37B | $12.15B | – | 17.1% (שנה אחת) |
| [Mordor Intelligence](https://www.mordorintelligence.com/industry-reports/social-media-listening-market) | – | $10.91B | $20.51B (2031) | 11.2% |
| [Coherent Market Insights](https://www.coherentmarketinsights.com/industry-reports/social-media-listening-market) | – | $11.91B | $29.63B (2033) | 13.9% |
| [Grand View Research](https://www.grandviewresearch.com/industry-analysis/social-media-listening-market-report) | צפון אמריקה = 39.9% מהשוק (2024) | | | |

**הסתירה:** ההערכות ל-2026 שונות זו מזו בכ-11%, ושיעורי הצמיחה שונים בכ-6 נקודות אחוז. לא הכרעתי ביניהן, ולכן בהמשך אני משתמש בטווח **$10.4-12.2B**.

**שוק "אבטחת דיסאינפורמציה":** [עובדה, מקור משני] לפי [Blackbird.AI](https://blackbird.ai/blog/disinformation-security-and-narrative-intelligence/), השוק היה $1.8B ב-2025 וצפוי להגיע ל-$4.2B ב-2033, ו-Gartner צופה שהוצאות ארגונים בתחום יעברו $30B עד 2028. **הסתייגות:** זה ציטוט של ספקית שיש לה אינטרס, ולא מצאתי את הדוח המקורי. שני המספרים שונים זה מזה פי 7, כנראה בגלל הגדרות שונות.

### 3.2 הנישה בישראל: חישוב בשתי שיטות (סקיל market-sizing)
**כל הקלטים כאן הם [הערכה]**, והם שמורים ב-`research/market.json`.

| | מלמעלה-למטה (top-down) | מלמטה-למעלה (bottoms-up) |
|---|---|---|
| נקודת מוצא | חלק ישראל בשוק העולמי: ~0.5%, לפי חלקה בתמ"ג העולמי [הערכה], מתוך $10.4B → **$52M** | 4,000 ארגונים פוטנציאליים (חברות עם 100+ עובדים, כ-250 רשויות מקומיות, בתי חולים, אוניברסיטאות, עמותות גדולות) [הערכה] × $15K לשנה → **$60M** |
| SAM | 25% שחשופים לסיכון נרטיב → $13M | 30% → $18M |
| SOM (3 שנים) | 5% → **$650K** | 5% → **$900K** (כ-60 לקוחות) |

**תוצאה:** הפער בין השיטות הוא 15.4%, בתוך הסף של 30%, כלומר ההצלבה עברה. **[פרשנות]** המספר המכריע הוא ה-SOM: פחות ממיליון דולר ARR בישראל. זה עסק שירות קטן, לא חברה שנבנית לגיוס הון. לכן בהמלצות מופיע כיוון ההתרחבות (נישה 3).

**מה צריך לאמת:** מספר החברות בישראל עם 100 עובדים ומעלה, מול נתוני הלמ"ס ורשות לעסקים קטנים ובינוניים. לא מצאתי מקור ישיר.

---

## 4. דינמיקה תעשייתית: חמשת הכוחות של Porter (לנישת הנרטיב)

| כוח | רמה | נימוק |
|---|---|---|
| איום מתחרים חדשים | **גבוה** | [פרשנות] מודלי שפה וספקי נתונים זולים ([Apify מ-$29 לחודש](https://apify.com/pricing), [Bright Data כ-$1.5 ל-1,000 רשומות](https://brightdata.com/pricing/web-scraper)) מורידים את חסם הכניסה הטכנולוגי. החסם שנשאר הוא אמון ומומחיות מקומית. |
| כוח הספקים | **בינוני-גבוה** | [עובדה] X גובה [$0.005 לפוסט דרך ה-API](https://docs.x.com/x-api/getting-started/pricing), ובתנאי השימוש שלה יש [פיצוי מוסכם של $15K לכל מיליון פוסטים](https://x.com/en/tos) כשניגשים ליותר ממיליון פוסטים ביממה. [פרשנות] ספקי צד-שלישי מחליפים זה את זה בקלות יחסית, אבל כולם תלויים בפלטפורמות. |
| כוח הקונים | **בינוני** | [פרשנות] ארגון בינוני רגיש למחיר, אבל כשיש משבר הרגישות יורדת. אפשר להחליף ספק בקלות, אלא אם השירות כולל אנליסט שמכיר את הארגון. |
| תחליפים | **גבוה** | [פרשנות] התחליף העיקרי הוא עובד יח"צ שגולל פיד, או כלי זול כמו Brand24 או Buzzilla. גם הסוכנות הקיימת של הלקוח היא תחליף. |
| יריבות | **בינונית** בישראל, **גבוהה** בעולם | [עובדה] בישראל: Cyabra (ארגונים גדולים וממשלות), Buzzilla/Ifat (ניטור). בעולם: Blackbird, Alethea, Graphika, Osavul. |

**אטרקטיביות כוללת:** 3 מתוך 5 [פרשנות]. זו נישה שאפשר להיכנס אליה, בתנאי שהבידול הוא מקומיות ושירות, לא טכנולוגיה.

---

## 5. מפת שוק (תחרות)

הטבלה המלאה עם 36 שחקנים ומקורות נמצאת ב-`competitors.csv`. כאן מופיעים הרלוונטיים ביותר.

### 5.1 לפי כיוון
| כיוון | ענקיות כלליות | כלים זולים | שחקנים ורטיקליים | מקומיים (ישראל/אזור) |
|---|---|---|---|---|
| **1. טרנדים באופנה** | Brandwatch, Meltwater, Talkwalker | Brand24, Awario | [Heuritech (נקנתה ב-2024)](https://www.cbinsights.com/company/heuritech), WGSN, [Trendalytics (נקנתה ב-2024)](https://tracxn.com/d/companies/trendalytics/__N3Xd5bLsJoHM6-6Ddu6XXKQJKncHGdmL29871nDiRUA), EDITED, Nextatlas, Stylumia | לא נמצא שחקן ייעודי |
| **2. אותות מוקדמים לסיכון עסקי** | Sprinklr, Meltwater | – | [Dataminr](https://www.securityweek.com/dataminr-to-acquire-threatconnect-for-290-million/), [Signal AI](https://signal-ai.com/insights/press_release/signal-ai-announces-165-million-investment-round-led-by-battery-ventures-to-redefine-risk-and-reputation-intelligence/), Samdesk, Factal, Seerist | Webz.io (נתונים), BrandShield (התחזות) |
| **3. סיכוני נרטיב ומוניטין** | Brandwatch, Talkwalker, Sprout (NewsWhip) | Brand24, Mentionlytics | [Blackbird.AI](https://www.securityweek.com/blackbird-ai-raises-28-million-for-narrative-intelligence-platform/), [Alethea](https://alethea.com/insights/alethea-launches-risk-radar), Graphika, [Osavul](https://tech.eu/2024/09/12/kyivs-osavul-secures-unding-to-fight-disinformation-with-ai/) | **[Cyabra](https://www.nasdaq.com/press-release/cyabra-delivers-record-second-quarter-revenue-39-year-over-year-growth-2026-08-13)**, **[Buzzilla/Ifat](https://buzzilla.co.il/)**, [Lucidya](https://www.middleeastainews.com/p/lucidya-biggest-saudi-ai-funding), [Crowd Analyzer](https://crowdanalyzer.com/) |

### 5.2 סולם מחירים [עובדה, בעיקר ממקורות משניים]
| רמה | דוגמאות | מחיר |
|---|---|---|
| זול, בשירות עצמי | [Awario](https://leedlime.com/reviews/awario-review/), [Mentionlytics](https://www.xpoz.ai/blog/comparisons/social-listening-tools-pricing-compared-2026/), [Brand24](https://www.trustradius.com/products/brand24/pricing) | $24-$1,499 לחודש |
| ביניים | [YouScan](https://youscan.io/pricing/), [Talkwalker entry](https://presscable.com/insights/meltwater-vs-talkwalker-pros-cons-costs-alternatives/), [Sprinklr Essentials](https://chatarmin.com/en/blog/sprinklr-pricing) | $2.8K-$10K לשנה ומעלה |
| ארגוני | [Brandwatch](https://checkthat.ai/brands/brandwatch/pricing), [Meltwater](https://syncly.app/blog/brandwatch-vs-meltwater-vs-talkwalker), [Sprinklr Enterprise](https://chatarmin.com/en/blog/sprinklr-pricing) | $15K-$150K+ לשנה |
| מודיעין נרטיב | Cyabra, Blackbird, Alethea | לא מפורסם. אצל Cyabra דווחו עסקאות [של שש ספרות, כולל אחת מעל $500K](https://www.cbinsights.com/company/cyabra) |

**סתירה:** המחיר ההתחלתי של Awario מופיע כ-$24 במקור אחד וכ-$29 או $49 במקורות אחרים.

### 5.3 מפת מיצוב [פרשנות]
```
                 עומק ניתוח / שירות אנליסט  ↑
                                           |
   Cyabra · Blackbird · Alethea            |   ← לארגונים גדולים וממשלות
   Dataminr · Signal AI                    |
                                           |
          ┌──────────── הנישה ─────────────┐
          │ ניתוח נרטיב + אנליסט, במחיר    │
          │ של ארגון בינוני, עברית/ערבית   │
          └────────────────────────────────┘
                                           |
   Buzzilla · YouScan · Talkwalker         |
   Brand24 · Awario · Mentionlytics        |   ← דשבורד בשירות עצמי
  ─────────────────────────────────────────┼──────────→ מחיר
         נמוך                                        גבוה
```

### 5.4 מגמות מ-2024 עד 2026 [עובדה]
- **התכנסות:** Hootsuite קנתה את Talkwalker (2024), Sprout קנתה את NewsWhip (2025), Dataminr קנתה את ThreatConnect (2025), ו-Heuritech ו-Trendalytics נקנו (2024).
- **לחץ פיננסי על הענקיות:** [Cision (הבעלים של Brandwatch) גייסה $250M בהסדר חוב](https://www.prnewswire.com/news-releases/cision-announces-250-million-new-money-financing-refinancing-extension-of-debt-maturities-302427810.html), ו-[שילוב Brandwatch איטי](https://9fin.com/insights/cision-faces-margin-pressure-on-both-sides-compounding-slow-brandwatch-integration).
- **קריסה בתחום הדיסאינפורמציה:** Logically (2025). **שינוי כיוון:** [ActiveFence הפכה ל-Alice](https://www.calcalistech.com/ctechnews/article/hyk5chss11x) ועברה לאבטחת מודלי AI.

---

## 6. ניתוח לקוחות

**הקשר הישראלי [עובדה]:**
- [8.2 מיליון משתמשי פייסבוק (85.8% מהאוכלוסייה), 5.9 מיליון באינסטגרם](https://stats.napoleoncat.com/social-media-users-in-israel/) (אוגוסט 2026). [DataReportal: 7.01 מיליון זהויות משתמש ברשתות](https://datareportal.com/reports/digital-2026-israel).
- **סתירה:** NapoleonCat מדווחת על יותר משתמשי פייסבוק (8.2M) מאשר DataReportal על משתמשי רשתות בכלל (7.0M). ההסבר הסביר הוא שמדובר בקהל פרסומי מול זהויות ייחודיות, כלומר מדידות שונות.
- **מבצעי השפעה:** [רשת זרה התחזתה לקבוצות פייסבוק ישראליות בעזרת תוכן שנוצר ב-AI](https://www.timesofisrael.com/ai-tools-supercharge-foreign-influence-campaigns-targeting-israelis-on-social-media/). [חברה תל-אביבית הפעילה כ-1,000 חשבונות מזויפים](https://www.jpost.com/business-and-innovation/article-909100). [ישראל עדיין בלי גוף ממשלתי אחראי לנושא](https://www.timesofisrael.com/ai-tools-supercharge-foreign-influence-campaigns-targeting-israelis-on-social-media/).
- **חרמות:** [מותגים שנקשרו לישראל ספגו פגיעה במוניטין ובמכירות](https://www.business-humanrights.org/en/latest-news/iopt-companies-face-significant-financial-losses-from-boycotts-over-support-for-israel-study-finds/). [מקור טורקי מדווח על ירידות מניה של עד 15%](https://www.dailysabah.com/business/economy/2-years-into-gaza-genocide-global-boycotts-batter-brands-linked-to-israel), אבל זה מקור מוטה ולא אימתתי את הנתון.

**[פרשנות] מי מרגיש את הכאב הכי חזק:**
| פלח | הכאב | מי קונה | תקציב [הערכה] |
|---|---|---|---|
| מותגי צריכה ויצואנים ישראליים עם נוכחות בחו"ל | קמפייני חרם, הצפות ביקורות, נרטיבים עוינים בשפות זרות | סמנכ"ל שיווק או תקשורת, מנכ"ל | בינוני-גבוה |
| מוסדות ציבוריים (בתי חולים, אוניברסיטאות, רשויות) | משברים מקומיים, קבוצות פייסבוק, שמועות | דובר, מנהל תקשורת | נמוך-בינוני, והרכש איטי |
| סוכנויות יח"צ וניהול משברים | צריכות מודיעין ללקוחות ואין להן צוות מודיעין | שותף בסוכנות | בינוני, והן חוזרות כלקוחות |
| ארגונים יהודיים ופרו-ישראליים בחו"ל | אנטישמיות, דה-לגיטימציה, סיכון פיזי | מנהל אבטחה או תקשורת | בינוני-גבוה |
| חברות ביטחון וסייבר | מודיעין גלוי (OSINT) | – | גבוה, אבל Cyabra ו-Webz כבר שם |

---

## 7. טכנולוגיה ותשתית נתונים

| ספק | מודל תמחור | מחיר [עובדה] |
|---|---|---|
| [Bright Data](https://brightdata.com/pricing/web-scraper) | תשלום רק על רשומה שהתקבלה בהצלחה | כ-$1.5 ל-1,000 רשומות; מאגר פרופילי פייסבוק ב-$250 ל-100K |
| [Apify](https://apify.com/pricing) | מנוי + יחידות מחשוב | מ-$29 לחודש; $0.16-0.2 ליחידה |
| [EnsembleData](https://ensembledata.com/pricing) | יחידות יומיות | $100-$1,400 לחודש |
| [X API הרשמי](https://docs.x.com/x-api/getting-started/pricing) | תשלום לפי שימוש (מפברואר 2026) | $0.005 לקריאת פוסט; תקרה של 3M קריאות בחודש |

**[פרשנות] מה זה אומר:**
- **עלות הנתונים נמוכה ביחס למחיר השירות.** 100K רשומות בחודש עולות בערך $150 דרך Bright Data. העלות העיקרית היא אנליסט אנושי, לא נתונים.
- **קבוצות פייסבוק פרטיות ו-WhatsApp לא נגישות** בלי התחברות. דווקא שם רצים חלק מהמבצעים (ראו מקרה ISNAD). זו מגבלה מהותית שצריך להגיד ללקוח במפורש, ואסור לעקוף אותה בחשבונות מזויפים.
- **NLP בעברית:** קיימים מודלים פתוחים כמו [HeBERT/HebEMO](https://arxiv.org/pdf/2102.01909). [עובדה] Brandwatch [מצהירה על סנטימנט ב-40+ שפות](https://www.brandwatch.com/blog/data-science-behind-brandwatchs-new-sentiment-analysis/), ו-Talkwalker על [127+ שפות](https://www.talkwalker.com/sentiment-analysis). לא מצאתי אישור שעברית נכללת אצל אף אחת מהן. [פרשנות] בפועל, עברית וערבית מדוברת (סלנג, אירוניה, ערבית ישראלית) הן יתרון לשחקן מקומי. **כדאי לבדוק את זה בעצמך:** להריץ 100 פוסטים בעברית דרך trial של Brandwatch או Talkwalker.

---

## 8. רגולציה ומשפט (PESTLE: Legal)

### 8.1 מעמד ה-scraping (ארה"ב) [עובדה]
- **[Meta נגד Bright Data](https://www.fbm.com/publications/major-decision-affects-law-of-scraping-and-online-data-collection-meta-platforms-v-bright-data/)** (ינואר 2024): בית המשפט קבע שתנאי השימוש של פייסבוק ואינסטגרם **לא אוסרים איסוף של מידע ציבורי בלי התחברות**, ושסעיף "השרידות" שנועד לחול גם אחרי סגירת החשבון לא אכיף. [Meta ויתרה על התביעה](https://techcrunch.com/2024/02/26/meta-drops-lawsuit-against-web-scraping-firm-bright-data-that-sold-millions-of-instagram-records).
- **[X נגד Bright Data](https://www.mofo.com/resources/insights/240604-california-federal-court-holds-x-s-claims)** (מאי 2024): התביעה נדחתה, כי טענות ההפרה נדחקו מפני חוק זכויות היוצרים הפדרלי.
- **הסתייגויות:** [ההלכה לא קובעת ש-scraping חוקי תמיד](https://www.lowenstein.com/news-insights/publications/client-alerts/meta-v-bright-data-ruling-has-important-implications-for-webscraping-activities-by-investment-advisers-im). איסוף **תוך התחברות** כפוף לחוזה. [בתנאי השימוש של X יש פיצוי מוסכם](https://x.com/en/tos) של $15K לכל מיליון פוסטים מעל סף של מיליון ביממה.
- **[פרשנות]** מדובר בהחלטות של ערכאה ראשונה בקליפורניה, שאינן הלכה מחייבת במקומות אחרים. הסיכון החוזי נשאר בעיקר אצל הספק (Bright Data), אבל לא נעלם לגמרי אצלך.

### 8.2 פרטיות: GDPR [עובדה]
- **[רשות הפרטיות ההולנדית (מאי 2024)](https://www.hoganlovells.com/en/publications/dutch-dpa-issues-guidelines-on-data-scraping_1):** לפי הרשות, scraping "כמעט תמיד" לא חוקי, ואינטרס מסחרי טהור לא נחשב אינטרס לגיטימי. **סתירה:** [הנציבות האירופית ביקרה את הפרשנות, ובית משפט הולנדי השעה החלטת קנס שהתבססה עליה](https://www.hoganlovells.com/en/publications/dutch-dpas-fine-decision-suspended-by-dutch-court-amidst-commercial-legitimate). השאלה פתוחה.
- **[חוות דעת EDPB 28/2024](https://www.edpb.europa.eu/system/files/2024-12/edpb_opinion_202428_ai-models_en.pdf):** אפשר להסתמך על אינטרס לגיטימי במבחן תלת-שלבי, בבחינה פרטנית של כל מקרה. "זיהוי תוכן או התנהגות הונאתיים" מופיע כדוגמה לאינטרס לגיטימי.
- **הדוגמה הקיצונית:** [Clearview AI נקנסה ב-€30.5M](https://www.hoganlovells.com/en/publications/dutch-dpa-issues-guidelines-on-data-scraping_1) על איסוף תמונות ויצירת ביומטריה.

### 8.3 פרטיות: ישראל [עובדה]
- **[תיקון 13 לחוק הגנת הפרטיות](https://www.loc.gov/item/global-legal-monitor/2025-11-17/israel-amendment-to-privacy-protection-law-goes-into-effect/)** נכנס לתוקף ב-14.8.2025. הוא [מרחיב את הגדרת "מידע אישי"](https://iapp.org/news/a/israel-marks-a-new-era-in-privacy-law-amendment-13-ushers-in-sweeping-reform) למזהים מקוונים, מגדיר "מידע בעל רגישות מיוחדת" (המקורות מזכירים ביומטריה, מידע גנטי, רישום פלילי, נטייה מינית ומידע פיננסי; **לא אימתתי** אם דעות פוליטיות נכללות, וחשוב לבדוק את זה), ונותן לרשות להגנת הפרטיות סמכות להטיל עיצומים כספיים.
- **[הרשות הישראלית חתמה ב-2024 על ההצהרה הבינלאומית נגד scraping](https://ico.org.uk/about-the-ico/media-centre/news-and-blogs/2024/10/global-privacy-authorities-issue-follow-up-joint-statement-on-data-scraping-after-industry-engagement/).**
- **[לפי הנחיות הרשות בנושא AI](https://www.gornitzky.com/privacy-in-artificial-intelligence-systems-guidelines-of-the-israeli-privacy-protection-authority/)**, איסוף מידע אישי מהרשת לאימון מודל AI בלי הסכמה מדעת הוא פגיעה בפרטיות.

### 8.4 מה זה אומר למוצר [פרשנות, לא ייעוץ משפטי]
1. **לנתח נרטיבים, לא אנשים.** יחידת הניתוח צריכה להיות נרטיב, רשת חשבונות או ערוץ, ולא תיק על אדם פרטי. אישי ציבור וחשבונות מוסדיים הם מקרה שונה.
2. **איסוף בלי התחברות בלבד.** בלי חשבונות מזויפים ובלי כניסה לקבוצות סגורות. צריך להגדיר את זה בחוזה עם ספק הנתונים וגם בחוזה עם הלקוח.
3. **צמצום ושמירה:** לשמור רק את מה שצריך, למחוק בתוך X ימים, ולהסתיר שמות של אנשים פרטיים בדוחות.
4. **לא לאמן מודלים על המידע שנאסף** (בגלל הנחיית הרשות בנושא AI). להשתמש במודלים קיימים לצורך הסקה בלבד.
5. **תסקיר השפעה על הפרטיות (DPIA)** לפני לקוח ראשון, במיוחד כשהלקוח אירופי (ב-GDPR דעות פוליטיות הן מידע מקטגוריה מיוחדת) או כשמנתחים שיח פוליטי.
6. **לקוחות ממשלתיים ופוליטיים** מעלים סיכון תדמיתי ומשפטי. ראו מקרה IntelEye למעלה, והביקורת על [רכש מערכות ניטור בידי המדינה](https://www.haaretz.com/israel-news/2017-04-01/ty-article/.premium/israel-buys-social-media-monitoring-system-that-can-plant-ideas/0000017f-e31c-d568-ad7f-f37fc88f0000).

### 8.5 PESTLE בקצרה [פרשנות]
| | גורם | השפעה |
|---|---|---|
| פוליטי | מלחמה, חרמות, בחירות ב-2026, מבצעי השפעה | ↑ ביקוש |
| כלכלי | לחץ תקציבי על ארגונים בינוניים; ירידה בעלות הנתונים | ↔ |
| חברתי | קבוצות פייסבוק ו-WhatsApp דומיננטיות; טיקטוק צומח בקרב צעירים | ↑ ביקוש, ↓ נגישות |
| טכנולוגי | מודלי שפה מוזילים ניתוח; AI מייצר גם את האיום | ↑ |
| משפטי | תיקון 13, GDPR, תנאי השימוש של X | ↓ (עלות ציות) |
| סביבתי | לא רלוונטי | – |

---

## 9. הזדמנויות ואיומים

### 9.1 השוואת שלושת הכיוונים: טבלת ניקוד
סולם 1-5, **5 = הכי טוב בשבילך** (בתחרות, בקושי ובתלות, 5 = נמוך). **כל הציונים הם [הערכה] שלי, על בסיס הממצאים שלמעלה.**

| קריטריון | אופנה | סיכון עסקי | נרטיב (מקומי) |
|---|---|---|---|
| גודל הכאב | 3 | 4 | **4** |
| נכונות לשלם | 3 | 4 | 3 |
| רמת תחרות (5 = נמוכה) | 2 (Heuritech, WGSN) | 1 (Dataminr, Signal AI) | **3** |
| קושי טכני ומשפטי (5 = קל) | 2 (ראייה ממוחשבת, תמונות) | 2 (דורש מקורות רבים: חדשות, רגולציה) | **3** |
| תלות בפלטפורמות סגורות (5 = נמוכה) | 1 (אינסטגרם וטיקטוק = הכל) | 3 | **3** (פורומים ואתרי חדשות מקזזים) |
| זמן עד לקוח ראשון (5 = מהר) | 2 (מחזורי עונה, מעט מותגים בישראל) | 2 (רכש ארגוני) | **4** (משבר = החלטה מהירה) |
| **סה"כ (מתוך 30)** | **13** | **16** | **20** |

**נימוקים עיקריים:**
- **אופנה:** [עובדה] Heuritech [סורקת 3M תמונות ביום](https://heuritech.com/) ונקנתה על ידי Luxurynsight, ו-WGSN [גובה עד כ-$25K לשנה](https://fashiontheoryco.substack.com/p/wgsn-and-fashion-forecasting). [פרשנות] מספר מותגי האופנה בישראל שיקנו מודיעין טרנדים קטן, ורוב הערך נמצא בתמונות מאינסטגרם ומטיקטוק, בדיוק איפה שהגישה לנתונים הכי שברירית.
- **סיכון עסקי:** [עובדה] Dataminr גייסה [מעל $1B בסך הכל](https://fintech.global/2025/10/23/dataminr-buys-threatconnect-to-boost-ai-threat-intelligence/), ו-Signal AI משרתת [650+ ארגונים](https://signal-ai.com/insights/press_release/signal-ai-announces-165-million-investment-round-led-by-battery-ventures-to-redefine-risk-and-reputation-intelligence/). [פרשנות] אין דרך להתחרות בהן בכיסוי רחב. אפשר רק ב"סיכון נרטיבי" ממוקד, ואז זה בעצם כיוון 3.
- **נרטיב:** הכי הרבה כאב מקומי, תחרות מקומית חלקית, וזמן קצר עד לקוח ראשון.

### 9.2 בדיקת ההשערה המובילה
> "יש נישה פנויה של מודיעין סיכוני נרטיב לארגונים בינוניים, בעברית, ערבית וקהילות מקומיות, כשירות מנוהל של AI + אנליסט."

| רכיב | מחזיק? | ראיות |
|---|---|---|
| "סיכוני נרטיב" הוא כאב אמיתי | ✅ כן | חרמות, מבצעי השפעה, [WEF דירג נרטיבים עוינים כאיום מספר 1 (דרך Blackbird)](https://blackbird.ai/blog/blackbird-ai-reports-arr-growth-triples-customer-wins-and-secures-strategic-funding/) |
| "ארגונים בינוניים" לא מקבלים מענה | ✅ כנראה | Cyabra, Blackbird ו-Alethea מוכרים לארגונים גדולים וממשלות במחירים של שש ספרות; כלים זולים לא מנתחים נרטיב |
| "עברית, ערבית וקהילות מקומיות" זה פער | ⚠️ חלקית | Buzzilla מכסה עברית ופורומים; Lucidya ו-Crowd Analyzer מכסים ערבית במפרץ. **אין** מי שמשלב ניתוח נרטיב עם ערבית ישראלית ופלסטינית ועם קבוצות מקומיות |
| "שירות מנוהל עם AI ואנליסט" | ✅ בידול | Factal כבר עובדת במודל היברידי של AI ועיתונאים, אז המודל מוכח. בישראל לא מצאתי שירות כזה לארגונים בינוניים |
| "נישה פנויה" מספיק גדולה | ❌ לא, בישראל לבד | SOM של $0.65-0.9M. צריך התרחבות לחו"ל |

**המתחרים הקרובים ביותר:**
1. **Buzzilla/Ifat.** יש להם נתונים בעברית, לקוחות יח"צ וקשר לממשלה. אם יוסיפו שכבת ניתוח נרטיב, הם יכולים לסגור את הפער. זה האיום המיידי.
2. **Cyabra.** ישראלית ונסחרת בבורסה, וצריכה צמיחה. [הכנסות של $1.85M ברבעון](https://www.tradingview.com/news/tradingview:e1a1915f878b8:0-cyabra-inc-q2-2026-revenue-1-85m-eps-0-26-10-q-summary/) ו[הפסד של $3.44M](https://www.tradingview.com/news/tradingview:e1a1915f878b8:0-cyabra-inc-q2-2026-revenue-1-85m-eps-0-26-10-q-summary/). [פרשנות] היא עשויה לרדת לשוק הבינוני עם מוצר זול יותר.
3. **סוכנויות יח"צ עם צוות ניטור פנימי.** זה תחליף, אבל גם ערוץ הפצה אפשרי.

**סיכונים:**
| סיכון | חומרה | הפחתה |
|---|---|---|
| שוק מקומי קטן | גבוהה | להתרחב לארגונים ישראליים ויהודיים בחו"ל (נישה 3) |
| חסימה בפלטפורמות או שינוי מחירים אצל הספקים | גבוהה | לעבוד עם שני ספקים לפחות; להוסיף פורומים, אתרי חדשות וטוקבקים |
| עסק שלא מתרחב כי הוא תלוי באנליסטים | בינונית | תבניות דוח; AI לטיוטה ואנליסט לאישור; מחיר לפי היקף |
| רגולציה (תיקון 13, GDPR) | בינונית | ניתוח ברמת נרטיב, DPIA, צמצום מידע |
| תדמית של "חברת מעקב" | בינונית | לא לעבוד עם לקוחות פוליטיים; מדיניות שימוש מפורסמת |
| תלות בלקוח או חוזה גדול אחד (לקח Logically) | בינונית | לפזר בין הרבה לקוחות בינוניים |

### 9.3 SWOT (לנישת הנרטיב המקומי) [פרשנות]
| **חוזקות** | **חולשות** |
|---|---|
| שפה ותרבות מקומיות, שירות אנליסט, מחיר נגיש | אין מותג, אין נתונים ייחודיים, תלות בספקים |
| **הזדמנויות** | **איומים** |
| חרמות, בחירות 2026, מבצעי השפעה, אין גוף ממשלתי אחראי, סוכנויות יח"צ כערוץ | Buzzilla/Ifat או Cyabra יורדות לשוק הבינוני; חסימות בפלטפורמות; תיקון 13 |

---

## 10. המלצות אסטרטגיות

### נישה 1: מודיעין סיכוני נרטיב לארגונים ישראליים בינוניים שחשופים לחו"ל ⭐ (מומלצת ראשונה)
- **ICP:** חברה ישראלית עם 100-1,000 עובדים, עם מותג צרכני או ייצוא, ועם נוכחות ב-2 שווקים זרים לפחות (אירופה או ארה"ב). **קונה:** סמנכ"ל שיווק או תקשורת. **טריגר:** משבר או קריאה לחרם ב-12 החודשים האחרונים.
- **הצעת ערך:** "תדעו על קמפיין נגדכם 48 שעות לפני שהוא מגיע לתקשורת, בעברית, ערבית ואנגלית, עם אנליסט שממליץ מה לעשות, במחיר של עשירית מכלי ארגוני."
- **תמחור ראשוני [הערכה]:** ריטיינר של **$1,500-$3,500 לחודש**: ניטור רציף, דוח שבועי, התראות, ושעת אנליסט. **כוננות משבר:** $2,000-$5,000 לאירוע. [פרשנות] זה ממקם אותך מעל Brand24 ($199-$1,499) ומתחת לארגוניים ($15K-$150K לשנה).

### נישה 2: white-label לסוכנויות יח"צ וניהול משברים (ערוץ הפצה)
- **ICP:** סוכנות יח"צ ישראלית עם 10-80 עובדים ו-20+ לקוחות, בלי צוות מודיעין. **קונה:** שותף מנהל.
- **הצעת ערך:** "מחלקת מודיעין בלי לגייס אנליסטים. דוחות עם הלוגו שלכם ללקוחות שלכם."
- **תמחור [הערכה]:** $800-$1,500 לחודש לכל לקוח קצה, או חבילה של 5 לקוחות ב-$4,000-$6,000 לחודש.
- **למה:** זה מקצר את הזמן עד לקוח ראשון, כי סוכנות אחת מביאה כמה לקוחות.

### נישה 3: ארגונים יהודיים ופרו-ישראליים בחו"ל (התרחבות)
- **ICP:** ארגון קהילתי יהודי, אוניברסיטה, או מותג בינלאומי עם זיקה לישראל, בארה"ב, בריטניה או צרפת. **קונה:** מנהל אבטחה או תקשורת.
- **הצעת ערך:** "מודיעין על נרטיבים עוינים בערבית, עברית ואנגלית, עם הקשר מקומי שלא תקבלו מ-Brandwatch."
- **תמחור [הערכה]:** $3,000-$8,000 לחודש.
- **שימו לב:** זה פלח רגיש פוליטית. מדיניות אתית ברורה היא תנאי הכרחי, וצריך ייעוץ GDPR ללקוחות באירופה.

### מפת דרכים [פרשנות]
| שלב | זמן | מה |
|---|---|---|
| 1 | חודש 1 | 10 ראיונות אימות (שאלות בהמשך); ייעוץ ראשוני עם עו"ד פרטיות |
| 2 | חודשים 1-2 | פיילוט ידני: Bright Data או Apify + מודל שפה + אנליסט (את). 2-3 לקוחות בחינם או בהנחה, בתמורה למקרה בוחן |
| 3 | חודשים 3-4 | שותפות עם סוכנות יח"צ אחת (נישה 2); תבנית דוח קבועה |
| 4 | חודשים 5-6 | 5-8 לקוחות משלמים; להחליט אם להתרחב לחו"ל (נישה 3) |

**מדדי הצלחה:** 3 לקוחות משלמים עד חודש 4, שיעור נטישה מתחת ל-10% ברבעון, ולפחות מקרה אחד שבו התרעה מוקדמת שינתה החלטה אצל הלקוח.

---

## 11. נספחים

### 11.1 שאלות לראיונות אימות (10 לקוחות פוטנציאליים)
השאלות נפתחות ולא מובילות. לא לשאול "היית משלם על X?", אלא לשאול על מה שכבר קרה.

1. ספר/י לי על הפעם האחרונה שמשהו ברשת פגע בארגון, או כמעט פגע. מה קרה, ומתי ידעתם על זה?
2. איך גיליתם את זה? מי גילה, ומאיזה ערוץ (לקוח, עיתונאי, עובד, כלי ניטור)?
3. כמה זמן עבר מתחילת השיח ועד שהגבתם? מה זה עלה לכם (כסף, זמן, מכירות, תדמית)?
4. מה אתם עושים היום כדי לעקוב אחרי מה שאומרים עליכם? אילו כלים, מי אחראי, וכמה שעות בשבוע זה לוקח?
5. כמה אתם משלמים היום על ניטור או יח"צ או ייעוץ משברים, ומאיזה תקציב זה יוצא?
6. באילו שפות ובאילו פלטפורמות מתנהל השיח עליכם? יש דברים שאתם יודעים שאתם מפספסים?
7. מה הדבר הכי מתסכל בכלי או בספק הנוכחי שלכם?
8. אם הייתה לכם התרעה 48 שעות מוקדם יותר באירוע האחרון, מה הייתם עושים אחרת?
9. מי בארגון היה צריך לאשר רכישה של שירות כזה, ומה התהליך?
10. מה היה גורם לכם **לא** לסמוך על שירות כזה (פרטיות, דיוק, סודיות)?
11. (לסוכנויות) כמה מהלקוחות שלכם ביקשו מודיעין או ניטור בשנה האחרונה? מה עשיתם?
12. (לסיום) את מי עוד כדאי שאדבר איתו?

**טיפ מתודולוגי (סקיל market-sizing):** 10 ראיונות מספיקים לגילוי כיוון, לא למדידה. אם תעשי אחר כך סקר כמותי, צריך לחשב מדגם מינימלי לכל פלח בנפרד: `sample_size_planner.py`.

### 11.2 סתירות בין מקורות (ריכוז)
| נושא | הסתירה |
|---|---|
| גודל השוק ב-2026 | $10.9B מול $11.9B מול $12.15B; שיעור צמיחה של 11-17% |
| שוק הדיסאינפורמציה | $1.8B (2025) מול "$30B עד 2028", כנראה בגלל הגדרות שונות. שני הנתונים מגיעים דרך Blackbird, מקור בעל אינטרס |
| משתמשים בישראל | פייסבוק 8.2M (NapoleonCat) מול 7.0M משתמשי רשתות בכלל (DataReportal) |
| מחיר Awario | מ-$24 מול מ-$29 מול מ-$49 |
| גיוסי Trendalytics | $3.59M מול $4.31M |
| scraping ו-GDPR | רשות הפרטיות ההולנדית (מחמירה) מול בית המשפט ההולנדי והנציבות (מקלים) |
| הכנסות Cyabra | 2025: $5.7M הכנסות; יוני 2026: $8.1M ARR. אין כאן סתירה, אלה שני מדדים שונים |

### 11.3 מתודולוגיה ומגבלות
- כ-30 חיפושים ברשת, ספטמבר 2026. עדיפות למקורות מ-2025-2026, והתאריכים מצוינים.
- מחירי ספקים שלא מפרסמים מחיר מגיעים מאתרי השוואה (צד שלישי), והם פחות אמינים.
- לא נמצאו נתונים על מספר החברות הבינוניות בישראל או על תקציבי ניטור בישראל, ולכן גודל השוק המקומי מבוסס על הנחות.
- לא אומתה תמיכה בעברית אצל Brandwatch ו-Talkwalker.
- הגישה ל-mcpmarket.com חסומה בסביבה הזו. זה לא השפיע על המחקר.
- יומן מקורות מלא: `research/notes.md`.
