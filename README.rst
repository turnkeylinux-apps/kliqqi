Pligg - Social publishing CMS
=============================

`Pligg`_ is an open source CMS (Content Management System) that provides
social publishing software that encourages visitors to register on your
website so that they can submit content and connect with other users.
Create websites where stories are created and voted on by members, not
website editors.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Pligg configurations:
   
   - Installed from upstream source code to /var/www/pligg

- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL, Adminer: username **root**
-  Pligg: username **admin**


.. _Pligg: http://pligg.com/
.. _TurnKey Core: http://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org/
