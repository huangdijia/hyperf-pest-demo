# hyperf-pest-demo

## 安装依赖

```shell
composer u -o
```

## 运行测试

- co-phpunit

```shell
php vendor/bin/co-phpunit --prepend test/bootstrap.php -c phpunit.xml --colors=always
```

输出

```shell
PHPUnit 10.2.1 by Sebastian Bergmann and contributors.

Runtime:       PHP 8.1.20
Configuration: /private/tmp/hyperf-pest-demo/phpunit.xml

.                                                                   1 / 1 (100%)

Time: 00:00.012, Memory: 18.00 MB

OK (1 test, 2 assertions)
```

- co-pest
  
```shell
php vendor/bin/co-pest --prepend test/bootstrap.php --colors=always
```

输出

```shell
# 空白
```

- pest-with-plugin

```shell
php vendor/bin/pest --prepend test/bootstrap.php --coroutine --colors=always
```

输出

```shell
   PASS  HyperfTest\Cases\ExampleTest
  ✓ example                                                                                                                                                                                        0.01s  

  Tests:    1 passed (2 assertions)
  Duration: 0.36s
  ```
  