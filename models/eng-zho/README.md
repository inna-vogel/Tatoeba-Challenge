# opus-2020-07-14.zip

* dataset: opus
* model: transformer
* source language(s): eng
* target language(s): cjy_Hans cjy_Hant cmn cmn_Hans cmn_Hant gan lzh lzh_Hans nan wuu yue yue_Hans yue_Hant
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* download: [opus-2020-07-14.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-zho/opus-2020-07-14.zip)
* test set translations: [opus-2020-07-14.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-zho/opus-2020-07-14.test.txt)
* test set scores: [opus-2020-07-14.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-zho/opus-2020-07-14.eval.txt)

## Benchmarks

| testset               | BLEU  | chr-F |
|-----------------------|-------|-------|
| Tatoeba-test.eng.zho 	| 31.1 	| 0.265 |

# opus-2020-07-17.zip

* dataset: opus
* model: transformer
* source language(s): eng
* target language(s): cjy_Hans cjy_Hant cmn cmn_Hans cmn_Hant gan lzh lzh_Hans nan wuu yue yue_Hans yue_Hant
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* download: [opus-2020-07-17.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-zho/opus-2020-07-17.zip)
* test set translations: [opus-2020-07-17.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-zho/opus-2020-07-17.test.txt)
* test set scores: [opus-2020-07-17.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-zho/opus-2020-07-17.eval.txt)

## Benchmarks

| testset               | BLEU  | chr-F |
|-----------------------|-------|-------|
| Tatoeba-test.eng.zho 	| 31.4 	| 0.268 |

# opus-2021-02-23.zip

* dataset: opus
* model: transformer
* source language(s): eng
* target language(s): cjy cmn gan hak hsn lzh nan wuu yue
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* valid language labels: >>cmn_Hans<< >>cmn_Hant<< >>cmn<< >>yue_Hant<< >>yue_Hans<< >>nan<< >>wuu<<
* download: [opus-2021-02-23.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-zho/opus-2021-02-23.zip)
* test set translations: [opus-2021-02-23.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-zho/opus-2021-02-23.test.txt)
* test set scores: [opus-2021-02-23.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-zho/opus-2021-02-23.eval.txt)

## Benchmarks

| testset | BLEU  | chr-F | #sent | #words | BP |
|---------|-------|-------|-------|--------|----|
| Tatoeba-test.eng-zho 	| 31.6 	| 0.267 	| 9999 	| 110463 	| 0.911 |

