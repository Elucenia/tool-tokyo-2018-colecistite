<!-- ELUCENIA technical documentation · tokyo-2018-colecistite · es · no clinical/professional/rights approval -->

# Gravedad de la colecistitis aguda (Tokyo 2018)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/tokyo-2018-colecistite)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Grado III · Cardiovascular: hipotensión con dopamina ≥ 5 µg/kg/min o cualquier dosis de noradrenalina

`cardio`

### Grado III · Neurológico: disminución del nivel de conciencia

`neuro`

### Grado III · Respiratoria: PaO₂/FiO₂ \< 300

`resp`

### Grado III · Renal: oliguria o creatinina \> 2,0 mg/dL

`renal`

### Grado III · Hepática: INR \> 1,5

`hepat`

### Grado III · Hematológica: plaquetas \< 100.000/mm³

`hemato`

### Grado II · Leucocitos \> 18.000/mm³

`leuco`

### Grado II · Masa palpable y dolorosa en el hipocondrio derecho

`massa`

### Grado II · Síntomas durante más de 72 horas

`tempo`

### Grado II · Inflamación local importante (gangrena, absceso pericolecístico o hepático, peritonitis biliar, colecistitis enfisematosa)

`local`

## Edición del método

Tokyo Guidelines 2018/Yokoe (criterios TG13 mantenidos): gravedad I–III; cualquiera de las 6 disfunciones orgánicas define III; en su ausencia, cualquiera de los 4 criterios moderados define II

## Fórmula documentada

Grado III (grave): cualquier disfunción orgánica listada.

Grado II (moderado): sin disfunción orgánica de grado III y con cualquiera de los cuatro criterios de grado II: leucocitos \> 18.000/mm³; masa palpable y dolorosa en el hipocondrio derecho; síntomas durante más de 72 horas; o inflamación local importante.

Grado I (leve): colecistitis en un paciente sin criterios de grado II o III.

## Límites y población

La edición TG18/TG13 mantiene los criterios diagnósticos y de gravedad anteriores. La clasificación requiere sus definiciones clínicas y de laboratorio completas; el documento de manejo tiene condiciones adicionales y debe considerarse por separado, sin deducir una conducta únicamente de la categoría. En la Tabla 7 de TG18, el grado II requiere cualquiera de los cuatro criterios listados, siempre que no exista disfunción de grado III; no se limita a la inflamación local importante. Esta verificación prueba hallazgos ya marcados en una colecistitis previamente diagnosticada. No prueba la atribución clínica de los hallazgos, los límites de laboratorio, la elegibilidad diagnóstica ni la conducta.

## Referencias

- [Yokoe M et al. Tokyo Guidelines 2018: diagnostic criteria and severity grading of acute cholecystitis (with videos). J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.515)

- [Okamoto K et al. Tokyo Guidelines 2018: flowchart for the management of acute cholecystitis. J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.516)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Grado I (leve): sin criterios de grado II o III

| Detalles del resultado | |
| --- | --- |
| Conducta sugerida (TG18) | Colecistectomía laparoscópica precoz si el riesgo quirúrgico lo permite. |


### 2

Grado II (moderada): inflamación local importante

| Detalles del resultado | |
| --- | --- |
| Conducta sugerida (TG18) | Colecistectomía laparoscópica precoz en un centro con experiencia si el riesgo quirúrgico lo permite; de lo contrario, tratamiento médico y drenaje si es necesario. |


### 3

Grado II (moderada): inflamación local importante

| Detalles del resultado | |
| --- | --- |
| Conducta sugerida (TG18) | Colecistectomía laparoscópica precoz en un centro con experiencia si el riesgo quirúrgico lo permite; de lo contrario, tratamiento médico y drenaje si es necesario. |


### 4

Grado III (grave): colecistitis aguda con disfunción orgánica

| Detalles del resultado | |
| --- | --- |
| Conducta sugerida (TG18) | Soporte orgánico y antibiótico; colecistectomía precoz solo en un centro con experiencia y con criterios favorables; de lo contrario, drenaje urgente o precoz de la vesícula biliar. |

