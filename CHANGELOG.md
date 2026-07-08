# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Changed

- PascalCase and CamelCase
- Replace abbreviations
- Add missing dot at end of sentences
- Replace http://schema.org with https://schema.org
- Remove empty `ap-usage-note` values
- Capitalise sentences

## 2025-03-03
Aanmaak eerste datamodel op basis van business werkgroep

## 2025-04-07
Aanpassingen van datamodel op basis van feedback eerste thematische werkgroep en op basis van uitgewerkte datavoorbeelden:
Verwijderde klassen:
Klasse Energieverbruik 
Klasse Weer 
Klasse Energieprijs 
Klasse Tijdstip 
Klasse Software 
Klasse Observatieverzoekmerk 
Klasse Aanstellingsverzoekmerk 
Klasse Aanstelling Energieaanstelling 
Klasse Energieaanstelling 
Klasse Energieaanbodsimulatie 
Klasse Energiecontract 
Klasse Systeem Energietoestel 
Klasse Energiebruiktoestel 
Klasse Energieopwektoestel 

Toegevoegde klassen:
Klasse SSN/SOSA::Observatieverzameling 
Klasse SSN/SOSA::Observatiegroepkenmerk 
Klasse SSN/SOSA::Systeem 
Klasse SSN/SOSA::Deployment 
Klasse SSN/SOSA::Platform 
Klasse MWL-LD::Aanstelling 
Klasse MWL-LD::Netwerkonderdeel/netwerk 

Uitgebreide klassen (van eenvoudig naar gedetailleerd):
Klasse Observatieverzameling: uitgebreid met volledige attributenlijst en namespace SSN/SOSA::
Klasse Procedure: uitgebreid naar SSN/SOSA::Aanstellingsprocedure met volledige attributenlijst
Klasse SSN/SOSA::Observatieprocedure: uitgebreid met volledige attributenlijst
Klasse SSN/SOSA::ObserveerbaarKenmerk: uitgebreid met volledige attributenlijst
Klasse SSN/SOSA::AanstellbaarKenmerk: uitgebreid met volledige attributenlijst
Klasse SSN/SOSA::Aanstelling: uitgebreid met volledige attributenlijst
Klasse Activiteit SSN/SOSA::Observatie: uitgebreid met volledige attributenlijst
Klasse OMS::Object: uitgebreid met volledige attributenlijst
Klasse OMS::Domeinobject: uitgebreid met volledige attributenlijst
Klasse SAREF::Meter: uitgebreid met volledige attributenlijst
Klasse SAREF::Toestel: uitgebreid met volledige attributenlijst
Klasse Systeem SSN/SOSA::Sensor: uitgebreid met volledige attributenlijst
Klasse Systeem Aanstellingsysteem: uitgebreid naar SSN/SOSA::Aanstellingsysteem met volledige attributenlijst
