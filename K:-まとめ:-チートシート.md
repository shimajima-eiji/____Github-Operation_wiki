Wiki上で表記されるものを列挙。

## リッチエディタ標準機能
### 見出しタグ
リッチエディタではh3までだが、h6まで使える

# h1
## h2
### h3
#### h4
##### h5
###### h6

```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```

### リンク(画像)
[リンク](#h1)

画像（重いので略）
```
[リンク](URL)

![altタグ文字](URL)
```

### 文字修飾
**太文字**

_斜め文字_

`コード`
```
**太文字**

_斜め文字_

`コード`
```

### リスト
* 箇条書き

1. 順番

> 引用

***
```
* 箇条書き

1. 順番

> 引用

***
```

## リッチエディタで使えないもの
### コードブロック
自動的に補完されてしまうので、ソースコードに+を付与している。  
使用時は+を削除すること
```
コードブロック
```

```
+```
+コードブロック
+```
```

### テーブル
|項目１|項目２|
|---|---|
|テスト|テスト|

```
|項目１|項目２|
|---|---|
|テスト|テスト|
```

### 絵文字
[多いので詳細](https://www.webfx.com/tools/emoji-cheat-sheet/)👍 

😄 
```
:smile:
```

## HTMLタグを打ち込むもの
### アコーディオン
<details><summary>見出し文字</summary><div>
内容
</div></details>

```
<details><summary>見出し文字(クリックで開閉)</summary><div>
内容
</div></details>
```

見やすさを考慮するなら

<details><summary>見出し文字(クリックで開閉)</summary><div>

---

内容

---

</div></details>

```
<details><summary>見出し文字(クリックで開閉)</summary><div>
---
内容
---
</div></details>
```

https://qiita.com/nomurasan/items/29a704baa6d91def607c