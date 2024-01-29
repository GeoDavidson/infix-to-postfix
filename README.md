# Infix To postfix

Convert infix notation to postfix notation with the shunting yard algorithm.

## Examples

## Ex.1

```text
input: 10 + 5
```

```text
output: 10 5 +
```

## Ex.2

```text
input: 4 * -5
```

```text
output: 4 -5 *
```

## Ex.3

```text
input: 25 - 3 * 10 / 2
```

```text
output: 25 3 10 * 2 / -
```

## Ex.4

```text
input: 16 - 2 * ( 3 * 18 / 2 )
```

```text
output: 16 2 3 18 * 2 / * -
```

## Ex.5

```text
input: ( 6 + -9 - -2 ) * ( 4 + 3 - 11 )
```

```text
output: 6 -9 + -2 - 4 3 + 11 - *
```
