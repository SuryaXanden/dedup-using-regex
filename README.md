dedup-using-regex

https://stackoverflow.com/questions/1573361/how-do-i-find-and-remove-duplicate-lines-from-a-file-using-regular-expressions

Find:
^(.*)$((?:\r?\n.*)*?)^\1$\r?\n?

Replace:
$1$2
