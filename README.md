# Dronepros

Dronepros lager ortofoto, høydemodeller, punktskyer, 3D-modeller og Gaussian
splats av dronebilder, og eksporterer til GIS, CAD og QGIS. Her ligger
installasjonsfilene. Koden ligger i et privat repo.

Last ned fra [**siste versjon**](https://github.com/simon-ludvigsen/dronepros-releases/releases/latest).

## Windows

1. Last ned `Dronepros-Setup-<versjon>.exe` og åpne den.
2. Windows viser «Windows beskyttet PC-en din» fordi programmet ikke er signert:
   klikk **Mer info** og så **Kjør likevel**.
3. Følg veiviseren. Til slutt lastes bibliotekene ned (5–10 minutter).

Krav: 64-biters Windows 10 eller 11. Gaussian splats krever et skjermkort med
DirectX 12 eller Vulkan (NVIDIA, AMD eller Intel).

## Mac

1. Last ned `Dronepros-<versjon>.dmg`, åpne den og dra **Dronepros** til **Programmer**.
2. Åpne Dronepros. Appen er ikke godkjent (notarisert) av Apple, så første gang
   sier macOS at den ikke kan åpnes. Gå til **Systeminnstillinger → Personvern og
   sikkerhet**, bla ned og trykk **Åpne likevel**.
3. Første gang lastes bibliotekene ned (noen minutter).

Krav: Mac med Apple Silicon (M1 eller nyere) og macOS 15 (Sequoia) eller nyere.

## Oppdatere

Appen sier fra når det finnes en ny versjon. Klikk **Oppdater nå**, så lastes
den ned, kontrolleres og installeres, og appen starter igjen av seg selv.
Prosjektene dine blir ikke rørt. `.sha256`-filene er kontrollsummene appen
sjekker nedlastingen mot.
