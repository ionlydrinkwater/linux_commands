# Tutorial 1: Navigate files and folders

Run these commands in the Ubuntu/WSL terminal inside VS Code. If you followed
the setup guide, your current folder should be `~/linux-practice`.

## See where you are

```bash
pwd
```

`pwd` prints the current working directory. In Ubuntu, `~` is shorthand for
your home folder.

## List folder contents

```bash
ls
ls -la
```

`ls` lists files and folders. The `-l` option shows details and `-a` includes
hidden entries (names that start with a dot).

## Make and enter a folder

```bash
mkdir animals
cd animals
pwd
cd ..
```

`mkdir` creates a directory. `cd` changes directory; `..` means the parent
directory. Try `cd ~` to return to your home folder, then return to the
practice folder with:

```bash
cd ~/linux-practice
```

## Practice

Create a folder named `week1` inside your practice folder, enter it, and check
its location. Then go back to the practice folder.

```bash
mkdir week1
cd week1
pwd
cd ..
```

If you get “File exists,” the folder was already created; use `cd week1` to
continue.
