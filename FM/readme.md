1. fm_numpy是ipython文件，单步执行，具体看fm是如何进行预测的
2. fm_tensorflow_movielens文件使用movielens100k的数据进行预测，使用了最基本的one-hot编码
3. fm文件是用自己的数据集就行实验，因为自己的数据集特征太多，直接使用one-hot编码运行时会过载，因此对特征建立字典进行提取
