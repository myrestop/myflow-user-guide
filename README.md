# Welcome To Our RunFlow User Guide

In this documentation, you will learn our RunFlow's general rules and tips.

### Introduction

RunFlow is a powerful efficiency tool that can be combined with many plugins, and it's running based on keywords, a keyword mean a feature.

You can also pin a keyword to the tab (if keyword support), doing this you don't need always input the keyword to trigger the feature.

> the keyword can be at the front, or the end (but need a whitespace to separate).

### General Constraints

The example usage in the plugin description page, you may see some special characters, like `[]|{}`, `[]` means an optional parameter, `|` means or,  `{}` means a parameter need user input. And all the usage cases are based on the default keyword.

> example: `timer [{name}] {date}` means name is a optional parameter, but you must input a date parameter to start a timer.

In searching action, `?` means match one any character, `*` means match any number of characters.

### Hotkey Tips

`Alt` is a magic hotkey, you can press it to refresh the result (if result support), or open the result context menu (if result has multi operations).

In result list, press `Tab` to get the selected result suggestion text.

#### Switch Pinned Keyword

Use `Alt+LEFT` switch to the previous pinned keyword, `Alt+RIGHT` switch to the next pinned keyword.

And you can also use `Ctrl+{number}` switch to the specified indexed pinned keyword, like `Ctrl+0` switch to the first, `Ctrl+1` switch to the second, `Ctrl+9` switch to the last pinned keyword. And in here, `Alt` has another wonderful usage, press with `Alt`, whether the action window is visible or not, it always show, for example: `Ctrl+Alt+2`, app will show the action window and switch to the third pinned keyword even if it is hidden.

> In macOS, the `Ctrl` is instead by `Command` key.

### Other Tips

- At action input field, you can input by dragging text or file (ensure the action window is pinned)

### Focused Mode

This feature need keyword support, you will always work under the function of this keyword without other keywords disturbed while you enter the focused keyword.

To exit the focused mode, you can type `exit` (you can customize this text at general settings page) or press `Esc` key.

### Multi Language Support

We require plugins must support english language, so english is always available. And our official plugins also contains simplified chinese yet, if you are a traditional chinese user, you can install our [Chinese Processor](https://myrest.top/myflow/plugin?id=top.myrest.myflow.chinese), it can convert simplified chinese to traditional or traditional to simplified.

#### More Language Request

If you request more languages support, you can go to the [plugin store](https://myrest.top/store/myflow/plugin) to find a plugin which support translate language.
