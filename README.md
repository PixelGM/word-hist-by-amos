# Word Hist, by Amos

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/PixelGM/word-hist-by-amos#word-hist-by-amos)

Word Hist is a cloud-enabled, Microsoft Word history.

  - Saves your commit automatically when you pressed it
  - Did an oopsie on the file? Just Discard Changes!
  - Word Hist doesn't use your storage to store the changes, we use GitHub cloud to store your changes.

# 1. Setup

1. Download Github Desktop
2. Sign up and Sign in on GitHub
3. Download this repo
4. Folk the repo
5. Install **Pandoc** in Installer
6. Go to "Files to put"
7. Set hidden items off in File Explorer
8. Copy config to word-diff-by-amos\.git
9. Copy post-commit-git-diff-docx.sh and pre-commit-git-diff-docx.sh to word-diff-by-amos\ .git\hooks

# 2. How to use
1. Open test.docx
2. Edit in word whatever you want
3. Go to Github Desktop, see if it changes.
4. Commit to save the changes
5. You can also *"Revert Changes"* in History
6. Press *crtl + p* or click on *"Publish to repository"* to save the changes to cloud.

### Softwares

Word Hist uses a number of open source projects to work properly:
* [Visual Studio] - Advanced all languages coding software
* [Notepad++] - Awesome text editor
* [Dillinger] - Making README is easier with this!


> The overriding design goal for Word Hist's
> making easier to fetch your recent document
> without saving on your desktop.
> Docx documents can't be seen
> because we need to convert it to
> MarkDown to see the history

   [Visual Studio]: <https://visualstudio.microsoft.com/vs/r>
   [Notepad++]: <https://notepad-plus-plus.org/downloads/>
   [Dillinger]: <https://dillinger.io/>