# Broken API

## Projekta apraksts

**Broken API** ir Python projekts, kura mērķis ir nodrošināt vienkāršas API programmas darbību. Projekts ir paredzēts palaišanai Python vidē un Docker konteinerī.

Projekts satur programmas kodu, testus un Docker konfigurāciju. Pirms izmantošanas nepieciešams instalēt projekta atkarības.

## Instalācijas instrukcija

1. Pārliecinies, ka datorā ir instalēts Python.
2. Lejupielādē vai noklonē projekta repozitoriju.
3. Atver termināli projekta mapē.
4. Instalē nepieciešamās bibliotēkas:

```bash
pip install -r requirements.txt
```

## Programmas palaišana

Lai palaistu programmu, izmanto komandu:

```bash
python app.py
```

## Testu palaišana

Lai pārbaudītu, vai programma darbojas pareizi, palaid testus:

```bash
pytest
```

## Docker

Ja datorā ir instalēts Docker, projektu iespējams palaist Docker konteinerī.

Izveido Docker image:

```bash
docker build -t broken-api .
```

Palaid Docker konteineru:

```bash
docker run broken-api
```

## Prasības

* Python
* pip
* Docker (pēc izvēles)
* projekta atkarības no `requirements.txt`

