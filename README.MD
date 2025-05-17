# JPEG XL vs. AVIF
## Kandidatexamensarbete i Datavetenskap
Stockholms universitet, Institutionen för Data- och Systemvetenskap  
Höstterminen 2024 

## Sammanfattning
### Introduktion
Denna studie undersöker skillnader i bildkvalitet mellan de moderna komprimeringsalgoritmerna JPEG XL och AVIF vid destruktiv komprimering. Genom att analysera hur dessa algoritmer presterar i tre scenarier – mörka scener, skarpa kanter och detaljrika bilder – syftar studien till att bidra till en bättre förståelse av deras relativa styrkor och svagheter.

### Forskningsfråga
Den primära forskningsfrågan är: Vilka skillnader finns det gällande bildkvalitet mellan komprimeringsalgoritmerna JPEG XL och AVIF vid destruktiv komprimering? Studien undersöker dessutom tre underfrågor som fokuserar på specifika scenarier.

### Metod
Studien mäter bildkvalitet hos algoritmerna med hjälp av PSNR och SSIM. För att möjliggöra jämförelser mellan algoritmerna utvärderades deras prestanda i ett antal testfall som representerar de tre nämnda scenarierna. Statistiska analyser genomfördes med Mann-Whitney U-test och deskriptiv statistik.

### Resultat
Resultaten visar att JPEG XL överträffar AVIF i bildkvalitet för mörka scener medan AVIF presterar bättre vid skarpa kanter. För detaljrika scener uppvisade båda algoritmerna jämförbara resultat men med viss fördel för AVIF. Studien indikerar att algoritmernas prestanda är kontextberoende och att val av komprimeringsteknik bör anpassas efter användningsområde.

### Diskussion
Studien belyser behovet av att balansera bildkvalitet och filstorlek beroende på användarens krav. Begränsningar inkluderar antalet testfall och den specifika hårdvara som användes. Vidare forskning bör undersöka fler scenarier och kombinera objektiva mätvärden med subjektiva användarupplevelser för att ge en mer heltäckande bild av algoritmernas prestanda.

📄 [Till uppsatsen](./Uppsats.pdf)
