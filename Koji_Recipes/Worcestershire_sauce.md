# ウスターソース麹（うすたーそーす こうじ）


### 📅 YYYY-MM-DD

##### 🥣 recipe（いい感じ👍）

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=150; I='米麹 水 ウスターソース 塩 合計'.split(); r=[1,1.5,2]; s_s=0.06; salt=0.058; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

---



### 📅 2026-02-10 トンカツソース麹

##### 🥣 recipe（いい感じ👍）

|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**トンカツソース**|3.0|270.0g|59.3%||
|**米麹**|1.0|90.0g|19.8%||
|**水**|1.0|90.0ml|19.8%||
|**塩**|0.06|5.0g|1.1%||
|**合計**|5.06|455.0g|100.0%|塩分:2.0%|

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=270; I='トンカツソース 米麹 水 塩 合計'.split(); r=[3,1,1]; s_s=0.046; salt=0.02; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

ガラス瓶500で8分目。

2026-02-10 15:14 保温開始。

2026-02-11 16:36 完成。柔らかく膨らんでドロドロ

---



### 📅 2026-01-12 ウスターソース塩麹

##### 🥣 recipe（いい感じ👍）

|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**米麹**|1.0|150.0g|21.5%||
|**水**|1.5|225.0ml|32.3%||
|**ウスターソース**|2.0|300.0g|43.0%||
|**塩**|0.15|22.5g|3.2%||
|**合計**|4.65|697.5g|100.0%|塩分:5.8%|
##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=150; I='米麹 水 ウスターソース 塩 合計'.split(); r=[1,1.5,2]; s_s=0.06; salt=0.058; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

2026-01-12 15:20 材料を混ぜるだけ。
<img width="400" alt="画像" src="images/20260112_1.png">


香りが強いのでディルで使ったタッパーを使用。
<img width="400" alt="画像" src="images/20260112_2.png">


2026-01-14 21:25 中瓶２つできました。
<img width="400" alt="画像" src="images/20260114.png">


---


