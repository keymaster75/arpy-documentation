# ARPy Wizard 0.9.9 - kratko uputstvo sa screenshotovima

Tekst je namerno bez srpskih slova sa kvacicama radi pouzdanog prikaza u PDF citacima.

## Pregled procesa
1. Osnovni podaci - klijent, godina, vrsta izvestaja i output folder.
2. Obrasci - dodavanje i provera PDF obrazaca / priloga.
3. Sadrzaj i misljenje - izracun sadrzaja, Word alati i PDF misljenja.
4. Prilozi i FINAL - kreiranje Prilozi PDF i FINAL PDF dokumenta.
5. Zavrsni pregled - provera spremnosti, FINAL QC i output folder.

## Najcesce greske i resenja
- **Sadrzaj je izracunat pre nego sto je poznata strana misljenja.** Uneti poslednju numerisanu stranu ili izabrati PDF misljenja, pa tek onda racunati sadrzaj.
- **PDF misljenja i Prilozi PDF su greskom isti fajl.** Vratiti se na Korak 3 i izabrati pravi PDF misljenja. ARPy 0.9.9 ovo blokira pre kreiranja FINAL PDF-a.
- **Obrasci su promenjeni nakon sto je Prilozi PDF vec napravljen.** Ponovo kreirati Prilozi PDF, zatim ponovo FINAL PDF.
- **Word sadrzaj nije stvarno ubacen, ali je cekirana potvrda.** Otvoriti Word alate, ubaciti sadrzaj u Word, pa tek tada potvrditi status u Wizardu.
- **FINAL QC prikazuje upozorenje.** Procitati upozorenje. Neka upozorenja su informativna, ali rotacije, prazan PDF ili los broj strana treba proveriti pre slanja.
- **Output folder sadrzi stare fajlove od ranijih pokusaja.** Koristiti namenski folder po klijentu/godini ili ocistiti Wizard i ponoviti postupak.

## Screenshotovi
### 1. Korak 1 - Osnovni podaci
Unos subjekta, klijenta, godine, vrste izvestaja i output foldera.
![Korak 1 - Osnovni podaci](../screenshots/0.9.9-wizard/01_wizard_step1_basic_data.png)

### 2. Korak 2 - PDF obrasci
Dodavanje obrazaca i provera tipa i redosleda priloga.
![Korak 2 - PDF obrasci](../screenshots/0.9.9-wizard/02_wizard_step2_forms_added.png)

### 3. Korak 3 - Sadrzaj spreman
Izracun tehnickog sadrzaja i priprema za Word alate.
![Korak 3 - Sadrzaj spreman](../screenshots/0.9.9-wizard/03_wizard_step3_toc_ready.png)

### 4. Word alati - ubacivanje sadrzaja
Ubacivanje TXT sadrzaja u Word dokument na marker [SADRZAJ].
![Word alati - ubacivanje sadrzaja](../screenshots/0.9.9-wizard/04_word_tools_insert_toc.png)

### 5. Korak 3 - PDF misljenja izabran
Povezivanje PDF misljenja sa Wizard tokom.
![Korak 3 - PDF misljenja izabran](../screenshots/0.9.9-wizard/05_wizard_step3_opinion_pdf_selected.png)

### 6. Korak 4 - Prilozi PDF kreiran
Kreiranje Prilozi PDF dokumenta nakon provere obrazaca.
![Korak 4 - Prilozi PDF kreiran](../screenshots/0.9.9-wizard/06_wizard_step4_prilozi_ready.png)

### 7. Korak 4 - FINAL PDF kreiran
Kreiranje finalnog PDF dokumenta i kontrola ocekivanog broja strana.
![Korak 4 - FINAL PDF kreiran](../screenshots/0.9.9-wizard/07_wizard_step4_final_ready.png)

### 8. Korak 5 - Pregled i zavrsna provera
Zavrsni pregled spremnosti izvestaja, broja strana i output foldera.
![Korak 5 - Pregled i zavrsna provera](../screenshots/0.9.9-wizard/08_wizard_step5_review_ready.png)

### 9. FINAL PDF QC
Zavrsna tehnicka provera finalnog dokumenta.
![FINAL PDF QC](../screenshots/0.9.9-wizard/09_final_pdf_qc.png)

### 10. Output folder - rezultat
Primer output foldera sa generisanim fajlovima.
![Output folder - rezultat](../screenshots/0.9.9-wizard/10_output_folder_result.png)
