# About

作者が個人的に使っているリセットCSSです。
好みベースの設計なので、必要に応じて自由に調整してください。

This is a reset CSS that the author uses for personal projects.
It is designed based on personal preferences, so feel free to adjust it as needed.

# インストール

```
npm install @akimeaki/reset-css
```

# 使い方

## 読み込み順

以下の順番で読み込むことで`@akimeaki/reset-css`のスタイルの優先度が一番下になります。

```js
import "@akimeaki/reset-css";
import "上書きしたいオリジナルスタイル.scss";
```

## カスケードレイヤー

`@akimeaki/reset-css`は`aki-reset`layer配下に設定されています。

以下のような形でカスケードレイヤーの順序を設定することを推奨します。

```css
@layer aki-reset, <他に使いたいレイヤー1>, <他に使いたいレイヤー2>;
```

# License

Released under the [MIT license](https://opensource.org/license/mit)
