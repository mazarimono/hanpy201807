
## Pandas_DataReaderを使って
## ニュースに切り込む

kyopy20180720     
合同会社長目　小川　英幸     

---

- @mazarimono       
- 主催：はんなりPython、Blockchain勉強会 in Kyoto       
- 最近は自分の会社の決算処理に死んでいます    
- 証券アナリストという資格を持っています。     
- 株の話が大好物です。     
- 来週から企業の決算発表が本格化するのですが、この処理をなんとかPythonでサーッと済ませられるようにしたい     
- そのあたりの良いネタを語り合えないかと・・・     
      
---    

- 本日の話題      
### 投信で損失、個人の半数
https://www.nikkei.com/article/DGXMZO32607510U8A700C1EE9000/      



---

### どんな投資信託が人気かみてみる
- 投信のことならモーニングスター     
http://www.morningstar.co.jp/FundData/FundRankingJyunshisan.do      
     
- トップには日本株のETFが並んでいます。     
===> これには理由が     
      
- それに続くのは米国のREIT     
===> REITとは      

---      

### Pandas_DataReaderで価格の動きを見てみる


--- 

- 導入方法
```python3
pip install pandas_datareader     
```
- 注意　Pandasとは別     
      
- 経済データなどが取れるライブラリ。色々なソースからデータが取得できます。      
http://pandas-datareader.readthedocs.io/en/latest/     
     
- 今回はFREDからデータを取ります。     
https://research.stlouisfed.org/       

===> jupyter notebookへ     

---     

- データがこれだけ取れると機械学習とかにもこれを使っていろいろ調べると、景気の方向とか金融商品の方向とか分かって良いかも。      
- 手数料稼ぎにだまされないために。      
- というよりは・・・・
      
# 完

---- 
