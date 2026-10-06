<!-- ELUCENIA technical documentation · repeticao-maxima-1rm · pt-BR · no clinical/professional/rights approval -->

# 1RM estimada (Epley e Brzycki)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/repeticao-maxima-1rm)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Carga levantada

`carga`

kg · intervalo: 1–500

### Repetições completas até a falha

`reps`

intervalo: 1–15

## Edição do método

Epley carga×(1+reps/30) e Brzycki 1993 carga×36/(37−reps); média local; 1 rep=carga

## Fórmula documentada

Epley: 1RM = carga × (1 + repetições/30).

Brzycki: 1RM = carga × 36 ÷ (37 − repetições).

O resultado principal é a média das duas. Com 1 repetição, a própria carga é a 1RM.

## Limites e população

A 1RM é uma estimativa a partir de carga em kg e repetições completas até a fadiga, não um máximo medido. LeSuer 1997 estudou 67 universitários sem treinamento, após familiarização, no supino, agachamento e levantamento terra, com séries de 10 repetições ou menos. A interface aceita até 15, mas esse estudo não sustenta extrapolação para 11–15. O erro variou por exercício. A média Epley–Brzycki é uma escolha local, não uma equação combinada validada nesse estudo; o resultado não garante uma carga máxima segura.

## Referências

- [Brzycki M. Strength testing: predicting a one-rep max from reps-to-fatigue. J Phys Educ Recreat Dance, 1993.](https://doi.org/10.1080/07303084.1993.10606684)

- [LeSuer DA et al. The accuracy of prediction equations for estimating 1-RM performance in the bench press, squat, and deadlift. J Strength Cond Res, 1997.](https://doi.org/10.1519/00124278-199711000-00001)

- [LeSuer1997,JStrengthCondRes11(4):211–213](https://paulogentil.com/pdf/The%20Accuracy%20of%20Prediction%20Equations%20for%20Estimating%201-RM%20Performance%20in%20the%20Bench%20Press,%20Squat,%20and%20Deadlift.pdf)

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

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Epley 133,3 kg · Brzycki 133,3 kg

| Detalhes do resultado | |
| --- | --- |
| 90% de 1RM (força máxima) | 120,0 kg |
| 80% de 1RM (hipertrofia/força) | 106,7 kg |
| 70% de 1RM | 93,3 kg |
| 60% de 1RM (iniciantes, resistência) | 80,0 kg |


### 2

Epley 93,3 kg · Brzycki 90,0 kg

| Detalhes do resultado | |
| --- | --- |
| 90% de 1RM (força máxima) | 82,5 kg |
| 80% de 1RM (hipertrofia/força) | 73,3 kg |
| 70% de 1RM | 64,2 kg |
| 60% de 1RM (iniciantes, resistência) | 55,0 kg |


### 3

Epley 60,0 kg · Brzycki 60,0 kg

| Detalhes do resultado | |
| --- | --- |
| 90% de 1RM (força máxima) | 54,0 kg |
| 80% de 1RM (hipertrofia/força) | 48,0 kg |
| 70% de 1RM | 42,0 kg |
| 60% de 1RM (iniciantes, resistência) | 36,0 kg |

