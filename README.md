# עבודה עם ניהול גרסאות ושיתוף עבודה
### GIT & GITHUB on Visual Studio 2017
### כפי שמותקן במחשבי המעבדות במרכז האקדמי לב
 
 מדריך זה נועד להראות פעולות בסיסיות של פתיחת מאגר מקומי ושיתופו בשרת מרוחק
 
 
 הוא לא מכיל את כל המידע הנחוץ לעבודה בניהול גרסאות
 
 
 קראו עוד על 
 [ניהול גרסאות בויקיפדיה](https://he.wikipedia.org/wiki/%D7%A0%D7%99%D7%94%D7%95%D7%9C_%D7%92%D7%A8%D7%A1%D7%90%D7%95%D7%AA#%D7%90%D7%95%D7%A6%D7%A8_%D7%9E%D7%99%D7%9C%D7%99%D7%9D_%D7%A9%D7%9B%D7%99%D7%97)
 
 
וגם על [מערכת גיט](https://he.wikipedia.org/wiki/%D7%92%D7%99%D7%98) 
 
 
 
## 0 הרשמה לגיטהאב
   
   כדי שנוכל לעבוד עם שרת גיטהאב, עלינו לפתוח חשבון באתר
  [Github](https://www.github.com)

הערה : אם משתמש בכתובת מייל אקדמית, למשל של המרכז האקדמי לב
ניתן לקבל חבילת הטבות לסטודנט, בכתובת הבאה:
[Student Pack](https://education.github.com/pack)
 
## 1 יצירת מאגר מרוחק בשרת

ניצור מאגר ריק בשרת
למאגר זה נדחוף בהמשך את הקוד שלנו

![new Repo](https://github.com/yair-go/gitExampleVS/blob/master/pic/1%20%20Create%20Remote%20Repo/new%20Repo.png)

![new Repo](https://github.com/yair-go/gitExampleVS/blob/master/pic/1%20%20Create%20Remote%20Repo/create%20repo.PNG)


בשלב הזה נעתיק ללוח את הכתובת של המאגר המרוחק

![copy address](https://github.com/yair-go/gitExampleVS/blob/master/pic/1%20%20Create%20Remote%20Repo/copy%20adress.png)

## 2 יצירת מאגר מקומי

נפתח פרוייקט חדש בסביבת העבודה
נשים לב לסמן את תיבת הבחירה 
Add to Source Control

![new project](https://github.com/yair-go/gitExampleVS/blob/master/pic/2%20Create%20Local%20Repo/1.png)

עכשיו אנחנו יכולים לעבוד על הגרסה המקומית של הפרוייקט 

## 3 פרסום המאגר המקומי

כאשר אנחנו רוצים לפרסם את המאגר המקומי לשרת

*הערה : מומלץ לעשות זאת בעת יצירת הפרוייקט*

Team Explorer לטאב של  Solution  Explorer נעבור בחלונית 

![Team Explorer](https://github.com/yair-go/gitExampleVS/blob/master/pic/3%20Sync%20and%20Publish/2.png)

נחבר לסנכרן בין המאגר המקומי למאגר המרוחק שיצרנו בשלב הראשון

![Sync](https://github.com/yair-go/gitExampleVS/blob/master/pic/3%20Sync%20and%20Publish/3.png)

נקבל מסך ששואל היכן לפרסם את המאגר

![publish1](https://github.com/yair-go/gitExampleVS/blob/master/pic/3%20Sync%20and%20Publish/publish1.PNG)

Publish נדביק את הכתובת של המאגר המרוחק בשרת ונלחץ על 

![publish2](https://github.com/yair-go/gitExampleVS/blob/master/pic/3%20Sync%20and%20Publish/publish2.PNG)


יכול להיות שנקבל מסך שמבקש את שם המשתמש והסיסמא לאתר

![login github](https://github.com/yair-go/gitExampleVS/blob/master/pic/3%20Sync%20and%20Publish/login%20github.PNG)


## 4 שמירת שינויים

במהלך העבודה, נרצה לשמור שינויים בפרוייקט גם במאגרים שמנהלים את ניהול הגרסאות
Team Explorer נחזור לחלונית  
ונבחר לבצע סנכרון

## 5 עבודה משותפת

במידה ולא בחרנו ליצור מאגר פרטי, כל אחד (אפילו ללא רישום) יכול לראות את המאגר שלנו
אבל רק הבעלים של המאגר יכול להוסיף ולשנות
אם רוצים לאפשר עבודה משותפת על אותו מאגר, נוסיף הרשאות גישה לשותפים

setting נבחר בלשונית 

![setting](https://github.com/yair-go/gitExampleVS/blob/master/pic/5%20Collaboration/setting.PNG)

collaborators בתפריט נבחר


![Collaborarors1](https://github.com/yair-go/gitExampleVS/blob/master/pic/5%20Collaboration/Collaborarors1.PNG)


Add collaborator נחפש את שם המשתמש של השותף ונלחץ


![Collaborarors2](https://github.com/yair-go/gitExampleVS/blob/master/pic/5%20Collaboration/Collaborarors2.PNG)


עכשיו השותף יכול לשכפל את המאגר לעותק מקומי אצלו ולסנכרן את השינויים עם המאגר המרוחק


## 6 שכפול מאגר


![Clone github](https://github.com/yair-go/gitExampleVS/blob/master/pic/6%20Clone/clone%20on%20github.png)


![connect](https://github.com/yair-go/gitExampleVS/blob/master/pic/6%20Clone/connection.png)


![colne VS](https://github.com/yair-go/gitExampleVS/blob/master/pic/6%20Clone/clone%20on%20VS.png)

## סיכום


[Issues](https://github.com/yair-go/gitExampleVS/issues) לתגובות ניתן להשאיר בחלק  ה


> Written with [StackEdit](https://stackedit.io/).
