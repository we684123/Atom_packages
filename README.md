# Atom套件推薦
主要介紹Atom的程式開發、「整合開發環境」(IDE)、「除錯工具」(Debugger tool)等套件，主要以Python、C、TypeScript、JavaScript、Markdown的工具。

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
  - [linter for C](#linter-for-c)
- [Atom IDE UI](#atom-ide-ui)
  - [Atom IDE UI for Python](#atom-ide-ui-for-python)
  - [Atom IDE UI for VHDL and Verilog](#atom-ide-ui-for-vhdl-and-verilog)
- [Other](#other)
  - [網頁設計](#網頁設計)
    - [Icons](#icons)
      - [seti-icons](#seti-iconshttpsatomiopackagesseti-icons)
      - [svg-icons](#svg-iconshttpsatomiopackagessvg-icons)
      - [icon-fonts](#icon-fontshttpsatomiopackagesicon-fonts)
    - [TypeScript + JavaScript 系列](#typescript-javascript-系列)
      - [atom-typescript](#atom-typescripthttpsgithubcomtypestrongatom-typescript)
      - [atom-jsdoc](#atom-jsdochttpsgithubcomcoffuttatom-jsdoc)
  - [Python](#python)
    - [hydrogen](#hydrogenhttpsgithubcomnteracthydrogen)
    - [autocomplete-python](#autocomplete-pythonhttpsgithubcomautocomplete-pythonautocomplete-python)
    - [python-debugger](#python-debuggerhttpsatomiopackagespython-debugger)
  - [C](#c)
    - [gpp-compiler](#gpp-compiler)
  - [PLC](#plc)
  - [Gettext](#gettext)
  - [Markdown](#markdown)
    - [Markdown preview enhanced](#markdown-preview-enhancedhttpsgithubcomshd101wyymarkdown-preview-enhanced)
  - [Verilog and VHDL](#verilog-and-vhdl)
  - [reStructuredText](#restructuredtext)
  - [Android](#android)
  - [Tool](#tool)
    - [intentions](#intentionshttpsatomiopackagesintentions)
    - [busy-signal](#busy-signalhttpsatomiopackagesbusy-signal)
    - [Atom Beautify](#atom-beautifyhttpsgithubcomglavin001atom-beautify)
    - [highlight-selected](#highlight-selectedhttpsatomiopackageshighlight-selected)
    - [minimap](#minimaphttpsatomiopackagesminimap)
    - [Icons](#icons-1)
      - [file-icons](#file-iconshttpsatomiopackagesfile-icons)
      - [front-icons](#front-iconshttpsatomiopackagesfront-icons)
      - [atom-file-icons](#atom-file-iconshttpsatomiopackagesatom-file-icons)
      - [atom-icons](#atom-iconshttpsatomiopackagesatom-icons)
    - [終端機](#終端機)
      - [platformio-ide-terminal](#platformio-ide-terminalhttpsatomiopackagesplatformio-ide-terminal)
      - [atom-ide-terminal](#atom-ide-terminalhttpsatomiopackagesatom-ide-terminal)
    - [Sync settings](#sync-settingshttpsgithubcomatom-communitysync-settings)
    - [Regex](#regex)
    - [atom-regex-railroad-diagrams](#atom-regex-railroad-diagramshttpsgithubcomklorenzatom-regex-railroad-diagrams)
    - [Activate Power Mode](#activate-power-modehttpsgithubcomjoelbesadaactivate-power-mode)
    - [cht-menu](#cht-menuhttpsatomiopackagescht-menu)
    - [atom-i18n](#atom-i18nhttpsgithubcomliuderchiatom-i18n)
    - [teletype](#teletypehttpsgithubcomatomteletype)
    - [atom-wakatime](#atom-wakatimehttpsgithubcomwakatimeatom-wakatime)
    - [git-time-machine](#git-time-machinehttpsgithubcomlittlebeegit-time-machine)
    - [context-menu-manager](#context-menu-managerhttpsgithubcomhughfenghencontext-menu-manager)
    - [Diagram](#diagram)
- [參考資料](#參考資料)

<!-- /code_chunk_output -->


# Atom IDE base
整合不同的IDE套件於此，它將提供以下 Atom IDE 套件：

- `atom-ide-datatip`
- `atom-ide-signature-help`
- `atom-ide-hyperclick`
- `atom-ide-definitions`
- `atom-ide-outline`
- `linter`
- `linter-ui-default`
- `intentions`
- `atom-ide-markdown-service`

還提供用於 Atom 的 TypeScript 套件。目前尚未測試，但應該會是很好用的。

此為 Atom IDE UI 的基礎延伸出來，等於說也跟其他的也相容，因為 linter 也是在 Atom IDE UI 設計出來的。另外記得有一個IDE是以自己微基礎，不打算相容其他的特立獨行的IDE，但忘記名稱了。

## Atom IDE base for Python

### [ide-python](https://atom.io/packages/ide-python)
![](https://camo.githubusercontent.com/864864542907959a28b50dc5ad5f954ee33d62c8dac6b972ea6ef05caaee7ed4/68747470733a2f2f6261646765732e677265656e6b65657065722e696f2f6c6765696765722f6964652d707974686f6e2e737667)

過去使用`atom-ide-ui`，目前使用`atom-ide-community`，更新後的功能有提供哪些功能目前尚未得知與測試，但以過去的經驗是不錯的。

缺點使用與相依上需要另外安裝 [python-language-server](https://github.com/palantir/python-language-server)。

提供 Python 原始碼編輯，有以下功能：
  - [Jedi](https://github.com/davidhalter/jedi)：用於完成、定義、懸停、引用、簽名幫助和符號。
  - [Rope](https://github.com/python-rope/rope)：完成和重命名。
  - [Pyflakes](https://github.com/PyCQA/pyflakes)：用於檢測各種錯誤。
  - [McCabe](https://github.com/PyCQA/mccabe)：為復雜性檢查做好準備。
  - [pycodestyle](https://github.com/PyCQA/pycodestyle)：用於原始碼風格檢查。
  - [Pylint](https://www.pylint.org/)：用於檢測各種錯誤。
  - [pydocstyle](https://github.com/PyCQA/pydocstyle)：用於文件風格檢查的。
  - [autopep8](https://github.com/hhatto/autopep8)：用於原始碼格式化(優先於YAPF)。
  - [YAPF](https://github.com/google/yapf)：用於原始碼格式化。

# linter
IDE界面整合器，目前還有在更新，建議使用這個套件。

- [linter-ui-default](https://atom.io/packages/linter-ui-default)：設定默認的UI界面，雖然還不知道這個是作什麼的。

## linter for Data Exchange
- [linter-js-yaml](https://atom.io/packages/linter-js-yaml)：相依 linter，檢查 Json 或 Yaml 的資料結構與內容。

## linter for Python
### [linter-flake8](https://atom.io/packages/linter-flake8)
相依 linter，使用 Flake8 檢查。

### [linter-mypy](https://atom.io/packages/linter-mypy)
相依 linter，使用 Mypy 檢查。

### [linter-pycodestyle](https://atom.io/packages/linter-pycodestyle)
相依 linter，使用 pycodestyle 檢查。

### [linter-pylint](https://atom.io/packages/linter-pylint)
相依linter，使用 pylint 檢查。

### [linter-pylama](https://atom.io/packages/linter-pylama)
相依`linter`，使用`Pylama`檢查，`Pylama`整合`Pylint`、`pycodestyle`/`pep8`、`pydocstyle`/`pep257`、`Pyflakes`、`McCabe`、`Radon`和`isort`等套件。

需要另外安裝 [Pylama](https://github.com/klen/pylama#instalat) 的 Python 套件才能使用。

如果以完整來說這個套件相當好用，但尚未測試與使用，同時會翰其他`linter`套件衝突。

![](https://raw.githubusercontent.com/AtomLinter/linter-pylama/master/in_action.gif)

### [python-linters](https://atom.io/packages/python-linters)

[![repo status Active](https://www.repostatus.org/badges/latest/active.svg "repo status Active")](https://www.repostatus.org/#active)
[![last commit](https://img.shields.io/github/last-commit/elarivie/atom-python-linters)](https://github.com/elarivie/atom-python-linters/commits/master)
[![python-linters_BugTracker](https://img.shields.io/github/issues/elarivie/atom-python-linters.svg)]([python-linters_BugTracker])
[![Build Status](https://travis-ci.org/elarivie/atom-python-linters.svg?branch=master)](https://travis-ci.org/elarivie/atom-python-linters)

Python的自動化檢查程式，可以取代 [linter](https://atom.io/packages/linter) 一系列套件，相當不錯，但不可與其他 linter 其他檢查套件共存使用，會出現錯誤訊息，相依 [linter](https://atom.io/packages/linter)，我現在都是使用這個。

提供`Pylint`、`Flake8`、`MyPy`與`pycodestyle`的套件直接使用與呼叫，因此可以透過更新上述檢查套件得到最新的更新。

另外可以透過`setup.cfg`檔案設定忽略項目與規則，但在錯誤訊息方面沒有很好的操作，另外如果`setup.cfg`沒有`Pylint`、`Flake8`、`MyPy`與`pycodestyle`四個規則放入，會出現錯誤內容。

## linter for VHDL and Verilog
- [linter-veriloghdl](https://atom.io/packages/linter-veriloghdl)：相依 Icarus Verilog、Slang 與 Verilator，可以選擇其中之一。
- [linter-vhdl](https://atom.io/packages/linter-vhdl)：相依 GHDL，需要安裝 GHDL，目前 GHDL 相依於 Ubuntu 14.04 TLS，如要安裝在 Ubuntu 18.04 要自己安裝函式庫。
- [linter-quartus](https://atom.io/packages/linter-quartus)：可以使用繞過 Quartus 通過 ModelSim 驗證與模擬電路，目前還不知道怎麼使用。

## linter for C

- linter-gcc

# Atom IDE UI
IDE界面整合器，讓不同的套件可以在這上面使用，以下套件為相依此套件的軟體，必須安裝 [atom-ide-ui](https://atom.io/packages/atom-ide-ui) 才能使用，建議別使用此IDE套件與相關套件，因為 Facebook 與 GitHub 已經宣佈取消繼續維護。

## Atom IDE UI for Python
- [atom-ide-debugger-python](https://atom.io/packages/atom-ide-debugger-python)：Python的除錯套件。

## Atom IDE UI for VHDL and Verilog
- [ide-vhdl](https://atom.io/packages/ide-vhdl)：相依於 Atom IDE UI，若使用 Atom IDE UI 可以使用此套件。

# Other
其他通常代表可以不用相依某些套件就可以使用，可能是語言支援、顏色標記語法、自動填入等功能。

##網頁設計

### Icons
#### [seti-icons](https://atom.io/packages/seti-icons)
最後更新時間是2017年，但最多人用。

#### [svg-icons](https://atom.io/packages/svg-icons)
最後更新時間是2021年，有更新但不是最多人用，未來有機會追過，通常 Atom 會優先將一直有更新的排名往前。

#### [icon-fonts](https://atom.io/packages/icon-fonts)
最後更新時間是2021年。

### TypeScript + JavaScript 系列

#### [atom-typescript](https://github.com/TypeStrong/atom-typescript)
撰寫 TypeScript 一定要裝的套件，自動完成輸入、向下編譯、程式碼bug提示...等功能。

- Autocomplete
- Live error analysis
- Type information on hover
- Compile on save
- Project Context Support (`tsconfig.json`)
- Project Build Support
- `package.json` Support
- Goto Declaration
- Find References
- Semantic view
- Block comment and uncomment
- Rename refactoring
- Common Snippets
- Alternative to symbols-view

#### [atom-jsdoc](https://github.com/coffutt/atom-jsdoc)
在 function 上按下 `Ctrl + Shift + j` 自動生成 jsdoc。

![Imgur](https://i.imgur.com/55OSyHD.png)

## Python
- [Hydrogen](https://atom.io/packages/Hydrogen)：使用此可以在編輯 Python 時像 Jupyter 一樣編輯後馬上可以看到程式執行結果，此套件不需要相依 [atom-ide-ui](https://atom.io/packages/atom-ide-ui) 與 [linter](https://atom.io/packages/linter)。
- [kite](https://atom.io/packages/kite)：一個自動填寫的套件，使用了人工智慧與機器學習去學習，因此建議的內容相當的還算精準，如有大家都使用的字詞彙會自動跳出來，也是不需要相依 [atom-ide-ui](https://atom.io/packages/atom-ide-ui) 與 [linter](https://atom.io/packages/linter) 等其他套件，但需要安裝Kite程式才可以運作，基本上還不錯。
- [autocomplete-python](https://atom.io/packages/autocomplete-python)：Python 變數、函式、模組、套件、除錯、自動輸入，使用 Jedi 與 Kite 技術作為支援，也是 Kite 官網在 Atom 上所指定與承認的套件，因此套件不需要相依 [atom-ide-ui](https://atom.io/packages/atom-ide-ui) 與 [linter](https://atom.io/packages/linter)。
- [python-debugger](https://atom.io/packages/python-debugger)

### [hydrogen](https://github.com/nteract/hydrogen)
使用 JPython 的核心，當然可以選擇其他的核心，此套件也可以支援，最大的特色就是即時執行 Python 指令並看到成果 (真的超強的...

![hero](https://cloud.githubusercontent.com/assets/13285808/20360886/7e03e524-ac03-11e6-9176-37677f226619.gif)

### [autocomplete-python](https://github.com/autocomplete-python/autocomplete-python)
Python 變數、函式、模組、套件、除錯、自動輸入，使用 Jedi 與 Kite 技術作為支援，也是 Kite 官網在 Atom 上所指定與承認的套件，因此套件不需要相依 [atom-ide-ui](https://atom.io/packages/atom-ide-ui) 與 [linter](https://atom.io/packages/linter)。

![自動補全 python 程式碼](https://cloud.githubusercontent.com/assets/193864/12288427/61fe2114-ba0f-11e5-9832-98869180d87f.gif)

### [python-debugger](https://atom.io/packages/python-debugger)
Python 的記憶體檢查工具，可以說是 Python 的 GDB ，與 C 語言的 GDB 不同的是，指令使用方式是 PDB 。

這個方式是比使用 `print` 的函式檢查變數來的方便，同時可以檢查內建數值與型態，是一個相當強大的套件，另外目前也不衝突。

會使用這個可以減少在刪除 `print` 指令的時間，這件事情是很重要的事情，尤其維護大型的程式時會省很多時間。

![Atom Python Debugger](https://github.com/dpo/atom-python-debugger/raw/master/screenshots/atom-python-debugger-demo.gif)

## C
### gpp-compiler
可以像大學很多教學使用的整合開發環境 Dev++ 一樣的功能與使用，按 `F5` 可以自動編譯，本人是覺得相當好用，但如果程式執行速度過快沒有等待或者任意鍵的停止動作會直接關閉甚至看不到視窗跑出來，但實際是有執行過但速度太快所以沒有看到。

前往 [Atom Packages](https://atom.io/packages/gpp-compiler)  
前往 [GitHub](https://github.com/kriscross07/atom-gpp-compiler)  

## PLC
- [language-structured-text](https://atom.io/packages/language-structured-text)：PLC程式語法套件。  

## Gettext
- [language-text](https://atom.io/packages/language-text)    
- [language-structured-text](https://atom.io/packages/language-structured-text)    
- [language-as-structured-text](https://atom.io/packages/language-as-structured-text)    

## Markdown
- [pdf-view](https://atom.io/packages/pdf-view)：檢視 PDF 檔案的套件，基本上不用設定即可使用。
- [markdown-toc](https://atom.io/packages/markdown-toc)：製作目錄的工具，當建立成功後在存檔時會自動更新，但目前有一些 bug 存在，當編輯的頁面關起或換到其他 Markdown 文件時，新增目錄的動作會在就頁面使用，會被鎖定在以更換的頁面中持續新增，必須重新開啟才可解決，目前都統一使用 [markdown-preview-enhanced](https://atom.io/packages/markdown-preview-enhanced) 套件。
- [markdown-preview-enhanced](https://atom.io/packages/markdown-preview-enhanced)：功能最強大的markdown套件，包括跟蹤滾動頁面、內建 PDF 轉換程式、照片貼上、照片上傳處理等，為內建套件`markdown-preview`的更強大套件，預設上會將內建的停用，並且刪除雙空白`  `換行，頁面以高亮風格為預設，不過可以自行設定使用 Atom 的 Dock 風格。內建`markdown-toc`的功能並且錯誤問題較少。
- [markdown-table-editor](https://atom.io/packages/markdown-table-editor)：製作表格工具，快速有效率。
- [insert-timestamp](https://atom.io/packages/insert-timestamp)：時間戳製作功能，寫部落格式很棒的工具。
- [markdown-image-insert](https://atom.io/packages/markdown-image-insert)：中國人製作，雖然不會與照片衝突，但有一些小問題。
- [markdown-image-insertion](https://atom.io/packages/markdown-image-insertion)：不提供快捷鍵，使用`Ctrl + Shift + P`來呼叫此功能出來，基本上不會與其他快捷鍵衝突。
- [markdown-pdf](https://atom.io/packages/markdown-pdf)：讓 Mark-down 可以輸出為 PDF 藉此輸出，但輸出後不會將照片嵌入，不是很好用。
- [markdown-image-assistant](https://atom.io/packages/markdown-image-assistant)：一個很好用的照片貼上套件，可以將照片拖曳到指定的欄位，使用`Ctrl + Shift + V`的快捷鍵，不影響原始的複製貼上快捷鍵。

### [Markdown preview enhanced](https://github.com/shd101wyy/markdown-preview-enhanced)
強大的 Markdown 及時預覽工具，可與 code 同步位置捲動。  

可用他查看用 Markdown 格式的投影片、流程圖、LaTeX數學、電子書...等另支援輸出 PDF、PNG、JPEG 的檔案。  

更多功能[點此網址](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-tw/)。    

![Markdown preview enhanced的使用狀況](https://i.imgur.com/WHPLhH9.gif)

## Verilog and VHDL
- [language-verilog](https://atom.io/packages/language-verilog)：Verilog 程式碼語法標記，這個可以優先安裝，因為可以找出 Verilog 檔案。
- [language-vhdl](https://atom.io/packages/language-vhdl)：VHDL 程式碼語法標記，這個可以優先安裝，因為可以找出 VHDL 檔案。
- [verilog-tools](https://atom.io/packages/verilog-tools)：看不出來怎麼使用，好像是自動化相關的程式。
- [lancelot-language-hdl](https://atom.io/packages/lancelot-language-hdl)：nand2tetris 課程的 HDL 的程式碼語法標記和現有晶片摘要，還是不懂這是要做什麼。

## reStructuredText
- [rst-preview-pandoc](https://atom.io/packages/rst-preview-pandoc)
- [atom-rst-preview-docutils](https://atom.io/packages/atom-rst-preview-docutils)
- [language-restructuredtext](https://atom.io/packages/language-restructuredtext)

## Android

- dart
- atom-toolbar

Dart部份已經沒有人在維護了，大家都轉移到 Android Studio ，但是可以使用的，只要更改版本位置就可以。

## Tool

### [intentions](https://atom.io/packages/intentions)
將色碼顏色顯示在色碼下方。    
![Intentions List API](https://cloud.githubusercontent.com/assets/4278113/12488546/e73809ba-c08d-11e5-8038-dd222f3a815d.png)

### [busy-signal](https://atom.io/packages/busy-signal)
顯示其他套件是否執行忙碌。    
![](https://cloud.githubusercontent.com/assets/4278113/22865536/0a123074-f188-11e6-8c6e-38574a6fe14c.gif)

### [Atom Beautify](https://github.com/Glavin001/atom-beautify)
只需要簡單的按下`Ctrl+Alt+B`便會把你的 code 排列得整整齊齊，省去排版所浪費的時間。

> Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom

| Before                                                                                                         | After                                                                                                          |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| Original HTML                                                                                                  | Beautified HTML                                                                                                |
| ![image](https://cloud.githubusercontent.com/assets/1885333/16542727/db52adc6-408a-11e6-824e-04aed06bd2f7.png) | ![image](https://cloud.githubusercontent.com/assets/1885333/16542728/dcac3700-408a-11e6-8e35-9c8fc4432edc.png) |

### [highlight-selected](https://atom.io/packages/highlight-selected)
輕點2下自動突顯其他一致的字詞，快速尋找。

![Gif in action](http://i.imgur.com/C5FnzzQ.gif)

### [minimap](https://atom.io/packages/minimap)
可在視窗左右側顯示一張程式碼地圖，協助你快速掌握全局。 Minimap [有許多的輔助套件](https://github.com/atom-minimap/minimap#available-plugins)可以下載安裝，例如 [Highlight Selected](https://atom.io/packages/minimap-highlight-selected) 跟上方介紹的 Highlight Selected 一樣會在 minimap 中高亮所選的字。

![Imgur](https://i.imgur.com/qZoWRw3.png)

### Icons
幫文件加上 Icons ，方便識別文件。

#### [file-icons](https://atom.io/packages/file-icons)
最後更新時間是2021年，推薦使用這個，圖片完善且完整。

![](https://raw.githubusercontent.com/file-icons/atom/6714706f268e257100e03c9eb52819cb97ad570b/preview.png)

#### [front-icons](https://atom.io/packages/front-icons)
最後更新時間是2019年。

![](https://raw.githubusercontent.com/donovanhiland/atom-file-icons/master/icons-on-dark.png)

#### [atom-file-icons](https://atom.io/packages/atom-file-icons)
最後更新時間是2019年。

#### [atom-icons](https://atom.io/packages/atom-icons)
最後更新時間是2016年。

### 終端機
能讓你在 Atom 中開啟終端機(CLI)或提示字元命令 CMD 。

#### [platformio-ide-terminal](https://atom.io/packages/platformio-ide-terminal)
目前最多人使用的套件，也應該問題最少，目前是更新時間最新的，2020年更新。為 PlatformIO 維護，是相當活躍的組織，是針對嵌入式系統開發為目標。

![Imgur](https://i.imgur.com/YrIwZMQ.gif)

#### [atom-ide-terminal](https://atom.io/packages/atom-ide-terminal)
建議此不要使用了，最後一次更新是 2018 年。

### [Sync settings](https://github.com/atom-community/sync-settings)
可用來 **同步或備份** 你的 Atom 所有套件、設定。

- Sync Atom's and package settings
- Sync installed packages
- Sync user keymaps
- Sync user styles
- Sync user init script
- Sync snippets
- Sync user defined text files

### Regex
### [atom-regex-railroad-diagrams](https://github.com/klorenz/atom-regex-railroad-diagrams)
讓你複雜的正規表達式以圖形化的方式呈現，終於不是寫完後就變成無字天書了QwQ。這個在C語言很好用。最後更新時間是2017年，但可能很好用。

![regex-railraod-diagram in action](https://raw.githubusercontent.com/klorenz/atom-regex-railroad-diagrams/master/regex-railroad-diagrams.png)

### [Activate Power Mode](https://github.com/JoelBesada/activate-power-mode)
讓你輸入 code 特別有氣勢的東西(?

話說我覺得 combo 太干擾我的節奏就關了。

![activate-power-mode-0 4 0](https://cloud.githubusercontent.com/assets/688415/11615565/10f16456-9c65-11e5-8af4-265f01fc83a0.gif)
![activate-power-mode-combo](https://cloud.githubusercontent.com/assets/10590799/18817237/876c2d84-8321-11e6-8324-f1540604c0bd.gif)

### [cht-menu](https://atom.io/packages/cht-menu)
Atom 中文化，感謝作者大大，雖然已經看習慣英文了。目前可能會暫停維護，最新版本2017年。雖然個人不捨，陪伴了五年了，而且比較喜歡這個的翻譯，但還是必須捨棄此套件。

![Atom 中文化畫面](https://raw.githubusercontent.com/Sheng-Bo/atom-cht-menu/master/screenshot/03.png)

### [atom-i18n](https://github.com/liuderchi/atom-i18n)
Atom 中文化，嚴格來說是國際化，使用 i18n 的方式翻譯。而且這個套件不會拖到什麼效能，比上一個好很多，推推。

![](https://cloud.githubusercontent.com/assets/4994705/23652298/5123f294-0363-11e7-8f8f-e9c83f19710e.png)

### [teletype](https://github.com/atom/teletype)
能夠讓你跟其他人同時編輯同一份文件的東東。

![demo](https://user-images.githubusercontent.com/2988/32753167-d781baf0-c899-11e7-8b64-683ab84d3a8c.gif)

### [atom-wakatime](https://github.com/wakatime/atom-wakatime)
紀錄你的 coding 時間，可同步其他的編輯器紀錄，也可每周寄報表到你的信箱。

![Project Overview](https://wakatime.com/static/img/ScreenShots/Screen-Shot-2016-03-21.png)

### [git-time-machine](https://github.com/littlebee/git-time-machine)    
可用圖示化的方式來查看 git commit 差異

![Git time machine GIF](https://raw.githubusercontent.com/littlebee/git-time-machine/master/resources/timemachine.gif)

### [context-menu-manager](https://github.com/hughfenghen/context-menu-manager)
自定義右键選單。  

![](https://raw.githubusercontent.com/hughfenghen/context-menu-manager/master/resources/compare.png)     

管理界面

![](https://raw.githubusercontent.com/hughfenghen/context-menu-manager/master/resources/manager-view.png)     

### Diagram
- flow-diagram
- diagrams

# 參考資料

- [開發環境建構](https://github.com/TSVS-Special-Topic-Group/Development-Environment-Build)
- [Atom 套件推薦](https://github.com/we684123/Atom_packages/tree/8663ebefbbcaf7003b6806314be70cc751cc7773)
- [Setting up Atom as a Python IDE [A How To Guide]](https://hackernoon.com/setting-up-atom-as-a-python-ide-a-how-to-guide-o6dd37ff)
