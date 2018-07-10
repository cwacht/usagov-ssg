# USAGOV SSG


### PREPARE:
* `brew install php`
* `brew install composer`
* `git clone https://github.com/dnarkiewicz/usagov-ssg.git`
* `cd usagov-ssg`
* `composer install`
* `cp config/USA.gov.config-default.php config/USA.gov.config.php`
* edit config/USA.gov.config.php to update parameters for TemplateSync source

### RUN:
* `./ssg`
* options:
  * `./ssg --freshdata`
  * `./ssg --freshtemplates`
  * `./ssg --freshdata --freshtemplates`

### VALIDATE:
* cd sites/usa.gov
* php -S localhost:8000

