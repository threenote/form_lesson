# formレッスン理解度確認テスト

## 注意事項

- 回答はすべて埋めるようお願いします。
- レビュー依頼の際にこのファイルも合わせてプッシュしてください。

## 問題

1. formタグに必要な二つの属性とはなんですか？
  - action,method

2. 入力必須にするためにはなんという属性が必要ですか？
  - input要素のrequired属性

3. name属性はどのような役割がありますか？
  - スクリプト言語などから参照できるよう名前を指定する

4. 送信ボタンのtype属性は、なにである必要がありますか？
  - submit

5. 入力欄にあらかじめ記入されている薄い灰色のテキストを設定するにはどうしたらいいですか？
  -
  <form action="" method="post">
  <p>
  <label>電話番号：
  <br><input type="tel" name="telNumber" placeholder="090-1234-5678">
  </label>
  </p>
  <p>
  <label>メールアドレス：
  <br><input type="email" name="mailAddress" placeholder="info@example.com">
  </label>
  </p>
  <p><input type="submit" value="送信"></p>
</form>

6. 擬似クラス`:focus`はどのような時適応するcssのことですか？
  - ユーザーが要素をクリックやタップをしたり、キーボードの「タブ」キーで選択したときに適応する

7. inputタグやselectタグに`appearance: none;`を指定するとどうなりますか？また、なぜ設定する必要があるのですか？
  - デフォルトのスタイルを無効にする
  - macOSでのChromiumベースのブラウザーでは、検索ボックスはスタイル設定の制限があり、heightやfont-sizeを自在に調整ができないためappearance:noneを設定しないといけない。

8. ベンダープレフィックスとはなんですか？
  - cssの新しいプロパティにつけて、記述したプロパティが拡張機能であることを、各ブラウザに示すために使われる識別子です。