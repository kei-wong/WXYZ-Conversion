# WXYZ-Conversion

There is a 500-character English string as follows:

```
JNPGCZBUXHJAVWXGWIZAXTIQYMRRSSYDNUWCJYVZVZZCYZYKWUMOJNZYUJIKCWXUVDDNOYJDXYIXADXJYZNZTSNQDXGUBYSZPRCRPQYIPTXCSIHNZXWFWSQKVYOHWIZJYWZDQSLPIFXRYWYLXWWYDCBWIKJQGWSUXPHCORZXSXLWWOIZPIMQXCWVCMAYWKKPRNWAYYATXCHQCZKTIWIRLOZVQWKXZGYRZUQJXDJQQYMYLNBZXWWMJXPZXKYPGWRETBPPDHUMQMKNUYHFGQKHMYKJKWYTIBZSTOZFHLQVYXLGCNIEXQFAGBWAFMXSWXTCWZKXSAXUZFLUYPWIGKWYUDTOOYYWZYQZXDVJSYSTGJWXNZGZOZSZCXCHZERWCIWYTIPQRWXZWCYYQYUWTNGZXZUBYKYVZWPEKOYZNWKYGPOYXLTWYYTAFYXPXXQWCWSZLMXRGKVCCWLANWWCBZYWLIRYGJRHMKWVBWXWGRLETQNZHYAQUTZK
```

Apply the following transformations to this string in sequence:
- Remove all occurrences of W.
- If the character three positions after X is not X, change that (former) character to E.
- Change all instances of the consecutive charaters YZ to E.

Please provide the 5 characters in the resulting string starting from the 432-th position (counting from the first character as top).

The output from running main in `WXYZConversion.java` is as follows:
```
true
Five characters starting at (including) the 432nd character: RLETQ
```
