# 大根塩麹（だいこん しお こうじ）

### 📅 YYYY-MM-DD
##### 🥣 recipe（いい感じ👍）


##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=960; I='大根 米麹 塩 合計'.split(); r=[3,1]; s_s=[0,0]; salt=0.07; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); liq_s=sum(v*s for v,s in zip(r_norm, s_s)); t_r=max(s_r, (s_r-liq_s)/(1-salt)); s_amt=max(0, t_r-s_r); act_s=(liq_s+s_amt)/t_r; R=r_norm+[s_amt, t_r]; N=[f'塩分:{round(s*100,1)}%' if s != 0 else '' for s in s_s]+[f'塩分:100%']+[f'全体塩分:{round(act_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2) if i<len(r) else round(v,2)}|{round(x*v,1)}{'ml' if n in['水','醤油','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

---

### 📅 2026-06-27 大根塩麹（青果市場）

##### 🥣 recipe（いい感じ👍）

|   材料    |  割合  |   分量    |   %    |    備考     |
| :-----: | :--: | :-----: | :----: | :-------: |
| **大根**  | 6.0  | 1300.0g | 62.0%  |           |
| **玄米麹** | 2.0  | 433.3g  | 20.7%  |           |
|  **水**  | 1.0  | 216.7ml | 10.3%  |           |
|  **塩**  | 0.11 | 146.8g  |  7.0%  |  塩分:100%  |
| **合計**  | 1.61 | 2096.8g | 100.0% | 全体塩分:7.0% |

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=1300; I='大根 玄米麹 水 塩 合計'.split(); r=[6,2,1]; s_s=[0,0,0]; salt=0.07; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); liq_s=sum(v*s for v,s in zip(r_norm, s_s)); t_r=max(s_r, (s_r-liq_s)/(1-salt)); s_amt=max(0, t_r-s_r); act_s=(liq_s+s_amt)/t_r; R=r_norm+[s_amt, t_r]; N=[f'塩分:{round(s*100,1)}%' if s != 0 else '' for s in s_s]+[f'塩分:100%']+[f'全体塩分:{round(act_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2) if i<len(r) else round(v,2)}|{round(x*v,1)}{'ml' if n in['水','醤油','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント



---

### 📅 2026-04-11 大根塩麹（節子さん）

##### 🥣 recipe（いい感じ👍）

|   材料    |  割合  |   分量    |   %    |    備考     |
| :-----: | :--: | :-----: | :----: | :-------: |
| **大根**  | 6.0  | 936.0g  | 62.0%  |           |
| **玄米麹** | 2.0  | 312.0g  | 20.7%  |           |
|  **水**  | 1.0  | 156.0ml | 10.3%  |           |
|  **塩**  | 0.11 | 105.7g  |  7.0%  |  塩分:100%  |
| **合計**  | 1.61 | 1509.7g | 100.0% | 全体塩分:7.0% |

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=936; I='大根 玄米麹 水 塩 合計'.split(); r=[6,2,1]; s_s=[0,0,0]; salt=0.07; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); liq_s=sum(v*s for v,s in zip(r_norm, s_s)); t_r=max(s_r, (s_r-liq_s)/(1-salt)); s_amt=max(0, t_r-s_r); act_s=(liq_s+s_amt)/t_r; R=r_norm+[s_amt, t_r]; N=[f'塩分:{round(s*100,1)}%' if s != 0 else '' for s in s_s]+[f'塩分:100%']+[f'全体塩分:{round(act_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2) if i<len(r) else round(v,2)}|{round(x*v,1)}{'ml' if n in['水','醤油','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~



##### 📝 コメント

2026-04-11 21:32 材料

<img width="400" alt="画像" src="images/20260411_1.jpg"> 

2026-04-11 21:34 塩きり麹を作る。

<img width="400" alt="画像" src="images/20260411_2.jpg"> 

2026-04-11 21:37 大根おろしと水を混ぜ混ぜ。

<img width="400" alt="画像" src="images/20260411_3.jpg"> 

2026-04-11 21:42 丸いタッパーでスレスレ。

<img width="400" alt="画像" src="images/20260411_4.jpg"> 

2026-04-11 21:45 中瓶に分ける。

<img width="400" alt="画像" src="images/20260411_5.jpg"> 

2026-04-11 21:47 保温開始。

<img width="400" alt="画像" src="images/20260411_6.jpg"> 

2026-04-11 21:48 保温開始。

<img width="400" alt="画像" src="images/20260411_7.jpg"> 





---




---


### 📅 2026-04-08 大根塩麹（節子さん）

##### 🥣 recipe（いい感じ👍）

|   材料    |  割合  |   分量    |   %    |    備考     |
| :-----: | :--: | :-----: | :----: | :-------: |
| **大根**  | 6.0  | 1200.0g | 62.0%  |           |
| **玄米麹** | 2.0  | 400.0g  | 20.7%  |           |
|  **水**  | 1.0  | 200.0ml | 10.3%  |           |
|  **塩**  | 0.11 | 135.5g  |  7.0%  |  塩分:100%  |
| **合計**  | 1.61 | 1935.5g | 100.0% | 全体塩分:7.0% |

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=1200; I='大根 玄米麹 水 塩 合計'.split(); r=[6,2,1]; s_s=[0,0,0]; salt=0.07; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); liq_s=sum(v*s for v,s in zip(r_norm, s_s)); t_r=max(s_r, (s_r-liq_s)/(1-salt)); s_amt=max(0, t_r-s_r); act_s=(liq_s+s_amt)/t_r; R=r_norm+[s_amt, t_r]; N=[f'塩分:{round(s*100,1)}%' if s != 0 else '' for s in s_s]+[f'塩分:100%']+[f'全体塩分:{round(act_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2) if i<len(r) else round(v,2)}|{round(x*v,1)}{'ml' if n in['水','醤油','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

2026-04-08 18:04 材料。

<img width="400" alt="画像" src="images/20260408_1.jpg">

2026-04-08 18:06 塩きり麹を作る

<img width="400" alt="画像" src="images/20260408_2.jpg"> 

2026-04-08 18:07 大きいボウルに変更。

<img width="400" alt="画像" src="images/20260408_3.jpg"> 

2026-04-08 18:14 大根も混ぜ混ぜ。

<img width="400" alt="画像" src="images/20260408_4.jpg"> 

2026-04-08 18:19 塩水を追加。

<img width="400" alt="画像" src="images/20260408_5.jpg"> 

2026-04-08 18:22 いい感じ。

<img width="400" alt="画像" src="images/20260408_6.jpg"> 

2026-04-08 18:23 保温開始。

<img width="400" alt="画像" src="images/20260408_7.jpg"> 

2026-04-11 18:56 225g×8本

<img width="400" alt="画像" src="images/20260411_0.jpg"> 



---


### 📅 2026-04-03 大根塩麹（つるじい）

##### 🥣 recipe（いい感じ👍）

|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**大根**|9.0|762.0g|64.4%||
|**米麹**|3.0|254.0g|21.5%||
|**水**|1.0|84.7ml|7.2%||
|**塩**|0.11|82.8g|7.0%|塩分:100%|
|**合計**|1.55|1183.5g|100.0%|全体塩分:7.0%|

|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**大根**|9.0|762.0g|59.8%||
|**米麹**|3.0|254.0g|19.9%||
|**水**|2.0|169.3ml|13.3%||
|**塩**|0.12|89.2g|7.0%|塩分:100%|
|**合計**|1.67|1274.6g|100.0%|全体塩分:7.0%|

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=762; I='大根 米麹 水 塩 合計'.split(); r=[9,3,2]; s_s=[0,0,0]; salt=0.07; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); liq_s=sum(v*s for v,s in zip(r_norm, s_s)); t_r=max(s_r, (s_r-liq_s)/(1-salt)); s_amt=max(0, t_r-s_r); act_s=(liq_s+s_amt)/t_r; R=r_norm+[s_amt, t_r]; N=[f'塩分:{round(s*100,1)}%' if s != 0 else '' for s in s_s]+[f'塩分:100%']+[f'全体塩分:{round(act_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2) if i<len(r) else round(v,2)}|{round(x*v,1)}{'ml' if n in['水','醤油','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

2026-04-03 13:04 材料

<img width="400" alt="画像" src="images/20260403_1.jpg"> 

2026-04-03 13:07 塩きり麹にする。

<img width="400" alt="画像" src="images/20260403_2.jpg"> 

2026-04-03 13:11 大根に混ぜるが、水気が少ない。

<img width="400" alt="画像" src="images/20260403_3.jpg">

2026-04-03 13:20 水と塩を追加。

<img width="400" alt="画像" src="images/20260403_4.jpg"> 

2026-04-03 13:21 水分量もいい感じ。

<img width="400" alt="画像" src="images/20260403_5.jpg"> 

2026-04-03 13:26 丸タッパーに収まる。

<img width="400" alt="画像" src="images/20260403_6.jpg">

2026-04-03 14:30 保温開始。

<img width="400" alt="画像" src="images/20260403_7.jpg"> 

2026-04-05 21:28 脱気瓶250×5本

<img width="400" alt="画像" src="images/20260405_1.jpg"> 






---


### 📅 2026-03-30 大根塩麹（つるじい）

##### 🥣 recipe（いい感じ👍）

|    材料     |  割合  |   分量    |   %    |    備考     |
| :-------: | :--: | :-----: | :----: | :-------: |
| **つる爺大根** | 3.0  | 900.0g  | 69.8%  |           |
|  **玄米麹**  | 1.0  | 300.0g  | 23.2%  |           |
|   **塩**   | 0.1  |  90.3g  |  7.0%  |  塩分:100%  |
|  **合計**   | 1.43 | 1290.3g | 100.0% | 全体塩分:7.0% |
塩水（7%）を100g追加


##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=900; I='つる爺大根 玄米麹 塩 合計'.split(); r=[3,1]; s_s=[0,0]; salt=0.07; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); liq_s=sum(v*s for v,s in zip(r_norm, s_s)); t_r=max(s_r, (s_r-liq_s)/(1-salt)); s_amt=max(0, t_r-s_r); act_s=(liq_s+s_amt)/t_r; R=r_norm+[s_amt, t_r]; N=[f'塩分:{round(s*100,1)}%' if s != 0 else '' for s in s_s]+[f'塩分:100%']+[f'全体塩分:{round(act_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2) if i<len(r) else round(v,2)}|{round(x*v,1)}{'ml' if n in['水','醤油','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

2026-03-30 14:17:30 材料。

<img width="400" alt="画像" src="images/20260330_1.jpg">

2026-03-30 14:17:40 麹に塩を加える。

<img width="400" alt="画像" src="images/20260330_2.jpg">

2026-03-30 14:18 浴回混ぜて塩きり麹を作る。

<img width="400" alt="画像" src="images/20260330_3.jpg">


2026-03-30 14:20 大根に塩きり麹を混ぜながら加える。

<img width="400" alt="画像" src="images/20260330_4.jpg">

2026-03-30 14:23 良く混ぜてタッパーに移す。

<img width="400" alt="画像" src="images/20260330_5.jpg">

2026-03-30 14:28 ギリ入った。（机上値1290g）

<img width="400" alt="画像" src="images/20260330_6.jpg">

2026-03-30 14:41 保温開始。

<img width="400" alt="画像" src="images/20260330_7.jpg">



---


### 📅 2026-01-18 大根塩麹

##### 🥣 recipe（いい感じ👍）

|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**大根**|3.0|990.0g|69.8%||
|**黴米乳酸麹**|1.0|330.0g|23.2%||
|**塩**|0.3|99.4g|7.0%||
|**合計**|4.3|1419.4g|100.0%|塩分:7.0%|

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=990; I='大根 黴米乳酸麹 塩 合計'.split(); r=[3,1]; s_s=0.00; salt=0.07; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

2026-01-18 15:11 保温開始。
<img src="images/2026-01-18.jpeg" alt="丸いタッパーに大根塩麹が並々入った画像" width="400">

---

### 📅 2026-01-03 大根塩麹

##### 🥣 recipe（いい感じ👍）


|材料|割合|分量|%|備考|
|:-:|:-:|:-:|:-:|:-:|
|**大根**|3.0|834.0g|69.8%||
|**黴米乳酸麹**|1.0|278.0g|23.2%||
|**塩**|0.3|83.7g|7.0%||
|**合計**|4.3|1195.7g|100.0%|塩分:7.0%

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=834; I='大根 黴米乳酸麹 塩 合計'.split(); r=[3,1]; s_s=0.00; salt=0.07; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

2026-01-03 17:40 材料を全部混ぜて保温開始。

<img width="400" alt="画像" src="images/20260103_1.png">

<img width="400" alt="画像" src="images/20260103_2.png">


---

### 📅 2025-12-09 大根おろし塩麹

##### 🥣 recipe（いい感じ👍）

##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=800; I='大根 黴米乳酸麹 塩 合計'.split(); r=[3,1]; s_s=0.00; salt=0.07; import clipboard; b_r=r[0]; r=[v/b_r for v in r]; s_r=sum(r); t_r=max(s_r, (s_r-r[-1]*s_s)/(1-salt)); salt_amt=max(0, t_r-s_r); actual_s=(r[-1]*s_s+salt_amt)/t_r; R=r+[salt_amt, t_r]; N=['']*(len(r)+1)+[f'塩分:{round(actual_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2)}|{round(x*v,1)}{'ml' if n in['水','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for n,v,note in zip(I,R,N)); clipboard.set(res)
~~~

##### 📝 コメント

2025-12-09 12:12 うま旨い。粒感が気になる。
2025-12-08 14:53 保温開始。

---