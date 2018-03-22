# JavaMap.EntryInterface
Map.Entryインタフェース

## 処理
Map.Entryインタフェースを使ってHashMapの配列を出力。

## コード
```
import java.util.HashMap;
import java.util.Map.Entry;

public class Mapentry {

	public static void main(String[] args) {
		HashMap<String, String> enemyMap = new HashMap<String, String>();
		enemyMap.put("ザコ", "スライム");
		enemyMap.put("中ボス", "ドラゴン");
		enemyMap.put("ラスボス", "魔王");
		for (Entry<String, String> entry : enemyMap.entrySet()) {
			System.out.print(entry.getKey() + ",");
			System.out.println(entry.getValue());
		}

	}

}
```

## 出力結果  
```
中ボス,ドラゴン
ラスボス,魔王
ザコ,スライム
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 統合開発環境(IDE) | Eclipse 4.7.0 Oxygen |
| 開発言語 | Java8 |
