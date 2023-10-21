# OfficeWorkManual

# 事務マニュアル
## 事務マニュアル
### 事務マニュアル
#### 事務マニュアル
##### 事務マニュアル
###### 事務マニュアル

Hello!  

* リストテスト
	* コラム 1
	* Column 2
		* Indent 1

- Dash is also OK
	- Dash Column 1
	- コラム 2
		- インデントはタブ

1. Numbering List
2. ほげ
	1. 同じ数字を並べてもOK
	1. ほげほげ
	1. ほげほげほげ
	1. ほげほげほげほげ
	1. ほげほげほげほげほげ

改行は空白2つ  
brでも可<br>
<br>
`インライン表示`  
`
	int i=0;
`
```java
// コードブロック (java:未検証)
public class Main {
	public static void main(String[] args){
		System.out.println("ナベアツコード");

		int max=1000;
		
		for(int i=1; i<=max; i++){
			String num = Integer.toString(i);
			if(i%3 == 0 || num.contains("3")){
				System.out.println("アホ");
			} else System.out.println(num);
		}
	}
}
```
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

画像  
![低クヲリティ](sample.png "低クヲリティ")

htmlのようにimgタグを使用することも可  
<img width="320" alt="低クヲリティ" src="sample.png">  
<img width="240" alt="低クヲリティ" src="sample.png">  
<img width="180" alt="低クヲリティ" src="sample.png">  

テーブル  
| 列1 | 列2 | 列3 |
| --- | --- | --- |
| 行1 | 行1 | 行1 |
| 行2 | 行2 | 行2 |
| 行3 | 行3 | 行3 |

文字色指定  
<font color="red">赤っぽいな</font>  
<font color="gree">緑っぽいな</font>  
<font color="blue">青っぽいな</font>  

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
スーパーマリオワンダー[^1]  

[^1]: https://www.nintendo.com/jp/switch/aqmxa/index.html

エスケープ  
\`インライン表示されなくなる`