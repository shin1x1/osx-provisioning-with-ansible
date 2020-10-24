# osx provisioning playbook
 
Inspired by https://github.com/mawatari/mac-provisioning
 
## Usage
 
```
$ git clone this_repo
$ cd this_repo
$ ansible-playbook -i hosts osx.yml
```
 
## Usage with dotfiles and ssh role（for me）

```
$ git clone this_repo
$ cd this_repo
$ vi osx.yml
  roles:
    - homebrew
    - dotfiles # uncomment this line
    - ssh # uncomment this line

$ ansible-playbook -i hosts osx.yml --ask-vault-pass
Vault password: # <--- Enter vault password
```

## Apps

* [AdoptOpenJDK](https://adoptopenjdk.net/)
* [JetBrains Toolbox App](https://www.jetbrains.com/toolbox-app/)
* [iTerm2](https://iterm2.com/)
* [Google Chrome](https://www.google.co.jp/chrome/)
* [Firefox](https://www.mozilla.org/ja/firefox/new/)
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](https://www.vagrantup.com/)
* [Docker Desktop for Mac](https://www.docker.com/products/docker-desktop)
* [Dropbox](https://www.dropbox.com/basic)
* [Google 日本語入力](https://www.google.co.jp/ime/)
* [Typora](https://typora.io/)
* [Franz](https://meetfranz.com/)
* [Bartender](https://www.macbartender.com/)
* [XMind](https://jp.xmind.net/)
* [Zoom](https://zoom.us/)
* [LICEcap](https://www.cockos.com/licecap/)
* [Adobe Acrobat Reader DC](https://acrobat.adobe.com/jp/ja/acrobat/pdf-reader.html)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Office 365](https://www.office.com/)
* [Rust](https://www.rust-lang.org/)
* [Auphonic Leveler Batch Processor](https://auphonic.com/leveler)
* [DeepL翻訳](https://www.deepl.com/translator)

### App Store

* CotEditor
* iStat Menus
* Pomo Done
* BetterSnapTool
* LiveReload
* Kindle
* WinArchiver
* Bear
* 1Password
* Evernote
* Logic Pro X

## Licence

MIT
