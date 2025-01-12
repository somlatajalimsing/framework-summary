# Goverance Framework HU
## 1 Samenvatting van het verhaal van Jannick - *Essentie*
Deze samenvatting behandeld de presentatie van Jannick, een Product Owner met ervaring in IT (Azure en deels AWS) en Product Management. 
### 1.1 Wat is cloud governance? 
Cloud Governance bestaat uit beleidsregeles die ervoor zorgen dat de risico's en compliancy van je organisatie in orde zijn en dat het bedrijf voldoet aan de regels en wetgevingen die hiervoor bedoeld zijn, iets waar er binnen de HU veel aandacht aan wordt besteed. Compliance kun je technisch (met technologie) en organisatorisch afdwingen. Educatie is ook een belangrijke factor. 
### 1.2 Infrastructuur
De infrastructuur van de HU bestaat uit 3 lagen welke beheerd worden door technisch applicatie en functioneel beheer. Dit is de applicatielaag , infralaag en coreplatform. Kostenworden worden gemonitord en gerapporteerd. 
### 1.3 Cloud Adoption Framework
Het Cloud Adoption Framework beschrijft:
- Hoe kan je een bepaalde strategie kan aanpakken?
- Hoe kan je een bepaalde processen inrichten?
- Hoe kan je het plannen en zorgen dat het operationeel blijft?
### 1.4 Best practises van Cloud Governance volgens Jannick
- Het opzetten van processen is cruciaal;
- ISO's volgen en CSIS om te kijken om alles voldoet aan de wensen;
- Microsoft Cloud Securtity Baseline geeft ook veel aanvullingen;
### 1.5 Netwerkbeveliging
`Stap 1`: Risico's identificeren en minimaliseren (haal dit uit de applicaties die gebruikt worden). Bij de HU is hiervoor bijvoorbeeld de Azure Marketplace dichtgezet, zodat 3e partijen anders bijbetrokken worden;
`Stap 2`: De HU gebruik een Azure Sandbox (niet in prd omgevingen) voor automatische student subscription beheer door het gebruik van service principles. Deze worden ingekocht bij een coöperatieve vereniging genaamd SURF; `Stap 3`: Gebruik maken van Multi-Factor Authentication;
`Stap 4`: Hiernaast wordt de manier "vetten van resource types" gebruikt door gebruik te maken van een speciale vault. Dit wordt gebruikt om keys, certificaten, wachtwoorden op te slaan;
`Stap 5`: Gebruik maken van Azure landing zones waar applicaties draaien (core laag). Dit "de" manier om governance in goede banen te leiden. 

## 2 Kritische reflectie - *Feedback en feedforward*

### 2.1 Hoe vind ik ervan hoe het op de HU is geregeld en wat vind ik goed?
Jannick's presentatie benadrukt de complexiteit, belang van Cloud Governance en de noodzaak hiervan binnen een organisatie/instelling zoals Hogeschool Utrecht.
Binnen de HU wordt er voldoende aandacht besteed aan Governance en Beveiliging. Er zijn er diverse maatregelen geïmplementeerd zoals de Azure Sandbox, Multi-Factor Authentication en het gebruik van Azure Landing Zones om de veiligheid van data en compliancy te waarborgen. Hiernaast wordt er gebruik gemaakt van de ISO's en CSIS. Hiermee voldoet het aan de regels en richtlijnen.
### 2.2 Wat kan er beter?
Jannick heeft benoemd dat er alleen gebruik gemaakt wordt van het Cloud platform Microsoft Azure Cloud. Dit betreft de componenten binnen alle 3 lagen van de infrastructuur namelijk de core, infra en applicatielaag.  Maar het is wel handig om rekening te houden met een Azure vendor-lock. Zodat er meer flexibiliteit en schaalbaarheid is. Mijn advies is om bijvoorbeeld een diverse mix van toonaangevende hardware- en softwareleveranciers uit te kiezen voor verschillende niveaus van redundantie en rekening te houden met duurzaamheid en economische evalutaties. Dit stelt de Hogeschool Utrecht in staat om snel te kunnen spelen op geopolitieke invloeden en voorkomt een vendor lock-in.

### 2.3 Wat moet er als eerste gebeuren?
1. Onderzoek mogelijkheden om vendor lock-in te voorkomen;
2. Onderzoek waar de risico's liggen;
3. Onderzoek naar kosteneffectiviteit en duurzaamheid;
4. Educatie

## 3 In hoeverre kan ik dit toepassen in mijn werksituatie? *waarom*

### 3.1 Wetten en regels
In mijn werksituatie voldoen wij aan veel verschillende ISO's zoals ISO 9001, 27001, 20000, 14001, 22301, NEN 7510, SOC 2, ISAE 3402, DigiD TPM, CO2-Prestatieladder. Op dit gebied zitten wij als organisatie goed. Er worden ook regelmatige organisatie en klantsysteem audits uitgevoerd.
### 3.2 Infrastructuur
Een deel van onze infrastructuur bestaat ook uit Azure welke wij ook aan klanten leveren als dienst, ook hebben wij een eigen cloud en zijn wij ook een Internet Service Provider (ISP). Wat wij afnemen is een Managed Azure Tenant waar diensten in geleverd kunnen worden. Op beveiliging niveau komen er ook heel veel dingen overeen in mijn werksituatie en bij de HU.
### 3.3 Processen (verbetering)
Wij maken gebruik van de Windows Security baselines maar nog geen regels of informatie van CSIS opgevolgd. Ook maken wij geen gebruik van het Cloud Adoption Framework. Hoewel onze huidige processen ook in orde zijn denk ik   dat we hier ook waardevolle inzichten uit kunnen halen en dat onze processen hierdoor verbeterd kunnen worden
