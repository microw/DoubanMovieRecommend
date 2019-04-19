# DoubanMovieRecommend
对豆瓣电影的简单推荐，利用简单的深度学习，构建全连接网络，提取电影和用户的embedding特征，计算相似性进行推荐。
# Code
crawler.py：对豆瓣网站的电影和用户数据爬取，利用beautifulsoup和requests基础库。
data_util.py：对爬取到的数据进行清洗，并简单提取用于训练的特征矩阵。
visual.py：对清洗之后的数据进行简单的可视化。
models.py：建立神经网络模型，分为电影模型和用户模型，利用回归问题训练得到电影和用户的embedding特征。
recommend.py：利用embedding特征计算电影和用户相似性，并给出简单的推荐策略。
# 本次实验也是本人对推荐相关问题的首次尝试，效果不尽如人意，以后还会多多学习。
