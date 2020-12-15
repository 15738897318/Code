# ��С��(2020-11-9): Shortest Path Problem�����ż�����һЩ̽��(��Python����Gurobiʵ��)

@[TOC] 
# Shortest Path Problem�����ż�����һЩ̽��(��Python����Gurobiʵ��)

���ߣ�����»���廪��ѧ���廪����������ѧԺ (��ʿ�ڶ�)

���䣺hsinglul@163.com

> ԭ�������� [https://blog.csdn.net/HsinglukLiu/article/details/107834197](https://blog.csdn.net/HsinglukLiu/article/details/107834197)

## Introduction

> ��������Ҫ����֤Shortest path problem�Լ����ż����


���е���������

![���������ͼƬ����](https://img-blog.csdnimg.cn/20201215170957756.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0hzaW5nbHVrTGl1,size_16,color_FFFFFF,t_70)

## Model
### Shortest path problemģ�ͣ�ģ��1��
![���������ͼƬ����](https://img-blog.csdnimg.cn/20201215171154429.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0hzaW5nbHVrTGl1,size_16,color_FFFFFF,t_70)

### Shortest path problem��׼ģ�ͣ�ģ��2��
![���������ͼƬ����](https://img-blog.csdnimg.cn/20201215171236444.png)

### Shortest path problem�Ķ�ż���⣨ģ��3��
![���������ͼƬ����](https://img-blog.csdnimg.cn/20201215171923187.png)


## Quick start 

 - `SPP_Gurobi.py`:��Python����Gurobi���ģ��1��ʽ�Ĵ���
 - `SPP_Standard_form_Gurobi.py`����Python����Gurobi���ģ��2��ʽ�Ĵ���
 - `SPP_Dual.py`����Python����Gurobi���ģ��3��ʽ�Ĵ���


## Dependencies

> gurobi
> numpy
> pandas


## Dataset Format
Solomon VRP benchmark instance
���ص�ַ[https://www.sintef.no/projectweb/top/vrptw/solomon-benchmark/100-customers/](https://www.sintef.no/projectweb/top/vrptw/solomon-benchmark/100-customers/)

```python
Nodes = ['s', 'a', 'b', 'c', 't'] 

Arcs = {('s','a'): 5 
        ,('s','b'): 8
        ,('a','c'): 2
        ,('b','a'): -10
        ,('c','b'): 3
        ,('b','t'): 4
        ,('c','t'): 3
       }
Arcs
```



## Contact
Your Name ������»   hsinglul@163.com

My blog:   [https://blog.csdn.net/HsinglukLiu?spm=1010.2135.3001.5113](https://blog.csdn.net/HsinglukLiu?spm=1010.2135.3001.5113)


## About us
��С�﹫�ں��������ڷ����˳��Ż�(LP��MIP��NLP������滮��³���Ż�)��͹�Ż���ǿ��ѧϰ���о�����������Լ��漰�����㷨�Ĵ���ʵ�֡�������Ժ͹��߰���Java��Python��Matlab��CPLEX��Gurobi��SCIP �ȡ�


**��ע����:  �˳�С���ں�**
![���������ͼƬ����](https://img-blog.csdnimg.cn/20201214000806951.png)
