---
title: Bash ls
---

## Bash ls

`ls` is a command on Unix-like operating systems to list contents of a directory, for example folder and file names.


### Usage

```bash
ls [options] [/path/directory/file/]
```
You can list the items in any directory without even entering the directory. Consider you are in a directory with folders- Test1,Test2. You're in the parent directory you can list all files in Test1 as follows-
`ls Test1`

Most used options:

* `-a`, all files and folders, including ones that are hidden and start with a `.`
* `-l`, List in long format
* `-G`, enable colorized output.

### Example:

List files in `freeCodeCamp/guide/`

```bash
ls                                                                ⚬ master
CODE_OF_CONDUCT.md bin                package.json       utils
CONTRIBUTING.md    gatsby-browser.js  plugins            yarn.lock
LICENSE.md         gatsby-config.js   src
README.md          gatsby-node.js     static
assets             gatsby-ssr.js      translations
```

List files inside current directory with its attributes and in chronological order
```bash
ls -lhtr
```

#### More Information:

* [Wikipedia](https://en.wikipedia.org/wiki/Ls)
