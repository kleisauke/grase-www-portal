# Grase Hotspot

The GRASE Hotspot is a project that glues individual components together easily, and provides a nice simple interface to administer the hotspot. With a lot of time and effort, most people can follow the tutorials on the internet and setup up MySQL, FreeRadius, CoovaChilli, Squid and any other optional components, and setup a Captive Portal Hotspot. But as soon as one component changes, for example FreeRadius changed how it’s config files are handled, the whole system breaks and the tutorial doesn’t help.

The GRASE Hotspot takes all the hard work out of keeping the individual components glued together, and provides a nice simple interface to manage the Hotspot and it’s users. As components change, the project is updated so the glue stays together.

## Installation

1. Run `composer update` inside the root directory.
2. Create a user with administrator privileges `php app/console fos:user:create admin admin@example.com hotspotadmin --super-admin`
3. Log into the administrator panel (located at 'web/admin') with the username `admin` and the password `hotspotadmin`.
4. Enjoy!

### Info

This branch is currently in development. It is not recommended to install this branch in production systems!