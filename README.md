# 2022-es OGY választások előválasztási vitáinak automatikus szövges átiratai

Ez a projekt a 2021 őszén a [Partizán](https://www.youtube.com/c/Partiz%C3%A1nm%C3%A9dia) youtube csatornáján megrendezett előválasztási viták automatikus szöveges átiratait tartalmazza.  
Az átiratokat a Partizán csapatának beleegyezésével tesszük közzé, azok szabadon fölhasználhatók pl. adatvizualizációs, korpusznyelvészeti célokra.  
Érdemes tudni, hogy mivel az átiratok automatikusan készültek (a Google Cloud speech-to-text megoldását használva), így azok tartalmazhatnak helyesírási, szegmentálási, stb. hibákat.
Magukat az átiratokat a `transcripts` mappa tartalmazza vitánként egy-egy JSON fájl formájában, az egyes videók metaadatai pedig a [debates_meta_data.json](debates_meta_data.json) fájlban találhatók meg.

Az átiratok alapjául szolgáló egyes videók, a közzétételük időpontja szerinti sorrendben az alábbiak:
* [Nagykanizsa képviselőjelöltjeinek vitája | Zala megye 3. sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=2og3Dgxrmp4)
* [Szombathely képviselőjelöltjeinek vitája | Vas megye 1. sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=VqP5iqfxwpA)
* [Debrecen képviselőjelöltjeinek vitája | Hajdú-Bihar megye 1. sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=bupfGmtDnGE)
* [Debrecen képviselőjelöltjeinek vitája | Hajdú-Bihar megye 2. sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=P7B_M7kY9Ts)
* [Eger képviselőjelöltjeinek vitája | Heves megye 1. sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=ePpQ_-IgMOk)
* [Salgótarján képviselőjelöltjeinek vitája | Nógrád megye 1. sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=T4NiK5x3JPQ)
* [Nyíregyháza képviselőjelöltjeinek vitája | Szabolcs-Szatmár-Bereg megye 1. sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=aha8xkvQCVc)
* [Nyíregyháza és környéke képviselőjelöltjeinek vitája | Szabolcs-szatmár-Bereg megye 2. sz. OEVK](https://www.youtube.com/watch?v=2rov5StUxio)
* [Érd képviselőjelöltjeinek vitája | Pest megye 1. sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=84CNJoQsmM4)
* [Székesfehérvár képviselőjelöltjeinek vitája | Fejér megye 1. sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=K5IsfmHt2yo)
* [Hegyvidék képviselőjelöltjeinek vitája | Budapest 3.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=HNbruk1GEQY)
* [Zugló képviselőjelöltjeinek vitája | Budapest 8.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=Ky5bq1k_QmE)
* [Rákosmente képviselőjelöltjeinek vitája | Budapest 14.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=jhbgvWo084M)
* [Erzsébetváros-Terézváros képviselőjelöltjeinek vitája | Budapest 5.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=93daDvgCvrw)
* [Belváros és Várnegyed képviselőjelöltjeinek vitája | Budapest 1.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=otQfb8UTqg4)
* [Józsefváros-Ferencváros képviselőjelöltjeinek vitája | Budapest 6.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=ZFvriJBFgQY)
* [Budafok-Tétény képviselőjelöltjeinek vitája | Budapest 18.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=10Sv5moT-cA)
* [Kőbánya képviselőjelöltjeinek vitája | Budapest 9.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=wwREE6pX9fk)
* [II-III. kerület képviselőjelöltjeinek vitája | Budapest 4.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=WgP1hKMVDBs)
* [Csepel-Soroksár képviselőjelöltjeinek vitája | Budapest 17.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=u7gxlBoJKm8)
* [Újbuda képviselőjelöltjeinek vitája | Budapest 2.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=-Za5nvhNcAQ)
* [Szeged képviselőjelöltjeinek vitája | Csongrád 1.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=yFKZ5syovxM)
* [Szeged és a Homokhátság képviselőjelöltjeinek vitája | Csongrád 2.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=VJ32nXETxDs)
* [Hódmezővásárhely képviselőjelöltjeinek vitája | Csongrád 4.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=a653Z_J-TgM)
* [Orosháza képviselőjelöltjeinek vitája | Békés megye 4.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=TMTJnBS6Fj0)
* [Tatabánya képviselőjelöltjeinek vitája | Komárom-Esztergom megye 1.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=f6wdfMlJGOQ)
* [Győr képviselőjelöltjeinek vitája | Győr-Moson-Sopron megye 1.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=KtT6JQfTQfk)
* [Pécs képviselőjelöltjeinek vitája | Baranya 1.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=wWoeUJ1HkvQ)
* [Pécs képviselőjelöltjeinek vitája | Baranya 2.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=BSko35MLh3o)
* [Miskolc képviselőjelöltjeinek vitája | Borsod-Abaúj-Zemplén megye 1.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=D8RJr44G5yg)
* [Miskolc képviselőjelöltjeinek vitája | Borsod-Abaúj-Zemplén megye 2.sz. OEVK | Előválasztás](https://www.youtube.com/watch?v=Ystv2NQWuSc)
* [Karácsony visszalép Márki-Zay javára | Exkluzív páros interjú](https://www.youtube.com/watch?v=gGgLg86Iu98)
