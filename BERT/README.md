■BERTによる自然言語処理


```
自然言語処理の学習
・トークン化と前処理（単語分割、文字分割、サブワード分割）
・Word2Vec（CBOW, Skip-Gram）
・ELMo（LSTM）

BERTの基礎
・BERTの構造（Scaled Dot-Product Attention, Multi-Head Attention, Residual Connection, Layer Normalization, Feedforward Network）
・入力形式（トークン化、ベクトル形式）
・学習（事前学習、ファインチューニング）

Huggingface Transformers
・transformers（トークナイザ、BERTモデル）

BERT実装
・BERTによる文章の穴埋め実装
・livedoorニュースコーパスを用いた文章分類の実装
（データローダ、データの前処理、PyTorch Lightningによるファインチューニングとテスト、ファインチューニングしたモデルの保存と読み込み）
・BERTによるマルチラベル文章分類（データセット：chABSA-dataset、ファインチューニングと性能評価）
・固有表現抽出（IO法の実装、BIO法の実装）
・文章校正（データセット：日本語Wikipedia入力誤りデータセット）
・文章ベクトルを用いたデータの可視化と類似文章検索
（データセット：livedoorニュースコーパス、文章コーパスの可視化（主成分分析、t-SNE）、類似文章検索）
```
