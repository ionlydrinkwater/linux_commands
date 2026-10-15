# Tutorial 3: Create, copy, and move files

Run these examples in your practice folder. They only use files created for
these lessons.

## Create a file and add text

```bash
cd ~/linux-practice
touch notes.txt
printf 'My first Linux notes\n' > notes.txt
cat notes.txt
```

`touch` creates an empty file if it does not exist. `>` writes text into the
file and replaces its contents if it already exists.

## Copy a file

```bash
cp notes.txt notes-copy.txt
ls
```

`cp source destination` copies a file and leaves the original in place.

## Rename or move a file

```bash
mv notes-copy.txt saved-notes.txt
ls
```

`mv` renames a file when the destination is in the same folder. It can also
move a file into another folder:

```bash
mkdir archive
mv saved-notes.txt archive/
ls archive
```

## Remove a practice file

```bash
rm archive/saved-notes.txt
ls archive
```

`rm` permanently removes the named file; it does not move it to a recycle bin.
For this exercise, remove only the practice file shown above. Avoid `rm -r`
and never run a removal command on a path unless you have checked it carefully.

## Practice

Create `todo.txt`, copy it to `todo-backup.txt`, then rename the backup to
`todo-done.txt`. Use `ls` to check your results.
