# Drupal Status Report Error Fixes
Steps on how to fix Drupal status report errors.

### SimplePie
*Error:* `SimplePie library is required for Feeds SimplePie Parser. Download the compiled version of the library from SimplePie download page.`

1. Direct download link: http://simplepie.org/downloads/simplepie_1.3.1.compiled.php
2. Save file as `simplepie.compiled.php`
3. Create a new folder in /sites/all/libraries/ called `simplepie` (with http://drupal.org/project/libraries module installed), and uploaded file. You should have the path : `/sites/all/libraries/simplepie/simplepie.compiled.php`
4. Clear caches.
