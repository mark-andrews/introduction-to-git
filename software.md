# Installing Git

Mac users usually don't have to do anything. Just go to your terminal and type `which git`, and you should get a oneliner essentially informing you that Git installed. It might look like `/usr/bin/git`. For Windows users, you should install *Git bash* from here https://gitforwindows.org/. Just download and install as you would with any Windows installer. When installing just accept all the defaults in the dialog box.

After you've installed Git, you configure it to use your name and your email.
```bash
git config --global user.name "<your name here>"
git config --global user.email "<your email here>"
```
You should also configure an editor, which will pop up when you add messages.
A good choice is the cross-platform [atom editor](https://atom.io):
```bash
git config --global core.editor "atom --wait"
```
(If you are working on a Mac, and encounter trouble, see [this discussion thread](https://discuss.atom.io/t/not-able-to-associate-atom-with-git-error-macos/15786).)

Some other useful Git configurations are the following:
```bash
git config --global merge.conflictstyle diff3
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
```
