# 命名規則(python、ファイル・フォルダ操作用)

## ケーススタイル

| スタイル名                         | 記法例             | 主な用途                  | 備考                |
| ----------------------------- | --------------- | --------------------- | ----------------- |
| **パスカルケース (PascalCase)**      | `PascalCase`    | クラス名                  | 単語の先頭をすべて大文字にする   |
| **スネークケース (snake_case)**      | `snake_case`    | 変数名・関数名・モジュール名・パッケージ名 | Pythonの標準的な命名形式   |
| **チェインケース (chain-case)**      | `chain-case`    | 主ファイル名・プロジェクトフォルダ名    | URLやCLIなどでも使用される  |
| **コンスタントケース (CONSTANT_CASE)** | `CONSTANT_CASE` | 定数                    | すべて大文字＋アンダースコア区切り |
| **キャメルケース (camelCase)**       | `camelCase`     | 外部API・SDKで使用されることが多い  | Python内部では非推奨     |

## 命名略語規則
### 変数名によく使われるもの
| 略語            | 意味             | 用途・備考         |
| ------------- | -------------- | ------------- |
| `c`, `ch`     | Character      | 1文字扱う変数       |
| `s`, `str`    | String         | 文字列を扱う変数      |
| `i`, `j`, `k` | 整数 (Fortran由来) | ループカウンタに使用される |
| `buf`, `buff` | Buffer         | 一時的なデータ格納領域   |
| `temp`        | Temporary      | 仮・一時的な値       |
| `n`, `num`    | Number         | 数値・要素数を示す     |
| `x`, `y`, `z` | 座標             | 位置情報などに使用     |
| `r`           | Radius         | 半径            |
| `p`           | Pointer        | ポインタ的な参照を示す   |
| `rect`        | Rectangle      | 長方形領域         |
| `func`        | Function       | 関数            |
| `arg`         | Argument       | 引数            |


### 母音を消して略すパターン
| 略語     | 元の単語      | 意味・用途    |
| ------ | --------- | -------- |
| `ctr`  | Control   | 制御・指令値   |
| `trgt` | Target    | 対象・目標    |
| `cmd`  | Command   | コマンド・命令  |
| `msg`  | Message   | 処理メッセージ  |
| `spd`  | Speed     | 速度       |
| `mv`   | Move      | 移動・動作    |
| `cnst` | Constant  | 一定・定速    |
| `md`   | Mode      | モード      |
| `sts`  | Status    | 状態・ステータス |
| `cnfg` | Configure | 構成・設定情報  |


## ティップス
### 日付接頭辞

### 日付接尾辞

### ID識別
S001T003A001M003_datanogaiyou
| セクション           | 意味            | 例 |
| --------------- | ------------- | - |
| `S001`          | システムまたはシナリオID |   |
| `T003`          | タスクID         |   |
| `A001`          | アクションID       |   |
| `M003`          | モジュールID       |   |
| `_datanogaiyou` | 内容の説明         |   |


## 参考
https://odigo.jp/%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E3%81%AE%E5%91%BD%E5%90%8D%E8%A6%8F%E5%89%87%E3%81%A8%E3%81%AF%EF%BC%9F<br>
https://qiita.com/Shons_a/items/bd6eed229253ee266b7d<br>

