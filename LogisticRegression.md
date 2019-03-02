## 1. 逻辑回归与线性回归的联系与区别
方法 | 自变量（特征） | 因变量（结果） | 关系 | 一般表达式 | 
:-: |:-: |:-: |:-:|:-:|
linear | 连续或离散 | 连续实数 | 线性 | f(x) = wx<sub>i</sub> + b 
Logistic | 连续或离散 | （0,1）之间连续值 | 非线性 | g(z) = /frac{1}{1+e<sup>-z</sup>}

## 2. 逻辑回归原理
## 3. 逻辑回归损失函数推倒及优化
## 4. 正则化与模型评估指标
## 5. 逻辑回归的优缺点
## 6. 样本不均衡问题解决办法
## 7. sklearn 参数
### 附：相关知识复习
1. **log && lg && ln**
  - 如果a(a>0，且a≠1)的b次幂等于N，即ab=N，那么数b叫做以a为底N的对数，记作：**log<sub>a</sub>N=b** ,其中a叫做对数的底数，N叫做真数.  
  - 以10为底的对数叫常用对数，记作 **log<sub>10</sub>N = lgN** .    
  - 以无理数e(e=2.718 28…)为底的对数叫做自然对数，记作 **log<sub>e</sub>N = lnN**.