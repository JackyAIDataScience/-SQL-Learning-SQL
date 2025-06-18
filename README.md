# -SQL-Learning-SQL                                                   
01.コース紹介 ~ SQLとは？ ~ 環境構築｜初心者向け [Introduction]                
02.データベースのテーブルとは                                               
03.SELECT文｜データベースからデータ抽出する方法                            
For Example Query : SELECT  商品分類 FROM test_table;                   
04.
05. 
06.
SELECT  商品名,sum(売上金額)
from test_table
GROUP by 商品名
order by sum(売上金額)
