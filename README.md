# SEM Track_Minspore
本代码利用mindspore框架实现了SEM Track攻击

## 依赖
* 硬件：Atlas 800/Atlas 800T A2
* MindSpore：2.2.13
* CANN: 7.0
* MindFormers版本：1.0

## 攻击数据集
  数据通过MindFormers llama7b模型，在alpaca_data上推理，收集第0层LLamaDecoderlayer输入输出10000条制作SEM Track数据集

## 运行SEM攻击
