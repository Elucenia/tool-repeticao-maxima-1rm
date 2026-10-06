<!-- ELUCENIA technical documentation · repeticao-maxima-1rm · es · no clinical/professional/rights approval -->

# 1RM estimada (Epley y Brzycki)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/repeticao-maxima-1rm)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Carga levantada

`carga`

kg · intervalo: 1–500

### Repeticiones completas hasta el fallo

`reps`

intervalo: 1–15

## Edición del método

Epley carga×(1+reps/30) y Brzycki 1993 carga×36/(37−reps); media local; 1 rep=carga

## Fórmula documentada

Epley: 1RM = carga × (1 + repeticiones/30).

Brzycki: 1RM = carga × 36 ÷ (37 − repeticiones).

El resultado principal es la media de ambas. Con 1 repetición, la propia carga es la 1RM.

## Límites y población

La 1RM es una estimación a partir de la carga en kg y las repeticiones completas hasta la fatiga, no un máximo medido. LeSuer 1997 estudió a 67 universitarios sin entrenamiento, tras familiarización, en press de banca, sentadilla y peso muerto, con series de 10 repeticiones o menos. La interfaz admite hasta 15, pero ese estudio no respalda extrapolar a 11–15. El error varió según el ejercicio. La media Epley–Brzycki es una elección local, no una ecuación combinada validada en ese estudio; el resultado no garantiza una carga máxima segura.

## Referencias

- [Brzycki M. Strength testing: predicting a one-rep max from reps-to-fatigue. J Phys Educ Recreat Dance, 1993.](https://doi.org/10.1080/07303084.1993.10606684)

- [LeSuer DA et al. The accuracy of prediction equations for estimating 1-RM performance in the bench press, squat, and deadlift. J Strength Cond Res, 1997.](https://doi.org/10.1519/00124278-199711000-00001)

- [LeSuer1997,JStrengthCondRes11(4):211–213](https://paulogentil.com/pdf/The%20Accuracy%20of%20Prediction%20Equations%20for%20Estimating%201-RM%20Performance%20in%20the%20Bench%20Press,%20Squat,%20and%20Deadlift.pdf)

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

Epley 133,3 kg · Brzycki 133,3 kg

| Detalles del resultado | |
| --- | --- |
| 90% de 1RM (fuerza máxima) | 120,0 kg |
| 80% de 1RM (hipertrofia/fuerza) | 106,7 kg |
| 70% de 1RM | 93,3 kg |
| 60% de 1RM (principiantes, resistencia) | 80,0 kg |


### 2

Epley 93,3 kg · Brzycki 90,0 kg

| Detalles del resultado | |
| --- | --- |
| 90% de 1RM (fuerza máxima) | 82,5 kg |
| 80% de 1RM (hipertrofia/fuerza) | 73,3 kg |
| 70% de 1RM | 64,2 kg |
| 60% de 1RM (principiantes, resistencia) | 55,0 kg |


### 3

Epley 60,0 kg · Brzycki 60,0 kg

| Detalles del resultado | |
| --- | --- |
| 90% de 1RM (fuerza máxima) | 54,0 kg |
| 80% de 1RM (hipertrofia/fuerza) | 48,0 kg |
| 70% de 1RM | 42,0 kg |
| 60% de 1RM (principiantes, resistencia) | 36,0 kg |

