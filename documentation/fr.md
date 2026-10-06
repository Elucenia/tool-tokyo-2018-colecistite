<!-- ELUCENIA technical documentation · tokyo-2018-colecistite · fr · no clinical/professional/rights approval -->

# Sévérité de la cholécystite aiguë (Tokyo 2018)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/tokyo-2018-colecistite)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Grade III · Cardiovasculaire : hypotension sous dopamine ≥ 5 µg/kg/min ou toute dose de noradrénaline

`cardio`

### Grade III · Neurologique : baisse du niveau de conscience

`neuro`

### Grade III · Respiratoire : PaO₂/FiO₂ \< 300

`resp`

### Grade III · Rénale : oligurie ou créatinine \> 2,0 mg/dL

`renal`

### Grade III · Hépatique : INR \> 1,5

`hepat`

### Grade III · Hématologique : plaquettes \< 100 000/mm³

`hemato`

### Grade II · Leucocytes \> 18 000/mm³

`leuco`

### Grade II · Masse palpable et douloureuse de l’hypochondre droit

`massa`

### Grade II · Symptômes depuis plus de 72 heures

`tempo`

### Grade II · Inflammation locale importante (gangrène, abcès péricholécystique ou hépatique, péritonite biliaire, cholécystite emphysémateuse)

`local`

## Édition de la méthode

Tokyo Guidelines 2018/Yokoe (critères TG13 conservés) : gravité I–III ; l’une des 6 dysfonctions d’organe définit III ; en leur absence, l’un des 4 critères modérés définit II

## Formule documentée

Grade III (sévère) : toute dysfonction d’organe listée.

Grade II (modéré) : absence de dysfonction d’organe de grade III et présence de l’un des quatre critères de grade II : leucocytes \> 18 000/mm³ ; masse palpable et douloureuse de l’hypocondre droit ; symptômes depuis plus de 72 heures ; ou inflammation locale importante.

Grade I (léger) : cholécystite chez un patient sans critères de grade II ou III.

## Limites et population

L’édition TG18/TG13 conserve les critères diagnostiques et de sévérité antérieurs. La classification exige leurs définitions cliniques et biologiques complètes ; le document de prise en charge contient des conditions supplémentaires et doit être considéré séparément, sans déduire une conduite de la seule catégorie. Dans le Tableau 7 de TG18, le grade II exige l’un des quatre critères listés, en l’absence de dysfonction de grade III ; il ne se limite pas à une inflammation locale importante. Cette vérification teste des signes déjà cochés pour une cholécystite préalablement diagnostiquée. Elle ne teste ni l’attribution clinique des signes, ni les seuils biologiques, ni l’éligibilité diagnostique, ni la prise en charge.

## Références

- [Yokoe M et al. Tokyo Guidelines 2018: diagnostic criteria and severity grading of acute cholecystitis (with videos). J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.515)

- [Okamoto K et al. Tokyo Guidelines 2018: flowchart for the management of acute cholecystitis. J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.516)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Grade I (léger) : sans critères de grade II ou III

| Détails du résultat | |
| --- | --- |
| Conduite proposée (TG18) | Cholécystectomie laparoscopique précoce si le risque chirurgical le permet. |


### 2

Grade II (modéré) : inflammation locale importante

| Détails du résultat | |
| --- | --- |
| Conduite proposée (TG18) | Cholécystectomie laparoscopique précoce dans un centre expérimenté si le risque chirurgical le permet ; sinon, traitement médical et drainage si nécessaire. |


### 3

Grade II (modéré) : inflammation locale importante

| Détails du résultat | |
| --- | --- |
| Conduite proposée (TG18) | Cholécystectomie laparoscopique précoce dans un centre expérimenté si le risque chirurgical le permet ; sinon, traitement médical et drainage si nécessaire. |


### 4

Grade III (sévère) : cholécystite aiguë avec dysfonction d’organe

| Détails du résultat | |
| --- | --- |
| Conduite proposée (TG18) | Soutien d’organe et antibiotiques ; cholécystectomie précoce seulement dans un centre expérimenté et avec des critères favorables, sinon drainage vésiculaire urgent ou précoce. |

