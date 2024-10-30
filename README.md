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

Commits before d718bef3c0c256d66466f496f11f7e1b5c88bd03 did not contain
certdata.txt. If you want the corresponding source for the ca bundle in an old
commit, then please refer to this table:

<details>
<summary>Click here to show or hide the table.</summary>

| Commit                                   | URL for corresponding source                                                                                                                  |
|------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| 7d228da8f3f05c0123d72f13db9de10ea6dee621 | N/A                                                                                                                                           |
| 5a391619cb2490d3304a91c71e2fa338a0557f81 | https://hg.mozilla.org/releases/mozilla-release/raw-file/66b7259580f45c2599eefae69f40dae55ef17e0a/security/nss/lib/ckfw/builtins/certdata.txt |
| f1d870d5da0d48d4cc31174f501b5190f01e6b8c | Same as the previous commit                                                                                                                   |
| 2b45e5d67ded140f1be0bcc649fa88d3c231883e | Same as the previous commit                                                                                                                   |
| 0a9e02c6fc9604cdf3807472a76b7af1e4260171 | Same as the previous commit                                                                                                                   |
| f68eb7b9674cfafd78a581e85abd3438b70e5804 | https://hg.mozilla.org/releases/mozilla-release/raw-file/e6aee77687d39f32cf2e76974fda5dd7d3353494/security/nss/lib/ckfw/builtins/certdata.txt |
| e9175fec5d0c4d42de24ed6d84a06d504d5e5a09 | https://hg.mozilla.org/releases/mozilla-release/raw-file/cd52a7f8954809fd893196dc857f81b0cb61717c/security/nss/lib/ckfw/builtins/certdata.txt |
| b072e4efd42b8602855bba127586c42fcf4f73d5 | https://hg.mozilla.org/releases/mozilla-release/raw-file/fbecd3b75a32805785ab6c04071ba22ff9e12f15/security/nss/lib/ckfw/builtins/certdata.txt |
| d82fc46afaf6478aaa22989bcc2202ba7b72ad71 | https://hg.mozilla.org/releases/mozilla-release/raw-file/784a4c059370ea7eb6bd3e5597b2cf60b01fff61/security/nss/lib/ckfw/builtins/certdata.txt |
| bff056d04b9e2c92ea8c83b2e39be9c8d0501039 | https://hg.mozilla.org/releases/mozilla-release/raw-file/1864de1dd58496710df537ebf6a3cb7655be25cb/security/nss/lib/ckfw/builtins/certdata.txt |
| 86347ecbdc2277f365d02f0d208b822a214e012d | https://hg.mozilla.org/releases/mozilla-release/raw-file/4c4aa555dbb768be28989e14577d408cc7963f36/security/nss/lib/ckfw/builtins/certdata.txt |
| 751ec767788ef26616dcc40c300c306a86076099 | Same as the previous commit                                                                                                                   |
| 57d1a1632d82e365e67ebfd65550dda12812d478 | Same as the previous commit                                                                                                                   |
| dfcc02c918b7bf40ed3a7f27a634c74ef4e80829 | https://hg.mozilla.org/releases/mozilla-release/raw-file/02e787b058edbc15355a89c61564661d34043d1c/security/nss/lib/ckfw/builtins/certdata.txt |
| a87bf7b88d735dc6fcbcdc116e4044d964cf389c | Same as the previous commit                                                                                                                   |
| 7ba8a667420bd2e3ba32c34ae255deae6493fba7 | https://hg.mozilla.org/releases/mozilla-release/raw-file/236993bf136ebdcf87c2569e424a4c230b66123e/security/nss/lib/ckfw/builtins/certdata.txt |
| db7eb8a3e0c7b7fa39a6a78d5f8610ac26ccfadf | Same as the previous commit                                                                                                                   |
| a9de2411cd1aec4eee49fc7905f09f923573cda8 | https://hg.mozilla.org/releases/mozilla-release/raw-file/725796b69ce57e5654d21bdd9bee131b57d141dd/security/nss/lib/ckfw/builtins/certdata.txt |
| 5cd5a2299379e6880134b0caf842aacdab9db727 | https://hg.mozilla.org/releases/mozilla-release/raw-file/4f753ccec3d08822b45bda237110074c6937e99e/security/nss/lib/ckfw/builtins/certdata.txt |
| d9785b19b9030c1a7985b614eb2cac428b346c0d | https://hg.mozilla.org/releases/mozilla-release/raw-file/380093135a3bf54c6971595a0f4f945081484a38/security/nss/lib/ckfw/builtins/certdata.txt |
| ae9e4be79a2be3f8b341ff6f24576bc78b0f9aad | https://hg.mozilla.org/releases/mozilla-release/raw-file/28fadaace7bd2189a6c13db6765bf04048a41789/security/nss/lib/ckfw/builtins/certdata.txt |
| f0185186159dcfee874795a5861535e4ed596b56 | https://hg.mozilla.org/releases/mozilla-release/raw-file/40755aa80f41ee6df8995ae44044caf7a024b128/security/nss/lib/ckfw/builtins/certdata.txt |
| ca9dc7463c9ef5d4d19ed778c255da5f671e655c | https://hg.mozilla.org/releases/mozilla-release/raw-file/54ee1aebd3927ea70f46398feffef7e869aae7e0/security/nss/lib/ckfw/builtins/certdata.txt |
| 2e3c764182fcfc170e9f8a99a6923bd28e674d39 | https://hg.mozilla.org/releases/mozilla-release/raw-file/e9f06fd63988182f9f79f223a295b57acf81cee8/security/nss/lib/ckfw/builtins/certdata.txt |
| acd399daddb0b72964324013f3acde222f3c0625 | https://hg.mozilla.org/releases/mozilla-release/raw-file/ea3b45ed3e04155184f4b85da43dc2328424f2d2/security/nss/lib/ckfw/builtins/certdata.txt |
| fa1e9f3dccfa995b2b9ed7478fe92d308fa634fa | https://hg.mozilla.org/releases/mozilla-release/raw-file/d7f1b0b90dcc2fd7b999cd8e1935ef4f1c6a8357/security/nss/lib/ckfw/builtins/certdata.txt |
| 449f554bb6853af5f6510601671f00ef5d1b93e6 | https://hg.mozilla.org/releases/mozilla-release/raw-file/2c9fa0eb1c2597fe5ee2a9f42a96e96618af51fd/security/nss/lib/ckfw/builtins/certdata.txt |
| 6067692770f1b7625c4039536ccaf23d0a49ee7f | https://hg.mozilla.org/releases/mozilla-release/raw-file/50bba836b642b517fddd49b7f8f9e72ed0e0b677/security/nss/lib/ckfw/builtins/certdata.txt |
| 0afaa1b7f4ac157dcd9240c198dbc10fdba00c02 | https://hg.mozilla.org/releases/mozilla-release/raw-file/1d559668fc4795e6f1d426ecfa8fc86be0e91a82/security/nss/lib/ckfw/builtins/certdata.txt |
| 22eb23ed4198052d1e5405911c6d028be75c817c | https://hg.mozilla.org/releases/mozilla-release/raw-file/e92c4aeac6c046e5f6e3954ffee9fcc9d19045dd/security/nss/lib/ckfw/builtins/certdata.txt |
| b27af886c380c59bbbf81afe7c186483184195a3 | https://hg.mozilla.org/releases/mozilla-release/raw-file/ed839e4a302121a4105806c22023ad3a2cf60a98/security/nss/lib/ckfw/builtins/certdata.txt |
| 2a33f9977cd5aa22fe91dbe8727e198298e53606 | https://hg.mozilla.org/releases/mozilla-release/raw-file/a85986cd3e05efd8afd71ff5ad6409102deddfeb/security/nss/lib/ckfw/builtins/certdata.txt |
| fd0b671eefb2556ca8c2f45a0b4003df18bc6124 | Same as the previous commit                                                                                                                   |
| 6f9394f01a5adc6e11b145d787136cec6c0d4f49 | Same as the previous commit                                                                                                                   |
| ed090aff3f6fd4e03f3e88ada8eae5fa48a262d4 | Same as the previous commit                                                                                                                   |
| 4a20d8c0705c78f588635eaa8a1fa9edf73b8c97 | https://hg.mozilla.org/releases/mozilla-release/raw-file/0f8e8f595cdaa3c640eebbcf5a3c1640597d6fe5/security/nss/lib/ckfw/builtins/certdata.txt |
| 2b15b55ea65cf6a5251fc14d778d5f39b512ba71 | Same as the previous commit                                                                                                                   |
| a0e9c8e2956e1b79ded5f6fe7084884550a44550 | https://hg.mozilla.org/releases/mozilla-release/raw-file/d712f161492e6534aa05dbc7b71f58ee4431d6c4/security/nss/lib/ckfw/builtins/certdata.txt |
| 2554eb9e77bde6e5030217ced250ca21b5bc344b | https://hg.mozilla.org/releases/mozilla-release/raw-file/326adbc7882af5850e30faecaca4a5f2eb3e4ac5/security/nss/lib/ckfw/builtins/certdata.txt |
| 1c78e2ab91957d4847913c4cdd0625d62b58c6a7 | https://hg.mozilla.org/releases/mozilla-release/raw-file/b608bef3805d31d583e719314ce55152a6724cf5/security/nss/lib/ckfw/builtins/certdata.txt |
| 59e7c349caebdbd90e7f9d7f06be066933425a6f | https://hg.mozilla.org/releases/mozilla-release/raw-file/93720442b571341fd67dd76b50dd4ae73226e10a/security/nss/lib/ckfw/builtins/certdata.txt |
| 8b263a18fca98ea371e54227837321c5cdaa1ba7 | https://hg.mozilla.org/releases/mozilla-release/raw-file/db0157931387a232eba6ed90247b0cb89671cbed/security/nss/lib/ckfw/builtins/certdata.txt |
| 0f9691f953dd3dd7b4d88a8f9069b9af71f6c668 | Same as the previous commit                                                                                                                   |
| edd798d35abc8cc32519b08b3d8485780bb0fd20 | https://hg.mozilla.org/releases/mozilla-release/raw-file/ed80dc53fca3452420400edd349b01600bc9a475/security/nss/lib/ckfw/builtins/certdata.txt |
| 74bfa39fdcacc2072ef9ab9bab6776002ea322a4 | https://hg.mozilla.org/releases/mozilla-release/raw-file/4d6bd444b886615f85e86f29598551048d2690a7/security/nss/lib/ckfw/builtins/certdata.txt |
| 39c6ac0550873e5c9214f265a1d0d9876c64c669 | https://hg.mozilla.org/releases/mozilla-release/raw-file/879ef40783f7255764ac9f401757c726a6c387c6/security/nss/lib/ckfw/builtins/certdata.txt |
| 7bbb8cfe6b9d5e1711584c3adb7fdc50c7471b50 | https://hg.mozilla.org/releases/mozilla-release/raw-file/c8f0f5eb3ec78cab045d24ba2ed359ebbe09f56e/security/nss/lib/ckfw/builtins/certdata.txt |
| 7f33e7eb8472dbcf31fdcf50cd216c89a282825d | https://hg.mozilla.org/releases/mozilla-release/raw-file/f478b87846055e0e762d5493d26efab821091ce9/security/nss/lib/ckfw/builtins/certdata.txt |
| b2f7415648411b6fd7c298c6c92d6552f0165f60 | https://hg.mozilla.org/releases/mozilla-release/raw-file/92f6d58167e0e0afd56305c9975b89134dd0424d/security/nss/lib/ckfw/builtins/certdata.txt |
| 8bcd1092d29849d9fe0a3261ab3bb875eb410694 | https://hg.mozilla.org/releases/mozilla-release/raw-file/7d8e7a75db1e1489fa6b112be71b458ea028453b/security/nss/lib/ckfw/builtins/certdata.txt |
| 3aaca635bad074a0ce5c15fa8aa0dff47f5c639a | https://hg.mozilla.org/releases/mozilla-release/raw-file/238ea457a20e22e269b95456d4dc47abf8bb8263/security/nss/lib/ckfw/builtins/certdata.txt |
| 68844bbac67c0a2513165f4024c238cbb0b7ec64 | https://hg.mozilla.org/releases/mozilla-release/raw-file/f741b9b7161bdda9aa4dfc1bef67afcfbfa2c956/security/nss/lib/ckfw/builtins/certdata.txt |
| bef37a977ccb45fb4c1b213b79dd6ba438077561 | https://hg.mozilla.org/releases/mozilla-release/raw-file/bb22fcd79ecfaccff57cf9814e6b62a758db6f43/security/nss/lib/ckfw/builtins/certdata.txt |
| c5a419971b1bec220368c619aaafd0b818aa119f | https://hg.mozilla.org/releases/mozilla-release/raw-file/163c38ee7a7a13a344e7fe15b75d86e6c5212ae0/security/nss/lib/ckfw/builtins/certdata.txt |
| ae77ab685577d4f455d52cda7877bafe5d06a1d0 | https://hg.mozilla.org/releases/mozilla-release/raw-file/ce4c4f72a97d4ef2a387d39bfe964c8a13f05d2c/security/nss/lib/ckfw/builtins/certdata.txt |
| f3d27c23c986e495dcd98eed8f1e72a4919300ec | https://hg.mozilla.org/releases/mozilla-release/raw-file/b8ea2342548b8571e58f9176d9555ccdb5ec199f/security/nss/lib/ckfw/builtins/certdata.txt |

</details>

license
=======

The converted file is licensed under the same license as the Mozilla source
file: MPL 2.0

conversion
==========
We use mk-ca-bundle.pl from curl:

  https://github.com/curl/curl/blob/master/scripts/mk-ca-bundle.pl
