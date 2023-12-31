SendGrid Integration Reports
============================

With this module enabled you will have reports and insights into your SendGrid
account. The dashboard displays the general stats created by SendGrid.

This module creates a custom cache bin for the statistics and reports. The data
could be large depending on the activity of your site; therefore, we store this
in a cache to make the reports pages display without having to perform service
calls on each load.

A custom cache bin was created in order to allow you to use other caching
backends for your Backdrop website. By default, the data gets stored into the
main database for the website. But you could store the information in other
caching backends such as Memcache, MongoDB, or Redis.

This module requires the main SendGrid Integration module to be loaded.

