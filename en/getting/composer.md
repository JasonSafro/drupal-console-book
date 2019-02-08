# Install Drupal Console Using Composer

Change directory to Drupal site:
```
cd /path/to/drupal8.dev
```

Execute composer require command: 
```
composer require drupal/console:~1.0 \
--prefer-dist \
--optimize-autoloader
```

## Download using DrupalComposer project template
```
composer create-project \
drupal-composer/drupal-project:8.x-dev \
drupal8.dev \
--prefer-dist \
--no-progress \
--no-interaction
```

## Update DrupalConsole
```
composer update drupal/console --with-dependencies
```

## Windows Users
Windows users may have to remove the backslashes at the end of each line in the commands above. Better windows documentation is available at: https://docs.drupalconsole.com/en/getting/windows.html

