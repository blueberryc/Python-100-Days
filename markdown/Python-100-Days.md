
## Day01 - 初识`Python`

### 1.1 环境安装

建议直接安装 `Anaconda` ，不过由于清华大学等一系列镜像源都已经不在支持 `Anaconda` 。所以目前都需要到官网进行下载：

下载地址：[Anaconda官网](https://www.anaconda.com/distribution/)

#### 1.1.1 Windows 环境

1. 下载 Windows 版本的 `Anaconda`；
2. 执行安装，环境默认就好；
3. 不建议连同 Vscode 一起安装，个人都是分开安装

环境变量：
- D:\Coding\anaconda
- D:\Coding\anaconda\Scripts
- D:\Coding\anaconda\Library\bin

#### 1.1.2 Linux 环境

1. 下载 Linux 版本的 Anaconda；
2. bash ./xxx-anaconda.sh
3. 其余部分直接默认就好；

环境变量：

在 `~/.bashrc` 或 `~/.zshrc` 中添加：

```shell
export PATH=/home/weisheng/anaconda3/bin:$PATH
```

---

### 1.2 编程工具

 推荐个人使用比较多的工具，以及相应的软件配置。大家有更好的编程工具，也希望分享。
 
 工具：
 1. 微软的 Visual Studio Code
 2. Jupyterlab

#### 1.2.1 VScode

常用插件：
- ms-python.python
- Code Runner
- Code Spell Checker
- Guides
- Setting Sync
- SFTP
- Visual Studio IntelliCode
- Xcode Default Theme

首选项设置：

```json
{
    "editor.renderIndentGuides": false,
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Xcode Partial (Dark)",
    "editor.fontSize": 16,
    "editor.lineHeight": 22,
    "editor.formatOnSave": true,
    "editor.fontFamily": "Menlo, Consolas, 'Courier New', monospace",
    "python.autoComplete.addBrackets": true,
    "python.linting.flake8Enabled": true,
    "python.linting.pylintEnabled": false,
    "python.linting.flake8Args": [
        "--max-line-length=160"
    ],
    "python.formatting.autopep8Args": [
        "--max-line-length=160"
    ],
    "git.ignoreMissingGitWarning": false,
    "files.autoGuessEncoding": true,
    "files.eol": "\n",
    "[markdown]": {
        "editor.quickSuggestions": true
    },
    "files.autoSave": "off",
    "search.followSymlinks": false,
    "gitlens.advanced.messages": {
        "suppressShowKeyBindingsNotice": true
    },
    "gitlens.defaultDateStyle": "absolute",
    "editor.highlightActiveIndentGuide": true,
    // Guides设置
    "guides.normal.color.dark": "rgba(91, 91, 91, 0.6)",
    "guides.normal.color.light": "rgba(220, 220, 220, 0.7)",
    "guides.active.color.dark": "rgba(210, 110, 210, 0.6)",
    "guides.active.color.light": "rgba(200, 100, 100, 0.7)",
    "guides.active.style": "dashed",
    "guides.normal.style": "dashed",
    "guides.stack.style": "dashed",
    "code-runner.runInTerminal": true,
    "terminal.integrated.cursorStyle": "line",
    "C_Cpp.updateChannel": "Insiders",
    "terminal.integrated.shell.windows": "C:\\Windows\\System32\\cmd.exe",
    "powermode.enabled": true,
    "powermode.presets": "flames",
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue"
}
```

#### 1.2.2 `Jupyterlab`

`Jupyterlab` 是 `Juyter notebook` 的升级版本，安装方式如下：

```shell
conda install jupyterlab
```

---

### 1.3 今日练习

1、Python交互环境中查看下面的代码结果，并将内容翻译成中文。


```python
import this
```

    The Zen of Python, by Tim Peters
    
    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Although practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Although never is often better than *right* now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!


2、 学习使用turtle在屏幕上绘制图形。

代码文件：[小猪佩琪](https://github.com/blueberryc/Python-100-Days/blob/master/code/peppa_pig.py)

还未研究出如何在 `Jupyterlab` 中使用 `turtle` 包...


```python

```
