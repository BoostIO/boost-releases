# Boostnote Changelog

[back to readme.md](readme.md)

> ### Other languages
> - [日本語](changelog-jp.md)
> - [한국어](changelog-kr.md)

## 0.5.2 (2015/1/18)

- Unintended behavior of switching Preview/Editor when right clicking is fixed
- Opening search form in editor(OSX: ⌘ + F, Win: Ctrl + F) won't fire switching preview.
- 'Right click to toggle Preview/Editor' option will be added.
- Strikethrough syntax `~~` won't be sanitized.
- Checkbox syntax `[ ]`, `[x]` will be added.
- Default key of global shortcut open-main-window will be changed.(OSX: ⌘ + alt + L Wins: Windows + Alt + E)
- \& in Latex block won't be sanitized to &amp;
- Windows Only : Base font-family will be changed(helvetica, arial, sans-serif -> meiryo, 'Microsoft Yahei', helvetica, arial, sans-serif)

## 0.5.1 (2015/1/11)

- Enhanced UI/UX (No more Edit / Save button)
- CommonMark support(HTML available)
- Latex block(`$$`, `$$$`)
- Configurable Font/Indent style
- Insensitive-case Search

## 0.5.0 (2015/12/13)

- Windows app has been released!
- Boostnote has been codesigned properly. (both Windows and Mac app)
- IPC between main window and finder window has been improved.

---

## 0.4.7 (2015/12/13)

We relaunch our app. Boost, therefore, became **OBSOLETE**.
Please re-install from [here](http://b00st.io)! Your data automatically moved to our new app.

## 0.4.6 (2015/12/14)

- Sharing a post via public URL(valid for 7 days) is available
- Hotkey added: Ctrl+p for move cursor up in CodeEditor.
- Debug: Dragging in Finder window is available.
- Debug: Search value of Finder window will be reset automatically.
- Debug: Changing order of the folders will be saved correctly.

## 0.4.5 (2015/12/8)

- Markdown preview will be automatically scrolled to the position of cursor.
- Style of markdown is improved.

## 0.4.4 (2015/12/4)

- The value of search input will be escaped.
- User name(Top-left) is editible now. check the preferences.

> User name is not significant yet.
> It will be needed when git repository based sharing is available.

## 0.4.3 (2015/12/1)

- Discuss Link added.
- When creating a new post without title, creation time will be set to its title.
- new short-cut key, Cmd + p, is available to toggle markdown preview/edit mode.
- new short-cut key, Cmd + n, is available to create a new post.
- 'visible on all workspace' option is unset.
- some trivial problems is fixed.

## 0.4.2 (2015/11/25)

- Finder behaviour fixed.
- Syntax hightlight in code block of markdown is available.
- Emoji is also available.
- Clicking cancel button when editing also causes show alert if there is a unsaved feature.

## 0.4.1-beta.3 (2015/11/22)

- Fix some bugs when creating an post
- Edit default article content
- Fix notification(Node-notifier -> WebNotification)

## 0.4.1-beta.2 (2015/11/21)

We decided to hide our codes.
Actually there is a plan to make our app public, but not now.

- The code in this app has been uglified and pack with Asar.
- Disable to toggle devtools

## 0.4.1-beta.1 (2015/11/18)

- Fixed Unsaved alert modal which appears wrong time.

## 0.4.1-beta (2015/11/16)

- App will check a new update automatically(former: Only checked once when app is just started)
- Editing the order and the color of folders is available.
- When an article is on editing, switching article will be blocked with alert modal.
- Notification icons are fixed properly.
- keydown handling of some input is improved.
(Enter to submit: CreateNewFolder, Preferences/ManageFolder)
- Tag suggest is available when editing tags
