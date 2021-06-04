## 3.1.0 (2020-06-22)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/3.1.0)

*  Support global 6.x Laravel components *(Joaquín Marcher)*
*  Update valet.php *(Joaquín Marcher)*
*  Prevent FPM to die when a ton of requests are made per second *(Joaquin Marcher)*
*  Bump version *(Joaquin Marcher)*
*  FIX: Update VALET_STATIC_PREFIX when changing the port *(Joaquin Marcher)*
*  Bump version *(Joaquin Marcher)*
*  Update ngrok to 2.3.35 *(Joaquin Marcher)*
*  Add small optimisations *(Joaquin Marcher)*
*  Reformat code *(Joaquin Marcher)*
*  Add `use` command to sudo *(Joaquin Marcher)*
*  Edit PHP-FPM config for Arch. *(Joaquin Marcher)*
*  Bump version *(Joaquin Marcher)*
*  Remove static from command closures *(Nenad Živanović)*
*  Option used as a flag shouldn't have default value *(Nenad Živanović)*
*  composer dependencies update *(Filipe Craveiro)*
*  Symfony's 4.x Process component has deprecated passing a command string to the constructor, but older versions (which Valet's Composer constraints allow) don't have the fromShellCommandLine method. For more information, see: https://github.com/laravel/valet/pull/761 *(Filipe Craveiro)*
*  Revert "Edit PHP-FPM config for Arch." *(Joaquin Marcher)*
*  Create bug_report.md *(Joaquín Marcher)*
*  rtrim() slashes for paths *(Joaquin Marcher)*
*  Bump version *(Joaquin Marcher)*
*  Edit php-fpm systemd config *(Joaquin Marcher)*
*  Bump version *(Joaquin Marcher)*
*  add dropIn override for systemd *(Muhammet Sait)*
*  Added local network feature. *(Pushpak)*
*  Update valet.php *(Joaquín Marcher)*
*  Fix possible function redefinition *(Joaquin Marcher)*
*  Version bump *(Joaquin Marcher)*
*  Fix list of Eopkg installed packages. *(Joaquín Marcher)*
*  Version bump Add compatibility with Laravel 7.0 *(Joaquín Marcher)*
*  add options to query all nameservers *(Ethan Brace)*
*  fix dns error *(Abdallah Samy)*
*  Version Bump *(Joaquín Marcher)*
*  [FEATURE] Added additional php script csp_reporter.php *(Lewis Voncken)*
*  [DOCS] Updated the CHANGELOG.md *(Lewis Voncken)*


## 3.0.0 (2020-02-11)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/3.0.0)

*  [FEATURE] Added z-performance.ini *(Sam)*
*  [FEATURE] - Add ElasticSearch support *(Cas Satter)*
*  [REFACTOR] - Refactor sitePath variable *(Cas Satter)*
*  [DOCS] - Add .github bug report and feature request templates *(Cas Satter)*
*  [FEATURE] - Add default php.ini improvements *(Cas Satter)*
*  [FEATURE] - Add xDebug .ini settings allowing xdebug to run remotely *(Cas Satter)*
*  [FEATURE] - Add max xdebug nesting setting *(Cas Satter)*
*  Update z-performance.ini to *(SamMorssinkhof)*
*  [DOCS] Updated the CHANGELOG.md *(Cas Satter)*
*  [FEATURE] - Add zend_extension xdebug.so to automatically start xdebug, this way you don't nessecarily have to add it to your php.ini *(Cas Satter)*
*  [BUGFIX] - Revert Sam's attempt to fix *(Cas Satter)*
*  Update composer.json *(Hexmage)*


## v2.1.10 (2019-10-11)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.10)

*  Fix from upstream for paths containing a plus symbol (#232) *(Jamie Burchell)*
*  Bump version *(Joaquín Marcher)*


## v2.1.9 (2019-09-26)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.9)

*  Update SECURITY.md *(Joaquin Marcher)*
*  fix static files path issues with some of latest versions (#230) *(Mahmoud AboElnouR)*
*  Bump version *(Joaquín Marcher)*


## v2.1.9-beta (2019-08-20)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.9-beta)

*  Update contributors *(Joaquin Marcher)*


## v2.1.8 (2019-08-05)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.8)

*  fix: ngrok strange hostname error when sharing (#221) *(Hammed Oyedele)*
*  Update valet.php *(Joaquin Marcher)*


## v2.1.7 (2019-07-31)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.7)

*  Update valet.php *(Joaquin Marcher)*


## v2.1.6 (2019-07-24)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.6)

*  Add support for Solus Package Manager - eopkg (#127) *(Iván Lo Giudice)*


## v2.1.5 (2019-06-26)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.5)

*  Disable old service and enable new service (#217) *(indykoning)*
*  Bump version *(Joaquin Marcher)*


## v2.1.4 (2019-06-26)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.4)

*  Implemented version switcher as `valet use`. *(Indy Koning)*


## v2.1.3 (2019-06-19)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.3)

*  Create SECURITY.md *(Joaquin Marcher)*
*  Add the php-fpm path for openSUSE. *(Dan)*


## v2.1.2 (2019-05-27)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.2)

*  Bring all drivers current *(Bryan Heath)*
*  Enforcing php >= 7.0 (#213) *(Bryan Heath)*
*  Remove Ubuntu 1404 as its EOL (#211) *(Bryan Heath)*
*  Add Ubuntu 18.04 to vagrant tests (#210) *(Bryan Heath)*
*  Update valet.php *(Joaquin Marcher)*


## v2.1.1 (2019-04-23)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.1)

*  Update valet.php *(Joaquin Marcher)*


## v2.1.0 (2019-04-23)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.1.0)

*  Update Magento2ValetDriver.php *(Antonino Bonumore)*
*  Fixed empty $SERVER['document_root'] environment variable in Magento 2 Driver *(keijsers)*
*  Update readme.md *(Carlos Priego)*
*  Update readme.md *(Joaquin Marcher)*
*  Update Travis CI *(Bryan Heath)*
*  Update Ngrok to 2.3.25 *(Bryan Heath)*
*  Wrong dns entry *(Bryan Heath)*


## v2.0.24 (2018-04-08)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.24)

*  Lowercase domain before check (#135) *(Leonardo Nodari)*
*  Remove files param (#150) *(arifkhn46)*
*  Remove Network-Manager dependency *(Carlos Priego)*
*  Bump version *(Carlos Priego)*
*  Remove /run/media from watch path *(Carlos Priego)*


## v2.0.23 (2018-01-15)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.23)

*  Symfony Process ~4.0 (#124) *(Leonardo Nodari)*
*  Add CakePHP 2 driver (#126) *(nnnms)*
*  Use UUID for static asset path instead of "static" (#132) *(Leonardo Nodari)*
*  Bump to version 2.0.23 *(Carlos Priego)*


## v2.0.22 (2017-10-07)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.22)

*  added support for wildcard-ssl for domains (#105) *(Nick)*
*  HTTPS port (#109) *(Leonardo Nodari)*
*  Convert Valet DNS scripts to services *(Carlos Priego)*
*  Create installer for service file *(Carlos Priego)*
*  Change sysvinit options to be compatible with ubuntu 14.04 *(Carlos Priego)*
*  Correct valet-dns race condition with PID *(Carlos Priego)*
*  [skip ci] SysVInit changes for ubuntu 14.04 *(Carlos Priego)*
*  [skip ci] check for valet dependencies *(Carlos Priego)*
*  [skip ci] Fix problems with systemd-resolved *(Carlos Priego)*
*  [skip ci] bump version *(Carlos Priego)*
*  [skip ci] Fix $this->files to $files *(Carlos Priego)*


## v2.0.21 (2017-09-21)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.21)

*  Update gitignore *(Carlos Priego)*
*  Update reference site in README *(Carlos Priego)*
*  sync ValetDrivers with upstream *(Matthias Niess)*
*  Ubuntu 16.04 Vagrant Box *(Leonardo Nodari)*
*  develop command *(Leonardo Nodari)*
*  Refactor Functional tests *(Leonardo Nodari)*
*  Acceptance testing *(Leonardo Nodari)*
*  develop test-all-parallel *(Leonardo Nodari)*
*  Test domains are resolved correctly *(Leonardo Nodari)*
*  Force flag to destroy-all command *(Leonardo Nodari)*
*  Ubuntu 14.04 *(Leonardo Nodari)*
*  Ubuntu 17.04 *(Leonardo Nodari)*
*  Fedora 25 *(Leonardo Nodari)*
*  Fedora 26 *(Leonardo Nodari)*
*  Valet share tests *(Leonardo Nodari)*
*  CentOS 7 *(Leonardo Nodari)*
*  Use full phpunit path because rsync (CentOS) breaks symlinks *(Leonardo Nodari)*
*  [skip ci] Completely refactor the DNSMasq configuration (#100) *(Carlos Priego)*
*  [skip ci] changed the default tld from dev to test (#99) *(Nick)*
*  [skip ci] Fix conflicts with TheNodi PR *(Carlos Priego)*
*  Remove unnecesary docker tests and try support for php 7.2 *(Carlos Priego)*
*  [skip ci] Check for /etc/rc.local existence *(Carlos Priego)*
*  [skip ci] search domain to /etc/resolv.conf *(Carlos Priego)*
*  Change /etc/rc.local read order *(Carlos Priego)*


## v2.0.20 (2017-07-09)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.20)

*  Added PackageKit package manager. *(Jonas Kervin Hansen)*
*  Deferred preference for PackageKit, so it function as fallback. *(Jonas Kervin Hansen)*
*  Fix certificate generation *(Carlos Priego)*
*  Fix nginx.conf for users/groups with whitespace. *(Carlos Priego)*
*  Fix nginx.conf test. *(Carlos Priego)*
*  Improve valet paths output. *(Carlos Priego)*
*  Updated version number in `cli/valet.php` *(Томица Кораћ)*


## v2.0.19 (2017-06-07)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.19)

*  Allow valet share to receive Ngrok parameters *(Carlos Priego)*


## v2.0.18 (2017-05-28)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.18)

*  Since service order changed, we need to add a method to disable services *(Carlos Priego)*
*  Updated tests *(Carlos Priego)*
*  DNSMasq fix for ubuntu 17.04 that does not require reboot *(Carlos Priego)*
*  Improve uninstall scripts *(Carlos Priego)*
*  Trim version string *(Carlos Priego)*
*  Version 2.0.18 *(Carlos Priego)*


## v2.0.17 (2017-05-21)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.17)

*  PSR-2 compliance *(Carlos Priego)*
*  Bump version *(Carlos Priego)*


## v2.0.16 (2017-05-01)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.16)

*  fix for switching domains/conf files *(nickurt)*
*  Only disable services if they exist *(Carlos Priego)*
*  Bump version *(Carlos Priego)*


## v2.0.15 (2017-05-01)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.15)

*  Proof of Concept: correcting dnsmasq *(Carlos Priego)*
*  Proof of Concept: correcting composer triggers *(Carlos Priego)*
*  Proof of Concept: still correcting composer triggers *(Carlos Priego)*
*  Proof of Concept: Updater *(Carlos Priego)*
*  Code cleanup *(Carlos Priego)*
*  Almost done... *(Carlos Priego)*
*  Trying to fix annoying systemd-resolved *(Carlos Priego)*
*  Try 2 *(Carlos Priego)*
*  Try 3 *(Carlos Priego)*
*  Seems fixed *(Carlos Priego)*
*  Fixed problem with dnsmasq but requires restart *(Carlos Priego)*


## v2.0.14 (2017-04-30)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.14)

*  Detect user primary group instead of assuming it is the same as the username. *(Carlos Priego)*
*  Fix group error *(Carlos Priego)*
*  added support for openssl-san in chrome 58+ #54 *(nickurt)*
*  Fix errors with user's group in config files for php-fpm and nginx *(Carlos Priego)*
*  update version *(Prabhat Shahi)*


## v2.0.13 (2017-04-22)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.13)

*  added support for package-manager yum *(nickurt)*
*  Update travis.yml to fix Arch build error *(Carlos Priego)*
*  Add CentOS 7 box to Travis *(Leonardo Nodari)*
*  using sha256 for certs to fix weak-cert-signature in chrome *(nickurt)*
*  Clean up dead code *(Carlos Priego)*
*  Change fpm PM to dynamic and add networkmanager.conf *(Carlos Priego)*
*  Change where we set the dnsmasq/network-manager config file. *(Carlos Priego)*
*  Remove typehints *(Carlos Priego)*
*  Fix nginx pid configuration *(Carlos Priego)*
*  Bump version *(Carlos Priego)*
*  Disable Arch travis build because of temporal issues with image dns *(Carlos Priego)*
*  Fixing travis builds *(Carlos Priego)*
*  Mock filesystem in test *(Carlos Priego)*
*  Mock filesystem method to avoid errors in travis *(Carlos Priego)*


## v2.0.12 (2017-04-16)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.12)

*  Updated ngrok to version 2.2.4 *(Carlos Priego)*
*  Add composer script to fix lack of a PORT config key if you have updated valet from previous versions *(Carlos Priego)*
*  Bump version *(Carlos Priego)*


## v2.0.11 (2017-04-03)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.11)

*  Move tests into Integration folder *(Leonardo Nodari)*
*  Move travis tests to shell script *(Leonardo Nodari)*
*  Function test group *(Leonardo Nodari)*
*  Valet install test *(Leonardo Nodari)*
*  Tests namespace *(Leonardo Nodari)*
*  FunctionalTestCase *(Leonardo Nodari)*
*  Test link command *(Leonardo Nodari)*
*  Test valet unlink command *(Leonardo Nodari)*
*  Test valet links command *(Leonardo Nodari)*
*  Test valet park command *(Leonardo Nodari)*
*  Test valet forget command *(Leonardo Nodari)*
*  Test valet (un)secure commands *(Leonardo Nodari)*
*  Downgrade Site class to PHP5.6 *(Leonardo Nodari)*
*  Print failing process output *(Leonardo Nodari)*
*  Travis CI docker build *(Leonardo Nodari)*
*  Update .travis.yml *(Leonardo Nodari)*
*  Travis execute docker container prepare script *(Leonardo Nodari)*
*  Add Arch Linux *(Leonardo Nodari)*
*  Manually pass the $HOME environment variable when using sudo in order to avoid weird edge cases when not even the change in the sudoers file was enough. This fix would also make the sudoers change unnecesary \o/ I've also introduced a check for the existence of the /etc/NetworkManager/dnsmasq.d directory. *(Carlos Priego)*
*  Updated version number. *(Томица Кораћ)*
*  Bump version 2.0.11 *(Carlos Priego)*


## v2.0.10 (2017-03-28)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.10)

*  Fix dnsmasq TLD change *(Carlos Priego)*
*  Updated ngrok to version 2.2.2 *(Carlos Priego)*
*  Allow users to change the valet port from the command line *(Carlos Priego)*


## v2.0.9 (2017-03-23)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.9)

*  Update WordPressValetDriver.php *(Prabhat Shahi)*
*  Integrate PR, bump version and update Readme *(Carlos Priego)*


## v2.0.8 (2017-03-10)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.8)

*  Fix for double semicolon in nginx.conf *(Carlos Priego)*
*  Update valet version *(Prabhat Shahi)*


## v2.0.7 (2017-03-06)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.7)

*  Adding Pacman *(Carlos Priego)*
*  Fixed 'valet status' *(Carlos Priego)*
*  Fix pacman and systemd *(Carlos Priego)*
*  Get better status *(Carlos Priego)*
*  Ignore composer.lock *(Leonardo Nodari)*
*  Update composer lowest versions *(Leonardo Nodari)*
*  $query_string is not needed in nginx rewrite (#23) *(Favre Anael)*
*  Update tests *(Leonardo Nodari)*
*  Save to update master *(Carlos Priego)*
*  Remove sudoers entry *(Carlos Priego)*
*  Pretty print links *(Carlos Priego)*
*  Lock commands if valet is not installed *(Carlos Priego)*
*  Fixed query_string for secure sites *(Carlos Priego)*
*  Fix last merge conflict from master *(Carlos Priego)*
*  Fix Configuration::uninstall() not removing the valet config directory *(Carlos Priego)*
*  Try to fix service manager detection *(Carlos Priego)*
*  Fix for nginx.conf problems in Arch based systems *(Carlos Priego)*
*  Fix typo in nginx.conf *(Carlos Priego)*
*  Fix typo last error nginx.conf *(Carlos Priego)*
*  Bump version and announce support for Arch *(Carlos Priego)*


## v2.0.6 (2017-02-12)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.6)

*  Slugify folder names in server.php *(Carlos Priego)*
*  Refactor slugify process *(Leonardo Nodari)*


## v2.0.5 (2017-02-10)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.5)

*  Updated getPHPVersion() from cli/Valet/PackageManagers/Apt.php to include digit regex *(Ganesh K)*
*  Fixed  filters and tests for Apt *(Carlos Priego)*


## v2.0.4 (2017-02-07)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.4)

*  Fixed Nginx installation problems, cleaned up total 0 output and updated readme and updates accordingly. *(Carlos Priego)*


## v2.0.3 (2017-02-05)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.3)

*  Testing Fedora refactor *(Carlos Priego)*
*  Updated README and fixed Fedora and Ubuntu quirks, pending Tests fixes... *(Carlos Priego)*
*  Verbose ServiceManager messages *(Carlos Priego)*
*  Fix Facades *(Carlos Priego)*
*  Fix PM contract errors *(Carlos Priego)*
*  Fix PHP FPM config missing directory separator *(Carlos Priego)*
*  Fix Valet uninstall *(Carlos Priego)*
*  Update README and fixed fpm.conf for Fedora *(Carlos Priego)*
*  add nginx client_max_body_size value *(Alexander Hjorth)*
*  Ignore nginx stop error during installation *(Leonardo Nodari)*
*  Warning user if home is inside /root *(Leonardo Nodari)*
*  Warning on SELinux in enforcing mode *(Leonardo Nodari)*
*  Update readme *(Leonardo Nodari)*
*  Throw exception on positive warning *(Leonardo Nodari)*
*  Rename Warning to Requirements *(Leonardo Nodari)*
*  Fix Error: nginx-core does not exists in PPA *(Carlos Priego)*
*  Fixed ALL tests and ready for multidistro *(Carlos Priego)*
*  Change name in composer.json file *(Carlos Priego)*
*  Update dependencies, fixed tests for namespaced PHPUnit, bump version and added TheNodi as author *(Carlos Priego)*
*  Downgrade composer for compatibility with PHP 5.6 *(Carlos Priego)*


## v2.0.2 (2016-12-11)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.2)

*  Modify FPM and Nginx config files to take advantage of default 'include' folders. *(Carlos Priego)*


## v2.0.1 (2016-12-11)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v2.0.1)

*  Remove php*-mysql from required php packages *(Vince Mitchell)*
*  Prevent redeclaring tap function *(Vince Mitchell)*
*  Upgrade Valet for Ubuntu to version 2.0 *(Carlos Priego)*
*  Try to fix Travis CI. *(Carlos Priego)*
*  Second try to fix Travis CI. *(Carlos Priego)*


## v1.1.16 (2016-06-21)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v1.1.16)

*  fix SpaValetDriver error *(est73)*
*  add error log *(est73)*
*  Removed git  merge traces in some dotfiles *(Carlos Priego)*
*  Write description for secure and unsecure commands *(Carlos Priego)*
*  unlink command: fix for the empty  issue *(Carlos Priego)*
*  Fix scan certificates directory error when first change domain *(Carlos Priego)*
*  Bump version *(Carlos Priego)*


## v1.1.15 (2016-06-12)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v1.1.15)

*  Fixed creation of sudoers entry and simlink *(Carlos Priego)*


## v1.1.14 (2016-06-07)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v1.1.14)

*  Fixed Ngrok sharing, certificate installation for Ubuntu, dependency installation and updated Readme *(Carlos Priego)*


## v1.1.13 (2016-06-05)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v1.1.13)

*  fixed wrong spelling for the word "working" under the "which" command *(Rico Maglayon)*
*  Updated Readme badges and added travis *(Carlos Priego)*
*  Updated readme with more useful info. *(Carlos Priego)*
*  Tweak the Readme layout. *(Carlos Priego)*
*  Fix brew installations. *(Taylor Otwell)*
*  Fix tests. *(Taylor Otwell)*
*  Add some dotfiles (#73) *(Lucas Michot)*
*  Detect WordPress by configuration file (#65) *(Till Krüss)*
*  Fix spaces in path when using 'valet link' (#62) *(Jason P. Scharf)*
*  Remove useless imports (#76) *(Lucas Michot)*
*  Use assertFileExists and assertFileNotExists (#75) *(Lucas Michot)*
*  Use strict comparisons (#74) *(Lucas Michot)*
*  fixed typo *(Alfred Bez)*
*  Populate SERVER_ADDR to avoid undefined index notices in WordPress (#77) *(Jan Pingel)*
*  fixed wrong spelling for the word "working" under the "which" command *(Carlos Priego)*
*  Add some dotfiles *(Carlos Priego)*
*  Detect WordPress by configuration file and populate SERVER_ADDR to avoid undefined index notices *(Carlos Priego)*
*  Fix spaces in path when using 'valet link' *(Carlos Priego)*
*  Use assertFileExists and assertFileNotExists *(Carlos Priego)*
*  Fix fpm.conf testfile *(Carlos Priego)*
*  Don't strip www from SiteName *(Carlos Priego)*
*  Added support for changing ngrok region *(Carlos Priego)*
*  Added drivers for ProcessWire, Sphinx, Themosis, CsCart, Jekyll, Drupal, ShopWare and SinglePageApplication *(Carlos Priego)*
*  version 1.1.13 *(Carlos Priego)*


## v1.1.12 (2016-05-15)

[View Release](git@github.com:experius/valet-linux.git/commits/tag/v1.1.12)

*  first *(Taylor Otwell)*
*  update composer json *(Taylor Otwell)*
*  tweak dnsmasq installation *(Taylor Otwell)*
*  remove dd *(Taylor Otwell)*
*  fix version *(Taylor Otwell)*
*  change messages *(Taylor Otwell)*
*  fix deps *(Taylor Otwell)*
*  increment version *(Taylor Otwell)*
*  update name *(Taylor Otwell)*
*  update files *(Taylor Otwell)*
*  create resolver directory if it doesnt exist *(Taylor Otwell)*
*  increment version *(Taylor Otwell)*
*  adding paths command *(Taylor Otwell)*
*  added prune command *(Taylor Otwell)*
*  adding commands *(Taylor Otwell)*
*  adding files *(Taylor Otwell)*
*  update version *(Taylor Otwell)*
*  fix restart *(Taylor Otwell)*
*  increment *(Taylor Otwell)*
*  general cleaning *(Taylor Otwell)*
*  share feature *(Taylor Otwell)*
*  tweak script detection *(Taylor Otwell)*
*  prompt for sudo within shell script itself *(Taylor Otwell)*
*  clean up chown *(Taylor Otwell)*
*  Fix bugs *(Taylor Otwell)*
*  check proto *(Taylor Otwell)*
*  fix up tunnel detection *(Taylor Otwell)*
*  rename file *(Taylor Otwell)*
*  sub prompt other commands *(Taylor Otwell)*
*  make link and unlink arguments optinoal *(Taylor Otwell)*
*  init log files if they dont exist *(Taylor Otwell)*
*  statamic support *(Taylor Otwell)*
*  determine php *(Taylor Otwell)*
*  remove path check *(Taylor Otwell)*
*  rename serve to park *(Taylor Otwell)*
*  added recall *(Taylor Otwell)*
*  rename recall to forget *(Taylor Otwell)*
*  silent output *(Taylor Otwell)*
*  increment version *(Taylor Otwell)*
*  fix *(Taylor Otwell)*
*  move server file *(Taylor Otwell)*
*  loosen requirementsS *(Taylor Otwell)*
*  dont override paths *(Taylor Otwell)*
*  increment version *(Taylor Otwell)*
*  working on readme *(Taylor Otwell)*
*  serving sites *(Taylor Otwell)*
*  docs *(Taylor Otwell)*
*  wip *(Taylor Otwell)*
*  wip *(Taylor Otwell)*
*  wip *(Taylor Otwell)*
*  adding links *(Taylor Otwell)*
*  sharing *(Taylor Otwell)*
*  docs *(Taylor Otwell)*
*  listing commands *(Taylor Otwell)*
*  docs *(Taylor Otwell)*
*  simplify *(Taylor Otwell)*
*  add note *(Taylor Otwell)*
*  note *(Taylor Otwell)*
*  break *(Taylor Otwell)*
*  note *(Taylor Otwell)*
*  note *(Taylor Otwell)*
*  note on supported frameworks *(Taylor Otwell)*
*  note *(Taylor Otwell)*
*  database *(Taylor Otwell)*
*  header *(Taylor Otwell)*
*  improve docs *(Taylor Otwell)*
*  note *(Taylor Otwell)*
*  working on docs *(Taylor Otwell)*
*  logs *(Taylor Otwell)*
*  swap to driver based setup *(Taylor Otwell)*
*  cleaning drivers *(Taylor Otwell)*
*  add files *(Taylor Otwell)*
*  prune on every command *(Taylor Otwell)*
*  comments *(Taylor Otwell)*
*  remove unneeded command *(Taylor Otwell)*
*  remove command *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fix check *(Taylor Otwell)*
*  increment *(Taylor Otwell)*
*  cleanup *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Clarify share instructions slightly *(Adam Wathan)*
*  Remove "simply" and "just" from README. *(Jack McDade)*
*  Link dnsmasq and clarify some wording *(Matt Stauffer)*
*  fix conflicts *(Taylor Otwell)*
*  fix cons *(Taylor Otwell)*
*  docs on custom drivers *(Taylor Otwell)*
*  more documentation *(Taylor Otwell)*
*  move docs *(Taylor Otwell)*
*  update keywords *(Taylor Otwell)*
*  de-escalate sooner *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fix statamic cp *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Fix missing bracket *(Jerguš Lejko)*
*  Add StaticValetDriver for static pages *(Jerguš Lejko)*
*  rewrite host on the fly for ngrok *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  improve static driver *(Taylor Otwell)*
*  tweak static driver *(Taylor Otwell)*
*  loosen requirements *(Taylor Otwell)*
*  tweaks to drivers. add jigsaw *(Taylor Otwell)*
*  tweak statamic sharing *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Add mime types for Handlebars / Mustache templates *(Jan Hohner)*
*  Add woff2 missing mime type *(Jerguš Lejko)*
*  wordpress driver *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  craft support *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  ValetDriver::serves() method should return bool *(Igor Pantović)*
*  Add Generic Driver to point to a public/ folder (SlimPHP, Non-Framework PHP) *(Joe Ferguson)*
*  Symfony2/3 Valet driver *(Igor Pantovic)*
*  Register SymfonyValetDriver within $drivers array *(Igor Pantovic)*
*  added which command for debugging *(Taylor Otwell)*
*  add files *(Taylor Otwell)*
*  Add Katana Driver *(Mohamed Said)*
*  Stop existing dnsmasq.conf from being obliterated *(Keoghan Litchfield)*
*  Quote all variables in shell script *(Jason P. Scharf)*
*  fixing statamic installer *(Taylor Otwell)*
*  fix wordpress permalinks *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  allow updating domain dynamically *(Taylor Otwell)*
*  a few fixes *(Taylor Otwell)*
*  tweaking thingsS *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Add Contao CMS driver *(Sebastian Schlein)*
*  fix undefined index in mimes array *(lifesign)*
*  change into front controller path when executing *(Taylor Otwell)*
*  Fix mine to mime *(Adam Wathan)*
*  some cleaning *(Taylor Otwell)*
*  Improve GenericPhpValetDriver, remove unnecessary check in WP driver *(Adam Wathan)*
*  Add Sculpin Valet driver *(Jason Walton)*
*  conslidate drivers into basic driver if possible *(Taylor Otwell)*
*  zonda *(Taylor Otwell)*
*  wordpress for later purposes *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fixes *(Taylor Otwell)*
*  Remove '/Users/' prefix *(Pantelis Peslis)*
*  use caddy as the server into php *(Taylor Otwell)*
*  a few php fpm fixes *(Taylor Otwell)*
*  general code cleaning and refactoring *(Taylor Otwell)*
*  dont do logs by default *(Taylor Otwell)*
*  simplify user check *(Taylor Otwell)*
*  working on formatting *(Taylor Otwell)*
*  move caddy *(Taylor Otwell)*
*  update a few names *(Taylor Otwell)*
*  Tweak sed to work regardless of user/group values *(Adam Wathan)*
*  added brew class *(Taylor Otwell)*
*  cleaning restarts *(Taylor Otwell)*
*  chown caddyfile *(Taylor Otwell)*
*  fix chown *(Taylor Otwell)*
*  tweak caddyfile *(Taylor Otwell)*
*  Write a Caddy directory for loading additional configuration files. *(Taylor Otwell)*
*  always touch keep file *(Taylor Otwell)*
*  refactor a few functions *(Taylor Otwell)*
*  extract helper into autoloaded file *(Taylor Otwell)*
*  Dry's up things *(Kennedy Tedesco)*
*  BasicValetDriver - Minor change *(Kennedy Tedesco)*
*  progress refactoring *(Taylor Otwell)*
*  working on dnsmasq refactor *(Taylor Otwell)*
*  working on php fpm refactor *(Taylor Otwell)*
*  Check static folder for html file *(Jason Varga)*
*  Slash cleanup wasn't necessary *(Jason Varga)*
*  refactor and tests *(Taylor Otwell)*
*  add license file for caddy *(Taylor Otwell)*
*  add travis file *(Taylor Otwell)*
*  move files *(Taylor Otwell)*
*  skip check when testing *(Taylor Otwell)*
*  remove old php version from travis *(Taylor Otwell)*
*  add env variable *(Taylor Otwell)*
*  remove 5.5 *(Taylor Otwell)*
*  detect phpunit *(Taylor Otwell)*
*  fix tests user call *(Taylor Otwell)*
*  change to preg replace instead of sed *(Taylor Otwell)*
*  fix check *(Taylor Otwell)*
*  Fix docblocks *(Lucas Michot)*
*  version *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  allow php56 *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Escape file paths *(mattdfloyd)*
*  fix share *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fix symlink storage on laravel driver *(Taylor Otwell)*
*  cleaning up code *(Taylor Otwell)*
*  Statamic V1 driver *(Jason Varga)*
*  Add Kirby CMS driver *(Pedro Borges)*
*  fix offset error in wp-admin *(Evan Mattson)*
*  added ngrok class *(Taylor Otwell)*
*  update readme *(Taylor Otwell)*
*  remove unneeded code. *(Taylor Otwell)*
*  Remove empty uri check and unnecessary condition *(Jason Varga)*
*  slight formatting *(Taylor Otwell)*
*  Fix filename *(Jason Varga)*
*  fix conflicts *(Taylor Otwell)*
*  fix a few things *(Taylor Otwell)*
*  fix conflicts *(Taylor Otwell)*
*  fixing conflicts *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Fix Caddyfile path *(Pantelis Peslis)*
*  cake driver *(Taylor Otwell)*
*  organize better *(Taylor Otwell)*
*  Create JoomlaValetDriver.php *(Christophor Wilson)*
*  Update require.php *(Christophor Wilson)*
*  Update ValetDriver.php *(Christophor Wilson)*
*  Move isActualFile() to ValetDriver *(Kennedy Tedesco)*
*  correcting a few script problems *(Taylor Otwell)*
*  tweaking scripts *(Taylor Otwell)*
*  tweaking scripts *(Taylor Otwell)*
*  adding note to update script *(Taylor Otwell)*
*  dont double sudo if already sudo *(Taylor Otwell)*
*  tweaks to scripts *(Taylor Otwell)*
*  keep user updated *(Taylor Otwell)*
*  remove character *(Taylor Otwell)*
*  move scripts *(Taylor Otwell)*
*  fix replacement *(Taylor Otwell)*
*  fix location *(Taylor Otwell)*
*  fix bug *(Taylor Otwell)*
*  fix autoload *(Taylor Otwell)*
*  link on every install *(Taylor Otwell)*
*  call back into source *(Taylor Otwell)*
*  call install on each update *(Taylor Otwell)*
*  added sudoers entries. *(Taylor Otwell)*
*  add files *(Taylor Otwell)*
*  move method to brew class *(Taylor Otwell)*
*  fix comment *(Taylor Otwell)*
*  Allows Valet to run under PHP 5.5 (#57) *(Glendon Solsberry)*
*  add Bedrock driver *(Evan Mattson)*
*  update driver location *(Evan Mattson)*
*  correct return value *(Evan Mattson)*
*  fix path *(Taylor Otwell)*
*  simplify dir checks *(Taylor Otwell)*
*  use variable *(Taylor Otwell)*
*  comment *(Taylor Otwell)*
*  remove variable *(Taylor Otwell)*
*  various fixes *(Taylor Otwell)*
*  increment verison *(Taylor Otwell)*
*  fix resolution *(Taylor Otwell)*
*  Fix resolution. *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Tweaking a few things. *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  extract logic *(Taylor Otwell)*
*  set descriptions *(Taylor Otwell)*
*  run commands as sudo *(Taylor Otwell)*
*  combine vars *(Taylor Otwell)*
*  load extensions *(Taylor Otwell)*
*  fix file paths on extensions *(Taylor Otwell)*
*  disable timeout *(Taylor Otwell)*
*  minor formatting *(Taylor Otwell)*
*  Add warning() helper (#58) *(Kennedy Tedesco)*
*  tweaks *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  tweak craft driver *(Taylor Otwell)*
*  fix env configs with craft *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  Remove current-domain in favor of domain with no args (#61) *(Adam Wathan)*
*  remove else block *(Taylor Otwell)*
*  Consistency changes (#60) *(Daniel Morris)*
*  remove ide hint *(Taylor Otwell)*
*  Open website in your browser (#50) *(Robin Malfait)*
*  fix open for symlinks *(Taylor Otwell)*
*  shorten method *(Taylor Otwell)*
*  desc *(Taylor Otwell)*
*  add secure and unsecure *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  create sites directory *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  fix sites directory *(Taylor Otwell)*
*  version *(Taylor Otwell)*
*  First attempt to remove OSX complexities and adapt to Ubuntu *(Carlos Priego)*
*  Change compatibility to Ubuntu *(Carlos Priego)*
*  Fixed wierd errors caused by different listing modes in dpkg vs homebrew *(Carlos Priego)*
*  Update Valet Ubuntu source *(Carlos Priego)*
*  Updated composer file *(Carlos Priego)*
*  Try to fix Caddy *(Carlos Priego)*
*  Fix and error with VALET_PATH *(Carlos Priego)*
*  Fixed PHP-FPM paths, added Caddy function *(Carlos Priego)*
*  Added Functions and fixed open command *(Carlos Priego)*
*  Fixed service file working directory, made systemd service run systemwide and (becasuse of that) changed caddy commands *(Carlos Priego)*
*  Added config file for easy update and adapted tests *(Carlos Priego)*
*  Updated Readme *(Carlos Priego)*
*  Changed PHP-FPM restarting method *(Carlos Priego)*
*  Added reload command and modified status command *(Carlos Priego)*
*  Changed package description and added tags. *(Carlos Priego)*


