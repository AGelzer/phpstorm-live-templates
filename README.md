Подробнее с шаблонами можно познакомиться [здесь](https://www.jetbrains.com/help/phpstorm/2016.1/live-templates.html).
Все шаблоны предназначены для php и yii2. В качестве аббревиатуры выступает заголовок.

## HTML шаблоны

### =
```
<?= $END$ ?>
```
PHP | Echo php code.

### ec
```
<?= $END$ ?>
```
PHP | Echo php code.

### yt
```
<?= Yii::t('frontend', '$SELECTION$') ?>
```
YII2 | Translation of word via Yii:t()

### php
```
<?php $END$ ?>
```
PHP | Open php tag

### nf
```
<?= number_format($VAR$, 0, ',', ' ') ?>
```
PHP | Number Format

### foreach
```
<?php foreach($ARRAY$ as $KEY$ => $VALUE$): ?>
    $SELECTION$
<?php endforeach ?>
```
PHP | Generates/surrounds selection with foreach

### if
```
<?php if ($CONDITION$) : ?>
    $SELECTION$
<?php endif; ?>
```
PHP | Generates/surrounds selection with if

## PHP шаблоны

### rmt
```
$this->registerMetaTag([
    'name' => '$TAGNAME$',
    'content' => $SELECTION$,
]);
```
Yii2 | Register Meta-tags

### 