Weight
======
This module provides a weight field that can be added to any fieldable entity.
The weight field can be used to provide customized sorting. 

This module also provides a Views field handler that allows users with the appropriate permission 
to rearrange the rows of a Views table (drag and drop) and save the new order. 

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.
- Add the weight field to an entity or content type.

Configuration options
-------------
  - Range: The range is set when adding a weight field to an entity. It defines 
    that fields available weight range. For example, a range of 20 will allow 
    you to select a weight between -20 and 20.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/hms_field/issues.

Current Maintainers
-------------------

- [argiepiano](https://github.com/argiepiano).

Credits
-------

- Ported to Backdrop CMS by [argiepiano](https://github.com/argiepiano).
- Original Drupal 7 module mantainers: [ziomizar](https://www.drupal.org/u/ziomizar), [Shreya Shetty](https://www.drupal.org/u/shreya-shetty), [kevinquillen](https://www.drupal.org/u/kevinquillen), [davisben](https://www.drupal.org/u/davisben), [deviantintegral](https://www.drupal.org/u/deviantintegral)

License
-------

This project is GPL v2 software. 
See the LICENSE.txt file in this directory for complete text.
