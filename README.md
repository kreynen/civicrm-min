civicrm-min
===========

This is mirror of the official civicrm-4.1.2-l10n release without libraries redundant to Drupal 7.  

The goal is a version of CiviCRM that compressed is < 10MB.  This will allow it to be packaged
as part of distributions from Drupal.org. The 10MB limit is part of the Drupal's Whitelist Criteria

http://drupal.org/node/1475972#whitelist-criteria

This version of CiviCRM removes:
- packages/jquery - 2.2MB (uncompressed)
- packages/ckeditor - 4.2MB (uncompressed)
- packages/tinymce - 2.2MB (uncompressed)

These files are all found with the core Drupal project or can be added to a package as seperate 
external libraries.

See http://drupal.org/project/cm_starterkit_moderate for an example of a packaged distribution
that includes civicrm-min