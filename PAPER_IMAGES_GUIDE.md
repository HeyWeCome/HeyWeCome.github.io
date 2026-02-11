# 论文图片放置指南

## 图片目录结构

请将论文预览图片放置在以下目录：
```
assets/img/publication_preview/
```

## 推荐的图片命名方案

为每篇论文准备一张预览图片，建议使用以下命名：

1. **interest-hd-model.jpg** - 对应TNNLS论文 "Interest HD: An Interest Frame Model for Recommendation Based on HD Image Generation"
2. **information-diffusion-pmrca.jpg** - 对应SIGIR论文 "A Pattern-Driven Information Diffusion Prediction Model Based on Multisource Resonance and Cognitive Adaptation"  
3. **behavioral-intention-foundation.jpg** - 对应Information Fusion论文 "Towards a foundation model for behavioral intention prediction through multi-source data fusion"
4. **dynamic-cognition-tcss.jpg** - 对应TCSS论文 "An Information Diffusion Prediction Model Aligning Multiple Propagation Intentions With Dynamic User Cognition"
5. **temporal-evolution-tcss.jpg** - 对应TCSS论文 "Disentangling Temporal Evolution in Frequency Domain for Sequential Recommendation"

## 图片规格建议

- **格式**: JPG 或 PNG
- **尺寸**: 建议 800×600 像素或类似比例
- **大小**: 每张图片不超过 500KB
- **内容**: 可以是论文的关键图表、模型架构图、实验结果图或相关示意图

## 替代方案

如果不想使用预览图片，也可以：

1. **删除preview字段** - 论文将只显示文本信息
2. **使用HTML页面** - 为每篇论文创建详细页面，在BibTeX中使用 `html` 字段指向对应页面

## 注意事项

- 图片文件名必须与BibTeX中的preview字段完全匹配
- 图片会自动在出版物页面上显示
- 支持响应式设计，图片会在不同设备上自适应显示