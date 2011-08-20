#  stripped/optimized magento default theme (http://www.magentocommerce.com/)

This repository contains adjustments for a vanilla Magento CE 1.6.0 install.
Since the default theme of Magento is a fallback from all other themes, it makes sense to optimize all frontend files for best speed performance.

## Changelog:

### v.0.1 : August 20th, 2011
* optimized all PNGs with http://www.smushit.com/ysmush.it/
* moving css images to Data-URIs with http://duris.ru/lang/en/
* deleting all superfluous images
* changing default head inserts to optimized styles
* added additional rules to .htaccess (mainly borrowed from http://html5boilerplate.com/)
* keep in mind, that mod_pagespeed is enabled by default in .htaccess!