Anax-oophp
=========

Anax-oophp builds upon Anax-base.

Anax-oophp is used as course material in the university course http://dbwebb.se/oophp.

Built by Mikael Roos, me@mikaelroos.se.



License 
------------------

This software is free software and carries a MIT license.



Use of external libraries
-----------------------------------

The following external modules are included and subject to its own license.



### Modernizr
* Website: http://modernizr.com/
* Version: 2.6.2
* License: MIT license 
* Path: included in `webroot/js/modernizr.js`



History
-----------------------------------


v1.0.x (latest)

* Cloned Anax-bas to be the base for Anax-oophp.
* Changed how jQuery is included, now using `jquery` and `jquery_src`.
* Added dynamic menu / navbar in `webroot/config.php`, `theme/index.tpl.php` and `theme/functions.php`.
* Changed order of including bootstrap.php and starting session in `config.php`. Compatible with anax-base v1.0.2.
* Changed default directory for displaying source code to '..' in `webroot/source.php`.
* Naming of session in `webroot/config.php` allows only alphanumeric characters.


v1.0.0 (2013-06-28)

* First release after initial article on Anax.



------------------
 .  
..:

Copyright (c) 2013 Mikael Roos



