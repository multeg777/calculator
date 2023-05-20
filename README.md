# Калькулятор

Выполняет математические операции

## Требования

- PHP 7.4

## Установка

```bash
$ composer require multeg777/calculator
```

## Использование

### Сложение
```php
<?php
$calculator = new Calculator();
echo $calculator->add(5, -3); // 2
```