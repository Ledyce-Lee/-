### 机器学习大作业代码+数据
### 0. python版本为3.11；所需依赖包括os、re、collections、pkuseg、transformers、torch、numpy、pandas、tqdm
### 1. 主程序：main.ipynb
### 2. 数据集与分词后的字典变量较大，见百度网盘：
- 通过网盘分享的文件：机器学习附件
链接: https://pan.baidu.com/s/1f2KLesRqFjo9lCxqmo31tg?pwd=2025 提取码: 2025 
--来自百度网盘超级会员v4的分享
### 3. main.ipynb中的分词环节所需时长约为40min，因此我将分词后生成的字典变量以numpy文件储存，第二次运行时无需重复进行分词步骤，可以直接用numpy库load该文件，即运行loaded = np.load("my_file.npy", allow_pickle=True)，随后可进行后续步骤，如不慎将my_file.npy文件覆盖，会导致后续步骤报错，请从网盘重新下载。
### 4. 代码无需特别修改可在mac上运行，如欲在windows上运行，注意修改年报文本文件夹路径
