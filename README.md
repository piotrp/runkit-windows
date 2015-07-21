Runkit binaries for Windows
===========================
This repository contains binaries of runkit PHP module maintained by Dmitry Zenovich.

Built according to instructions at [zenovich/runkit#22](https://github.com/zenovich/runkit/issues/22). After php_runkit.dll that I found earlier failed to work correctly I decided to build from master. File names contain runkit version or date of last commit on master that made it into my build.

runkit 1.0.3 built from sources at https://github.com/downloads/zenovich/runkit/runkit-1.0.3.tgz.<br />
runkit 1.0.4-5e179e978a built from sources at [zenovich/runkit@5e179e978a](https://github.com/zenovich/runkit/tree/5e179e978af79444d3c877d5681ea91d15134a01) (master branch after the last commit at 2013-04-04).
runkit 1.0.4-d6b0f05e6e built from sources at [zenovich/runkit@d6b0f05e6e](https://github.com/zenovich/runkit/tree/d6b0f05e6e6453d794b8f6f30a37187523104bc8) (master branch after the last commit at 2015-01-18) with merged pull requests:
* [#73 Fixed compilation with PHP 5.6](https://github.com/zenovich/runkit/pull/73)
* [#77 fix segfault when copied function contains finally](https://github.com/zenovich/runkit/pull/77)
* [#79 reset/unset (un)serialize handlers when changing methods](https://github.com/zenovich/runkit/pull/79)

Downloads:

* [php_runkit-1.0.3-5.3-vc9.dll](php_runkit-1.0.3-5.3-vc9.dll) - PHP 5.3.27 headers, VC9, TS
* [php_runkit-1.0.3-5.3-vc9-nts.dll](php_runkit-1.0.3-5.3-vc9-nts.dll) - PHP 5.3.27 headers, VC9, NTS
* [php_runkit-1.0.4-5e179e978a-5.3-vc9.dll](php_runkit-1.0.4-5e179e978a-5.3-vc9.dll) - PHP 5.3.27 headers, VC9, TS
* [php_runkit-1.0.4-5e179e978a-5.3-vc9-nts.dll](php_runkit-1.0.4-5e179e978a-5.3-vc9-nts.dll) - PHP 5.3.27 headers, VC9, NTS
* [php_runkit-1.0.4-5e179e978a-5.4-vc9.dll](php_runkit-1.0.4-5e179e978a-5.4-vc9.dll) - PHP 5.4.21 headers, VC9, TS
* [php_runkit-1.0.4-5e179e978a-5.4-vc9-nts.dll](php_runkit-1.0.4-5e179e978a-5.4-vc9-nts.dll) - PHP 5.4.21 headers, VC9, NTS
* [php_runkit-1.0.4-5e179e978a-5.5-vc11.dll](php_runkit-1.0.4-5e179e978a-5.5-vc11.dll) - PHP 5.5 headers, VC11, TS
* [php_runkit-1.0.4-5e179e978a-5.5-vc11-nts.dll](php_runkit-1.0.4-5e179e978a-5.5-vc11-nts.dll) - PHP 5.5 headers, VC11, NTS
* [php_runkit-1.0.4-d6b0f05e6e-5.6-vc11.dll](php_runkit-1.0.4-d6b0f05e6e-5.6-vc11.dll) - PHP 5.6 headers, VC11, TS
* [php_runkit-1.0.4-d6b0f05e6e-5.6-vc11-nts.dll](php_runkit-1.0.4-d6b0f05e6e-5.6-vc11-nts.dll) - PHP 5.6 headers, VC11, NTS
