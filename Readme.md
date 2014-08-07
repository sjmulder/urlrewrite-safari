URL Rewrite for Safari
======================

An extension that lets you redirect Safari for specific URLs.


Usage
-----

To install, [download here](http://60ef-sjmulder-nl.s3.amazonaws.com/files/URL%20Rewrite%201.1.safariextz).

To configure:

 1. Go to the Safari menu, Preferences, Extensions, then select URL Rewrite.
 2. In Source URL, enter the URL that should be rewritten, e.g. `http://jira.example.com/`
 3. In Destination URL, enter the URL that should replace the Source URL, e.g. `http://example.myvpn.com/jira/`
 4. Now, any link that begins with Source URL will have that replaced with Destination URL. In the example above, `http://jira.example.com/PROJ-123` would be rewritten to `http://example.myvpn.com/jira/PROJ-123`

Notes:

 * There is room for up to 5 replacements in the settings.
 * Make sure to include the protocol, like `http://`.
 * There is no wildcard support, just a prefix match.


Licence
-------

I, the copyright holder of this work, hereby release it into the public domain. This applies worldwide.

In case this is not legally possible: I grant anyone the right to use this work for any purpose, without any conditions, unless such conditions are required by law.


Author
------

By Sijmen Mulder (ik@sjmulder.nl).
