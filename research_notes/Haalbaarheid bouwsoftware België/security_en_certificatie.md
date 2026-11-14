# Security, privacy en certificatie voor een kleine Belgische B2B SaaS-vendor (bouwsoftware) — stand eind 2026

> **Methodologische noot (lees eerst).** In deze sessie werkte alleen web*search*; het rechtstreeks ophalen van pagina's (o.a. `www.vlaio.be`, `easycyberprotection-com.pages.dev`) was geblokkeerd door de netwerkinstellingen. Alle "Cited Findings" steunen dus op zoekresultaat-samenvattingen van de vermelde URL's, niet op volledig gelezen brondocumenten. Primaire teksten (CCB NIS2-FAQ, wet Rijksregister art. 8, ISO 27006-auditdagtabel, BELAC-lijst, prijspagina's) zijn **niet** integraal geverifieerd. Punten die uit algemene achtergrondkennis komen staan uitdrukkelijk onder "Inferences" of "Gaps" en zijn als zodanig gelabeld. Veel prijsbronnen zijn vendor-/consultancyblogs (verkopers van de dienst) en in USD/GBP, niet Belgisch.

---

## 1. ISO/IEC 27001:2022 — vereisten, proces, Belgische certificatie-instellingen, kost en duur voor een micro-onderneming, haalbaarheid voor één persoon

### Takeaway
ISO 27001 is haalbaar voor een bedrijf van 1-5 personen (er zijn gedocumenteerde gevallen van 2-persoonsbedrijven), maar kost realistisch een vijfcijferig bedrag in jaar 1 plus blijvende jaarlijkse kosten, en de grootste kost is interne tijd. Er is geen betrouwbare Belgische prijslijst gevonden: alle bedragen zijn generieke/vendor-schattingen en moeten via 2-3 offertes bij geaccrediteerde instellingen worden bevestigd.

### Cited Findings
- Cyclus: stage 1 en stage 2 zijn verplicht; certificaat is 3 jaar geldig met jaarlijkse surveillance-audits; clausule 9.2 vereist minstens één interne audit vóór de certificatie-audit — [Orbiq (vendor)](https://www.orbiqhq.com/nl/compliance-automatisering/kosten-iso-27001-certificering)
- Auditkost wordt berekend op basis van auditdagen, die afhangen van het aantal medewerkers in de ISMS-scope; de dagentabel staat in de accreditatienorm ISO 27006 — [DEKRA NL](https://www.dekra.nl/en/iso-27001-certification-costs/)
- "Grootste hefboom: scopedefinitie — een smalle scope verlaagt auditdagen en implementatieduur drastisch" (vendor-claim) — [Orbiq](https://www.orbiqhq.com/nl/compliance-automatisering/kosten-iso-27001-certificering)
- Auditdagtarief gemiddeld ca. $1.500/dag in 2026; een bedrijf met 1-10 medewerkers heeft typisch ca. 5 auditdagen nodig, dus ca. $7.800 voor de audit zelf (generieke, niet-Belgische schatting) — [Auditfront](https://auditfront.pages.dev/blog/iso-27001-certification-cost)
- UK-anker: externe auditkost voor 1-10 medewerkers ca. £6.250; surveillance ca. 1/3 van de initiële auditkost, hercertificatie om de 3 jaar — [High Table (UK-consultant)](https://hightable.io/iso-27001-certification-cost/)
- Totale kost jaar 1 voor een kleine organisatie: $15.000-$50.000 volgens één gids; $8.000-$30.000 volgens een andere; onderhoud $10.000-$25.000/jaar (alle vendor/consultant-schattingen, USD) — [Consilien](https://consilien.com/news/iso-27001-certification-cost-timeline); [Auditfront](https://auditfront.pages.dev/blog/iso-27001-certification-cost)
- Europese vendor-schattingen (gericht op middelgrote bedrijven, dus bovengrens voor een micro): audit €8.000-€25.000 initieel; totaal jaar 1 €20.000-€80.000; doorlopend €8.000-€25.000/jaar voor surveillance + software — [Orbiq](https://www.orbiqhq.com/nl/compliance-automatisering/kosten-iso-27001-certificering); zie ook [heyData](https://heydata.eu/en/magazine/iso-27001-costs-2026-certification-sme) en [Proliance](https://www.proliance.ai/en/blog/iso-27001-costs-2026-what-certification-really-costs) (niet gelezen, enkel als lead)
- Interne audit door een onafhankelijke consultant: $5.000-$15.000 voor kmo's (generieke schatting) — [Scytale](https://scytale.ai/resources/iso-27001-certification-costs/)
- Doorlooptijd: 6-10 maanden voor de meeste bedrijven, realistisch bereik 3-12 maanden afhankelijk van scope en maturiteit — [Consilien](https://consilien.com/news/iso-27001-certification-cost-timeline)
- "De grootste kostenfactor is mogelijk niet de audit maar de tijd van interne teams" — [Factorial](https://factorialhr.com/blog/how-much-does-iso-27001-certification-cost/)
- **Belgische certificatie-instellingen (BELAC):** Brand Compliance België meldt BELAC-accreditatie voor ISO 27001 (sept. 2025) en was op 4 sept. 2025 de eerste instelling met BELAC-accreditatie voor CyberFundamentals — [Brand Compliance accreditaties](https://brandcompliance.com/en/certification-body/accreditations/); [Brand Compliance nieuws](https://brandcompliance.com/en/?p=26563)
- KPMG Certification BV is door BELAC geaccrediteerd (nr. 615-QMS) voor ISO 27001 — [KPMG België](https://kpmg.com/be/en/services/kpmg-certification.html)
- Bureau Veritas Benelux biedt ISO 27001 aan onder o.a. BELAC-accreditatie — [Bureau Veritas Benelux](https://benelux.bureauveritas.com/en/iso-27001isms-information-security-certification)
- BELAC-document 2-405-ISMS bevat de specifieke accreditatiebepalingen voor ISMS-certificatie-instellingen, herzien in 2023 voor ISO/IEC 27001:2022 — [FOD Economie / BELAC 2-4xx](https://economie.fgov.be/en/publicaties/series-belac-2-4xx-guidelines)
- Vinçotte biedt CyFun-diensten aan (ISO 27001-accreditatie niet bevestigd in deze zoektocht) — [Vinçotte CyFun](https://www.vincotte.be/en/pages/cyfun-cyberfundamentals)
- **Compliance-automatisering (allemaal offerte-gebaseerd; bedragen uit derde-partij-blogs, USD):**
  - Vanta: start ca. $10.000-$12.000/jaar; bereik $10.000-$30.000/jaar (maart 2026); ISO 27001 als add-on ca. $5.000-$15.000 — [soc2auditors](https://soc2auditors.pages.dev/insights/soc-2-software-pricing-comparison/); [Compliance Stronghold](https://compliancestronghold.pages.dev/reviews/vanta)
  - Drata: start ca. $7.500/jaar + onboarding; extra framework ca. $1.500; Vendr-transactiedata: mediaan Drata Advanced $20.300 (bereik $16.600-$39.700, N=94) — [soc2auditors](https://soc2auditors.pages.dev/insights/soc-2-software-pricing-comparison/); [Costbench](https://costbench.com/compare/secureframe-vs-vanta/)
  - Secureframe: vanaf $7.500/jaar, tot >$80.000 voor grote multi-framework deployments — [Costbench](https://costbench.com/compare/secureframe-vs-vanta/)
  - Sprinto: doorgaans goedkoopst, start ca. $4.000-$8.000; prijs per framework — [soc2auditors](https://soc2auditors.pages.dev/insights/soc-2-software-pricing-comparison/)
  - Geen van deze vendors publiceert een tarief; alleen pakketnamen — [soc2auditors](https://soc2auditors.pages.dev/insights/soc-2-software-pricing-comparison/)
  - Drata ondersteunt CyberFundamentals (CyFun) als framework — [Drata](https://drata.com/updates/new-framework-support-cyberfundamentals-cyfun)
  - CISO Assistant (open source, intuitem) bevat het CyFun 2025-framework — [GitHub discussie](https://github.gg22.workers.dev/intuitem/ciso-assistant-community/discussions/3867)
- **Eén persoon / micro:** Advisera stelt dat implementatie met één persoon "perfectly feasible" is — [Advisera community](https://community.advisera.com/topic/iso-27001-implementation-28/)
- Gedocumenteerde case: softwarebedrijf van 2 personen behaalde ISO 27001 — [cloudonaut](https://cloudonaut.io/getting-iso-27001-certified-as-a-2-person-company/)
- Tegenstem: ISMS Copilot (tool-vendor) zegt zelf nog niet gecertificeerd te zijn omdat de norm organisatiestructuren met functiescheiding en onafhankelijk toezicht veronderstelt — [ISMS Copilot](https://ismscopilot.hc.ferndesk.com/why-we-re-not-iso-27001-certified-yet-64bat)
- Annex A 5.3 (segregation of duties): conflicterende taken scheiden zodat één persoon niet dezelfde activiteit uitvoert én controleert; waar scheiding onpraktisch is, zijn compenserende maatregelen toegelaten (logreview, goedkeuring door tweede partij) — [Advisera 5.3](https://advisera.com/iso27001/control-5-3-segregation-of-duties/); [ISMS.online 5.3](https://www.isms.online/iso-27001/annex-a-2022/5-3-segregation-of-duties-2022/)

### Inferences
- Voor een micro-vendor (1-5 p.) met smalle scope lijkt een realistische orde van grootte: externe audit jaar 1 ca. €6.000-€12.000 (ca. 5 auditdagen à ca. €1.200-€1.800 + reiskost/rapportage), surveillance ca. €2.500-€4.500/jaar, plus tooling €4.000-€12.000/jaar en eventueel consultant/interne auditor €5.000-€15.000. Totaal jaar 1 grofweg €15.000-€40.000 cash, exclusief 20-40 werkdagen eigen tijd. **Dit is een eigen afleiding uit bovenstaande niet-Belgische schattingen, geen geciteerd cijfer.**
- Een eenmanszaak kan technisch gecertificeerd worden, maar interne-auditonafhankelijkheid (clausule 9.2) vereist in de praktijk een externe interne auditor, en functiescheiding moet via gedocumenteerde compenserende maatregelen. Met 2+ personen (bv. wederzijdse code review, gescheiden deploy-goedkeuring) wordt dit merkbaar eenvoudiger. De certificatie-instelling beslist; vooraf aftoetsen.
- Vanta/Drata zijn voor een Belgische micro-SaaS zonder Amerikaanse klanten waarschijnlijk te duur t.o.v. het nut; goedkopere of open-source opties (CISO Assistant, Sprinto, Scytale, Brainframe) of gewoon gestructureerde documenten zijn te overwegen.
- Achtergrondkennis (niet geverifieerd in deze sessie): ISO/IEC 27001:2022 bestaat uit clausules 4-10 (context, leiderschap, planning/risicobeoordeling, ondersteuning, uitvoering, evaluatie incl. interne audit en directiebeoordeling, verbetering) en Annex A met 93 controls in 4 thema's (organisatorisch 37, mensen 8, fysiek 14, technologisch 34), met een verplichte Statement of Applicability.

### Gaps
- Geen Belgische dagtarieven of offertebedragen van BELAC-geaccrediteerde instellingen gevonden; geen bevestiging van BELAC-accreditatie ISO 27001 voor BSI, DNV, Kiwa, DQS, Vinçotte (velen werken onder buitenlandse accreditatie zoals RvA/UKAS/DAkkS, wat via EA-MLA evenwaardig is — achtergrondkennis, niet geverifieerd). De officiële BELAC-zoekmachine moet geraadpleegd worden.
- Exacte ISO 27006-auditdagtabel voor 1-10 personen niet geverifieerd.
- Geen prijzen gevonden voor Scytale en Brainframe (Luxemburgs/Belgisch georiënteerde GRC-tool).
- Structuur van de norm (93 controls enz.) niet uit een primaire bron bevestigd in deze sessie.

---

## 2. Alternatieven en opstapjes: CyberFundamentals (CyFun), SOC 2, ISO 27701/27017/27018, cloudcertificaten, pentestrapporten, vragenlijsten — en wat Belgische bouwbedrijven vragen

### Takeaway
CyFun (CCB) is de logische, veel goedkopere Belgische opstap: het framework en de zelfevaluatie zijn gratis, Basic/Important worden *geverifieerd* (niet gecertificeerd) door een geaccrediteerde instelling, en het CCB raadt CyFun Basic aan als minimum voor leveranciers van NIS2-entiteiten. Wat bouwbedrijven concreet aan softwareleveranciers vragen, kon niet met bronnen worden onderbouwd.

### Cited Findings
- Niveaus: Small is het instapniveau; Basic, Important en Essential zijn drie assurance-niveaus — [CCB Cyberguide](https://cyberguide.ccb.belgium.be)
- CyFun 2025 is uitgelijnd op NIST CSF 2.0 en NIS2 — [CCB nieuws "CyFun 2025 is here"](https://ccb.belgium.be/news/cyfunr-2025-here)
- Basic en Important: verificatie van de zelfevaluatie; Essential: certificatie-audit — [CCB-presentatie Johan Klykens, 28 mrt 2024](https://blog.cybersecuritycoalition.be/wp-content/uploads/Johan-Klykens_CCB_GRCBeConnected_28MAR2024final.pdf)
- Dezelfde CCB-presentatie noemt een ruwe orde van grootte van ca. €1.000/jaar voor de beperkte conformiteitsbeoordeling van Basic en Important (cijfer uit 2024, mogelijk verouderd) — [CCB-presentatie](https://blog.cybersecuritycoalition.be/wp-content/uploads/Johan-Klykens_CCB_GRCBeConnected_28MAR2024final.pdf)
- Framework, Excel-werkboek, scoringsrubriek en Safeonweb@work-portaal zijn gratis; er bestaan geen gepubliceerde prijslijsten van CAB's (vendor-samenvatting) — [Easy Cyber Protection](https://easycyberprotection-com.pages.dev/learn/cyberfundamentals/cab-audit-cost)
- Aantal controls per niveau is **tegenstrijdig** in secundaire bronnen: Small 7 of 8; Basic 34 (meest consistent; één bron zegt 25); Important 117 of 132; Essential 140 of 217 — [Easy Cyber Protection](https://easycyberprotection-com.pages.dev/learn/cyberfundamentals/what-is); [osix blog](https://osix-site.statichost.eu/blog/security/20250424/cyberfundamentals.html); [Hedylium](https://hedylium-site.pages.dev/en/articles/cyberfundamentals-niveaux)
- Voor Basic en Important dient het bedrijf zijn zelfevaluatie in bij een verificatie-instelling, die de verificatie-assurance afgeeft — [osix blog](https://osix-site.statichost.eu/blog/security/20250424/cyberfundamentals.html)
- Het CCB adviseert dat elke organisatie die deel kan uitmaken van de toeleveringsketen van een NIS2-entiteit minstens niveau Basic haalt (aanbeveling, geen wettelijke plicht voor de leverancier; via vendor-blogs die het CCB citeren) — [Easy Cyber Protection – supply chain](https://easycyberprotection-com.pages.dev/learn/nis2/supply-chain)
- Zowel CyFun als ISO 27001 worden door het CCB aanvaard voor NIS2-conformiteit; de ISO-route vereist een Statement of Applicability — [Easy Cyber Protection – certification](https://easycyberprotection-com.pages.dev/learn/nis2/certification); zie ook [Brand Compliance – NIS2 & CyFun](https://brandcompliance.com/en/?p=20668)
- Tijdlijn NIS2-entiteiten: Basic of Important bereikt tegen 18 april 2026; vereist niveau gecertificeerd/geverifieerd tegen 18 april 2027 — [Hedylium](https://hedylium-site.pages.dev/en/articles/cyberfundamentals-niveaux)
- Brand Compliance en Vinçotte bieden CyFun-verificatie/-certificatie aan — [Brand Compliance CyFun](https://brandcompliance.com/docs/cyberfundamentals/); [Vinçotte](https://www.vincotte.be/en/pages/cyfun-cyberfundamentals)
- Ierland (NCSC) heeft CyFun overgenomen, wat wijst op bredere EU-erkenning — [NCSC Ireland CyFun FAQ](https://ncsc.gov.ie/CyFun/CyFunFAQ)
- Voorbeeld van een SaaS-vendor die "CyFun Basic" in zijn trust center toont — [NextSDS trust center](https://trust-center.nextsds.com/docs/cyfun-basic)

### Inferences
- Aanbevolen pad voor een micro-vendor: (1) vanaf dag 1 bouwen volgens CyFun Basic + zelfevaluatie (gratis); (2) bij eerste betalende klanten CyFun Basic laten verifiëren (lage vierhonderd tot enkele duizenden euro's — exacte prijs op te vragen), gesubsidieerd via VLAIO; (3) ISO 27001 pas wanneer een concrete klant (grote aannemer, overheid, NIS2-entiteit) het contractueel eist of het een dealblocker wordt. CyFun Important overlapt sterk met ISO 27001 Annex A, dus het werk is herbruikbaar.
- SOC 2 is een Amerikaans attestatiekader (AICPA); voor een vendor met uitsluitend Belgische bouwklanten is het naar verwachting weinig relevant. ISO 27701 (privacy-extensie), 27017/27018 (cloud-controls/PII in cloud) zijn add-ons op een bestaand 27001-certificaat en dus geen startpunt. (Achtergrondkennis, niet met bronnen onderbouwd in deze sessie.)
- De certificaten van de cloudprovider (ISO 27001, SOC 2 enz.) dekken alleen de infrastructuurlaag; ze zijn nuttig bewijs in vragenlijsten maar vervangen geen eigen maatregelen op applicatieniveau (shared responsibility). (Achtergrondkennis.)
- Een "trust page" met: hosting-locatie + providercertificaten, CyFun-zelfevaluatie/verificatie, recent pentest-samenvattingsrapport, verwerkersovereenkomst, subverwerkerslijst en back-up/RPO/RTO-verklaring beantwoordt vermoedelijk 90% van de vragen van kmo-aannemers.

### Gaps
- **Geen bronnen gevonden** over wat Belgische bouw-kmo's en grote algemene aannemers (bv. BESIX, Jan De Nul, DEME, Willemen, Democo) feitelijk eisen van softwareleveranciers (vragenlijsten, ISO 27001-eis, CyFun-eis). Dit vereist interviews met klanten of inkoopdocumenten. Verwachting uit achtergrondkennis: kleine aannemers vragen vrijwel niets formeels behalve GDPR-verwerkersovereenkomst; grote groepen sturen IT-security-vragenlijsten en vragen steeds vaker ISO 27001 of CyFun.
- Officiële CCB-controlaantallen per CyFun-niveau en actuele CAB-prijzen niet geverifieerd (ccb.belgium.be / atwork.safeonweb.be raadplegen).
- Geen Belgische equivalent van het Britse "Cyber Essentials"-label gevonden anders dan CyFun Small/Basic zelf.
- Relevantie SOC 2 in België, ISO 27701, 27017/27018: geen bronnen opgehaald.

---

## 3. NIS2 in België (wet van 26 april 2024), CRA, DORA, Data Act, AI Act

### Takeaway
Een micro-SaaS-vendor en doorsnee bouwbedrijven vallen zeer waarschijnlijk niet rechtstreeks onder NIS2, maar worden indirect geraakt via leverancierseisen van NIS2-klanten. De EU Data Act (cloud-switching, hoofdstuk VI) geldt daarentegen wél voor SaaS, zonder kmo-uitzondering, sinds 12 september 2025; zuivere SaaS valt in principe buiten de Cyber Resilience Act.

### Cited Findings
- De wet van 26 april 2024 trad in werking op 18 oktober 2024; betrokken ondernemingen moesten zich in de meeste gevallen uiterlijk 18 maart 2025 bij het CCB registreren — [Unizo](https://www.unizo.be/ondernemersgids/bedrijfsvoering/digitalisering/it-cloud-security/nis-2)
- De wet geldt (op uitzonderingen na) voor organisaties van een bepaalde omvang die in België gevestigd zijn en een dienst uit de bijlagen I/II verlenen; sommige entiteiten vallen eronder ongeacht omvang — [CCB NIS2-FAQ NL](https://ccb.belgium.be/sites/default/files/NIS2%20FAQ%20Website%20v1.0%20NL.pdf); [Unizo](https://www.unizo.be/ondernemersgids/bedrijfsvoering/digitalisering/it-cloud-security/nis-2)
- Omvangscriteria volgen Aanbeveling 2003/361/EG; het is irrelevant of de in-scope dienst een hoofd- of nevenactiviteit is — [Loyens & Loeff / Chambers Cybersecurity 2026 België](https://www.loyensloeff.com/chambers_cyber-security-2026_004_belgium-td.pdf)
- "ICT service management (B2B)" (managed service providers) en digitale infrastructuur staan in bijlage I (hoog-kritieke sectoren) — [CCB – NIS2-wet](https://ccb.belgium.be/en/nis2); [CCB NIS-2 Scope v2](https://ccb.belgium.be/sites/default/files/nis2/NIS-2%20Scope%20v2.pdf)
- Het CCB publiceert een FAQ (v2.1, januari 2026) met o.a. een sectie over de toeleveringsketen (3.8) — [CCB FAQ EN](https://ccb.belgium.be/sites/default/files/NIS2%20FAQ%20Website%20v1.0%20EN.pdf)
- Ondernemingen die niet rechtstreeks onder de wet vallen, kunnen geraakt worden via klanten die beveiligingseisen aan leveranciers opleggen — [Unizo](https://www.unizo.be/ondernemersgids/bedrijfsvoering/digitalisering/it-cloud-security/nis-2)
- De NIS2-drempels (50 werknemers / €10 mln) gelden alleen voor rechtstreekse regulering, niet voor supply-chain-verplichtingen (vendor-claim, niet bevestigd tegen CCB-FAQ) — [Easy Cyber Protection](https://easycyberprotection-com.pages.dev/learn/nis2/supply-chain)
- **CRA:** SaaS valt niet onder de CRA tenzij het kwalificeert als "remote data processing solution" die noodzakelijk is voor de werking van een product met digitale elementen en door (of onder verantwoordelijkheid van) de fabrikant is ontwikkeld; NIS2 kan in sommige gevallen wel gelden — [Pillsbury](https://pillsburylaw.com/en/news-and-insights/eu-cyber-resilience-act-requirements-products-software.html); [DLA Piper, feb. 2026](https://www.dlapiper.com/en/insights/publications/2026/02/cyber-resilience-act-the-fine-line-between-saas-and-digital-products)
- Een ontwerp-richtsnoer van de Commissie (maart 2026) introduceert een drie-vragen-test voor remote data processing solutions (nog ontwerp) — [cyberresilienceact.eu FAQ (onafhankelijke gids)](https://www.cyberresilienceact.eu/faq.html); zie ook [DIGITALEUROPE](https://www.digitaleurope.org/resources/towards-clear-guidance-for-remote-data-processing-solutions-under-the-cra/)
- **Data Act:** van toepassing sinds 12 september 2025; SaaS is een "data processing service" met switching-verplichtingen; opzegtermijn voor switching max. 2 maanden — [Bird & Bird](https://www.twobirds.com/da/insights/2025/the-data-act-what-mandatory-switching-rights-mean-for-fixed-term-saas-models); [Eubelius](https://www.eubelius.com/en/news/the-eu-data-act-in-force-what-changes-on-12-september-2025)
- Hoofdstuk VI (switching/portabiliteit) bevat — anders dan andere hoofdstukken — geen uitzondering voor kmo-aanbieders — [Pinsent Masons](https://publications.pinsentmasons.com/vario-uk/euda-handbook/the-new-switching-regime)
- Switching-kosten mogen tot 11 januari 2027 nog worden aangerekend, beperkt tot rechtstreekse kosten; vanaf 12 januari 2027 verboden — [DLA Piper, juli 2025](https://www.dlapiper.com/en-es/insights/publications/2025/07/understanding-switching-termination-rights-under-the-data-act)
- Vroegtijdige-beëindigingsvergoedingen zijn geen "switching charges"; proportionele vergoedingen blijven mogelijk toelaatbaar, maar de tekst is onduidelijk — [Bird & Bird](https://www.twobirds.com/da/insights/2025/the-data-act-what-mandatory-switching-rights-mean-for-fixed-term-saas-models); [Schjødt](https://schjodt.com/news/data-act-impact-on-saas-business-models-and-contracts)
- Het Digital Omnibus-voorstel kan delen van het regime nog wijzigen — [Addleshaw Goddard, okt. 2025](https://www.addleshawgoddard.com/link/ace41335d6b44236a4c2f0338329e15b.aspx)

### Inferences
- Bouw (NACE F) staat niet in bijlage I of II van NIS2 (achtergrondkennis; niet bevestigd door de opgehaalde bronnen). Een bouwbedrijf kan wel in scope komen via een nevenactiviteit die wél gelijst is (bv. energieproductie, afvalbeheer, productie van bepaalde goederen) — de DLA Piper/Eversheds-artikelen over "self-generated power" illustreren dat risico ([Eversheds](https://www.eversheds-sutherland.com/en/global/insights/nis2-in-belgium)). Grote bouwgroepen met zulke activiteiten zullen dus leverancierseisen doorschuiven.
- Een SaaS-vendor van 1-5 personen valt als micro-onderneming onder de size-cap. Aandachtspunt: als de vendor zich als "cloud computing service provider" of "managed service provider" kwalificeert, wordt hij in scope zodra hij middelgroot wordt (≥50 VTE of >€10 mln omzet/balans). Niet relevant voor de MVP-fase, wel voor groeiplanning.
- DORA geldt alleen voor financiële entiteiten en hun kritieke ICT-dienstverleners; niet relevant tenzij banken/verzekeraars klant worden (achtergrondkennis).
- Data Act-implicaties voor de MVP: exportfunctie in gangbaar machineleesbaar formaat voor alle klantdata, contractclausules over switching (max. 2 maanden opzeg, overgangsperiode ca. 30 dagen — de 30 dagen is achtergrondkennis), geen exit-fees vanaf 12/01/2027, en een online register met datastructuren/exportformaten. Meerjarige contracten met lock-in zijn juridisch kwetsbaar.
- AI Act: als AI-functies worden toegevoegd (bv. offerte-generatie, planning-suggesties) is dat doorgaans beperkt/minimaal risico met transparantieplichten; AI die werknemers beoordeelt, taken toewijst op basis van gedrag of prestaties monitort valt onder hoog-risico (bijlage III, tewerkstelling) — te vermijden in een MVP. (Achtergrondkennis; geen bronnen opgehaald in deze sessie.)

### Gaps
- De inhoud van CCB-FAQ sectie 3.8 (supply chain) en de precieze definitie/size-regels voor cloud/MSP/SaaS zijn niet gelezen. Te verifiëren in [CCB FAQ](https://ccb.belgium.be/sites/default/files/NIS2%20FAQ%20Website%20v1.0%20EN.pdf) (v2.1, jan. 2026).
- Geen bron die uitdrukkelijk bevestigt dat bouw niet in de NIS2-bijlagen staat.
- AI Act en DORA: geen bronnen opgehaald; tijdlijn van AI Act-verplichtingen (incl. mogelijke uitstel via Digital Omnibus) niet geverifieerd.

---

## 4. GDPR voor dit product: verwerker, werknemersdata, rijksregisternummer/INSZ, geolocatie en tijdsregistratie, DPIA, GBA

### Takeaway
De vendor is verwerker (art. 28) voor de aannemer-verwerkingsverantwoordelijke; de twee gevoeligste punten zijn het rijksregisternummer/INSZ (in België sterk gereguleerd, gebruik vereist een wettelijke grondslag of machtiging) en geolocatie/tijdsregistratie van werknemers, waarvoor de GBA proportionaliteit, transparantie en bij voorkeur een DPIA en een aan/uit-mogelijkheid verwacht.

### Cited Findings
- Het Belgische rijksregisternummer is sterk gereguleerd en kan slechts met voorafgaande machtiging worden gebruikt (ouder Belspo-onderzoek; regels gewijzigd bij wet van 25 november 2018) — [Belspo studie](https://www.belspo.be/Belspo/organisation/Publ/pub_ostc/AP/rAP38_nl.pdf); [KSZ-beraadslaging 12/013](https://bcss.fgov.be/sites/default/files/assets/gegevensbescherming/beraadslagingen/12_013_n320.pdf)
- Toegang tot het Rijksregister zelf vereist een machtiging die steeds betrekking heeft op bepaalde gegevens en bepaalde doeleinden — [KSZ-beraadslaging 12/013](https://bcss.fgov.be/sites/default/files/assets/gegevensbescherming/beraadslagingen/12_013_n320.pdf)
- Checkinatwork: registratie gebeurt met eID, rijksregisternummer of Limosa-nummer; er bestaat een webservice-route voor eigen registratiesystemen/software, met een technische gebruiker en een simulatieomgeving — [socialsecurity.be – hoe](https://www.socialsecurity.be/site_nl/employer/applics/checkinatwork/general/how.htm); [socialsecurity.be – Checkinatwork](https://www.socialsecurity.be/site_nl/employer/applics/checkinatwork/index.htm); [Securex](https://www.securex.be/nl/lex4you/werkgever/themas/verplichtingen-werkgever/verplichtingen-in-bepaalde-sectoren/hoe-worden-de-aanwezigheden-geregistreerd)
- GBA-Geschillenkamer beslissing 62/2024 betreft beveiliging en gebruik van het rijksregisternummer in een online afsprakensysteem (uitkomst niet gelezen) — [GBA/APD beslissing 62/2024](https://www.AutoriteProtectionDonnees.be/publications/decision-quant-au-fond-n-62-2024.pdf)
- **Geolocatie:** GBA-Geschillenkamer (21 februari 2023) oordeelde dat een track-and-trace-systeem in een bedrijfsvoertuig de AVG schond omdat het permanent actief was en er onvoldoende transparantie was — [Claeys & Engels via Legalnews](https://legalnews.be/arbeid-sociale-zekerheid/geolocalisatiesysteem-in-voertuigen-van-werknemers-gba-brengt-voorwaarden-in-herinnering-voor-legitiem-gebruik-claeys-engels/); [Mondaq](https://www.mondaq.com/data-protection/1331462/geolocalisation-system-in-employees-vehicles-dpa-recalls-conditions-for-legitimate-use)
- Toestemming is geen geldige rechtsgrond voor het volgen van werknemers; gerechtvaardigd belang kan, mits proportionaliteit — [Securex](https://www.securex.be/nl/lex4you/werkgever/themas/verplichtingen-werkgever/gdpr-en-privacy/is-geolokalisatie-wettelijk-toegestaan)
- Louter vermelden van track & trace in het arbeidsreglement volstaat niet; een gedetailleerd geolokalisatiebeleid is aanbevolen; een handmatige aan/uit-schakelaar voor werknemers is volgens de GBA best practice — [Securex nieuws](https://www.securex.be/nl/lex4you/werkgever/nieuws/gebruik-je-een-track-trace-systeem-check-je-geolokalisatiebeleid); [Lexgo](https://www.lexgo.be/nl/nieuws-en-publicaties/14141-geolocalisatie-van-bedrijfswagens-bevestiging-van-de-principes-van-de-belgische-gegevensbeschermingsautoriteit)
- Controle op taakuitvoering moet gericht zijn en gerechtvaardigd door aanwijzingen van misbruik; een DPIA is sterk aanbevolen bij geolocatie met werknemersmonitoring; pseudonimisering (voertuig-ID i.p.v. naam) is good practice — [Claeys & Engels via Legalnews](https://legalnews.be/arbeid-sociale-zekerheid/geolocalisatiesysteem-in-voertuigen-van-werknemers-gba-brengt-voorwaarden-in-herinnering-voor-legitiem-gebruik-claeys-engels/)
- Vakbondsbrochure over geomonitoring (spelregels) bestaat — relevant voor sociaal overleg bij klanten — [ABVV](https://abvv.be/sites/default/files/2024-04/Geomonitoring-%20de%20spelregels.pdf)
- GBA-handhaving in arbeidscontext: op 12 mei 2026 twee boetes van samen €176.946,61 wegens het niet afsluiten van de mailbox van een vertrokken werknemer — [Everest via Legalnews](https://legalnews.be/privacy-gegevensbescherming/gdpr-op-de-werkvloer-wat-moet-een-werkgever-vandaag-op-orde-hebben-everest/)
- De werkgever blijft als verwerkingsverantwoordelijke aansprakelijk voor onrechtmatige raadpleging door een eigen werknemer — [Claeys & Engels via Legalnews](https://legalnews.be/arbeid-sociale-zekerheid/opgepast-u-als-werkgever-blijft-verantwoordelijk-voor-een-onrechtmatige-toegang-tot-persoonsgegevens-door-een-van-uw-werknemers-claeys-engels/)

### Inferences
- Ontwerpkeuzes voor de MVP rond INSZ: (a) INSZ alleen opslaan als de klant Checkinatwork-/Dimona-achtige koppelingen effectief gebruikt (de werkgever heeft daarvoor een wettelijke verplichting; de vendor handelt als verwerker op instructie); (b) veld-niveau-encryptie, gemaskeerde weergave (laatste cijfers), strikte rolgebaseerde toegang, logging van elke inzage; (c) INSZ nooit als primaire sleutel, in URL's, logs, exports of analytics; (d) nooit gebruiken voor andere doeleinden. Juridische validatie door een Belgische privacy-jurist is nodig vóór livegang.
- Geolocatie/tijdsregistratie: bouw privacy-by-design in — klokken met locatie-snapshot op het moment van in-/uitklokken i.p.v. continue tracking; configureerbare bewaartermijnen; aan/uit door werknemer; duidelijke in-app transparantietekst; een DPIA-template dat de klant kan hergebruiken. Dit is ook een verkoopargument.
- Als verwerker moet de vendor leveren: standaard verwerkersovereenkomst (art. 28), publieke subverwerkerslijst met notificatie bij wijziging, EU/EER-hosting, bijstand bij datalekken (melding aan klant "zonder onredelijke vertraging" zodat de klant de 72-uurstermijn van art. 33 haalt) en bij verzoeken van betrokkenen, verwijdering/teruggave bij einde contract. (Achtergrondkennis van de AVG; niet via bronnen in deze sessie.)
- Bewaartermijnen (achtergrondkennis, te verifiëren): sociale documenten/prestatiestaten doorgaans 5 jaar, boekhoudkundige stukken 7 jaar (10 jaar voor bepaalde stukken sinds recente wijzigingen); de software moet per datacategorie instelbare retentie ondersteunen.

### Gaps
- **Kernpunt niet geverifieerd:** de huidige tekst van art. 8 wet 8 augustus 1983 (zoals gewijzigd in 2018) en of een werkgever/verwerker het rijksregisternummer zonder afzonderlijke machtiging mag gebruiken wanneer een wet het gebruik oplegt (Checkinatwork, Dimona). Achtergrondkennis suggereert dat sinds de wet van 25 november 2018 geen machtiging nodig is wanneer het gebruik bij of krachtens wet is voorgeschreven, maar dit is hier niet met een bron bevestigd. Raadpleeg de geconsolideerde wettekst en ibz.rrn.fgov.be.
- Geen GBA-richtsnoer specifiek over tijdsregistratie-apps of over verwerkers van INSZ gevonden; uitkomst van GBA-beslissing 62/2024 en 61/2025 ([beslissing 61/2025](https://autoriteprotectiondonnees.be/publications/beslissing-ten-gronde-nr.-61-2025.pdf)) niet gelezen.
- De Belgische GBA-lijst van verwerkingen waarvoor een DPIA verplicht is, is niet opgehaald (bevat o.a. systematische monitoring van werknemers — achtergrondkennis).
- CAO 81 betreft controle op elektronische online-communicatie, niet GPS; toepasselijkheid op tijdsregistratie niet bevestigd.
- Geen overzicht van GBA-boetes aan SaaS-verwerkers gevonden.

---

## 5. Praktische secure-by-design baseline voor een multi-tenant SaaS-MVP (tenant-isolatie, authenticatie, pentest, verzekering)

### Takeaway
Voor authenticatie is kopen/hosten (managed IdP of open source) goedkoper en veiliger dan zelf bouwen; enterprise-SSO kost bij managed diensten ca. $100-$125 per connectie per maand. Een webapp-pentest in de EU kost ordegrootte €1.000-€1.800 per testdag; Belgische verzekeringspremies voor IT-BA/cyber zijn niet publiek gevonden.

### Cited Findings
- **Auth – WorkOS:** SSO ca. $125 per connectie/maand met volumekorting (tot ca. $65); AuthKit (user management) gratis tot 1 miljoen MAU — [SSOJet prijsvergelijking 2026](https://ssojet.com/blog/enterprise-authentication-pricing-2026); [WorkOS blog](https://workos.com/blog/enterprise-sso-providers-b2b-saas)
- **Auth0:** B2B Essentials vanaf ca. $150/maand, oplopend tot ca. $3.800/maand bij 20.000 MAU; extra enterprise-connecties ca. $100/maand; gratis tier 25.000 MAU (bronnen spreken elkaar tegen over het aantal inbegrepen connecties) — [SSOJet](https://ssojet.com/blog/enterprise-authentication-pricing-2026); [Deepak Gupta vergelijking](https://guptadeepak.com/ciam-compass/guides/workos-vs-auth0-vs-clerk/)
- **Clerk:** Pro-plan $25/maand; enterprise SSO per connectie met één connectie inbegrepen; gratis tier ca. 50.000 monthly retained users — [Clerk artikel](https://clerk.com/articles/the-real-cost-of-enterprise-sso-per-connection-vs-per-mau-pricing.md)
- Bij 10 SSO-connecties: lijstprijs ca. $1.250/maand (WorkOS) en ca. $1.300/maand (Auth0 B2B Professional) — [SSOJet](https://ssojet.com/blog/enterprise-authentication-pricing-2026)
- **Pentest:** grondige manuele pentesters in de EU rekenen ca. €1.000-€1.800 per dag (vendor-indicatie) — [DeepStrike België](https://deepstrike.io/blogs/penetration-testing-companies-belgium-2025)
- Amerikaanse benchmark: $8.900-$34.600 per webapplicatie-test; eenvoudige test ca. 3 dagen — [7ASecurity](https://7asecurity.com/blog/2025/11/web-app-pen-test-cost/)
- **Cyberverzekering:** Belgisch premievolume cyberpolissen 2025: €17,1 mln, stabiel t.o.v. 2024; premies dalen maar voorwaarden worden strenger; in 81% van de gevallen bleef de kost van een cyberincident in 2025 beperkt tot max. €20.000 — [ITdaily / Vanbreda 2026](https://itdaily.com/news/security/cybersecurity-verzekering-vanbreda-2026)
- Indicatieve kmo-premies van één aanbieder: ca. €35-€82 per maand afhankelijk van omzet en verzekerd bedrag (voorbeelden niet voor IT-bedrijven, ongedateerd) — [Xerius](https://www.xerius.be/nl-be/pensioen-verzekeringen/zaak/cyberverzekering)
- Premie hangt af van activiteit, omzet, aantal medewerkers, preventievoorwaarden, verzekerd bedrag en franchise — [KBC](https://www.kbc.be/ondernemen/nl/verzekeren/cybercriminaliteit.html)

### Inferences
(Onderstaande baseline is eigen synthese uit gangbare praktijk — OWASP ASVS, CyFun Basic, ISO 27001 Annex A — en **niet** via bronnen in deze sessie onderbouwd.)
- **Tenant-isolatie:** gedeelde database met `tenant_id` + PostgreSQL Row-Level Security als standaard (goedkoop, schaalbaar, één migratiepad), met tenant-context afgedwongen in de datalaag en geautomatiseerde cross-tenant-tests in CI. Schema- of database-per-tenant enkel als optie voor grote klanten die het eisen (hogere operationele kost). Object storage met tenant-prefix + gescheiden sleutels.
- **Authenticatie:** niet zelf bouwen. Opties: managed (Clerk/WorkOS/Auth0 — let op: Amerikaanse subverwerkers) of EU/self-hosted (Keycloak, Zitadel [Zwitsers, open source, cloud + self-host]) of Microsoft Entra ID als externe IdP voor klanten met Microsoft 365 (zeer gangbaar bij Belgische kmo's). Minimaal: OIDC, MFA (TOTP/passkeys) verplicht voor beheerders, "Sign in with Microsoft/Google", SSO pas per klant wanneer gevraagd. Voor werfarbeiders zonder bedrijfs-e-mail: passwordless (magic link/SMS/pincode + device binding) overwegen; itsme als Belgische optie.
- **Encryptie:** TLS 1.2+ overal, encryptie at rest (provider-managed KMS), extra veld-encryptie voor INSZ/IBAN. **Secrets:** geen secrets in repo; secret manager van cloudprovider; rotatie.
- **Back-ups/DR:** dagelijkse back-ups + point-in-time recovery, kopie in tweede EU-locatie/provider, kwartaalmatige hersteltest; publiceer doelen (bv. RPO ≤ 1-24 u, RTO ≤ 4-24 u) en maak ze contractueel niet strenger dan getest.
- **Logging/audit trail:** onveranderbaar applicatie-auditlog per tenant (wie-wat-wanneer, vooral facturen, loon-/prestatiegegevens, INSZ-inzage), gecentraliseerde security-logs met 6-12 maanden retentie.
- **Kwetsbaarheidsbeheer / SDLC:** Dependabot/Renovate, SCA + SBOM (bv. CycloneDX), SAST en secret scanning in CI, verplichte PR-review (ook als compenserende maatregel voor functiescheiding), aparte omgevingen, geen productiedata in test, MFA + hardware keys op cloud/GitHub-accounts, security.txt en responsible-disclosure-beleid.
- **Pentest:** eerste grey-box pentest vóór of kort na eerste betalende klanten; reken op 4-8 testdagen ≈ €5.000-€12.000 (afgeleid van het EU-dagtarief hierboven), daarna jaarlijks of bij grote wijzigingen; samenvattend rapport delen met klanten.
- **Incidentrespons:** schriftelijk IR-plan van 1-2 pagina's; als verwerker de klant "zonder onredelijke vertraging" verwittigen (contractueel vaak 24-48 u) zodat die binnen 72 u aan de GBA kan melden; contactlijst (CCB/CERT.be, verzekeraar, jurist).
- **Verzekering:** combineer BA beroepsaansprakelijkheid IT + cyber in één polis; verwachte ordegrootte voor een micro-IT-bedrijf enkele honderden tot enkele duizenden euro's per jaar — **onbevestigd**, offerte bij makelaar (bv. Vanbreda, Hiscox-distributeurs) nodig. Verzekeraars eisen doorgaans MFA, back-ups en patching — wat samenvalt met CyFun Basic.

### Gaps
- Geen Belgische prijzen voor pentests van Belgische aanbieders (bv. Toreon, NVISO, Secutec, Intigriti bug bounty) gevonden; het €1.000-€1.800 dagtarief komt van één vendor-blog.
- Geen Belgische premiecijfers voor beroepsaansprakelijkheid IT en cyber voor een micro-softwarebedrijf.
- Geen prijsinformatie voor Zitadel, Keycloak-hosting of Entra External ID opgehaald; Auth0-tierdetails tegenstrijdig tussen bronnen.
- De volledige technische baseline is expert-synthese zonder bronvermelding; aan te raden om te toetsen aan het officiële CyFun Basic-werkboek en OWASP ASVS.

---

## 6. EU-/Belgische (soevereine) hosting en certificaten

### Takeaway
Alle grote opties hebben ISO 27001; OVHcloud heeft het breedste Europese certificaatportfolio (incl. SecNumCloud, HDS, C5, SOC 2), Scaleway heeft ISO 27001 + HDS (SecNumCloud in voorbereiding), en de AWS European Sovereign Cloud (Brandenburg) is sinds januari 2026 beschikbaar. Voor Hetzner, Exoscale en vooral Belgische hosters (Combell, Nucleus) is de certificaatstatus in deze sessie niet sluitend bevestigd.

### Cited Findings
- AWS European Sovereign Cloud: eerste regio in Brandenburg (Duitsland), algemeen beschikbaar sinds 15 januari 2026 (oorspronkelijk gepland eind 2025); aparte partitie `aws-eusc`, regio `eusc-de-east-1` — [AWS News Blog](https://aws.amazon.com/blogs/aws/opening-the-aws-european-sovereign-cloud); [InfoQ jan. 2026](https://www.infoq.com/news/2026/01/aws-european-sovereign-cloud)
- AWS ESC ontving eerste compliance-attesten: SOC 2 en C5 Type 1-rapporten en zeven ISO-certificaten (incl. ISO 27001:2022) voor 69 diensten; Type 1 = ontwerp op één tijdstip — [heise](https://heise.de/-11210793)
- OVHcloud: ISO/IEC 27001:2022, ISO/IEC 27017:2015, SOC 2 Type 2; C5 — [OVHcloud docs – security certifications](https://docs.ovhcloud.com/en/guides/account-and-service-management/account-information/security-certifications); [OVHcloud C5](https://www.ovhcloud.com/asia/compliance/c5/)
- OVHcloud heeft SecNumCloud 3.2 en HDS (via aggregator) — [europe-alternatives](https://europe-alternatives.pages.dev/en/company/ovhcloud/)
- Scaleway: ISO 27001:2022 en HDS; SecNumCloud-kwalificatie is "strategische prioriteit" en nog in uitvoering — [Scaleway security & compliance](https://www.scaleway.com/en/security-and-compliance/)
- Exoscale: ISO 27001, SOC 2 Type II, C5 en HDS volgens één bron (vendor-stated volgens Qovery); geen SecNumCloud — [Qovery EU sovereign cloud guide](https://www.qovery.com/blog/top-eu-sovereign-cloud-platforms-migration-guide); [Cloud Landscape](https://cloudlandscape.github.io/en/providers/)
- Hetzner: ISO 27001; C5-status tegenstrijdig tussen bronnen (één zegt niet geverifieerd, één zegt C5-gecertificeerd) — [Qovery](https://www.qovery.com/blog/top-eu-sovereign-cloud-platforms-migration-guide); [Gart Solutions](https://gartsolutions.com/scaleway-vs-hetzner)

### Inferences
- Voor een Belgische bouw-SaaS zonder overheids-/zorgklanten is "EU-regio + ISO 27001 van de provider + verwerkersovereenkomst met provider" voldoende; SecNumCloud/HDS zijn Franse eisen (overheid/gezondheid) en geen vereiste. Soevereiniteit (geen blootstelling aan US CLOUD Act) is een commercieel argument, geen wettelijke plicht voor deze markt.
- Praktische keuze: (a) hyperscaler EU-regio (GCP `europe-west1` in Saint-Ghislain, België; AWS Frankfurt/Parijs/Ierland; Azure West Europe/Belgium Central) voor managed services en snelheid — regio-/datacenterlocaties zijn achtergrondkennis; of (b) Europese provider (Scaleway, OVHcloud, Hetzner, Exoscale) voor lagere kost en "100% Europees"-boodschap. Managed PostgreSQL + object storage + container-hosting volstaan.
- Ruwe kost voor een MVP met enkele tientallen klanten: ca. €50-€300/maand bij Hetzner/Scaleway/OVH, ca. €200-€800/maand bij een hyperscaler met managed database, HA en back-ups. **Eigen schatting, niet met bronnen onderbouwd.**

### Gaps
- Geen certificaatgegevens gevonden voor Combell/team.blue en Nucleus (Belgische hosters; achtergrondkennis zegt ISO 27001 voor beide, niet geverifieerd).
- Azure/GCP-regio's in België en hun certificaten niet via bronnen bevestigd in deze sessie.
- Geen actuele prijsvergelijking van hostingkosten opgehaald.
- Status Hetzner C5 en Exoscale-certificaten te verifiëren op de eigen compliance-pagina's; SecNumCloud-status via de ANSSI-catalogus.

---

## 7. Subsidies voor cybersecurity/certificatie in Vlaanderen

### Takeaway
Vlaanderen subsidieert cybersecurity nog steeds stevig in 2026: VLAIO-cybersecurity-verbetertrajecten aan 50% voor kmo's (pakketten START/MEDIUM/PLUS) en kmo-portefeuille aan 45% voor kleine ondernemingen specifiek voor cybersecurity-advies en -opleiding (plafond €7.500/jaar). Sinds 1 februari 2026 is cybersecurity het enige overblijvende adviesthema in de kmo-portefeuille.

### Cited Findings
- VLAIO subsidieert 50% van de kost van externe begeleiding in een cybersecurity-verbetertraject voor kmo's (ook maatwerkbedrijven en vzw's); 35% voor niet-kmo's die onder NIS2 vallen — [VLAIO – cybersecurity verbetertrajecten](https://vlaio.be/nl/subsidies-financiering/subsidiedatabank/cybersecurity-verbetertrajecten)
- Het programma loopt door in 2026 met drie pakketten START, MEDIUM en PLUS, elk 50% gesubsidieerd — [VLAIO nieuws 2026](https://www.vlaio.be/nl/nieuws/krijg-ook-2026-vlaio-steun-om-te-investeren-cyberveiligheid)
- Eigen bijdrage na subsidie: tussen €3.550 en €19.950 excl. btw volgens één VLAIO-pagina; tussen €4.600 en €17.500 excl. btw volgens een artikel uit 2026 (**tegenstrijdig** — actuele VLAIO-pagina controleren) — [VLAIO – welke financiële steun](https://www.vlaio.be/nl/subsidies-financiering/cybersecurity-verbetertrajecten/welke-financiele-steun-kan-je-krijgen); [Forum for the Future](https://blog.forumforthefuture.be/nl/article/bij-wie-kan-je-terecht-om-je-cyberveiligheid-te-versterken/29210)
- Kmo-portefeuille: vanaf 1 februari 2026 verdwijnt de dienst "advies", behalve adviesdiensten rond cybersecurity — [Partena Professional](https://www.partena-professional.be/nl/node/22320)
- Kmo-portefeuille cybersecurity (advies en opleiding bij geregistreerde dienstverleners): 45% voor kleine en 35% voor middelgrote ondernemingen; plafond €7.500 steun per jaar voor alle diensten samen — [VLAIO kmo-portefeuille](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille); [VLAIO – financiële steun cybersecurity](https://www.vlaio.be/nl/begeleiding-advies/digitalisering/cybersecurity/krijg-financiele-steun-om-te-investeren-de)
- Algemeen tarief kmo-portefeuille voor andere opleidingen: 30% (klein) / 20% (middelgroot) (oudere VLAIO-pagina's) — [VLAIO – wat is de kmo-portefeuille](https://www.vlaio.be/nl/subsidies-financiering/kmo-portefeuille/wat-is-de-kmo-portefeuille)

### Inferences
- Voor de vendor zelf: een consultant voor CyFun-/ISO 27001-voorbereiding of een pentest via een geregistreerde kmo-portefeuille-dienstverlener kan tot 45% gesubsidieerd worden (max. €7.500 steun/jaar → ca. €16.700 aan gefactureerde diensten). Of de certificatie-audit zelf (auditdagen van de certificatie-instelling) subsidiabel is, is niet bevestigd.
- Voor de *klanten* (bouw-kmo's): dezelfde steun is een verkoopargument — hun cybersecurity-traject kan de adoptie van veilige cloudsoftware omvatten.
- Het verbetertraject-minimum (eigen bijdrage ≥ ca. €3.550-€4.600) is voor een startende micro-vendor mogelijk te zwaar; de kmo-portefeuille is flexibeler voor kleine opdrachten.

### Gaps
- VLAIO-pagina's konden niet rechtstreeks gelezen worden (host geblokkeerd in deze sessie): exacte inhoud van START/MEDIUM/PLUS, koppeling met CyFun-niveaus, en of certificatie-/verificatiekosten zelf subsidiabel zijn, blijven te verifiëren op vlaio.be.
- Geen informatie opgehaald over equivalenten in Brussel (bv. Hub.brussels/Innoviris) en Wallonië (bv. chèques-entreprises cybersécurité / Keep It Secure) — bestaan volgens achtergrondkennis, niet geverifieerd.
- Of een pas opgerichte vennootschap zonder omzet meteen in aanmerking komt, is niet nagegaan.
