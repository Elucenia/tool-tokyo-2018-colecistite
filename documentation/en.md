<!-- ELUCENIA technical documentation · tokyo-2018-colecistite · en · no clinical/professional/rights approval -->

# Acute cholecystitis severity (Tokyo 2018)

[conditions, sources and permissions](https://elucenia.org/en/tools/tokyo-2018-colecistite)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Grade III · Cardiovascular: hypotension requiring dopamine ≥ 5 µg/kg/min or any dose of norepinephrine

`cardio`

### Grade III · Neurological: reduced level of consciousness

`neuro`

### Grade III · Respiratory: PaO₂/FiO₂ \< 300

`resp`

### Grade III · Renal: oliguria or creatinine \> 2.0 mg/dL

`renal`

### Grade III · Hepatic: INR \> 1.5

`hepat`

### Grade III · Hematologic: platelets \< 100,000/mm³

`hemato`

### Grade II · Leukocytes \> 18,000/mm³

`leuco`

### Grade II · Palpable tender mass in the right upper quadrant

`massa`

### Grade II · Symptoms for more than 72 hours

`tempo`

### Grade II · Marked local inflammation (gangrene, pericholecystic or hepatic abscess, biliary peritonitis, emphysematous cholecystitis)

`local`

## Method edition

Tokyo Guidelines 2018/Yokoe (TG13 criteria retained): severity I–III; any of the 6 organ dysfunctions defines III; in their absence, any of the 4 moderate criteria defines II

## Documented formula

Grade III (severe): any listed organ dysfunction.

Grade II (moderate): no grade III organ dysfunction and any of the four grade II criteria: white blood cells \> 18,000/mm³; a palpable tender mass in the right upper quadrant; symptoms for more than 72 hours; or marked local inflammation.

Grade I (mild): cholecystitis in a patient without grade II or III criteria.

## Limits and population

The TG18/TG13 edition retains the previous diagnostic and severity criteria. Classification requires their complete clinical and laboratory definitions; the management document has additional conditions and must be considered separately, without deriving a course of action solely from the category. In TG18 Table 7, grade II requires any of the four listed criteria, provided there is no grade III dysfunction; it is not limited to marked local inflammation. This review tests already checked findings in previously diagnosed cholecystitis. It does not test the clinical assignment of findings, laboratory thresholds, diagnostic eligibility or management.

## References

- [Yokoe M et al. Tokyo Guidelines 2018: diagnostic criteria and severity grading of acute cholecystitis (with videos). J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.515)

- [Okamoto K et al. Tokyo Guidelines 2018: flowchart for the management of acute cholecystitis. J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.516)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
