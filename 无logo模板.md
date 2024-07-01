---
marp: true
header : ' ***Southwestern University of Finance and Economics***'
footer : ' ![](https://jsd.onmicrosoft.cn/gh/momozhangxuan/tuchuang@main/img/logo.jpg) '
theme: myself
papaginate: true

---
<!-- paginate: true -->

# <!-- fit -->  An Introduction to the use of markdown
## markdown的一个简介

#### 章轩 <br>西南财经大学<br>经济学院<br>*2024年7月1日*


---
## 引用页

### *Henry Kissnger: On China*
>  Poured out of the countryside to take over the cities stood a colossus
### 周黎安：官员晋升锦标赛



> 本文研究了中国地方官员的治理模式——"晋升锦标赛治理模式"的性质与特征,并试图揭示这种特定模式与中国高速经济增长及其各种特有问题的内在关联。本文认为,晋升锦标赛作为中国政府官员的激励模式,它是中国经济奇迹的重要根源,但由于晋升锦标赛自身的一些缺陷,尤其是其激励官员的目标与政府职能的合理设计之间存在严重冲突,它目前正面临着重要的转型。

---
![bg left opacity:.40](https://jsd.onmicrosoft.cn/gh/momozhangxuan/tuchuang@main/img/%E8%A5%BF%E8%B4%A2%E8%83%8C%E6%99%AF.jpg)
## <!-- fit --> 一、摘要 & *Abstract* 


---

## 这个是标题哦
### 尽可能不要用一级标题哦
* 本文研究了中国地方官员的治理模式——"晋升锦标赛治理模式"的性质与特征,并试图揭示这种特定模式与中国高速经济增长及其各种特有问题的内在关联。本文认为,晋升锦标赛作为中国政府官员的激励模式,它是中国经济奇迹的重要根源,但由于晋升锦标赛自身的一些缺陷,尤其是其激励官员的目标与政府职能的合理设计之间存在严重冲突,它目前正面临着重要的转型。
* 你看看这波是不是非常完美了（Wozi &Jisuode,2024)
### 还是那句话，尽可能不要用一级标题


---

![bg left opacity:.40](https://jsd.onmicrosoft.cn/gh/momozhangxuan/tuchuang@main/img/%E8%A5%BF%E8%B4%A2%E8%83%8C%E6%99%AF.jpg)
## <!-- fit --> 一、引言
## <!-- fit --> *Introduction*




---


## 我是图片页
### 尽可能不要用一级标题哦
* 右边要是插个图，味道就很不错了
* 你看看这波是不是非常完美了（Wozi &Jisuode,2024)
### 还是那句话，尽可能不要用一级标题

![bg right 80%](https://jsd.onmicrosoft.cn/gh/momozhangxuan/tuchuang@main/img/%E6%A9%98%E5%AD%90%E6%B4%B2%E5%A4%B4.jpg)



---
## 展示思路
### 1. 引言<br>
### 2. 文献综述
### 3. 理论推导<br>4. 实证检验<br>5. 稳健性<br>6. 结论与反思

![bg right 100%](https://jsd.onmicrosoft.cn/gh/momozhangxuan/tuchuang@main/img/%E6%AF%9B%E6%B3%BD%E4%B8%9C.png)


---

![bg left opacity:.40](https://jsd.onmicrosoft.cn/gh/momozhangxuan/tuchuang@main/img/%E8%A5%BF%E8%B4%A2%E8%83%8C%E6%99%AF.jpg)
## <!-- fit --> 我是章节二


---
## 公式页面

### 根据
$$\lambda\theta a_i-b_i+2\varepsilon b_i=\lambda\theta(a_i+b_i)e_i-\lambda\theta\cdot b_i e_j$$
$$\lambda\theta a_j-b_j+2\varepsilon b_j=\lambda\theta(a_j+b_j)e_j-\lambda\theta\cdot b_j e_i$$
### 求解得到
$$e_i^*=-\frac{-\theta  \lambda  a_j b_i-\theta  \lambda  a_i b_j-2 \varepsilon  a_j b_i+a_j b_i-\theta  \lambda  a_i a_j-4 \varepsilon  b_i b_j+2 b_i b_j}{\theta  \lambda  \left(a_j b_i+a_i b_j+a_i a_j\right)}$$

$$e_j^*=-\frac{-\theta  \lambda  a_j b_i-\theta  \lambda  a_i b_j-2 \varepsilon  a_i b_j+a_i b_j-\theta  \lambda  a_i a_j-4 \varepsilon  b_i b_j+2 b_i b_j}{\theta  \lambda  \left(a_j b_i+a_i b_j+a_i a_j\right)}$$


---
## 代码页
```stata
reg A B,r
estat vif
est store a1
//普通回归

xtreg A B,r
es store a2
//面板回归

xtreg A B,r fe
es store a3
//固定效应的面板回归

```

---

# <!-- fit --> Thanks for listening
## <!-- fit --> 感谢批评指正

