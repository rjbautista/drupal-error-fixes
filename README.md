# Drupal Status Report Error Fixes
Steps on how to fix Drupal status report errors.

## SimplePie
*Error:* `SimplePie library is required for Feeds SimplePie Parser. Download the compiled version of the library from SimplePie download page.`

#. Direct download link: http://simplepie.org/downloads/simplepie_1.3.1.compiled.php
#. Save file as `simplepie.compiled.php`
#. Create a new folder in /sites/all/libraries/ called `simplepie` (with (libraries|http://drupal.org/project/libraries) module installed), and uploaded file. You should have the path : `/sites/all/libraries/simplepie/simplepie.compiled.php`
#. Clear caches.
