---
title: LocationFeatureSpecification - Ausstattungen
permalink: /docs/types/LocationFeatureSpecification
---
# LocationFeatureSpecification - Ausstattungen

[schema.org/LocationFeatureSpecification](https://schema.org/LocationFeatureSpecification).
[docs.discover.swiss - LocationFeatureSpecification](https://docs.discover.swiss/dev/reference/dataschema/definition/infocenter-classes/LocationFeatureSpecification/)

## Datentabelle der Auszeichnungen
Ist die Basis für das JSON-LD

[Google Tabelle](https://docs.google.com/spreadsheets/d/1GnhG0kU3Nfkry1wTNCbapPzWXL9XswWIsL7rMmyDpsw/edit#gid=0)

## Data / API

* [JSON-LD](/api/types/LocationFeatureSpecification/index.jsonld) (ToDo)

### Examples
```json
{
    "@context": "https://schema.org",
    "@type": "LocationFeatureSpecification",
    "name": "Sauna",
    "value": true,
    "hoursAvailable": {
        "@type": "OpeningHoursSpecification",
        "dayOfWeek": "https://schema.org/Thursday",
        "opens": "16:00:00",
        "closes": "21:00:00"
    },
},
{
    "@context": "https://schema.org",
    "@type": "LocationFeatureSpecification",
    "name": "Gym",
    "value": true,
}
```