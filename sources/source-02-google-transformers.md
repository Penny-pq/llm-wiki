# LLMs: What's a large language model?（Google Machine Learning Crash Course）

- 發布者：Google for Developers
- 年份／查閱日期：線上教材；查閱日期 2026-11-24
- 原始網址：https://developers.google.com/machine-learning/crash-course/llm/transformers

## 摘要筆記
- Transformer 是現代許多 LLM 採用的重要神經網路架構。
- Self-attention（自注意力）讓模型在處理序列時，依上下文調整不同 token 對目前表示的影響。
- Encoder（編碼器）與 Decoder（解碼器）是 Transformer 常見元件；不同模型可能採用 encoder-only、decoder-only 或 encoder-decoder 設計。
- LLM 可能產生幻覺，也可能帶有偏誤；訓練與推論都會消耗運算資源。
## 可支持的簡報內容
Transformer、自注意力、編碼器／解碼器、LLM 的限制。
## 使用提醒
不可說所有 Transformer 都同時包含 encoder 與 decoder；架構依模型設計而異。
