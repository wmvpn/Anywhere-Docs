# 添加 Intent Extras

使用以下格式添加 Extras

``` bash
-e|--es <EXTRA_KEY> <EXTRA_STRING_VALUE>

--ez <EXTRA_KEY> <EXTRA_BOOLEAN_VALUE>

--ei <EXTRA_KEY> <EXTRA_INT_VALUE>

--el <EXTRA_KEY> <EXTRA_LONG_VALUE>

--ef <EXTRA_KEY> <EXTRA_FLOAT_VALUE>

--eu <EXTRA_KEY> <EXTRA_URI_VALUE>

--ecn <EXTRA_KEY> <EXTRA_COMPONENT_NAME_VALUE>

--eia <EXTRA_KEY> <EXTRA_INT_VALUE>[,<EXTRA_INT_VALUE...]

--ela <EXTRA_KEY> <EXTRA_LONG_VALUE>[,<EXTRA_LONG_VALUE...]

--efa <EXTRA_KEY> <EXTRA_FLOAT_VALUE>[,<EXTRA_FLOAT_VALUE...]
```

例如：
``` bash
--es name absinthe
--ei id 123
...
```
