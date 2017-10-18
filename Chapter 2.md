# Chapter 2 - Data Representation
# 第3章 数据储存

英语教材与中文教材在本章略有不同。

## 生词

生词表：[FoCS C2](https://www.vocabulary.com/lists/1892630)

algebraic, trigonometric, intensity, grainy, decompose, curve, coordinate, quantization, prone

## 位模式（Bit Pattern）

位模式（0和1的序列）统一了数据在计算机内部的表现形式。位（比特，bit）是能储存在计算机中的最小数据类型。通常，8位是1字节（byte）。

## 常见字符编码

编码一个字符需要的比特数由语言符号的数量决定，假设语言符号有n种，那么至少需要log₂n个比特的组合来表示这种语言。

- **美国标准信息交换码（ASCII，American Standard Code for Information Interchange）** 由ANSI（American National Standards Institude）开发，使用7个比特来表示英语符号。**大写字母在小写字母前**，大写字母与对应的小写字母只在**尤其第六位**（即权重2^5位置）不同。
- **拓展的美国标准信息交换码（Extended ASCII）** 使用8个比特来表示语言符号。
- **EBCDIC（Extended Binary Coded Decimal Interchange Code）** 使用8个比特的组合来表示语言符号。
- **Unicode** 使用16个比特的组合来表示语言符号。
- **ISO（International Organization for Standardization）** 使用32个比特的组合来表示语言符号。

## 图像表示

基本概念：光栅图（位图，bitmap） 矢量图（vector） 像素（pixel） 分辨率（resolution） 灰度（gray scale）

## 音频表示

基本概念：模拟信号（analog） 数字信号（digital） 采样（sampling） 量化（quantization）
