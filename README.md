# want -- what we want to do?
金融行业的应用有哪些顶层要求？通过技术语言描述一个总体的API模型。

### 面向金融行业的应用
源于对金融行业的业务理解,适应互联网金融发展方向
### 顶层
自顶向下的设计  
来自“用户”所提出的要求  
参考互联网企业分享的经验  
提出一种要求的实现方向  
### 总体
包括场景，业务，应用，基础设施各层次的要求
不涉及应用内部的模型，子系统模型
### 模型
* 技术地图  
表达总体印象，帮助定位问题
作为服务治理的总体蓝图
* 模块边界  
提出一种应用系统切分的方案，并可作为其依据
* 实现的依据  
接口模型可直接用于对接应用实现
也可在兼容的情况下通过简便的适配器对接现存的应用、工具


# 谁是“用户”
1. 人
    1. 目标用户群
    1. 管理者
2. 应用
    2. 第三方应用
    如银联
    2. 内部依赖方
    如渠道之于核心，视图层之于控制层
    
