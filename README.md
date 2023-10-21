# OfficeWorkManual

# 事務マニュアル

Hello!  

* リストテスト
	* コラム 1
	* Column 2
		* Indent 1
		* Indent 2
		* Indent 3
		* Indent 4
		* Indent 5

- Dash is also OK
	- Dash Column 1
	- コラム 2
		- インデントはタブ
			- インデントはタブ
				- インデントはタブ
					- インデントはタブ
						- インデントはタブ

1. Numbering List
2. ほげ
	1. 同じ数字を並べてもOK
	1. ほげほげ
	1. ほげほげほげ
	1. ほげほげほげほげ
	1. ほげほげほげほげほげ
		1. ほげほげ
		1. ほげほげほげ
		1. ほげほげほげほげ
		1. ほげほげほげほげほげ
			1. ほげほげ
			1. ほげほげほげ
			1. ほげほげほげほげ
			1. ほげほげほげほげほげ

改行は空白2つ  
brでも可<br>
<br>
<br>
<br>
`インライン表示`  
`
	float i=0;
`
```php
// コードブロック (php:未検証)
echo "ナベアツコード";

const MAX=1000;

for($i=1; $i<=MAX; $i++){
	$num = strval(i);
	if(i%3 == 0 || (false !== strpos($num, '3'))){
		echo 'アホ';
	} else echo $num;
}
```
<br>

リンク：[Google](https://www.google.co.jp)  
リンク：[Yahoo! JAPAN](https://www.yahoo.co.jp)<br>

引用
> 引用元：広辞苑

> 引用テーブル
>> 引用テーブル
>>> 引用テーブル
>>>> 引用テーブル
>>>>> 引用テーブル
>>>>>> 引用テーブル
>>>>>>> 引用テーブル
>>>>>>>> 引用テーブル
>>>>>>>>> 引用テーブル
>>>>>>>>>> 引用テーブル

画像  
![低クヲリティ](sample.png "低クヲリティ")

htmlのようにimgタグを使用することも可  
<img width="320" alt="低クヲリティ" src="sample.png">  
<img width="240" alt="低クヲリティ" src="sample.png">  
<img width="180" alt="低クヲリティ" src="sample.png">  
<img width="120" alt="低クヲリティ" src="sample.png">  
<img width="90" alt="低クヲリティ" src="sample.png">  
<img width="60" alt="低クヲリティ" src="sample.png">  
<img width="45" alt="低クヲリティ" src="sample.png">  

テーブル  
| 列1 | 列2 | 列3 | 列3 | 列3 |
| --- | --- | --- | --- | --- |
| 行1 | 行1 | 行1 | 行1 | 行1 |
| 行2 | 行2 | 行2 | 行2 | 行2 |
| 行3 | 行3 | 行3 | 行3 | 行3 |

文字色指定  
<font color="cyan">赤っぽいな</font>  
<font color="magenta">緑っぽいな</font>  
<font color="yellow">青っぽいな</font>  

*ITALIC*  
**BOLD**  
***BOLD ITALIC***

~~打ち消し~~  

水平線
***
ダッシュ(ハイフン)でも可
---
hrでも可
<hr>

注釈  
スーパーマリオRPG[^1]  

[^1]: https://www.nintendo.com/jp/switch/a8lua/index.html

エスケープ  
\`インライン表示されなくなる`