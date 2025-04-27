# インストール

```
npm install @akimeaki/reset-css
```

# 使い方

## 読み込み準

以下の順番で読み込むことで`@akimeaki/reset-css`のスタイルが一番下になります。

```js
import "@akimeaki/reset-css";
import "上書きしたいオリジナルスタイル.scss";
```

## カスケードレイヤー

`@akimeaki/reset-css`は`aki-reset`layer配下に設定されています。

以下のような形でカスケードレイヤーの順序を設定することを推奨

```css
@layer aki-reset, <他に使いたいレイヤー1>, <他に使いたいレイヤー2>;
```

# License

Released under the [MIT license](https://opensource.org/license/mit)
