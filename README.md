# Words Spelling Correction using Char2Vec

We build Words Spelling Correction using Char2Vec that follow [https://github.com/dogterbox/word-spelling-correction-char2vec](https://github.com/dogterbox/word-spelling-correction-char2vec) for [issue 1075](https://github.com/PyThaiNLP/pythainlp/issues/1075).


We use the Thai words from Royal Society of Thailand by pythainlp.corpus.thai_orst_words.


Steps:

1. download.ipynb: Download dict
2. build-dict.ipynb: build data to train
3. build model in build-model.ipynb
4. usage.ipynb
5. export-model.ipynb: export to onnx model
6. use-onnx.ipynb
7. usage-onnx.ipynb