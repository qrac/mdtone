# MDTONE

## Demo

- [Demo Page][link-demo]

## About

Material Design Color を Sass で使いやすいよう変数化しました。

## Use

### デザインツールで使う場合

- ツールに合わせてスウォッチファイルをダウンロードして使用
- NSColorList 形式のスウォッチ(※)は Mac の様々なソフトウェアで共有利用が可能

|          |      Illustrator       |       Photoshop        |           Sketch           | Keynote / Pages / Numbers  |
| :------: | :--------------------: | :--------------------: | :------------------------: | :------------------------: |
| Swatches | [Download][link-dl-a1] | [Download][link-dl-a1] | [Download][link-dl-a2] (※) | [Download][link-dl-a2] (※) |

### コーディングで使う場合

- CSS > [Demo Page][link-demo]の色コードを直接コピー
- SCSS > `/src/scss/tone/_mdtone.scss` を変数ファイルとして include
- Stylus > `/src/stylus/tone/_mdtone.styl` を変数ファイルとして include

npm で `_mdtone.scss` や `_mdtone.styl` をインストールして使えます。

```bash
$ npm i -D mdtone
```

## Reference

- [Color - Style - Google design guidelines](https://material.google.com/style/color.html#color-color-palette)

## License

- CC0 1.0 Public Domain
- Author: [Qrac][link-twitter]
- Author Group: [QRANOKO][link-qranoko]

[link-demo]: https://qrac.github.io/mdtone/
[link-dl-a1]: https://qrac.github.io/mdtone/dist/swatches-mdtone.ase
[link-dl-a2]: https://qrac.github.io/mdtone/dist/swatches-mdtone.clr
[link-dl-b1]: https://qrac.github.io/mdtone/dist/template-mdtone.ai
[link-twitter]: https://twitter.com/Qrac_JP
[link-qranoko]: https://qranoko.jp
