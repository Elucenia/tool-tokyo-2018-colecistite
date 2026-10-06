<!-- ELUCENIA technical documentation · tokyo-2018-colecistite · it · no clinical/professional/rights approval -->

# Gravità della colecistite acuta (Tokyo 2018)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/tokyo-2018-colecistite)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Grado III · Cardiovascolare: ipotensione con dopamina ≥ 5 µg/kg/min o qualsiasi dose di noradrenalina

`cardio`

### Grado III · Neurologico: riduzione del livello di coscienza

`neuro`

### Grado III · Respiratoria: PaO₂/FiO₂ \< 300

`resp`

### Grado III · Renale: oliguria o creatinina \> 2,0 mg/dL

`renal`

### Grado III · Epatica: INR \> 1,5

`hepat`

### Grado III · Ematologica: piastrine \< 100.000/mm³

`hemato`

### Grado II · Leucociti \> 18.000/mm³

`leuco`

### Grado II · Massa palpabile e dolente nell’ipocondrio destro

`massa`

### Grado II · Sintomi da più di 72 ore

`tempo`

### Grado II · Marcata infiammazione locale (gangrena, ascesso pericolecistico o epatico, peritonite biliare, colecistite enfisematosa)

`local`

## Edizione del metodo

Tokyo Guidelines 2018/Yokoe (criteri TG13 mantenuti): gravità I–III; una qualsiasi delle 6 disfunzioni d’organo definisce III; in loro assenza, uno qualsiasi dei 4 criteri moderati definisce II

## Formula documentata

Grado III (grave): qualsiasi disfunzione d’organo elencata.

Grado II (moderato): nessuna disfunzione d’organo di grado III e uno qualsiasi dei quattro criteri di grado II: leucociti \> 18.000/mm³; massa palpabile e dolente nell’ipocondrio destro; sintomi da più di 72 ore; o importante infiammazione locale.

Grado I (lieve): colecistite in un paziente senza criteri di grado II o III.

## Limiti e popolazione

L’edizione TG18/TG13 mantiene i precedenti criteri diagnostici e di gravità. La classificazione richiede le loro definizioni cliniche e di laboratorio complete; il documento di gestione presenta condizioni aggiuntive e deve essere considerato separatamente, senza dedurre una condotta dalla sola categoria. Nella Tabella 7 di TG18, il grado II richiede uno qualsiasi dei quattro criteri elencati, purché non sia presente disfunzione di grado III; non si limita all’importante infiammazione locale. Questa verifica testa segni già selezionati in una colecistite precedentemente diagnosticata. Non testa l’attribuzione clinica dei segni, i limiti di laboratorio, l’idoneità diagnostica o la condotta.

## Riferimenti

- [Yokoe M et al. Tokyo Guidelines 2018: diagnostic criteria and severity grading of acute cholecystitis (with videos). J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.515)

- [Okamoto K et al. Tokyo Guidelines 2018: flowchart for the management of acute cholecystitis. J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.516)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Grado I (lieve): senza criteri di grado II o III

| Dettagli del risultato | |
| --- | --- |
| Condotta suggerita (TG18) | Colecistectomia laparoscopica precoce se il rischio chirurgico lo consente. |


### 2

Grado II (moderato): infiammazione locale importante

| Dettagli del risultato | |
| --- | --- |
| Condotta suggerita (TG18) | Colecistectomia laparoscopica precoce in un centro esperto se il rischio chirurgico lo consente; altrimenti, trattamento medico e drenaggio se necessario. |


### 3

Grado II (moderato): infiammazione locale importante

| Dettagli del risultato | |
| --- | --- |
| Condotta suggerita (TG18) | Colecistectomia laparoscopica precoce in un centro esperto se il rischio chirurgico lo consente; altrimenti, trattamento medico e drenaggio se necessario. |


### 4

Grado III (grave): colecistite acuta con disfunzione d’organo

| Dettagli del risultato | |
| --- | --- |
| Condotta suggerita (TG18) | Supporto d’organo e antibiotico; colecistectomia precoce solo in un centro esperto e con criteri favorevoli, altrimenti drenaggio urgente o precoce della colecisti. |

