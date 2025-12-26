# このパッケージについて / About

このパッケージは、作者個人の利用を主目的として作成したリセットCSSです。
特定の思想や好みに基づいて設計されており、汎用的な利用を保証するものではありません。

This package is a reset CSS primarily created for the author's personal use.
It is designed based on specific preferences and opinions, and is not intended to be a universal solution.

考え方や挙動が合う場合は、自由に利用・カスタマイズしてください。

If its behavior and design philosophy fit your needs, feel free to use and customize it.

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
