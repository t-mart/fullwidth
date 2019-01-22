# thicc

Convert characters to their fullwidth representation

## Usage Examples

Pipe in text from standard input:

```bash
$ echo "foo" | thc
```

```bash
ｆｏｏ
```

Pass a filename argument:

```bash
$ thc thatfile
```

```bash
ｂａｒ
```

Reverse fullwidth text:

```bash
$ thc -r <<<ｂａｚ
```

`<<<` is not special thicc syntax. It is a shell "herestring". It is one of many ways to pass standard input to a
program on your shell.

```bash
baz
```

Installation
============

```bash
$ pip install --upgrade thicc
```
