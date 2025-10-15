---
name: Gespreksverslag CRM
about: Leg klantgesprekken vast om CRM-inzichten op te bouwen
title: CRM - Gespreksverslag
labels: ''
assignees: ''

---

name: 🗓️ Gespreksverslag CRM
description: Leg klantgesprekken vast om CRM-inzichten op te bouwen
title: "[Klantgesprek] "
labels: ["CRM", "klantgesprek"]
body:
  - type: input
    id: datum
    attributes:
      label: Datum
      description: Wanneer vond het gesprek plaats?
      placeholder: "JJJJ-MM-DD"
  - type: input
    id: klant
    attributes:
      label: Naam klant / bedrijf
      placeholder: "Bedrijfsnaam"
  - type: input
    id: contactpersoon
    attributes:
      label: Contactpersoon
      placeholder: "Naam van de contactpersoon"
  - type: input
    id: functie
    attributes:
      label: Functie
      placeholder: "Bijv. Inkoopmanager, Bedrijfsleider"
  - type: dropdown
    id: gesprekstype
    attributes:
      label: Gesprekstype
      options:
        - Telefonisch
        - Online
        - Op locatie
  - type: input
    id: medewerkers
    attributes:
      label: Betrokken Florisoft-medewerker(s)
      placeholder: "Bijv. Jan Jansen, Lisa de Vries"
  - type: textarea
    id: samenvatting
    attributes:
      label: Samenvatting van het gesprek
      description: Beschrijf kort onderwerp, aanleiding en context.
  - type: textarea
    id: signalen
    attributes:
      label: Belangrijkste punten / signalen
      description: Benoem opvallende zaken of belangrijke inzichten.
      placeholder: "- ..."
  - type: textarea
    id: kansen
    attributes:
      label: Kansen & behoeften
      description: Welke wensen, verbeterpunten of commerciële kansen kwamen naar voren?
      placeholder: "- ..."
  - type: textarea
    id: acties
    attributes:
      label: Acties & opvolging
      description: Beschrijf vervolgstappen en wie verantwoordelijk is.
      placeholder: |
        | Actie | Verantwoordelijke | Deadline | Status |
        |-------|--------------------|-----------|--------|
        |       |                    |           |        |
  - type: textarea
    id: inzichten
    attributes:
      label: Opmerkingen / inzichten voor CRM
      description: Denk aan klantsegment, tevredenheid, productgebruik, relatie-status, etc.
  - type: input
    id: tags
    attributes:
      label: Tags
      placeholder: "#CRM #klantgesprek #opvolging"
