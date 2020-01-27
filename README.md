# poems-generator
这个例子可以用LSTM来写五言诗，同时也可以写藏头诗。  

# 使用方法
1、利用poem_keras.py可以训练模型。  

2、利用predict.py可以进行预测。  
下面这段代码用于随机生成诗词：  
predict_from_nothing(0,x_data,char2id_dict,id2char_dict,model)  
下面这段代码用于生成藏头诗：  
predict_from_head("快乐",x_data,char2id_dict,id2char_dict,model)  
# 效果
随机生成诗词：  
木落识岁秋，鹤声徒尘毕。句衾莫刻清，自洗如是薪。  
藏头诗：  
快慕双王女，乐吟七女歌。欠衰春满酒，童稚李临田。
