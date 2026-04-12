# 大根の水漬け


### 📅 YYYY-MM-DD

##### 🥣 recipe（いい感じ👍）


##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=1367; salt=0.03; sugar=0.02; I='大根 水 漬け汁 塩 砂糖 合計'.split(); r=[1367,600,300]; s_s=[0,0,0.03]; sg_s=[0,0,0.02]; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); l_s=sum(v*s for v,s in zip(r_norm,s_s)); l_sg=sum(v*s for v,s in zip(r_norm,sg_s)); t_r=max(s_r,(s_r-l_s-l_sg)/(1-salt-sugar)); s_a=max(0,t_r*salt-l_s); sg_a=max(0,t_r*sugar-l_sg); act_s=(l_s+s_a)/t_r; act_sg=(l_sg+sg_a)/t_r; R=r_norm+[s_a,sg_a,t_r]; N=[f'塩分:{round(s*100,1)}%' for s in s_s]+['塩分100%','糖分100%',f'全体:{round(act_s*100,1)}% / {round(act_sg*100,1)}%']; res="|材料|比率|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v,3)}|{round(x*v,1)}{'ml' if n in['水','醤油'] else 'g'}|{round(v/t_r*100,1)}%|{note if i<len(N) else ''}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

---

### 📅 2026-04-11  大根の水漬け 4ℓ

##### 🥣 recipe（いい感じ👍）

|材料|比率|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**大根**|1.0|2607.0g|58.9%|塩分:0%|
|**水**|0.575|1500.0ml|33.9%|塩分:0%|
|**漬け汁**|0.038|100.0g|2.3%|塩分:3.0%|
|**塩**|0.05|129.7g|2.9%|塩分100%|
|**砂糖**|0.033|86.5g|2.0%|糖分100%|
|**合計**|1.697|4423.2g|100.0%|全体:3.0% / 2.0%|
###### 薬味

| **材料** | **分量** |
| :----: | :----: |
|  鷹の爪   |   5本   |
|  乾燥昆布  |   5枚   |

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=2607; salt=0.03; sugar=0.02; I='大根 水 漬け汁 塩 砂糖 合計'.split(); r=[2607,1500,100]; s_s=[0,0,0.03]; sg_s=[0,0,0.02]; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); l_s=sum(v*s for v,s in zip(r_norm,s_s)); l_sg=sum(v*s for v,s in zip(r_norm,sg_s)); t_r=max(s_r,(s_r-l_s-l_sg)/(1-salt-sugar)); s_a=max(0,t_r*salt-l_s); sg_a=max(0,t_r*sugar-l_sg); act_s=(l_s+s_a)/t_r; act_sg=(l_sg+sg_a)/t_r; R=r_norm+[s_a,sg_a,t_r]; N=[f'塩分:{round(s*100,1)}%' for s in s_s]+['塩分100%','糖分100%',f'全体:{round(act_s*100,1)}% / {round(act_sg*100,1)}%']; res="|材料|比率|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v,3)}|{round(x*v,1)}{'ml' if n in['水','醤油'] else 'g'}|{round(v/t_r*100,1)}%|{note if i<len(N) else ''}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

2026-04-11
水500に塩15.5
```500/97*3 = 15.5 (15.463917525773198)```
漬け汁100をもらい126の塩水を返す
```515.5-126 = 389.5 (389.5)```
水500+塩15.5
水200+塩6
水200+塩6
計算ミスに気付く、2607を2067で計算してたため、塩17g足りない。
水100+塩20
```100/97*3 = 3.1 (3.092783505154639)```
```80.6-63.9 = 16.7 (16.699999999999996)```
```3.1+16.7 = 19.8 (19.8)```
100+82+3
4.5




---

### 📅 2026-04-09  大根の水漬け 4ℓ

##### 🥣 recipe（いい感じ👍）


|材料|比率|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**大根**|1.0|2594.0g|61.7%|塩分:0%|
|**水**|0.424|1100.0ml|26.2%|塩分:0%|
|**聖水**|0.116|300.0g|7.1%|塩分:0%|
|**塩**|0.049|126.1g|3.0%|塩分100%|
|**砂糖**|0.032|84.1g|2.0%|糖分100%|
|**合計**|1.621|4204.2g|100.0%|全体:3.0% / 2.0%|

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python

x=2594; salt=0.03; sugar=0.02; I='大根 水 聖水 塩 砂糖 合計'.split(); r=[2594,1100,300]; s_s=[0,0,0]; sg_s=[0,0,0]; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); l_s=sum(v*s for v,s in zip(r_norm,s_s)); l_sg=sum(v*s for v,s in zip(r_norm,sg_s)); t_r=max(s_r,(s_r-l_s-l_sg)/(1-salt-sugar)); s_a=max(0,t_r*salt-l_s); sg_a=max(0,t_r*sugar-l_sg); act_s=(l_s+s_a)/t_r; act_sg=(l_sg+sg_a)/t_r; R=r_norm+[s_a,sg_a,t_r]; N=[f'塩分:{round(s*100,1)}%' for s in s_s]+['塩分100%','糖分100%',f'全体:{round(act_s*100,1)}% / {round(act_sg*100,1)}%']; res="|材料|比率|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v,3)}|{round(x*v,1)}{'ml' if n in['水','醤油'] else 'g'}|{round(v/t_r*100,1)}%|{note if i<len(N) else ''}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

2026-04-10
水100g
塩3g

2026-04-12 16:35 
砂糖78g
塩3g




---


### 📅 2026-04-04  大根の水漬け 2200ml

##### 🥣 recipe（いい感じ👍）

|材料|比率|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**大根**|1.0|1367.0g|57.7%|塩分:0%|
|**水**|0.439|600.0ml|25.3%|塩分:0%|
|**漬け汁**|0.219|300.0g|12.7%|塩分:3.0%|
|**塩**|0.045|62.1g|2.6%|塩分100%|
|**砂糖**|0.03|41.4g|1.7%|糖分100%|
|**合計**|1.734|2370.5g|100.0%|全体:3.0% / 2.0%|

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=1367; salt=0.03; sugar=0.02; I='大根 水 漬け汁 塩 砂糖 合計'.split(); r=[1367,600,300]; s_s=[0,0,0.03]; sg_s=[0,0,0.02]; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); l_s=sum(v*s for v,s in zip(r_norm,s_s)); l_sg=sum(v*s for v,s in zip(r_norm,sg_s)); t_r=max(s_r,(s_r-l_s-l_sg)/(1-salt-sugar)); s_a=max(0,t_r*salt-l_s); sg_a=max(0,t_r*sugar-l_sg); act_s=(l_s+s_a)/t_r; act_sg=(l_sg+sg_a)/t_r; R=r_norm+[s_a,sg_a,t_r]; N=[f'塩分:{round(s*100,1)}%' for s in s_s]+['塩分100%','糖分100%',f'全体:{round(act_s*100,1)}% / {round(act_sg*100,1)}%']; res="|材料|比率|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v,3)}|{round(x*v,1)}{'ml' if n in['水','醤油'] else 'g'}|{round(v/t_r*100,1)}%|{note if i<len(N) else ''}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント


2026-04-04 15:21 大根の水漬け2200ml。

<img width="400" alt="画像" src="images/20260404_2.jpg"> 

2026-04-10
水100g
塩3g

2026-04-12 16:51 
砂糖41g
塩2g


---

### 📅 2026-04-04 大根の水漬け 700ml

##### 🥣 recipe（いい感じ👍）

|材料|比率|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**大根**|1.0|369.0g|45.9%|塩分:0%|
|**水**|0.813|300.0ml|37.3%|塩分:0%|
|**漬け汁**|0.271|100.0g|12.4%|塩分:3.0%|
|**塩**|0.057|21.1g|2.6%|塩分100%|
|**砂糖**|0.038|14.1g|1.8%|糖分100%|
|**合計**|2.179|804.2g|100.0%|全体:3.0% / 2.0%|

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=369; salt=0.03; sugar=0.02; I='大根 水 漬け汁 塩 砂糖 合計'.split(); r=[369,300,100]; s_s=[0,0,0.03]; sg_s=[0,0,0.02]; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); l_s=sum(v*s for v,s in zip(r_norm,s_s)); l_sg=sum(v*s for v,s in zip(r_norm,sg_s)); t_r=max(s_r,(s_r-l_s-l_sg)/(1-salt-sugar)); s_a=max(0,t_r*salt-l_s); sg_a=max(0,t_r*sugar-l_sg); act_s=(l_s+s_a)/t_r; act_sg=(l_sg+sg_a)/t_r; R=r_norm+[s_a,sg_a,t_r]; N=[f'塩分:{round(s*100,1)}%' for s in s_s]+['塩分100%','糖分100%',f'全体:{round(act_s*100,1)}% / {round(act_sg*100,1)}%']; res="|材料|比率|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v,3)}|{round(x*v,1)}{'ml' if n in['水','醤油'] else 'g'}|{round(v/t_r*100,1)}%|{note if i<len(N) else ''}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

2026-04-04 15:20 大根の水漬け700ml。

<img width="400" alt="画像" src="images/20260404_1.jpg">

2026-04-12 17:04 
砂糖14g（16g入れちゃった）
塩1g



---