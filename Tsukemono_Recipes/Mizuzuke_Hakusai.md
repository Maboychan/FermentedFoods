
# 白菜の水漬け

### 📅 YYYY-MM-DD

##### 🥣 recipe（いい感じ👍）

|材料|比率|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**大根**|1.0|776.0g|36.0%|塩分:0%|
|**水**|0.932|723.0ml|33.6%|塩分:0%|
|**漬け汁**|0.744|577.0g|26.8%|塩分:3.0%|
|**塩**|0.061|47.3g|2.2%|塩分100%|
|**砂糖**|0.041|31.6g|1.5%|糖分100%|
|**合計**|2.777|2154.9g|100.0%|全体:3.0% / 2.0%|

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=776; salt=0.03; sugar=0.02; I='大根 水 漬け汁 塩 砂糖 合計'.split(); r=[776,723,577]; s_s=[0,0,0.03]; sg_s=[0,0,0.02]; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); l_s=sum(v*s for v,s in zip(r_norm,s_s)); l_sg=sum(v*s for v,s in zip(r_norm,sg_s)); t_r=max(s_r,(s_r-l_s-l_sg)/(1-salt-sugar)); s_a=max(0,t_r*salt-l_s); sg_a=max(0,t_r*sugar-l_sg); act_s=(l_s+s_a)/t_r; act_sg=(l_sg+sg_a)/t_r; R=r_norm+[s_a,sg_a,t_r]; N=[f'塩分:{round(s*100,1)}%' for s in s_s]+['塩分100%','糖分100%',f'全体:{round(act_s*100,1)}% / {round(act_sg*100,1)}%']; res="|材料|比率|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v,3)}|{round(x*v,1)}{'ml' if n in['水','醤油'] else 'g'}|{round(v/t_r*100,1)}%|{note if i<len(N) else ''}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

---


### 📅 2026-04-14 白菜の水漬（つるじい）

##### 🥣 recipe（いい感じ👍）

|材料|比率|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**大根**|1.0|776.0g|36.0%|塩分:0%|
|**水**|0.932|723.0ml|33.6%|塩分:0%|
|**漬け汁**|0.744|577.0g|26.8%|塩分:3.0%|
|**塩**|0.061|47.3g|2.2%|塩分100%|
|**砂糖**|0.041|31.6g|1.5%|糖分100%|
|**合計**|2.777|2154.9g|100.0%|全体:3.0% / 2.0%|

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=776; salt=0.03; sugar=0.02; I='大根 水 漬け汁 塩 砂糖 合計'.split(); r=[776,723,577]; s_s=[0,0,0.03]; sg_s=[0,0,0.02]; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); l_s=sum(v*s for v,s in zip(r_norm,s_s)); l_sg=sum(v*s for v,s in zip(r_norm,sg_s)); t_r=max(s_r,(s_r-l_s-l_sg)/(1-salt-sugar)); s_a=max(0,t_r*salt-l_s); sg_a=max(0,t_r*sugar-l_sg); act_s=(l_s+s_a)/t_r; act_sg=(l_sg+sg_a)/t_r; R=r_norm+[s_a,sg_a,t_r]; N=[f'塩分:{round(s*100,1)}%' for s in s_s]+['塩分100%','糖分100%',f'全体:{round(act_s*100,1)}% / {round(act_sg*100,1)}%']; res="|材料|比率|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v,3)}|{round(x*v,1)}{'ml' if n in['水','醤油'] else 'g'}|{round(v/t_r*100,1)}%|{note if i<len(N) else ''}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

以前に柚子皮を加えた白菜の水漬けの漬け汁をリサイクルする。
577gの漬け汁の濃度は、塩3%、砂糖2%で計算する。



---





