# 💰 Budget – från lön till lön

En enkel budgetapp som räknar per löneperiod i stället för per kalendermånad.

## Funktioner

- **Kvar att spendera idag** – ett tydligt tal som räknas om varje dag fram till nästa lön
- **Löneperiod** – från lön till lön, lönedag på helg flyttas till fredagen innan
- **Prognos** – hur mycket du har kvar vid lön i nuvarande takt
- **Fasta utgifter & prenumerationer** – med nedräkning till nästa dragning
- **Sparmål** – för en resa eller en summa, med firande vid 25/50/75/100 %
- **Positiv förstärkning** – sviter under dagsbudget och jämförelser med förra perioden
- **Grupper** – dela kostnader med kompisar, appen räknar ut vem som ska betala vem
- **Översikt** – stapeldiagram dag för dag mot dagsbudgeten, plus fördelning per kategori
- **Redigera & ångra** – tryck på en utgift för att ändra belopp, kategori eller datum; borttagningar kan ångras
- **Sök** – hitta utgifter bland alla perioder
- **Ljust/mörkt tema** – följer telefonen eller väljs manuellt
- **Installerbar (PWA)** – fungerar offline och kan läggas på hemskärmen

All data sparas lokalt i webbläsaren. Inget skickas till någon server.

## Köra lokalt

Öppna `index.html` i webbläsaren. För att testa installation och offline-läge behövs en webbserver, t.ex.:

```bash
npx serve .
```
