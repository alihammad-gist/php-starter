# A PHP Starter Project

A starting point with a lot of repetitive tasks already configured

1. PHP Codesniffer with Strict PSR-12 Standard
   [opsway/psr12-strict-modern-standard](https://github.com/opsway/psr12-strict-modern-standart)
2. Psalm
3. PHPUnit

## Dependencies checking

To check undeclared implicit dependency,
[maglnet/composer-require-checker](https://github.com/maglnet/ComposerRequireChecker)
package can be used. It should be installed as global composer
package.
`composer global require maglnet/composer-require-checker`. Run
`composer run composer-require-check` to analyze the `src/` folder.

Similarly unused packages can be identified by
[composer-unused/composer-unused](https://github.com/composer-unused/composer-unused)
package. Again this should be installed locally, the package author
recommends downloading a `phar` release from github's release page.
