# Zotero CSL (LVS ISO 690:2010, RTU)

LV:

Šis fails ļauj uzģenerēt bibliogrāfiju un citātus LVS ISO 690:2010 (RTU adaptēts) standartā izmantojot Zotero. Vienkārši saglabājat šo failu, un ielādējat to iekš Zotero iestatījumiem.

Lai Zotero veidotu citātus, kuros ir divi autori, kas ir atdalīti ar & simbolu (piem, (Jānis & Pēteris, 2000)), manuāli jāievieto `Type: Dataset` iekš Extra lauka. Šis ir standarta ierobežojums - CSL neatbalsta citātu stilus atkarībā no autoru skaita.

EN:

This file allows one to generate bibliography and citations in the LVS ISO 690:2010 (RTU adapted) format using Zotero. To use it just save the csl file in the repository, and load it in Zotero settings.

To make citations that have two authors that are divided by an ampersand (instead of a comma), i.e. (Jānis & Pēteris, 2000), you need to manually put `Type: Dataset` in the Extra field for your entry. Unfortunately this seems to be the only way to achieve this, as CSL doesn't support any kind of value (i.e. author count) matching conditionals.
