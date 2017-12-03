
# word2vec
# 完整版
* Medium： [自然語言處理入門- Word2vec小實作](https://medium.com/pyladies-taiwan/%E8%87%AA%E7%84%B6%E8%AA%9E%E8%A8%80%E8%99%95%E7%90%86%E5%85%A5%E9%96%80-word2vec%E5%B0%8F%E5%AF%A6%E4%BD%9C-f8832d9677c8)

# 實作流程
1. 在 terminal 進行套件安裝以及下載資料格式檔案轉換 (若已有現成文本可略過) 
2. 在 jupyter notebook 透過 jieba套件斷詞，再經由 word2vec 萃取文章特徵，轉換成以向量空間表示的詞向量
3. 視覺化呈現相近詞向量之結果
---

## 本次使用資料集
- 搜狗實驗室的新聞文本 (完整版648MB、tar.gz格式)；當然你也可以使用迷你版(110KB)，但要記得下載tar.gz格式的資料集，因示範程式碼是以此格式做清理。
[下載連結](http://www.sogou.com/labs/resource/cs.php)
- 本次將簡體文本以三種方式實現：繁體中文版，簡體中文版、繁體中文_small_sample版



## 會使用到的套件
- jieba
- sklearn
- matplotlib
- numpy
- hanziconv
- 須下載可呈現中文字的[支援文件](https://github.com/sebastianbergmann/phpunit-documentation/blob/master/build/fonts/wqy-microhei/wqy-microhei.ttc)
