# Pet-projects with transformer architecture for NLP tasks
![image](transformers.png)

## Implemented projects
1) <b>[Implementation transformer model](https://github.com/Arseny5/nlp-personal-projects/tree/main/01-implement-vanilla-transformer):</b>
   - Implementation vanilla transformer from encoder-decoder classes to positional encoding, self-attention, multi-head attention, feed-forward network, residual connections and layer normalization.
   - Using [WMT 2014](https://huggingface.co/datasets/wmt14) English-German and English-French datasets solve text translation problem.
   - Analyze Label Smoothing in transformer with KLDiv loss.
   - Using [Tatoeba Russian-English](https://huggingface.co/datasets/tatoeba) dataset solve text translation problem.
3) <b>[BERT analyzing](https://github.com/Arseny5/nlp-personal-projects/tree/main/02-bert-models-analyze):</b>
   - Work with Byte-pair-encoding and Word-piece tokenizers.
   - Visualization of the token relationship inside BERT-model using bertviz.
   - Сlassification of [restaurant reviews](https://huggingface.co/datasets/blinoff/restaurants_reviews/resolve/main/restaurants_reviews.jsonl) using ruBert-base finetune model.
4) <b>[NER-problem with BERT](https://github.com/Arseny5/nlp-personal-projects/tree/main/03-bert-for-NER):</b>
   - Using [rubert-tiny2](https://huggingface.co/cointegrated/rubert-tiny2) work with Named Entity Recognition on [Russian Drug Reaction Corpus](https://github.com/cimm-kzn/RuDReC).
   - Use [Seqeval](https://github.com/chakki-works/seqeval) framework to compute metrics.
   - Freeze layers in rubert-tiny2 and fine-tune model.
