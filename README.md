# symfony.plugin.zsh

Oh My ZSH plugin for [Symfony 2/3/4](https://symfony.com/) with usefull commands and autocompletion.

## Installation

Go to plugin directory
```sh
cd ~/.oh-my-zsh/custom/plugins
```

Clone via SSH or HTTPS
```sh
# SSH
git clone git@github.com:Ostendorf/symfony.plugin.zsh.git ostendorf-symfony

# HTTPS
git clone https://github.com/Ostendorf/symfony.plugin.zsh.git ostendorf-symfony
```

Open `~/.zshrc`
```sh
zshconfig
```

Add this at end of file:
```sh
source ~/.oh-my-zsh/custom/plugins/ostendorf-symfony/symfony.plugin.zsh
```

## Usage

This plugin provides some useful commands and shortcuts:

- `sf` is used for running Symfony console commands. You can run this command inside project's folders because it searches the console script upward from a current dir;
- `sfprod` and `sfdev` are shortcuts for `sf --env=prod` and `sf --env=dev`;
- `sfsh` launches Symfony's shell;
- `sfstart` starts PHP built-in web server in the background;
- `sfrun` runs PHP built-in web server;
- `sfstop` stops PHP's built-in web server;
- `sfservice` shows a service definition. It has an autocompletion for service ids;
- `sfroute` shows a route definition. It has autocompletion for routes names;
- `sfconfig` shows a container extensions configuration. It has autocompletion for extensions names;
- `sfhelp` shows a help message for a specified command;
- `symfony-get-installer` downloads a Symfony installer from the symfony.com;
- `sfnew` is just a shortcut for `symfony new`.

Also this plugin provides a commands and some options autocompletion for both Symfony's console and installer.

## Ascii movie

[![asciicast](https://asciinema.org/a/03shcf05p1wz0ppg2dambztig.png)](https://asciinema.org/a/03shcf05p1wz0ppg2dambztig)

## License

Released under the [MIT license](LICENSE.txt)
