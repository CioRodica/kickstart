# README #

***1. Install dependencies:***
* composer require drupal/paragraphs
* composer require drupal/components
* composer require drupal/crop

***2. Enable modules:***
* drush en paragraphs -y
* drush en components -y
* drush en crop -y
* drush en responsive_image -y
* drush en kickstart -y
* drush config-set system.theme default kickstart -y

***3. Install npm plugins and lunch task in .npm/ folder:***
* npm install
* npm run [dev/ build]

***3. Lunch test task in .npm/ folder:***
* phantomjs --webdriver=4444 (optional, for local testing)
* npm run test
