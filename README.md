# Islandora Slick Carousel Example

This module creates Slick Carousel blocks for a Repository Item's members and peers.

## Installation

Both the Slick and Blazy Drupal modules used require additional javascript libraries 
that can't be installed with composer.

Assuming a standard install using claw-playbook, vagrant ssh into the machine and run the following commands:
```
cd /var/www/html/drupal/web
composer require drupal/blazy drupal/slick_extras drupal/slick_views
sudo git clone https://github.com/kenwheeler/slick.git libraries/slick
sudo git clone https://github.com/dinbror/blazy.git libraries/blazy
```
## Use

To use the slick carousel blocks modify the Collection and Content contexts to use the
Slick Member Of blocks instead of the existing Member Of blocks.

## Updating

Several of the Slick and Blazy settings can be updated by editing the Slick Member Of view.
Additional settings can be updated, including adding additional Slick option sets, by
enabling the Slick UI and Blazy UI modules.
