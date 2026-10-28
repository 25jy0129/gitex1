# 見出し1
## 見出し2
### 見出し3
*ここがemタグで強調されます*  
__ここがemタグで強調されます__  
**ここがstrongタグで強調されます**  
__ここがstrongタグで強調されます__  
~~打ち消し線~~  
<details><summary>要約をここに記述する</summary>
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</details>

リスト <UL>
文頭に-、+、*のいずれかを入れるとリストになる。
- HTML
- JAVA  

番号付きリスト <OL>
1. SQL
1. JavaScript
1. SQL  

- [ ] タスク1  
- [x] タスク2  

テーブル（表）を表示する。
|A列|B列|C列|D列|E列|  
|-|:-:|:-|-:|-|  
|あ|い|う|え|お|  
|かか|きき|くく|けけ|ここ|  
|さささ|しし|すすす|せせせ|そそそ|  

プログラムなどのコードをそのまま記述したい場合は、バッククォートで囲む
```
for(int i=0; i<10; i++){
    int rand = (int)(Math.random()*10);
    System.out.println("乱数[" + i + "]:" + rand);
}
```
