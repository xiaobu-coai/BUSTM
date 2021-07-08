# 小布助手对话短文本匹配数据集（BUSTM）

本数据集来自于OPPO小布助手。小布助手是OPPO公司为旗下多种品牌手机和IoT智能设备研发的智能助手，为上亿用户提供便捷的对话式服务。

意图识别是对话系统中的核心任务，而对话短文本语义匹配是意图识别的主流算法方案之一，在实际业务应用中会面临有监督样本不足等问题，迫切需要小样本条件下关键算法模型的突破。基于这个目的，特开放此数据集，希望能和业界同行一起促进相关算法技术的发展。

对话段文本语义匹配任务要求根据短文本query-pair，预测它们是否属于同一语义。

数据量：训练集（32），验证集（32），公开测试集（1772），测试集（2000），无标签语料（4251）
距离：
{"id": 5, "sentence1": "女孩子到底是不是你", "sentence2": "你不是女孩子吗", "label": "1"}
{"id": 18, "sentence1": "小影,你说话慢了", "sentence2": "那你说慢一点", "label": "0"}

## 数据链接
该数据集是[FewCLUE](https://github.com/CLUEbenchmark/FewCLUE)评测基本的子任务之一，数据可以在以下链接下载：

[https://github.com/CLUEbenchmark/FewCLUE/tree/main/datasets/bustm](https://github.com/CLUEbenchmark/FewCLUE/tree/main/datasets/bustm)

## 引用
@misc{BUSTM,
  title={BUSTM: OPPO XiaoBu Dialogue Short Text Matching Dataset},
  author={OPPO XiaoBu Conversational-AI Center},
  year={2021},
  howpublished={\url{https://github.com/xiaobu-coai/BUSTM}},
}

