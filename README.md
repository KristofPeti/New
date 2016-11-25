# Év végi beadandó feladat
A beadandó célja, hogy elkészíts egy többképernyős alkalmazást, melyben a félév során tanultak nagyrészét használod. A leírás hosszúnak tűnhet, de sok feladat van ami pillanatok alatt kipipálható.

Az első 4 feladat mindenkitől elvárt tudás. Az 5, 6, 7-es feladatok megoldása pedig kb 2, 3, 4-5-ös érdemjegynek felelnek meg.

Igényes megoldásokkal, szép kinézet készítésével, egyéb fel nem sorolt, de hasznos funkciók kidolgozásával plusz pontok szerezhetők, így kaphatsz jobb jegyet, annak ellenére, ha valamelyik felsorolt feladatot nem sikerült teljesen megoldani. (Ésszerűen hasonló nehézségű funkciókra gondolok, ha készítesz ilyet jelezd a README-ben!)

## Feladatok:
1. Legalább 3 (értelmes) commit
2. Készíts saját README fájlt, [Markdown][1] formátumban
3. Hozz létre egy új Android projektet
4. Az alkalmazás legyen [többnyelvű][2] (minimum 2 nyelv)
5. Készíts egy Login Activityt, az alábbiak szerint
  * Tartalmazzon 2 beviteli mezőt a felhasználónév és jelszó beírásához, és egy gombot a bejelentkezéshez
  * Ez legyen az első Activity ami megjelenik
  * A gombra kattintva mentsd el a felhasználónevet [SharedPreferences][3] segítségével
  * Ha már bejelentkezett korábban a felhasználó, akkor ugorj automatikusan a következő Activity-re
6. Készítsd el az alkalmazásod főképernyőjét az alábbiak szerint:
  * Tartalmazzon egy szöveges mezőt, ahol üdvözlöd a felhasználót (pl: "Üdv Csaba!") és egy gombot amivel ki lehet jelentkezni
  * Ha kijelentkezik a felhasználó akkor törlődjön a neve a SharedPreferences-ből, és kerüljünk a Login képernyőre
  * Ha első alkalommal jelentkezett be a felhasználó, akkor az üdvözlő szöveget egészítsd ki (pl: "Üdv Csaba! Remélem tetszeni fog az app, adj rá egy ötöst!")
  * Későbbi bejelentkezéseknél ez a plusz szöveg már ne jelenjen meg, csak az üdvözlés - Tipp: Használd a SharedPrefet a feladat megoldásához
  * Ezen kívül szabadon testreszabhatod a képernyő kinézetét, extra elemek használatával (plusz pont!)
7. Készíts egy [listát][4]:
  * Lehet a főképernyőn vagy egy külön Activityn is
  * Egy általad létrehozott osztály elemeit jelenítse meg, a saját [ArrayAdapter][5]-ed segítségével
  * Töltsd fel adattal internetről letöltött json segítségével (használhatsz bármilyen json forrást, kivéve az órán használt [url][6]-t) - Tipp: Retrofit használata nem kötelező, de erősen ajánlott
  * Ha nem szeretnél saját forrást keresni/készíteni, [itt][7] van egy tőlem
  * Ha nem sikerül internetről letölteni az adatot, töltsd fel "kézzel" a listát
  * Ha nem sikerül saját osztály elemeit megjeleníteni, jeleníts meg Stringeket az alap ArrayAdapter segítségével
8. Készíts képernyőfelvételt (video) ami bemutatja az appod működését a feladatok szerint:
  * [AZ Screen Recorder][8]
  * Töltsd fel a felvételt valahova (ha máshova nem megy akkor a repodba)


## README fájl tartalma
A saját README fájlodban írj rövid, 2-3 mondatos bemutatót az alkalmazásodhoz. Sorold fel mely feladatokat oldottad meg. Írd le mely feladatokat nem tudtad megoldani és miért. Írd bele a képernyőfelvétel urlt ha nem a repoba tetted fel. Egyéb saját ötlet alapján elkészített funkciók leírása. Írd bele milyen érdemjegyet vársz a beadandódra.

## Határidő
2016.12.15.

[1]: https://guides.github.com/features/mastering-markdown
[2]: https://developer.android.com/training/basics/supporting-devices/languages.html
[3]: https://developer.android.com/training/basics/data-storage/shared-preferences.html
[4]: https://developer.android.com/guide/topics/ui/declaring-layout.html#AdapterViews
[5]: http://www.ezzylearning.com/tutorial/customizing-android-listview-items-with-custom-arrayadapter
[6]: https://adobe.github.io/Spry/data/json/array-02.js
[7]: http://aries.ektf.hu/~szugyi/people.json
[8]: https://play.google.com/store/apps/details?id=com.hecorat.screenrecorder.free&hl=en
