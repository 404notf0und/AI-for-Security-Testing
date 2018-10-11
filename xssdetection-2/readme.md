文件目录结构为：
数据集：
./data 

分词：
utils.py

word2vec训练字典：
word2vec_gensim.ipynb

训练得到的字典及降至二维可是化图：
./file/word2vec.pickle
./file/word2vec.png	

批训练、5000数据正常训练及预测：
xssdetection_batch_trainning.ipynb
xssdetection_trainning.ipynb
./file/xss_lstm.h5	批训练模型
./file/xss_lstm_5000 5000	数据训练模型
./file/pre_datas_train.csv	训练数据向量化的文件
./file/pre_datas_test.csv	测试数据向量化的文件

批测试和5000数据正常测试：
xssdetection_testing.ipynb
