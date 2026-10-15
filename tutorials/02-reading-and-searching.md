# Tutorial 2: Read and search text

Use the Ubuntu/WSL terminal in VS Code. These examples create sample files
inside your practice folder.

## Create a sample text file

```bash
cd ~/linux-practice
printf 'apple\nbanana\nblueberry\n' > fruit.txt
```

`>` writes the output into a file, replacing its previous contents. Here,
`printf` writes three lines to `fruit.txt`.

## Read the file

```bash
cat fruit.txt
```

`cat` prints a file's contents in the terminal. For a longer file, use
`less filename`; press `q` to leave `less`.

## Search for matching lines

```bash
grep 'berry' fruit.txt
grep -n 'a' fruit.txt
```

`grep` prints lines matching the text you provide. The `-n` option adds line
numbers. Searches are case-sensitive by default.

## Find files by name

```bash
find ~/linux-practice -name '*.txt'
```

`find` searches a folder tree. The quotes keep the `*.txt` pattern intact so
`find` can match every name ending in `.txt`.

## Practice

Add another fruit to the file, display it, and search for the new fruit:

```bash
printf 'orange\n' >> fruit.txt
cat fruit.txt
grep 'orange' fruit.txt
```

`>>` appends text rather than replacing the file.
