# BaiduNer2020
2020语言与智能技术竞赛：关系抽取任务

比赛页面: https://aistudio.baidu.com/aistudio/competition/detail/31

前两个文件在对model进行练习和尝试，不供参考。04才是完整的pipeline

Moedl: BERT + LSTM + FullConnect (Tensorflow(2.x) + HuggingFace) 

自己电脑显存仅有6G，加载不了BERT，故使用Colab GPU

TPU的话必须存放数据在谷歌的某个存储服务中(very expensive)，代码里也有使用TPU代码，但启动时发现有雷

第一次训练到epoch16后Colab就down了性能，model未拟合，故也未做蒸馏，结果丢人，此经历仅当个人学习历程
