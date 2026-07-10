# ARPy – alat za bržu pripremu revizorskih PDF izveštaja

![Version](https://img.shields.io/badge/version-0.9.9-blue)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Python](https://img.shields.io/badge/Python-3.12-yellow)
![Status](https://img.shields.io/badge/status-Active-success)
![License](https://img.shields.io/badge/license-Commercial-red)

**ARPy** je desktop aplikacija namenjena revizorskim društvima za automatizaciju tehničke pripreme završnih PDF izveštaja.

Aplikacija pomaže u objedinjavanju Word i PDF dokumenata, dodavanju memoranduma, potpisa i pečata, obradi priloga, kontroli kvaliteta i generisanju finalnog dokumenta spremnog za predaju APR-u, klijentima i drugim institucijama.

Dokumentacioni repozitorijum sadrži GitHub Pages prezentaciju, release notes, screenshotove, PDF vodiče i update metadata fajlove za proveru novih verzija iz aplikacije.

---

## 🚀 Glavne funkcionalnosti

- 📄 Spajanje Word i PDF dokumenata u jedan izveštaj
- 🏢 Automatsko dodavanje memoranduma prema profilu izveštaja
- ✍️ Umetanje potpisa i pečata
- 📑 Kreiranje Prilozi PDF i FINAL PDF dokumenata
- 🧙 Čarobnjak (Wizard) za vođenu pripremu kompletnog izveštaja
- 🧭 Akcioni vodič kroz sledeći preporučeni korak u Wizard-u
- 🔍 Kontrole kvaliteta i upozorenja pre kreiranja FINAL PDF-a
- 🛡 Word Quality Control (Word QC)
- ✅ PDF i FINAL PDF Quality Control
- 📂 Automatsko arhiviranje pomoćnih PDF fajlova
- 📦 Automatska provera novih verzija i jednostavan update postupak
- 🖼 Dokumentacioni screenshotovi i PDF vodič za rad kroz Wizard

---

## 🧠 Tipičan workflow

1. Unos osnovnih podataka:
   - subjekt / naslov izveštaja
   - naziv klijenta
   - godina
   - vrsta izveštaja
   - output folder

2. Dodavanje dokumenata:
   - PDF obrasci
   - napomene
   - drugi prilozi
   - PDF mišljenja nakon izvoza iz Word-a

3. Priprema sadržaja:
   - izračun tehničkog sadržaja
   - čuvanje TXT sadržaja
   - ubacivanje sadržaja u Word kroz Word alate

4. Kreiranje PDF rezultata:
   - Prilozi PDF
   - FINAL PDF
   - opciona A4 obrada i optimizacija

5. Završna kontrola:
   - Korak 5 — završni pregled
   - FINAL PDF QC
   - pregled output foldera

---

## 🧙 Wizard 0.9.9

Verzija **0.9.9** donosi završno poliranje Wizard toka i praktičniji rad za korisnike koji žele vođeni proces pripreme izveštaja.

Najvažnije novosti:

- posebne ilustracije za sve korake Wizard-a
- akcione preporuke u vodiču kroz Wizard
- završni pregled spremnosti u Koraku 5
- brze komande za otvaranje FINAL PDF-a, FINAL QC-a, output foldera i kopiranje finalne putanje
- validacija sadržaja pre izračuna TOC-a
- zaštita od pogrešnog spajanja PDF mišljenja i Priloga PDF
- kontrola očekivanog broja strana nakon kreiranja FINAL PDF-a
- bolja sinhronizacija Word alata sa podacima iz Wizard-a

---

## 🛡️ PDF zaštite i kontrole

ARPy sadrži više mehanizama za smanjenje rizika od grešaka tokom pripreme izveštaja:

- upozorenje za zastarele priloge
- upozorenje za neusklađen PDF mišljenja
- detekcija rasterizovanih/skeniranih PDF dokumenata
- analiza veličine PDF fajlova
- kontrola promene broja strana tokom A4 konverzije
- selektivna rasterizacija potpisanih PDF strana radi očuvanja kvaliteta i veličine dokumenta
- zaštita od korišćenja istog fajla kao PDF mišljenja i Prilozi PDF
- provera očekivanog broja strana nakon spajanja
- Word Quality Control
- Opinion PDF Quality Control
- Management Letter PDF Quality Control
- FINAL PDF Quality Control
- automatska provera A4 formata
- detekcija formularskih polja
- detekcija elektronskih potpisa

---

## 🆕 Najvažnije novosti u verziji 0.9.9

Verzija **ARPy 0.9.9 — Wizard polish build** fokusirana je na stabilizaciju i vizuelno-korisničko unapređenje rada kroz Čarobnjak.

### Wizard

- uveden kompletan set ilustracija po koracima
- povezana akciona dugmad vodiča sa konkretnim funkcijama aplikacije
- dodat završni pregled spremnosti u Koraku 5
- unapređene poruke korisniku tokom prelaska između koraka
- dodati screenshotovi kompletnog 0.9.9 workflow-a u dokumentaciju

### PDF i FINAL workflow

- blokirano kreiranje FINAL PDF-a ako su PDF mišljenja i Prilozi PDF isti fajl
- dodata provera očekivanog broja strana nakon spajanja
- smanjen rizik od dupliranja priloga
- jasnije poruke kada je potrebno ponovo kreirati Priloge ili FINAL PDF

### Word alati

- Word alati stabilnije preuzimaju podatke iz Wizard-a
- sprečeno neželjeno prepisivanje osnovnih Wizard podataka
- ubacivanje sadržaja u Word jasnije je povezano sa Korakom 3 Wizard-a

### Dokumentacija

- ažuriran GitHub Pages sadržaj za verziju 0.9.9
- dopunjena stranica za Čarobnjak
- dopunjena screenshot galerija
- dodat PDF vodič za ARPy Wizard 0.9.9 sa screenshotovima
- ažuriran `latest.json` za automatsku proveru nove verzije

---

## 📚 Dokumentacija na GitHub Pages

Kompletna dokumentacija dostupna je na:

https://keymaster75.github.io/arpy-documentation/

Obuhvata:

- početnu prezentaciju aplikacije
- Čarobnjak (Wizard)
- Quality Control
- Release Notes
- Screenshots galeriju
- PDF vodiče

Korisne stranice:

- `index.html` — početna strana
- `wizard.html` — dokumentacija za Čarobnjak
- `features.html` — pregled funkcionalnosti
- `qc.html` — Quality Control dokumentacija
- `screenshots.html` — galerija screenshotova
- `release-notes.html` — istorija verzija

---

## 📸 Screenshots

Screenshotovi i vizuelni primeri rada nalaze se u dokumentaciji:

https://keymaster75.github.io/arpy-documentation/screenshots.html

Za verziju 0.9.9 dodat je kompletan Wizard workflow:

- Korak 1 — osnovni podaci
- Korak 2 — obrasci
- Korak 3 — sadržaj i mišljenje
- Word alati — ubacivanje sadržaja
- PDF mišljenja izabran
- Korak 4 — Prilozi PDF
- Korak 4 — FINAL PDF
- Korak 5 — završni pregled
- FINAL PDF QC
- Output folder rezultat

---

## 📖 PDF vodič

Za ARPy Wizard 0.9.9 dodat je praktičan PDF vodič sa screenshotovima.

Predložena putanja u dokumentacionom repozitorijumu:

```text
docs/guides/arpy-wizard-0.9.9-guide-full.pdf
```

Vodič je namenjen korisnicima koji prvi put prolaze kroz Čarobnjak sa revizorima i pokriva:

- pregled procesa
- korake rada
- najčešće greške i rešenja
- kontrolnu listu pre isporuke
- screenshotove po koracima

---

## 🔄 Update metadata

Repozitorijum sadrži `latest.json`, koji ARPy koristi za proveru dostupnosti nove verzije.

Metadata uključuje:

- aktuelnu verziju
- datum izdanja
- link ka installeru
- naziv installera
- link ka release notes
- kratke release notes
- informaciju da li je nadogradnja obavezna

Za verziju 0.9.9 koristi se installer:

```text
ARPy_Setup_0.9.9.exe
```

---

## 🎯 Namena

Aplikacija je namenjena:

- revizorskim društvima
- knjigovodstvenim firmama
- internim revizijama
- organizacijama koje generišu standardizovane Word/PDF izveštaje
- korisnicima kojima je važna kontrola redosleda, kvaliteta i finalnog PDF dokumenta

---

## 📌 Napomena

Ovaj repozitorijum služi za prezentaciju aplikacije, dokumentaciju, screenshotove, PDF vodiče i distribuciju instalacionih paketa.

Izvorni kod ARPy aplikacije nije javno dostupan.

---

## 📬 Kontakt

Za više informacija ili demo verziju:

📧 [aleksica@gmail.com](mailto:aleksica@gmail.com)
