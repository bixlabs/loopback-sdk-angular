2019-01-14, Version 3.4.1
=========================

 * fix(model-namespacing): Fix namespacing of models (rcky)

 * add lts annoucement (jannyHou)


2018-09-20, Version 3.4.0
=========================

 * Upgrade strong-globalize to latest (Miroslav Bajtoš)

 * Drop support for Node.js 4.x, test 10.x (Miroslav Bajtoš)

 * [WebFM] cs/pl/ru translation (candytangnb)


2018-05-10, Version 3.3.2
=========================

 * fix inherit params for custom endpoint (Matteo Padovano)


2018-04-19, Version 3.3.1
=========================

 * fix: Node.js 4.x support (Miroslav Bajtoš)

 * Enable Travis CI integration (Miroslav Bajtoš)


2018-01-25, Version 3.3.0
=========================

 * Update ejs to the latest version (Lorenzo Kappeler)

 * README: update link to docs (Dr Luke Angel)

 * Update LICENSE (Diana Lau)


2017-08-22, Version 3.2.1
=========================

 * Address code review comment (rashmihunt)

 * updateOnly property (rashmihunt)

 * Update Issue and PR Templates (#277) (Sakib Hasan)

 * Update translated strings Q3 2017 (Allen Boone)

 * update translation file (Diana Lau)

 * Add CODEOWNER file (Diana Lau)

 * Replicate new issue_template from loopback (Siddhi Pai)

 * Replicate issue_template from loopback repo (Siddhi Pai)


2017-04-25, Version 3.2.0
=========================

 * Add new option namespaceCommonModels (Kenny Sabir)


2017-02-06, Version 3.1.0
=========================

 * Update sdk to use loopback 3.x (David Cheung)

 * Update ko translation file (Candy)

 * Update paid support URL (Siddhi Pai)


2016-11-22, Version 3.0.0
=========================

 * Drop support for Node v0.10 and v0.12 (Miroslav Bajtoš)

 * Start the development of the next major version (Miroslav Bajtoš)

 * Update README.md (Rand McKinney)

 * test: array descriptions for remoteMethods (David Cheung)


2016-10-14, Version 1.10.2
==========================

 * Update LoopBackResource function parameter name (Nick Duffy)

 * Update ja translation file (Candy)

 * clear user upon failed auth upon User.getCurrent (David Cheung)

 * getEndPoints() compatibility for strong-remoting (David Cheung)

 * Update translation files - round#2 (Candy)

 * globalization: add translated strings (gunjpan)


2016-09-05, Version 1.10.1
==========================

 * Revert globalization for init script (David Cheung)


2016-08-24, Version 1.10.0
==========================

 * Add "modelsToIgnore" option (Aquid Shahwar)

 * Support `PATCH` method in test cases (David Cheung)

 * Globalize loopback-sdk-angular (David Cheung)


2016-07-29, Version 1.9.0
=========================

 * Allow namespacing and shared module exclusion (Keith Aleq Jackson)

 * Update deprecated remoting metadata functions (David Cheung)

 * Update dependency and test command for PhantomJS (jeff-clegg)

 * Update URLs in CONTRIBUTING.md (#227) (Ryan Graham)


2016-07-13, Version 1.8.0
=========================

 * Expose configured properties on LoopBackResource (Matteo Padovano)

 * Describe model schema in generated $resource (Miroslav Bajtos)

 * update copyright notices and license (Ryan Graham)

 * Clear user data when logout returns error response (Matteo Padovano)

 * Lint generated code (David Cheung)

 * Use ESlint in replace of jshint (David Cheung)

 * added test for LoopBackResourceProvider.getAuthHeader() method. (Martin Juhasz)

 * Added getter for AuthHeader value in LoopBackResource (Martin Juhasz)


2016-02-24, Version 1.7.0
=========================

 * Handle Safari private/incognito mode (David Cheung)

 * Update dependencies (Miroslav Bajtoš)

 * Remove bower.json, install deps via npm (Miroslav Bajtoš)

 * Add CommonJS package manager support (Djamel Feddad)

 * Fix npm test on windows (David Cheung)


2015-12-08, Version 1.6.0
=========================

 * Send auth header to all URLs on the same host (Partap Davis)

 * Add `rememberMe` to `props` in LoopBackAuth (David Cheung)

 * Add model description for docular (David Cheung)

 * Refer to licenses with a link (Sam Roberts)

 * Use strongloop conventions for licensing (Sam Roberts)


2015-09-01, Version 1.5.0
=========================

 * Add loopBackResourceProvider.getUrlBase() (Jonathan Sheely)

 * fixed the hard coded 'lbServices' in the documentation (Roi Ezra)


2015-08-10, Version 1.4.1
=========================

 * Support remote methods named like scope methods (kennethlynne)


2015-06-17, Version 1.4.0
=========================

 * Add createMany functionallity (Jonathan Casarrubias)

 * Support "accepts" arguments mapped to URL params (Matt McCabe)

 * Fix bad CLA URL in CONTRIBUTING.md (Ryan Graham)


2014-11-19, Version 1.3.7
=========================

 * Fix IE8 comma trailing (ru108)


2014-11-14, Version 1.3.6
=========================

 * Fix the URL requested by `User.getCurrent` (Loïc Payol)

 * Clear keys from both local and session storage on logout (Ilia Nazarov)


2014-11-11, Version 1.3.5
=========================

 * apidocs: include PersistedModel, sort models (Miroslav Bajtoš)


2014-11-05, Version 1.3.4
=========================

 * services: fix ngdoc @param missing a description (Miroslav Bajtoš)

 * test-server: return non-zero exit on test failure (Miroslav Bajtoš)


2014-10-29, Version 1.3.3
=========================

 * services: improve LoopBackResourceProvider apidocs (Miroslav Bajtoš)

 * apidocs: fix handling of anchor URLs (Miroslav Bajtoš)


2014-10-28, Version 1.3.2
=========================

 * services: make ngdoc comments jsdoc compatible (Miroslav Bajtoš)

 * Add AngularJS API docs for built-in models (Miroslav Bajtoš)

 * Update contribution guidelines (Ryan Graham)


2014-10-01, Version 1.3.1
=========================

 * Fix request interceptor to process only urlBase requests (Ariel Schiavoni)


2014-09-30, Version 1.3.0
=========================

 * Make urlBase configurable (Ariel Schiavoni)

 * Add configurable authentication header (Khashayar Hajian)

 * Add `R.modelName` property (Miroslav Bajtoš)


2014-09-18, Version 1.2.2
=========================

 * Use moduleName tag for User methods documentation (Franco Cedillo)


2014-09-18, Version 1.2.1
=========================

 * Fix the code detecting User model (Miroslav Bajtoš)

 * Run tests using loopback 2.x. (Miroslav Bajtoš)

 * Add extension to template file name (Aleksandr Tsertkov)


2014-07-24, Version 1.2.0
=========================

 * Fix ngdoc comment for related method (Miroslav Bajtoš)

 * Support custom User-based models (Miroslav Bajtoš)

 * Revert mocha back to 1.18 (Miroslav Bajtoš)


2014-07-24, Version 1.1.4
=========================

 * Update dependencies (Miroslav Bajtoš)

 * Hide original scope methods from ngdoc (Miroslav Bajtoš)

 * Fix ngdoc generated for scope methods (Miroslav Bajtoš)

 * Improve the ngdoc comments generator. (Miroslav Bajtoš)


2014-07-03, Version 1.1.3
=========================

 * Implement support for remote method aliases. (Miroslav Bajtoš)

 * Use "mocha" reporter instead of "progress" (Miroslav Bajtoš)

 * package: freeze mocha at ~1.18 (Miroslav Bajtoš)


2014-07-02, Version 1.1.2
=========================

 * Bump version (Raymond Feng)

 * Fix name refs (Raymond Feng)

 * Upgrade mocha to 1.20.1 (Miroslav Bajtoš)


2014-07-01, Version 1.1.1
=========================

 * Update module name (Raymond Feng)

 * Update link to doc (Rand McKinney)

 * User.isAuthenticated and User.getCurrentId (Miroslav Bajtoš)

 * Implement User.getCachedCurrent(). (Miroslav Bajtoš)

 * Change User.login to send include=user by default. (Miroslav Bajtoš)

 * Fail the "pretest" script on jshint errors (Miroslav Bajtoš)


2014-04-09, Version 1.1.0
=========================

 * Fix - Minification issue, global object (Aurelien Chivot)

 * test: verify belongsTo relation (Miroslav Bajtoš)

 * sharedCtor arguments in ngdoc of prototype methods (Miroslav Bajtoš)

 * Support hasAndBelongsToMany scope methods (Miroslav Bajtoš)

 * Prevent reuse of model classes between tests (Miroslav Bajtoš)

 * Allow e2e tests to run custom setup code on server (Miroslav Bajtoš)

 * Support internal and @deprecated methods in ngdoc (Miroslav Bajtoš)

 * Template refactoring: extract ngdocForMethod (Miroslav Bajtoš)

 * npm test: remove dependency on global karma-cli (Miroslav Bajtoš)

 * test-server: exit when child process failed (Miroslav Bajtoš)

 * package.json: remove bin scripts (Miroslav Bajtoš)

 * Update all dependencies to latest versions. (Miroslav Bajtoš)

 * Remove mocha-as-promised. (Miroslav Bajtoš)

 * Remove bin/ scripts. (Miroslav Bajtoš)

 * Ignore CI generated files (Ryan Graham)

 * Add secondary karma reporter: junit (Ryan Graham)


2014-02-19, Version 1.0.0
=========================

 * Update to MIT/StrongLoop dual license (Raymond Feng)

 * Upgrade devDependencies (Miroslav Bajtoš)

 * Add missing devDependency: jshint (Ryan Graham)

 * Add bower as devDependency (Ryan Graham)

 * Update README, link to doc.strongloop.com (Miroslav Bajtoš)


2014-02-07, Version 0.2.1
=========================

 * Use `self` instead of `bind(this)` (Miroslav Bajtoš)

 * Fix template to add getCurrent to User model only. (Miroslav Bajtoš)


2014-02-06, Version 0.2.0
=========================

 * Implement "rememberMe" option for login. (Miroslav Bajtoš)

 * Add User.getCurrent, persist accessTokenId (Miroslav Bajtoš)

 * Remove extra empty lines from services.template (Miroslav Bajtoš)

 * Add "pretest" script to run jshint before tests. (Miroslav Bajtoš)

 * Remove bin/ and related code. (Miroslav Bajtoš)

 * Improve ngdoc for params and returns. (Miroslav Bajtoš)

 * Add CONTRIBUTING guide (Miroslav Bajtoš)

 * Add .jshintignore file (Miroslav Bajtoš)

 * Extract test parsers (Miroslav Bajtoš)


2014-01-31, Version 0.1.0
=========================

 * First release!
