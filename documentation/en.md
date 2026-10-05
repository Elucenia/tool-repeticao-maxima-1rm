<!-- ELUCENIA technical documentation · repeticao-maxima-1rm · en · no clinical/professional/rights approval -->

# Estimated 1RM (Epley and Brzycki)

[conditions, sources and permissions](https://elucenia.org/en/tools/repeticao-maxima-1rm)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Weight lifted

`carga`

kg · range: 1–500

### Completed repetitions to failure

`reps`

range: 1–15

## Method edition

Epley load×(1+reps/30) and Brzycki 1993 load×36/(37−reps); local average; 1 rep=load

## Documented formula

Epley: 1RM = load × (1 + repetitions/30).

Brzycki: 1RM = load × 36 ÷ (37 − repetitions).

The main result is the average of both. With 1 repetition, the load is the 1RM.

## Limits and population

1RM is an estimate from load in kg and complete repetitions to fatigue, not a measured maximum. LeSuer 1997 studied 67 untrained college students after familiarization, using bench press, squat and deadlift sets of 10 repetitions or fewer. The interface accepts up to 15, but this study does not support extrapolation to 11–15. Error varied by exercise. The Epley–Brzycki mean is a local choice, not a combined equation validated in that study; the result does not guarantee a safe maximum load.

## References

- [Brzycki M. Strength testing: predicting a one-rep max from reps-to-fatigue. J Phys Educ Recreat Dance, 1993.](https://doi.org/10.1080/07303084.1993.10606684)

- [LeSuer DA et al. The accuracy of prediction equations for estimating 1-RM performance in the bench press, squat, and deadlift. J Strength Cond Res, 1997.](https://doi.org/10.1519/00124278-199711000-00001)

- [LeSuer1997,JStrengthCondRes11(4):211–213](https://paulogentil.com/pdf/The%20Accuracy%20of%20Prediction%20Equations%20for%20Estimating%201-RM%20Performance%20in%20the%20Bench%20Press,%20Squat,%20and%20Deadlift.pdf)

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
