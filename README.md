# slackbuild script for sublime text 3

Sublime Text is a sophisticated text editor for code, markup and prose.
You'll love the slick user interface, extraordinary features and amazing performance.

## dependencies

## usage

```bash
git clone https://github.com/slackwarecn-slackbuilds/sublimetext
wget https://download.sublimetext.com/sublime_text_3_build_3114_x64.tar.bz2
# or wget https://download.sublimetext.com/sublime_text_3_build_3114_x32.tar.bz2 if you are not in slackware64
cd sublimetext
ln -s ../sublime_text_3_build_3114_x64.tar.bz2 # or sublime_text_3_build_3114_x32.tar.bz2
sudo sh sublimetext.SlackBuild
```

## Recommend patch

[Sublime-Text-3 IM-FIX](https://github.com/nnnewb/sublime-text-imfix)