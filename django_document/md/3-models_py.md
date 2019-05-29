# models.py
ここではsystem/models.pyについて記述する．

## ER図
本システムのデータベースは下図のようになっている
![ER図](../img/graph_system.png)

四角で囲まれているものがテーブルで，その中に含まれるidから始まる縦一列がカラム名である．  

データベースはmodels.pyで作られており，