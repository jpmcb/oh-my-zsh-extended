# Oh-my-Zsh-Extended

This is a repository of useful scripts,
custom configurations,
themes, and much more that you may find useful to further extend
Oh-My-Zsh.

## Installation

#### Is Zsh your current shell?

```sh
echo $SHELL
```

If not, you'll want to follow the Oh-My-Zsh instructions
for getting Zsh, installing it to your machine,
and setting it as your users default shell.

#### Install Oh-My-Zsh

Warning: the Oh-My-Zsh documentation recommends instalation via
Curl piped into `sh` which _can be risky_. Go with caution!

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#### Install Oh-My-Zsh-Extended

After Oh-My-Zsh has installed, you should have a `~/.ohmyzsh/` directory.
This is where Oh-My-Zsh, all it's scripts, and everything lives.
It has a special `custom` sub-directory where we want to place this extension.

```
git clone git@github.com:jpmcb/oh-my-zsh-extended.git ~/.ohmyzsh/custom/
```

Now, open a new termianl session, and Oh-My-Zsh will automatically load/source
the scripts, configs, and customizations found under the `custom` directory!
Enjoy and good luck!
