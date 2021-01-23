# Atom套件推薦
主要介紹Atom的程式開發、「整合開發環境」(IDE)、「除錯工具」(Debugger tool)等套件，主要以Python、TypeScript、JavaScript、Markdown的工具。

# 目錄

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->
<!-- code_chunk_output -->

- [Atom套件推薦](#atom套件推薦)
- [目錄](#目錄)
- [Atom IDE base](#atom-ide-base)
  - [Atom IDE base for Python](#atom-ide-base-for-python)
    - [ide-python](#ide-pythonhttpsatomiopackageside-python)
- [linter](#linter)
  - [linter for Data Exchange](#linter-for-data-exchange)
  - [linter for Python](#linter-for-python)
    - [linter-flake8](#linter-flake8httpsatomiopackageslinter-flake8)
    - [linter-mypy](#linter-mypyhttpsatomiopackageslinter-mypy)
    - [linter-pycodestyle](#linter-pycodestylehttpsatomiopackageslinter-pycodestyle)
    - [linter-pylint](#linter-pylinthttpsatomiopackageslinter-pylint)
    - [linter-pylama](#linter-pylamahttpsatomiopackageslinter-pylama)
    - [python-linters](#python-lintershttpsatomiopackagespython-linters)
  - [linter for VHDL and Verilog](#linter-for-vhdl-and-verilog)
- [Atom IDE UI](#atom-ide-ui)
  - [Atom IDE UI for Python](#atom-ide-ui-for-python)
  - [Atom IDE UI for VHDL and Verilog](#atom-ide-ui-for-vhdl-and-verilog)
- [Other](#other)
  - [Atom Beautify](#atom-beautifyhttpsgithubcomglavin001atom-beautify)
    - [Highlight Selected](#highlight-selectedhttpsgithubcomrichracehighlight-selected)
    - [File Icons](#file-iconshttpsatomiopackagesfile-icons)
    - [Minimap](#minimaphttpsgithubcomatom-minimapminimap)
    - [Markdown preview enhanced](#markdown-preview-enhancedhttpsgithubcomshd101wyymarkdown-preview-enhanced)
    - [Platformio ide terminal](#platformio-ide-terminalhttpsgithubcomplatformioplatformio-atom-ide-terminal)
    - [Sync settings](#sync-settingshttpsgithubcomatom-communitysync-settings)
    - [Regex railroad diagram](#regex-railroad-diagramhttpsgithubcomklorenzatom-regex-railroad-diagrams)
    - [Activate Power Mode](#activate-power-modehttpsgithubcomjoelbesadaactivate-power-mode)
    - [Atom cht menu](#atom-cht-menuhttpsgithubcomsheng-boatom-cht-menu)
    - [Teletype](#teletypehttpsgithubcomatomteletype)
    - [Atom-i18n](#atom-i18nhttpsgithubcomliuderchiatom-i18n)
    - [wakatime](#wakatimehttpsgithubcomwakatimeatom-wakatime)
    - [Git time machine](#git-time-machinehttpsgithubcomlittlebeegit-time-machine)
    - [context-menu-manager](#context-menu-managerhttpsgithubcomhughfenghencontext-menu-manager)
  - [TypeScript + JavaScript 系列](#typescript-javascript-系列)
    - [Atom typescript](#atom-typescripthttpsgithubcomtypestrongatom-typescript)
    - [Atom jsdoc](#atom-jsdochttpsgithubcomcoffuttatom-jsdoc)
  - [Python 系列](#python-系列)
    - [Hydrogen](#hydrogenhttpsgithubcomnteracthydrogen)
    - [Autocomplete python](#autocomplete-pythonhttpsgithubcomautocomplete-pythonautocomplete-python)
- [參考資料](#參考資料)

<!-- /code_chunk_output -->


# Atom IDE base
整合不同的IDE套件於此，它將提供以下Atom IDE套件：

- `atom-ide-datatip`
- `atom-ide-signature-help`
- `atom-ide-hyperclick`
- `atom-ide-definitions`
- `atom-ide-outline`
- `linter`
- `linter-ui-default`
- `intentions`
- `atom-ide-markdown-service`

還提供用於Atom的TypeScript套件。目前尚未測試，但應該會是很好用的。

## Atom IDE base for Python

### [ide-python](https://atom.io/packages/ide-python)
![](https://camo.githubusercontent.com/864864542907959a28b50dc5ad5f954ee33d62c8dac6b972ea6ef05caaee7ed4/68747470733a2f2f6261646765732e677265656e6b65657065722e696f2f6c6765696765722f6964652d707974686f6e2e737667)

過去使用`atom-ide-ui`，目前使用`atom-ide-community`，更新後的功能有提供哪些功能目前尚未得知與測試，但以過去的經驗是不錯的。

缺點使用與相依上需要另外安裝[python-language-server](https://github.com/palantir/python-language-server)。

提供Python原始碼編輯，有以下功能:
  - [Jedi](https://github.com/davidhalter/jedi)用於完成、定義、懸停、引用、簽名幫助和符號。
  - [Rope](https://github.com/python-rope/rope)完成和重命名。
  - [Pyflakes](https://github.com/PyCQA/pyflakes)用於檢測各種錯誤。
  - [McCabe](https://github.com/PyCQA/mccabe)為復雜性檢查做好準備。
  - [pycodestyle](https://github.com/PyCQA/pycodestyle)用於原始碼風格檢查。
  - [Pylint](https://www.pylint.org/):用於檢測各種錯誤。
  - [pydocstyle](https://github.com/PyCQA/pydocstyle)用於文件風格檢查的。
  - [autopep8](https://github.com/hhatto/autopep8)用於原始碼格式化(優先於YAPF)。
  - [YAPF](https://github.com/google/yapf)用於原始碼格式化。

# linter
IDE界面整合器，目前還有在更新，建議使用這個套件。

- [linter-ui-default](https://atom.io/packages/linter-ui-default):設定默認的UI界面，雖然還不知道這個是作什麼的。

## linter for Data Exchange
- [linter-js-yaml](https://atom.io/packages/linter-js-yaml):相依linter，檢查Json或Yaml的資料結構與內容。

## linter for Python
### [linter-flake8](https://atom.io/packages/linter-flake8)
相依linter，使用Flake8檢查。

### [linter-mypy](https://atom.io/packages/linter-mypy)
相依linter，使用Mypy檢查。

### [linter-pycodestyle](https://atom.io/packages/linter-pycodestyle)
相依linter，使用pycodestyle檢查。

### [linter-pylint](https://atom.io/packages/linter-pylint)
相依linter，使用pylint檢查。

### [linter-pylama](https://atom.io/packages/linter-pylama)
相依`linter`，使用`Pylama`檢查，`Pylama`整合`Pylint`、`pycodestyle`/`pep8`、`pydocstyle`/`pep257`、`Pyflakes`、`McCabe`、`Radon`和`isort`等套件。

需要另外安裝[Pylama](https://github.com/klen/pylama#instalat)的Python套件才能使用。

如果以完整來說這個套件相當好用，但尚未測試與使用，同時會翰其他`linter`套件衝突。

![](https://raw.githubusercontent.com/AtomLinter/linter-pylama/master/in_action.gif)

### [python-linters](https://atom.io/packages/python-linters)
[![repo status Active](https://www.repostatus.org/badges/latest/active.svg "repo status Active")](https://www.repostatus.org/#active)
[![last commit](https://img.shields.io/github/last-commit/elarivie/atom-python-linters)](https://github.com/elarivie/atom-python-linters/commits/master)

[![python-linters_BugTracker](https://img.shields.io/github/issues/elarivie/atom-python-linters.svg)][python-linters_BugTracker]
[![Build Status](https://travis-ci.org/elarivie/atom-python-linters.svg?branch=master)](https://travis-ci.org/elarivie/atom-python-linters)

Python的自動化檢查程式，可以取代[linter](https://atom.io/packages/linter)一系列套件，相當不錯，但不可與其他linter其他檢查套件共存使用，會出現錯誤訊息，相依[linter](https://atom.io/packages/linter)，我現在都是使用這個。

提供`Pylint`、`Flake8`、`MyPy`與`pycodestyle`的套件直接使用與呼叫，因此可以透過更新上述檢查套件得到最新的更新。

另外可以透過`setup.cfg`檔案設定忽略項目與規則，但在錯誤訊息方面沒有很好的操作，另外如果`setup.cfg`沒有`Pylint`、`Flake8`、`MyPy`與`pycodestyle`四個規則放入，會出現錯誤內容。

## linter for VHDL and Verilog
- [linter-veriloghdl](https://atom.io/packages/linter-veriloghdl):相依Icarus Verilog、Slang與Verilator，可以選擇其中之一。
- [linter-vhdl](https://atom.io/packages/linter-vhdl):相依GHDL，需要安裝GHDL，目前GHDL相依於Ubuntu 14.04 TLS，如要安裝在Ubuntu 18.04要自己安裝函式庫。
- [linter-quartus](https://atom.io/packages/linter-quartus):可以使用繞過Quartus通過ModelSim驗證與模擬電路，目前還不知道怎麼使用。

# Atom IDE UI
IDE界面整合器，讓不同的套件可以在這上面使用，以下套件為相依此套件的軟體，必須安裝[atom-ide-ui](https://atom.io/packages/atom-ide-ui)才能使用，建議別使用此IDE套件與相關套件，因為Facebook與GitHub已經宣佈取消繼續維護。

## Atom IDE UI for Python
- [atom-ide-debugger-python](https://atom.io/packages/atom-ide-debugger-python):Python的除錯套件。

## Atom IDE UI for VHDL and Verilog
- [ide-vhdl](https://atom.io/packages/ide-vhdl):相依於Atom IDE UI，若使用Atom IDE UI可以使用此套件。

# Other
其他通常代表可以不用相依某些套件就可以使用，可能是語言支援，例如顏色標記語法、自動填入等功能。

## [Atom Beautify](https://github.com/Glavin001/atom-beautify)
只需要簡單的按下 Ctrl+Alt+B 便會把你的 code 排列得整整齊齊，省去排版所浪費的時間。
> Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom

| Before | After |
| --- | ---- |
| Original HTML | Beautified HTML |
| ![image](https://cloud.githubusercontent.com/assets/1885333/16542727/db52adc6-408a-11e6-824e-04aed06bd2f7.png) | ![image](https://cloud.githubusercontent.com/assets/1885333/16542728/dcac3700-408a-11e6-8e35-9c8fc4432edc.png) |


### [Highlight Selected](https://github.com/richrace/highlight-selected)
輕點2下自動高亮

![Gif in action](http://i.imgur.com/C5FnzzQ.gif)

### [File Icons](https://atom.io/packages/file-icons)
幫文件加上 icons ，方便識別文件。    

![Imgur](https://i.imgur.com/TrCvBWn.png)


### [Minimap](https://github.com/atom-minimap/minimap)
可在視窗左右側顯示一張程式碼地圖，協助你快速掌握全局。    
Minimap [有許多的輔助套件](https://github.com/atom-minimap/minimap#available-plugins)可以下載安裝，例如 [Highlight Selected](https://atom.io/packages/minimap-highlight-selected) 跟上方介紹的 Highlight Selected 一樣會在 minimap 中高亮所選的字。

![Imgur](https://i.imgur.com/qZoWRw3.png)


### [Markdown preview enhanced](https://github.com/shd101wyy/markdown-preview-enhanced)
強大的 Markdown 及時預覽工具，可與 code 同步位置捲動。    
可用他查看用 Markdown 格式的投影片、流程圖、LaTeX數學、電子書...等    
另支援輸出 PDF、PNG、JPEG 的檔案。    
更多功能[點此網址](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-tw/)。    

![Markdown preview enhanced的使用狀況](https://i.imgur.com/WHPLhH9.gif)


### [Platformio ide terminal](https://github.com/platformio/platformio-atom-ide-terminal)
能讓你在 Atom 中開啟終端(CLI、cmd)

![Imgur](https://i.imgur.com/YrIwZMQ.gif)


### [Sync settings](https://github.com/atom-community/sync-settings)
可用來 **同步或備份** 你的 Atom 所有套件、設定。
* Sync Atom's and package settings
* Sync installed packages
* Sync user keymaps
* Sync user styles
* Sync user init script
* Sync snippets
* Sync user defined text files


### [Regex railroad diagram](https://github.com/klorenz/atom-regex-railroad-diagrams)
讓你複雜的正則式以圖形化的方式呈現
終於不是寫完後就變成無字天書了QwQ

![regex-railraod-diagram in action](https://raw.githubusercontent.com/klorenz/atom-regex-railroad-diagrams/master/regex-railroad-diagrams.png)


### [Activate Power Mode](https://github.com/JoelBesada/activate-power-mode)
讓你輸入 code 特別有氣勢的東西(?    
話說我覺得 combo 太干擾我的節奏就關了


![activate-power-mode-0 4 0](https://cloud.githubusercontent.com/assets/688415/11615565/10f16456-9c65-11e5-8af4-265f01fc83a0.gif)
![activate-power-mode-combo](https://cloud.githubusercontent.com/assets/10590799/18817237/876c2d84-8321-11e6-8324-f1540604c0bd.gif)


### [Atom cht menu](https://github.com/Sheng-Bo/atom-cht-menu)
Atom 中文化    
感謝作者大大m(_ \_)m  雖然已經看習慣英文了

![Atom 中文化畫面](https://raw.githubusercontent.com/Sheng-Bo/atom-cht-menu/master/screenshot/03.png)

### [Teletype](https://github.com/atom/teletype)
能夠讓你跟其他人同時編輯同一份文件的東東。

![demo](https://user-images.githubusercontent.com/2988/32753167-d781baf0-c899-11e7-8b64-683ab84d3a8c.gif)



### [Atom-i18n](https://github.com/liuderchi/atom-i18n)
Atom 中文化
嚴格來說是國際化，使用 i18n 的方式翻譯。
而且這個套件不會拖到什麼效能，比上一個好很多，推推。
![](https://cloud.githubusercontent.com/assets/4994705/23652298/5123f294-0363-11e7-8f8f-e9c83f19710e.png)

### [wakatime](https://github.com/wakatime/atom-wakatime)
紀錄你的 coding 時間，可同步其他的編輯器紀錄，也可每周寄報表到你的信箱。
![Project Overview](https://wakatime.com/static/img/ScreenShots/Screen-Shot-2016-03-21.png)


### [Git time machine](https://github.com/littlebee/git-time-machine)    
可用圖示化的方式來查看 git commit 差異    
![Git time machine GIF](https://raw.githubusercontent.com/littlebee/git-time-machine/master/resources/timemachine.gif)



### [context-menu-manager](https://github.com/hughfenghen/context-menu-manager)
Atom插件，管理右键菜单。    

清理菜单 显示快捷键      
![](https://raw.githubusercontent.com/hughfenghen/context-menu-manager/master/resources/compare.png)     

管理界面      
![](https://raw.githubusercontent.com/hughfenghen/context-menu-manager/master/resources/manager-view.png)     


---
## TypeScript + JavaScript 系列

### [Atom typescript](https://github.com/TypeStrong/atom-typescript)
撰寫 TypeScript 一定要裝的套件    
自動完成輸入、向下編譯、程式碼bug提示...等功能。

-   Autocomplete
-   Live error analysis
-   Type information on hover
-   Compile on save
-   Project Context Support (`tsconfig.json`)
-   Project Build Support
-   `package.json` Support
-   Goto Declaration
-   Find References
-   Semantic view
-   Block comment and uncomment
-   Rename refactoring
-   Common Snippets
-   Alternative to symbols-view


### [Atom jsdoc](https://github.com/coffutt/atom-jsdoc)
在 function 上按下 (Ctrl + Shift + j) 自動生成 jsdoc 。

![Imgur](https://i.imgur.com/55OSyHD.png)

---
## Python 系列

### [Hydrogen](https://github.com/nteract/hydrogen)
及時執行 python 指令並看到成果 (真的超強的...
![hero](https://cloud.githubusercontent.com/assets/13285808/20360886/7e03e524-ac03-11e6-9176-37677f226619.gif)


### [Autocomplete python](https://github.com/autocomplete-python/autocomplete-python)
自動補全 python 程式碼

![自動補全 python 程式碼](https://cloud.githubusercontent.com/assets/193864/12288427/61fe2114-ba0f-11e5-9832-98869180d87f.gif)

# 參考資料
