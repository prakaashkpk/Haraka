mail\_from.blocklist
===================

This plugin blocks MAIL\_FROM addresses in a list.

NOTE: If all you need is to deny mail based on the exact address, this plugin
will work just fine. If you want to customize the deny message, add blocks
based on a regex, or add whitelists, please use the mail\_from.access plugin.

Configuration
-------------

* mail\_from.blocklist
  
  Contains a list of email addresses to block.
