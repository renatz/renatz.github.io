---
permalink: /project/
title: "Recent Project"
---
## 闲聊机器人大头
本机器人原型为网红猫大头，作者非常喜欢头宝，并尝试模拟它的性格，以陪伴广大社恐！

<!-- <img src="assets/image-20230211025917123.png" alt="image-20230211025917123" style="zoom:50%;" /> -->
![image-20230211025917123](assets/image-20230211025917123.png)

### 1. 预览

#### 1.1 首页

![首页](assets/首页.jpg)

#### 1.2 聊天页面

##### 1.2.1 注册用户

![image-20230224014850637](assets/image-20230224014850637-16771757580111.png)

##### 1.2.2 游客

![image-20230224032738972](assets/image-20230224032738972.png)

#### 1.3 个人中心及聊天记录

![image-20230224020408663](assets/image-20230224020408663-16771757580112.png)

![image-20230224201941788](assets/image-20230224201941788.png)

### 2.  技术栈

- os：ubuntu
- 版本控制：git
- 算法框架：pytorch + numpy + jieba + sklearn + matplotlib 
- 后端框架：django + drf + cors
- 前端框架：vue + elementui + axios
- 异步框架：celery
- 数据库：mysql
- 中间件：redis

### 3.  模型架构
- v1.0：纯手撕的seq2seq模型(gru + luong attention的general attention + SgdM)

- v2.0：fine-tune预训练模型的seq2seq模型 + AdamW
  - encoder：q —— bert、transformer_encoder  —— q_embedding —— gru —— q_output
  - decoder：a —— gru —— a_embedding —— transformer_decoder、gpt2 ——  a_output

- v3.0：基于CDialGPT的受控对话模型 + AdamW
  - 待优化
  - 参考：https://arxiv.org/pdf/1911.04700.pdf

### 4.  项目架构

- 整体架构

<!--   <img src="assets/整体架构.png" alt="整体架构" style="zoom:50%;" /> -->
  ![整体架构](assets/整体架构.png)

- 算法架构

<!-- <img src="assets/算法架构.png" alt="算法架构" style="zoom:50%;" /> -->
  ![算法架构](assets/算法架构.png)

- 后端架构

<!-- <img src="assets/后端架构.png" alt="后端架构" style="zoom:50%;" /> -->
  ![后端架构](assets/后端架构.png)

- 前端架构

<!-- <img src="assets/前端架构.png" alt="前端架构" style="zoom:50%;" /> -->
 ![前端架构](assets/前端架构.png)

