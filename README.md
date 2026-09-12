# Terugleverkosten: staffel of per kWh?

Open rekentool voor de **terugleverkosten** die energieleveranciers rekenen als u stroom van uw zonnepanelen teruglevert. Eén HTML-bestand, geen build, geen tracking, geen afhankelijkheden. Gemaakt door [energievergelijken2027.nl](https://energievergelijken2027.nl), MIT-licentie.

**Gebruik de tool:** https://tyscode14.github.io/energie-terugleverkosten-monitor/

## Het probleem dat deze tool oplost

Leveranciers rekenen terugleverkosten op twee **onderling onvergelijkbare** manieren:

- een **vast bedrag per maand**, dat verspringt zodra uw jaarlijkse teruglevering in een hogere staffel valt;
- een **tarief per teruggeleverde kWh**, dat lineair meeschaalt.

Daardoor bestaat er geen enkele ranglijst die voor iedereen klopt. Wie 800 kWh teruglevert is bij een heel ander bedrijf goedkoop uit dan wie 4.000 kWh teruglevert. De tool rekent beide methodes door op úw volume en laat zien waar het **kantelpunt** ligt.

In 2026 loopt de marktspreiding van **€ 0 tot € 875 per jaar**.

## Wat er op 1 januari 2027 verandert

De salderingsregeling stopt op 1 januari 2027, vastgelegd door de Eerste Kamer op 17 december 2024 (wetsvoorstel 36.611). Vrijwel de hele markt stapt dan over van staffels naar een tarief per kWh, waarmee elke op staffels gebaseerde vergelijking haar geldigheid verliest. Vanaf 2027 moet de terugleververgoeding minimaal **50% van het kale leveringstarief** zijn; die ondergrens geldt **tot 2030**.

## Over de dataset

`data/terugleverkosten.json` is nadrukkelijk een **seed-dataset**, geen ranglijst.

De bedragen komen uit openbare secundaire bronnen en zijn **indicatief**. Ze zijn niet bij de leveranciers geverifieerd. Controleer altijd het actuele tarievenblad voordat u hierop een keuze baseert.

De rekenkern van de tool werkt volledig onafhankelijk van die dataset: vult u de tarieven van uw eigen leverancier in, dan klopt de vergelijking. De dataset is er om het gesprek te beginnen, niet om het te beëindigen.

**Aanvullingen zijn welkom.** Elk record heeft velden voor `bron`, `bron_url`, `gecontroleerd_op` en `zekerheid`. Een pull request met een link naar het tarievenblad is genoeg.

## Bronnen

- Rijksoverheid over de salderingsregeling — https://www.rijksoverheid.nl/themas/klimaat-milieu-en-natuur/energie-thuis/salderingsregeling
- Wet beëindiging salderingsregeling (36.611), Eerste Kamer, 17 december 2024

## Licentie

MIT.
