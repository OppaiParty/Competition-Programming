#文字を移動してください

##問題
まず2列に渡って、数字がスペース区切りで、２つ入力されます
それを4行目以降の処理で移動してください
3行目は、4行目以降の処理の数を表しています

left   -> 左から右に値を1つずらします
right  -> 右から左に値を1つずらします
top    -> 下から上に値を1つづらします
bottom -> 上から下に値を1つづらします

||1|2|
|:--|:--|:--|
|1|n1|n2|
|2|n3|n4|

##入力フォーマット

~~~
n1 n2
n3 n4
rn
s1 g
s2 g
:
sn g
~~~

##入力値1

~~~
10 5
4 12
2
left 1
top 2
~~~

##出力値1

~~~
4 10 
5 12
~~~

##入力値2

~~~
6 8 
4 1
3
bottom 2
top 1
left 2
~~~

##出力値2

~~~
4 1
8 6
~~~

##入力値3

~~~
3 17
7 0
3
left 2
top 1
right 1
~~~

##出力値3

~~~
17 0
3 7
~~~