Backup only
===========

This repository serves only as a backup to https://curl.se/docs/caextract.html.
That's the primary resource and site.

ca-bundle.crt
=============

The Mozilla CA bundle extracted and converted to PEM at regular intervals. See
the PEM file itself for the actual date of the latest Mozilla source change
that is included in converted file.

certdata.txt
============

This is the corresponding source file used as input to generate the ca bundle
output. Copied from the Mozilla source repository at the time the conversion
is done.

license
=======

The converted file is licensed under the same license as the Mozilla source
file: MPL 2.0

conversion
==========
We use mk-ca-bundle.pl from curl:

  https://github.com/curl/curl/blob/master/lib/mk-ca-bundle.pl
