刘泓尊  计84 Word2vec(Python)

1.word2vec.py中定义了Word2Vec类，test.py中使用该模块进行训练，并使用gensim的接口进行准确度验证。
2.参数设置:size = 300, window = 6, min_count = 6, iter = 20, threads = 12, negative = 5, hs = 0, sample = 1e-3, cbow, alpha = 0.025

3.训练效果：
使用dataset.txt(2GB)（https://cloud.tsinghua.edu.cn/f/86914550920f4719b499/）进行训练
得到的词向量在output.txt中（放在云盘https://cloud.tsinghua.edu.cn/f/e264e54210e24196ab0e/）
词汇文件在vocab.txt中

测试结果：
Google Analogy: 0.6548512523736323, 具体结果在questions-words-result.txt中
wordsim-353: 0.6438742114261823，具体结果在simlilarity-result.txt中

