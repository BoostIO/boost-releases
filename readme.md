# Boost releases

## Download link

[Latest](https://github.com/BoostIO/boost-releases/releases/latest)

## Changelog

## 0.5.13 (2015/6/12)

- Scroll bar will be hidden when modal opens

## 0.5.12 (2015/5/13)

- Line number for code block in Markdown note

## 0.5.11 (2015/4/25)

- Enable Finder on Cinnamon.
- Add missing features of Dark theme.

## 0.5.10 (2015/4/25)

- Dark theme.
- Editor themes & Preview codeblock themes.

## 0.5.9 (2015/4/11)

- App will quit when main-window closed.
- 'There is no newer version' alert won't show anymore.

## 0.5.8 (2015/4/3)

- Fix editor selection bug
- Fix file drop bug

## 0.5.7 (2016/3/28)

- modify contact links

## 0.5.6 (2016/3/28)

- add announcement about OSS
- replace contact form with contact link

### 0.5.5 (2016/3/16)

- Focus search input when main-window called by hotkey
- Bump up Electron to v0.36.11
- Editor font family also applied title input
- Zoom factor can be configurable by Ctrl+WheelScroll(Windows, Linux only)
- Fix emacs key binding of Ace editor(Ctrl-a, Ctrl-p)
- Long line of tags in Post list will be wrapped

### 0.5.4 (2016/1/25)

- HTML code in code fence won't be sanitized.
- The bug of Ace editor, command ctrl+e on Editor(go to line end),  is fixed.
- Markdown style is improved.
- Anchor with image works well now.

### 0.5.3 (2016/1/19)

- Fixed. Switching preview with ESC key when set switch preview on right click doesn't work well.
- Fixed. Switching preview/editor which doesn't work well after updating v0.5.2.
- Strange behavior of Preferences when setting shortcuts is fixed.

### 0.5.2 (2016/1/18)

- Unintended behavior of switching Preview/Editor when right clicking is fixed
- Opening search form in editor(OSX: ⌘ + F, Win: Ctrl + F) won't fire switching preview.
- 'Right click to toggle Preview/Editor' option will be added.
- Strikethrough syntax `~~` won't be sanitized.
- Checkbox syntax `[ ]`, `[x]` will be added.
- Default key of global shortcut open-main-window will be changed.(OSX: ⌘ + alt + L Wins: Windows + Alt + E)
- \& in Latex block won't be sanitized to &amp;
- Windows Only : Base font-family will be changed(helvetica, arial, sans-serif -> meiryo, 'Microsoft Yahei', helvetica, arial, sans-serif)

### 0.5.1 (2016/1/11)

- Enhanced UI/UX (No more Edit / Save button)
- CommonMark support(HTML available)
- Latex block(`$$`, `$$$`)
- Configurable Font/Indent style
- Insensitive-case Search

### 0.5.0 (2015/12/13)

- Windows app has been released!
- Boostnote has been codesigned properly. (both Windows and Mac app)
- IPC between main window and finder window has been improved.

---

### 0.4.7 (2015/12/13)

We relaunch our app. Boost, therefore, became **OBSOLETE**.
Please re-install from [here](http://b00st.io)! Your data automatically moved to our new app.

### 0.4.6 (2015/12/14)

- Sharing a post via public URL(valid for 7 days) is available
- Hotkey added: Ctrl+p for move cursor up in CodeEditor.
- Debug: Dragging in Finder window is available.
- Debug: Search value of Finder window will be reset automatically.
- Debug: Changing order of the folders will be saved correctly.

### 0.4.5 (2015/12/8)

- Markdown preview will be automatically scrolled to the position of cursor.
- Style of markdown is improved.

### 0.4.4 (2015/12/4)

- The value of search input will be escaped.
- User name(Top-left) is editible now. check the preferences.

> User name is not significant yet.
> It will be needed when git repository based sharing is available.

### 0.4.3 (2015/12/1)

- Discuss Link added.
- When creating a new post without title, creation time will be set to its title.
- new short-cut key, Cmd + p, is available to toggle markdown preview/edit mode.
- new short-cut key, Cmd + n, is available to create a new post.
- 'visible on all workspace' option is unset.
- some trivial problems is fixed.

### 0.4.2 (2015/11/25)

- Finder behaviour fixed.
- Syntax hightlight in code block of markdown is available.
- Emoji is also available.
- Clicking cancel button when editing also causes show alert if there is a unsaved feature.

### 0.4.1-beta.3 (2015/11/22)

- Fix some bugs when creating an post
- Edit default article content
- Fix notification(Node-notifier -> WebNotification)

### 0.4.1-beta.2 (2015/11/21)

We decided to hide our codes.
Actually there is a plan to make our app public, but not now.

- The code in this app has been uglified and pack with Asar.
- Disable to toggle devtools

### 0.4.1-beta.1 (2015/11/18)

- Fixed Unsaved alert modal which appears wrong time.

### 0.4.1-beta (2015/11/16)

- App will check a new update automatically(former: Only checked once when app is just started)
- Editing the order and the color of folders is available.
- When an article is on editing, switching article will be blocked with alert modal.
- Notification icons are fixed properly.
- keydown handling of some input is improved.
(Enter to submit: CreateNewFolder, Preferences/ManageFolder)
- Tag suggest is available when editing tags
