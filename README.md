# Speed Up Your Workflow <br/> and Live the Easy Life
## Sublime Shortcuts and Package Managers

###Top 10 Sublime Shortcuts:

| **Shortcut Command**  | **Shortcut Function** |  |
| ------------- | ----------------- | ------------------- |
| ⌘ + ⇧ + P    | Open Command Palette| Easy Access to Installed Packages |
| ⌘ + P         | File Switching      | Searches your open directory.  See below for even more functionality. |
| ⌘ + L  | Select Entire Line     | Can repeat command to select more lines.   |
| ⌃ + Tab or ⌃ + ⇧ + Tab  | Select Next/Previous Tab      | Easily move across multiple files |
| ⌘ + [ or ⌘ + ]  | Indent forward or backward     | Allows easy management and organization of your code |
| ⌘ + ⌥ + 2  | Split into 2 windows <br/> (Can open up to 4 windows|  ⌃ + Window Number will move cursor to that window                   |
| ⌘ + ⌃ + Up/Down:  | Move selection up/down      | Can move large code chunks and paragraphs without continuously copy/pasting |
| ⌃ + ⇧ + Up/Down  | Select line above below (Multi-select)     | Multi-select is your best friend.  Use it often to really speed things up! |
| ⌃ + ⌘ + G  | Select All Instances of Selection      | Effortlessly change class, tag, and id names |
| ⌘ + K, ⌘ + V  | Paste History | Lets you keep and choose from multiple items in your clipboard. |
| ⌘ + K, ⌘ + B  | Hide Side Bar | Gives more space to see your code.  |


####*Legend:*
  * ⌘: Command Key
  * ⇧: Shift Key
  * ⌃: Control Key
  * ⌥: Alt Key

###⌘ + P Hack:
```
⌘ + P Will open any file in your directory.  You can chain this with the following symbols to make your search even more accurate!


# : Fuzzy Matching.  Will find by tag name, class name, etc.

: : Line Matching.

@ : Symbol Search. Very useful when navigating css
```
---


| **Package Name**  | **Package Use** | Link |
| ------------- | ----------------- | ------------------- |
|  Emmet   | Emmet can make your HTML and CSS workflow lightning fast! <br/>Over Has over 1.43 million users! | [Emmet Website](http://emmet.io/) <br/> [Emmet Cheatsheet](http://docs.emmet.io/cheat-sheet/) |
|  AdvancedNewFile  | Allows faster file creation within Sublime Text | [AdvancedNewFile Repo](https://github.com/skuroda/Sublime-AdvancedNewFile) |
|  Color Highlighter  | Adds unobtrusive preview colors and color picker. <br/> Open Color Picker: ⇧+⌃+C | [Color Highlighter Repo](https://packagecontrol.io/packages/Color%20Highlighter) |
|  Git & Gitgutter  | Adds git functionality within Sublime and shows changes to most recent commit in real time. | [Git for Sublime](https://github.com/kemayo/sublime-text-git) <br/> [GitGutter](https://github.com/jisaacks/GitGutter) |
|  SideBar Enhancements  | Expands your options in the sidebar and allows you to easily open files within the browser. | [SideBar Repo](https://github.com/titoBouzout/SideBarEnhancements) |
|  Sublime Linter  | Analyzes your code for potential error.  Available for CSS, Javascript, Ruby, jQuery, and more! | [Sublime Linter](http://www.sublimelinter.com/en/latest/about.html) |
|  Prettify  | Automatically indents your code to make it more readable. | [Prettify Repo](https://github.com/victorporof/Sublime-HTMLPrettify) |

<br>
<br>
If you are curious about a particular package, check out https://packagecontrol.io/


===
###Advanced:
####Running Javascript inside of Sublime Text 3 (for OSX):
  1. Make sure you have node installed
  2. Go to Tools --> Build System --> New Build System
  3. A file named untitled.sublime-build should open and look like this

    ```JSON
    {
      "shell_cmd": "make"
    }
    ```

  4. Insert the following code:

    ```JSON
    {
      "shell_cmd": "node ${file}",
      "selector" : "source.js"
    }
    ```

  5. Save the file as Node.sublime-build
  6. Go back to Tools --> Build System and select Node.
  7. Press ⌘ + B in the file you want to run.
  8. ???
  9. Profit!
