---
title: ML and Data Science, and vs code
layout: post
date: '2018-03-10 11:00:01'
categories: Machine Learning and Data Science
tags: Machine Learning, Data Science
---

### Data Science and Machine Learning
* [Scipy](https://www.scipy.org/) - numpy, scipy, matplotlib, ipython, pandas
* [Scikit-learn](http://scikit-learn.org/stable/#)
* [Tensorflow](https://www.tensorflow.org/)

### ML Packages
```
pip install -U
seaborn
scikit-learn
ipython jupyter notebook
tensorflow keras theano
```
* should install python3 64bit for tensorflow
* seaborn (included numpy, scipy, matplotlib, pandas)

### VS Code
[extensions](https://marketplace.visualstudio.com/VSCode) -  python, python extension pack
pylint, autopep8

* settings
```
"python.pythonPath": "C:/path/to/Envs/env/Scripts/python.exe",
"python.linting.enabled": true,
"python.autoComplete.addBrackets": true,
```

* keybindings default + my custom
```
[
    {
        "key": "f9",
        "command": "workbench.action.terminal.focus",

    },
    {
        "key": "ctrl+d",
        "command": "editor.action.deleteLines",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+k",
        "command": "-editor.action.deleteLines",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+h",
        "command": "cursorLeft"
    },
    {
        "key": "shift+alt+j",
        "command": "cursorWordLeft"
    },
    {
        "key": "shift+alt+l",
        "command": "cursorWordRight"
    },
    {
        "key": "shift+alt+;",
        "command": "cursorRight"
    },
    {
        "key": "shift+alt+q",
        "command": "cursorLineStart"
    },
    {
        "key": "shift+alt+w",
        "command": "cursorLineEnd"
    },
    {
        "key": "shift+alt+i",
        "command": "cursorUp",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+k",
        "command": "cursorDown",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+alt+o",
        "command": "deleteWordRight",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+u",
        "command": "deleteWordLeft",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+y",
        "command": "deleteAllLeft"
    },
    {
        "key": "shift+alt+p",
        "command": "deleteAllRight"
    },
    {
        "key": "shift+alt+z",
        "command": "workbench.action.toggleMaximizedPanel"
    },
    {
        "key": "f10",
        "command": "workbench.action.terminal.focusNext"
    }
]
```

[VS Code - Python tutorial](https://code.visualstudio.com/docs/python/python-tutorial)
