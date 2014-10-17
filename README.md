# Drupal Travis-CI Demonstration

[![Build Status](https://travis-ci.org/geerlingguy/drupal-travis-ci.svg)](https://travis-ci.org/geerlingguy/drupal-travis-ci)

This project will demonstrate basic Drupal/Travis-CI integration on GitHub.

Over time, the following will be illustrated through the included `.travis.yml` file:

  - Drupal and drush installation via Ansible and/or git.
  - Drupal core test run via drush (both simpletest and PHPUnit).
  - Contributed module test run via drush.
  - Behat test run.
  - Static code analysis (using tools like PHPMD, CodeSniffer, etc.) and simple reporting.

Please watch this space for updates!

## Other Examples

  - [DrupalCI by Midwestern Mac](http://drupalci.midwesternmac.com/) - Powered by Jenkins and SonarQube
    This site (which is powered by the [drupalci-sonar-jenkins](https://github.com/geerlingguy/drupalci-sonar-jenkins) project) combines Jenkins with SonarQube to allow for deep PHP code analysis for Drupal core versions (and, in the future, other projects).
