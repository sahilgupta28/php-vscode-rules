# Vscode PHP CS Fixer by junstyle ([Phpcs](https://github.com/junstyle/vscode-php-cs-fixer))

## Install PHP CS-Fixer (ubuntu)
`wget https://cs.symfony.com/download/php-cs-fixer-v2.phar -O php-cs-fixer`
`sudo chmod a+x php-cs-fixer`
`sudo mv php-cs-fixer /usr/local/bin/php-cs-fixer`
For more details [click here](https://github.com/FriendsOfPHP/PHP-CS-Fixer)

## Install PHP CS Fixer by junstyle extension in Vscode
1. Press <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>x</kbd>
2. Search  `PHP CS Fixer  by junstyle`
3. Click on install

## Change settings as per coding guidelines
1. `cd /.vscode`
2. `mkdir custom-settings`
3. Download php_cs file from [here](#).
4. `cp path/to/php_cs path/to/.vscode/custom-settings/.php_cs`
5. Run command `pwd` and copy path.
6. Open Your IDE and go to extension settings > Configure Extension Settings
7. Paste copied path to PHP-cs-fixer: Config
