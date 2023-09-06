# 中国矿业大学Beamer模板(CUMT-Beamer-Template)

- 本Beamer模板基于 [UESTC-Beamer](https://www.overleaf.com/latex/templates/uestc-beamer-theme/ybqzdsgvrfdq)修改而来，旨在帮助矿大师生高效完成答辩、组会等幻灯片制作
- 除基于tex的Beamer模板之外，在ppt文件夹中提供了一个ppt版本，可使用PowerPoint实现所见即所得的编辑
- 欢迎大家提交pr和issue一起完善~

## 主题预览

### latex版

![CUMT_Beamer_Theme_页面_01](https://lgy0404.oss-cn-shanghai.aliyuncs.com/typoraCUMT_Beamer_Theme_%E9%A1%B5%E9%9D%A2_01.jpg)

![CUMT_Beamer_Theme-1_页面_1](https://lgy0404.oss-cn-shanghai.aliyuncs.com/typoraCUMT_Beamer_Theme-1_%E9%A1%B5%E9%9D%A2_1.jpg)

![CUMT_Beamer_Theme-1_页面_2](https://lgy0404.oss-cn-shanghai.aliyuncs.com/typoraCUMT_Beamer_Theme-1_%E9%A1%B5%E9%9D%A2_2.jpg)

### ppt版

![](https://lgy0404.oss-cn-shanghai.aliyuncs.com/typora%E4%BB%BF%E7%85%A7Beamer%E5%AE%9E%E7%8E%B0%E7%9A%84PPT%E7%89%88%E6%A8%A1%E6%9D%BF-%E8%AF%B7%E5%85%88%E5%AE%89%E8%A3%85%E5%AD%97%E4%BD%93.jpg)

## latex版使用说明

### 编译环境设置

- 编译器选择 `XeLaTeX` 
- 主文件为 `slide.tex`

![image-20230904201347448](https://lgy0404.oss-cn-shanghai.aliyuncs.com/typoraimage-20230904201347448.png)



### 比例修改

- 支持4:3和16:9，默认比例为4:3
- 在`slide.tex`首行中将 `\documentclass{beamer}` 注释掉，并取消 `%\documentclass[aspectratio=169]{beamer}` 的注释即可

### 更新计划

- 支持标题行加粗
- 支持不同的字体
- 支持不同的主题颜色

## ppt版使用说明

### 字体支持

- 如果使用ppt版，请先安装 `.\ppt\fonts` 路径下的字体

---

❤️对你有帮助的话点个star吧~❤️