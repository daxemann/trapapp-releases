# Lovačko streljaštvo – zapisnik

Program za natjecanja i trening u lovnom streljaštvu (lovački trap, lovački parkur, karabin) prema Pravilniku HLS-a.
Za Windows 10 i 11.

## ⬇️ Preuzimanje

**[Preuzmi TrapApp-win-Setup.exe](https://github.com/daxemann/trapapp-releases/releases/latest/download/TrapApp-win-Setup.exe)** (uvijek najnovija verzija)

Sve verzije i popis promjena: [Releases](https://github.com/daxemann/trapapp-releases/releases)

---

## Instalacija

1. Preuzmite datoteku **TrapApp-win-Setup.exe** (poveznica gore).
2. Pokrenite je dvostrukim klikom.
3. **Pojavit će se plavi prozor sustava Windows** (SmartScreen):

   > **Windows je zaštitio vaše računalo** *(njem. „Der Computer wurde durch Windows geschützt“)*

   To je **normalno** i ne znači da je program opasan. Windows ovo prikazuje za svaki program koji nije potpisan skupim komercijalnim certifikatom.

4. Kliknite na poveznicu **„Više informacija“** ispod teksta *(njem. „Weitere Informationen“)*.
5. Dolje se pojavi gumb **„Svejedno pokreni“** – kliknite ga *(njem. „Trotzdem ausführen“)*.
6. Instalacija traje nekoliko sekundi, bez dodatnih pitanja i bez administratorskih prava. Program se zatim sam pokrene.

Program se nalazi u izborniku **Start** pod nazivom **„Lovacko streljastvo“**.

> ℹ️ Plavi prozor pojavljuje se **samo jednom**, kod prve instalacije. Ažuriranja ga više ne prikazuju.

### Instalacija s USB sticka

Ako datoteku **TrapApp-win-Setup.exe** kopirate na USB stick i pokrenete je s njega na drugom računalu, plavi prozor se u pravilu ne pojavljuje.

---

## Ažuriranja

- Program kod svakog pokretanja sam provjerava postoji li nova verzija (potreban je internet).
- Ako postoji, na početnoj stranici pojavi se narančasti okvir **„Dostupna je nova verzija …“** s opisom promjena.
- Kliknite **„Preuzmi i ažuriraj“** → program preuzme novu verziju i ponovno se pokrene.
- Dok je natjecanje otvoreno, ažuriranje nije moguće (prvo zatvorite natjecanje).
- Ručna provjera: početna stranica, dolje → **„Provjeri ažuriranja“**.
- Instalirana verzija vidi se na početnoj stranici dolje i u naslovu prozora (npr. *v0.1.1*).

## Podaci

Natjecanja se automatski spremaju u mapu:

```
%LOCALAPPDATA%\LovackoStreljastvo\Natjecanja
```

Podaci **ostaju sačuvani** kod ažuriranja, deinstalacije i ponovne instalacije.

## Deinstalacija

Postavke sustava Windows → **Aplikacije** → **„Lovacko streljastvo“** → **Deinstaliraj**.
