# 《统计数据挖掘》课程材料说明 - README

## 材料概述  
本tutorial均为我在编写，作为研究生级别《统计数据挖掘》的配套教学材料，涵盖数据挖掘全流程（问题定义、数据清洗、EDA、特征工程、建模评估、优化与应用、结果呈现），通过11个实际案例帮助学生掌握分类、聚类等数据挖掘核心算法。所有案例均基于Python技术栈（numpy/pandas/sklearn/Matplotlib）实现，并包含完整数据集，代码与文档。

---

## 案例研究列表：

### 1. **Case study1: 大学入学计划建模（决策树）**  
- **问题**：通过决策树模型预测学生大学入学选择。  
- **算法**：决策树  
- **文件**：  
  - `Case study1...DecisionTree/`：代码、数据集
  - `Case study1...DecisionTree.pdf`：完整报告

### 2. **Case study2: 信用风险管理（决策树）**  
- **问题**：评估贷款申请人的信用风险。  
- **算法**：决策树  
- **文件**：  
  - `CaseStudy2...DecisionTree/`
  - `CaseStudy2...DecisionTree.pdf`

### 3. **Case study3: 合同续约预测（k-NN & 朴素贝叶斯）**  
- **问题**：预测用户合同续约意愿。  
- **算法**：k近邻（k-NN）、朴素贝叶斯  
- **文件**：  
  - `Case study3&4...models/`
  - `Case study3&4...models.pdf`

### 4. **Case study5: 意大利葡萄酒分类（SVM）**  
- **问题**：基于化学成分对葡萄酒产地分类。  
- **算法**：支持向量机（SVM）  
- **文件**：  
  - `Case study5...SVMs/`
  - `Case study5...SVMs.pdf`

### 5. **Case study6: 房产所有权分类（逻辑回归）**  
- **问题**：预测个人是否拥有房产。  
- **算法**：逻辑回归  
- **文件**：  
  - `Case study6...LogisticRegression/`
  - `Case study6...LogisticRegression.pdf`

### 6. **Case study7: 大学入学计划建模（随机森林）**  
- **问题**：对比随机森林与决策树的性能差异。  
- **算法**：随机森林  
- **文件**：  
  - `Case study7...RandomForest/`
  - `Case study7...RandomForest.pdf`

### 7. **Case study8: 电影推荐（奇异值分解）**  
- **问题**：构建用户电影推荐系统。  
- **算法**：奇异值分解（SVD）  
- **文件**：  
  - `Case study8...Decomposition/`
  - `Case study8...Decomposition.pdf`

### 8. **Case study9: 电信套餐定制（k-means）**  
- **问题**：用户分群以实现套餐个性化推荐。  
- **算法**：k-means聚类  
- **文件**：  
  - `Case study9...K-means/`
  - `Case study9...K-means.pdf`

### 9. **Case study10: 用户高频活动区域挖掘（DBSCAN）**  
- **问题**：识别用户常驻区域。  
- **算法**：DBSCAN  
- **文件**：  
  - `Case study10...DBSCAN/`
  - `Case study10...DBSCAN.pdf`

### 10. **Case study11: 基站数据商业区挖掘（层次聚类）**  
- **问题**：基于基站数据划分商业区。  
- **算法**：层次聚类  
- **文件**：  
  - `Case study11...Clustering/`
  - `Case study11...Clustering.pdf`

---

## 其他材料  
### 考试与练习  
- `Exam_Final_Ans.pdf`：期末考题&参考答案
- `Exam_Mid-term_Ans.pdf`：期中考试&参考答案
- `Exercise1Classification.pdf`：分类算法练习题&参考答案

### 教程材料  
- `Tutorial1DataType...similarity.pdf`：数据质量与相似度计算教程
- `Tutorial2...Clustering/`：k-means算法复习代码
- `Tutorial2...Clustering.pdf`：聚类算法总结
- `Tutorial6...algorithms.pdf`：分类算法综述

---

## 文件结构说明  
- **每个案例包含两个部分**：  
  1. **文件夹**：存放Python代码、数据集、中间结果及可视化图表。  
  2. **PDF文稿**：详细说明问题背景、方法实现、结果分析与应用建议。  
---

## 技术与工具  
- **环境**：Python3.7
- **库**：numpy、pandas、sklearn、Matplotlib
- **算法覆盖**：分类、聚类、降维、推荐系统  

---