# Microsoft Cloud Adoption Framework voor Azure
*Lesson 11 – Governance Frameworks*

[Github Link](https://github.com/happybartman/Cloud-Governance)

## Introductie

Voor veel organisaties lijkt de overstap naar de cloud in eerste instantie eenvoudig. Er wordt een cloudaccount aangemaakt, een proof of concept uitgevoerd en al snel draaien de eerste workloads in de cloud. In de praktijk ontstaan daarna echter vaak problemen. Kosten lopen onverwacht op, beveiligingsinstellingen blijken onvoldoende, auditors stellen vragen en het overzicht ontbreekt. Dit laat zien dat cloudadoptie zonder duidelijke afspraken en sturing risico’s met zich meebrengt. Cloud governance is nodig om grip te houden op processen, kosten, beveiliging en verantwoordelijkheden. Het Microsoft Cloud Adoption Framework voor Azure is ontwikkeld om organisaties hierbij te ondersteunen.

---

## 1. Wat is het Microsoft Cloud Adoption Framework voor Azure?

Het Microsoft Cloud Adoption Framework (CAF) voor Azure is een praktisch raamwerk dat organisaties helpt bij het gestructureerd plannen, uitvoeren en beheren van cloudadoptie. Het framework is ontwikkeld door Microsoft en richt zich specifiek op organisaties die Azure gebruiken als cloudplatform. Het Cloud Adoption Framework is geen norm of certificeringsstandaard, maar een verzameling richtlijnen, best practices en hulpmiddelen die samen een leidraad vormen voor cloud governance en cloudimplementatie.

![Afbeelding 1](https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/caf-overview.png)

Het framework gaat ervan uit dat cloudadoptie niet alleen een technisch traject is, maar ook een organisatorische en bestuurlijke verandering. Daarom richt CAF zich niet uitsluitend op IT-teams, maar ook op management en de business. Het doel is om cloudgebruik af te stemmen op bedrijfsdoelstellingen, terwijl risico’s, kosten en compliance beheersbaar blijven.

Microsoft beschrijft het Cloud Adoption Framework als een set kern- en operationele methodologieën. De kernmethodologieën volgen grotendeels een logische volgorde: Strategy, Plan, Ready en Adopt. Daarnaast zijn er operationele methodologieën die gedurende de hele cloudlevenscyclus doorlopen: Govern, Secure en Manage. Samen zorgen deze onderdelen voor een complete aanpak van cloudadoptie en cloud governance.

In hoofdlijnen omvat CAF de volgende onderdelen:
- **Strategy** – het bepalen van zakelijke doelen en cloudmotivaties  
- **Plan** – het voorbereiden van mensen, processen en technologie  
- **Ready** – het inrichten van de Azure-omgeving en landing zones  
- **Adopt** – het migreren, moderniseren of cloud-native bouwen van workloads  
- **Govern** – het vaststellen van governancebeleid, zoals kosten en compliance  
- **Secure** – het end-to-end beveiligen van de cloudomgeving  
- **Manage** – het operationeel beheren en optimaliseren van de omgeving  

*Bron: Microsoft Azure Cloud Adoption Framework; Microsoft Learn – Azure Cloud Adoption Framework.*

---

## 2. Hoe draagt het Azure Cloud Adoption Framework bij aan Cloud Governance?

Het Cloud Adoption Framework draagt op meerdere niveaus bij aan cloud governance door structuur aan te brengen in processen, techniek, mensen en besluitvorming. Governance binnen CAF draait om het beheerst inzetten van cloudtechnologie en het kunnen aantonen dat dit op een verantwoorde manier gebeurt.

### Processen

CAF helpt organisaties bij het vastleggen van processen rondom cloudgebruik. In de **Govern**-methodologie worden richtlijnen opgesteld voor kostenbeheer, beveiliging en compliance. Denk hierbij aan budgetlimieten, goedkeuringsprocedures en standaardwerkwijzen voor het aanmaken van cloudresources. Hierdoor wordt voorkomen dat teams ongecontroleerd resources inzetten, wat kan leiden tot hoge kosten of beveiligingsincidenten.

### Cloudcomponenten en services

Op technisch niveau introduceert CAF het concept van landing zones. Dit zijn vooraf ingerichte Azure-omgevingen met standaard netwerken, identiteiten, beveiligingsinstellingen en policies. Governance wordt hiermee technisch afgedwongen via Azure Policies en role-based access control (RBAC). Hierdoor zijn beveiliging en compliance niet alleen vastgelegd in documenten, maar ook daadwerkelijk geïmplementeerd in de cloudomgeving.

### Security als doorlopend onderdeel

Een belangrijk uitgangspunt van CAF is dat security geen eenmalige stap is. De Secure-methodologie loopt door alle fasen heen en richt zich op het beschermen van identiteiten, data, netwerken en workloads. Door security structureel mee te nemen, ondersteunt CAF organisaties bij het toepassen van het shared responsibility model en het beperken van risico’s.

### Business en mensen

CAF benadrukt dat cloud governance niet alleen een IT-verantwoordelijkheid is. Het framework stimuleert samenwerking tussen business en IT door rollen en verantwoordelijkheden duidelijk te definiëren. Een belangrijk concept hierbij is het Cloud Center of Excellence (CCoE): een multidisciplinair team dat richtlijnen opstelt, kennis deelt en toezicht houdt op cloudgebruik. Daarnaast helpt CAF bij het koppelen van cloudinitiatieven aan bedrijfsdoelstellingen, zodat cloudtechnologie daadwerkelijk waarde toevoegt aan de organisatie.

---

## 3. Is het Cloud Adoption Framework compleet?

Het Cloud Adoption Framework dekt veel belangrijke aspecten van cloud governance, zoals strategie, kostenbeheer, beveiliging en operationeel beheer. Vooral voor organisaties die volledig op Azure inzetten, biedt het framework een samenhangende en praktische aanpak. Toch is het framework niet volledig allesomvattend. Voor formele audits, uitgebreide risicobeoordelingen of wettelijke compliance kan aanvullende standaarden zoals ISO 27001 of COBIT nodig zijn. CAF fungeert daarmee vooral als praktisch governance-raamwerk en niet als vervanging van formele normen.

---

## 4. Sterke punten van het Azure Cloud Adoption Framework

Een belangrijk sterk punt van CAF is de  toepasbaarheid. Het framework sluit goed aan op Azure-diensten en tooling, waardoor organisaties snel stappen kunnen zetten. Daarnaast biedt CAF een duidelijke structuur met herkenbare fasen, wat helpt bij het plannen en beheersen van cloudadoptie. Ook de nadruk op samenwerking tussen business en IT is een sterk punt, omdat governance hierdoor breder wordt gedragen binnen de organisatie.

---

## 5. Beperkingen en zwakke punten

Een duidelijke beperking van het Cloud Adoption Framework is dat het sterk Azure-gericht is. Voor organisaties met een multicloudstrategie is het framework minder geschikt zonder aanvullende richtlijnen. Daarnaast is CAF geen officiële standaard met certificering, wat betekent dat het minder geschikt is voor organisaties die formeel moeten aantonen dat zij aan bepaalde normen voldoen. Tot slot vereist het framework een bepaalde mate van volwassenheid binnen de organisatie om effectief toegepast te worden.

---

## 6. Relatie met grote cloud providers

Microsoft past het Cloud Adoption Framework actief toe binnen Azure en integreert het framework met Azure-diensten zoals Azure Policy en Cost Management. Andere cloudproviders hebben vergelijkbare frameworks ontwikkeld, zoals het AWS Cloud Adoption Framework en het Google Cloud Adoption Framework. Hoewel deze frameworks verschillen in uitwerking, delen ze dezelfde principes op het gebied van governance, kostenbeheer en security. Dit laat zien dat cloud governance een provider-onafhankelijk thema is, ondanks verschillen in tooling.

---

## Uitlegvideo

Voor een korte en toegankelijke uitleg van het Microsoft Cloud Adoption Framework voor Azure is de volgende video gebruikt:

- **Titel:** Microsoft Azure Cloud Adoption Framework Explained  
- **Platform:** YouTube  
- **Duur:** 2:06 
- **Link:** https://www.youtube.com/watch?v=NGz6fA7aQL4 

Deze video geeft een overzicht van het Azure Cloud Adoption Framework, waaronder strategie, planning, governance, en beheer. Het is geschikt als introductie voor studenten die het framework nog niet kennen.

---

## Conclusie

Het Microsoft Cloud Adoption Framework voor Azure biedt een praktische en gestructureerde aanpak voor cloud governance binnen Azure-omgevingen. Het framework helpt organisaties om cloudadoptie te koppelen aan bedrijfsdoelstellingen, terwijl kosten, beveiliging en compliance beheersbaar blijven. Hoewel het framework niet alle governance-aspecten volledig afdekt en sterk Azure-gericht is, vormt het een solide basis voor organisaties die grip willen houden op hun cloudomgeving.

---

## Bronnen

- Microsoft Azure, *Cloud Adoption Framework – overzicht*  
  https://azure.microsoft.com/nl-nl/solutions/azure-essentials/cloud-adoption-framework/

- Microsoft Learn, *Azure Cloud Adoption Framework*  
  https://learn.microsoft.com/nl-nl/azure/cloud-adoption-framework/

- Microsoft Learn, *Cloud Governance – Cloud Adoption Framework*  
  https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/govern/

- Microsoft Learn, *Secure methodology – Cloud Adoption Framework*  
  https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/secure/

- Microsoft Learn, *Azure Landing Zones*  
  https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/

- Amazon Web Services, *AWS Cloud Adoption Framework*  
  https://aws.amazon.com/cloud-adoption-framework/

- NIST, *Cybersecurity Framework*  
  https://www.nist.gov/cyberframework

- Moresi, *What the 5 R’s of Cloud Rationalization Are and How They Work*  
  https://www.moresi.com/en/what-the-5-rs-of-cloud-rationalization-are-and-how-they-work/

- Video: *Microsoft Azure Cloud Adoption Framework Explained*  
  https://www.youtube.com/watch?v=NGz6fA7aQL4





