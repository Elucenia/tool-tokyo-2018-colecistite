<!-- ELUCENIA technical documentation · tokyo-2018-colecistite · pt-BR · no clinical/professional/rights approval -->

# Gravidade da colecistite aguda (Tokyo 2018)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/tokyo-2018-colecistite)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Grau III · Cardiovascular: hipotensão com dopamina ≥ 5 µg/kg/min ou qualquer dose de noradrenalina

`cardio`

### Grau III · Neurológica: rebaixamento do nível de consciência

`neuro`

### Grau III · Respiratória: PaO₂/FiO₂ \< 300

`resp`

### Grau III · Renal: oligúria ou creatinina \> 2,0 mg/dL

`renal`

### Grau III · Hepática: INR \> 1,5

`hepat`

### Grau III · Hematológica: plaquetas \< 100.000/mm³

`hemato`

### Grau II · Leucócitos \> 18.000/mm³

`leuco`

### Grau II · Massa palpável e dolorosa no hipocôndrio direito

`massa`

### Grau II · Sintomas há mais de 72 horas

`tempo`

### Grau II · Inflamação local importante (gangrena, abscesso pericolecístico ou hepático, peritonite biliar, colecistite enfisematosa)

`local`

## Edição do método

Tokyo Guidelines 2018/Yokoe (critérios TG13 mantidos): gravidade I–III; qualquer uma das 6 disfunções orgânicas define III; na sua ausência, qualquer um dos 4 critérios moderados define II

## Fórmula documentada

Grau III (grave): qualquer disfunção orgânica listada.

Grau II (moderado): sem disfunção orgânica de grau III e com qualquer um dos quatro critérios de grau II: leucócitos \> 18.000/mm³; massa palpável e dolorosa no hipocôndrio direito; sintomas há mais de 72 horas; ou inflamação local importante.

Grau I (leve): colecistite em paciente sem critérios de grau II ou III.

## Limites e população

A edição TG18/TG13 mantém os critérios diagnósticos e de gravidade anteriores. A classificação requer suas definições clínicas e laboratoriais completas; o documento de manejo tem condições adicionais e deve ser considerado separadamente, sem deduzir uma conduta apenas da categoria. Na Tabela 7 da TG18, o grau II requer qualquer um dos quatro critérios listados, desde que não exista disfunção de grau III; não se limita à inflamação local importante. Esta verificação testa sinais já assinalados em uma colecistite previamente diagnosticada. Não testa a atribuição clínica dos sinais, os limites laboratoriais, a elegibilidade diagnóstica ou a conduta.

## Referências

- [Yokoe M et al. Tokyo Guidelines 2018: diagnostic criteria and severity grading of acute cholecystitis (with videos). J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.515)

- [Okamoto K et al. Tokyo Guidelines 2018: flowchart for the management of acute cholecystitis. J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.516)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
