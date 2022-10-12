---
title: 軌跡方程式
description: 15個高中數學的軌跡方程式
date: 2022-10-12
slug: test-chinese
image: track_pic.jpg
math: true
categories:
    - 高中數學
---
# 軌跡方程式

觀念1：圓上任一點，與該圓的任意直徑兩端點連線，形成直角(三角形)。

觀念2：圓上任一點，到圓心的距離為定值，即半徑。

觀念3：拋物線上任一點，到焦點的距離與到準線的最小距離相等。

觀念4：橢圓上任一點，到兩焦點的距離和為定值。

觀念5：雙曲線上任一點，到兩焦點的距離差為定值。

`by kpshih`

## 圓 1、過圓內一點之弦中點軌跡

圓 $O: x^2+y^2=100$ ，

過圓內一點 $P(8,0)$ 作圓 $O$ 的弦，

請問其弦中點 $M$ 的軌跡方程式為何？

1. 連接 $\overline{OM}$ ，則 $\overline{OM}\,\bot\,\overline{MP}$ 。
（弦心距線段與該弦垂直）
2. 故 $M$ 軌跡是以 $\overline{OP}$ 為直徑所作的圓。
3. $M$ 的軌跡方程式：（圓的直徑式）
$(x-8)(x-0)+(y-0)(y-0)=0$

<aside>
😼 注意右圖的 $\angle OMP$ ，不論經過 $P$ 的弦取哪一條，皆恆為直角。

</aside>

[https://www.desmos.com/calculator/baeif3qqtv?embed](https://www.desmos.com/calculator/baeif3qqtv?embed)

<iframe src="https://www.desmos.com/calculator/jriggdiwuq?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0>
</iframe>

---

## 圓 2、過同心圓之切點軌跡

圓 $O: x^2+y^2=k^2$ ，其中 $0\leq k\leq 10$，

過 $P(10,0)$ 作切線，交圓 $O$ 於$A$、$B$，

請問其切點的軌跡方程式為何？

1. 連接 $\overline{OA}$ 、 $\overline{OB}$，
則 $\overline{OA}\,\bot\,\overline{AP}$ 、 $\overline{OB}\,\bot\,\overline{BP}$ 。
2. 故 $A$ 是以 $\overline{OP}$ 為直徑所作的上半圓；
$B$ 是以 $\overline{OP}$ 為直徑所作的上半圓。
3. 切點的軌跡方程式：（圓的直徑式）
$(x-10)(x-0)+(y-0)(y-0)=0$

<aside>
🐶 注意右圖的 $\angle OAP$ 與 $\angle OBP$ ，不論藍色圓的半徑為何，皆恆為直角。

</aside>

[https://www.desmos.com/calculator/jog9blexns?embed](https://www.desmos.com/calculator/jog9blexns?embed)

---

## 圓 3、固定切線段長之點集合

圓 $O: x^2+y^2=6^2$ ，$P$ 為圓上一點，

過 $P$ 作切線，並在切線上取 $A、B$，

使得 $\overline{AP} =\overline{PB} =8$ ，即切線段長$=8$，

請問 $A、B$ 通過的圖形方程式為何？

1. 連接 $\overline{OP}$  ， 則 $\overline{OP}\,\bot\,\overline{AB}$ 。

1. 已知 $\overline{OP} =6$ 、 $\overline{AP} =\overline{PB} =8$ ，
則 $\overline{OA}=\overline{OB}=\sqrt{6^2+8^2}=10$

1.  由此可知，$A、B$ 通過的圖形為所有距離 $O$ 為 $10$ 的點，即圓心為 $O$ 、半徑為 $10$ 的圓。

1. 若藍圓半徑為 $R$ 、切線段長為 $r$ ，
$A、B$ 經過的圓方程式：（圓的標準式）
$x^2+y^2=R^2+r^2$

<aside>
🙉 注意右圖的 $\overline{OA}$ 線段，不論切點取在哪，距離 $O$ 的距離恆為定值，即新圓半徑。

</aside>

[https://www.desmos.com/calculator/ufdqfyx20m?embed](https://www.desmos.com/calculator/ufdqfyx20m?embed)

[https://www.desmos.com/calculator/fwkgyhigum?embed](https://www.desmos.com/calculator/fwkgyhigum?embed)

---

## 圓 4、固定兩切線夾角之圓外一點軌跡

圓 $O:x^2+y^2=5^2$ ， $P$ 為圓外一點，

過 $P$ 作切線，交圓 $O$ 於兩切點 $A$、$B$。

已知 $\angle APB = 60\degree$ ，

求 $P$ 通過的圖形方程式為何？

1. 連接 $\overline{OA}$ ， 則 $\overline{OA}\,\bot\,\overline{AP}$ 。
（連接 $\overline{OB}$  ， 則 $\overline{OB}\,\bot\,\overline{BP}$ 。）
2. 已知 $\overline{OP} =5$ 、  $\angle APB = 60\degree$ ，
則 $\angle APO = \angle BPO =30\degree$ ，
則$\overline{OP}=5 \,\div\, sin\,30\degree=10$
3. $P$ 經過的圓方程式：（圓的標準式）$x^2+y^2=(\frac{5}{sin\,30\degree})^2=10^2$

<aside>
🦉 注意右圖的 $\overline{OP}$ 線段，不論兩切點取在哪，因為兩切線夾角為定值，$\overline{OP} =5$ 恆為定值，即新圓半徑。

</aside>

<aside>
🦉 如果「已知 $\angle APB = 60\degree$」條件改為「兩切線夾角 $60\degree$」，要注意「$\angle APB = 120\degree$」也滿足要求。

</aside>

[https://www.desmos.com/calculator/3kgluwikgo?embed](https://www.desmos.com/calculator/3kgluwikgo?embed)

[https://www.desmos.com/calculator/wcbn44pufo?embed](https://www.desmos.com/calculator/wcbn44pufo?embed)

---

## 拋物線 1、已知圓上一點與一切線之圓心軌跡

已知平面上一圓與直線 $L: y=-1$ 相切，並通過 $F(0,1)$，求該圓圓心 $P$ 的軌跡方程式。

1. 連接 $\overline{PF}$ ，並作 $\overline{PQ}$ 垂直 $L$ 於 $Q$ 。
2. $\because \overline{PQ}=\overline{PF}$
$\therefore P$ 點通過的圖形，是以 $F$ 作為焦點、$y=-1$ 為準線的拋物線。
3. 拋物線方程式：（根據定義）
    
    任一點到焦點的距離$=$到準線的距離
    
    $\sqrt{x^2+(y-1)^2}=y-(-1)$
    
    兩邊同時平方後展開：
    
    $x^2+(y^2-2y+1)=y^2+2y+1$
    
    化簡得到： $y=\frac{1}{4}x^2$
    

<aside>
👽 移動看看右圖的 $P$ 點，隨著半徑變大縮小，該圓恆過焦點、並與準線相切，這就是拋物線定義的性質！

</aside>

[https://www.desmos.com/calculator/1pe7ylq6hd?embed](https://www.desmos.com/calculator/1pe7ylq6hd?embed)

[https://www.desmos.com/calculator/5fqbtewcbq?embed](https://www.desmos.com/calculator/5fqbtewcbq?embed)

---

## 拋物線 2、同時與一圓一直線相切的圓之圓心軌跡

已知平面上一圓與直線 $L: y=-3$ 相切，並與另一圓 $(x-3)^2+y^2=3^2$ 相切，
求該圓圓心 $P$ 的軌跡方程式。

1. $F(3,0)$ ，連接 $\overline{PF}$ 交圓 $F$ 於 $F'$ 。
2. 作 $\overline{PQ}$ 垂直 $L$ 於 $Q$ ，得 $\overline{PQ}=\overline{PF’}$。
3. 作 $L_2:y=-6$。
4. 延長 $\overline{PQ}$ 交 $L_2$ 於 $Q'$ 。

$$
\begin{align*}
\because &\,\,\,\overline{PF}=\overline{PF'}+R,\\
&\,\,\,\overline{PQ'}=\overline{PQ}+R,\\
&\,\,\,\overline{PQ}=\overline{PF’}\\
\therefore
&\,\,\,\overline{PQ'}=\overline{PF}
\end{align*}
$$

1. 故 $P$ 點通過的圖形，是以 $F$ 作為焦點、$y=-6$ 為準線的拋物線。

1. 拋物線方程式：（根據定義）
    
    任一點到焦點的距離$=$到準線的距離
    
    $\sqrt{x^2+(y-3)^2}=y-(-6)$
    
    兩邊同時平方後展開：
    
    $x^2+(y^2-6y+9)=y^2+12y+36$
    
    化簡得到： $y=\frac{1}{18}x^2-\frac32$
    

[https://www.desmos.com/calculator/abfyawe4pe?embed](https://www.desmos.com/calculator/abfyawe4pe?embed)

[https://www.desmos.com/calculator/5av0rxijqt?embed](https://www.desmos.com/calculator/5av0rxijqt?embed)

<aside>
🐙 關鍵是要找到真正的焦點、準線在哪！移動 $P$ 點，觀察拋物線的性質：到焦點、準線距離是否相等。

</aside>

---

## 橢圓 1、與一圓相切並過圓內一點之圓心軌跡

平面上 $O: x^2+y^2=10^2$ 與 $F(6,0)$，

已知有一圓內切於 $O$，並且恆通過點 $F$，

求該圓圓心 $P$ 的軌跡方程式。

1. 作 $\overline{PO}$ 、 $\overline{PF}$ ，並且延長 $\overrightharpoon{OP}$
2. 令 $\overline{PF}=r$ ，則 $\overline{OP}=10-r$ 。
（大圓半徑減去小圓半徑）
3. 由此可得到：$\overline{PF}+\overline{OP}=10$，
即 $P$ 到 $O$、$F$ 的距離和恆為定值，
圖形是以 $O$、$F$ 作為焦點的橢圓。
4. 計算橢圓方程式：
    
    長軸長 $=10$、 $\overline{OF}=6$，
    
    可得到短軸長 $=\sqrt{10^2-6^2}=8$。
    
    橢圓的標準式： $\frac{(x-3)^2}{5^2}+\frac{y^2}{4^2}=1$
    

<aside>
🦁 $P$ 點的移動方式，也是現實中手繪橢圓的方法哦！
試著將一條細繩的兩端點固定於平面上兩點，再用一支筆保持拉緊細繩作圓，就能夠畫出一個橢圓！
因為筆尖到兩焦點的距離和就是細繩長度，手不要抖就恆為定值。

</aside>

[https://www.desmos.com/calculator/oivyzkkatl?embed](https://www.desmos.com/calculator/oivyzkkatl?embed)

[https://www.desmos.com/calculator/6cs1mlkiaq?embed](https://www.desmos.com/calculator/6cs1mlkiaq?embed)

---

## 橢圓 2、與兩內離圓同時相切的圓之圓心軌跡

已知平面上兩圓內離，圓$O:x^2+y^2=10^2$ 與圓$F:(x+5)^2+y^2=3^2$ ，今有第三圓與兩圓相切，問其圓心軌跡方程式為何？

<aside>
😈 此題「與圓 $O$ 相切」有兩種情形：
一是與圓 $F$ 外切（如右側藍色圓） 
二是與圓 $F$ 內切（如左側紅色圓）
可以注意到，不論 $A$、$B$，到 $O$、$F$ 的距離和皆恆為定值。 

**- 以下將分別討論兩種情形 -**

</aside>

[https://www.desmos.com/calculator/vjj5wzevzy?embed](https://www.desmos.com/calculator/vjj5wzevzy?embed)

---

$-\,Case\,\,1\,-$

內切於大圓 $O$ ，並與小圓 $F$ 外切。

[https://www.desmos.com/calculator/f1rcdxy6jd?embed](https://www.desmos.com/calculator/f1rcdxy6jd?embed)

1. 稱藍色圓為 $O_A$ 、其圓心 $A$，
作 $\overline{AF}$、$\overline{AO}$。
2. 令圓 $O$ 半徑為 $R$、圓 $F$ 半徑為 $r$、
藍色圓 $O_A$ 半徑為 $a$。
3.  $\overline{AF} = a+r$、$\overline{AO}=R-a$，
則 $\overline{AF}+\overline{AO}=R+r$ 。
4. 故圓心 $A$ 所經過的軌跡，是以 $F$、$O$ 為焦點的橢圓。
5. 計算橢圓方程式：
    
    長軸長 $=13$、 $\overline{OF}=5$，
    
    可得到短軸長 $=\sqrt{13^2-5^2}=12$。
    
    橢圓的標準式： $\frac{(x-2.5)^2}{6.5^2}+\frac{y^2}{6^2}=1$
    

$-\,Case\,\,2\,-$

內切於大圓 $O$ ，並與小圓 $F$ 內切 。

[https://www.desmos.com/calculator/m9v5jic5yd?embed](https://www.desmos.com/calculator/m9v5jic5yd?embed)

1. 稱藍色圓為 $O_B$ 、其圓心 $B$，
作 $\overline{BF}$、$\overline{BO}$。
2. 令圓 $O$ 半徑為 $R$、圓 $F$ 半徑為 $r$、
藍色圓 $O_B$ 半徑為 $b$。
3.  $\overline{BF} = b-r$、$\overline{BO}=R-b$，
則 $\overline{BF}+\overline{BO}=R-r$ 。
4. 故圓心 $A$ 所經過的軌跡，是以 $F$、$O$ 為焦點的橢圓。
5. 計算橢圓方程式：
    
    長軸長 $=7$、 $\overline{OF}=5$，
    
    可得到短軸長 $=\sqrt{7^2-5^2}=2\sqrt{6}$。
    
    橢圓的標準式： $\frac{(x-2.5)^2}{3.5^2}+\frac{y^2}{\sqrt6^2}=1$
    

---

## 雙曲線 1、與已知圓相切並通過圓外一點之圓心軌跡

已知圓 $O:x^2+y^2=4^2$ 與 $F(8,0)$ ，

今有一圓通過 $F$ ，並與圓 $O$ 相切，

試問該圓之圓心軌跡方程式為何？

<aside>
⛄ 此題「與圓 $O$ 相切」有兩種情形：
一是與圓 $O$ 外切（如右側綠色圓） 
二是與圓 $O$ 內切（如左側紅色圓）
可以注意到，$A$、$B$ 到 $O$、$F$ 的距離差恆為定值，且兩值相等。 

**- 以下將分別討論兩種情形 -**

</aside>

[https://www.desmos.com/calculator/qe9csdlghm?embed](https://www.desmos.com/calculator/qe9csdlghm?embed)

---

$-\,Case\,\,1\,-$

通過 $P$ 點，並與圓 $O$ 外切。

[https://www.desmos.com/calculator/nuoa9mrloa?embed](https://www.desmos.com/calculator/nuoa9mrloa?embed)

1. 連結 $\overline{AO}$、$\overline{AF}$ 。
2. 令圓 $O$ 半徑 $R$ 、綠色圓 $A$ 半徑 $r$ 。
3. 得到 $\overline{AO}=R+r$ 、$\overline{AF}=r$ ，
則 $\overline{AO}-\overline{AF}=R$ 。
4. $A$ 到兩焦點 $O$、$F$ 的距離差為定值 $R$，故 $A$ 的軌跡為右半邊的雙曲線。

$-\,Case\,\,2\,-$

通過 $P$ 點，並與圓 $O$ 內切。

[https://www.desmos.com/calculator/bsye6dlhnv?embed](https://www.desmos.com/calculator/bsye6dlhnv?embed)

1. 連結 $\overline{BO}$、$\overline{BF}$ 。
2. 令圓 $O$ 半徑 $R$ 、紅色圓 $B$ 半徑 $r$ 。
3. 得到 $\overline{BO}=r-R$ 、$\overline{BF}=r$ ，
則 $\overline{BF}-\overline{BO}=R$ 。
4. $B$ 到兩焦點 $O$、$F$ 的距離差為定值 $R$，故 $B$ 的軌跡為左半邊的雙曲線。

> 綜合以上兩情況
> 
1. $\because\overline{AO}-\overline{AF}=R$ 、 $\overline{BF}-\overline{BO}=R$ 
令 $P$ 為 $A$ 與 $B$ 的集合， $\therefore\vert\,\overline{PO}-\overline{PF}
\,\vert=R$ ，即完整的雙曲線定義。
2. 計算雙曲線方程式：
    
    $R=4$ 、 $\overline{OF}=8$，可得到 $b=\sqrt{8^2-4^2}=4\sqrt3$。
    
    雙曲線的標準式： $\frac{(x-4)^2}{4^2}-\frac{y^2}{(4\sqrt3)^2}=1$
    

---

## 雙曲線 2、與兩外離圓同時相切的圓之圓心軌跡

已知平面上兩圓外離，圓 $O:x^2+y^2=4^2$ 與圓 $P:(x+10)^2+y^2=1$ ，今有第三圓與兩圓相切，問其圓心軌跡方程式為何？

<aside>
🐰 此題「與圓 $O$ 相切」有四種情形！
一是「外切圓$O$、外切圓$F$」
二是「內切圓$O$、內切圓$F$」
三是「外切圓$O$、內切圓$F$」
四是「內切圓$O$、外切圓$F$」
作法與上題「雙曲線1 」類似，其中一二一組、三四一組，分別會作出完整的雙曲線，方法一樣是找出 $A$、$B$ 分別到 $O$、$F$ 的距離差為定值。 

**- 以下將分別討論兩種情形 -**

</aside>

[https://www.desmos.com/calculator/nd6b5rhb9f?embed](https://www.desmos.com/calculator/nd6b5rhb9f?embed)

---

$-\,Case\,\,1\,-$

一、「外切圓$O$、外切圓$F$」(左半雙曲線)
二、「內切圓$O$、內切圓$F$」(右半雙曲線)

[https://www.desmos.com/calculator/d5zyyat05s?embed](https://www.desmos.com/calculator/d5zyyat05s?embed)

1. 連結 $\overline{AO}$、$\overline{AF}$ 。
2. 令右圓 $O$ 半徑 $R$ 、左圓 $F$ 半徑 $r$ 、紅色圓 $A$ 半徑 $a$ 。
3. 左側： $\overline{AO}=a+R$ 、$\overline{AF}=a+r$ ，則 $\overline{AO}-\overline{AF}=R-r$ 。
4. 右側： $\overline{AO}=a-R$ 、$\overline{AF}=a-r$ ，則 $\overline{AO}-\overline{AF}=-R+r$ 。
5. 得到 $\vert\overline{AO}-\overline{AF}\vert=\vert R-r\vert$
6. $A$ 到兩焦點 $O$、$F$ 的距離差 $\vert R-r \vert$ 為定值，故 $A$ 的軌跡為完整的的雙曲線。
7. 計算雙曲線方程式：
    
    $R=4$、$r=1$、$\overline{OF}=10$，可得到 $b=\sqrt{10^2-(4-1)^2}=\sqrt{91}$。
    
    雙曲線的標準式：$\frac{(x-4)^2}{3^2}-\frac{y^2}{(\sqrt{91})^2}=1$
    

$-\,Case\,\,2\,-$

三、「外切圓$O$、內切圓$F$」(左半雙曲線)
四、「內切圓$O$、外切圓$F$」(右半雙曲線)

[https://www.desmos.com/calculator/bsoflvkbpn?embed](https://www.desmos.com/calculator/bsoflvkbpn?embed)

1. 連結 $\overline{BO}$、$\overline{BF}$ 。
2. 令右圓 $O$ 半徑 $R$ 、左圓 $F$ 半徑 $r$ 、藍色圓 $B$ 半徑 $b$ 。
3. 左側： $\overline{BO}=b+R$ 、$\overline{BF}=b-r$ ，則 $\overline{BO}-\overline{BF}=R+r$ 。
4. 右側： $\overline{BO}=b-R$ 、$\overline{BF}=b+r$ ，則 $\overline{BO}-\overline{BF}=-R-r$ 。
5. 得到 $\vert\overline{BO}-\overline{BF}\vert=R+r$
6. $B$ 到兩焦點 $O$、$F$ 的距離差 $R+r$ 為定值，故 $B$ 的軌跡為完整的的雙曲線。
7. 計算雙曲線方程式：
    
    $R=4$、$r=1$、$\overline{OF}=10$，可得到 $b=\sqrt{10^2-(4+1)^2}=5\sqrt{3}$。
    
    雙曲線的標準式：$\frac{(x-4)^2}{5^2}-\frac{y^2}{(5\sqrt{3})^2}=1$
    

<aside>
✍🏼 拉拉看這題圖上的 $F$，在 $F$ 無限接近圓 $O$ 的時候，雙曲線接近水平線，會看到圓心在$[0,\infty],[-\infty,0]$來回跑，會有一瞬間從 $\infty$ 飛到 $-\infty$，與圓內切會變成外切！

</aside>

---

11. 與兩直線同時相切的圓之圓心軌跡

12. 圓上任一點，和已知p點所連線段之中點M的軌跡

13. 與已知兩點「距離比為固定值」的所有點之軌跡 — 阿波羅圓

14. 木棍貼著牆面、地面下滑時，其中點軌跡

15. 木棍貼著牆面、地面下滑時，棍上某等分點之軌跡

# Reference

*原先看到嘉義高中的教甄題目，想說試著把類似問題搜集起來、做成圖，想不到網路上已經有人做了，大部分只是把它做成desmos動圖而已。作圖過程需要克服很多小問題、可以學到很多！*

有熊老師。****給指考戰士的：「軌跡圖形」在搞什麼軌？****
[https://tpdjdje0525.medium.com/給指考戰士的-軌跡圖形-在搞什麼軌-fca7c4dba66f](https://tpdjdje0525.medium.com/%E7%B5%A6%E6%8C%87%E8%80%83%E6%88%B0%E5%A3%AB%E7%9A%84-%E8%BB%8C%E8%B7%A1%E5%9C%96%E5%BD%A2-%E5%9C%A8%E6%90%9E%E4%BB%80%E9%BA%BC%E8%BB%8C-fca7c4dba66f)

嘉義高中111年數學科教師甄試。第17題。

![messageImage_1665243852244.jpg](%E8%BB%8C%E8%B7%A1%E6%96%B9%E7%A8%8B%E5%BC%8F%20da8e4f122d0545f7a343a55163a0385a/messageImage_1665243852244.jpg)