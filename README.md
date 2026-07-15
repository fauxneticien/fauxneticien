### Nay San

Staff Engineer at [rime](https://rime.ai), working on data and modelling for
conversational voice AI. Previously a PhD in Linguistics at Stanford (advised by
[Dan Jurafsky](https://web.stanford.edu/~jurafsky/)), on improving access to
untranscribed speech corpora with AI.

More at [resunay.com](https://resunay.com) ·
[Google Scholar](https://scholar.google.com/citations?user=z_KqSbwAAAAJ&hl=en)

---

**Speech: search and low-resource ASR**
- [qbe-std_feats_eval](https://github.com/fauxneticien/qbe-std_feats_eval) — evaluation of feature-extraction methods for query-by-example spoken term detection in low-resource languages
- [bnf_cnn_qbe-std](https://github.com/fauxneticien/bnf_cnn_qbe-std) — query-by-example spoken term detection using bottleneck features and a CNN
- [u2u-asr](https://github.com/fauxneticien/u2u-asr) — "user-to-user" ASR: a proof-of-concept workflow taking users from their own data to a fine-tuned model they can run locally in the browser (a play on "end-to-end ASR")
- [active_learning-w2v2_asr](https://github.com/fauxneticien/active_learning-w2v2_asr) — active learning for fine-tuning wav2vec 2.0 ASR
- [asr-dataset-prep](https://github.com/fauxneticien/asr-dataset-prep) — scripts for preparing datasets for automatic speech recognition

**Cross-lingual and self-supervised speech models**
- [w2v2-cpt-transfer](https://github.com/fauxneticien/w2v2-cpt-transfer) — predicting positive cross-lingual transfer for low-resource ASR; introduces Acoustic Token Distribution Similarity (ATDS)
- [fastconformer_standalone](https://github.com/fauxneticien/fastconformer_standalone) — extracting NeMo's FastConformer into a clean, dependency-free PyTorch model class for experimentation
- [scriptable_hubert_encoder](https://github.com/fauxneticien/scriptable_hubert_encoder) — a scriptable HuBERT encoder for testing "cramming" strategies to cut low-resource pretraining compute
- [wav2vec2-codebook-indices](https://github.com/fauxneticien/wav2vec2-codebook-indices) — a playground for extracting wav2vec 2.0 quantizer codebook indices
- [w2v2-fairseq-pretrain](https://github.com/fauxneticien/w2v2-fairseq-pretrain) — wav2vec 2.0 XLS-R continued pretraining with fairseq
- [w2v2-hf-pretrain-test](https://github.com/fauxneticien/w2v2-hf-pretrain-test) — testing wav2vec 2.0 pre-training with HuggingFace
- [w2v2-10min-exps](https://github.com/fauxneticien/w2v2-10min-exps) — experiments training wav2vec 2.0 with only 10 minutes of transcribed speech
- [w2v2-10min-replication](https://github.com/fauxneticien/w2v2-10min-replication) — replicating the 10-minute LibriSpeech training run
- [ssl-harness](https://github.com/fauxneticien/ssl-harness) — a lightweight harness for evaluating self-supervised speech models (mainly HuBERT)
- [lightning-speech-sampling](https://github.com/fauxneticien/lightning-speech-sampling) — trying out samplers for speech data with PyTorch Lightning

**Phonetics and phonology**
- [phonpack](https://github.com/fauxneticien/phonpack) — an R package of fun(ctions) for doing phonetics
- [kphon](https://github.com/fauxneticien/kphon) — helper functions for the Kaytetye Phonological project (KPHON)
- [kaytetye-medial-vowels](https://github.com/fauxneticien/kaytetye-medial-vowels) — processing scripts and datasets for a study of medial vowels in Kaytetye
- [akwelye](https://github.com/fauxneticien/akwelye) — text-setting in akwelye (Kaytetye song)
- [census-languages](https://github.com/fauxneticien/census-languages) — analysis of ABS Census data on Australian Indigenous languages

**Lexicography and dictionaries**
- [lexloop](https://github.com/fauxneticien/lexloop) — iterative correction tool for data in a domain-specific language: edit a file, re-run, see validation and parsed views in the browser
- [lexicon-grammars](https://github.com/fauxneticien/lexicon-grammars) — a collection of grammars for parsing backslash-coded lexicons
- [LexDev](https://github.com/fauxneticien/LexDev) — a toolkit for generating live feedback on lexicographical data
- [kdict](https://github.com/fauxneticien/kdict) — data-processing functions for the Kaytetye Dictionary Transcriptions project
- [anamR](https://github.com/fauxneticien/anamR) — helper functions to read/write/process data from the Kaytetye database (KDB)
