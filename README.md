# Anomaly_Detection
***时空异常检测（Spatio-Temporal Anomaly Detection） paper1: 车联网异常检测及数据恢复技术研究 &amp; paper2: 无线传感器网络节点软故障检测与处理技术研究***

---

### File Information
1. **"车联网异常检测及数据恢复技术研究_张倩.pdf"** 复现的第一篇文章，本项目复现其中第四节的算法《基于时空相关性组合模型的异常检测及数据修复》。
2. **"无线传感器网络节点软故障检测与处理技术研究_支寒晓.pdf"** 复现的第二篇文章，本项目复现其中第三节的算法《基于时空相关性的节点故障检测算法》。
3. **"AirQualityUCI.xlsx"** 复现文章一的数据。
4. **"my_data.xlsx"** 复现文章二的数据。
5. **"时空异常检测.ipynb"** 复现文章一的代码。
6. **"时空异常检测2.ipynb"** 复现文章二的代码。

### Methods Description
#### 复现文章一的思路：
1. 随机注错，待研究的错误率5% 10% 15% 20% ～ 40%，其余错误率5%
2. 计算待研究数据滞后1-5期的自相关系数
3. 计算彼此之间的pearson系数，以及对应的双侧显著性
4. 划分训练集测试集，前90%做训练，后10%做测试
5. 确定超参数，平滑系数设置0.5，最优阈值由置信区间法来定
6. 检测结果如下所示

![out](https://github.com/ArcherCYM/Anomaly_Detection/assets/49087999/af7b525c-0d62-419c-a34c-0950f501e55e)

#### 复现文章二的思路：
1. 随机注错，错误的位置和数值随便选 待研究的错误率5% 10% 15% 20% ～ 40%，其余错误率5%
2. 自我检测
3. 相似性检测

---

### Tips
*If you have any problem, you can send an email archercym@gmail.com or make an issue directly. We can discuss together.*
