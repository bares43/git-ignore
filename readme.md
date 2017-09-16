Git aliases for manipulating *.gitignore* file based on [gitignore.io](https://www.gitignore.io/) for Windows.

# Installation

  - Copy file git-ignore.cmd to Program Files/Git/cmd path
  - Run aliases.bat

# Commands

Commands can be called everywhere inside valid git repository.

**Create .gitignore**
```sh
git ignore yeoman,node
```

**Open .gitignore file in texteditor**
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

**Show list of available sources and filter them using findstr**
```sh
git ignore-flist node
```