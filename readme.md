Git aliases for manipulating with *.gitignore* based on [gitignore.io](https://www.gitignore.io/) for Windows.

# Install

  - Copy file git-ignore.cmd to git/cmd path
  - Run aliases.bat

# Commands

Commands can be called everywhere in valid git repository.

**Create .gitignore**
```sh
git ignore yeoman,node
```

**Open .gitignore file**
```sh
git ignore-open
```

**Add sources to .gitignore**

```sh
git ignore-add yeoman,node
```

**Show content of .gitignore**
```sh
git ignore-show
```

**Show list of available sources**
```sh
git ignore-list
```

**Show list of available sources and filter using findstr**
```sh
git ignore-flist node
```