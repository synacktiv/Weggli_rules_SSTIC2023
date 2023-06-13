Here is a curated list of weggli queries
========================================

You can read them and use them one by one, or launch them by batch:

Usage:

```bash
$ bash dangerous_functions.qry code.c
$ bash malloc_overflow.qry -e cc sourcedir/
```

There is threee categories:

1. dangerous functions: such as strcpy, system, etc..
2. stack : tries to detect copie son stack, on other things..
3. malloc : finding overflows in malloc functions

They should be autodocumented, so read the source.

