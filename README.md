
## Description
This is library to convert UTF-8 strings in to normal string
Copy code from: https://xuanthulab.net/su-dung-composer-trong-lap-trinh-php.html

`trương hoàng ngọc lâm` -> `truong hoang ngoc lam`

## Install

```
composer require hoangngoclam/test_lib
```
## Using

```
<?php
use Hoangngoclam\TestLib\Convert;
$text = Convert::convertLatin("Xin chào Việt Nam");
echo ($text);
```


