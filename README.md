# IntelliJ IDEA Key Bindings for Visual Studio Code that transforms Mac-keybindings to PC-keybindings

This is a fork of kasecato's popular library. This simply re-maps a Mac to act like a PC (switching CTRL and CMD keys). It leaves PC alone.

[![Build Status](https://travis-ci.org/kasecato/vscode-intellij-idea-keybindings.svg?branch=master)](https://travis-ci.org/kasecato/vscode-intellij-idea-keybindings) [![License: MIT](https://img.shields.io/badge/license-MIT-orange.svg)](LICENSE.md) [![Marketplace Version](https://vsmarketplacebadge.apphb.com/version/k--kato.intellij-idea-keybindings.svg)](https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings) [![Install](https://vsmarketplacebadge.apphb.com/installs-short/k--kato.intellij-idea-keybindings.svg)](https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings)

Port of IntelliJ IDEA key bindings for VS Code. Includes keymaps for popular JetBrains products like IntelliJ Ultimate, WebStorm, PyCharm, PHP Storm, etc.

## Usage


### Editing

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
ctrl+space | ctrl+space | Basic code completion (the name of any class, method or variable) | ✅
ctrl+shift+space | ctrl+shift+space | Smart code completion (filters the list of methods and variabl
es by expected type) | N/A
ctrl+shift+enter | ctrl+shift+enter | Complete statement | ✅
ctrl+p | ctrl+p | Parameter info (within method call arguments) | ✅
ctrl+q | ctrl+q | Quick documentation lookup | ✅
ctrl+f1 | ctrl+f1 | External Doc | N/A
ctrl+mouseover | ctrl+mouseover | Brief Info | N/A
ctrl+f1 | ctrl+f1 | Show descriptions of error or warning at caret | ✅
alt+insert | cmd+insert | Generate code... (Getters, Setters, Constructors, hashCode/equals, toStrin
g) | ✅
ctrl+o | ctrl+o | Override methods | N/A
ctrl+i | ctrl+i | Implement methods | N/A
ctrl+alt+t | ctrl+cmd+t | Surround with... (if..else, try..catch, for, synchronized, etc.) | N/A
ctrl+/ | ctrl+/ | Comment/uncomment with line comment | ✅
ctrl+numpad_divide | ctrl+numpad_divide | Comment/uncomment with line comment | ✅
ctrl+alt+/ | ctrl+cmd+/ | Comment/uncomment with block comment | ✅
ctrl+alt+numpad_divide | ctrl+cmd+numpad_divide | Comment/uncomment with block comment | ✅
ctrl+w | ctrl+w | Select successively increasing code blocks | ✅
ctrl+shift+w | ctrl+shift+w | Decrease current selection to previous state | ✅
alt+q | cmd+q | Context info | N/A
alt+enter | cmd+enter | Show intention actions and quick-fixes | ✅
ctrl+alt+l | ctrl+amd+l | Reformat code | ✅
ctrl+alt+l | ctrl+cmd+l | Reformat selected code | ✅
ctrl+alt+o | ctrl+cmd+o | Optimize imports | N/A
ctrl+alt+i | ctrl+cmd+i | Auto-indent line(s) | N/A
tab | tab | Indent selected lines | N/A
shift+tab | shift+tab | Unindent selected lines | N/A
ctrl+x | ctrl+x | Cut current line or selected block to clipboard | ✅
shift+delete | shift+delete | Cut current line or selected block to clipboard | ✅
ctrl+c | ctrl+c | Copy current line or selected block to clipboard | ✅
ctrl+v | ctrl+v | Paste from clipboard | ✅
ctrl+shift+v | ctrl+shift+v | Paste from recent buffers... | N/A
ctrl+d | ctrl+d | Duplicate current line or selected block | ✅
ctrl+y | ctrl+y | Delete line at caret | ✅
ctrl+shift+j | ctrl+shift+j | Smart line join | ✅
ctrl+enter | ctrl+enter | Smart line split | ✅
shift+enter | shift+enter | Start new line | ✅
ctrl+shift+u | ctrl+shift+u | Toggle case for word at caret or selected block | N/A
ctrl+shift+] | ctrl+shift+] | Select till code block end | N/A
ctrl+shift+[ | ctrl+shift+[ | Select till code block start | N/A
ctrl+delete | ctrl+delete | Delete to word end | ✅
ctrl+backspace | ctrl+backspace | Delete to word start | ✅
ctrl+= | ctrl+= | Expand code block | ✅
ctrl+numpad_add | ctrl+numpad_add | Expand code block | ✅
ctrl+- | ctrl+- | Collapse code block | ✅
ctrl+numpad_subtract | ctrl+numpad_subtract | Collapse code block | ✅
ctrl+shift+= | ctrl+shift+= | Expand all | ✅
ctrl+shift+numpad_add | ctrl+shift+numpad_add | Expand all | ✅
ctrl+shift+- | ctrl+shift+- | Collapse all | ✅
ctrl+shift+numpad_subtract | ctrl+shift+numpad_subtract | Collapse all | ✅
ctrl+f4 | ctrl+w | Close active editor tab | ✅
alt+j | cmd+g | Add selection for Next Occurrence | ✅
alt+shift+j | cmd+shift+g | Unselect Occurrence | ✅
shift+alt+down | shift+cmd+down | Move Line Down | ✅
shift+alt+up | shift+cmd+up | Move Line Up | ✅

### Search/Replace

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
shift shift | shift shift | Search everywhere | N/A
ctrl+f | ctrl+f | Find | ✅
f3 | f3 | Find next | ✅
shift+f3 | shift+f3 | Find previous | ✅
ctrl+r | ctrl+r | Replace | ✅
ctrl+shift+f | ctrl+shift+f | Find in path | ✅
ctrl+shift+r | ctrl+shift+r | Replace in path | ✅
ctrl+shift+s | ctrl+shift+s | Search structurally (Ultimate Edition only) | N/A
ctrl+shift+m | ctrl+shift+m | Replace structurally (Ultimate Edition only) | N/A

### Usage Search

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
alt+f7 | cmd+f7 | Find usages | ✅
alt+ctrl+f7 | cmd+ctrl+f7 | Show usages | ✅
ctrl+f7 | ctrl+f7 | Find usages in file | N/A
ctrl+shift+f7 | ctrl+shift+f7 | Highlight usages in file | N/A
ctrl+alt+f7 | ctrl+cmd+f7 | Show usages | N/A

### Compile and Run

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
ctrl+f9 | ctrl+f9 | Make project (compile modifed and dependent) | ✅
ctrl+shift+f9 | ctrl+shift+f9 | Compile selected file, package or module | N/A
alt+shift+f10 | cmd+shift+f10 | Select configuration and run | ✅
alt+shift+f9 | cmd+shift+f9 | Select configuration and debug | ✅
shift+f10 | shift+f10 | Run | N/A
shift+f9 | shift+f9 | Debug | ✅
ctrl+shift+f10 | ctrl+shift+f10 | Run context configuration from editor | N/A
ctrl+shift+f10 | ctrl+shift+f10 | Debug context configuration from editor | N/A

### Debugging

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
f8 | f8 | Step over | ✅
f7 | f7 | Step into | ✅
shift+f7 | shift+f7 | Smart step into | N/A
shift+f8 | shift+f8 | Step out | ✅
alt+f9 | alt+f9 | Run to cursor | ✅
alt+f8 | alt+f8 | Evaluate expression | ✅
alt+f8 | alt+f8 | Evaluate expression (selection) | ✅
f9 | f9 | Resume program | ✅
ctrl+f8 | ctrl+f8 | Toggle breakpoint | ✅
ctrl+shift+f8 | ctrl+shift+f8 | View breakpoints | ✅

### Navigation

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
ctrl+n | ctrl+n | Go to class | ✅
ctrl+shift+n | ctrl+shift+n | Go to file | ✅
ctrl+alt+shift+n | ctrl+cmd+shift+n | Go to symbol | ✅
alt+left | cmd+left | Go to previous editor tab | ✅
alt+right | cmd+right | Go to next editor tab | ✅
f12 | f12 | Go back to previous tool window | N/A
escape | escape | Go to editor (from tool window) | N/A
shift+escape | shift+escape | Hide active or last active window (Sidebar) | ✅
shift+escape | shift+escape | Hide active or last active window (Output) | ✅
shift+escape | shift+escape | Hide active or last active window (Problems) | ✅
shift+escape | shift+escape | Hide active or last active window (Debug Console) | ✅
shift+escape | shift+escape | Hide active or last active window (Terminal) | ✅
shift+escape | shift+escape | Hide active or last active window (Panel) | N/A
ctrl+shift+f4 | ctrl+shift+f4 | Close active run/messages/find/... tab | N/A
ctrl+g | ctrl+l | Go to line | ✅
ctrl+e | ctrl+e | Recent files popup | ✅
ctrl+alt+left | ctrl+cmd+left | Navigate back | ✅
 | ctrl+[ | Navigate back | ✅
ctrl+alt+right | ctrl+cmd+right | Navigate forward | ✅
 | ctrl+] | Navigate forward | ✅
ctrl+shift+backspace | ctrl+shift+backspace | Navigate to last edit location | ✅
alt+f1 | cmd+f1 | Select current file or symbol in any view | N/A
ctrl+b | ctrl+b | Go to declaration | ✅
ctrl+alt+b | ctrl+cmd+b | Go to implementation(s) | ✅
ctrl+shift+i | ctrl+shift+i | Open quick definition lookup | ✅
ctrl+shift+b | ctrl+shift+b | Go to type declaration | ✅
ctrl+u | ctrl+u | Go to super-method/super-class | N/A
alt+up | cmd+up | Go to previous method | N/A
alt+down | cmd+down | Go to next method | N/A
ctrl+] | ctrl+] | Move to code block end | N/A
ctrl+[ | ctrl+[ | Move to code block start | N/A
alt+7 | cmd+7 | Structure | ✅
ctrl+f12 | ctrl+f12 | File structure popup | ✅
ctrl+h | ctrl+h | Type hierarchy | N/A
ctrl+shift+h | ctrl+shift+h | Method hierarchy | N/A
ctrl+alt+h | ctrl+alt+h | Call hierarchy | N/A
f2 | f2 | Next highlighted error | ✅
shift+f2 | shift+f2 | Previous highlighted error | ✅
f4 | f4 | Edit source | ✅
ctrl+enter | ctrl+down | View source | ✅
shift+ctrl+down | shift+ctrl+down | Move Statement Down | ✅
shift+ctrl+up | shift+ctrl+up | Move Statement Up | ✅
alt+home | alt+home | Show navigation bar | N/A
f11 | f11 | Toggle bookmark | N/A
ctrl+f11 | ctrl+f3 | Toggle bookmark with mnemonic | N/A
ctrl+0 | ctrl+0 | Go to numbered bookmark | N/A
shift+f11 | shift+f3 | Show bookmarks | N/A
ctrl+alt+shift+down | ctrl+alt+shift+down | Next Change | ✅
ctrl+alt+shift+up | ctrl+alt+shift+up | Previous Change | ✅

### Refactoring

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
f5 | f5 | Copy | N/A
f6 | f6 | Move | N/A
alt+delete | cmd+delete | Safe Delete | N/A
shift+f6 | shift+f6 | Rename | ✅
shift+f6 | shift+f6 | Rename (File) | ✅
ctrl+f6 | ctrl+f6 | Change Signature | N/A
ctrl+alt+n | ctrl+cmd+n | Inline | N/A
ctrl+alt+m | ctrl+cmd+m | Extract Method | ✅
ctrl+alt+v | ctrl+cmd+v | Extract Variable | ✅
ctrl+alt+f | ctrl+cmd+f | Extract Field | N/A
ctrl+alt+c | ctrl+cmd+c | Extract Constant | N/A
ctrl+alt+p | ctrl+cmd+p | Extract Parameter | N/A

### VCS/Local History

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
ctrl+alt+k | ctrl+cmd+k | Commit project to VCS | ✅
ctrl+shift+k | ctrl+shift+k | Push commits to VCS | ✅
ctrl+t | ctrl+t | Update project from VCS | ✅
ctrl+alt+z | ctrl+cmd+z | Rollback Lines | ✅
alt+shift+c | cmd+shift+c | View recent changes | N/A

### Live Templates

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
ctrl+alt+j | ctrl+cmd+j | Surround with Live Template | N/A
ctrl+j | ctrl+j | Insert Live Template | N/A

### General

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
alt+0 | cmd+0 | Activate Messages window (Problems) | ✅
alt+numpad0 | cmd+numpad0 | Activate Messages window (Problems) | ✅
alt+1 | cmd+1 | Open corresponding tool window (Explorer) | ✅
alt+numpad1 | cmd+numpad1 | Open corresponding tool window (Explorer) | ✅
alt+1 | cmd+1 | Close corresponding tool window (Explorer) | ✅
alt+numpad1 | cmd+numpad1 | Close corresponding tool window (Explorer) | ✅
alt+3 | cmd+3 | Open corresponding tool window (Search) | ✅
alt+numpad3 | cmd+numpad3 | Open corresponding tool window (Search) | ✅
alt+3 | cmd+3 | Close corresponding tool window (Search) | ✅
alt+numpad3 | cmd+numpad3 | Close corresponding tool window (Search) | ✅
alt+5 | cmd+5 | Open corresponding tool window (Debug) | ✅
alt+numpad5 | cmd+numpad5 | Open corresponding tool window (Debug) | ✅
alt+5 | cmd+5 | Close corresponding tool window (Debug) | ✅
alt+numpad5 | cmd+numpad5 | Close corresponding tool window (Debug) | ✅
alt+9 | cmd+9 | Open corresponding tool window (Git) | ✅
alt+numpad9 | cmd+numpad9 | Open corresponding tool window (Git) | ✅
alt+9 | cmd+9 | Close corresponding tool window (Git) | ✅
alt+numpad9 | cmd+numpad9 | Close corresponding tool window (Git) | ✅
ctrl+s | ctrl+s | Save all | ✅
ctrl+alt+y | ctrl+cmd+y | Synchronize | ✅
ctrl+alt+f | ctrl+cmd+f | Toggle full screen mode | ✅
ctrl+shift+f12 | ctrl+shift+f12 | Toggle maximizing editor | ✅
alt+shift+f | cmd+shift+f | Add to Favorites | N/A
alt+shift+i | cmd+shift+i | Inspect current file with current profile | N/A
ctrl+\` | ctrl+\` | Quick switch current scheme | ✅
ctrl+alt+s | ctrl+cmd+s, | Open Settings dialog | ✅
ctrl+alt+s | ctrl+cmd+s | Open Settings dialog | ✅
ctrl+alt+shift+s | ctrl+cmd+shift+s | Open Project Structure dialog | ✅
ctrl+shift+a | ctrl+shift+a | Find Action | ✅
ctrl+tab | ctrl+tab | Switch between tabs and tool window | ✅

### Custom

Linux, Windows | macOS | Feature | Supported
---------------|------|---------|----------
f7 | f7 | Next difference | ✅
shift+f7 | shift+f7 | Previous difference | ✅
alt+ctrl+enter | cmd+ctrl+enter | Start new line before current | ✅
shift+ctrl+enter | shift+ctrl+enter | Start new line | ✅
alt+f12 | cmd+f12 | Opens and focuses corresponding tool window (Terminal) | ✅
alt+f12 | cmd+f12 | Close corresponding tool window (Terminal) | ✅
ctrl+shift+alt+j | ctrl+shift+cmd+j | Sublime Text style multiple selections | ✅
alt+left | cmd+left | Select previous tab (Terminal) | ✅
alt+right | cmd+right | Select next tab (Terminal) | ✅
alt+tab | cmd+tab | Goto next splitter | ✅
shift+alt+tab | shift+cmd+tab | Goto previous splitter | ✅
enter | enter | Open Highlighted File (Explorer) | ✅
alt+home | cmd+home | Jump to Navigation Bar | ✅
shift+ctrl+c | shift+ctrl+c | Copy paths | ✅

## Installation

1. Install Visual Studio Code 1.30.2 or higher
1. Launch Code
1. From the extension view `Ctrl`-`Shift`-`X` (Windows, Linux) or `Cmd`-`Shift`-`X` (macOS)
1. Search and Choose the extension `Intellij IDEA Keybindings`
1. Reload Visual Studio Code


## Contributing to the Code

Clone a copy of the repo:

```
git clone https://github.com/kasecato/vscode-intellij-idea-keybindings.git
```


### Building the code

First, install the package dependencies:

```
npm install
```

Now you can compile the code:

1. Launch Code
1. Edit **`src/package-with-comment.json`** (**NOT `package.json`**)
1. Run Build Task `Ctrl`-`Shift`-`B` (Windows, Linux) or `Cmd`-`Shift`-`B` (macOS)
1. Run Command Markdown Generator `node src/tool/gene-keybind-markdown.js`
1. Paste the Command Markdown to `README.md`

After the initial compile, the source files will be watched and recompiled
when changes are saved.


## Contributors

* [@brianegan](https://github.com/brianegan)
* [@whinc](https://github.com/whinc)
* [@HSAR](https://github.com/HSAR)
* [@mastersimon](https://github.com/mastersimon)
* [@thekalinga](https://github.com/thekalinga)
* [@joaomoreno](https://github.com/joaomoreno)
* [@kasperpeulen](https://github.com/kasperpeulen)
* [@waderyan](https://github.com/waderyan)
* [@megha-n-bodke](https://github.com/megha-n-bodke)
* [@gregbacchus](https://github.com/gregbacchus)
* [@acim](https://github.com/acim)
* [@skysteve](https://github.com/skysteve)
* [@spik3s](https://github.com/spik3s)
* [@AlexAkhremenko](https://github.com/AlexAkhremenko)
* [@rtconner](https://github.com/rtconner)
* [@pavilion](https://github.com/pavilion)
* [@xc1427](https://github.com/xc1427)
* [@michielboekhoff](https://github.com/michielboekhoff)
* [@thekalinga](https://github.com/thekalinga)
* [@andrewda](https://github.com/andrewda)
* [@deftomat](https://github.com/deftomat)
* [@rinormaloku](https://github.com/rinormaloku)
* [@covertbert](https://github.com/covertbert)
* [@flashsphere](https://github.com/flashsphere)
* [@kroleg](https://github.com/kroleg)
* [@faucct](https://github.com/faucct)


## License

This extension is [licensed under the MIT License](LICENSE.md).


## References

1. Source code, Resharper 9 Keybindings, https://marketplace.visualstudio.com/items?itemName=ms-vscode.resharper9-keybindings
1. IntelliJ IDEA DEFAULT KEYMAP, https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf
1. Key Bindings for Visual Studio Code, https://code.visualstudio.com/Docs/customization/keybindings
1. Integrate with External Tools via Tasks, https://code.visualstudio.com/docs/editor/tasks#_autodetecting-gulp-grunt-and-jake-tasks
1. gulp-strip-json-comments, https://www.npmjs.com/package/gulp-strip-json-comments
1. Icon, vscode-vs-keybindings, https://github.com/rebornix/vscode-vs-keybindings/blob/master/visualstudio-keyboard.svg
