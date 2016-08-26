Deprecated!
===========

Since the original curl site hosts this data over HTTPS now, this repository
has no purpose and is going away soon. Go to
https://curl.haxx.se/docs/caextract.html instead!

ca-bundle
=========

The Mozilla CA bundle extracted and converted to PEM at regular intervals. See
the PEM file itself for the actual date of the latest Mozilla source change
that is included in converted file.

license
=======

The converted file is licensed under the same license as the Mozilla source
file: MPL 2.0

conversion
==========
We use mk-ca-bundle.pl from curl:

  https://github.com/curl/curl/blob/master/lib/mk-ca-bundle.pl
