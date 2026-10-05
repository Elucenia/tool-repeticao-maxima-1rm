<!-- ELUCENIA technical documentation · repeticao-maxima-1rm · it · no clinical/professional/rights approval -->

# 1RM stimato (Epley e Brzycki)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/repeticao-maxima-1rm)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Carico sollevato

`carga`

kg · intervallo: 1–500

### Ripetizioni complete fino al cedimento

`reps`

intervallo: 1–15

## Edizione del metodo

Epley carico×(1+rip/30) e Brzycki 1993 carico×36/(37−rip); media locale; 1 rip=carico

## Formula documentata

Epley: 1RM = carico × (1 + ripetizioni/30).

Brzycki: 1RM = carico × 36 ÷ (37 − ripetizioni).

Il risultato principale è la media delle due. Con 1 ripetizione, il carico è la 1RM.

## Limiti e popolazione

La 1RM è una stima basata sul carico in kg e sulle ripetizioni complete fino alla fatica, non un massimo misurato. LeSuer 1997 ha studiato 67 universitari non allenati, dopo familiarizzazione, in panca piana, squat e stacco da terra, con serie di 10 ripetizioni o meno. L’interfaccia accetta fino a 15, ma lo studio non sostiene l’estrapolazione a 11–15. L’errore variava secondo l’esercizio. La media Epley–Brzycki è una scelta locale, non un’equazione combinata validata in quello studio; il risultato non garantisce un carico massimo sicuro.

## Riferimenti

- [Brzycki M. Strength testing: predicting a one-rep max from reps-to-fatigue. J Phys Educ Recreat Dance, 1993.](https://doi.org/10.1080/07303084.1993.10606684)

- [LeSuer DA et al. The accuracy of prediction equations for estimating 1-RM performance in the bench press, squat, and deadlift. J Strength Cond Res, 1997.](https://doi.org/10.1519/00124278-199711000-00001)

- [LeSuer1997,JStrengthCondRes11(4):211–213](https://paulogentil.com/pdf/The%20Accuracy%20of%20Prediction%20Equations%20for%20Estimating%201-RM%20Performance%20in%20the%20Bench%20Press,%20Squat,%20and%20Deadlift.pdf)

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
