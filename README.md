This submodule requires the Slick and Blazy javascript libraries to be installed.

Assuming a standard install using claw-playbook, vagrant ssh into the machine and run the following commands:
```
cd /var/www/html/drupal/web
composer require drupal/blazy drupal/slick_extras drupal/slick_views
git clone https://github.com/kenwheeler/slick.git libraries/slick
git clone https://github.com/dinbror/blazy.git libraries/blazy
```
