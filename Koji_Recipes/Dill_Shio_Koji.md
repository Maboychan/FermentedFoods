

### 📅 YYYY-MM-DD

##### 🥣 recipe（いい感じ👍）



 ##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=200; I='ディル 米乳 水 塩 合計'.split(); r=[2,3,4]; s_s=0.00; salt=0.10; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

---


### 📅 2026-01-31 ディル塩麹

##### 🥣 recipe 2026-01-31

|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**ディル**|1|200g|20.0%||
|**白米麹**|1.5|300.0g|30.0%||
|**水**|2|400ml|40.0%||
|**塩**|0.5|100.0g|10.0%||
|**合計**|5.0|1000.0g|100.0%|塩分:10.0%|


PyKeysのREPL用ワンライナー
~~~python
x=200; I='ディル 白米麹 水 塩 合計'.split(); r=[1,1.5,2]; s_s=0.00; salt=0.10; import clipboard; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

フードプロセッサーは２回に分けたほうが良さそう。
ソース麹を作ったタッパーを使用する。

---
### 📅 2025-12-31ディル塩麹

##### 🥣 recipe（いい感じ👍）

|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**ディル**|2.0|150.0g|20.0%||
|**黴米乳酸圧力麹**|3.0|225.0g|30.0%||
|**水**|4.0|300.0ml|40.0%||
|**塩**|1.0|75.0g|10.0%||
|**合計**|10.0|750.0g|100.0%|塩分:10.0%|

 ##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=150; I='ディル 黴米乳酸圧力麹 水 塩 合計'.split(); r=[2,3,4]; s_s=0.00; salt=0.10; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

---
### 📅 2025-12-24ディル塩麹

##### 🥣 recipe（いい感じ👍）

|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**ディル**|2.0|220.0g|20.0%||
|**黴米乳酸圧力麹**|3.0|330.0g|30.0%||
|**水**|4.0|440.0ml|40.0%||
|**塩**|1.0|110.0g|10.0%||
|**合計**|10.0|1100.0g|100.0%|塩分:10.0%

 ##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=220; I='ディル 黴米乳酸圧力麹 水 塩 合計'.split(); r=[2,3,4]; s_s=0.00; salt=0.10; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

---

