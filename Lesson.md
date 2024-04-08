# 4.2 Comparison Operators

Now that we know what Booleans are, let's take a look at various methods we can use to produce/evaluate `True` or `False`.

Just as there are arithmetic operators (`+`, `-`, `*`, `/`, `**`) and string operators (`+`) that allow us to form mathematical and string operations, boolean expressions are formed using **`comparision operators`** or **`logical operators`**.

## Comparing Numbers (`int` or `float`)

| Comparison Operator | Description              | Example  | Result  |
| ------------------- | ------------------------ | -------- | ------- |
| `<`                 | Less than                | `6 < 7`  | `True`  |
| `>`                 | Greater than             | `6 > 7`  | `False` |
| `<=`                | Less than or equal to    | `7 <= 7` | `True`  |
| `>=`                | Greater than or equal to | `8 >= 7` | `True`  |
| `==`                | Equivalent               | `6 == 7` | `False` |
| `!=`                | Not equivalent           | `6 != 7` | `True`  |

 <span style="color:red">
<b>NOTE:</b> To compare if two numbers are equal, we use <b>TWO</b> equal signs instead of one. When we use one equal sign, remember that this is the <b>assignment operator</b>.
</span> 

## Comparing Strings
We can also use the same comparison operators to compare strings. 

| Comparison Operator | Description               | Example           | Result  |
| ------------------- | ------------------------- | ----------------- | ------- |
| `<`                 | Earlier in the dictionary | `"hello" < "hi"`  | `True`  |
| `>`                 | Later in the dictionary   | `"hello" > "hi"`  | `False` |
| `<=`                | Less than or equal to     | `"hello" <= "hi"` | `True`  |
| `>=`                | Greater than or equal to  | `"hello" >= "hi"` | `False` |
| `==`                | Equivalent                | `"hello" == "hi"` | `False` |
| `!=`                | Not equivalent            | `"hello" != "hi"` | `True`  |

### Order in Python's "Dictionary"
The following sequence below is the order in which Python compares strings in it's own "dictionary".
```
(space)!"#$%&'()*+,-./0123456789:;<=>?@ABCDEFGHIJKLMNOPQRSTUVWXYZ[ \ ]^_`abcdefghijklmnopqrstuvwxyz{|}~
```