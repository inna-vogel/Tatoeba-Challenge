# opus-2021-01-03.zip

* dataset: opus
* model: transformer
* source language(s): deu
* target language(s): fra
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* download: [opus-2021-01-03.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-fra/opus-2021-01-03.zip)
* test set translations: [opus-2021-01-03.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-fra/opus-2021-01-03.test.txt)
* test set scores: [opus-2021-01-03.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-fra/opus-2021-01-03.eval.txt)

## Benchmarks

| testset               | BLEU  | chr-F |
|-----------------------|-------|-------|
| euelections_dev2019.de-fr-deufra.deu.fra 	| 32.2 	| 0.594 |
| newssyscomb2009-deufra.deu.fra 	| 26.8 	| 0.555 |
| news-test2008-deufra.deu.fra 	| 26.6 	| 0.549 |
| newstest2009-deufra.deu.fra 	| 25.4 	| 0.539 |
| newstest2010-deufra.deu.fra 	| 29.1 	| 0.575 |
| newstest2011-deufra.deu.fra 	| 27.1 	| 0.555 |
| newstest2012-deufra.deu.fra 	| 27.5 	| 0.556 |
| newstest2013-deufra.deu.fra 	| 29.7 	| 0.562 |
| newstest2019-defr-deufra.deu.fra 	| 35.9 	| 0.628 |
| Tatoeba-test.deu.fra 	| 48.6 	| 0.661 |
| Tatoeba-test.deu-fra.deu.fra 	| 48.6 	| 0.661 |

# opus-2021-02-22.zip

* dataset: opus
* model: transformer-align
* source language(s): deu
* target language(s): fra
* model: transformer-align
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* download: [opus-2021-02-22.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-fra/opus-2021-02-22.zip)
* test set translations: [opus-2021-02-22.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-fra/opus-2021-02-22.test.txt)
* test set scores: [opus-2021-02-22.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/deu-fra/opus-2021-02-22.eval.txt)

## Benchmarks

| testset | BLEU  | chr-F | #sent | #words | BP |
|---------|-------|-------|-------|--------|----|
| euelections_dev2019.de-fr.deu-fra 	| 32.5 	| 0.595 	| 1512 	| 38376 	| 0.965 |
| newssyscomb2009.deu-fra 	| 26.8 	| 0.556 	| 502 	| 12334 	| 0.985 |
| news-test2008.deu-fra 	| 26.6 	| 0.551 	| 2051 	| 52685 	| 0.989 |
| newstest2009.deu-fra 	| 25.2 	| 0.538 	| 2525 	| 69278 	| 0.968 |
| newstest2010.deu-fra 	| 29.5 	| 0.579 	| 2489 	| 66043 	| 1.000 |
| newstest2011.deu-fra 	| 27.3 	| 0.557 	| 3003 	| 80626 	| 0.978 |
| newstest2012.deu-fra 	| 27.5 	| 0.556 	| 3003 	| 78011 	| 1.000 |
| newstest2013.deu-fra 	| 29.7 	| 0.564 	| 3000 	| 70037 	| 0.975 |
| newstest2019-defr.deu-fra 	| 36.2 	| 0.631 	| 1701 	| 42530 	| 0.957 |
| Tatoeba-test.deu-fra 	| 49.2 	| 0.665 	| 10000 	| 81669 	| 0.982 |

