# Âge des viticulteurs et transmission des exploitations en Champagne et en Bourgogne : statistiques publiques (2019-2022)

Jeu de données de l'**Observatoire VITACEAE** (Reims, France). Valeurs publiées par la statistique publique sur l'âge des viticulteurs et la transmission des exploitations viticoles dans la Marne, l'Aube, la Côte-d'Or, la Saône-et-Loire et l'Yonne : recensement agricole 2020 (Agreste), Mutualité sociale agricole (MSA, effectifs 2019, départs 2011-2018, projection 2019-2029) et recensement de la population 2022 (Insee). Aucune donnée nouvelle n'est produite.

*English summary below.*

## Contenu

| Fichier | Lignes | Description |
|---|---|---|
| `VITACEAE_age_transmission_viticulture_Champagne_Bourgogne_v1.0.1.csv` | 55 | Une ligne par valeur citée dans l'étude, avec sa source. Séparateur : point-virgule ; encodage UTF-8 ; décimales à la virgule. |

### Colonnes

| Colonne | Contenu |
|---|---|
| `zone` | Département, région ou France métropolitaine |
| `departement_code` | Code du département, vide pour une région |
| `indicateur` | Libellé de l'indicateur |
| `valeur` | Valeur publiée par la source |
| `unite` | Unité (%, personnes, exploitations, ha, ans, ratio) |
| `annee` | Année ou période de référence |
| `champ` | Champ couvert par la valeur |
| `source_ref` | Numéro de la référence dans l'étude (1 à 7) |
| `source` | Publication d'origine |

## Précautions de lecture

- Les champs diffèrent selon les sources (exploitations, affiliés MSA, personnes en emploi) : les valeurs se lisent côte à côte et ne s'additionnent pas.
- Dans la source Insee, la catégorie « viticulteur » inclut l'arboriculture.
- La projection 2019-2029 est une simulation du service statistique de la DRAAF Grand Est (SRISE) d'après la MSA, à installations constantes.
- Le taux de renouvellement publié par Agreste Grand Est rapporte les installations de 2010 à 2020 à l'effectif d'exploitants de 60 ans et plus en 2010. Ce n'est pas un taux de reprise. En viticulture, les valeurs par département sont lues d'après l'ordre des colonnes du tableau source.

## Étude et page de présentation

- Étude (PDF) : Petit, P. (2026). *Âge des viticulteurs et transmission des exploitations en Champagne et en Bourgogne. Ce que disent les statistiques publiques (2019-2022)*. Observatoire VITACEAE. DOI [10.5281/zenodo.24143511](https://doi.org/10.5281/zenodo.24143511)
- Page de présentation : [vitaceae.fr/observatoire/demographie-et-transmission/](https://vitaceae.fr/observatoire/demographie-et-transmission/)

## Autres dépôts du même jeu

- Zenodo : DOI [10.5281/zenodo.24143687](https://doi.org/10.5281/zenodo.24143687) (version 1.0.1)
- Figshare : DOI [10.6084/m9.figshare.34984282](https://doi.org/10.6084/m9.figshare.34984282)

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Réutilisation libre avec mention de la source : « Observatoire VITACEAE, d'après Agreste, MSA et Insee », avec un lien vers https://vitaceae.fr/observatoire/demographie-et-transmission/

## Auteur

Philippe Petit, VITACEAE, Reims. ORCID [0009-0000-9388-6370](https://orcid.org/0009-0000-9388-6370)
Site : [www.vitaceae.fr](https://www.vitaceae.fr)

Travail documentaire ; ni conseil juridique, ni fiscal, ni patrimonial.

---

## English summary

Values published by French public statistics on the age of winegrowers and the succession of wine farms in the Marne, Aube, Côte-d'Or, Saône-et-Loire and Yonne departments: 2020 agricultural census (Agreste), farmers' social security fund (MSA, 2019 headcounts, departures 2011-2018 and a 2019-2029 projection by the Grand Est statistical service SRISE DRAAF based on MSA data) and 2022 population census (Insee). One row per value with its source; semicolon-separated, UTF-8, decimal comma. Scopes differ between sources and values must not be added together. The renewal rate compares farmers who set up between 2010 and 2020 with farmers aged 60 or over in 2010; it is not a takeover rate.

Study: https://doi.org/10.5281/zenodo.24143511. Presentation page: https://vitaceae.fr/observatoire/demographie-et-transmission/. Licence CC BY 4.0, attribution "Observatoire VITACEAE, after Agreste, MSA and Insee".
