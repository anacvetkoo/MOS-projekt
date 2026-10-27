# MOS-projekt

## Ali se študij danes še splača?

**Predmet:** Modeli in odločitveni sistemi  
**Avtorici:** Ana Cvetko in Živa Šumak

## Opis projekta

V projektu raziskujeva, kako so se v zadnjih približno 20 letih spreminjali dostopnost, stroški in uspešnost študija na ameriških univerzah, s poudarkom na Ivy League.

Univerze Ivy League primerjava z drugimi javnimi in zasebnimi neprofitnimi štiriletnimi univerzami. Obravnavava tudi zaslužke v računalniških poklicih glede na izobrazbo.

## Raziskovalna vprašanja

- **RV1:** Kako so se spreminjali prijave, sprejemi in vpisi?
- **RV2:** Kako se je spreminjala stopnja zaključevanja študija?
- **RV3:** Kako so se spreminjali stroški študija ob upoštevanju inflacije?
- **RV4:** Kako sta se spreminjala število in delež diplomantov računalništva?
- **RV5:** Kako se zaslužki in zaposlitvene možnosti v IT razlikujejo glede na izobrazbo?
- **RV6:** Kdaj se finančna naložba v študij povrne v primerjavi z neposredno zaposlitvijo?

Pri **RV5** je trenutno opravljena primerjava zaslužkov zaposlenih v računalniških poklicih glede na izobrazbo. Zaposlitvene možnosti še niso analizirane. **RV6** je načrtovan za nadaljnje faze projekta.

## Podatkovni viri

- **IPEDS / NCES:** podatki o univerzah, vpisih, zaključevanju študija, šolninah in diplomantih.
- **College Scorecard:** neto cene in skupni stroški študija.
- **IPUMS ACS:** izobrazba in zaslužki v računalniških poklicih.
- **CPI-U (FRED / BLS):** prilagoditev stroškov za inflacijo.


## Struktura repozitorija

- `notebooks/` – Python koda in analize v Google Colabu
- `data/processed/` – pripravljene podatkovne zbirke
- `data/raw/` – prostor za izvorne podatke
- `figures/` – grafi in vizualizacije
- `docs/` – dokumentacija
- `src/` – dodatna Python koda

## Uporaba

Analize izvajava v Pythonu (Google Colab), predvsem s knjižnicami pandas, numpy in matplotlib. Pred izvajanjem je treba zagotoviti ustrezne podatkovne datoteke, saj jih nekateri zvezki berejo iz Google Drive, drugi pa iz okolja Colab.

Individualnih podatkov IPUMS ACS zaradi pogojev uporabe ne objavljava na GitHubu.

Projekt je še v izdelavi in ga sproti dopolnjujeva.
