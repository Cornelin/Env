# Sublime Text 3

## Introduction

Sublime Text 3 is our editor of choice here at [Cornelin]!

We chose Sublime Text 3 for several reasons. It is fast, light-weight and highlycustomisable through plugins and snippets!

Sublime Text 3 can really be a representation of your coding style. It will feel like home in a matter of minutes!

#### Notes

In this readme we will use the notation ⌘ to describe commands since we are running on Mac Os X. Just replace ⌘ with ctrl if you are on another sytsem.

## Get Started!

First of all you need to get [Sublime Text 3].

In order to get the most out of Sublime Text 3 you also need to install the [Package Control]. Follow the [instructions] to get you ready for what is coming next!

## Some basics

#### Multi cursor

Just select a portion of text and press `⌘ + D` to select the next occurrence. Repeat this action until you have highlighted everything you want!

#### Open a folder

Hit `⌘ + O` and select a folder to open an entier folder and nagivate throught all the files inside with the side bar

#### Quickly open a file

When you are working inside a folder you can quickly open a file by hitting `⌘ + P` and type the filename you want. It's far more efficiant than selecting it from the sidebar. You can also specify a function after the file name with `@` to open a file at the given point!

#### Command Palette

Hit `⌘ + ⇧ + P` to access the Command Palette. The Command Palette gives you fast access to functionality. For instance let's say you want to set the syntax coloration to javascript, open the Command Palette and start typing javascript. You will see the dropdown list with Set Syntax: Javascript. This works for almost every actions you can with Sublime Text or it's plugins and snippets!

## Advanced configuration

This configuration is the final step to get your Sublime Text working as we experienced it without plugins or snippets.

To do so go into `Preferences -> Settings - User`.

#### Commit on tab instead of enter
When sublime propose you some actions this options allow you to confirm it by hitting `tab` instead or `enter` this allows you to differenciate between a newline and validating an action:

```json
"auto_complete_commit_on_tab": true,
"auto_complete_delay": 0
```

#### Highlight line
Highlight the line where the cursor is located:

``` json
"highlight_line": true,
```

#### Highlight modified tab
This highlight every tab where a modification has been made since the last save:

``` json
"highlight_modified_tabs": true,
```

#### Trim and add spaces
This add a newline at the end of file and trim trailing white spaces:

``` json
"ensure_newline_at_eof_on_save": true,
"trim_trailing_white_space_on_save": true
```

#### Full configuration file
Here is our full configuration file:
``` json
{
    "auto_complete_commit_on_tab": true,
    "auto_complete_delay": 0,
    "bold_folder_labels": true,
    "ensure_newline_at_eof_on_save": true,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "rulers":
    [
        80
    ],
    "scroll_past_end": true,
    "trim_trailing_white_space_on_save": true
}
```

## Projects

TODO

## Plugins

#### Install a plugin
After you installed the package control, hit `⌘ + ⇧ + P` to open the command palette and type `install` then press `enter`. Next, type in the name of the plugin you want to install and press `enter` to install it.

- Alignment
- All autocomplete
- BracketHighligter
- DashDoc
- DocBlockr
- EditorConfig
- LoremIpsum
- Markdown Previez
- Markdown editing
- Modific
- SublimeLinter
- SublimeLinter-contib-eslint

[Cornelin]: https://github.com/Cornelin
[Sublime Text 3]:http://www.sublimetext.com/3
[Package Control]:https://packagecontrol.io/
[instructions]:https://packagecontrol.io/installation
