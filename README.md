# Onlab2
Önálló Laboratórium 2 - NLP
Ez a repository az Önálló Laboratórium 2 tantárgy mellett a korábbi, Önálló Laboratórium 1 tantárgy anyagát is tartalmazza, melynek célja egy gazdasági szövegeken finomhangolt magyar nyelvű modell bemutatása. A program szenzitív adatok kezdetleges maszkolára is képes.
Ezek mellett az Önlab 2 keretein belül megvalósított pontok: 
3 NER modell, prompt engineering alapú kategorizációt, RAG implementáció és egy Hugging Face chatbot felületet is tartalmaz.

# A projekt főbb elemei:

NER modellek: 2 magyar és 1 multilingual modell, melyek a gazdasági szövegekben szereplő entitásokat (pl. személyek, szervezetek, helyszínek) azonosítják.
Prompt engineering: Kategorizációhoz használt technikák, amelyekkel a NER kiegészíthető. A program példamondatok alapján eldönti, hogy azoknak mi a témájuk.
RAG implementáció: 4 magyar vonatkozású tanulmány feldolgozása, forrásmegjelöléssel ellátott válaszok adása a dokumentumokra vonatkozó kérdésekre.
Hugging Face chatbot: A modell interaktív használatát biztosító felület.

# További információk:

A tantárgy honlapja: [https://github.com/richard-peng-xia/LMPT](https://inflab.tmit.bme.hu/24t/)
A modell dokumentációja minden esetben a notebook fájlban található közvetlenül az implementáció előtt! (Véglegesítés után itt is olvasható lesz)
A Hugging Face chatbot felülete: gradio

# Használat:

A projekt futtatásához lineáris sorrendben kell haladni. A komponensek külön is futtathatóak, nem szükséges az adott komponenst megelőzők futtatása a rendes működéshez.


# Megjegyzések:

A projekt futtatásához Python 3 vagy újabb verzió szükséges.
A modellek betöltése hosszabb időt vehet igénybe.
A szenzitív adatok maszkolása még fejlesztés alatt áll.
Bejelentkezéshez szükséges API kulcs a notebookban.
A RAG-hoz szükséges kurzus linkje a notebookban van.
