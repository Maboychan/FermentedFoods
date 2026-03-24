# ねぎ塩麹（ねぎ しおこうじ）

### 📅 YYYY-MM-DD

##### 🥣 recipe（いい感じ👍）

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=436; I='ねぎ 黴米乳酸麹 水 塩 合計'.split(); r=[4,2,1]; s_s=0.00; salt=0.125; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

---
### 📅 2026-02-02 ねぎ塩麹

##### 🥣 recipe 1（水分少なめ）2026-02-02

|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**ねぎ**|4.0|436.0g|50.0%||
|**黴米乳酸麹**|2.0|218.0g|25.0%||
|**水**|1.0|109.0ml|12.5%||
|**塩**|1.0|109.0g|12.5%||
|**合計**|8.0|872.0g|100.0%|塩分:12.5%|

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=436; I='ねぎ 黴米乳酸麹 水 塩 合計'.split(); r=[4,2,1]; s_s=0.00; salt=0.125; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

- フードプロセッサーは２回に分けたほうが良さそう。
- ソース麹を作ったタッパーを使用する。


---

### 📅 2025-11-29 ねぎ塩麹

##### 🥣 recipe（いい感じ👍）

|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**ねぎ**|4.0|400.0g|54.1%||
|**黴米乳酸麹**|2.0|200.0g|27.0%||
|**水**|0.5|50.0ml|6.8%||
|**塩**|0.9|90.0g|12.2%||
|**合計**|7.4|740.0g|100.0%|塩分:12.2%

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=400; I='ねぎ 黴米乳酸麹 水 塩 合計'.split(); r=[4,2,0.5]; s_s=0.00; salt=0.1216; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

---