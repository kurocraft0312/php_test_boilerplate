# php_test_boilerplate
PHP用のテストテンプレート

# 使い方

## 準備
プロジェクト直下に作成した「index.php」の冒頭に以下のコードを記載してください。

```index.php
<?php
require_once(dirname(__FILE__) . '/test/variable_check.php');
?>
```

## 利用方法
$hogehogeにチェックしたい変数を入れてください。

```index.php
<?php
var_test($hogehoge);
?>
```