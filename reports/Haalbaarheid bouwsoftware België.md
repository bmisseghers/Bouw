# Eigen bouwsoftware loont alleen als betonniche met betalende eerste klant

## 1. Samenvatting en advies

**Het is haalbaar, maar niet als "nog een alles-in-één pakket".** Een generiek pakket naast Vertuoza, Bouwflow, Robaws en Visma Bouwsoft bouwen is voor één ontwikkelaar een no-go: de generieke laag (offerte tot factuur) is verzadigd en geprijsd op ruwweg 30 tot 150 euro per gebruiker per maand ([Belg.be](https://www.belg.be/artikel/software-bouwbedrijf-terugverdientijd-en-roi-berekend~83532)). Wel haalbaar is een **betaald maatwerkproject voor de lokale betonklant, met behoud van de auteursrechten**, dat daarna stap voor stap een nicheproduct voor beton- en ruwbouwaannemers wordt. Geen van de onderzochte pakketten adverteert met betonspecifieke opvolging (m³ per stortfase, betonbonnen, bekisting, wapening); dat is een afwezigheid van bewijs uit zoekresultaten, geen bewijs van afwezigheid.

Het advies in drie delen:

| Beslissing | Advies | Voorwaarde |
|---|---|---|
| Maatwerk-MVP voor de betonklant | **Go** | Schriftelijk contract: licentie in plaats van overdracht, betaald onderhoud, continuïteitsclausule |
| Uitbouw tot product (SaaS) | **Voorwaardelijke go** | 3 tot 5 extra betalende aannemers op dezelfde codebase binnen ongeveer 12 maanden na de eerste livegang (eigen drempel) |
| Generiek alles-in-één pakket zonder betalende eerste klant | **No-go** | Gefinancierde spelers, verzadigde prijslaag, wetgevingsonderhoud |

De snelste zinvolle MVP is **niet facturatie maar de stroom van werf naar kantoor**: werfbonnen, uren, betonleveringen en materieel per werf, met nacalculatie per project. Dat draait naast het bestaande facturatiepakket van de klant. De klant heeft dat pakket bijna zeker al, want gestructureerde e-facturatie via Peppol is sinds 1 januari 2026 verplicht ([Unizo](https://www.unizo.be/ondernemersgids/financieel/factuur/e-facturatie-correct-werken-met-peppol-en-je-digitale)). Eigen schatting van de inspanning: 40 tot 65 werkdagen, dus 8 tot 12 weken.

Voor security geldt: **CyberFundamentals (CyFun) Basic vanaf dag één, ISO 27001 pas wanneer een klant het contractueel eist.** ISO 27001 is haalbaar voor een bedrijf van één tot twee personen, maar kost naar eigen schatting 15.000 tot 40.000 euro in jaar één, plus 20 tot 40 eigen werkdagen. Dat is in de MVP-fase niet te verantwoorden.

Financieel is het product pas na jaren zelfdragend. Eigen schatting: 24 tot 50 betalende bedrijven zijn nodig om een freelance-inkomen van 120.000 euro te vervangen, en dat duurt vermoedelijk 2,5 tot 4 jaar. Het maatwerkproject en het onderhoudscontract moeten die periode overbruggen.

### Bewijskwaliteit: lees dit eerst

Alle onderzoekers konden in deze omgeving alleen met **fragmenten uit zoekresultaten** werken. Primaire sites (Statbel, Embuild, socialsecurity.be, VLAIO, de sites van de concurrenten) waren niet bereikbaar. Elk cijfer in dit rapport is dus **indicatief**. Cijfers die een beslissing dragen, moeten in de bron zelf worden nagekeken. Tegenstrijdige cijfers staan als conflict vermeld en zijn niet weggewerkt. Eigen schattingen zijn overal als schatting gelabeld. De lijst met open vragen voor de klant, een jurist en een boekhouder staat in sectie 9.

## 2. Markt en doelgroep

**De markt is groot op papier, maar de reële doelgroep is klein en staat onder druk.** De bruikbare doelgroep is niet "alle bouwbedrijven" maar de werkgevers met meerdere ploegen, en binnen die groep de beton- en ruwbouwaannemers.

### Aantal bedrijven: de cijfers spreken elkaar tegen

| Cijfer | Waarde | Jaar | Bron | Opmerking |
|---|---|---|---|---|
| Btw-plichtige ondernemingen bouwnijverheid (NACE F) | 164.427 | eind 2025 | [Statbel be.STAT](https://bestat.statbel.fgov.be/bestat/api/views/d198b9d1-2d0b-4186-8f16-35638f73df4b/result/PDF) | Uit zoekfragment |
| Ondernemingen bouwnijverheid | 160.910 | eind 2023 | [Statbel be.STAT](https://bestat.statbel.fgov.be/bestat/api/views/9d19ebe2-f35a-4b51-ac1a-c153e6d77d67/result/PDF) | Derde grootste sector |
| Btw-geregistreerde bouwbedrijven | 134.355 | 2022 | [Embuild Kerncijfers 2023](https://cms.embuild.be/election/media/_Users/Kerncijfers%20van%20de%20Belgische%20bouw%20-%202023.pdf) | **Conflict** met Statbel |
| Werkgevers in de bouw (RSZ) | 29.559 | 2022 | [Embuild Kerncijfers 2023](https://cms.embuild.be/election/media/_Users/Kerncijfers%20van%20de%20Belgische%20bouw%20-%202023.pdf) | De relevante populatie |

Het verschil tussen 164.427 en 134.355 is **niet verklaard**. Mogelijke oorzaken zijn een andere definitie of afbakening en het verschil in jaar. Dat moet in de bronnen zelf worden nagekeken. Voor de conclusie maakt het weinig uit: in beide gevallen heeft de overgrote meerderheid geen personeel. Eigen berekening: ongeveer 80 procent of meer van de btw-plichtigen is geen werkgever (let op: twee bronnen, twee jaren).

De uitsplitsing per gewest en per grootteklasse is niet gevonden. Het aantal Vlaamse bouwbedrijven met 5 tot 50 werknemers, de echte doelgroep, is dus **onbekend**. Dat cijfer is te halen uit be.STAT of RSZ-tabellen.

### Het betonsegment is niet te tellen

Er is geen officiële telling van betonaannemers gevonden. Bedrijvengidsen lijsten elk 150 tot 170 bedrijven op: 167 bij [Europages](https://www.europages.nl/ondernemingen/belgi%C3%AB/betonwerken.html) en 156 bij [RevenueBase](https://revenuebase.ai/companies/concrete-contractors/belgium). Dat is een ondergrens zonder statistische waarde. Ruwbouwers en algemene aannemers met eigen betonploegen zitten er niet in en zijn niet uit NACE-codes te isoleren. **De omvang van de niche is de grootste open vraag van dit onderzoek.** Een steekproef van 30 tot 50 betonaannemers via jaarrekeningen is de aangewezen volgende stap.

### Digitalisering: veel ruimte, maar oude en gekleurde cijfers

| Bevinding | Waarde | Bron | Kwaliteit |
|---|---|---|---|
| Aannemers met ERP | circa 20% | [Orange Belgium, 2019](https://corporate.orange.be/nl/node/9631) | Raming, zeven jaar oud |
| Bouw-kmo's met alleen Excel-achtige tools op de werf | 42% | [Exact KMO Barometer 2025](https://files.exact.com/static/web/pdf/mkb-barometer/2025/BENL-CST-mkb-barometer-sectorrapport.pdf) | Leverancier, België en Nederland |
| Bouw-kmo's met alleen papier op de werf | een kwart | [Exact KMO Barometer 2025](https://files.exact.com/static/web/pdf/mkb-barometer/2025/BENL-CST-mkb-barometer-sectorrapport.pdf) | Leverancier |
| Aannemers die te weinig info hebben over digitale oplossingen | 59% | [Orange Belgium, 2019](https://corporate.orange.be/nl/node/9631) | Oud |
| Aannemers die kosten als rem noemen | 16% | [Orange Belgium, 2019](https://corporate.orange.be/nl/node/9631) | Oud |

Ongeveer twee derde van de bouw-kmo's gebruikt dus geen echte werfsoftware (eigen optelling). De rem was in 2019 kennis en interne competentie, niet prijs. Dat pleit voor eenvoud en begeleiding boven een lage prijs. Bijna alle cijfers komen van partijen met belang bij een "achterstand". Buildwise bevestigt kwalitatief een zeer ongelijke digitale maturiteit ([Buildwise rapport nr. 40](https://ecobuild.brussels/wp-content/uploads/2023/04/31400-nl-unprotected-trend-en-impactanalyse-van-de-bouwsector-1.pdf)).

### Conjunctuur: zwak, en dat werkt in twee richtingen

De bouw is al jaren de sector met de meeste faillissementen. Statbel telde 1.192 bouwfaillissementen in de eerste vijf maanden van 2025, 9 procent boven het vorige record ([Statbel](https://statbel.fgov.be/sites/default/files/files/documents/Ondernemingen/7.5%20Faillissementen/report_BRI_2025_05_NL.pdf)). Na drie kwartalen van 2026 blijft de bouw de zwaarst getroffen sector ([Made in West-Vlaanderen](https://www.made-in.be/west-vlaanderen/eerste-negen-maanden-waren-in-west-vlaanderen-rampzalig-voor-falingen-dixit-graydoncreditsafe/)). Vooral kleinere bedrijven komen in de problemen ([GraydonCreditsafe](https://www.creditsafe.com/content/dam/be/press-releases/files/Studie-faillissementen-20251001.pdf)). Embuild meldde 5,5 procent minder nieuwbouw in 2025 en het laagste aantal vergunningen in bijna dertig jaar ([Brussels Times](https://www.brusselstimes.com/belgium/1863380/belgiums-construction-sector-continues-to-decline/)). In juni 2026 stonden winstmarges zwaar onder druk ([VRT NWS](https://www.vrt.be/vrtnws/nl/2026/06/18/vlaams-brabant-bouwsector-onder-druk-winstmarges-failissementen/)). Vlaanderen telt circa 17.000 openstaande bouwvacatures ([Made in Antwerpen](https://www.made-in.be/antwerpen/bouwfederaties-trekken-aan-alarmbel-over-dalend-aantal-leerlingen-in-bouwrichtingen/)).

De gevolgen zijn dubbel. Er is minder investeringsbudget en meer klantverloop. Maar margedruk en personeelstekort maken nacalculatie en ploegplanning ook dringender. De les voor de doelgroep: mik op gevestigde bedrijven met personeel, niet op starters.

### Peppol: het instapmoment is voorbij

In maart 2026 stonden 995.819 ondernemingen op het Peppol-netwerk ([Banqup](https://www.banqup.com/nl-be/resources/blog/belgium-s-2026-e-invoicing-mandate-what-have-we-learned-so-far-)). In augustus 2026 waren negen op tien bedrijven aangesloten ([VRT NWS](https://www.vrt.be/vrtnws/en/2026/08/03/9-out-of-10-businesses-connect-to-peppol-invoice-network.consumer/)). Bijna elke aannemer heeft dus net een facturatietool gekozen. "Facturatie" is geen ingang meer voor een nieuwkomer. Het voordeel is dat leveranciersfacturen nu gestructureerd binnenkomen. Automatisch koppelen aan werf, bestelling en nacalculatie wordt daardoor veel goedkoper om te bouwen.

### Marktomvang in euro

De enige gevonden raming komt van Data Bridge: circa 132 miljoen dollar voor "construction management software" in België, groeiend naar circa 214 miljoen dollar in 2032 ([Data Bridge Market Research](https://www.databridgemarketresearch.com/nucleus/belgium-construction-management-software-market)). Het basisjaar is onduidelijk en de methode is niet te controleren. Behandel dit als zwakke bovengrens. Eigen rekenvoorbeeld zonder bron: 29.559 werkgevers maal 3.000 tot 5.000 euro per jaar geeft 90 tot 150 miljoen euro. Een Benelux-raming en cijfers over softwarebesteding per werknemer zijn niet gevonden.

### Doelgroep (eigen afbakening)

Aannemers met 5 tot 50 werknemers in ruwbouw, betonwerken, funderingen en industriebouw in Vlaanderen. Bedrijven zonder personeel betalen geen 300 euro per maand. Bedrijven boven 50 werknemers kopen een groot pakket met een implementatiepartner.

## 3. Concurrentie

**De vier gevestigde pakketten zijn vakoverschrijdend en concurreren op breedte; geen ervan toont betonspecifieke diepte.** Een nieuwkomer wint niet op breedte of prijs, wel op niche, flexibele contractvoorwaarden en persoonlijke begeleiding.

### De vier hoofdspelers

| | Vertuoza | Robaws | Bouwflow | Visma Bouwsoft |
|---|---|---|---|---|
| Profiel | Waalse scale-up met durfkapitaal | Zelf gefinancierde West-Vlaamse cloud-ERP | Zeer jong team uit Oudenaarde | Gevestigde Vlaamse speler, sinds 2021 van Visma |
| Omvang | 10 mln euro opgehaald; 88 tot 121 medewerkers naargelang bron | "Meer dan 50" medewerkers volgens pers; 26 tot 32 volgens databanken | 1 VTE in jaarrekening; 2 tot 10 op LinkedIn | 10 tot 50 medewerkers; moeder Visma 3,1 mld euro omzet |
| Klanten (eigen claim) | 13.000+ bouwbedrijven | 20.000+ gebruikers; 700+ klanten (ongedateerd) | 1.000+ bouwprofessionals | 10.000+ bouwprofessionals |
| Doelgroep | 5 tot 50 medewerkers | Kmo's bouw en installatie | 5 tot 100 medewerkers | Bouw, installatie, tuin, architecten |
| Publieke prijs | Geen | Volledig publiek | Alleen instapprijs | Basisprijs publiek |
| Sterk | Meetstaat-import, snelle start | Vorderingsstaten, nacalculatie, 200+ integraties, API | Breed aanbod, lage instap | Werfadministratie, nacalculatie, regiewerken |
| Zwak | Lock-in, trage support, dunne mobiele app | Diepte zit in duurste pakket | Klein team, onbewezen | Verouderde interface, hybride architectuur (vooral volgens concurrenten) |
| Securityclaim | Niets gevonden | ISO 27001 op SLA-pagina (vermoedelijk datacenter) | Niets gevonden | Entiteit vermeld op ISO 27001-certificaat van Visma |

Bronnen per speler: Vertuoza ([Fortino Capital](https://www.fortinocapital.com/news/vertuoza-reinforces-its-growth-ambitions-and-successfully-concludes-its-10-million-eu-series), [Tracxn](https://tracxn.com/d/companies/vertuoza/__NWgymfDTszXMof0aMBZ-DcdpenB7Er4iVmu-BwSAUrg), [Latka](https://getlatka.com/companies/vertuoza#team), [Vertuoza](https://www.vertuoza.com/nl-be)); Robaws ([Made in West-Vlaanderen](https://www.made-in.be/west-vlaanderen/zwevegemse-robaws-groeit-50-procent-per-jaar-zonder-investeerders/), [PitchBook](https://pitchbook.com/profiles/company/529670-35), [Growjo](https://growjo.com/company/Robaws), [Embedded Finance Index](https://www.embeddedfinanceindex.com/companies/robaws), [vsk.nl](https://vsk.nl/en/?p=11756), [Robaws SLA](https://robaws.com/en/service-level-agreement)); Bouwflow ([Companyweb](https://www.companyweb.be/en/0805950036/nwn-software), [LinkedIn](https://www.linkedin.com/in/wannesmatthys/), [G2](https://www.g2.com/products/bouwflow/reviews)); Visma Bouwsoft ([Visma.be](https://www.visma.be/onze-bedrijven/visma-bouwsoft), [Dutch IT Channel](https://dutchitchannel.nl/677424/visma-koopt-belgische-useitgroup-bouwsoft.html), [Accountancy Vanmorgen](https://www.accountancyvanmorgen.nl/2026/03/19/omzet-visma-boven-3-miljard-klantenbestand-explodeert/), [Nemko-certificaat](https://www.tripletex.no/wp-content/uploads/2025/03/Visma-iso-27001-2025.pdf)).

Alle klantenaantallen zijn eigen claims van de leveranciers. Het is niet duidelijk of het om bedrijven of gebruikers gaat. Jaarrekeningen bij de Nationale Bank zijn niet geraadpleegd.

### Prijzen: de bronnen spreken elkaar tegen

| Pakket | Prijsvariant | Bron | Status |
|---|---|---|---|
| Robaws | Starter 29, Go 59, Pro 119 euro per maand, 1 gebruiker inbegrepen; extra gebruikers 24, 49, 89 euro | [Robaws pricing](https://robaws.com/en/pricing) | Leverancier, jaarfacturatie |
| Robaws | 39, 69, 139 euro bij maandfacturatie | [Bedrijfssoftwaregids](https://bedrijfssoftwaregids.nl/blog/projectmanagement-software-bouwbedrijven-2026/) | Derde partij, 2 oktober 2026 |
| Robaws | Go 99, Pro 199 euro | [OMR](https://omr.com/en/reviews/product/robaws/pricing) | Vermoedelijk verouderd |
| Robaws | 59, 119, 239 euro | [Tekpon](https://tekpon.com/software/robaws/reviews/) | Vermoedelijk verouderd |
| Robaws | Pro 199 euro per maand bij jaarfacturatie, 2 gebruikers inbegrepen | [SaaSworthy](https://www.saasworthy.com/product/robaws) | **Conflict** met leverancierspagina |
| Visma Bouwsoft | 69 euro per maand plus 865 euro opstartkost | [Bouwsoft prijspagina](https://www.bouwsoft.be/nl/prijs-visma-bouwsoft/prijs-voor-bouwprofessionals) | Leverancier, basislicentie |
| Visma Bouwsoft | 79 euro per maand, plus 35 euro per extra gebruiker | [Taklo](https://taklo.nl/beste/software-voor-belgische-installatiebedrijven) | Derde partij, 18 september 2026 |
| Visma Bouwsoft | 80 tot 150 euro per gebruiker, of 100 tot 200 euro per maand | [UNIVO](https://univo.be/blog/beste-erp-software-bouw), [Enfin](https://enfin.be/nl/blog/beste-facturatie-software-belgie) | Schattingen van concurrenten |
| Vertuoza | Geen publieke prijs, demo verplicht | [Taklo](https://taklo.nl/beste/software-voor-belgische-installatiebedrijven) | |
| Vertuoza | 1.490 euro per jaar per functie | [Capterra](https://www.capterra.com/p/232769/Vertuoza/) | **Conflict** |
| Vertuoza | Vanaf 1.320 euro per maand | [comparatif-logiciels](https://www.comparatif-logiciels.fr/logiciel/avis-vertuoza/) | **Conflict** |
| Vertuoza | 100 tot 150 euro per gebruiker per maand | [Prezapp](https://prezapp.be/blog/vertuoza-prix-avis-alternative/) | Schatting van een concurrent |
| Bouwflow | Vanaf 37 euro per gebruiker per maand, plus opstartkost op maat | [UNIVO](https://univo.be/blog/beste-erp-software-bouw) | Alleen instapprijs publiek |

Wat betaalt een betonaannemer realistisch? Bij Robaws zitten vorderingsstaten en nacalculatie in het Pro-pakket ([Softwareshaker](https://softwareshaker.com/bouwbedrijven/)). Eigen rekensom op basis van de leverancierspagina: vijf kantoorgebruikers kosten 119 plus vier maal 89, dus 475 euro per maand, zonder licenties voor de werf-app. Bij Bouwsoft zijn nacalculatie, vorderingsstaten, stock en tijdsregistratie optionele modules ([Bouwsoft prijspagina](https://www.bouwsoft.be/nl/prijs-visma-bouwsoft/prijs-voor-bouwprofessionals)); de reële prijs ligt dus boven de basisprijs. **Het prijsanker voor de doelgroep ligt rond 300 tot 500 euro per bedrijf per maand** (eigen conclusie).

### Zwakke plekken die een nieuwkomer kan benutten

| Speler | Zwakte | Bewijs | Kans |
|---|---|---|---|
| Vertuoza | Jaarcontract vooraf betaald, geen proefperiode, klachten over lock-in; score 3,6 op 5 uit 22 reviews | [Capterra reviews](https://www.capterra.com/p/232769/Vertuoza/reviews/), [Le Conduc](https://leconduc.fr/logiciel-batiment/logiciel-gestion-chantier/avis-vertuoza/) | Maandelijks opzegbaar, transparante prijs |
| Visma Bouwsoft | Verouderde interface, modulaire meerkost | [UNIVO](https://univo.be/blog/beste-erp-software-bouw), [Robaws](https://robaws.com/nl-BE/vergelijking-robaws-vs-bouwsoft-visma) (beide concurrenten) | Moderne mobiele werf-app |
| Robaws | Vakoverschrijdend; beperkt voor complexe processen | [SpotSaaS](https://www.spotsaas.com/product/robaws) | Betonspecifieke diepte |
| Bouwflow | Eén VTE, opgericht september 2023 | [Companyweb](https://www.companyweb.be/en/0805950036/nwn-software) | Zelfde zwakte geldt voor de nieuwkomer |

Bouwflow is zowel het bewijs dat een klein team kan toetreden als de meest vergelijkbare rivaal. Hun aanpak is goedkoop te kopiëren: partnerschap met Embuild Plus, vergelijkingsartikels voor zoekmachines, gratis intakegesprek ([Embuild Plus](https://embuildplus.be/nl/nieuws/bouwflow-digitale-eenvoud-voor-complexe-bouwprojecten)).

### Overige spelers en trends

De laag eronder is druk. UNIVO vraagt 35 tot 65 euro per gebruiker per maand ([UNIVO](https://univo.be/blog/beste-erp-software-bouw)). Enfin, Trustup Pro, Buildbase, Cafca, Plenion, HandSoft en Taklo mikken op dezelfde kmo's. C-PRO van Buildwise is gratis voor leden ([Worktalia](https://www.worktalia.com/article.asp?article=317)). Maatwerkbouwers zoals [Codelines](https://www.codelines.be/oplossingen/bouwsoftware-op-maat/) en [Prezapp](https://prezapp.be/blog/vertuoza-prix-avis-alternative/) bestaan ook. Bijna alle vergelijkingsartikels zijn door leveranciers geschreven.

Twee trends vallen op. De markt consolideert: Visma kocht Bouwsoft in 2021, Exact kocht Bouw7 in 2019, Pro4all kocht STA Software in 2025 ([Emerce](https://www.emerce.nl/wire/pro4all-neemt-sta-software-bouwt-verder-positie-toonaangevende-europese-leverancier-bouwsoftware)). Dat versterkt de distributie van gevestigde spelers, maar toont ook een exitroute voor nicheproducten. En Robaws kan sinds 10 november 2026 via MCP aan ChatGPT of Claude worden gekoppeld ([Robaws product updates](https://support.robaws.com/nl/article/product-updates-2026-mch86v/)). Met zijn open API is Robaws dus ook een mogelijk platform om **op** te bouwen in plaats van tegen te concurreren.

### De betonlacune

Een gerichte zoektocht naar beton- of ruwbouw-ERP in België leverde alleen generieke pakketten op ([Robaws](https://robaws.com/nl-BE/bouwsoftware), [Bouwsoft](https://www.bouwsoft.be/nl/voor-wie/voor-bouwprofessionals), [Buildbase](https://www.buildbase.be/erp-bouw)). Nacalculatie bij Bouwsoft draait rond uren en materialen van de werf ([Digital Construction World](https://www.digitalconstructionworld.be/visma-bouwsoft-duidelijk-zicht-op-winstgevendheid-door-nacalculatie/)). Geen leverancier is rechtstreeks bevraagd en geen demo is bekeken. Robaws kan beton vermoedelijk benaderen met vrije velden en artikels, maar niet standaard. De lacune kan ook betekenen dat het segment te klein is om te bedienen. Vóór de productbeslissing moet dat getest worden met demo's bij Robaws en Bouwflow.

## 4. Belgische wetgeving en verplichte functionaliteit

**De wetgeving is de echte toetredingsdrempel, niet de techniek.** Een Belgisch bouwpakket moet minstens Peppol, vier btw-regimes, de inhoudingsplicht en werfmeldingen correct afhandelen. De aanbeveling is om gereguleerde onderdelen in te kopen en de MVP buiten de facturatie te houden. Alle onderstaande punten steunen op secundaire bronnen. De wetteksten zelf zijn niet gelezen.

### Verplichtingen en wat de software moet doen

| Verplichting | Stand eind 2026 | Wat de software moet doen | In MVP? |
|---|---|---|---|
| E-facturatie B2B via Peppol | Verplicht sinds 1 januari 2026; gedoogperiode voorbij sinds 31 maart 2026; boetes 1.500, 3.000 en 5.000 euro ([Practicali](https://www.practicali.be/blog/e-facturering-tolerantieperiode-eerste-drie-maanden-2026), [lookuptax](https://lookuptax.com/docs/einvoicing/peppol-einvoicing-belgium)) | Peppol BIS/UBL-facturen en creditnota's versturen en ontvangen via een provider-API; XML en status bewaren; pdf voor particulieren | Nee voor versturen. Ontvangen is nuttig voor nacalculatie |
| E-reporting | Gepland 1 januari 2028; voorontwerp van wet goedgekeurd 18 juli 2026 ([Banqup](https://www.banqup.com/nl-be/resources/compliance-pulse/belgie)) | Provider kiezen die dit zal ondersteunen | Nee |
| Btw verlegd (medecontractant) | Art. 20 KB nr. 1; verplichte vermelding ([Accountable](https://www.accountable.eu/nl-be/help-center/het-btw-medecontractantstelsel-in-belgie-wanneer-en-hoe-verlegging-van-heffing-van-toepassing-is-op-bouwwerken/)) | Btw-regime per project, juiste wettekst en UBL-code | Fase 2 |
| 6% renovatie | Woning minstens 10 jaar oud; verklaring op de factuur vervangt het attest sinds 1 juli 2022 ([KPMG](https://kpmg.com/be/nl/home/insights/2022/02/kmo-renovatie-en-herstellingswerken-afschaffing-btw-attest.html)) | Verklaringstekst automatisch invoegen; btw per lijn | Fase 2 |
| 6% sloop en heropbouw | Permanente regeling sinds 1 juli 2025; voorafgaande verklaring via MyMinfin met formulieren 111 ([Forum for the Future](https://blog.forumforthefuture.be/nl/article/nieuwe-formulieren-111-voor-definitieve-regeling-afbraak-wederopbouw-beschikbaar/29146)) | Kopie van formulier 111 bij het project; blokkeren zonder kopie | Later, weinig relevant voor onderaannemer |
| Inhoudingsplicht (art. 30bis) | 35% RSZ, 15% fiscus, nieuw 15% RSVZ, plafond 50% ([socialsecurity.be](https://www.socialsecurity.be/site_nl/employer/applics/30bis/general/invoice.htm)) | Controle per leverancier bij betaling; resultaat en tijdstip bewaren; betaling splitsen | Fase 2 of 3; eerst als link met logboek |
| Aangifte van werken | Vanaf 30.000 euro zonder btw; vanaf 5.000 euro met onderaannemer ([Securex](https://www.securex.be/nl/lex4you/werkgever/themas/verplichtingen-werkgever/verplichtingen-in-bepaalde-sectoren/welke-werken-moeten-aangegeven-worden)) | Werfmeldingsnummer en contractwaarde per project; waarschuwingen | Ja, als veld en waarschuwing |
| Aanwezigheidsregistratie | Werven vanaf 500.000 euro ([FOD WASO](https://werk.belgie.be/nl/news/aanwezigheidsregistratie-op-bouwplaatsen-verlaagd-drempelbedrag-vanaf-1-maart-2016)); vanaf **1 april 2027** Check In and Out at Work met aankomst én vertrek, niet meer vooraf op afstand ([Partena](https://www.partena-professional.be/nl/onze-inzichten/infoflashes/check-and-out-work-voor-werken-onroerende-staat-uitgesteld-naar-1-april)) | In- en uitklokken op de werf; later koppeling met de RSZ-webservice | Klokken ja; koppeling als aparte connector |
| Algemene tijdsregistratie | Aangekondigd voor 1 januari 2027, nog geen definitieve wet in oktober 2026 ([Securex](https://www.securex.be/nl/lex4you/werkgever/nieuws/tijdsregistratie-vanaf-2027-waar-staan-we-vandaag)) | Werkelijk gepresteerde uren registreren | Ja |
| Vorderingsstaten overheidsopdrachten | 30 dagen verificatie plus 30 dagen betaling ([Belfius](https://www.belfius.be/common/NL/multimedia/MMDownloadableFile/Newsletters/BelfiusContact/MMDF%20Contact%208%20Markets.pdf)); prijsherziening met formules en indexen ([MOW-catalogus](https://dienstverlening-mow.vlaanderen.be/system/files/2025-07/20251707_DV_catalogus_prijsherzieningsformules%20%282.0%29.pdf)) | Cumulatieve logica, meer- en minwerken, instelbare herzieningsformule, termijnbewaking | Fase 2 |
| Betalingstermijn B2B | Maximaal 60 dagen, verificatie inbegrepen; 40 euro forfait ([Credendo](https://credendo.com/nl/knowledge-hub/aangepaste-betalingstermijnen-vanaf-1-februari-2022)) | Vervaldagen en intresten berekenen | Later |
| Wet Breyne | Voorschot maximaal 5%; schijven niet hoger dan uitgevoerde werken ([Bouwunie via Bouwinfo](https://www.bouwinfo.be/news/bouwen-en-verbouwen/wetgeving-en-premies/partner/b2b/bouwunie/de-wet-breyne-wat-moet-je-weten-als-aannemer)) | Optionele projectmodus | Nee |
| Weerverlet en PC 124 | Melding aan de RVA; elektronische controlekaart ([Securex](https://www.securex.be/nl/lex4you/werkgever/nieuws/tijdelijke-werkloosheid-omwille-van-slecht-weer-vergeet-de-aangifte-niet)) | Afwezigheidscodes en kilometers registreren; export naar sociaal secretariaat; geen loonberekening | Codes ja, export later |
| Geolocatie werknemers | Geen permanente tracking; duidelijk beleid nodig ([Claeys & Engels](https://legalnews.be/arbeid-sociale-zekerheid/geolocalisatiesysteem-in-voertuigen-van-werknemers-gba-brengt-voorwaarden-in-herinnering-voor-legitiem-gebruik-claeys-engels/)) | Locatie alleen op het moment van in- en uitklokken | Ja, bij ontwerp |

### Conflicten in de bronnen

| Onderwerp | Variant A | Variant B | Variant C |
|---|---|---|---|
| Startdatum RSVZ-inhouding | 1 januari 2026 ([Securex](https://www.securex.be/nl/lex4you/zelfstandige/rechten-plichten/hoofdberoep/plichten/inschrijving-in-de-kbo/de-inhoudingsplicht-in-de-bouw-en-schoonmaaksector-vanaf-1-01-2026)) | 1 mei 2026 ([Baker Tilly](https://bakertilly.be/nl/news/nieuwe-inhoudingsplicht-vanaf-1-mei-2026/)) | Eerste effectieve inhoudingen vanaf 30 oktober 2026 ([Jubel](https://www.jubel.be/nieuwe-inhoudingsplicht-voor-zelfstandigen-in-de-bouw)) |
| Drempel RSVZ-schuld | 2.647 euro (Jubel) | 2.591,36 euro ([Unizo](https://www.unizo.be/ondernemersgids/bedrijfsvoering/samenwerken-met-zelfstandigen/werken-met-dienstverleners)) | 2.500 euro ([Forum for the Future](https://blog.forumforthefuture.be/nl/article/nieuwe-inhoudingsplicht-vanaf-1-mei-2026/31059)) |
| Bereik webservice BillRetainment | Bundelt RSZ, RSVZ en fiscus sinds mei 2026 (Forum for the Future) | Dekt alleen RSZ-schulden (Securex) | Wordt uitgebreid ([Partena](https://www.partena-professional.be/nl/onze-inzichten/infoflashes/inhoudingsplicht-de-bouw-en-schoonmaaksector)) |

Een plausibele lezing van de startdatum is: wet op 1 januari 2026, operationeel op 1 mei 2026, eerste schulden zichtbaar eind oktober 2026. Dat is een **eigen interpretatie en niet bevestigd**. De drempelbedragen zijn vermoedelijk hetzelfde geïndexeerde basisbedrag in verschillende jaren. Een boekhouder of sociaal secretariaat moet dit bevestigen voordat het in software komt.

### Drie punten die specifiek zijn voor beton

De levering van stortklaar beton wordt volgens de titel van een Schoups-artikel beschouwd als werk in onroerende staat ([Schoups](https://legalnews.be/arbeid-sociale-zekerheid/leveren-van-stortklaar-beton-wordt-een-werk-in-onroerende-staat-schoups/)). Betalingen aan de betoncentrale vallen dan onder de inhoudingsplicht. Dat is alleen op titelniveau bevestigd.

De leveringsbon van de centrale is het scharnierdocument. Hij draagt het BENOR-logo, de categorie en de gegarandeerde verwerkbaarheidsduur ([Holcim](https://www.holcim.be/sites/belgium/files/documents/fiche_technique_benor_beton_nl_lr.pdf)). De klant moet de bon bij levering controleren en afwijkingen meteen melden ([Heidelberg Materials](https://www.heidelbergmaterials-benelux.com/sites/default/files/2023-12/Algemene%20verkoopvoorwaarden_beton_belgi%C3%AB.pdf)). Beton wordt gespecificeerd volgens NBN EN 206 en NBN B 15-001 ([Buildwise](https://www.buildwise.be/media/yjwl0ywi/folder_specificatie_van_beton_volgens_de_normen_nbn_en_206_en_nbn_b_15_001.pdf)).

Er bestaat geen Belgische uitwisselingsstandaard voor meetstaten. Excel en pdf domineren. Publieke opdrachtgevers gebruiken eigen systemen, zoals Standaardbestek 250 ([AWV](https://wegenenverkeer.be/sites/default/files/uploads/documenten/Catalogus-4.1a.pdf)) en het VMSW-bestek ([handleiding](https://assets.vlaanderen.be/image/upload/v1678302305/Handleiding_BouwtechnischBestekWoningbouw_ve8she.pdf)). Een robuuste Excel-import met kolomtoewijzing is dus de kernvereiste. De vorderingsstaat moet terug kunnen in de opmaak van de opdrachtgever.

## 5. MVP voor een klant in de betonbouw

**Bouw eerst de stroom van werf naar kantoor en laat facturatie bij het bestaande pakket.** Die keuze levert binnen weken nacalculatie op, vermijdt een riskante overstap en raakt de zwaarste wetgeving niet. De inhoud hieronder is een hypothese: er is geen gepubliceerde bron gevonden over hoe Belgische betonaannemers calculeren en nacalculeren. De klant moet dit in fase 0 bevestigen.

### Waarom deze snede eerst

| Criterium | Werf naar kantoor (aanbevolen) | Geldstroom (offerte, vorderingsstaat, factuur) |
|---|---|---|
| Waarde voor de klant | Uren, m³ en materieel per werf: data die nu ontbreekt | Vervangt een tool die de klant al heeft |
| Wettelijk risico | Laag: GDPR en tijdsregistratie | Hoog: btw-regimes, Peppol, inhoudingsplicht |
| Overstapkost voor de klant | Geen, draait ernaast | Hoog, net na de Peppol-overstap |
| Concurrentie | Zwak op betonspecifiek | Frontaal met gevestigde spelers |
| Inspanning (eigen schatting) | 25 tot 40 dagen plus fundament | 30 tot 50 dagen plus fundament |
| Commerciële haak later | Middelmatig | Sterk |

### Omvang van de MVP (eigen schatting, te valideren)

| Onderdeel | Inhoud | Werkdagen |
|---|---|---|
| Fundament | Login, tenants, rollen, klanten, werven, artikels, pdf, hosting, back-ups | 15 tot 25 |
| Werf-app (PWA) | In- en uitklokken per werf, uren per activiteit (bekisten, vlechten, storten), afwezigheidscodes, materieel en machines, foto's | 25 tot 40, samen met de twee volgende rijen |
| Betonbonnen | Foto van de leveringsbon, m³ en betonsamenstelling, koppeling aan werf en stortfase | inbegrepen |
| Goedkeuring en nacalculatie | Goedkeuring door werfleider; per werf: uren en m³ tegenover budget; export naar Excel | inbegrepen |
| **Totaal MVP** | | **40 tot 65 dagen, 8 tot 12 weken** |

Uitdrukkelijk **niet** in de MVP: offertes, vorderingsstaten, facturen, Peppol-verzending, boekhoudkoppeling, planbord, aankopen, de RSZ-webservice en loonberekening.

### Hypotheses over de pijnpunten van de klant

| Nr. | Hypothese | Grondslag | Valideren met |
|---|---|---|---|
| 1 | Nacalculatie in fysieke eenheden ontbreekt: m³ besteld, geleverd en theoretisch; kg wapening; m² bekisting; uren per m³ | Eigen vakkennis, geen bron | Klant |
| 2 | Betonbonnen raken zoek; factuurcontrole van de centrale is lastig | Duplicaat van een bon kost 15 euro per stuk, minimum 50 euro per aanvraag ([Heidelberg Materials](https://www.heidelbergmaterials-benelux.com/sites/default/files/2023-12/bijzondere_voorwaarden_beton_belgi%C3%AB_2023.11.28%20.pdf)) | Klant |
| 3 | Toeslagen (wachturen, onvolle vracht, pomp, winter, zaterdag) worden niet opgevolgd | Geen bron | Klant, facturen van de centrale |
| 4 | Ploegplanning met pomp, mixers, kraan en bekisting gebeurt via telefoon en berichten | Aanname | Klant |
| 5 | Huur en rotatie van bekisting is een verborgen kost | Aanname | Klant |
| 6 | Vorderingsstaten worden in Excel gemaakt op de meetstaat van de architect | Aanname; Excel is het gangbare uitwisselmedium ([Buildwise Coplaco](https://www.buildwise.be/media/5ghhgl1d/coplaco-handleiding.pdf)) | Klant |

### Betonspecifiek datamodel (voorstel, niet uit bronnen)

Het model draait rond de **stortfase**: datum, element, m³, betonspecificatie, pomp ja of nee, centrale. Per vrachtwagen komt er een leveringsbon met bonnummer, tijden, m³ en eventuele wachttijd. Nacalculatie vergelijkt het geleverde volume met het theoretische volume uit de meetstaat. Zo wordt meerverbruik zichtbaar. Uren komen uit de tijdsregistratie per activiteit. In een latere fase leidt het gestorte volume per element bijna automatisch tot de maandelijkse vorderingsstaat. Omdat leveranciersfacturen nu als gestructureerde Peppol-factuur binnenkomen, wordt een automatische driehoekscontrole van bestelling, bon en factuur haalbaar. Dat is het sterkste onderscheidende kenmerk voor later.

Of betoncentrales een digitale leveringsbon of API aanbieden, is niet onderzocht. De verkoopvoorwaarden van Heidelberg Materials spreken wel van ondertekening op "de Handheld". FedBeton werkt samen met een telematicaleverancier ([Suivo](https://suivo.com/?p=5267)). Rechtstreeks navragen bij FedBeton en de centrale van de klant is een actiepunt voor fase 0.

### Succescriteria voor de MVP (eigen drempels)

| Criterium | Drempel |
|---|---|
| Gebruik op de werf | Minstens 80% van de uren via de app na vier weken |
| Betonbonnen | Minstens 90% van de leveringen geregistreerd |
| Nacalculatie | Eerste werf met volledige vergelijking van budget en werkelijkheid binnen acht weken na livegang |
| Klant | Tekent het onderhoudscontract en wil referentie zijn |

## 6. Architectuur en technologiekeuzes

**Kies een saaie monoliet op PostgreSQL, met een responsieve webapp en een PWA voor de werf, en koop alles wat gereguleerd is.** De enige beslissing die later moeilijk terug te draaien is, is multi-tenancy ([Aloa](https://aloa.co/ai/resources/deep-dive/scope-a-saas-mvp)). Die moet er dus vanaf dag één in zitten, ook voor één klant. De stackaanbevelingen zijn eigen oordeel, niet gebaseerd op een geciteerde vergelijking.

### Kernkeuzes

| Onderwerp | Keuze | Reden | Status |
|---|---|---|---|
| Stack | Het framework dat de ontwikkelaar het best kent (Laravel, Django, Rails, .NET of TypeScript) | Alle zijn toereikend; snelheid telt | Eigen oordeel |
| Database | PostgreSQL met `tenant_id` op elke tabel en row-level security | Eenvoudigste model voor tientallen tot honderden klanten | Eigen oordeel |
| Maatwerk per klant | Sjablonen en instellingen, geen aparte codetakken | Vermijdt forks | Eigen oordeel |
| Mobiel | PWA met offline wachtrij voor werfbonnen | Volstaat meestal in Vlaanderen; native pas bij pushmeldingen of achtergrond-gps | Eigen oordeel |
| Offline sync | Alleen als werven echt geen dekking hebben; dan PowerSync of ElectricSQL ([PowerSync](https://powersync.com/blog/electricsql-vs-powersync)) | Leveranciersbron, bevooroordeeld | Indicatief |
| Pdf | HTML-sjabloon naar pdf met een headless browser | Sjabloon per tenant telt meer dan de engine | Eigen oordeel |
| Hosting | EU-regio bij een Europese provider of hyperscaler | Zie sectie 7 | |
| Meertaligheid | Vertaalstructuur vanaf het begin; eerst alleen Nederlands | Frans later; werftalen (Pools, Roemeens, Portugees) mogelijk eerder | Eigen oordeel |

### Bouwen of kopen

| Component | Advies | Indicatieve prijs | Bron |
|---|---|---|---|
| Peppol versturen en ontvangen | Kopen | Recommand: gratis tot 25 documenten, daarna 0,30 euro; 29 euro per maand voor 200 documenten; 99 euro voor 1.000 | [openbankingtracker](https://openbankingtracker.com/peppol-providers) |
| Peppol, alternatief | Kopen | Digiteal: 365 euro opstart, minimum 85 euro per maand | [Digiteal](https://www.digiteal.eu/pricing/) |
| Zelf Peppol-toegangspunt worden | Niet doen | Lidmaatschap, certificatie en ISO-plicht | [OpenPeppol](https://peppol.org/join/fees/), [Storecove](https://www.storecove.com/blog/en/peppol-standards-iso-certification) |
| Boekhoudkoppeling | Eerst export plus één directe koppeling; later Chift | Chift: prijs op aanvraag | [Chift](https://docs.chift.eu/unified-apis/accounting/connectors) |
| Bankkoppeling | Kopen (Ponto) | Circa 1 tot 4 euro per rekening per maand | [Informer](https://www.informer.nl/ponto) |
| Herkenning van bonnen en facturen | Kopen of taalmodel | Mindee: circa 0,05 tot 0,10 dollar per pagina | [Mindee](https://mindee.com/l/invoice) |
| Authenticatie | Kopen of open source hosten | Clerk Pro 25 dollar per maand; WorkOS SSO circa 125 dollar per connectie per maand | [Clerk](https://clerk.com/articles/the-real-cost-of-enterprise-sso-per-connection-vs-per-mau-pricing.md), [SSOJet](https://ssojet.com/blog/enterprise-authentication-pricing-2026) |
| Planbord | Component kopen | Syncfusion gratis onder 1 miljoen dollar omzet en minder dan 5 ontwikkelaars; Bryntum via OEM-offerte; DHTMLX Commercial sluit SaaS uit | [Syncfusion](https://www.syncfusion.com/blogs/post/milestone-syncfusion-s-community-license), [Bryntum](https://bryntum.com/oem-pricing/), [DHTMLX](https://dhtmlx.com/docs/products/dhtmlxScheduler/commercial) |
| Check In and Out at Work | Zelf bouwen als connector | Certificaat en technische gebruiker; simulatieomgeving beschikbaar | [socialsecurity.be](https://www.socialsecurity.be/site_nl/employer/applics/checkinatwork/general/how.htm) |
| Boekhouding, loon, bankbetalingen | Nooit zelf bouwen | Integreren met boekhouder en sociaal secretariaat | Eigen oordeel |

De Peppol-prijzen van Billit spreken elkaar tegen tussen bronnen ([e-invoice.app](https://www.e-invoice.app/vendors/billit), [Rentman](https://rentman.io/integrations/billit)). Eigen schatting van de variabele kost per klant van 15 personen: 15 tot 70 euro per maand. Bij 300 tot 450 euro omzet per klant is de brutomarge dan 80 tot 93 procent, vóór supporttijd.

De RSZ certificeert geen oplossingen van leveranciers. De werkgever blijft wettelijk aansprakelijk, ook als hij software van een leverancier gebruikt ([socialsecurity.be](https://www.socialsecurity.be/foreign/working_in_belgium/en/checkinatwork.html)). Fouten in zo'n koppeling stellen de klant dus bloot. Dat is een reden om de koppeling pas na de MVP te bouwen.

### Bestaande platformen als basis

| Optie | Voordeel | Nadeel | Oordeel |
|---|---|---|---|
| Odoo | Boekhouding, aankoop, facturatie en gratis Peppol ingebouwd ([Odoo](https://www.odoo.com/electronic-invoicing/belgium)) | Enterprise kost circa 31 tot 61 dollar per gebruiker per maand ([Odoo pricing](https://www.odoo.com/nl_BE/pricing)); eet de marge op; Belgische bouwlogica moet toch gebouwd worden | Goed als integrator voor 5 tot 15 klanten, slecht voor een eigen product |
| ERPNext | Geen prijs per gebruiker | GPLv3; rechtspositie van gesloten maatwerk betwist ([Frappe forum](https://discuss.frappe.io/t/licensing-of-app-made-using-frappe-erpnext/9836)) | Afgeraden zonder juridisch advies |
| Bouwen op Robaws via API | Klant houdt een compleet pakket; alleen de betonmodule is maatwerk | Afhankelijk van een concurrent; weinig eigen productwaarde | Ernstig alternatief als de klant al Robaws gebruikt |

### AI-ondersteund ontwikkelen: reken op "wat sneller", niet op "tien keer sneller"

Het bewijs is gemengd. Een gerandomiseerde studie van METR vond dat ervaren ontwikkelaars op grote, bekende codebases 19 procent trager werkten met AI-tools, terwijl ze dachten sneller te zijn ([InfoQ](https://www.infoq.com/news/2025/07/ai-productivity)). Een NBER-paper op basis van meer dan 100.000 ontwikkelaars mat 40 tot 180 procent meer commits ([NBER](https://www.nber.org/system/files/working_papers/w35275/w35275.pdf)). Een Harvard-studie zag meer code, maar ook 49 procent langere doorlooptijd van review ([samenvatting](https://letsdatascience.com/news/harvard-study-finds-ai-coding-agents-raise-code-volume-not-o-ea78729b)). Geen enkele studie dekt een solo-ontwikkelaar op een nieuw project. Eigen planningsaanname: 1,5 tot 2,5 keer sneller op implementatie, en geen versnelling op analyse, workshops, datamigratie, testen en support. Het risico is dat één persoon meer code genereert dan hij kan controleren. Geautomatiseerde tests op alle geldlogica zijn daarom verplicht.

## 7. Security, GDPR, NIS2 en ISO 27001

**Bouw vanaf dag één volgens CyFun Basic, laat dat verifiëren bij de eerste betalende klanten, en stel ISO 27001 uit tot een klant het eist.** De vendor valt als micro-onderneming zeer waarschijnlijk niet rechtstreeks onder NIS2. De EU Data Act geldt wel, zonder kmo-uitzondering.

### Certificatiepad

| Stap | Wat | Kost (indicatief) | Wanneer |
|---|---|---|---|
| 1 | CyFun Basic zelfevaluatie; werkboek en portaal zijn gratis ([Easy Cyber Protection](https://easycyberprotection-com.pages.dev/learn/cyberfundamentals/cab-audit-cost)) | Eigen tijd | Fase 0 en 1 |
| 2 | Trustpagina: hosting, verwerkersovereenkomst, subverwerkers, back-updoelen | Eigen tijd | Bij livegang |
| 3 | Eerste pentest | 5.000 tot 12.000 euro (eigen schatting op basis van 1.000 tot 1.800 euro per dag, [DeepStrike](https://deepstrike.io/blogs/penetration-testing-companies-belgium-2025)) | Vóór de tweede klant |
| 4 | CyFun Basic laten verifiëren | Circa 1.000 euro per jaar volgens een CCB-presentatie uit 2024 ([CCB](https://blog.cybersecuritycoalition.be/wp-content/uploads/Johan-Klykens_CCB_GRCBeConnected_28MAR2024final.pdf)); mogelijk verouderd | Bij 3 tot 5 klanten |
| 5 | CyFun Important | Niet gevonden | Als een grotere klant het vraagt |
| 6 | ISO 27001 | 15.000 tot 40.000 euro in jaar één (eigen schatting) | Alleen bij contractuele eis |

Het CCB raadt leveranciers van NIS2-entiteiten minstens niveau Basic aan; dat is een aanbeveling, geen plicht, en gekend via blogs die het CCB citeren ([Easy Cyber Protection](https://easycyberprotection-com.pages.dev/learn/nis2/supply-chain)). Bij Basic en Important wordt de zelfevaluatie geverifieerd; alleen Essential is een certificatie-audit ([CCB-presentatie](https://blog.cybersecuritycoalition.be/wp-content/uploads/Johan-Klykens_CCB_GRCBeConnected_28MAR2024final.pdf)). CyFun 2025 is afgestemd op NIST CSF 2.0 en NIS2 ([CCB](https://ccb.belgium.be/news/cyfunr-2025-here)). Het aantal controls per niveau is **tegenstrijdig** in secundaire bronnen: Basic 34 of 25, Important 117 of 132, Essential 140 of 217 ([Easy Cyber Protection](https://easycyberprotection-com.pages.dev/learn/cyberfundamentals/what-is), [Hedylium](https://hedylium-site.pages.dev/en/articles/cyberfundamentals-niveaux)). Het officiële werkboek geeft uitsluitsel.

### ISO 27001 voor één tot twee personen

| Vraag | Antwoord | Bron |
|---|---|---|
| Kan het met één of twee personen? | Ja. Er is een gedocumenteerd geval van een softwarebedrijf met twee personen | [cloudonaut](https://cloudonaut.io/getting-iso-27001-certified-as-a-2-person-company/), [Advisera](https://community.advisera.com/topic/iso-27001-implementation-28/) |
| Wat is het struikelblok? | Functiescheiding en onafhankelijke interne audit; compenserende maatregelen zijn toegelaten | [Advisera 5.3](https://advisera.com/iso27001/control-5-3-segregation-of-duties/) |
| Hoe verloopt het? | Stage 1 en stage 2; certificaat drie jaar geldig; jaarlijkse opvolgingsaudit; interne audit vooraf | [Orbiq](https://www.orbiqhq.com/nl/compliance-automatisering/kosten-iso-27001-certificering) |
| Doorlooptijd | Meestal 6 tot 10 maanden | [Consilien](https://consilien.com/news/iso-27001-certification-cost-timeline) |
| Auditkost | Circa 5 auditdagen voor 1 tot 10 medewerkers; circa 7.800 dollar of 6.250 pond | [Auditfront](https://auditfront.pages.dev/blog/iso-27001-certification-cost), [High Table](https://hightable.io/iso-27001-certification-cost/) |
| Totaal jaar één | 8.000 tot 50.000 dollar naargelang de bron | [Consilien](https://consilien.com/news/iso-27001-certification-cost-timeline), [Auditfront](https://auditfront.pages.dev/blog/iso-27001-certification-cost) |
| Wie certificeert in België? | Brand Compliance, KPMG Certification en Bureau Veritas melden BELAC-accreditatie | [Brand Compliance](https://brandcompliance.com/en/certification-body/accreditations/), [KPMG](https://kpmg.com/be/en/services/kpmg-certification.html), [Bureau Veritas](https://benelux.bureauveritas.com/en/iso-27001isms-information-security-certification) |

Er is **geen Belgische prijslijst** gevonden. Alle bedragen zijn generieke schattingen van verkopers, in dollar of pond. De eigen raming (audit 6.000 tot 12.000 euro, opvolging 2.500 tot 4.500 euro per jaar, tooling 4.000 tot 12.000 euro per jaar, plus 20 tot 40 eigen werkdagen) is een afleiding en moet met twee of drie offertes worden getoetst. Vanta en Drata starten rond 7.500 tot 12.000 dollar per jaar ([soc2auditors](https://soc2auditors.pages.dev/insights/soc-2-software-pricing-comparison/)) en zijn voor een Belgische micro-vendor waarschijnlijk te duur. CISO Assistant is open source en bevat CyFun 2025 ([GitHub](https://github.gg22.workers.dev/intuitem/ciso-assistant-community/discussions/3867)). Een solo-ontwikkelaar heeft in de praktijk een externe interne auditor nodig. Met een tweede persoon wordt functiescheiding merkbaar eenvoudiger.

Concurrentieel is het beeld gemengd. Visma Bouwsoft staat als entiteit op een ISO 27001-certificaat van de groep. Bij Robaws beschrijft de vermelding vermoedelijk het datacenter. Bij Vertuoza en Bouwflow is niets gevonden. **Wat Belgische aannemers feitelijk van softwareleveranciers eisen, is niet met bronnen onderbouwd.** De verwachting, uit achtergrondkennis, is dat kleine aannemers alleen een verwerkersovereenkomst vragen en dat grote groepen vragenlijsten sturen.

### Regelgeving voor de vendor

| Regel | Geldt voor de vendor? | Gevolg voor het product | Bron |
|---|---|---|---|
| NIS2 (wet van 26 april 2024) | Zeer waarschijnlijk niet rechtstreeks; wel indirect via klanten | CyFun Basic als antwoord op leverancierseisen | [Unizo](https://www.unizo.be/ondernemersgids/bedrijfsvoering/digitalisering/it-cloud-security/nis-2), [CCB](https://ccb.belgium.be/en/nis2) |
| EU Data Act, overstapregels | Ja, sinds 12 september 2025, zonder kmo-uitzondering | Exportfunctie voor alle klantdata; opzeg maximaal twee maanden; geen overstapkosten vanaf 12 januari 2027 | [Eubelius](https://www.eubelius.com/en/news/the-eu-data-act-in-force-what-changes-on-12-september-2025), [Pinsent Masons](https://publications.pinsentmasons.com/vario-uk/euda-handbook/the-new-switching-regime), [DLA Piper](https://www.dlapiper.com/en-es/insights/publications/2025/07/understanding-switching-termination-rights-under-the-data-act) |
| Cyber Resilience Act | In principe niet voor zuivere SaaS | Geen actie | [DLA Piper](https://www.dlapiper.com/en/insights/publications/2026/02/cyber-resilience-act-the-fine-line-between-saas-and-digital-products) |
| GDPR | Ja, als verwerker voor de aannemer | Verwerkersovereenkomst, subverwerkerslijst, EU-hosting, bijstand bij datalekken | Achtergrondkennis, niet geverifieerd |
| AI Act | Alleen bij AI-functies | Geen AI die werknemers beoordeelt of taken toewijst op basis van gedrag | Achtergrondkennis, niet geverifieerd |

Dat de bouw niet in de NIS2-bijlagen staat, is achtergrondkennis en niet door een bron bevestigd. De Data Act maakt meerjarige contracten met lock-in juridisch kwetsbaar. Dat is een argument tegen het contractmodel van Vertuoza en vóór maandelijks opzegbare voorwaarden.

### De twee gevoelige GDPR-punten

**Rijksregisternummer.** Het nummer is in België sterk gereguleerd ([KSZ-beraadslaging](https://bcss.fgov.be/sites/default/files/assets/gegevensbescherming/beraadslagingen/12_013_n320.pdf)). Registratie voor Checkinatwork gebeurt met eID, rijksregisternummer of Limosa-nummer ([socialsecurity.be](https://www.socialsecurity.be/site_nl/employer/applics/checkinatwork/general/how.htm)). Of een verwerker het nummer zonder aparte machtiging mag verwerken wanneer een wet het gebruik oplegt, is **niet geverifieerd**. Ontwerpadvies: niet opslaan in de MVP. Later alleen met veldversleuteling, gemaskeerde weergave, strikte rollen en logging van elke inzage. Een privacyjurist moet dit valideren vóór livegang.

**Locatie en tijdsregistratie.** De Gegevensbeschermingsautoriteit oordeelde in 2023 dat een permanent actief volgsysteem zonder transparantie de AVG schond ([Claeys & Engels](https://legalnews.be/arbeid-sociale-zekerheid/geolocalisatiesysteem-in-voertuigen-van-werknemers-gba-brengt-voorwaarden-in-herinnering-voor-legitiem-gebruik-claeys-engels/)). Toestemming is geen geldige rechtsgrond; gerechtvaardigd belang kan, mits proportionaliteit ([Securex](https://www.securex.be/nl/lex4you/werkgever/themas/verplichtingen-werkgever/gdpr-en-privacy/is-geolokalisatie-wettelijk-toegestaan)). Ontwerpadvies: alleen een locatiemoment bij in- en uitklokken, instelbare bewaartermijnen, een duidelijke tekst in de app en een sjabloon voor de effectbeoordeling van de klant. Dat is ook een verkoopargument.

### Technische basis (eigen synthese, niet uit bronnen)

| Domein | Maatregel |
|---|---|
| Tenant-isolatie | Row-level security plus geautomatiseerde tests op toegang tussen tenants |
| Authenticatie | Niet zelf bouwen; tweestapsverificatie verplicht voor beheerders; aanmelden met Microsoft; wachtwoordloos voor arbeiders |
| Versleuteling | TLS overal; versleuteling in rust; extra veldversleuteling voor gevoelige nummers |
| Back-ups | Dagelijks, met herstel naar tijdstip; kopie op tweede EU-locatie; hersteltest per kwartaal |
| Auditlog | Wie deed wat en wanneer, per tenant |
| Ontwikkelproces | Afhankelijkheden automatisch bijwerken; scannen op geheimen; aparte omgevingen; geen productiedata in test |
| Incidenten | Kort plan; klant snel verwittigen zodat die de termijn van 72 uur haalt |
| Verzekering | Beroepsaansprakelijkheid IT plus cyber; premie niet gevonden, offerte nodig |

### Hosting

| Provider | Certificaten volgens bronnen | Opmerking |
|---|---|---|
| OVHcloud | ISO 27001, ISO 27017, SOC 2 Type 2, C5 ([OVHcloud](https://docs.ovhcloud.com/en/guides/account-and-service-management/account-information/security-certifications)) | Breedste Europese portfolio |
| Scaleway | ISO 27001 en HDS ([Scaleway](https://www.scaleway.com/en/security-and-compliance/)) | |
| Hetzner | ISO 27001; C5-status tegenstrijdig ([Qovery](https://www.qovery.com/blog/top-eu-sovereign-cloud-platforms-migration-guide)) | Te verifiëren |
| AWS European Sovereign Cloud | Beschikbaar sinds 15 januari 2026 ([AWS](https://aws.amazon.com/blogs/aws/opening-the-aws-european-sovereign-cloud)) | Voor deze markt niet nodig |

Voor deze markt volstaat een EU-regio, een provider met ISO 27001 en een verwerkersovereenkomst. Soevereiniteit is een commercieel argument, geen wettelijke plicht. Eigen schatting van de hostingkost voor een MVP: 50 tot 300 euro per maand bij een Europese provider.

### Subsidies voor security

De kmo-portefeuille steunt cybersecurity-advies en -opleiding met 45 procent voor kleine ondernemingen, tot 7.500 euro steun per jaar ([VLAIO](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille)). Sinds 1 februari 2026 is cybersecurity het enige overgebleven adviesthema ([Partena](https://www.partena-professional.be/nl/node/22320)). De VLAIO-verbetertrajecten subsidiëren 50 procent van externe begeleiding ([VLAIO](https://vlaio.be/nl/subsidies-financiering/subsidiedatabank/cybersecurity-verbetertrajecten)). De eigen bijdrage is **tegenstrijdig**: 3.550 tot 19.950 euro volgens een VLAIO-pagina, 4.600 tot 17.500 euro volgens een artikel uit 2026 ([VLAIO](https://www.vlaio.be/nl/subsidies-financiering/cybersecurity-verbetertrajecten/welke-financiele-steun-kan-je-krijgen), [Forum for the Future](https://blog.forumforthefuture.be/nl/article/bij-wie-kan-je-terecht-om-je-cyberveiligheid-te-versterken/29210)). Of de audit van de certificatie-instelling zelf subsidieerbaar is, is niet bevestigd.

## 8. Businessmodel en financieel

**Het maatwerkproject is vanaf dag één kaspositief; het product wordt dat pas na jaren.** Het model is daarom: betaald bouwen voor de eerste klant, auteursrechten behouden, onderhoud maandelijks factureren, en pas productiseren als meer klanten tekenen. Bijna alle bedragen in deze sectie zijn eigen schattingen.

### Wat de markt betaalt

Vertuoza haalde begin 2022 1 miljoen euro jaarlijks terugkerende omzet met meer dan 3.000 gebruikers ([tech.eu](https://tech.eu/2022/10/14/belgiums-vertuoza-raises-eur4-million-in-pre-series-a/)). Eigen deling: ongeveer 28 euro per gebruiker per maand. Bij de kapitaalronde van 2023 had Vertuoza 4 miljoen euro terugkerende omzet met 72 medewerkers ([Fortino Capital](https://www.fortinocapital.com/news/vertuoza-reinforces-its-growth-ambitions-and-successfully-concludes-its-10-million-eu-series)). Dat is ongeveer 55.000 euro per medewerker (eigen deling). Het toont hoe arbeidsintensief verkoop, onboarding en support in dit segment zijn. Werkaanname: 30 tot 50 euro per kantoorgebruiker per maand, of 200 tot 450 euro per bedrijf per maand.

### Break-even (eigen schatting)

| Scenario | Omzet per klant per jaar | Klanten voor 120.000 euro | Klanten voor 60.000 euro |
|---|---|---|---|
| Laag | 2.400 euro | 50 | 25 |
| Midden | 3.500 euro | circa 35 | circa 17 |
| Hoog | 5.000 euro | 24 | 12 |

Vaste kosten van 10.000 tot 20.000 euro per jaar voegen 3 tot 8 klanten toe. Het klantverloop bij kmo-software ligt volgens secundaire bronnen tussen 11 en 25 procent per jaar; de bronnen zijn **niet verzoend** ([We Are Founders](https://www.wearefounders.uk/saas-churn-rates-and-customer-acquisition-costs-by-industry-2025-data/)). Tien tot vijftien nieuwe aannemers per jaar is voor één persoon die ook bouwt en ondersteunt al ambitieus. Break-even op abonnementen alleen ligt dus vermoedelijk 2,5 tot 4 jaar ver.

### Inkomsten uit het maatwerkproject (eigen schatting)

| Post | Bedrag |
|---|---|
| Eerste snede, 40 tot 70 factureerbare dagen aan 600 tot 900 euro | 25.000 tot 60.000 euro |
| Hosting en onderhoud | 300 tot 800 euro per maand |
| Onboarding per latere klant, 1 tot 3 dagen | Als opstartkost aanrekenen |

Het dagtarief van 600 tot 900 euro is een aanname; een betrouwbaar Belgisch gemiddelde is niet gevonden. Gangbaar compromis: vol tarief voor klantspecifieke analyse en migratie, verlaagd tarief voor generieke functies die de ontwikkelaar behoudt.

### Contractvorm: licentie, geen overdracht

Naar Belgisch recht ontstaat auteursrecht op software automatisch, en een overdracht moet contractueel geregeld worden ([Unizo](https://www.unizo.be/ondernemersgids/juridisch/intellectuele-eigendom/bescherming-van-software), [LexGO](https://www.lexgo.be/en/news-and-articles/1782-leidraad-bij-de-bescherming-van-apps)). De uitgangspositie is dus gunstig voor de ontwikkelaar. Adviseurs van klanten raden echter aan om overdracht, broncode en documentatie te eisen ([K law](https://legalnews.be/it-ip/softwareontwikkeling-enkele-tips-voor-de-klant-opdrachtgever-k-law/)). Aansprakelijkheid kan niet vrij worden uitgesloten: de regels over onrechtmatige bedingen tussen ondernemingen gelden ook voor IT-contracten ([Jubel](https://www.jubel.be/het-beperken-van-aansprakelijkheid-in-b2b-relaties/), [CMS](https://cms.law/en/int/expert-guides/limitations-and-exclusions-of-liability-in-b2b-contracts/belgium)).

| Clausule | Voorstel (door een IT-jurist te laten nakijken) |
|---|---|
| Eigendom | Ontwikkelaar behoudt alle rechten; klant krijgt een eeuwigdurende, niet-exclusieve licentie voor eigen gebruik |
| Voordeel eerste klant | Korting op de bouwprijs, lange prijsgarantie, inspraak in de roadmap, eventueel 6 tot 12 maanden exclusiviteit in de regio |
| Continuïteit | Broncode in bewaring of toegang bij stopzetting of uitval |
| Onderhoud | Apart contract met maandbedrag en reactietijden |
| Aansprakelijkheid | Plafond, zo opgesteld dat het buiten de grijze lijst blijft |
| Gegevens | Verwerkersovereenkomst; export op elk moment |

### Subsidies en fiscaliteit

| Instrument | Inhoud | Bruikbaar? | Bron |
|---|---|---|---|
| VLAIO ontwikkelingsproject | 25 tot 50 procent van aanvaarde kosten; minimum 25.000 euro subsidie; nieuwe procedure vanaf 1 januari 2027 | Alleen met echte innovatie, bijvoorbeeld meetstaat-extractie met AI. Kans laag tot matig (eigen schatting) | [VLAIO](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/ontwikkelingsproject-subsidie-voor-innovatie) |
| Kmo-groeisubsidie | Afgeschaft | Nee | [VLAIO](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/kmo-groeisubsidie-strategisch-adviesaanwerving-bij-groeitraject) |
| Kmo-portefeuille | Alleen nog cybersecurity | Voor de vendor ja; klanten krijgen geen steun voor implementatie | [VLAIO](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille/wat-is-de-kmo-portefeuille/digitalisering) |
| Innovatieaftrek | 85 procent vrijstelling op inkomsten uit kwalificerende software; onderzoeksproject moet via BELSPO lopen | Pas bij winst; melding vroeg indienen | [VLAIO](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/innovatieaftrek) |
| Auteursrechtenregime | Volgens bronnen opnieuw van toepassing op softwareontwikkelaars vanaf 1 januari 2026 | Met boekhouder bekijken | [LexGO](https://www.lexgo.be/nl/nieuws-en-publicaties/14992-auteursrechtvergoeding-voor-software-opnieuw-fiscaal-voordelig-vanaf-2026) |
| Tax shelter voor starters | Tot 500.000 euro ophalen; 30 tot 45 procent belastingvermindering voor investeerders | Alleen bij externe investeerders | [VLAIO](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/tax-shelter-voor-startende-ondernemingen) |

### Verkoopkanalen (eigen rangschikking)

De beste kanalen voor één persoon zijn: doorverwijzing en een klantverhaal van de eerste klant, twee of drie lokale boekhoudkantoren met bouwklanten, lokale afdelingen van Bouwunie en Embuild, en Nederlandstalige artikels over concrete pijnpunten. Beurzen zijn duur voor één persoon. De verkoopcyclus is naar eigen schatting 1 tot 3 maanden bij zaakvoerders van kleine bedrijven en 3 tot 9 maanden bij vervanging van een bestaand pakket. Bronnen over verkoopcycli in de Belgische bouw zijn niet gevonden.

## 9. Risico's en mitigatie

**De grootste risico's zijn niet technisch: afhankelijkheid van één klant, de onderhoudslast voor één persoon en de terechte vrees van kopers voor een eenmansleverancier.** De inschatting hieronder is eigen oordeel. Er zijn geen Belgische ervaringsverslagen van kleine bouwsoftwareleveranciers gevonden.

### Risicotabel

| Risico | Kans | Impact | Mitigatie |
|---|---|---|---|
| Afhankelijkheid van één klant | Hoog | Hoog | Freelance-inkomen aanhouden in jaar één; 2 tot 3 ontwerppartners vóór verdere bouw; eerste klant onder 50 procent van de omzet binnen 18 maanden |
| De betonniche is te klein | Onbekend | Hoog | Steekproef via jaarrekeningen; generieke aannemerskern met beton als module |
| Scope groeit uit tot een volledige ERP | Hoog | Hoog | Geen boekhouding, loon of bankbetalingen; wensen van één klant zijn instelbaar of worden geweigerd |
| Wetgevingsonderhoud | Zeker | Middel | Peppol, boekhoud- en bankkoppelingen kopen; btw-logica in één geteste module |
| Supportlast | Hoog | Middel | Vast onboardingpakket; support via tickets met vaste uren; vanaf 30 tot 40 klanten een deeltijdse kracht |
| Uitval van de ontwikkelaar | Middel | Hoog | Continuïteitsovereenkomst met tweede ontwikkelaar of klein bureau; gedocumenteerd herstel; export voor de klant |
| Faillissement of wanbetaling van klanten | Middel | Middel | Mikken op gevestigde bedrijven met personeel; maandelijks vooraf factureren |
| Fout in geld- of btw-logica | Middel | Hoog | Geautomatiseerde tests; gefaseerde uitrol; jaarlijkse externe codereview; verzekering |
| Datalek of privacyklacht | Laag tot middel | Hoog | CyFun Basic; geen rijksregisternummer in de MVP; locatie alleen bij klokken |
| Gevestigde speler bouwt een betonmodule | Laag tot middel | Middel | Diepte en persoonlijke begeleiding; overname als legitieme uitkomst |
| Klant eist overdracht van de broncode | Middel | Hoog | Vooraf contractueel regelen; licentie plus bewaring aanbieden |
| AI genereert meer code dan één persoon kan controleren | Middel | Middel | Tests op geldlogica; kleine stappen; review |

### Open vragen voor de eerste klant

| Nr. | Vraag | Waarom het telt |
|---|---|---|
| 1 | Welke software gebruikt de klant nu voor facturatie, boekhouding en loon? | Bepaalt koppelingen en of bouwen op Robaws een optie is |
| 2 | Hoe gebeuren calculatie en nacalculatie vandaag, en met welke normen? | Kern van de MVP; geen bron beschikbaar |
| 3 | Hoeveel werven, ploegen, kantoorgebruikers en betonleveringen per maand? | Prijs en omvang |
| 4 | Welke centrales leveren, en bieden zij digitale bonnen of een portaal? | Mogelijke integratie |
| 5 | Welke opdrachtgevers: privé, overheid, hoofdaannemers? In welke opmaak worden vorderingsstaten gevraagd? | Omvang van fase 2 |
| 6 | Zijn er werven boven 500.000 euro en hoe gebeurt de aanwezigheidsregistratie nu? | Urgentie van 1 april 2027 |
| 7 | Is er dekking op de werven? Welke talen spreken de arbeiders? Eigen toestel of toestel van de zaak? | PWA, offline, vertalingen |
| 8 | Aanvaardt de klant een licentie in plaats van eigendom, en wat wil hij in ruil? | Go of no-go |
| 9 | Welke securityvragen stellen zijn eigen opdrachtgevers? | Timing van CyFun en ISO |
| 10 | Kent de klant 3 tot 5 collega-aannemers die willen meekijken? | Poort naar productisering |

### Open vragen voor een jurist

| Nr. | Vraag |
|---|---|
| 1 | Is een schriftelijke overdracht vereist en volstaat de voorgestelde licentieconstructie? De wettekst is niet gelezen |
| 2 | Hoe formuleer je een aansprakelijkheidsplafond dat de regels over onrechtmatige bedingen doorstaat? |
| 3 | Mag een verwerker het rijksregisternummer verwerken zonder aparte machtiging wanneer de wet het gebruik oplegt? |
| 4 | Welke contractclausules vraagt de Data Act over overstappen en opzeg? |
| 5 | Is een effectbeoordeling verplicht voor tijdsregistratie met locatie, en wat hoort in het beleid van de klant? |
| 6 | Wat is de aansprakelijkheid van de leverancier bij een fout in de koppeling met de RSZ? |
| 7 | Wat zijn gangbare voorwaarden en kosten voor bewaring van broncode in België? |

### Open vragen voor een boekhouder of sociaal secretariaat

| Nr. | Vraag |
|---|---|
| 1 | Wat is de juiste startdatum en drempel van de RSVZ-inhouding, en wat dekt de webservice vandaag? |
| 2 | Valt betaling aan de betoncentrale onder de inhoudingsplicht, en hoe verhoudt dat zich tot btw verlegd? |
| 3 | Wat zijn de exacte wettelijke factuurteksten voor btw verlegd en het tarief van 6 procent? |
| 4 | Welk exportformaat verwacht het sociaal secretariaat voor uren, mobiliteit en weerverlet? |
| 5 | Is het auteursrechtenregime bruikbaar voor de licentie-inkomsten, en heeft een melding bij BELSPO zin? |
| 6 | Vennootschap of eenmanszaak, gelet op aansprakelijkheid en de tax shelter? |
| 7 | Bestaan er nog fiscale voordelen voor klanten die digitale facturatiesoftware kopen? Dit is niet uit een primaire bron bevestigd |

### Te verifiëren cijfers

De volgende gegevens moeten in de primaire bron worden nagekeken voordat ze in een businessplan komen: het aantal bouwbedrijven per grootteklasse en gewest; de actuele prijspagina's van de vier concurrenten; de officiële aantallen controls van CyFun en de prijs van verificatie; offertes van certificatie-instellingen; de technische documentatie van de RSZ-webservices; en de definitieve regels voor Check In and Out at Work.

## 10. Roadmap en planning

**Plan in vijf fasen met vier harde beslismomenten, en bouw nooit verder dan de laatste gepasseerde poort.** De eerste poort valt al na vier tot zes weken en kost alleen analyse. De planning start op 16 november 2026. Alle doorlooptijden zijn eigen schattingen voor één ontwikkelaar die AI-ondersteund werkt.

### Fasen

| Fase | Periode | Inhoud | Resultaat |
|---|---|---|---|
| 0. Analyse en contract | Half november 2026 tot eind december 2026 | Procesanalyse bij de klant; hypotheses uit sectie 5 toetsen; demo's bij Robaws en Bouwflow; steekproef betonaannemers; contract; keuze van stack en tenantmodel; start CyFun-zelfevaluatie | Getekend contract, functionele beschrijving, marktraming |
| 1. MVP werf naar kantoor | Januari 2027 tot eind maart 2027 | Fundament, werf-app, betonbonnen, goedkeuring, eerste nacalculatie; wekelijkse terugkoppeling op echte werven | Live bij de klant vóór 1 april 2027 |
| 2. Nacalculatie en geldstroom | April 2027 tot juli 2027 | Dashboards; Peppol-ontvangst voor factuurcontrole; daarna offerte, vorderingsstaat en factuur via een Peppol-provider; boekhoudexport; pentest | Klant kan zijn facturatietool vervangen als hij dat wil |
| 3. Productiseren | Augustus 2027 tot februari 2028 | Planbord, aankopen, tweede en derde klant, prijspagina, opstartpakket, verificatie CyFun Basic | Drie tot vijf betalende klanten |
| 4. Opschalen | Vanaf 2028 | Frans, koppeling met de RSZ, controle inhoudingsplicht, boekhoudaggregator, eerste medewerker of partner | Dertig tot veertig klanten |

### Go/no-go-momenten

| Poort | Wanneer | Go als | No-go of bijsturen als |
|---|---|---|---|
| G0: contract | Eind december 2026 | Klant tekent licentie en onderhoud; betaalt de analyse; proces bevestigt minstens drie van de zes hypotheses | Klant eist volledige eigendom zonder meerprijs, of een bestaand pakket dekt de behoefte: dan configuratie van dat pakket aanbieden als dienst |
| G1: MVP in gebruik | Eind april 2027 | Minstens 80 procent van de uren via de app; betonbonnen geregistreerd; klant betaalt onderhoud | Ploegen gebruiken de app niet: eerst gebruiksgemak oplossen, niets nieuws bouwen |
| G2: productpotentieel | Juli 2027 | Eerste werf volledig nagecalculeerd; twee tot drie ontwerppartners met intentieverklaring; marktraming toont voldoende betonaannemers | Geen interesse buiten de eerste klant: blijven bij maatwerk plus onderhoud, geen verdere productinvestering |
| G3: product of dienst | Februari 2028 | Drie tot vijf betalende aannemers op dezelfde codebase; verloop onder controle | Minder dan drie: stoppen met productiseren, of gesprek met een gevestigde speler over integratie of overname |
| G4: ISO 27001 en aanwerven | Wanneer het zich aandient | Een klant eist ISO 27001 contractueel en de deal dekt de kost; of dertig tot veertig klanten | Zonder concrete eis: bij CyFun blijven |

### Externe data die de planning sturen

| Datum | Gebeurtenis | Gevolg |
|---|---|---|
| 1 januari 2027 | Aangekondigde algemene tijdsregistratie, nog geen definitieve wet ([Securex](https://www.securex.be/nl/lex4you/werkgever/nieuws/tijdsregistratie-vanaf-2027-waar-staan-we-vandaag)) | Extra argument voor de werf-app |
| 1 januari 2027 | Nieuwe VLAIO-procedure voor ontwikkelingsprojecten ([VLAIO](https://www.vlaio.be/nl/subsidies-financiering/ontwikkelingsproject/aanvraag-en-evaluatieprocedure/nieuw-proces-onderzoeks-en-ontwikkelingsprojecten-2027)) | Eventuele aanvraag pas daarna |
| 12 januari 2027 | Overstapkosten verboden onder de Data Act ([DLA Piper](https://www.dlapiper.com/en-es/insights/publications/2025/07/understanding-switching-termination-rights-under-the-data-act)) | Contractmodel zonder exitkosten |
| 1 april 2027 | Check In and Out at Work voor werken in onroerende staat ([Lexgo](https://www.lexgo.be/nl/nieuws-en-publicaties/15016-actief-op-belgische-werven-vanaf-2027-wordt-in-en-uitchecken-verplicht)) | Streefdatum voor livegang van de MVP |
| 18 april 2027 | NIS2-entiteiten moeten hun niveau geverifieerd of gecertificeerd hebben ([Hedylium](https://hedylium-site.pages.dev/en/articles/cyberfundamentals-niveaux)) | Meer leveranciersvragen verwacht |
| 1 januari 2028 | Geplande e-reporting ([Comarch](https://www.comarch.com/trade-and-services/data-management/legal-regulation-changes/belgium-confirms-2026-peppol-e-invoicing-mandate-with-2028-near-real-time-reporting-to-follow/)) | Via de Peppol-provider opvangen |

De MVP is in drie maanden haalbaar als de klant wekelijks tijd vrijmaakt en als de omvang beperkt blijft tot sectie 5. De streefdatum van 1 april 2027 is ambitieus maar commercieel sterk. Eén klokactie kan dan dienen voor loon, nacalculatie en later de wettelijke registratie. De koppeling met de RSZ zelf hoort niet in de MVP, omdat de specificaties nog niet beschikbaar waren.

### Budget voor het eerste jaar (eigen schatting)

| Post | Bedrag |
|---|---|
| Hosting en tools | 1.000 tot 4.000 euro |
| Jurist voor contract en privacy | Niet gevonden; offerte vragen |
| Pentest | 5.000 tot 12.000 euro, mogelijk deels via kmo-portefeuille |
| Verificatie CyFun Basic | Circa 1.000 euro, te bevestigen |
| Verzekering | Niet gevonden; offerte vragen |
| Componenten zoals het planbord | 0 tot 5.000 euro |
| Inkomsten uit maatwerk en onderhoud | 25.000 tot 60.000 euro plus 300 tot 800 euro per maand |

Het traject is dus alleen zinvol als de eerste klant de bouw betaalt. Zonder die betaling verandert het van een kaspositief project in een speculatieve investering van zes tot tien maanden eigen tijd, tegen gefinancierde concurrenten.

## 11. Bronnen

Alle bronnen zijn geraadpleegd via fragmenten uit zoekresultaten op 14 november 2026. Geen enkele pagina is volledig gelezen. Bronnen van leveranciers en concurrenten zijn als zodanig gemarkeerd.

### Markt en sector

- [Statbel be.STAT, btw-plichtigen bouw, eind 2025](https://bestat.statbel.fgov.be/bestat/api/views/d198b9d1-2d0b-4186-8f16-35638f73df4b/result/PDF)
- [Statbel be.STAT, ondernemingen eind 2023](https://bestat.statbel.fgov.be/bestat/api/views/9d19ebe2-f35a-4b51-ac1a-c153e6d77d67/result/PDF)
- [Embuild, Kerncijfers van de Belgische bouw 2023](https://cms.embuild.be/election/media/_Users/Kerncijfers%20van%20de%20Belgische%20bouw%20-%202023.pdf)
- [Statbel, faillissementenrapport mei 2025](https://statbel.fgov.be/sites/default/files/files/documents/Ondernemingen/7.5%20Faillissementen/report_BRI_2025_05_NL.pdf)
- [GraydonCreditsafe, studie oktober 2025](https://www.creditsafe.com/content/dam/be/press-releases/files/Studie-faillissementen-20251001.pdf)
- [Made in West-Vlaanderen, faillissementen eerste negen maanden 2026](https://www.made-in.be/west-vlaanderen/eerste-negen-maanden-waren-in-west-vlaanderen-rampzalig-voor-falingen-dixit-graydoncreditsafe/)
- [Brussels Times, daling bouwsector](https://www.brusselstimes.com/belgium/1863380/belgiums-construction-sector-continues-to-decline/)
- [VRT NWS, bouwsector onder druk, 18 juni 2026](https://www.vrt.be/vrtnws/nl/2026/06/18/vlaams-brabant-bouwsector-onder-druk-winstmarges-failissementen/)
- [VRT NWS, faillissementen eerste kwartaal 2025](https://www.vrt.be/vrtnws/nl/2025/04/18/faillissementen-vlaanderen-eerste-kwartaal/)
- [Made in Antwerpen, vacatures en leerlingenaantallen](https://www.made-in.be/antwerpen/bouwfederaties-trekken-aan-alarmbel-over-dalend-aantal-leerlingen-in-bouwrichtingen/)
- [Orange Belgium, enquête digitalisering 2019](https://corporate.orange.be/nl/node/9631)
- [Exact KMO Barometer 2025, sectorrapport bouw](https://files.exact.com/static/web/pdf/mkb-barometer/2025/BENL-CST-mkb-barometer-sectorrapport.pdf) (leverancier)
- [Buildwise, trend- en impactanalyse nr. 40](https://ecobuild.brussels/wp-content/uploads/2023/04/31400-nl-unprotected-trend-en-impactanalyse-van-de-bouwsector-1.pdf)
- [Data Bridge Market Research, Belgische markt](https://www.databridgemarketresearch.com/nucleus/belgium-construction-management-software-market)
- [Banqup, Peppol-cijfers maart 2026](https://www.banqup.com/nl-be/resources/blog/belgium-s-2026-e-invoicing-mandate-what-have-we-learned-so-far-)
- [VRT NWS, negen op tien bedrijven op Peppol](https://www.vrt.be/vrtnws/en/2026/08/03/9-out-of-10-businesses-connect-to-peppol-invoice-network.consumer/)
- [Europages, betonwerken België](https://www.europages.nl/ondernemingen/belgi%C3%AB/betonwerken.html)
- [RevenueBase, concrete contractors Belgium](https://revenuebase.ai/companies/concrete-contractors/belgium)
- [Belg.be, prijsvork bouwsoftware](https://www.belg.be/artikel/software-bouwbedrijf-terugverdientijd-en-roi-berekend~83532)

### Concurrentie

- [Fortino Capital, Vertuoza Series A](https://www.fortinocapital.com/news/vertuoza-reinforces-its-growth-ambitions-and-successfully-concludes-its-10-million-eu-series)
- [tech.eu, Vertuoza pre-Series A](https://tech.eu/2022/10/14/belgiums-vertuoza-raises-eur4-million-in-pre-series-a/)
- [Tracxn, Vertuoza](https://tracxn.com/d/companies/vertuoza/__NWgymfDTszXMof0aMBZ-DcdpenB7Er4iVmu-BwSAUrg)
- [Latka, Vertuoza](https://getlatka.com/companies/vertuoza#team)
- [Vertuoza, website](https://www.vertuoza.com/nl-be) (leverancier)
- [Capterra, Vertuoza](https://www.capterra.com/p/232769/Vertuoza/) en [reviews](https://www.capterra.com/p/232769/Vertuoza/reviews/)
- [Le Conduc, review Vertuoza](https://leconduc.fr/logiciel-batiment/logiciel-gestion-chantier/avis-vertuoza/)
- [comparatif-logiciels, Vertuoza](https://www.comparatif-logiciels.fr/logiciel/avis-vertuoza/)
- [Prezapp, Vertuoza prijs](https://prezapp.be/blog/vertuoza-prix-avis-alternative/) (concurrent)
- [Robaws, prijzen](https://robaws.com/en/pricing) (leverancier)
- [Robaws, SLA](https://robaws.com/en/service-level-agreement) (leverancier)
- [Robaws, product updates 2026](https://support.robaws.com/nl/article/product-updates-2026-mch86v/) (leverancier)
- [Robaws, vergelijking met Bouwsoft](https://robaws.com/nl-BE/vergelijking-robaws-vs-bouwsoft-visma) (concurrent)
- [Robaws, bouwsoftware](https://robaws.com/nl-BE/bouwsoftware) (leverancier)
- [Made in West-Vlaanderen, Robaws](https://www.made-in.be/west-vlaanderen/zwevegemse-robaws-groeit-50-procent-per-jaar-zonder-investeerders/)
- [PitchBook, Robaws](https://pitchbook.com/profiles/company/529670-35)
- [Growjo, Robaws](https://growjo.com/company/Robaws)
- [Embedded Finance Index, Robaws](https://www.embeddedfinanceindex.com/companies/robaws)
- [vsk.nl, Robaws klantenaantal](https://vsk.nl/en/?p=11756)
- [Bedrijfssoftwaregids, vergelijking 2026](https://bedrijfssoftwaregids.nl/blog/projectmanagement-software-bouwbedrijven-2026/)
- [OMR, Robaws prijzen](https://omr.com/en/reviews/product/robaws/pricing)
- [Tekpon, Robaws](https://tekpon.com/software/robaws/reviews/)
- [SaaSworthy, Robaws](https://www.saasworthy.com/product/robaws)
- [SpotSaaS, Robaws](https://www.spotsaas.com/product/robaws)
- [Softwareshaker, Robaws voor bouwbedrijven](https://softwareshaker.com/bouwbedrijven/) (partner van Robaws)
- [Companyweb, NWN Software](https://www.companyweb.be/en/0805950036/nwn-software)
- [LinkedIn, medeoprichter Bouwflow](https://www.linkedin.com/in/wannesmatthys/)
- [G2, Bouwflow](https://www.g2.com/products/bouwflow/reviews)
- [Embuild Plus, Bouwflow](https://embuildplus.be/nl/nieuws/bouwflow-digitale-eenvoud-voor-complexe-bouwprojecten)
- [UNIVO, vergelijking ERP bouw](https://univo.be/blog/beste-erp-software-bouw) (concurrent)
- [Taklo, vergelijking](https://taklo.nl/beste/software-voor-belgische-installatiebedrijven) (concurrent)
- [Enfin, facturatiesoftware](https://enfin.be/nl/blog/beste-facturatie-software-belgie) (concurrent)
- [Bouwsoft, prijspagina](https://www.bouwsoft.be/nl/prijs-visma-bouwsoft/prijs-voor-bouwprofessionals) (leverancier)
- [Bouwsoft, voor bouwprofessionals](https://www.bouwsoft.be/nl/voor-wie/voor-bouwprofessionals) (leverancier)
- [Visma.be, Visma Bouwsoft](https://www.visma.be/onze-bedrijven/visma-bouwsoft)
- [Dutch IT Channel, overname Bouwsoft](https://dutchitchannel.nl/677424/visma-koopt-belgische-useitgroup-bouwsoft.html)
- [Accountancy Vanmorgen, omzet Visma](https://www.accountancyvanmorgen.nl/2026/03/19/omzet-visma-boven-3-miljard-klantenbestand-explodeert/)
- [Nemko, ISO 27001-certificaat Visma](https://www.tripletex.no/wp-content/uploads/2025/03/Visma-iso-27001-2025.pdf)
- [Digital Construction World, nacalculatie Bouwsoft](https://www.digitalconstructionworld.be/visma-bouwsoft-duidelijk-zicht-op-winstgevendheid-door-nacalculatie/)
- [Buildbase](https://www.buildbase.be/erp-bouw) (leverancier)
- [Worktalia, C-PRO](https://www.worktalia.com/article.asp?article=317)
- [Codelines, bouwsoftware op maat](https://www.codelines.be/oplossingen/bouwsoftware-op-maat/)
- [Emerce, Pro4all neemt STA Software over](https://www.emerce.nl/wire/pro4all-neemt-sta-software-bouwt-verder-positie-toonaangevende-europese-leverancier-bouwsoftware)

### Wetgeving en betonpraktijk

- [Unizo, e-facturatie en Peppol](https://www.unizo.be/ondernemersgids/financieel/factuur/e-facturatie-correct-werken-met-peppol-en-je-digitale)
- [Practicali, boetes e-facturatie](https://www.practicali.be/blog/e-facturering-tolerantieperiode-eerste-drie-maanden-2026)
- [lookuptax, Peppol België](https://lookuptax.com/docs/einvoicing/peppol-einvoicing-belgium)
- [Banqup, compliance pulse België](https://www.banqup.com/nl-be/resources/compliance-pulse/belgie)
- [Comarch, e-reporting 2028](https://www.comarch.com/trade-and-services/data-management/legal-regulation-changes/belgium-confirms-2026-peppol-e-invoicing-mandate-with-2028-near-real-time-reporting-to-follow/)
- [OpenPeppol, tarieven](https://peppol.org/join/fees/)
- [Storecove, ISO-plicht voor toegangspunten](https://www.storecove.com/blog/en/peppol-standards-iso-certification)
- [socialsecurity.be, inhouding op factuur](https://www.socialsecurity.be/site_nl/employer/applics/30bis/general/invoice.htm)
- [Securex, inhoudingsplicht vanaf 1 januari 2026](https://www.securex.be/nl/lex4you/zelfstandige/rechten-plichten/hoofdberoep/plichten/inschrijving-in-de-kbo/de-inhoudingsplicht-in-de-bouw-en-schoonmaaksector-vanaf-1-01-2026)
- [Baker Tilly, nieuwe inhoudingsplicht vanaf 1 mei 2026](https://bakertilly.be/nl/news/nieuwe-inhoudingsplicht-vanaf-1-mei-2026/)
- [Jubel, inhoudingsplicht voor zelfstandigen](https://www.jubel.be/nieuwe-inhoudingsplicht-voor-zelfstandigen-in-de-bouw)
- [Forum for the Future, inhoudingsplicht](https://blog.forumforthefuture.be/nl/article/nieuwe-inhoudingsplicht-vanaf-1-mei-2026/31059)
- [Partena, inhoudingsplicht](https://www.partena-professional.be/nl/onze-inzichten/infoflashes/inhoudingsplicht-de-bouw-en-schoonmaaksector)
- [Unizo, werken met dienstverleners](https://www.unizo.be/ondernemersgids/bedrijfsvoering/samenwerken-met-zelfstandigen/werken-met-dienstverleners)
- [Schoups, stortklaar beton als werk in onroerende staat](https://legalnews.be/arbeid-sociale-zekerheid/leveren-van-stortklaar-beton-wordt-een-werk-in-onroerende-staat-schoups/)
- [Securex, aangifte van werken](https://www.securex.be/nl/lex4you/werkgever/themas/verplichtingen-werkgever/verplichtingen-in-bepaalde-sectoren/welke-werken-moeten-aangegeven-worden)
- [FOD WASO, drempel aanwezigheidsregistratie](https://werk.belgie.be/nl/news/aanwezigheidsregistratie-op-bouwplaatsen-verlaagd-drempelbedrag-vanaf-1-maart-2016)
- [Partena, Check In and Out at Work uitgesteld naar 1 april 2027](https://www.partena-professional.be/nl/onze-inzichten/infoflashes/check-and-out-work-voor-werken-onroerende-staat-uitgesteld-naar-1-april)
- [Lexgo, in- en uitchecken vanaf 2027](https://www.lexgo.be/nl/nieuws-en-publicaties/15016-actief-op-belgische-werven-vanaf-2027-wordt-in-en-uitchecken-verplicht)
- [Securex, tijdsregistratie vanaf 2027](https://www.securex.be/nl/lex4you/werkgever/nieuws/tijdsregistratie-vanaf-2027-waar-staan-we-vandaag)
- [socialsecurity.be, Checkinatwork: hoe](https://www.socialsecurity.be/site_nl/employer/applics/checkinatwork/general/how.htm)
- [socialsecurity.be, Checkinatwork (Engels)](https://www.socialsecurity.be/foreign/working_in_belgium/en/checkinatwork.html)
- [Accountable, btw-medecontractant](https://www.accountable.eu/nl-be/help-center/het-btw-medecontractantstelsel-in-belgie-wanneer-en-hoe-verlegging-van-heffing-van-toepassing-is-op-bouwwerken/)
- [KPMG, afschaffing btw-attest](https://kpmg.com/be/nl/home/insights/2022/02/kmo-renovatie-en-herstellingswerken-afschaffing-btw-attest.html)
- [Forum for the Future, formulieren 111](https://blog.forumforthefuture.be/nl/article/nieuwe-formulieren-111-voor-definitieve-regeling-afbraak-wederopbouw-beschikbaar/29146)
- [Belfius, betalingstermijnen overheidsopdrachten](https://www.belfius.be/common/NL/multimedia/MMDownloadableFile/Newsletters/BelfiusContact/MMDF%20Contact%208%20Markets.pdf)
- [MOW, catalogus prijsherzieningsformules 2.0](https://dienstverlening-mow.vlaanderen.be/system/files/2025-07/20251707_DV_catalogus_prijsherzieningsformules%20%282.0%29.pdf)
- [Credendo, betalingstermijnen vanaf 1 februari 2022](https://credendo.com/nl/knowledge-hub/aangepaste-betalingstermijnen-vanaf-1-februari-2022)
- [Bouwunie via Bouwinfo, Wet Breyne](https://www.bouwinfo.be/news/bouwen-en-verbouwen/wetgeving-en-premies/partner/b2b/bouwunie/de-wet-breyne-wat-moet-je-weten-als-aannemer)
- [Securex, weerverlet](https://www.securex.be/nl/lex4you/werkgever/nieuws/tijdelijke-werkloosheid-omwille-van-slecht-weer-vergeet-de-aangifte-niet)
- [Claeys & Engels, geolocatie](https://legalnews.be/arbeid-sociale-zekerheid/geolocalisatiesysteem-in-voertuigen-van-werknemers-gba-brengt-voorwaarden-in-herinnering-voor-legitiem-gebruik-claeys-engels/)
- [Securex, is geolokalisatie toegestaan](https://www.securex.be/nl/lex4you/werkgever/themas/verplichtingen-werkgever/gdpr-en-privacy/is-geolokalisatie-wettelijk-toegestaan)
- [Buildwise, specificatie van beton](https://www.buildwise.be/media/yjwl0ywi/folder_specificatie_van_beton_volgens_de_normen_nbn_en_206_en_nbn_b_15_001.pdf)
- [Buildwise, handleiding Coplaco](https://www.buildwise.be/media/5ghhgl1d/coplaco-handleiding.pdf)
- [Holcim, BENOR-fiche](https://www.holcim.be/sites/belgium/files/documents/fiche_technique_benor_beton_nl_lr.pdf)
- [Heidelberg Materials, algemene verkoopvoorwaarden beton](https://www.heidelbergmaterials-benelux.com/sites/default/files/2023-12/Algemene%20verkoopvoorwaarden_beton_belgi%C3%AB.pdf)
- [Heidelberg Materials, bijzondere voorwaarden 2023](https://www.heidelbergmaterials-benelux.com/sites/default/files/2023-12/bijzondere_voorwaarden_beton_belgi%C3%AB_2023.11.28%20.pdf)
- [Suivo, samenwerking met FedBeton](https://suivo.com/?p=5267)
- [AWV, catalogus Standaardbestek 250](https://wegenenverkeer.be/sites/default/files/uploads/documenten/Catalogus-4.1a.pdf)
- [VMSW, handleiding Bouwtechnisch Bestek Woningbouw](https://assets.vlaanderen.be/image/upload/v1678302305/Handleiding_BouwtechnischBestekWoningbouw_ve8she.pdf)

### Security en certificatie

- [CCB, CyFun 2025](https://ccb.belgium.be/news/cyfunr-2025-here)
- [CCB, presentatie Johan Klykens, 28 maart 2024](https://blog.cybersecuritycoalition.be/wp-content/uploads/Johan-Klykens_CCB_GRCBeConnected_28MAR2024final.pdf)
- [CCB, NIS2-wet](https://ccb.belgium.be/en/nis2)
- [Easy Cyber Protection, kost van verificatie](https://easycyberprotection-com.pages.dev/learn/cyberfundamentals/cab-audit-cost) (leverancier)
- [Easy Cyber Protection, wat is CyFun](https://easycyberprotection-com.pages.dev/learn/cyberfundamentals/what-is) (leverancier)
- [Easy Cyber Protection, toeleveringsketen](https://easycyberprotection-com.pages.dev/learn/nis2/supply-chain) (leverancier)
- [Hedylium, CyFun-niveaus](https://hedylium-site.pages.dev/en/articles/cyberfundamentals-niveaux)
- [Orbiq, kosten ISO 27001](https://www.orbiqhq.com/nl/compliance-automatisering/kosten-iso-27001-certificering) (leverancier)
- [Consilien, kost en doorlooptijd ISO 27001](https://consilien.com/news/iso-27001-certification-cost-timeline)
- [Auditfront, kost ISO 27001](https://auditfront.pages.dev/blog/iso-27001-certification-cost)
- [High Table, kost ISO 27001](https://hightable.io/iso-27001-certification-cost/)
- [cloudonaut, ISO 27001 met twee personen](https://cloudonaut.io/getting-iso-27001-certified-as-a-2-person-company/)
- [Advisera, implementatie met één persoon](https://community.advisera.com/topic/iso-27001-implementation-28/)
- [Advisera, control 5.3 functiescheiding](https://advisera.com/iso27001/control-5-3-segregation-of-duties/)
- [Brand Compliance, accreditaties](https://brandcompliance.com/en/certification-body/accreditations/)
- [KPMG Certification België](https://kpmg.com/be/en/services/kpmg-certification.html)
- [Bureau Veritas Benelux, ISO 27001](https://benelux.bureauveritas.com/en/iso-27001isms-information-security-certification)
- [soc2auditors, prijsvergelijking compliance-software](https://soc2auditors.pages.dev/insights/soc-2-software-pricing-comparison/)
- [CISO Assistant, CyFun 2025](https://github.gg22.workers.dev/intuitem/ciso-assistant-community/discussions/3867)
- [Unizo, NIS2](https://www.unizo.be/ondernemersgids/bedrijfsvoering/digitalisering/it-cloud-security/nis-2)
- [Eubelius, Data Act](https://www.eubelius.com/en/news/the-eu-data-act-in-force-what-changes-on-12-september-2025)
- [Pinsent Masons, overstapregels Data Act](https://publications.pinsentmasons.com/vario-uk/euda-handbook/the-new-switching-regime)
- [DLA Piper, overstap- en opzegrechten Data Act](https://www.dlapiper.com/en-es/insights/publications/2025/07/understanding-switching-termination-rights-under-the-data-act)
- [DLA Piper, Cyber Resilience Act en SaaS](https://www.dlapiper.com/en/insights/publications/2026/02/cyber-resilience-act-the-fine-line-between-saas-and-digital-products)
- [KSZ, beraadslaging 12/013](https://bcss.fgov.be/sites/default/files/assets/gegevensbescherming/beraadslagingen/12_013_n320.pdf)
- [DeepStrike, pentestprijzen België](https://deepstrike.io/blogs/penetration-testing-companies-belgium-2025) (leverancier)
- [OVHcloud, certificaten](https://docs.ovhcloud.com/en/guides/account-and-service-management/account-information/security-certifications)
- [Scaleway, security en compliance](https://www.scaleway.com/en/security-and-compliance/)
- [Qovery, Europese cloudplatformen](https://www.qovery.com/blog/top-eu-sovereign-cloud-platforms-migration-guide)
- [AWS, European Sovereign Cloud](https://aws.amazon.com/blogs/aws/opening-the-aws-european-sovereign-cloud)
- [VLAIO, kmo-portefeuille](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille)
- [VLAIO, cybersecurity-verbetertrajecten](https://vlaio.be/nl/subsidies-financiering/subsidiedatabank/cybersecurity-verbetertrajecten)
- [VLAIO, financiële steun verbetertrajecten](https://www.vlaio.be/nl/subsidies-financiering/cybersecurity-verbetertrajecten/welke-financiele-steun-kan-je-krijgen)
- [Forum for the Future, cyberveiligheid versterken](https://blog.forumforthefuture.be/nl/article/bij-wie-kan-je-terecht-om-je-cyberveiligheid-te-versterken/29210)
- [Partena, kmo-portefeuille vanaf februari 2026](https://www.partena-professional.be/nl/node/22320)

### Businessmodel en techniek

- [Unizo, bescherming van software](https://www.unizo.be/ondernemersgids/juridisch/intellectuele-eigendom/bescherming-van-software)
- [LexGO, bescherming van apps](https://www.lexgo.be/en/news-and-articles/1782-leidraad-bij-de-bescherming-van-apps)
- [K law, tips voor de opdrachtgever](https://legalnews.be/it-ip/softwareontwikkeling-enkele-tips-voor-de-klant-opdrachtgever-k-law/)
- [Jubel, aansprakelijkheid beperken in B2B](https://www.jubel.be/het-beperken-van-aansprakelijkheid-in-b2b-relaties/)
- [CMS, aansprakelijkheidsbeperking in België](https://cms.law/en/int/expert-guides/limitations-and-exclusions-of-liability-in-b2b-contracts/belgium)
- [LexGO, auteursrechtvergoeding voor software vanaf 2026](https://www.lexgo.be/nl/nieuws-en-publicaties/14992-auteursrechtvergoeding-voor-software-opnieuw-fiscaal-voordelig-vanaf-2026)
- [We Are Founders, klantverloop bij SaaS](https://www.wearefounders.uk/saas-churn-rates-and-customer-acquisition-costs-by-industry-2025-data/)
- [InfoQ, METR-studie](https://www.infoq.com/news/2025/07/ai-productivity)
- [NBER, working paper w35275](https://www.nber.org/system/files/working_papers/w35275/w35275.pdf)
- [Let's Data Science, samenvatting Harvard-studie](https://letsdatascience.com/news/harvard-study-finds-ai-coding-agents-raise-code-volume-not-o-ea78729b)
- [Aloa, een SaaS-MVP afbakenen](https://aloa.co/ai/resources/deep-dive/scope-a-saas-mvp)
- [openbankingtracker, Peppol-providers](https://openbankingtracker.com/peppol-providers)
- [Digiteal, prijzen](https://www.digiteal.eu/pricing/)
- [e-invoice.app, Billit](https://www.e-invoice.app/vendors/billit)
- [Rentman, Billit-integratie](https://rentman.io/integrations/billit)
- [Chift, connectoren](https://docs.chift.eu/unified-apis/accounting/connectors)
- [Informer, Ponto](https://www.informer.nl/ponto)
- [Mindee, factuurherkenning](https://mindee.com/l/invoice)
- [Clerk, kost van enterprise SSO](https://clerk.com/articles/the-real-cost-of-enterprise-sso-per-connection-vs-per-mau-pricing.md)
- [SSOJet, prijsvergelijking authenticatie](https://ssojet.com/blog/enterprise-authentication-pricing-2026)
- [Syncfusion, community-licentie](https://www.syncfusion.com/blogs/post/milestone-syncfusion-s-community-license)
- [Bryntum, OEM-prijzen](https://bryntum.com/oem-pricing/)
- [DHTMLX, Scheduler Commercial](https://dhtmlx.com/docs/products/dhtmlxScheduler/commercial)
- [PowerSync, vergelijking met ElectricSQL](https://powersync.com/blog/electricsql-vs-powersync) (leverancier)
- [Odoo, e-facturatie België](https://www.odoo.com/electronic-invoicing/belgium)
- [Odoo, prijzen België](https://www.odoo.com/nl_BE/pricing)
- [Frappe forum, licentie van maatwerk](https://discuss.frappe.io/t/licensing-of-app-made-using-frappe-erpnext/9836)
- [VLAIO, ontwikkelingsproject](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/ontwikkelingsproject-subsidie-voor-innovatie)
- [VLAIO, nieuw proces 2027](https://www.vlaio.be/nl/subsidies-financiering/ontwikkelingsproject/aanvraag-en-evaluatieprocedure/nieuw-proces-onderzoeks-en-ontwikkelingsprojecten-2027)
- [VLAIO, kmo-groeisubsidie](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/kmo-groeisubsidie-strategisch-adviesaanwerving-bij-groeitraject)
- [VLAIO, kmo-portefeuille digitalisering](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille/wat-is-de-kmo-portefeuille/digitalisering)
- [VLAIO, innovatieaftrek](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/innovatieaftrek)
- [VLAIO, tax shelter voor startende ondernemingen](https://www.vlaio.be/nl/subsidies-financiering/subsidiedatabank/tax-shelter-voor-startende-ondernemingen)
