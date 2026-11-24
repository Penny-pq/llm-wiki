# Token、Tokenizer 與 Embedding

## 1. Token 是什麼？
Token（詞元／符記）是模型處理文字時使用的基本單位。它可能是一個字、完整單字、標點符號，也可能是單字的一部分（子詞）。因此，一個單字不一定只對應一個 token。

## 2. Tokenizer 做什麼？
Tokenizer（分詞器／詞元化器）負責依照模型使用的規則，把文字轉成 token 序列；模型處理完成後，再把輸出 token 轉回可閱讀文字。

## 3. Embedding 是什麼？
Embedding（嵌入）是把 token 或其他資料項目轉換成數值向量的表示方式。模型透過訓練學到向量中的數值關係，使某些有關聯的項目在表示空間中呈現相似性。向量的每個維度通常不應直接解讀成一個人類可命名的特徵。

## 4. 簡化流程
文字 → Tokenizer → Token ID → Embedding 向量 → 模型處理。

## 常見誤解
- Token 不等於「字數」。
- Embedding 不是把文字翻譯成另一種語言，而是轉成模型可運算的數值表示。
- 不同模型的 tokenizer 可能不同。

## 來源
S3、S4、S1。詳見 [來源登錄](../sources/README.md)。
