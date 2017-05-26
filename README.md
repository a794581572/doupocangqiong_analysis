# doupocangqiong\_analysis

网络小说<斗破苍穹>的一个简单的分词与分析，是我学习Python的一个简单的练习。

## 内容分三个文件，分别是分词部分，按照类别对词的分析，以及按照词性的一个分析。
- 首先在doupo\_fenci里面，实现了使用jieba对小说的分词。
  - 运行jieba\_doupo.py可以对全文分词.
  - 运行jieba\_cixing.py可以对小说分词同时写入.
  - 词性分词后会产生一个words\_list.txt的文件
  - 这个文件是后面两个分析的基础文件，应该把这个文件拷贝到另外两个文件夹里。
- 然后在doupo_analysis里有初步的分析。
  - 第一个分析是对所有的词做一个词频的分析
  - 第二个分析是对具体的类别做的分析.
  - 他们运行的基础都是words_list.txt这个文件
- 最后是一个词性分析的demo，在doupo\_cixing里，按照形容词做了一个分析，这里要求分词文件word\_list.txt是运行了jieba\_fenci里的jieba\_cixing.py的结果