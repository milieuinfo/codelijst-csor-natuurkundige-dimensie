# Codelijst CSOR Natuurkundige Dimensie

Codelijst van natuurkundige dimensies voor het **Chemische Stoffen en Omgevingsparameters-Register (CSOR)**, beheerd door het Departement Omgeving van de Vlaamse overheid.

## Inhoud

Een **natuurkundige dimensie** duidt aan welke grootheid gebruikt wordt om de observatie te doen.

De codelijst is gepubliceerd als een SKOS-conceptenschema op:

```
https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/natuurkundigedimensie
```

Elk concept bevat:

| Eigenschap | Beschrijving |
|---|---|
| `skos:prefLabel` | Naam van de dimensie (nl) |
| `skos:notation` | Notatie / afkorting |
| `csor:symbool` | Symbool |
| `csor:referentieEenheid` | Link naar de referentie-eenheid in CSOR |
| `skos:definition` | Toelichting (optioneel) |
| `owl:deprecated` | Geeft aan of het concept verouderd is |
| `csor:geldigTot` | Einddatum geldigheid (bij verouderde concepten) |

Voorbeelden van opgenomen dimensies: lengte, massa, volume, temperatuur, druk, energie, molaire concentratie, radioactiviteit per volume, massa per oppervlakte per tijd, en vele andere.

## Bestanden

De codelijst wordt aangeboden in meerdere RDF-serialisaties:

| Bestand | Formaat |
|---|---|
| `natuurkundigedimensies.ttl` | Turtle |
| `natuurkundigedimensies.nt` | N-Triples |
| `natuurkundigedimensies.rj` | RDF/JSON |
| `natuurkundigedimensies_report.ttl` | SHACL-validatierapport |

De bestanden bevinden zich in:

```
src/main/resources/be/vlaanderen/omgeving/data/id/conceptscheme/csor/natuurkundigedimensie/
```

## Gebruikte ontologieen en vocabularia

| Prefix | Namespace |
|---|---|
| `csor:` | `https://data.omgeving.vlaanderen.be/ns/csor#` |
| `skos:` | `http://www.w3.org/2004/02/skos/core#` |
| `owl:` | `http://www.w3.org/2002/07/owl#` |
| `qudt:` | `http://qudt.org/schema/qudt/` |
| `iadopt:` | `https://w3id.org/iadopt/ont/` |

## Context

Dit project maakt deel uit van het **Chemische Stoffen en Omgevingsparameters-Register (CSOR)**, een register van de Vlaamse overheid voor het eenduidig beschrijven van observaties van chemische stoffen en omgevingsparameters. Gerelateerde codelijsten binnen CSOR zijn o.a. de eenheden (`codelijst-csor-eenheid`).

## Licentie

[GNU General Public License v3.0](LICENSE)
