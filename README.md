LibreDTE plugin for OpenCart 3
===============================

This plugin allows you to integrate OpenCart 3 with the LibreDTE web application.

The plugin has been tested with Opencart 3.0.2.0

If you want a version compatible with OpenCart 2 check [here] (https://github.com/LibreDTE/libredte-plugin-opencart/releases/tag/v2.0.0-alpha).

Implemented functionalities:

- API to obtain item data from the LibreDTE issuance page.
- Direct links to the LibreDTE application using pre-authentication.
- Generation of invoice or ticket from the OpenCart purchase order page.
- Access from the purchase order page to the DTE page in LibreDTE.
- Sending by email when issuing the document in OpenCart.

License
--------

This code is released under the free software license [AGPL] (http://www.gnu.org/licenses/agpl-3.0.en.html).
For details on how you can use, modify and / or distribute this plugin check the license terms.
It also has details, in Spanish, about this in the [terms and conditions] (https://wiki.libredte.cl/doku.php/terminos) of LibreDTE.

API
---

### URL items

To configure the reading of codes from the LibreDTE platform, for example, using the product SKU, the URL must be configured:

    http://www.mitienda.cl/index.php?route=libredte/product&codigo=

For example:

    https://altronics.cl/index.php?route=libredte/product&codigo=

The column to use, in this case the example is indicated SKU, it is assigned in the plugin configuration in OpenCart.

Contribute to the project
----------------------

If you want to contribute to the project, especially solving any of the
[* open * issues] (https://github.com/LibreDTE/libredte-plugin-opencart/issues) you must:

1. Fork the project on [GitHub] (https://github.com/LibreDTE/libredte-plugin-opencart)
2. Create a * branch * for the changes: git checkout -b branch-name
3. Modify code: git commit -am 'Add ...'
4. Publish changes: git push origin branch-name
5. Create a * pull request * to join the new * branch * with this official version.

** IMPORTANT **: before making a * pull request * verify that the code
comply with [PSR-1] standards (http://www.php-fig.org/psr/psr-1),
[PSR-2] (http://www.php-fig.org/psr/psr-2) and
[PSR-4] (http://www.php-fig.org/psr/psr-4). 

