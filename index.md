<div dir="rtl" markdown="1">

# מדיניות פרטיות, תוסף "בחרתי בי"

**עודכן לאחרונה: 23.8.2026 · גרסת תוסף 0.1.0**

## בקצרה

כל מה שהתוסף יודע עלייך שמור במחשב שלך, בתוך `Chrome`, ובשום מקום אחר. אין שרת, אין חשבון, אין הרשמה, ואין בתוסף שורת קוד אחת ששולחת משהו לאינטרנט. גם הפונטים והתמונות ארוזים בתוך התוסף עצמו, ולכן אפילו הם לא נטענים מהרשת, והתוסף לא מוריד קוד משום מקום בזמן שהוא רץ.

הדף הזה מפרט בדיוק מה נשמר, מה לא נאסף אף פעם, למה כל הרשאה נחוצה, ואיפה בכל זאת יש דברים שכדאי שתדעי.

## 1. מה נשמר

הכל נשמר במקום אחד: `chrome.storage.local`, האחסון המקומי של התוסף בדפדפן שלך, במחשב שלך.

**הקבלות שלך.** לכל קבלה: השם שנתת לה, האתרים או הפינות שבחרת (אתר שלם, או רק פינה אחת בתוכו), סוג הכלל, מכסה יומית בדקות או שעות שבהן את לא שם, נקודת הפתיחה שממנה יצאת, ותאריך היצירה.

**הדרך והרצף.** לכל קבלה בנפרד: הרצף הנוכחי, הרצף הארוך ביותר, מספר הימים שעמדת בה, התחנות שהגעת אליהן, ואם נפלת, באיזה יום זה קרה. נפילה בקבלה אחת לא נוגעת באחרות, וכל מספר כזה יושב בתוך הקבלה שלו.

**זמן יומי לפי אתר.** לכל יום נשמרת שורה אחת: כמה שניות היית באתר שנקבת בשמו. רק אתרים שאת בחרת נמדדים. אתר שלא רשום באף קבלה שלך לא נספר בכלל, ולא נכתבת עליו שום שורה. הרשומות היומיות האלה נמחקות לבד אחרי 45 יום.

**זמן בתוך שעות שסימנת.** אם הגדרת קבלה שהיא שעות ולא מכסה, נשמר לכל יום כמה שניות היית מול המסך בתוך השעות שאמרת שאת לא שם, בנפרד לכל קבלה. זה מה שקובע אם עמדת בה באותו יום.

**הארכות של 5 דקות.** כמה הארכות נוצלו השבוע (המאגר משותף לכל הקבלות, שלוש בשבוע), כמה נלקחו היום, ועד מתי הארכה פעילה תקפה. גם אלה נמחקות לבד אחרי 45 יום.

**יומן אירועים מקומי.** עד 500 האירועים האחרונים. כל רשומה היא סוג האירוע, התאריך והשעה שלו, מזהה הקבלה שהוא שייך לה, ומספר קטן שמתאר אותו: באיזה יום מדובר, כמה דקות, או איזו תחנה. הסוגים הם יום שעמדת בו, נפילה, הארכה, "הקבלה של עכשיו" שהצליחה או שנשברה, תחנה שהגעת אליה, ולחיצה על "קשה לי עכשיו". אין ביומן טקסט חופשי, ואין בו אף כתובת של אתר.

**שעות קבועות.** הימים והשעות שבחרת לכל טווח כזה. יש היקף אחד בלבד: בשעות האלה מסך העצירה מופיע על **כל** אתר בדפדפן הזה, גם אתרים שאין להם שום קשר לקבלות שלך. גם הבנק, גם אתר בית הספר, גם המייל. זו הבחירה שלך והיא נשמרת כמו שהיא, אבל כדאי לדעת בדיוק מה היא עושה לפני שבוחרים אותה. מי שרוצה שעה על מקום מסוים בלבד מגדירה קבלה עם חלון שעות משלה, במקום שעות קבועות.

**"הקבלה של עכשיו", האוצר והאוסף.** הקבלה הקצרה שפעילה עכשיו אם יש כזאת, סך הדקות שצברת באוצר, והסמלים שנשמרו באוסף שלך.

**ההערה האישית שלך.** מה שכתבת בשאלה "על מה את רוצה לעבוד", וגם הטיוטה של השאלות הראשונות אם עצרת באמצע: הקישור שהדבקת, השם שנתת, וההערה. שימי לב: שני הדברים האלה **לא נמחקים לבד**. אם עצרת באמצע ההגדרה הראשונה ולא חזרת, אחרי יממה התוסף כבר לא יציע לך להמשיך מאותה נקודה, אבל מה שכתבת נשאר שמור במחשב שלך עד שתאפסי או תסירי את התוסף.

**סימנים פנימיים קטנים.** באיזה יום נעשה החישוב האחרון, אם כבר הוצגה היום התזכורת "נשארו 10 דקות" (לכל קבלה בנפרד), אם כבר נשלחה היום תזכורת הצ׳ק-אין, ומתי נוקו הרשומות הישנות.

**הלשונית הפעילה ברגע זה.** כדי שהשעון יידע איפה הוא עומד, התוסף מחזיק רשומה אחת עם הכתובת המלאה של הלשונית שפתוחה מולך עכשיו, כולל כל מה שבא אחרי סימן השאלה בכתובת, ועם השנייה שממנה הספירה רצה. הרשומה נכתבת מחדש בכל מעבר לשונית וגם כל דקה, ונמחקת כשאת מתרחקת מהמחשב או מקטינה את החלון. היא לא נצברת להיסטוריה ולא נשלחת לשום מקום. אם פשוט סגרת את המחשב בלי לקום ובלי לעבור לחלון אחר, הערך האחרון נשאר שמור שם עד הפעם הבאה. זה המקום היחיד שבו כתובת של אתר שאינו בקבלות שלך נוגעת באחסון בכלל.

## 2. מה לא נאסף לעולם

- **אין חשבון ואין הרשמה.** לא מייל, לא סיסמה, לא שם, לא מספר טלפון, לא גיל.
- **אין שרת.** אין בתוסף שום פנייה לאינטרנט, ולכן אין לאן לשלוח. אין כתובת בצד השני.
- **אין קוד מרוחק.** כל הקוד שרץ ארוז בתוך התוסף ונבדק על ידי חנות כרום. התוסף לא מוריד ולא מריץ קוד מהאינטרנט, וזה גם אסור בכללי החנות.
- **אין כלי מדידה ואין צד שלישי.** לא `Google Analytics`, לא פרסומות, לא ספריות חיצוניות, לא כלים שסופרים משתמשים.
- **אין היסטוריית גלישה.** אתרים שלא נקבו בשם בקבלות שלך אינם נספרים, אינם מוצגים ואינם נשמרים — לעולם. התוסף לא בונה רשימה של איפה היית. יוצא דופן אחד, בבחירה שלך בלבד: בהגדרה הראשונה יש קישור קטן, "לא בטוחה? אפשר לבדוק את זה יחד." אם לחצת עליו ואישרת ל-`Chrome`, התוסף קורא פעם אחת, בזיכרון בלבד, את ההיסטוריה של עד 30 הימים האחרונים (לפעמים פחות — סעיף 3), מחשב ממנה הערכה של דקות ביום באתרים שבחרת (רק אם היו שם מספיק ביקורים על פני מספיק ימים שונים — גם זה בסעיף 3), ומשחרר את ההרשאה מיד. הקריאה הזאת בודקת גם מתי הגעת לאתרים שלא נקבעו בשם — לא כדי לספור אותם, אלא כי רגע ההגעה אליהם הוא מה שמלמד את התוסף מתי נגמר הביקור באתר שכן נקבע בשם. שום אתר שלא נקבע בשם לא נספר, מוצג או נשמר בשום שלב. ההיסטוריה עצמה לא נשמרת ולא נשלחת; רק המספר, ורק אם אישרת אותו, נכנס לקבלה, כאילו סובבת את הגלגל בעצמך. הפירוט בסעיף 3.
- **מה שנכתב בשיחה עם אורה לא נשמר ולא נשלח.** ההודעות חיות בחלון הפתוח בלבד, וברגע שסוגרים אותו הן נעלמות. בפיילוט אין מחשב אחר שעונה, וגם אין לאן לשלוח.
- **אין סנכרון בין מחשבים.** התוסף לא משתמש ב-`chrome.storage.sync`, ולכן הנתונים לא עוברים דרך חשבון הגוגל שלך למכשיר אחר.
- **אין מכירה ואין שיתוף.** בגרסה הזו (0.1.0) התוסף לא שולח שום דבר לשום מקום, ולכן אין נתונים למכור. זו לא רק הבטחה: שער האריזה בודק את זה בכל בנייה, ונכשל אם מתגלה בקוד המופץ קריאת רשת או כתובת חיצונית כלשהי (`docs/packaging.md`, שער 1).

## 3. למה כל הרשאה נחוצה

כשמתקינים את התוסף, `Chrome` מציג רשימת הרשאות. זו הרשימה המלאה:

| הרשאה | למה היא נחוצה |
|---|---|
| `storage` | לשמור את הקבלות, הרצף, הזמנים והיומן במחשב שלך. בלעדיה הכל היה נמחק ברגע שסוגרים את הדפדפן. |
| `alarms` | `Chrome` מרדים את התוסף אחרי כחצי דקה של שקט. שעון פנימי מעיר אותו כל דקה כדי לצבור את הזמן, לסגור את היום, ולהראות את מסך העצירה תוך דקה מהרגע שהזמן נגמר. |
| `idle` | לזהות שקמת מהמחשב אחרי 60 שניות של חוסר פעילות, ולעצור את הספירה. דקות שלא היית שם לא ייספרו נגדך. |
| `scripting` | `Chrome` מכניס את סקריפט הליווי רק לדפים שנפתחו אחרי ההתקנה. ההרשאה הזאת מאפשרת להיכנס גם ללשוניות שכבר היו פתוחות ברגע ההתקנה או העדכון, כדי שהדף שישבת עליו בדיוק אז לא יישאר נקודה עיוורת. |
| `notifications` | הודעות קטנות מהתוסף עצמו: כשעמדת ב"קבלה של עכשיו", כשנשארו כעשר דקות בקבלת מכסה יומית, ותזכורת צ׳ק-אין אחת ביום בשעה שבחרת. אף אחת מהן לא מופיעה מהשעה שקבעת ביום שישי ועד מוצאי שבת, ולא בשעות שקטות שהגדרת. אם השעה שבחרת לתזכורת חלה בתוכן, ההתראה נדחית לרגע הראשון שבו הן נגמרות **באותו יום**, ולא נשלחת בלי שתדעי בזמן שלא ביקשת. **ביום שישי בדרך כלל אין רגע כזה, ולכן תזכורת הצ׳ק-אין של יום שישי לא נשלחת בכלל:** אי אפשר לבחור תזכורת מוקדמת מ-17:00, וברירת המחדל של יום שישי מתחילה כבר ב-15:00. אם תקבעי ליום שישי שעה מאוחרת יותר, התזכורת של אותו יום נשלחת כרגיל. ההודעות נוצרות במחשב שלך ולא עוברות דרך שום שירות. |

### הרשאה אחת שלא במסך ההתקנה

יש הרשאה אחת שלא מופיעה ברשימה שלמעלה ולא במסך ההתקנה. היא מוצהרת בקובץ התוסף כאופציונלית (`optional_permissions`), ולכן `Chrome` מבקש אותה רק ברגע שאת לוחצת על כפתור מסוים בתוסף, ולא לפני.

| הרשאה | למה היא נחוצה |
|---|---|
| `history` | בשאלה "כמה זמן את שם ביום?" בהגדרה הראשונה יש קישור קטן: "לא בטוחה? אפשר לבדוק את זה יחד." רק אם לחצת עליו, `Chrome` שואל אותך אם לאפשר לתוסף לקרוא את ההיסטוריה. שימי לב לנוסח של החלון עצמו: כרום מציג לבקשה הזאת תמיד את המשפט הקבוע שלו, "Read and change your browsing history on all signed-in devices." התוסף לא משנה שום היסטוריה ולא קורא ממכשירים אחרים; אלה מילותיו של כרום לכל בקשת `history`, לא תיאור של מה שהתוסף עושה. אם אישרת, התוסף קורא פעם אחת את הביקורים של עד 30 הימים האחרונים — בפרופיל עמוס במיוחד ייתכן שפחות מזה בפועל, כי הקריאה מוגבלת למספר פריטים קבוע ולא לכל ה-30 יום בכל מחיר, בלי שהתוסף מודיע על כך בנפרד. מהביקורים האלה הוא מחשב הערכה של דקות ביום באתרים שבחרת, אבל רק לאתר שביקרת בו בחמישה ימים שונים לפחות בטווח, ושהזמן שנצבר בו מספיק כדי לעגל למעלה מדקה ביום; אם אחד מהתנאים האלה לא מתקיים, התוסף אומר בפירוש "יש ביקורים, אבל לא מספיק כדי להעריך" במקום להעמיד פנים שיש מספיק מידע. הקריאה נעשית בזיכרון בלבד ולוקחת בדרך כלל שניות ספורות; בפרופיל עם היסטוריה עמוסה במיוחד היא עשויה להתארך, אבל היא תמיד קצובה (עד כ-250 קבוצות קריאה עוקבות, עד 20 אתרים בכל קבוצה). היא בודקת גם מתי הגעת לאתרים שלא נקבעו בשם באחת הקבלות שלך — לא כדי לספור אותם, אלא כי רגע ההגעה אליהם הוא מה שמלמד את התוסף מתי נגמר הביקור באתר שכן נקבע בשם. שום אתר שלא נקבע בשם לא נספר, מוצג או נשמר בשום שלב; רק העיתוי של ההגעה אליו נבדק לרגע, בזיכרון, ונשכח. עם סיום הקריאה התוסף מחזיר את ההרשאה מיד, עוד לפני שהמספר מוצג לך; ואם לשונית ההגדרה נסגרת באמצע הקריאה בלי שההרשאה הוחזרה (קריסה, סגירת הדפדפן), בדיקה קצרה בהפעלה הבאה של הדפדפן, או בעדכון התוסף, מוודאת שההרשאה לא נשארת פתוחה בלי סיבה. שום ביקור, כתובת או תאריך לא נכתב לאחסון ולא נשלח לשום מקום. רק המספר, ורק אם אישרת אותו, נכנס לשדה, בדיוק כאילו סובבת את הגלגל בעצמך. אם סירבת, לא קורה כלום, וההערכה שלך מספיקה. המספר שמוצג הוא הערכה ולא מדידה: ההיסטוריה יודעת מתי נכנסת לאתר, לא כמה זמן נשארת בו. |

### ההרשאה לכל האתרים, `https://*/*` ו-`http://*/*`

זו ההרשאה הרחבה, וזה ההסבר המלא עליה.

ההרשאה הזאת היא גם מה שמאפשר לתוסף לדעת איזו לשונית פתוחה מולך עכשיו ומה הכתובת שלה. בלי זה השעון לא יודע אם הוא בכלל צריך לרוץ, ואי אפשר לשלוח לאותה לשונית את מסך העצירה או את התזכורת. התוסף לא מחזיק הרשאה לקרוא את היסטוריית הגלישה שלך: הוא רואה את הדף שפתוח מולך ברגע זה, ולא את רשימת המקומות שהיית בהם. הרגע היחיד שבו הוא מבקש הרשאה כזאת, בלחיצה שלך בלבד ולזמן קצוב (בדרך כלל שניות ספורות — הפירוט המלא, כולל הגבול העליון, למעלה תחת "הרשאה אחת שלא במסך ההתקנה"), מתואר שם.

את בוחרת את האתרים שלך אחרי ההתקנה, ואת יכולה לשנות אותם בכל יום. אין דרך ב-`Chrome` להגיד מראש "רק האתרים שהיא תבחר מחר", ולכן התוסף מבקש גישה רחבה ומצמצם אותה בעצמו בקוד.

בפועל, בכל דף שנפתח יושב סקריפט קטן ששואל את התוסף שאלה אחת: האם הדף הזה אמור להיעצר עכשיו. הוא שואל כשהדף נטען, ואז שוב כל 30 שניות כל עוד הלשונית פתוחה, והוא שולח לשם את הכתובת המלאה של הדף. השאלה והתשובה נשארות בתוך התוסף במחשב שלך, ולא נכתבת מהן שום שורה לאחסון. ברוב המוחלט של הדפים התשובה היא "לא", ואז פשוט לא קורה כלום.

מתי מסך העצירה כן מופיע: באתרים שרשומים בקבלות שלך, כשעברת את הזמן שקבעת. וגם, אם הגדרת שעות קבועות וסימנת בהן "בכל הדפדפן", בשעות האלה על כל אתר בדפדפן הזה, כולל אתרים שאין להם קשר לקבלות שלך. בלי ההרשאה הרחבה אי אפשר להראות את מסך העצירה במקומות שאת בוחרת, ואי אפשר להגיע ללשוניות שכבר היו פתוחות. היא לא קיימת כדי לקרוא את הגלישה שלך.

התוסף גם מגיש לדף את הקבצים `fonts/*` ו-`character/v3/*` מתוך הקובץ שלו עצמו, כדי שמסך העצירה ייראה נכון בלי להוריד שום דבר מהאינטרנט. שני אלה בלבד, ובכתובת שמתחלפת בכל הפעלה של הדפדפן — כך שאתר לא יכול לבדוק אם הם קיימים אצלך, ולהסיק מכך שהתוסף מותקן.

## 4. מי יכול לראות את הנתונים

**מהתוסף עצמו: רק את.** שרה, שבנתה את התוסף, לא רואה ממנו כלום. לא בגלל הבטחה, אלא כי אין לאן שזה יגיע: אין שרת, אין מסד נתונים, ואין שורת קוד ששולחת. הנתונים יושבים בפרופיל ה-`Chrome` שלך, כמו כל דבר אחר בדפדפן שלך, ומי שיש לו גישה למחשב ולפרופיל שלך יכול לפתוח את התוסף ולראות מה מופיע בו.

**המשוב בפיילוט הוא סיפור אחר, וחשוב שתדעי אותו.** במהלך הפיילוט אנחנו מבקשות משוב דרך **טופס גוגל**. הטופס הזה אינו חלק מהתוסף: הוא מתארח אצל גוגל, והתשובות שתכתבי בו נשמרות בשרתים של גוגל ומגיעות לשרה. התוסף לא ממלא אותו בשבילך, לא שולח אליו כלום ולא יודע שהוא קיים. את פותחת אותו בעצמך, כותבת מה שאת בוחרת לכתוב, ורק זה מגיע. אם את לא רוצה לענות, פשוט אל תעני, והתוסף ימשיך לעבוד בדיוק אותו דבר.

## 5. מחיקה

יש שתי דרכים למחוק, וגם דברים שנמחקים לבד.

1. **כפתור האיפוס בתוך התוסף.** בתחתית החלון של התוסף יש כפתור שכתוב עליו **"התחלה מחדש"**, והוא מוחק את כל האחסון המקומי בבת אחת. שימי לב מתי הוא מופיע: רק כשכבר יש לך קבלה, ורק אחרי שאישרת נפילה אם הייתה כזאת. במסך של הבוקר שאחרי נפילה, ולפני שהגדרת קבלה ראשונה, הכפתור לא על המסך. אין "סל מיחזור" ואין גיבוי, ולכן זו מחיקה סופית.
2. **הסרת התוסף מ-`Chrome`.** כשמסירים תוסף, `Chrome` מוחק את כל האחסון המקומי שלו. זו הדרך שמוחקת הכל בוודאות, בכל מצב.
3. **מה שנמחק לבד.** רשומות הזמן היומיות, רשומות ההארכות ורשומות השעות נמחקות אחרי 45 יום, ויומן האירועים שומר רק את 500 האירועים האחרונים.

**ומה שלא נמחק לבד:** הקבלות עצמן, הרצפים והדרך, האוצר והאוסף, השעות הקבועות, ההערה האישית שכתבת וטיוטת ההגדרה הראשונה. כל אלה נשארים עד שתלחצי על איפוס או תסירי את התוסף.

## 6. ילדים ונוער

בין המשתתפות בפיילוט יש נערות, ולכן מגיע לומר את הדברים במפורש.

התוסף לא שואל בת כמה את, לא מבקש שום פרט מזהה, ולא יוצר חשבון. אין בו רכישות, אין פרסומות, ואין תוכן שמגיע מבחוץ. התוסף עצמו לא שולח שום דבר עלייך לאף אחד.

יחד עם זאת, שני דברים חשוב שתדעי, והם כתובים למעלה בהרחבה. אחד מהם, המחשב המשותף, הוא תנאי לפני שמתקינים, לא רק עובדה לידיעה:

- **טופס המשוב של הפיילוט מתארח אצל גוגל** (סעיף 4). מה שתכתבי בו נשמר אצל גוגל ומגיע לשרה. זו הבחירה שלך בכל פעם מחדש, ואפשר גם פשוט לא לענות.
- **מחשב משותף: זה לא רק עניין של מי רואה, זה תנאי.** אם את משתמשת בפרופיל `Chrome` שגם אחרים נכנסים אליו, יש לזה שתי תוצאות. הראשונה: מי שפותח את התוסף על אותו פרופיל רואה את מה שיש בו, הקבלות, הרצפים, וההערה שכתבת. השנייה, והיא החמורה מבין השתיים: התוסף סופר את כל הגלישה שקורית על הפרופיל, לא רק את שלך, כך שגלישה של מישהו אחר יכולה לאפס את הרצף שלך על יום שלא נפלת בו. פרופיל `Chrome` נפרד, רק שלך, פותר את שני הדברים באותה פעולה, ולכן `docs/install-guide.md` מציג אותו כתנאי לפני שמתקינים, לא כהמלצה.

לנערה מתחת לגיל 18: כדאי שההורה שלך יידע על ההתקנה ויאשר אותה, ואפשר להראות לו בדיוק את הדף הזה. חשוב גם לומר את הצד השני: התוסף אינו כלי בקרה הורית. אין מסך שמראה להורה מה עשית, ואין דוח שנשלח לאף אחד.

## 7. שינויים במדיניות

אם משהו במוצר ישתנה באופן שנוגע לנתונים, הדף הזה יתעדכן והתאריך שלמעלה ישתנה. אם אי פעם ייכנס חלק ששולח משהו החוצה, למשל שיחה עם אורה שנענית ממחשב אחר, זה לא יקרה בשקט: יופיע מסך הסכמה מפורש שמסביר מה נשלח ולמה, ותהיה לך אפשרות לומר לא ולהמשיך להשתמש בתוסף כרגיל.

## 8. יצירת קשר

שאלה, בקשה או משהו שלא ברור בדף הזה: ani.bacharti.bi@gmail.com


</div>

<div dir="ltr" markdown="1">

## English summary

**Extension:** בחרתי בי ("I Chose Myself"), version 0.1.0. **Last updated: 23 August 2026.**

**Everything stays on the user's own computer.** The extension has no server, no backend, no account and no sign-up. It contains no network calls of any kind: no `fetch`, no `XMLHttpRequest`, no analytics, no third-party libraries, no telemetry. Fonts and images are bundled inside the extension package, so even those are never fetched. No remotely hosted code is loaded or executed at any point.

**What is stored**, all of it in `chrome.storage.local` on the user's device:

- The commitments she creates: name, the sites or specific site sections she chose, her rule (a daily limit in minutes, or hours during which she is not there), her starting baseline, creation date.
- Her progress per commitment: current streak, longest streak, days kept, milestones reached, and whether she went over on a given day.
- Daily time spent on the sites she named, as seconds per site per day. Sites she did not name are never measured and never written. Auto-deleted after 45 days.
- For an hours-based commitment: per day and per commitment, the seconds spent at the screen inside the hours she declared she is away. This is what decides whether that day was kept.
- Use of the shared weekly pool of three 5-minute extensions.
- A local event journal, capped at the last 500 entries. Each entry holds an event type, a timestamp, the id of the commitment it belongs to, and one small descriptive value (which day, how many minutes, which milestone). Types: day kept, over-limit day, extension used, mini-commitment kept or broken, milestone reached, and "I'm struggling" clicks. No free text and no URL ever enters the journal.
- Quiet hours: the days, the times, and the scope she picked for each range. Scope is either "only sites in my commitments" or "the whole browser". The second one means that during those hours the stop screen appears on **every** site in that browser, including sites unrelated to her commitments. See the host permissions section below.
- Her active mini-commitment, accumulated minutes, and the achievements she has collected.
- A short personal note she wrote during setup, plus the setup draft (the link she pasted, the name she gave, the note). Neither is auto-deleted: a draft older than 24 hours is no longer offered for resuming, but it stays in storage until reset or uninstall.
- Small internal markers: the last day accounted for (`lastDay`), whether today's "10 minutes left" notice was already shown for each commitment separately (`warnedOnBy`), whether today's check-in reminder was already sent (`checkinRemindedOn`), and when old records were last swept (`lastPruned`).
- One record holding the currently active tab's full URL, including anything after the `?`, and the second the timer started from, so the clock knows where it stands. It is rewritten on every tab switch and once a minute, and cleared when she goes idle or unfocuses the browser. If she simply closes the laptop without going idle or switching windows, the last value stays at rest in storage until next time. It is never accumulated into a history and never leaves the device.

**What is never collected:** no account, email, password, name or age; no browsing history (sites outside her chosen list are never named, counted, shown or stored — the one exception is hers to trigger, described under "One permission that is not on the install screen" below: a one-time, in-memory read of up to the last 30 days, sometimes fewer, that also glances at when she arrived at OTHER sites, only to know when a visit to a NAMED one ended, and stores and sends nothing about any of it); nothing typed in the in-product chat is stored or transmitted (it lives only in the open popup window and disappears when it closes); no analytics; no third parties; no `chrome.storage.sync`, so nothing travels through a Google account to another device. Nothing is sold or shared: in this version (0.1.0), the extension sends nothing anywhere, so there is nothing to sell. This is not just a promise — every build is checked by a packaging gate that fails if any network call or external URL turns up in the shipped code (see `docs/packaging.md`, Gate 1).

**Permissions and why they are required:**

| Permission | Why it is needed |
|---|---|
| `storage` | Persist commitments, streaks, daily time and the journal locally. Without it everything is lost when the browser closes. |
| `alarms` | Chrome suspends the service worker after about 30 seconds. A one-minute alarm wakes it to accumulate time, settle the day, and show the stop screen within a minute of the limit being reached. |
| `idle` | Detect 60 seconds of inactivity and stop counting, so time away from the machine is not counted against her. |
| `scripting` | Chrome only injects content scripts into pages loaded after install. This lets the extension reach tabs that were already open at install or update time, so the page she was already sitting on is not a blind spot. |
| `notifications` | Local, self-generated notifications: when a mini-commitment is kept, when about ten minutes are left on a daily-quota commitment, and one daily check-in reminder at the hour she picked. None of these appear between the Friday hour and the motzash hour she sets herself, or during quiet hours she configured. If her chosen reminder hour falls inside either, the notification is delayed to the first moment they end **on that same day**, rather than sent unasked. **On Friday there is normally no such moment, so Friday's check-in reminder is not sent at all:** the earliest reminder hour that can be chosen is 17:00, and the default Friday hour already begins at 15:00. Setting a later Friday hour restores it. Created on the device, passing through no service. |

**One permission that is not on the install screen.** It is declared in the manifest as optional (`optional_permissions`), so Chrome never shows it at install and only asks for it in response to her own click on one button inside the extension.

| Permission | Why it is needed |
|---|---|
| `history` | On the first-setup question "how long are you there per day" there is a small link: "Not sure? Let's check it together." Only if she clicks it does Chrome ask whether to let the extension read her history. Note the wording of the prompt itself: Chrome always shows its own fixed sentence for this request, "Read and change your browsing history on all signed-in devices." The extension never changes any history and never reads from other devices; that is Chrome's standard sentence for any `history` request, not a description of what the extension does. If she allows it, the extension reads up to the last 30 days of visits once — on an unusually busy profile the read is capped by item count rather than by date, so the effective window can quietly be less than 30 days, without a separate notice — and estimates minutes per day on the sites she herself named, but only for a site with visits on at least five distinct days in that window, and only when the time that adds up to is enough to round to at least a minute a day; short of either, it says plainly that visits were found but not enough to estimate from, rather than showing a number it cannot stand behind. The read happens in memory only, and typically finishes in a few seconds — longer, but always bounded (at most roughly 250 sequential batches of up to 20 sites each), on an unusually active history. It also looks at when she arrived at sites she never named, not to count them, but because knowing when she left is how it knows how long a visit to a site she DID name lasted; nothing about an unnamed site — its address, how often, for how long — is ever kept, shown, or written down. No visit, URL or timestamp is ever written to storage or sent anywhere. Only the resulting number, and only if she accepts it, goes into the field, exactly as if she had turned the dial herself. Declining does nothing and leaves the extension fully usable. If the tab is closed or the browser itself closes before the permission is handed back, a brief check at the next browser start (or extension update) confirms it was not left granted by mistake. The number is presented as an estimate, not a measurement: history knows when she arrived on a site, not how long she stayed. |

**Host permissions, `https://*/*` and `http://*/*`.** This is the broad one, and here is the full account of it.

This is also what lets the extension know which tab is in front of her and what its address is: without that the timer cannot tell whether it should be running at all, and the stop screen and the reminder cannot be delivered to that tab. The extension does not hold permission to read her browsing history. It sees the page open in front of her right now, not the list of places she has been. The one moment it asks for such a permission, on her click only and for a bounded time (typically a few seconds — the full detail, including the upper bound, is above under "One permission that is not on the install screen"), is described there.

The user picks her sites after installation and can change them any day, and Chrome offers no way to declare "only the sites she will choose tomorrow", so the extension requests broad host access and narrows it in its own code.

In practice, a small content script on each page asks the extension one question: should this page be stopped right now. It asks on page load and then every 30 seconds for as long as the tab stays open, sending the page's full URL to the extension. The question and the answer stay inside the extension on her own machine, and nothing is written to storage as a result. For the overwhelming majority of pages the answer is no and nothing happens.

The stop screen appears in two cases: on sites listed in her commitments once she is past the time she set, and, if she configured quiet hours with the "whole browser" scope, on **every** site in that browser during those hours, including sites unrelated to her commitments. Without broad host access neither case can be rendered, and already-open tabs cannot be reached. The access does not exist to read her browsing.

The extension also serves `fonts/*` and `character/v3/*` to the page from its own bundle, so the stop screen renders with the right look without fetching anything from the internet. Those two only, and at an address that changes every time the browser starts, so a website cannot probe for them and infer that the extension is installed.

**Who can see the data.** From the extension itself, only the user: the developer cannot see any of it, because there is nowhere for it to arrive. Anyone with access to her computer and Chrome profile can open the extension and see what it shows, as with anything else in her browser. Separately, pilot feedback is collected through a **Google Form**, which is not part of the extension: it is hosted by Google, and answers she chooses to submit are stored on Google's servers and reach the developer. The extension neither fills it in nor knows it exists, and declining to answer changes nothing about how the extension works.

**Deletion.** A reset button at the bottom of the popup, labelled `התחלה מחדש`, wipes all local storage at once; it is only rendered once a commitment exists and after any fall has been acknowledged, so it is not on screen before first setup or on the morning-after screen. Uninstalling the extension makes Chrome delete all of its local storage, in every state. Daily time, extension-use and hours records auto-delete after 45 days, and the journal keeps only the last 500 events. Everything else, including the commitments, streaks, achievements, quiet hours, the personal note and the setup draft, persists until reset or uninstall.

**Children and teens.** Pilot testers include teenage girls. The extension asks for no age and no identifying detail, creates no account, and contains no purchases, ads or external content, and it sends nothing about her to anyone. Two things are stated plainly for them: the pilot's feedback form is hosted by Google, so whatever she chooses to write there is stored by Google and reaches the developer; and a shared computer is a precondition to handle, not only a privacy note: on a shared Chrome profile, anyone using it can open the extension and see her commitments, streaks and personal note, and, more seriously, the extension counts all browsing on that profile, not only hers, so someone else's use can reset her streak on a day she did not break it. A separate Chrome profile, hers alone, fixes both at once, which is why install-guide.md treats it as a condition before installing, not a suggestion. Users under 18 should install it with a parent's knowledge and consent. It is not a parental-control tool: there is no parent dashboard and no report is sent to anyone.

**Changes.** This page is updated and re-dated whenever the product changes in a way that touches data. If any component that sends data outside the device is ever added, it will be introduced behind an explicit consent screen, and declining will keep the extension fully usable.

**Contact:** ani.bacharti.bi@gmail.com

</div>
