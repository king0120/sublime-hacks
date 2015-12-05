# Speed Up Your Workflow and Make Life Easy
## Sublime Shortcuts and Package Managers

###Top 10 Sublime Shortcuts:

| **Shortcut Command**  | **Shortcut Function** |  |
| ------------- | ----------------- | ------------------- |
| ⌘ + ⇧ + P    | Open Command Palette| Easy Access to Installed Packages |
| ⌘ + P         | File Switching      | Searches your open directory.  See below for even more functionality. |
| ⌘ + L  | Select Entire Line     | Can repeat command to select more lines.   |
| ⌃ + Tab or ⌃ + ⇧ + Tab  | Select Next/Previous Tab      |                     |
| ⌘ + [ or ⌘ + ]  | Indent forward or backward     |                     |
| ⌘ + ⌥ + 2  | Split into 2 windows (Can go up to 4) |  ⌃ + group number: hop to that grouping                   |
| ⌘ + ⌃ + Up/Down:  | Move selection up/down      |                     |
| ⌃ + ⇧ + Up/Down  | Select line above below (Multi-select)     |                     |
| ⌃ + ⌘ + G  | Select All of Selection      |                     |
| ⌘ + K, ⌘ + V  | Paste History      |                     |


####*Legend*
  * ⌘: Command Key
  * ⇧: Shift Key
  * ⌃: Control Key
  * ⌥: Alt Key

###⌘ + P Lifehacks:
```
⌘ + P Will open any file in your directory.  You can chain this
with the following symbols to make your search even more accurate!


# : Fuzzy Matching.  Will find by tag name, class name, etc.

: : Line Matching.

@ : Symbol Search. Very useful when navigating css
```
---


| **Package Name**  | **Package Use** | Link |
| ------------- | ----------------- | ------------------- |
|  Emmet   | Emmet can make your HTML and CSS workflow lightning fast! Over Has over 1.43 million users! | http://emmet.io/  http://docs.emmet.io/cheat-sheet/ |
|  AdvancedNewFile  | Allows faster file creation within Sublime Text | https://github.com/skuroda/Sublime-AdvancedNewFile |
|  Color Highlighter  | Adds unobtrusive preview colors and color picker. Open Color Picker: ⇧+⌃+C | https://packagecontrol.io/packages/Color%20Highlighter |
|  Git & Gitgutter  | Adds git functionality within Sublime and shows changes to most recent commit in real time. | https://github.com/kemayo/sublime-text-git    https://github.com/jisaacks/GitGutter |
|  SideBar Enhancements  | Expands your options in the sidebar and allows you to easily open files within the browser. | https://github.com/titoBouzout/SideBarEnhancements |
|  Sublime Linter  | Analyzes your code for potential error.  Available for CSS, Javascript, Ruby, jQuery, and more! | http://www.sublimelinter.com/en/latest/about.html |
|  Prettify  | Automatically indents your code to make it more readable. | https://github.com/victorporof/Sublime-HTMLPrettify |

If you are curious about a particular package, check out https://packagecontrol.io/packages/SideBarEnhancements



Advanced:
Running Javascript inside of Sublime Text 3:
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
