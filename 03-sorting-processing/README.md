# Sorting & Text Processing Commands

This section covers Linux commands used to organize, count, transform, and process text files. These commands are especially useful when working with logs, datasets, configuration files, and command output.

## Commands Covered

- `wc` - Count lines, words, and bytes.
- `sort` - Sort lines of text alphabetically or numerically.
- `uniq` - Remove or identify duplicate lines.
- `cut` - Extract specific columns or fields from text.
- `tr` - Translate or replace characters.
- `tee` - Display output and write it to a file simultaneously.

---
# wc Command

## Purpose

The `wc` (word count) command counts the number of lines, words, bytes, or characters in a file. It is commonly used to quickly determine the size and content statistics of text files.

## Syntax

```bash
wc [OPTION]... [FILE]...
```

## Common Options

| Option | Description |
|---------|-------------|
| `-l` | Counts the number of lines. |
| `-w` | Counts the number of words. |
| `-c` | Counts the number of bytes. |

## Examples

```bash
wc numbers.txt
```

Displays the number of lines, words, and bytes in the file.

```bash
wc -l numbers.txt
```

Displays only the number of lines.

```bash
wc -w numbers.txt
```

Displays only the number of words.

```bash
wc -c numbers.txt
```

Displays only the number of bytes.

## Sample Output

See the screenshot below.

![wc Command](../images/wc-command.png)

## Real-World Use Cases

- Count the number of records in a text file.
- Determine the number of lines in a log file.
- Check the size of text files.
- Verify the number of words in documentation or reports.

## Key Takeaways

- `wc` stands for **word count**.
- By default, it displays the number of **lines**, **words**, and **bytes**.
- Use options such as `-l`, `-w`, and `-c` to display specific counts.

## Common Mistakes

- Assuming `wc` only counts words.
- Confusing bytes (`-c`) with characters, especially when working with files containing special or Unicode characters.

## Pro Tip

Combine `wc` with other commands using pipes. For example:

```bash
ls | wc -l
```

This counts the number of items in the current directory.