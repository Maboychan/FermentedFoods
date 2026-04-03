
### 📅 YYYY-MM-DD

##### 🥣 recipe（いい感じ👍）


##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=600; I='白米 炊飯水 米麹 水 塩 合計'.split(); r=[6,10,1.5,2]; s_s=[0,0,0,0]; salt=0.0; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); liq_s=sum(v*s for v,s in zip(r_norm, s_s)); t_r=max(s_r, (s_r-liq_s)/(1-salt)); s_amt=max(0, t_r-s_r); act_s=(liq_s+s_amt)/t_r; R=r_norm+[s_amt, t_r]; N=[f'塩分:{round(s*100,1)}%' if s != 0 else '' for s in s_s]+[f'塩分:100%']+[f'全体塩分:{round(act_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2) if i<len(r) else round(v,2)}|{round(x*v,1)}{'ml' if n in['水','醤油','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

---


### 📅 2026-04-01

##### 🥣 recipe（いい感じ👍）

###### 材料

<details><summary> 甘酒 </summary><br>
<table>
<tr>
  <th colspan=5> 甘酒 </th>
</tr>
<tr>
  <td><b> 材料 </b></td>
  <td> 割合 </td>
  <td> 分量 </td>
  <td> % </td>
  <td> 備考 </td>
</tr>
<tr>
  <td><b> 白米 </b></td>
  <td> 6 </td>
  <td> 600g </td>
  <td> 30.8% </td>
  <td>  </td>
</tr>
<tr>
  <td><b> 炊飯水 </b></td>
  <td> 10 </td>
  <td> 1000ml </td>
  <td> 51.3% </td>
  <td>  </td>
</tr>
<tr>
  <td><b> 米麹 </b></td>
  <td> 1.5 </td>
  <td> 150g </td>
  <td> 7.7% </td>
  <td>  </td>
</tr>
<tr>
  <td><b> 水 </b></td>
  <td> 2 </td>
  <td> 200ml </td>
  <td> 10.3% </td>
  <td>  </td>
</tr>
<tr>
  <td><b> 合計 </b></td>
  <td> 19.5 </td>
  <td> 1950g </td>
  <td> 100% </td>
  <td> 全体塩分:0.0% </td>
</tr>
</table>
</details>
<details><summary> 生卵 </summary> つる爺の生卵 </details>




##### PyKeysのREPL用ワンライナー
実行するとクリップボードにテーブルがコピーされる。

~~~python
x=600; I='白米 炊飯水 米麹 水 塩 合計'.split(); r=[6,10,1.5,2]; s_s=[0,0,0,0]; salt=0.0; import clipboard; b_r=r[0]; r_norm=[v/b_r for v in r]; s_r=sum(r_norm); liq_s=sum(v*s for v,s in zip(r_norm, s_s)); t_r=max(s_r, (s_r-liq_s)/(1-salt)); s_amt=max(0, t_r-s_r); act_s=(liq_s+s_amt)/t_r; R=r_norm+[s_amt, t_r]; N=[f'塩分:{round(s*100,1)}%' if s != 0 else '' for s in s_s]+[f'塩分:100%']+[f'全体塩分:{round(act_s*100,1)}%']; res="|材料|割合|分量|%|備考|\n|:-:|:-:|:-:|:-:|:-:|\n"+"\n".join(f"|**{n}**|{round(v*b_r,2) if i<len(r) else round(v,2)}|{round(x*v,1)}{'ml' if n in['水','醤油','酒'] else 'g'}|{round(v/t_r*100,1)}%|{note}|" for i,(n,v,note) in enumerate(zip(I,R,N))); clipboard.set(res)
~~~

##### 📝 コメント

---
