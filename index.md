# みんなで変数名を考えてみよう！


## この変数は何を表してる？


``` 

my $total;

$user_id

int price;

```


## この変数名はどう改善できる？


```

kekka: 関数の返り値

name: ユーザーの苗字と名前

active: ブーリアン型で今ユーザーがこのサイトを見ているかを格納する

array: 数値が入った配列

userList: ユーザーの情報が入った配列

element: 1つ上の問題の userList から取り出した値

```


`active` のイメージ図 👇

![image1](https://i.ibb.co/XS0Nc80/Screen-Shot-2022-06-21-at-1-13-08.png)
![image2](https://i.ibb.co/0Yxktks/Screen-Shot-2022-06-21-at-1-15-13.png)



## まとめ


- （なるべく正しい）英語にしよう
- 自分が「いま何の値を扱っているのか？」を意識しよう
  - 単数のもの？
  - 複数あるもの？（配列など）
    - 中身は何になる？ （数値が入っているなら配列の変数名を "array" ではなく "numbers" にするなど


✨ コメントでの説明が要らないくらい分かりやすいコードを書こう！


## 参考


### この変数は何をしてる？


- 1問目: [Perl](https://perlzemi.com/blog/20081103122562.html)
- 2問目: [PHP](https://qiita.com/Kunikata/items/0337c6744a7c8fbc1586)
- 3問目: [C言語](https://www.javadrive.jp/cstart/var/index4.html)


### この変数名はどう改善できる？


- [変数名・関数名の付け方についての個人的ルール \- Qiita](https://qiita.com/Kunikata/items/0337c6744a7c8fbc1586)
- [変数名の付け方をまとめてみた](https://zenn.dev/naoki_oshiumi/articles/aad7e1b3719fad)


### おすすめ拡張機能


- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

