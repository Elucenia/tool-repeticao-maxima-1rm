<!-- ELUCENIA technical documentation · repeticao-maxima-1rm · ja · no clinical/professional/rights approval -->

# 推定1RM（Epley・Brzycki）

[条件・出典・許諾](https://elucenia.org/ja/tools/repeticao-maxima-1rm)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 挙上重量

`carga`

kg · 範囲: 1–500

### 限界までの完全反復回数

`reps`

範囲: 1–15

## 方法の版

Epley 負荷×(1+回数/30)とBrzycki 1993 負荷×36/(37−回数)；本実装では平均；1回=負荷

## 記載された計算式

Epley: 1RM = 負荷 × (1 + 反復回数/30).

Brzycki: 1RM = 負荷 × 36 ÷ (37 − 反復回数).

主な結果は両式の平均値です。1回の場合、 負荷が1RMとなります。

## 限界・対象集団

1RM は kg 単位の負荷と疲労に至るまでの完全な反復回数から得る推定値であり、実測した最大値ではありません。LeSuer 1997 は動作に慣れた後の未訓練の大学生 67 人を対象に、ベンチプレス、スクワット、デッドリフトを 10 回以下のセットで検討しました。画面では 15 回まで入力できますが、この研究は 11–15 回への外挿を裏付けません。誤差は種目によって異なりました。Epley–Brzycki の平均は本実装の選択であり、この研究で検証された統合式ではありません。結果は安全な最大負荷を保証しません。

## 参考文献

- [Brzycki M. Strength testing: predicting a one-rep max from reps-to-fatigue. J Phys Educ Recreat Dance, 1993.](https://doi.org/10.1080/07303084.1993.10606684)

- [LeSuer DA et al. The accuracy of prediction equations for estimating 1-RM performance in the bench press, squat, and deadlift. J Strength Cond Res, 1997.](https://doi.org/10.1519/00124278-199711000-00001)

- [LeSuer1997,JStrengthCondRes11(4):211–213](https://paulogentil.com/pdf/The%20Accuracy%20of%20Prediction%20Equations%20for%20Estimating%201-RM%20Performance%20in%20the%20Bench%20Press,%20Squat,%20and%20Deadlift.pdf)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

Epley 133.3 kg · Brzycki 133.3 kg

| 結果の詳細 | |
| --- | --- |
| 1RM の90%（最大筋力） | 120.0 kg |
| 1RM の80%（筋肥大/筋力） | 106.7 kg |
| 1RM の70% | 93.3 kg |
| 1RM の60%（初心者、持久力） | 80.0 kg |


### 2

Epley 93.3 kg · Brzycki 90.0 kg

| 結果の詳細 | |
| --- | --- |
| 1RM の90%（最大筋力） | 82.5 kg |
| 1RM の80%（筋肥大/筋力） | 73.3 kg |
| 1RM の70% | 64.2 kg |
| 1RM の60%（初心者、持久力） | 55.0 kg |


### 3

Epley 60.0 kg · Brzycki 60.0 kg

| 結果の詳細 | |
| --- | --- |
| 1RM の90%（最大筋力） | 54.0 kg |
| 1RM の80%（筋肥大/筋力） | 48.0 kg |
| 1RM の70% | 42.0 kg |
| 1RM の60%（初心者、持久力） | 36.0 kg |

