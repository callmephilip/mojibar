# Mojibar [![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

A menubar app adaptation of [Emoji searcher](http://emoji.muan.co).

![screenshot](https://cloud.githubusercontent.com/assets/1153134/8794765/1c246d46-2fb9-11e5-9429-560fa1192b4f.gif)

## Install

#### :triangular_flag_on_post: Download and drag

[Download the latest version for Mac on the releases page](https://github.com/muan/mojibar/releases) (and drag into your apps folder.)

#### :triangular_flag_on_post: Install using [Homebrew Cask](http://caskroom.io/)

```
$ brew cask install mojibar
```
#### :triangular_flag_on_post: Launch Mojibar

Go into your apps folder and select Mojibar (Mac shortcut: use command-space bar, then type Mojibar in the spotlight search field). Mojibar will display in the menubar at the top right corner of your screen. 

## Usage

<kbd>ctrl + shift + space</kbd><br>
Open app.

<kbd>👆/👇/👈/👉</kbd><br>
Navigate between emojis.

<kbd>enter</kbd><br>
Copy emoji unicode char and exit. For example: `💩`.

<kbd>shift + enter</kbd><br>
Copy emoji code and exit. For example: `:poop:`.

<kbd>space</kbd><br>
Next 6~9 results.

<kbd>shift + space</kbd><br>
Previous 6~9 results.

<kbd>/</kbd><br>
Jump to the search field.

<kbd>esc</kbd><br>
Exit.

<kbd>cmd + q</kbd><br>
Quit Mojibar (while window is open).

## Build

:construction:

```
$ git clone https://github.com/muan/mojibar.git
$ cd mojibar
$ npm install
$ npm run app
```

If you don't have `electron-prebuilt`, do this:

```
$ npm install electron-prebuilt -g
```

## Built with

- [maxogden/menubar](https://github.com/maxogden/menubar)
- [muan/emojilib](https://github.com/muan/emojilib)

## :heart:
