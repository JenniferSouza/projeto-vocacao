# Simple Voting Project in Drupal10
*by Jennifer Souza*

## Mandatory criteria for installing Lando, Docker, and Composer for the configuration.

Step 1: start your Drupal 10 environment by typing "lando start" on your terminal.

```bash
lando start
```

### Install Module Restui 

```bash
lando composer require drupal/restui
lando drush en rest restui
```

### Name View: \web\core\modules\views\views.views.voting_results.yml

### Module Name simple_voting_module
```bash
lando drush en simple_voting_module
 ´´´´

URLS
√ APPSERVER NGINX URLS
√ http://my-drupal10.lndo.site/ [200]
√ https://my-drupal10.lndo.site/ [200]

To access the interface, use ```bash drush uli ``` or:
```bash
User:admin
Password:admin
```