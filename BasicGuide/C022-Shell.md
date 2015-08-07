
### 2.2) erl shell命令简介，执行简单Erlang语句

erl
5 + 6.

Write a module

```
-module(test).
-export([fac/1]).

    fac(0) -> 1;
    fac(N) -> N * fac(N-1).
```

```
3> c(test).
{ok,test}
30> test:fac(20).
2432902008176640000
4> test:fac(40). 
815915283247897734345611269596115894272000000000
32> 
```

