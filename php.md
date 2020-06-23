# PHP

The code must follow PHP FIG standard.

- [PHP-FIG](https://www.php-fig.org/psr/)

Use PHP linter tool on your editor. Make it automatically lint upon file saved.

- [PHP-CS-Fixer] (https://github.com/FriendsOfPHP/PHP-CS-Fixer)

```
{
	"cmd": ["$HOME/.composer/vendor/bin/php-cs-fixer", "fix", "--using-cache=no", "$file"],
	"selector": "source.php"
}
```