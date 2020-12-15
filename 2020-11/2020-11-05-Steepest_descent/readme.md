
@[TOC]

# Pythonʵ�������½���(The steepest descent method)��ϸ����

> ԭ�������� [https://blog.csdn.net/HsinglukLiu/article/details/109524062](https://blog.csdn.net/HsinglukLiu/article/details/109524062)

## Introduction

> ��������Ҫ�ǽ���Pythonʵ�������½���(The steepest descent method)������ϸ����

������������ӻ�Ч����ͼ

> ���磺
> ![���������ͼƬ����](https://img-blog.csdnimg.cn/20201215173134647.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0hzaW5nbHVrTGl1,size_16,color_FFFFFF,t_70)




## Algorithm

> �����еĿμ������廪��ѧ���ڹ����о���Ժ�������뽻ͨѧ���Ų��ٽ��ڡ��߼��˳�ѧ���γ̡�
> 
![���������ͼƬ����](https://img-blog.csdnimg.cn/2020121517324338.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0hzaW5nbHVrTGl1,size_16,color_FFFFFF,t_70)


## Quick start 
��������Ҫ�漰python�ķ��ź����� 	`sympy`����Ҫ�������£�������ܼ�����С����ں�����

`�Ż�|�����½�������ϸ����+Pythonʵ��`

[https://mp.weixin.qq.com/s/lS5BhxnZcVoS991XTb6MmQ](https://mp.weixin.qq.com/s/lS5BhxnZcVoS991XTb6MmQ)


#### �������ű����ͷ��ź���
```python
from sympy import * 
x_1 = symbols('x_1')
x_2 = symbols('x_2') 
              
fun = 2 * x_1 * x_2 + 2 * x_2 - x_1**2 - 2 * x_2**2
fun  
```
��������������������ű���$x_1, x_2$���������������ĸ�������һ����Ȼ����Զ�������ǵĺ���
$$
\begin{aligned}
f(x_1,x_2)=&2x_1x_2 +2x_2-x_1^2-2x_2^2 ,
\end{aligned}
$$

`jupyter notebook`�е���ʾЧ����������

![���������ͼƬ����](https://img-blog.csdnimg.cn/20201106024350479.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0hzaW5nbHVrTGl1,size_16,color_FFFFFF,t_70#pic_center)
���Կ���`jupyter notebook`��ֱ�Ӿ���ʾ������ѧ��ʽ��ʽ����ʽ��������Ϊ`jupyter notebook`����Ƕ��`LaTeX`���֧�ְ���Ե�ʡ���֮�������ӻ��ͷǳ�����


## Dependencies

> sympy
> math 


## Dataset Format



## Contact
Your Name �� ����»  hsinglul@163.com

My blog:   [https://blog.csdn.net/HsinglukLiu?spm=1010.2135.3001.5113](https://blog.csdn.net/HsinglukLiu?spm=1010.2135.3001.5113)


## About us
��С�﹫�ں��������ڷ����˳��Ż�(LP��MIP��NLP������滮��³���Ż�)��͹�Ż���ǿ��ѧϰ���о�����������Լ��漰�����㷨�Ĵ���ʵ�֡�������Ժ͹��߰���Java��Python��Matlab��CPLEX��Gurobi��SCIP �ȡ�


**��ע����:  �˳�С���ں�**
![���������ͼƬ����](https://img-blog.csdnimg.cn/20201214000806951.png)
