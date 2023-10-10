SendGrid Integration Module
---------------------------

This project is not affiliated with SendGrid, Inc. If you want more info about
SendGrid services, contact [SendGrid](https://sendgrid.com).

This module uses a wrapper library for the SendGrid API. At the moment the
wrapper library is for V2 of the API. V3 upgrade is being developed.

Installation
------------

1. Navigate to Functionality Tab and enable SendGrid Integration in the Mail category.

2. Configure your SendGrid API-Key in admin/config/services/sendgrid

3. Confirm that the mail system is setup to use SendGrid for how you wish to run
   you website. If you want it all to run through SendGrid then you set the
   System-wide default MailSystemInterface class to "SendGridMailSystem".


Documentation
------------

Additional documentation is located in [the Wiki](https://github.com/backdrop-contrib/sendgrid_integration/wiki/Documentation).

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/sendgrid_integration/issues).

Current Maintainers
-------------------

- [Michael R. Bagnall](https://github.com/ElusiveMind).

Credits
-------

- Ported to Backdrop CMS by [Michael R. Bagnall](https://github.com/ElusiveMind).
- Original Maintainers on Drupal.org
   - [taz77 - Brady](https://github.com/taz77)
   - [Henri Hirvonen](https://github.com/exlin)
   - [wkfijenkins](https://github.com/wkfijenkins)
   - [Hailong](https://github.com/Hailong)
   - [Dave Hansen-Lange](https://github.com/dalin-)

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
