# Transformer 與自注意力

## 1. Transformer 是什麼？
Transformer 是一種神經網路架構。2017 年論文《Attention Is All You Need》提出以 attention 為核心的 Transformer，展示它在機器翻譯任務上的效果。後來 Transformer 成為許多大型語言模型的重要架構基礎。

## 2. 自注意力（Self-attention）
自注意力讓模型在處理序列中某個 token 時，參考同一序列中其他 token 的資訊，依相關程度整合上下文。這有助於模型處理詞語在不同語境中的意思。

例如「蘋果放在桌上」與「我用蘋果手機」中的「蘋果」，周圍文字提供不同脈絡。自注意力是模型學習利用上下文的一種機制；這個例子是直觀說明，不是完整數學運算。

## 3. Encoder 與 Decoder
Transformer 架構可依任務採用 encoder、decoder，或兩者組合。不是每個 Transformer 模型都一定同時具備兩者。許多文字生成模型採用 decoder-only 設計。

## 來源
S2、S5、S3。詳見 [來源登錄](../sources/README.md)。
