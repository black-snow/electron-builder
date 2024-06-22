# [](https://github.com/electron-userland/electron-builder/compare/v10.8.1...v) (2024-06-22)


### Bug Fixes

* __shim.js not found upon launch ([87896a8](https://github.com/electron-userland/electron-builder/commit/87896a8f720fded320f7540832c2549ec7b1eaf3)), closes [#2146](https://github.com/electron-userland/electron-builder/issues/2146)
* __shim.js not under the source directory ([01ab0ce](https://github.com/electron-userland/electron-builder/commit/01ab0ce6826e3d6362f62606e08617eca5e60c14)), closes [#2319](https://github.com/electron-userland/electron-builder/issues/2319)
* --ia32 parameter not working as expected anymore ([c37bd00](https://github.com/electron-userland/electron-builder/commit/c37bd009d60665994d07b98436fe4d11bd986e7f)), closes [#1348](https://github.com/electron-userland/electron-builder/issues/1348)
* "Can't reconcile two non-macho files" due to new Pre-Gyp-Copy functionality in electron/rebuild integration ([#7519](https://github.com/electron-userland/electron-builder/issues/7519)) ([abf3703](https://github.com/electron-userland/electron-builder/commit/abf370395f45e4005f12131c532325a1e3232309))
* "status 401: Unauthorized" issue with dl.bintray.com ([52995df](https://github.com/electron-userland/electron-builder/commit/52995df0025a9cdf4523545687810cc0eac3b2eb)), closes [#1581](https://github.com/electron-userland/electron-builder/issues/1581)
* ([#5685](https://github.com/electron-userland/electron-builder/issues/5685)) check if icons subdir exists in build resources, otherwise don't prepend it to fallback sources ([#5686](https://github.com/electron-userland/electron-builder/issues/5686)) ([8df250b](https://github.com/electron-userland/electron-builder/commit/8df250b4645924942883ba6ad1418da994116521))
* (mac) Fix intel mac upgrade flow when both x64 and arm64 published ([#6212](https://github.com/electron-userland/electron-builder/issues/6212)) ([0c21cd6](https://github.com/electron-userland/electron-builder/commit/0c21cd69663a7eebe0687eaba9eea851cc2fea9e))
* `inherit` stdio for electron-updater `exec` ([#7393](https://github.com/electron-userland/electron-builder/issues/7393)) ([#7394](https://github.com/electron-userland/electron-builder/issues/7394)) ([1bbcfb3](https://github.com/electron-userland/electron-builder/commit/1bbcfb3dc5f36b0803c69e9170db16ded52a0043))
* `publish` produced "...armv7l.yml", but updater finds for "...arm.yml" ([7b5ffe6](https://github.com/electron-userland/electron-builder/commit/7b5ffe686795b8a30272e223bb5501eb89f0ed7c)), closes [#2884](https://github.com/electron-userland/electron-builder/issues/2884)
* ${arch} causes a build fail ([#5905](https://github.com/electron-userland/electron-builder/issues/5905)) ([014cbf5](https://github.com/electron-userland/electron-builder/commit/014cbf5f98a25d6537f9f2b49e90cc401a2f3bce)), closes [#5857](https://github.com/electron-userland/electron-builder/issues/5857)
* ${arch} missing from app-update.yml ([77558e6](https://github.com/electron-userland/electron-builder/commit/77558e648cc7ce7e10ff8e7df6e6cdc9b74295a4)), closes [#1389](https://github.com/electron-userland/electron-builder/issues/1389)
* ${os} pattern in artifactName does not follow wiki ([38339b9](https://github.com/electron-userland/electron-builder/commit/38339b9dafae082c64256fef5bdb995bd1cd67d2)), closes [#1263](https://github.com/electron-userland/electron-builder/issues/1263)
* 19.20.0 does not read electron-builder.yml ([c4aacfc](https://github.com/electron-userland/electron-builder/commit/c4aacfcfc3dd9bc0ce826985bbe0f493cf7359c0)), closes [#1927](https://github.com/electron-userland/electron-builder/issues/1927)
* 19.8.0 broke ignoring folders ([50fe277](https://github.com/electron-userland/electron-builder/commit/50fe27724238d89de752c6446cadfb5a030a709d)), closes [#1741](https://github.com/electron-userland/electron-builder/issues/1741)
* 20.16.1 Hangs without building the app ([0ef803d](https://github.com/electron-userland/electron-builder/commit/0ef803d74d8371c9e6190ef01fe3344c79c27d31)), closes [#3043](https://github.com/electron-userland/electron-builder/issues/3043)
* Add "arm" as an alias for armv7l as process.arch outputs arm on armv7l hosts ([#6845](https://github.com/electron-userland/electron-builder/issues/6845)) ([d3452b0](https://github.com/electron-userland/electron-builder/commit/d3452b0427cb45035f6ed7f1266691db4accd5c4))
* add /debug flag to signtool, do not try to use openssl on Windows [#2875](https://github.com/electron-userland/electron-builder/issues/2875) ([bd77520](https://github.com/electron-userland/electron-builder/commit/bd77520ddbd209f4bdc180cf2d772fedb2d7a684))
* add `recursive: true` to `fs.rm` wnen removing locales ([#5961](https://github.com/electron-userland/electron-builder/issues/5961)) ([c9b78f9](https://github.com/electron-userland/electron-builder/commit/c9b78f958daf778747843dd2d671628f9cbb8ef6))
* add `signExts` configuration option to not sign `.node` files by default ([#7685](https://github.com/electron-userland/electron-builder/issues/7685)) ([78448af](https://github.com/electron-userland/electron-builder/commit/78448af062e2ce70c1eb590c05cce01919933e26))
* add appCannotBeClosed text for zh_CN ([#6287](https://github.com/electron-userland/electron-builder/issues/6287)) ([10b4727](https://github.com/electron-userland/electron-builder/commit/10b47273c32c32df17dfb910feb4a7704c83da91))
* add back missing `createLazyProductionDeps` that was missed during revert ([#7679](https://github.com/electron-userland/electron-builder/issues/7679)) ([f5d23ef](https://github.com/electron-userland/electron-builder/commit/f5d23ef4edce6096759a3e25dfe453366ab72da2))
* add dmg-builder and squirrel-windows to peerDependencies for pnpm ([#8052](https://github.com/electron-userland/electron-builder/issues/8052)) ([6a4f605](https://github.com/electron-userland/electron-builder/commit/6a4f605f9ae1a1de02a8260ffe054f74fbd097a5))
* add missing %U in desktop file of appimages ([#4909](https://github.com/electron-userland/electron-builder/issues/4909)) ([d96b3d3](https://github.com/electron-userland/electron-builder/commit/d96b3d39c4caf959cc929f562f70e4de3983420b)), closes [#4035](https://github.com/electron-userland/electron-builder/issues/4035)
* add product scope to keygen provider ([#6975](https://github.com/electron-userland/electron-builder/issues/6975)) ([8279d05](https://github.com/electron-userland/electron-builder/commit/8279d053d520e7506d84bf9710972b998e70b752))
* add product scope to keygen publisher ([#6990](https://github.com/electron-userland/electron-builder/issues/6990)) ([c3407a2](https://github.com/electron-userland/electron-builder/commit/c3407a202d4dc1599b2cb90a7ff3d56e8e32309e))
* add reject in handleError in Windows `verifySignature` function ([#7380](https://github.com/electron-userland/electron-builder/issues/7380)) ([7862e38](https://github.com/electron-userland/electron-builder/commit/7862e388a2049ccbe1e01a5624c6a8a5f2942d54))
* Add support for nested file extensions (such as `.dmg.blockmap`) to Keygen publisher ([#6234](https://github.com/electron-userland/electron-builder/issues/6234)) ([369f1fa](https://github.com/electron-userland/electron-builder/commit/369f1fa793c28d8743e19ef07ce6eb091c191fb0)), closes [#6229](https://github.com/electron-userland/electron-builder/issues/6229)
* add user agent check for yarn ([#3183](https://github.com/electron-userland/electron-builder/issues/3183)) ([6067acc](https://github.com/electron-userland/electron-builder/commit/6067accb36fc8a94da607403bef8132ef635fbcb)), closes [#3181](https://github.com/electron-userland/electron-builder/issues/3181)
* add warning to macCodeSign when skipping code signing on M1 macOS device ([#6522](https://github.com/electron-userland/electron-builder/issues/6522)) ([8730027](https://github.com/electron-userland/electron-builder/commit/87300278d24e8304caa4b053b883843a2447dab2))
* Added Changelog and Readme writing  to excluded files ([39f6b84](https://github.com/electron-userland/electron-builder/commit/39f6b84a62c8f5ab21b991ebd786aa8427d6e354))
* Added missing `event-update-not-available` in UpdaterEvents ([#5923](https://github.com/electron-userland/electron-builder/issues/5923)) ([dc359de](https://github.com/electron-userland/electron-builder/commit/dc359de5019807a014c62468385dfb14bbb5bd83))
* Added path normalization for file filter ([#1864](https://github.com/electron-userland/electron-builder/issues/1864)) ([82c8905](https://github.com/electron-userland/electron-builder/commit/82c89052ff7276f5900c54b8da50beefc69020cf))
* Added support for overriding ‘strict-verify’ electron-osx-sign property. ([#5261](https://github.com/electron-userland/electron-builder/issues/5261)) ([c554f25](https://github.com/electron-userland/electron-builder/commit/c554f25d7533f23e57c3f4fe11fa0ca54f7cfc29)), closes [#1480](https://github.com/electron-userland/electron-builder/issues/1480)
* adding `IMAGE_VERSION` arg for docker `node` image so that it force rebuilds when pnpm is updated on any date ([#7690](https://github.com/electron-userland/electron-builder/issues/7690)) ([47c1fd7](https://github.com/electron-userland/electron-builder/commit/47c1fd71080f8079f97f6513dd037a5a617f3809))
* Adding libxtst6 to base dockerfile image. Fixes: [#5907](https://github.com/electron-userland/electron-builder/issues/5907) ([#5913](https://github.com/electron-userland/electron-builder/issues/5913)) ([096e109](https://github.com/electron-userland/electron-builder/commit/096e10939c506c41e9cc9d5d69534aaad6e76fd2))
* adding log warning in case `afterSign` exists but no signing occurred ([#7388](https://github.com/electron-userland/electron-builder/issues/7388)) ([1cb8f50](https://github.com/electron-userland/electron-builder/commit/1cb8f50c3551b398e20b798aba0c60bb34860b49))
* Adding snapStore to AllPublishOptions for generating Configuration schema ([#6193](https://github.com/electron-userland/electron-builder/issues/6193)) ([7f933d0](https://github.com/electron-userland/electron-builder/commit/7f933d0004a0a5f808a2a1c71dca7362cab2728e))
* afterPack callback is not called at the same time for windows & mac ([087d90b](https://github.com/electron-userland/electron-builder/commit/087d90b5ef8d9a18be3aa7f01b090b99ab816d38)), closes [#1689](https://github.com/electron-userland/electron-builder/issues/1689)
* afterPack Usage in Build Config ([9b21b09](https://github.com/electron-userland/electron-builder/commit/9b21b09a68896c97beeb0a885ada5fb4163b8bc2)), closes [#2255](https://github.com/electron-userland/electron-builder/issues/2255)
* allow $schema property in electron-builder.json ([#3963](https://github.com/electron-userland/electron-builder/issues/3963)) ([1d9d5ed](https://github.com/electron-userland/electron-builder/commit/1d9d5ed9e470432c6bab6a4d66490a5134ca2464)), closes [#3962](https://github.com/electron-userland/electron-builder/issues/3962)
* Allow building MAS and MAC targets with different appId ([#7603](https://github.com/electron-userland/electron-builder/issues/7603)) ([f464e3e](https://github.com/electron-userland/electron-builder/commit/f464e3ee6b8a6330a9be2961afaaec150777f91c))
* allow CSC_LINK to have a mime-type prefix before extracting it to a p12 ([#7119](https://github.com/electron-userland/electron-builder/issues/7119)) ([323618f](https://github.com/electron-userland/electron-builder/commit/323618f79108a8bb829dc1e84e933ace90940010))
* Allow disabling of webinstaller files to avoid confusion with actual installers ([#6575](https://github.com/electron-userland/electron-builder/issues/6575)) ([5e381c5](https://github.com/electron-userland/electron-builder/commit/5e381c556d12ce185bb7ea720380509c1ddc5cf7))
* Allow MAS builds to be unsigned if `identity: null` is explicitly passed ([#7382](https://github.com/electron-userland/electron-builder/issues/7382)) ([bb37687](https://github.com/electron-userland/electron-builder/commit/bb37687540aa254bce6a92a86c56b606cc16f2be))
* Allow non-semver versions in getVersionInWeirdWindowsForm ([#7174](https://github.com/electron-userland/electron-builder/issues/7174)) ([0f9865d](https://github.com/electron-userland/electron-builder/commit/0f9865dc0775f9d80d3bd64cf3e2131be3ae9acb)), closes [#7173](https://github.com/electron-userland/electron-builder/issues/7173)
* allow user to define explicit `buildNumber` in config, useful for fpm `--iteration` flag ([#7075](https://github.com/electron-userland/electron-builder/issues/7075)) ([8166267](https://github.com/electron-userland/electron-builder/commit/8166267d487cd26b154e28cf60d89102a487a353))
* Allowing `test.js` in compiled asar to allow testing mechanisms like Playwright ([#7931](https://github.com/electron-userland/electron-builder/issues/7931)) ([f7aacab](https://github.com/electron-userland/electron-builder/commit/f7aacabd9cc1b98e365134004aafa31566c7d801))
* allowing + symbols for expanding macros. necessary for '+nightly' builds ([#5990](https://github.com/electron-userland/electron-builder/issues/5990)) ([8e6f008](https://github.com/electron-userland/electron-builder/commit/8e6f008d2f93e06aebb00402500e02a37edb0bd0))
* always respect arch in user custom artifact pattern ([45f17f5](https://github.com/electron-userland/electron-builder/commit/45f17f5e1f4826dc27591cf8f0409d7252411282)), closes [#3510](https://github.com/electron-userland/electron-builder/issues/3510)
* always revalidate cache ([02a96f4](https://github.com/electron-userland/electron-builder/commit/02a96f43ff5667ff9779b8e8941ebde294ac5c5e)), closes [#1186](https://github.com/electron-userland/electron-builder/issues/1186)
* any "node_module/____" glob pattern selects far too many node dependencies ([#6080](https://github.com/electron-userland/electron-builder/issues/6080)) ([72ffc25](https://github.com/electron-userland/electron-builder/commit/72ffc25063fc6d8f67e941ed7fc3b5991efb5448)), closes [#6045](https://github.com/electron-userland/electron-builder/issues/6045)
* **app-builder-lib:** Allow using lowercase value for certificateSha1 ([#4684](https://github.com/electron-userland/electron-builder/issues/4684)) ([5390bb6](https://github.com/electron-userland/electron-builder/commit/5390bb6a3b16ceab3dd4456f717fd8e978f4217c)), closes [#4631](https://github.com/electron-userland/electron-builder/issues/4631)
* **app-builder-lib:** bump @electron/universal to 1.2.1 ([#6750](https://github.com/electron-userland/electron-builder/issues/6750)) ([370f84b](https://github.com/electron-userland/electron-builder/commit/370f84bb2f32f28c374b63e1c795e4850f971274))
* **app-builder-lib:** change slash to backslash in NSIS's APP_PACKAGE_NAME ([#6772](https://github.com/electron-userland/electron-builder/issues/6772)) ([e861352](https://github.com/electron-userland/electron-builder/commit/e86135236908961b1269708ca645a66c7ff19287))
* **app-builder-lib:** channel alternation for github is not working ([#6449](https://github.com/electron-userland/electron-builder/issues/6449)) ([df7a425](https://github.com/electron-userland/electron-builder/commit/df7a4255d219aea7a1236fd5693f7c13460099ad))
* **app-builder-lib:** export missing TS types ([#6692](https://github.com/electron-userland/electron-builder/issues/6692)) ([93181a7](https://github.com/electron-userland/electron-builder/commit/93181a78f2893ea4929aea8878343336931b3a04))
* **app-builder-lib:** export missing TS types ([#7297](https://github.com/electron-userland/electron-builder/issues/7297)) ([9ce7448](https://github.com/electron-userland/electron-builder/commit/9ce74482ef0f4abc1206dc96dca559eb9f03d50c))
* **app-builder-lib:** macOS packager uses static icon name ([#6308](https://github.com/electron-userland/electron-builder/issues/6308)) ([fce1a1f](https://github.com/electron-userland/electron-builder/commit/fce1a1fab66e3f5cd741a4cecc4af8377aea9dd8))
* **app-builder-lib:** Overriding OutgoingHttpHeaders schema props ([#6775](https://github.com/electron-userland/electron-builder/issues/6775)) ([e9a87a7](https://github.com/electron-userland/electron-builder/commit/e9a87a738ceb2b9e14cbc85b4c62e11edab3d0cf)), closes [#6635](https://github.com/electron-userland/electron-builder/issues/6635)
* **app-builder-lib:** signing certificate selection by sha1 ([#4499](https://github.com/electron-userland/electron-builder/issues/4499)) ([1f2865b](https://github.com/electron-userland/electron-builder/commit/1f2865b1f317ab4671b76f490584749518120176))
* **app-builder-lib:** Typo in error ([#3698](https://github.com/electron-userland/electron-builder/issues/3698)) ([480b930](https://github.com/electron-userland/electron-builder/commit/480b930d017ae707b1c9e9e4483362cea3460b6e))
* **app-builder-lib:** use DigiCert timestamp server as default ([#3965](https://github.com/electron-userland/electron-builder/issues/3965)) ([09a6cdd](https://github.com/electron-userland/electron-builder/commit/09a6cddb515d5114514ea29adb66e44b7471292d))
* **app-builder-lib:** yarn install break on 'electron-builder install-app-deps' when used pnp ([#4147](https://github.com/electron-userland/electron-builder/issues/4147)) ([0fe8f12](https://github.com/electron-userland/electron-builder/commit/0fe8f1279112fa8bcb1e795e2fcd3594accc0b1f))
* app-update.yml not generated (MAC zip + pkg) ([3c7ef2d](https://github.com/electron-userland/electron-builder/commit/3c7ef2d2923bbeff53b472c32830f624b8a3ff8a)), closes [#2541](https://github.com/electron-userland/electron-builder/issues/2541)
* AppImage differential download fires too many requests ([79e3b79](https://github.com/electron-userland/electron-builder/commit/79e3b79e6edf95b7bdde63e1baf69a92057f63e0)), closes [#2219](https://github.com/electron-userland/electron-builder/issues/2219)
* **AppImage:** Add default argument --no-sandbox ([#4496](https://github.com/electron-userland/electron-builder/issues/4496)) ([ede6d50](https://github.com/electron-userland/electron-builder/commit/ede6d50ddb6c23fe6bbb056bd80509c8f2ea0116))
* **AppImage:** AppImage artifact name does not use `artifactName` template ([a02fbd7](https://github.com/electron-userland/electron-builder/commit/a02fbd7971ab697b2fd492c829ba9a28ef210c72)), closes [#1726](https://github.com/electron-userland/electron-builder/issues/1726)
* **AppImage:** AppImage content is not correct (resources_1 dir) ([b338c91](https://github.com/electron-userland/electron-builder/commit/b338c910f1590e7b879d6cdcf2b1413d73c328d8)), closes [#2958](https://github.com/electron-userland/electron-builder/issues/2958)
* **appimage:** AppImage tool runtimes is broken ([a3b2213](https://github.com/electron-userland/electron-builder/commit/a3b2213b82b196f34c225a69bc0106261e987984)), closes [#2316](https://github.com/electron-userland/electron-builder/issues/2316)
* **AppImage:** AppRun.sh sometimes fails to install icons ([#2300](https://github.com/electron-userland/electron-builder/issues/2300)) ([3926d23](https://github.com/electron-userland/electron-builder/commit/3926d23b173eb2e35abff753483a8c0e4701aba7))
* **AppImage:** Binary not found in new AppImage support ([efe0793](https://github.com/electron-userland/electron-builder/commit/efe0793de559bbc0974239ea10c23764a8875ce5)), closes [#2151](https://github.com/electron-userland/electron-builder/issues/2151)
* **AppImage:** do not print debug info about installed AppImage on run ([a167257](https://github.com/electron-userland/electron-builder/commit/a1672570347507a7e6b0b374caff22aa17015003)), closes [#2807](https://github.com/electron-userland/electron-builder/issues/2807)
* **AppImage:** Escape .desktop to fix RESOURCE_NAME detection ([#2041](https://github.com/electron-userland/electron-builder/issues/2041)) ([d61be58](https://github.com/electron-userland/electron-builder/commit/d61be586920b1b07a89bba3df82be7c385657a1e))
* **AppImage:** fix AppImage build regression if max compression used ([5081536](https://github.com/electron-userland/electron-builder/commit/5081536bce3d4d2eb1b8c946868293c6f347d749)), closes [#2664](https://github.com/electron-userland/electron-builder/issues/2664)
* **AppImage:** get rid of shell sed/find/whatever - just use EJS ([3b9e4fd](https://github.com/electron-userland/electron-builder/commit/3b9e4fd6767684b1f8f679d60efdc7b572b753fc)), closes [#2040](https://github.com/electron-userland/electron-builder/issues/2040)
* **AppImage:** include libappindicator1 in AppImage ([df7d316](https://github.com/electron-userland/electron-builder/commit/df7d3167471a399d64d04ea81b54a7ad55d300df)), closes [#1082](https://github.com/electron-userland/electron-builder/issues/1082)
* **AppImage:** kdialog args cause AppRun exit ([762225a](https://github.com/electron-userland/electron-builder/commit/762225a190729be309100dbf04579ef3775f88cd))
* **AppImage:** kdialog args cause AppRun exit ([0ee8779](https://github.com/electron-userland/electron-builder/commit/0ee8779b7422588d263a07034afa66ab021ae14b)), closes [#2244](https://github.com/electron-userland/electron-builder/issues/2244) [#2239](https://github.com/electron-userland/electron-builder/issues/2239)
* **appimage:** Linux AppImage target doesn't reuse the launcher icon ([96895cf](https://github.com/electron-userland/electron-builder/commit/96895cfe1d46a9b7546c8f7b8727fb369399448a)), closes [#1003](https://github.com/electron-userland/electron-builder/issues/1003)
* **AppImage:** pass --no-appstream ([c29d83f](https://github.com/electron-userland/electron-builder/commit/c29d83ffa75d750a73c4220e34fe287c48b79228)), closes [#2274](https://github.com/electron-userland/electron-builder/issues/2274)
* **AppImage:** remove nss lib ([0601352](https://github.com/electron-userland/electron-builder/commit/0601352736fe0246396033d2e3137c55ebe22a30))
* **AppImage:** restore appimaged compatibility (AppImage 2) ([b373275](https://github.com/electron-userland/electron-builder/commit/b373275314516fcb4fedfa241b109147fb31319f))
* **AppImage:** support for Tray icons ([a3240c2](https://github.com/electron-userland/electron-builder/commit/a3240c269308eaf8b67ce96c8f93dcf055738826))
* **appimage:** USE_SYSTEM_XORRISO env to force usage of system xorriso ([03e43d1](https://github.com/electron-userland/electron-builder/commit/03e43d1830bcc50c0c7bd6f6ee6c26543e8233be))
* **AppImage:** When unpacking the AppDir from the AppImage, then AppRun is not working correctly ([1e6df67](https://github.com/electron-userland/electron-builder/commit/1e6df674d35891801b310b8eafa407648b5689a8)), closes [#1289](https://github.com/electron-userland/electron-builder/issues/1289)
* Appx name changed ([dd0b208](https://github.com/electron-userland/electron-builder/commit/dd0b2080db74541b65712cac5a331daea99cacfc)), closes [#1650](https://github.com/electron-userland/electron-builder/issues/1650)
* **appx:** App sandbox not enabled (ITMS-90296) ([#4244](https://github.com/electron-userland/electron-builder/issues/4244)) ([e48681e](https://github.com/electron-userland/electron-builder/commit/e48681eeee6a48cf68deb6a0a0f1c5c13507d870))
* **appx:** Apps are not allowed to have a Version with a revision number other than zero specified in the app manifest ([86cd1d9](https://github.com/electron-userland/electron-builder/commit/86cd1d988dfc5394cebeb923b3810c6bafb2bd88)), closes [#2979](https://github.com/electron-userland/electron-builder/issues/2979)
* **appx:** AppX build fails ([9e9ed4f](https://github.com/electron-userland/electron-builder/commit/9e9ed4f0b0df9933590f867c907d5e3f71787686)), closes [#1515](https://github.com/electron-userland/electron-builder/issues/1515)
* **appx:** Command to create self signed certificate has changed ([184781f](https://github.com/electron-userland/electron-builder/commit/184781f2f1c5680298df936c1e2231617969091f)), closes [#1980](https://github.com/electron-userland/electron-builder/issues/1980)
* **appx:** Default rfc3161TimeStampServer to http://timestamp.digicert.com ([#5147](https://github.com/electron-userland/electron-builder/issues/5147)) ([34d1752](https://github.com/electron-userland/electron-builder/commit/34d17524e257721df07018943bc50b9a4a24e7e6))
* **appx:** Invalid code signing tool path when building for windows 10 arm64 ([#4879](https://github.com/electron-userland/electron-builder/issues/4879)) ([d898c4e](https://github.com/electron-userland/electron-builder/commit/d898c4e99ad2b917d7aafe6bcba2d2404e872e03))
* **appx:** Update `identityName` validation for windows 10 ([#8203](https://github.com/electron-userland/electron-builder/issues/8203)) ([66d6d6c](https://github.com/electron-userland/electron-builder/commit/66d6d6c73776b8a62ec30d569bf68c0f1eb83ce2))
* Arch & pacman use i686 instead of i386 and pkg.tar.xz ([#1148](https://github.com/electron-userland/electron-builder/issues/1148)) ([5fe94ee](https://github.com/electron-userland/electron-builder/commit/5fe94eede8b033db5bf67144ecb3c8ec72fcd920))
* **archive:** compute safe artifact name using standard util ([b3f9a13](https://github.com/electron-userland/electron-builder/commit/b3f9a135e80503ab3148bbe0e9ed154aec4a2363)), closes [#2984](https://github.com/electron-userland/electron-builder/issues/2984)
* Arguments aren't passed to Electron with portable target ([4948bd6](https://github.com/electron-userland/electron-builder/commit/4948bd6cd3232bba1a3eb14241791782c8a386a7)), closes [#1410](https://github.com/electron-userland/electron-builder/issues/1410)
* **arm64:** fix pacman build, pacman & rpm artifact names ([#5304](https://github.com/electron-userland/electron-builder/issues/5304)) ([069eba1](https://github.com/electron-userland/electron-builder/commit/069eba17fdbe5f33a78117f79b5f9f5e90a941b6))
* **arm64:** set RPM architecture as `aarch64` in name ([#7466](https://github.com/electron-userland/electron-builder/issues/7466)) ([1342f87](https://github.com/electron-userland/electron-builder/commit/1342f872f98229cf6c31069253fcf0f435bfd9df))
* armv7l should be set as arm for node gyp ([d649815](https://github.com/electron-userland/electron-builder/commit/d649815e62c44e60fed624077464711cb3cf5462)), closes [#2862](https://github.com/electron-userland/electron-builder/issues/2862)
* artifactName for portable ([8f6247a](https://github.com/electron-userland/electron-builder/commit/8f6247a6227f9a11882462a25ca8ec4f3d7a76d5)), closes [#1340](https://github.com/electron-userland/electron-builder/issues/1340)
* artifactName is not work as expected for zip/appimage ([ba999af](https://github.com/electron-userland/electron-builder/commit/ba999af2c619e8989ec76a0f80decc890097889a)), closes [#2258](https://github.com/electron-userland/electron-builder/issues/2258)
* artifactName option does not work in build section ([6224060](https://github.com/electron-userland/electron-builder/commit/622406055b042bcd681adcc501dff56331dd99c5)), closes [#1262](https://github.com/electron-userland/electron-builder/issues/1262)
* Asar: false, causing exception on app startup with v16.4.0 ([7c6b4ab](https://github.com/electron-userland/electron-builder/commit/7c6b4abe4586eb849f3c387f355cec2fabb2c783)), closes [#1409](https://github.com/electron-userland/electron-builder/issues/1409)
* asarUnpack unpacks parent directory when file is specified ([82f16d1](https://github.com/electron-userland/electron-builder/commit/82f16d1b3d6fe163d1f1c52e5a9d05717e0e03b9)), closes [#1071](https://github.com/electron-userland/electron-builder/issues/1071)
* Attempt dynamically importing hook as a module if package.json `type=module`, if fail, fallback to default `require` ([#8042](https://github.com/electron-userland/electron-builder/issues/8042)) ([63a0044](https://github.com/electron-userland/electron-builder/commit/63a00443cf4bae9d7406f7e879ea607632da08b8))
* attempting to wrap all `hdiutil`'s in a common retry mechanism for CI stability ([#8135](https://github.com/electron-userland/electron-builder/issues/8135)) ([c2392de](https://github.com/electron-userland/electron-builder/commit/c2392de71a8f7abc092a00452eac63dd24b34e88))
* auto-update powershell script requires reset of `PSModulePath` ([#8051](https://github.com/electron-userland/electron-builder/issues/8051)) ([48603ba](https://github.com/electron-userland/electron-builder/commit/48603ba09dc7103849a2975799c19068fd08fc07))
* **auto-updater:** Autoupdates to lower version with allowPrerelease=true using GitHub releases ([36fc3db](https://github.com/electron-userland/electron-builder/commit/36fc3db84a4a76a14938dfe7700f4472e455c8fc)), closes [#1497](https://github.com/electron-userland/electron-builder/issues/1497)
* **auto-updater:** do not require app-update.yml file ([c03d98f](https://github.com/electron-userland/electron-builder/commit/c03d98fc4a00672697024c3fc7d84329f8d9da5c))
* **auto-updater:** handle errors during emit ([ef9b5a6](https://github.com/electron-userland/electron-builder/commit/ef9b5a6f152a526aa82d34a99108edfc80712630)), closes [#1310](https://github.com/electron-userland/electron-builder/issues/1310)
* **auto-updater:** Log the raw version string ([#4947](https://github.com/electron-userland/electron-builder/issues/4947)) ([8f99057](https://github.com/electron-userland/electron-builder/commit/8f990576f58e50351cb3abdfdb577690d02145f8))
* **auto-updater:** Race condition during Application Quit ([#2746](https://github.com/electron-userland/electron-builder/issues/2746)) ([1df5d98](https://github.com/electron-userland/electron-builder/commit/1df5d9812c692beee33796fb71080449af8f83ff)), closes [#2745](https://github.com/electron-userland/electron-builder/issues/2745)
* **auto-updater:** respect vPrefixedTagName for auto update ([624311b](https://github.com/electron-userland/electron-builder/commit/624311b8ca0fe7a6ce77afb849f71fe02d05bd2c)), closes [#1417](https://github.com/electron-userland/electron-builder/issues/1417)
* **auto-updater:** use updateInfo.path as AppImage installer name ([#2722](https://github.com/electron-userland/electron-builder/issues/2722)) ([8233eae](https://github.com/electron-userland/electron-builder/commit/8233eae12518e59465052df39999158537b14dd5)), closes [#2672](https://github.com/electron-userland/electron-builder/issues/2672)
* Automatic unpack detection in scoped packages unpacks the entire scope ([3558b22](https://github.com/electron-userland/electron-builder/commit/3558b22e7a54e30d47decb7c4530f4747af34986)), closes [#1540](https://github.com/electron-userland/electron-builder/issues/1540)
* automatically regenerate schema if any config option changes in app-builder-lib ([51f5d49](https://github.com/electron-userland/electron-builder/commit/51f5d4915c4aa69f3253a41e1d7b4ab9f2328732))
* avoid delay due to powershell.exe waiting for input ([#2546](https://github.com/electron-userland/electron-builder/issues/2546)) ([ad6b285](https://github.com/electron-userland/electron-builder/commit/ad6b2852a34b7bd1cb61c1f44853af350d580916)), closes [#2535](https://github.com/electron-userland/electron-builder/issues/2535)
* binary detection signing ([#5493](https://github.com/electron-userland/electron-builder/issues/5493)) ([a6e86b5](https://github.com/electron-userland/electron-builder/commit/a6e86b593048b4eb3047b7c3a54d02d0521b02d2)), closes [#5465](https://github.com/electron-userland/electron-builder/issues/5465)
* build command should accept arg `--arm64` ([4bcdcad](https://github.com/electron-userland/electron-builder/commit/4bcdcad560daca1b764e6c89b944ff2556e9f59b)), closes [#2801](https://github.com/electron-userland/electron-builder/issues/2801)
* build fails with istextorbinary error stacktrace ([#5668](https://github.com/electron-userland/electron-builder/issues/5668)) ([#5851](https://github.com/electron-userland/electron-builder/issues/5851)) ([1011919](https://github.com/electron-userland/electron-builder/commit/10119197292c74234e76bdfba011ae2d7579dc85))
* Build with prepackaged app doesn't do anything for mac [#1284](https://github.com/electron-userland/electron-builder/issues/1284) ([0be724d](https://github.com/electron-userland/electron-builder/commit/0be724d7650ce9529603cf439f7877fbd0202e16))
* **builder-util-runtime:** fix description when request 404 ([#3964](https://github.com/electron-userland/electron-builder/issues/3964)) ([9087f4f](https://github.com/electron-userland/electron-builder/commit/9087f4ff368068ff80ec5f684c4800c9bdda83cd))
* **builder-util:** enable proxy handling in NodeHttpExecutor ([#6410](https://github.com/electron-userland/electron-builder/issues/6410)) ([#6286](https://github.com/electron-userland/electron-builder/issues/6286)) ([#5906](https://github.com/electron-userland/electron-builder/issues/5906)) ([04a8435](https://github.com/electron-userland/electron-builder/commit/04a84352b2b3fbb3c54533a8428bfd103df0af21))
* **builder-util:** Retry flaky builder operations ([b03f2c1](https://github.com/electron-userland/electron-builder/commit/b03f2c1bf32b87f5b37829ef9c774acae96c232e)), closes [#4657](https://github.com/electron-userland/electron-builder/issues/4657)
* Building Linux AppImage in >19.33 sometimes fails with tar error "file changed as we read it ([9eaacd4](https://github.com/electron-userland/electron-builder/commit/9eaacd4423789464c253596467ef2be9a1faa43e)), closes [#2187](https://github.com/electron-userland/electron-builder/issues/2187)
* building native modules does not fall back to building from source if prebuilt not found ([cd28eb0](https://github.com/electron-userland/electron-builder/commit/cd28eb093f0bf5969ad87c64773cc0714dc8d8ea)), closes [#4016](https://github.com/electron-userland/electron-builder/issues/4016)
* Builds fail on building .deb using packaged fpm on Travis ([037fba6](https://github.com/electron-userland/electron-builder/commit/037fba661a85b9e99515e74a08526db7ed2c3c7e)), closes [#1402](https://github.com/electron-userland/electron-builder/issues/1402)
* cached update validation failing on undefined filename ([#4929](https://github.com/electron-userland/electron-builder/issues/4929)) ([4a9e5ef](https://github.com/electron-userland/electron-builder/commit/4a9e5efedf380053c2dd2abea74d1031348ffd11)), closes [#4928](https://github.com/electron-userland/electron-builder/issues/4928)
* Cannot copy files from parent directory of build output ([7f00714](https://github.com/electron-userland/electron-builder/commit/7f007141332b4f389e8fb7a06e76f46c0608d4ee)), closes [#1482](https://github.com/electron-userland/electron-builder/issues/1482)
* Cannot find module '../blake2s.js' ([3143269](https://github.com/electron-userland/electron-builder/commit/3143269aa2888734f67022576e3c07c0ab5f6e42)), closes [#2210](https://github.com/electron-userland/electron-builder/issues/2210)
* Cannot find module 'electron-builder-http' ([4af210e](https://github.com/electron-userland/electron-builder/commit/4af210e88eb8fa92c104f0093645807783b18238)), closes [#1809](https://github.com/electron-userland/electron-builder/issues/1809)
* Cannot find module 'electron-download-tf' ([c57c52a](https://github.com/electron-userland/electron-builder/commit/c57c52a53867e3351a80f3ea49a3d7fdee395cc4)), closes [#2550](https://github.com/electron-userland/electron-builder/issues/2550)
* Cannot package "asar" as a runtime dependency ([b0656f8](https://github.com/electron-userland/electron-builder/commit/b0656f81d42747d5e68cd9a30aa1dddabeaddccf)), closes [#1935](https://github.com/electron-userland/electron-builder/issues/1935)
* certificate regex check the "subject CN=" sub string doing so harsh ([ba3d0bb](https://github.com/electron-userland/electron-builder/commit/ba3d0bb6360b4788b7e3b4e79f44c97d2aa423fa)), closes [#2082](https://github.com/electron-userland/electron-builder/issues/2082) [#2126](https://github.com/electron-userland/electron-builder/issues/2126)
* CFBundleVersion automatically pre appending app version ([9caead3](https://github.com/electron-userland/electron-builder/commit/9caead3a8a7190e44b87bb21cf42b13aad97ee91)), closes [#2088](https://github.com/electron-userland/electron-builder/issues/2088) [#2099](https://github.com/electron-userland/electron-builder/issues/2099)
* Change DEBUG_LOGGING env var for nsis installers as part of `customNsisBinary` config ([#6729](https://github.com/electron-userland/electron-builder/issues/6729)) ([0a30846](https://github.com/electron-userland/electron-builder/commit/0a308469f269dc5294f29f2c422d9936175c0880)), closes [#6715](https://github.com/electron-userland/electron-builder/issues/6715)
* change typed-emitter to tiny-typed-emitter to remove rxjs dependency ([#7633](https://github.com/electron-userland/electron-builder/issues/7633)) ([531a630](https://github.com/electron-userland/electron-builder/commit/531a6309283ea1b2b262817a170e2c030735f8b6))
* channel file name macro doesn't work when channel is latest ([e7a8e33](https://github.com/electron-userland/electron-builder/commit/e7a8e3379036f65afd3c818b8fe40e4263449350)), closes [#1778](https://github.com/electron-userland/electron-builder/issues/1778)
* Check dependencies is run on both devPackageFile and appPackageFile ([252d676](https://github.com/electron-userland/electron-builder/commit/252d67688155cd346d7fa9e678b6e513aa305478)), closes [#2330](https://github.com/electron-userland/electron-builder/issues/2330)
* check homepage/author in the dev metadata ([03df22d](https://github.com/electron-userland/electron-builder/commit/03df22d608783947ddb6b7210cb40e3724e414bb)), closes [#2024](https://github.com/electron-userland/electron-builder/issues/2024) [#1881](https://github.com/electron-userland/electron-builder/issues/1881)
* check null for `isCustomChannel` in GitHubProvider.ts [#7665](https://github.com/electron-userland/electron-builder/issues/7665) ([#7666](https://github.com/electron-userland/electron-builder/issues/7666)) ([441da40](https://github.com/electron-userland/electron-builder/commit/441da40d814d90154ed9b120684e7c1a7d919c52))
* CI unit tests ([#5489](https://github.com/electron-userland/electron-builder/issues/5489)) ([637334d](https://github.com/electron-userland/electron-builder/commit/637334ddbadebf503a45f79adf0b481fcba98679))
* ci-tests ([#5523](https://github.com/electron-userland/electron-builder/issues/5523)) ([ced6e50](https://github.com/electron-userland/electron-builder/commit/ced6e50b93c621de5de07838205d739010e2526b))
* **ci:** GitHub Workflows security hardening ([#7156](https://github.com/electron-userland/electron-builder/issues/7156)) ([50d126e](https://github.com/electron-userland/electron-builder/commit/50d126e43de83e4bb4e6e2c700ddca6a4dbef569))
* CLI fails but exit code is 0 ([2bdfe3a](https://github.com/electron-userland/electron-builder/commit/2bdfe3a618bace888e28672d09064c1e610cc0de)), closes [#2940](https://github.com/electron-userland/electron-builder/issues/2940)
* close file stream when error in httpExecutor ([#7094](https://github.com/electron-userland/electron-builder/issues/7094)) ([1023a93](https://github.com/electron-userland/electron-builder/commit/1023a93e92eaa26bf33b52edda5b22e56ed1ec18))
* codesign all binary-like files ([#5322](https://github.com/electron-userland/electron-builder/issues/5322)) ([27ea1b2](https://github.com/electron-userland/electron-builder/commit/27ea1b2b9ce47a234e82772e09adf0bc7931e0df))
* Codesigning fails when adding Puppeteer as a dependency ([d88236b](https://github.com/electron-userland/electron-builder/commit/d88236b715d3a899f68ae478cc7e16762def4a23)), closes [#2010](https://github.com/electron-userland/electron-builder/issues/2010)
* **codeSign:** signing with "Mac Developer" failed [#1103](https://github.com/electron-userland/electron-builder/issues/1103) ([88682e8](https://github.com/electron-userland/electron-builder/commit/88682e826c36d5032df6fe42c45aa60f9739da35))
* coerce mac.identity from "null" to null ([791b94b](https://github.com/electron-userland/electron-builder/commit/791b94b0d8d3024a71f53a0ef92c63d08821cc32))
* compat with newest @types/node to leverage `OutgoingHttpHeader` for httpExecutor's `RequestHeaders` ([#7806](https://github.com/electron-userland/electron-builder/issues/7806)) ([db424e8](https://github.com/electron-userland/electron-builder/commit/db424e8e876e6ac1985668bf78bd52a02824dd7f))
* compile using electron-compile not in place, but using cache ([08893e3](https://github.com/electron-userland/electron-builder/commit/08893e350e296c28fc928bdd59120c47babec9b2)), closes [#807](https://github.com/electron-userland/electron-builder/issues/807)
* compiler error and test updates ([#5449](https://github.com/electron-userland/electron-builder/issues/5449)) ([0dec1b8](https://github.com/electron-userland/electron-builder/commit/0dec1b8c198f1f9ca0124649883945ba561d11d3))
* config on command must coerce string ([faba9e3](https://github.com/electron-userland/electron-builder/commit/faba9e365a0a4d2402d91ca9bd5a5288cb78f0f7)), closes [#4086](https://github.com/electron-userland/electron-builder/issues/4086)
* **config:** use json5 parser for json5 build configs ([94d89eb](https://github.com/electron-userland/electron-builder/commit/94d89ebea559d57eb7b566650b173b53885be8e4)), closes [#1569](https://github.com/electron-userland/electron-builder/issues/1569) [#1578](https://github.com/electron-userland/electron-builder/issues/1578)
* console log data for electron-updater blockmaps are far too large ([#6143](https://github.com/electron-userland/electron-builder/issues/6143)) ([ae363e5](https://github.com/electron-userland/electron-builder/commit/ae363e51957d0abfc7d848f51aa23c7e5faf5f33))
* correct "to" support in the files for asar ([ffe9d54](https://github.com/electron-userland/electron-builder/commit/ffe9d54ad0353b91c0d9f54f27cdfbe52a92e27c)), closes [#2107](https://github.com/electron-userland/electron-builder/issues/2107)
* correct electron-updater version check ([f26f14d](https://github.com/electron-userland/electron-builder/commit/f26f14d4bf1bf28d4d258638c5759b59833cadb3))
* correct electron-updater version check ([1fda6f5](https://github.com/electron-userland/electron-builder/commit/1fda6f53104946b896cf1365ce940d0e1b84c865))
* correctly compute publisher name using openssl on posix platfoms ([84c512f](https://github.com/electron-userland/electron-builder/commit/84c512f6faec2a4d04b95d66751976fbd5d478a9)), closes [#1773](https://github.com/electron-userland/electron-builder/issues/1773)
* correctly copy sub node module (not to top-level dir) ([fe7d56c](https://github.com/electron-userland/electron-builder/commit/fe7d56c13a36439793d6599bb6f163a4f2611440))
* correctly pack cache folder for electron-compile ([419cf91](https://github.com/electron-userland/electron-builder/commit/419cf91783bd18db2d5b7eb19cbaf5afafe0c361)), closes [#1465](https://github.com/electron-userland/electron-builder/issues/1465)
* CSC_LINK is ignored on Windows ([e5e0782](https://github.com/electron-userland/electron-builder/commit/e5e0782c149df392417cf2a8eb588b901b1764bd)), closes [#2639](https://github.com/electron-userland/electron-builder/issues/2639)
* **deb:** add libxss1 to depends by default ([897fcf2](https://github.com/electron-userland/electron-builder/commit/897fcf29d6b9b5e44ade3ccda138f2cd9507216a))
* **deb:** Build on an armv7l architecture ends up with "Cannot set machine from deb_arch 'armv7l' ([095a05d](https://github.com/electron-userland/electron-builder/commit/095a05d13eef4bfba15f666a5358b1aa88e8ee10)), closes [#3349](https://github.com/electron-userland/electron-builder/issues/3349)
* **deb:** chmod SUID bit on chrome-sandbox for debs ([#4163](https://github.com/electron-userland/electron-builder/issues/4163)) ([7c2881e](https://github.com/electron-userland/electron-builder/commit/7c2881e52930082136f6e4b7950c3611e0e07100))
* **deb:** deb fails to install on the new Debian Buster ([3bf2091](https://github.com/electron-userland/electron-builder/commit/3bf20914bf946df0e46729ef0bf586d9f3f6a423)), closes [#4033](https://github.com/electron-userland/electron-builder/issues/4033)
* **deb:** do not use quotes for safe Exec ([d7aa12d](https://github.com/electron-userland/electron-builder/commit/d7aa12dec88aa60eb721e96e2a5ce248423c459a)), closes [#2759](https://github.com/electron-userland/electron-builder/issues/2759)
* **debian:** corrected path for binary in package ([#4002](https://github.com/electron-userland/electron-builder/issues/4002)) ([f1e9456](https://github.com/electron-userland/electron-builder/commit/f1e9456bc4acb0707bc397e021796ee74a44c8e8))
* **deb:** only execute `update-desktop-database` and `update-mime-database` when exists on the system ([#8067](https://github.com/electron-userland/electron-builder/issues/8067)) ([18340ee](https://github.com/electron-userland/electron-builder/commit/18340eef6d8e9ee6efbf528508bac7972168bedb))
* **deb:** Unable to build deb for packages with scoped names ([0e83437](https://github.com/electron-userland/electron-builder/commit/0e834377703589a00fa001475b36ec280044172d)), closes [#2963](https://github.com/electron-userland/electron-builder/issues/2963)
* deepAssign error without config ([5d72c10](https://github.com/electron-userland/electron-builder/commit/5d72c1040c9d4dacfe4bfc263c5c9addd1f20ff9)), closes [#1177](https://github.com/electron-userland/electron-builder/issues/1177)
* default the downloaded update file name to `fileInfo.info.url` ([#7597](https://github.com/electron-userland/electron-builder/issues/7597)) ([cd15e16](https://github.com/electron-userland/electron-builder/commit/cd15e161031e180200ab772f01198a5b68fa42fe))
* **deploy:** consolidating versioning commands into package.json ([6066681](https://github.com/electron-userland/electron-builder/commit/6066681077c8ba730155751b83b4550add9b0dcf))
* **deploy:** deactivate husky hooks for automatic versioning PR ([#6041](https://github.com/electron-userland/electron-builder/issues/6041)) ([0d4d305](https://github.com/electron-userland/electron-builder/commit/0d4d3056b440cc45a1f1a15ea4a27c688cb0e96e))
* **deploy:** Fixing zulip send message action ([41d5cae](https://github.com/electron-userland/electron-builder/commit/41d5cae325cba3031bc25148b1ff5927bc441913))
* **deployment:** another fix for "only first artifact is uploaded to GitHub" ([93b4d59](https://github.com/electron-userland/electron-builder/commit/93b4d599c06e2fe6efec6c68608658f45c7fd0fc)), closes [#1133](https://github.com/electron-userland/electron-builder/issues/1133)
* **deployment:** APPVEYOR_REPO_NAME must be used instead of APPVEYOR_ACCOUNT_NAME ([2eb9b1f](https://github.com/electron-userland/electron-builder/commit/2eb9b1f096cc7587c70b531bde5b28e69e7b3086)), closes [#2488](https://github.com/electron-userland/electron-builder/issues/2488)
* **deployment:** Artifacts being published to S3 when they shouldn't be ([b72b9e8](https://github.com/electron-userland/electron-builder/commit/b72b9e87a137f1a8487dd258da358d5a82fdf5e6)), closes [#2708](https://github.com/electron-userland/electron-builder/issues/2708)
* **deployment:** Artifacts still get pushed to github releases marked as published ([3987b06](https://github.com/electron-userland/electron-builder/commit/3987b069afc00515b98f09999375bd8ba01baeed)), closes [#1197](https://github.com/electron-userland/electron-builder/issues/1197)
* **deployment:** Bintray publisher doesn't escape filename ([d0487b0](https://github.com/electron-userland/electron-builder/commit/d0487b014ed9a933aebe3f3031f95d7d98c84441)), closes [#2600](https://github.com/electron-userland/electron-builder/issues/2600)
* **deployment:** change date comparison logic to use number of millseconds since 1/1/1970 for publishedAt ([#2074](https://github.com/electron-userland/electron-builder/issues/2074)) ([#2077](https://github.com/electron-userland/electron-builder/issues/2077)) ([1ac5de6](https://github.com/electron-userland/electron-builder/commit/1ac5de6bdfabf9452b788c3c55586ef87502dfbd))
* **deployment:** check for errors ([4c71fc0](https://github.com/electron-userland/electron-builder/commit/4c71fc02319c5f5c2fcb32593fe58c28e526a9c6))
* **deployment:** clear message why artifact is not uploaded ([1ecf290](https://github.com/electron-userland/electron-builder/commit/1ecf290497f1e176db754e0147bab965c2e6ed03)), closes [#2234](https://github.com/electron-userland/electron-builder/issues/2234) [#2275](https://github.com/electron-userland/electron-builder/issues/2275)
* **deployment:** different channels for different publish providers ([81fd398](https://github.com/electron-userland/electron-builder/commit/81fd398275774579b29095d27ad3fb14478eee50))
* **deployment:** disable automatic detection for S3 ([c4744af](https://github.com/electron-userland/electron-builder/commit/c4744afe7d12df570ba3012ee74336f9396472e7)), closes [#1334](https://github.com/electron-userland/electron-builder/issues/1334)
* **deployment:** do not fail if cannot resolve effective S3 publish config if not publish will be not performed ([e5d97bc](https://github.com/electron-userland/electron-builder/commit/e5d97bc7cc4d8b651e10c0be7c7bbfcada02c8c8)), closes [#2670](https://github.com/electron-userland/electron-builder/issues/2670)
* **deployment:** do not overwrite update info file for other provider ([ee82371](https://github.com/electron-userland/electron-builder/commit/ee8237144b744525d2d05db992ccf965a21b349c)), closes [#1814](https://github.com/electron-userland/electron-builder/issues/1814)
* **deployment:** electron-builder generic repository "publishing to null" ([8a31966](https://github.com/electron-userland/electron-builder/commit/8a3196621a63a3701c22e09946b27db67104e3e0)), closes [#2170](https://github.com/electron-userland/electron-builder/issues/2170)
* **deployment:** electron-builder uploads lastest.yml and install.exe seperately on GitHub ([07af748](https://github.com/electron-userland/electron-builder/commit/07af748a2d2ecb2dedb595b1a95434e1a6cebe86)), closes [#1996](https://github.com/electron-userland/electron-builder/issues/1996)
* **deployment:** ensure that we await update meta files publishing ([b5d4d66](https://github.com/electron-userland/electron-builder/commit/b5d4d660e9a5d8450b18f8003b15075c4f5e83fa))
* **deployment:** Error on CI build when GH_TOKEN not set for external PRs ([ee32575](https://github.com/electron-userland/electron-builder/commit/ee3257547daec1ea9a4f5d8dc73c8fd7b17fa0be)), closes [#1178](https://github.com/electron-userland/electron-builder/issues/1178)
* **deployment:** latest.yml is completely empty when uploaded to S3 bucket ([4b25ca2](https://github.com/electron-userland/electron-builder/commit/4b25ca2ea5f5217c2dcb32fbf91426bdb68c0cfb)), closes [#1582](https://github.com/electron-userland/electron-builder/issues/1582)
* **deployment:** log about uploading if non TTY stream ([4546b1c](https://github.com/electron-userland/electron-builder/commit/4546b1ca7c5dfdd6f6432d9340f1f5744922226d))
* **deployment:** Mac updates breaking change ([f664497](https://github.com/electron-userland/electron-builder/commit/f6644978e841c430cfb220b4b4ddbd5990cd1aa6)), closes [#2276](https://github.com/electron-userland/electron-builder/issues/2276)
* **deployment:** NSIS Web Installer update info is not generated [#1207](https://github.com/electron-userland/electron-builder/issues/1207) ([9f7c825](https://github.com/electron-userland/electron-builder/commit/9f7c8255b2989544f9a100cbac59193a2cc9a476))
* **deployment:** onTagOrDraft should not publish if no tag and no draft ([c67705f](https://github.com/electron-userland/electron-builder/commit/c67705feaa635d331c967cb38005b79e8f53aa8e)), closes [#1835](https://github.com/electron-userland/electron-builder/issues/1835)
* **deployment:** prevent latest-${os}.{yml,json} files from being rewritten ([9832788](https://github.com/electron-userland/electron-builder/commit/983278892889c578a55adc31ee3b948389e4aece)), closes [#1772](https://github.com/electron-userland/electron-builder/issues/1772) [#1775](https://github.com/electron-userland/electron-builder/issues/1775)
* **deployment:** Problem overriding the publish channel ([0b4ffa4](https://github.com/electron-userland/electron-builder/commit/0b4ffa4f27c17b9368dcd0ebef298dd18378d75e)), closes [#1847](https://github.com/electron-userland/electron-builder/issues/1847)
* **deployment:** properly check options.draft value in gitHubPublisher ([#2072](https://github.com/electron-userland/electron-builder/issues/2072)) ([#2076](https://github.com/electron-userland/electron-builder/issues/2076)) ([31d64f8](https://github.com/electron-userland/electron-builder/commit/31d64f8b23b713754bdf615f62b2d4ff1a4cd46e))
* **deployment:** Publish update meta info files only when artifacts were fully uploaded ([b596abf](https://github.com/electron-userland/electron-builder/commit/b596abf228f8d19e7329280bf2c71b1f4874ae2b)), closes [#1833](https://github.com/electron-userland/electron-builder/issues/1833)
* **deployment:** Publishing always fails on circleci [#1303](https://github.com/electron-userland/electron-builder/issues/1303) ([#1304](https://github.com/electron-userland/electron-builder/issues/1304)) ([81b7e46](https://github.com/electron-userland/electron-builder/commit/81b7e46f73cfcc48b6cd01323a0a03b697bded25))
* **deployment:** Repeat upload when it fails with ECONNRESET error ([#2296](https://github.com/electron-userland/electron-builder/issues/2296)) ([2752074](https://github.com/electron-userland/electron-builder/commit/2752074644db7036548c026b496f457651d8257c))
* **deployment:** respect releaseDate ([cc9f1d6](https://github.com/electron-userland/electron-builder/commit/cc9f1d6f092ee6f55e8c2d089ddd9fad56bfb74e)), closes [#2727](https://github.com/electron-userland/electron-builder/issues/2727)
* **deployment:** s3 publisher md5 integrity ([b57dc8a](https://github.com/electron-userland/electron-builder/commit/b57dc8a9e47a79eaaefb083cf176e4ff365837a0))
* **deployment:** S3 won't upload app files ([4149031](https://github.com/electron-userland/electron-builder/commit/4149031d1dd9ed1b8b89df02e9ec0c1d50e17648)), closes [#1331](https://github.com/electron-userland/electron-builder/issues/1331)
* **deployment:** warn "A release is already published" instead of error ([5d64693](https://github.com/electron-userland/electron-builder/commit/5d64693632469cbd4418d905703bd2dda56a68a8)), closes [#1183](https://github.com/electron-userland/electron-builder/issues/1183)
* **deployment:** warn if artifact will be not uploaded to GitHub because no release ([b960b3f](https://github.com/electron-userland/electron-builder/commit/b960b3f05de9ad0b55b2c0fa5ca6ff4d0c059c61)), closes [#2164](https://github.com/electron-userland/electron-builder/issues/2164)
* **deployment:** warn if cannot resolve repository ([3fa6259](https://github.com/electron-userland/electron-builder/commit/3fa62597ed85090ad1306d7124bf874f6edca726))
* **deployment:** when releasing for macOS & Windows at once, all files get uploaded to path in mac publish config ([c2e656e](https://github.com/electron-userland/electron-builder/commit/c2e656e68db55e695f1a715add9e5ce1aa777eb6)), closes [#1323](https://github.com/electron-userland/electron-builder/issues/1323)
* **deploy:** remove zulip release message ([695f89a](https://github.com/electron-userland/electron-builder/commit/695f89a7b18e100c15ac47f837ae10ee600710ac))
* **deploy:** Removing schema generation since it doesn't compile during release ([7e28c11](https://github.com/electron-userland/electron-builder/commit/7e28c11ec894c9ce7664a2ea3bfdb3e96f09d983))
* **deploy:** Update package.json script name ([e22fc16](https://github.com/electron-userland/electron-builder/commit/e22fc16cd196ab0f3cc7b2f9bdaae237e64121a8))
* **deps:** Update 7zip-bin to support Windows on ARM ([#7829](https://github.com/electron-userland/electron-builder/issues/7829)) ([1af7447](https://github.com/electron-userland/electron-builder/commit/1af7447edf47303de03ca2924727c78118161c60))
* **deps:** update dependency @electron/notarize to v2.2.1 ([#8029](https://github.com/electron-userland/electron-builder/issues/8029)) ([2248134](https://github.com/electron-userland/electron-builder/commit/2248134068e035ec76fe696385bb467a94dd384d))
* **deps:** update dependency @electron/notarize to v2.3.0 ([#8114](https://github.com/electron-userland/electron-builder/issues/8114)) ([0e8e7f6](https://github.com/electron-userland/electron-builder/commit/0e8e7f6524f0f00b28348fc47c57db8f801692b1))
* **deps:** update dependency @electron/universal to v1.5.1 ([#8030](https://github.com/electron-userland/electron-builder/issues/8030)) ([db3b18e](https://github.com/electron-userland/electron-builder/commit/db3b18e799a6579bbc36c41b3125a062ebf075ec))
* **deps:** update dependency @electron/universal to v2 ([#8115](https://github.com/electron-userland/electron-builder/issues/8115)) ([f8602aa](https://github.com/electron-userland/electron-builder/commit/f8602aa222ad8b85eb0b91a11f359580203ba024))
* **deps:** update dependency ejs to v3.1.10 [security] ([#8192](https://github.com/electron-userland/electron-builder/issues/8192)) ([77f9774](https://github.com/electron-userland/electron-builder/commit/77f977435c99247d5db395895618b150f5006e8f))
* **deps:** update dependency tar to v6.2.1 [security] ([#8171](https://github.com/electron-userland/electron-builder/issues/8171)) ([393f140](https://github.com/electron-userland/electron-builder/commit/393f140459dc4a7d6008750dc48de83c8e8d33a7))
* detect electron-compile in the dev deps ([0b8bff4](https://github.com/electron-userland/electron-builder/commit/0b8bff419750cea9f3c0cf379be27c159a1d6261))
* DigitalOcean Spaces doesn't support multiple range requests ([#4690](https://github.com/electron-userland/electron-builder/issues/4690)) ([f5cc292](https://github.com/electron-userland/electron-builder/commit/f5cc29248096d4bdd2924e5a6d16772aaeb87dd9))
* directories.output is ignored when building .dmg for a prepackaged app ([3e2798f](https://github.com/electron-userland/electron-builder/commit/3e2798fb921adebda9ef43735609f1cf6ec48a21)), closes [#1308](https://github.com/electron-userland/electron-builder/issues/1308)
* disable AppImage target by default if build on Windows ([4f05bad](https://github.com/electron-userland/electron-builder/commit/4f05bad648c95befccdd14d9e60179ab1ec71fcb))
* disable broken test, needs further debugging. It's broken on all previous versions of electron-builder, seems MacOS related ([ac6d887](https://github.com/electron-userland/electron-builder/commit/ac6d8875463cba89c02a35baf347a1c2f76697e9))
* disable broken test, needs further debugging. It's broken on all previous versions of electron-builder, seems MacOS related ([01a9c08](https://github.com/electron-userland/electron-builder/commit/01a9c08f2ddbd8d1b96c58089771a93fd695c753))
* disable broken test, needs further debugging. It's broken on all previous versions of electron-builder, seems MacOS related ([dbd1fc5](https://github.com/electron-userland/electron-builder/commit/dbd1fc5510dca1da90a199fb34407573e464dba3))
* display product names with an `&` properly ([#7831](https://github.com/electron-userland/electron-builder/issues/7831)) ([6e41480](https://github.com/electron-userland/electron-builder/commit/6e41480e6221693f6fec46ae813d513935e05f66))
* **dmb:** fix injecting dmg license with dmg-license package instead of deprecated Rez tool ([#5424](https://github.com/electron-userland/electron-builder/issues/5424)) ([9e7b3c3](https://github.com/electron-userland/electron-builder/commit/9e7b3c39ad3c59b88d78e3f5a5948cf4ced3f92a))
* DMG assembly on Apple Silicon ([#4606](https://github.com/electron-userland/electron-builder/issues/4606)) ([#5724](https://github.com/electron-userland/electron-builder/issues/5724)) ([469b85f](https://github.com/electron-userland/electron-builder/commit/469b85fa2a2660eaba1eafbbd528abec2b1f50d9))
* **dmg-builder:** exec python fail on Macos12.3 ([#6789](https://github.com/electron-userland/electron-builder/issues/6789)) ([76f3a1d](https://github.com/electron-userland/electron-builder/commit/76f3a1d102be04c0517a08826b8b1337478f766d))
* **dmg-builder:** fix dmg-license is incompatible with linux and win32 ([#5473](https://github.com/electron-userland/electron-builder/issues/5473)) ([2b116d1](https://github.com/electron-userland/electron-builder/commit/2b116d138e9effa3314fe6ff4474b639f7fddf47))
* **dmg-builder:** Support python 3 since python 2 was removed from MacOS 12.3 ([#6617](https://github.com/electron-userland/electron-builder/issues/6617)) ([2def112](https://github.com/electron-userland/electron-builder/commit/2def112bc1ac42046b921206825871b82ebf0955)), closes [#6606](https://github.com/electron-userland/electron-builder/issues/6606)
* **dmg-builder:** the "import" unbound issue for python 2/3 ([#6672](https://github.com/electron-userland/electron-builder/issues/6672)) ([3a4b64a](https://github.com/electron-userland/electron-builder/commit/3a4b64abb58f01e8a80e496b6c4681455b2434ca))
* dmg-license optional dependency ([#6244](https://github.com/electron-userland/electron-builder/issues/6244)) ([8ccb2da](https://github.com/electron-userland/electron-builder/commit/8ccb2da5d4c641b971f6a7403d3b2e3a3b844a05))
* dmg-license-dependency ([#6248](https://github.com/electron-userland/electron-builder/issues/6248)) ([f359035](https://github.com/electron-userland/electron-builder/commit/f3590355c61dab05a6c92c5951aae8e59503d693))
* dmg/pkg in the out dir, not in the subdir mac ([0bba4fe](https://github.com/electron-userland/electron-builder/commit/0bba4fe51d7f6b1e7f584e81883f27140f12c3f7))
* **dmg:** Adding ‘sign’ dmg option to scheme.json to fix build errors ([#3941](https://github.com/electron-userland/electron-builder/issues/3941)) ([766ecff](https://github.com/electron-userland/electron-builder/commit/766ecff197866355770dc80c1a12caf6600015eb))
* **dmg:** adding 10% on size for temporary dmg used in hdiutil  ([#4171](https://github.com/electron-userland/electron-builder/issues/4171)) ([1d21620](https://github.com/electron-userland/electron-builder/commit/1d2162093f6639165934849a073144832541bfbe)), closes [#3301](https://github.com/electron-userland/electron-builder/issues/3301)
* **dmg:** Building DMG hangs on OSX High Sierra ([db7092b](https://github.com/electron-userland/electron-builder/commit/db7092bd83fd4feea292e4ac3a850b2481f6898a)), closes [#2115](https://github.com/electron-userland/electron-builder/issues/2115)
* **dmg:** Can't locate Mac/Finder/DSStore.pm in @INC ([8d0e230](https://github.com/electron-userland/electron-builder/commit/8d0e2307688d6db19ed0646aa861a58d6bdae762)), closes [#1079](https://github.com/electron-userland/electron-builder/issues/1079)
* **dmg:** cannot build DMG on macOS 10.15 ([8f099f5](https://github.com/electron-userland/electron-builder/commit/8f099f53421fde604105208d28edec67d8358c6c)), closes [#3990](https://github.com/electron-userland/electron-builder/issues/3990)
* **dmg:** check path to be not empty to preserve old behavior ([a7092fc](https://github.com/electron-userland/electron-builder/commit/a7092fcff3ad0ac975257d4cd9f2761c02eac7aa)), closes [#2147](https://github.com/electron-userland/electron-builder/issues/2147)
* **dmg:** correctly encode Unicode characters in DMG licenses ([#4428](https://github.com/electron-userland/electron-builder/issues/4428)) ([ba92854](https://github.com/electron-userland/electron-builder/commit/ba92854eaaa5931a569f52bf77269934105fc161))
* **dmg:** custom licenseButton support is broken ([d4d52ce](https://github.com/electron-userland/electron-builder/commit/d4d52ce3f4c7b861da4fe82ba9558e0bdf2ce221))
* **dmg:** DMG License RTF ([92cd702](https://github.com/electron-userland/electron-builder/commit/92cd702dfaff341079aace5f8abd93d6dfdb9c55))
* **dmg:** Escaping special characters in DMG entries ([#5987](https://github.com/electron-userland/electron-builder/issues/5987)) ([c368f62](https://github.com/electron-userland/electron-builder/commit/c368f62b3aa63962826c38d65d0ad43aad9ec7e1))
* **dmg:** license ([5a163df](https://github.com/electron-userland/electron-builder/commit/5a163df78c69ea7f7429a3232c2355c0e9fd62a5)), closes [#1491](https://github.com/electron-userland/electron-builder/issues/1491)
* **dmg:** move hidden directories out of view ([452085b](https://github.com/electron-userland/electron-builder/commit/452085b7ba9034e0a7a9f6664de1b749ea172bc6)), closes [#1121](https://github.com/electron-userland/electron-builder/issues/1121)
* **dmg:** multi-language license encoding ([56e5786](https://github.com/electron-userland/electron-builder/commit/56e5786657de09442fd737f7111294365967e01f)), closes [#1982](https://github.com/electron-userland/electron-builder/issues/1982)
* **dmg:** Multiple license files don't seem to work for dmg ([4a2c599](https://github.com/electron-userland/electron-builder/commit/4a2c599d1512bf9054d21874f8e9a98861750bfa)), closes [#1982](https://github.com/electron-userland/electron-builder/issues/1982)
* **dmg:** new version of mac_alias ([#5460](https://github.com/electron-userland/electron-builder/issues/5460)) ([a8acb58](https://github.com/electron-userland/electron-builder/commit/a8acb583bc3c6fb1ff0dca2f07d1eefa26b1780a))
* **dmg:** pass -ov flag to overwrite existing dmg ([f4398a7](https://github.com/electron-userland/electron-builder/commit/f4398a7225c88880f9dee755b6c14699adf91c27)), closes [#1308](https://github.com/electron-userland/electron-builder/issues/1308)
* **dmg:** require().split is not a function ([dfcd010](https://github.com/electron-userland/electron-builder/commit/dfcd010c1e3d7593404832fa8c4c53baddaa8a3b)), closes [#4639](https://github.com/electron-userland/electron-builder/issues/4639)
* **dmg:** Unable to build with custom path ([3bf8c93](https://github.com/electron-userland/electron-builder/commit/3bf8c9311657ce71211c35af39a575ae3587ba58)), closes [#847](https://github.com/electron-userland/electron-builder/issues/847) [#1054](https://github.com/electron-userland/electron-builder/issues/1054)
* do not chmod for 7za when `process.env.USE_SYSTEM_7ZA` is true ([#8152](https://github.com/electron-userland/electron-builder/issues/8152)) ([a999da4](https://github.com/electron-userland/electron-builder/commit/a999da48480b5024d97c3028a655bb33b00fc3bc))
* do not copy electronDist using hard links ([c04dd20](https://github.com/electron-userland/electron-builder/commit/c04dd2071c50a76e3503d78d45bd1faa30cef0df)), closes [#1670](https://github.com/electron-userland/electron-builder/issues/1670)
* do not copy nested node modules to root ([2803086](https://github.com/electron-userland/electron-builder/commit/280308663b033c1d0ba25af825096a8cb1c6bb6a)), closes [#3039](https://github.com/electron-userland/electron-builder/issues/3039) [#3047](https://github.com/electron-userland/electron-builder/issues/3047)
* do not exclude *.h files from node_modules ([3763f31](https://github.com/electron-userland/electron-builder/commit/3763f312b8bf1c1c22c3784fb28c4e80a146ea32)), closes [#2852](https://github.com/electron-userland/electron-builder/issues/2852)
* do not fail if cannot rebuild optional dep ([f67b7d2](https://github.com/electron-userland/electron-builder/commit/f67b7d2edd1dbdc3ac9b7008849b21808e07bff5)), closes [#1075](https://github.com/electron-userland/electron-builder/issues/1075)
* do not remove GitHub's releaseType attribute from the publish configuration ([7f529ff](https://github.com/electron-userland/electron-builder/commit/7f529fff4983b781c78e74352aebe71b2e75a65e)), closes [#2971](https://github.com/electron-userland/electron-builder/issues/2971) [#2994](https://github.com/electron-userland/electron-builder/issues/2994)
* Do not run node modules file matcher when node_modules are handled externally ([#2975](https://github.com/electron-userland/electron-builder/issues/2975)) ([ac890d1](https://github.com/electron-userland/electron-builder/commit/ac890d18962aba373c5f4d7194bcd4d703f3d230))
* do not show MessageBox when app was killed (on not running) ([#6043](https://github.com/electron-userland/electron-builder/issues/6043)) ([0561674](https://github.com/electron-userland/electron-builder/commit/0561674b6c491ee1cfa0ba838f5c5d59ce205124))
* do not strip "bugs" field from main package.json ([58933e0](https://github.com/electron-userland/electron-builder/commit/58933e03e4264934d3c7b0060af7b49b8584e79a)), closes [#2606](https://github.com/electron-userland/electron-builder/issues/2606)
* do not try to merge config over the same config ([1243388](https://github.com/electron-userland/electron-builder/commit/12433887caeb63dec78a550a1227460e9eee28c9)), closes [#2016](https://github.com/electron-userland/electron-builder/issues/2016)
* do not use optional dependencies because NPM is broken by design ([f4099c6](https://github.com/electron-userland/electron-builder/commit/f4099c66899a6e6419bf352b08f3df868d15fe31)), closes [#2013](https://github.com/electron-userland/electron-builder/issues/2013)
* do not use scoped electron-download ([8c79f60](https://github.com/electron-userland/electron-builder/commit/8c79f605401a7f50726254dba68fc889f76afcde)), closes [#1458](https://github.com/electron-userland/electron-builder/issues/1458)
* **docker:** add missing libcurl3 for osslsigncode ([#1116](https://github.com/electron-userland/electron-builder/issues/1116)) ([f0a553a](https://github.com/electron-userland/electron-builder/commit/f0a553a500a9288271cfbd99bab7be3d05c57d20))
* **docker:** add missing libgconf-2-4 for chromedriver ([#2720](https://github.com/electron-userland/electron-builder/issues/2720)) ([0a343f3](https://github.com/electron-userland/electron-builder/commit/0a343f3fea8a37fcc8d625aaa899f3007e02f0bb))
* **docker:** Docker - wine - bad exe format for rcedit.exe ([920c230](https://github.com/electron-userland/electron-builder/commit/920c2307e277a8e384add788ce848f4f01c781d6))
* **docker:** fix install of wine ([#4622](https://github.com/electron-userland/electron-builder/issues/4622)) ([6f7eb12](https://github.com/electron-userland/electron-builder/commit/6f7eb121c4f478323dbaa32ddfcd1d707e0807f6))
* **docker:** osslsigncode with curl4 ([4e454f8](https://github.com/electron-userland/electron-builder/commit/4e454f8b4390a4bcc38a30f065e0ed1eba2acee9))
* **docker:** Squirrel.Windows requires tzdata package ([#3630](https://github.com/electron-userland/electron-builder/issues/3630)) ([9384e8e](https://github.com/electron-userland/electron-builder/commit/9384e8e8f797ab4a7b5a93e0c7c888f873697262))
* **docker:** upgrade libcurl3 to libcurl4 ([#4479](https://github.com/electron-userland/electron-builder/issues/4479)) ([a215a83](https://github.com/electron-userland/electron-builder/commit/a215a83e7bce553760cb8033f44dcdc31e1b3316)), closes [#4478](https://github.com/electron-userland/electron-builder/issues/4478)
* **docker:** use ubuntu 16 LTS to be able to compile compatible native deps of Electron ([b600e3f](https://github.com/electron-userland/electron-builder/commit/b600e3f33e70c9a0268e727dfb2508b61b61e901))
* **docs/configuration:** broken links ([#7949](https://github.com/electron-userland/electron-builder/issues/7949)) ([98624c9](https://github.com/electron-userland/electron-builder/commit/98624c93ae5063886e82eaa81f67317d5e79f26c))
* **docs/multi-platform-build.md:** broken link of build.sh ([#8193](https://github.com/electron-userland/electron-builder/issues/8193)) ([3a2ccdd](https://github.com/electron-userland/electron-builder/commit/3a2ccdd9483afa3134198b3ef56ba6163b2aaec9))
* **docs:** fix typo in default glob pattern ([#8256](https://github.com/electron-userland/electron-builder/issues/8256)) ([14942b7](https://github.com/electron-userland/electron-builder/commit/14942b70a5da79a5e36e330f64de66ec501b4ac6))
* **docs:** Fixing formatting of code groups and previews ([#6601](https://github.com/electron-userland/electron-builder/issues/6601)) ([b01d522](https://github.com/electron-userland/electron-builder/commit/b01d5225631115f6f301cb113b044fd10ebb5256)), closes [#6597](https://github.com/electron-userland/electron-builder/issues/6597) [#6574](https://github.com/electron-userland/electron-builder/issues/6574)
* **docs:** link to SquirrelWindowsOptions in configuration ([#6724](https://github.com/electron-userland/electron-builder/issues/6724)) ([4eaab19](https://github.com/electron-userland/electron-builder/commit/4eaab1936429ac69dafcc7cfbf53caa85c241a11))
* **docs:** minor grammar/formatting fixes ([#6107](https://github.com/electron-userland/electron-builder/issues/6107)) ([b9b275f](https://github.com/electron-userland/electron-builder/commit/b9b275fff0763faf110a8dcb3c8313963710bbeb))
* **docs:** PlatformSpecificBuildOptions.md broken link ([#7405](https://github.com/electron-userland/electron-builder/issues/7405)) ([ece7f88](https://github.com/electron-userland/electron-builder/commit/ece7f889f93921894cbbcb02b924dc90d793be7c))
* **docs:** typo of docs/generated/NsisOptions.md ([#7120](https://github.com/electron-userland/electron-builder/issues/7120)) ([740c411](https://github.com/electron-userland/electron-builder/commit/740c41146f875feaa730d18f8353b11416dab1e0))
* **docs:** typos in CONTRIBUTING.md ([#7691](https://github.com/electron-userland/electron-builder/issues/7691)) ([6bcea7f](https://github.com/electron-userland/electron-builder/commit/6bcea7f8a449daf9af09095b93bee71e22682488))
* **docs:** update autoupdate docs noting that `channels` work with Github ([#8227](https://github.com/electron-userland/electron-builder/issues/8227)) ([48c5953](https://github.com/electron-userland/electron-builder/commit/48c59535f84cd16fb2e44d71f6b75c25c739b993))
* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* Downgrading nsis to v3.0.4.1 since v3.0.4.2 throws false virus positives ([#6334](https://github.com/electron-userland/electron-builder/issues/6334)) ([#6447](https://github.com/electron-userland/electron-builder/issues/6447)) ([d20bcf0](https://github.com/electron-userland/electron-builder/commit/d20bcf0cea4e4cb49aab08f820131a2d6b083a2c))
* Download update from public Github repo failed on Mac ([16bc53c](https://github.com/electron-userland/electron-builder/commit/16bc53cdc66985fccd85bf81f9afd2c8fac5238b)), closes [#1388](https://github.com/electron-userland/electron-builder/issues/1388)
* Duplicate values during deep assign of extra files ([#7019](https://github.com/electron-userland/electron-builder/issues/7019)) ([98d3a63](https://github.com/electron-userland/electron-builder/commit/98d3a6361d500e85e443ee292529c27f0b4a0b59))
* electron download option `version` must be not required ([2e7ddb9](https://github.com/electron-userland/electron-builder/commit/2e7ddb9db6f13f2a7a7e9d59a865be79af6707d8)), closes [#3077](https://github.com/electron-userland/electron-builder/issues/3077)
* electron expects offset as string, not as a number ([b20166a](https://github.com/electron-userland/electron-builder/commit/b20166a0458553cfa37985839541197d44b69fb4))
* ELECTRON_BUILDER_NSIS_DIR env var setting ([#3068](https://github.com/electron-userland/electron-builder/issues/3068)) ([703a1fb](https://github.com/electron-userland/electron-builder/commit/703a1fb279bd86c34b23410aa8b948858fc97b1a)), closes [#3054](https://github.com/electron-userland/electron-builder/issues/3054)
* **electron-auto-updater:** Checking for updates from github was failing ([3401630](https://github.com/electron-userland/electron-builder/commit/340163009f0e3e5741d7dd46fab3bcaad2259789)), closes [#1038](https://github.com/electron-userland/electron-builder/issues/1038)
* **electron-auto-updater:** queue checkForUpdates ([62e0bcb](https://github.com/electron-userland/electron-builder/commit/62e0bcbb204a05edec12a8f3aa02541308dd691a)), closes [#1045](https://github.com/electron-userland/electron-builder/issues/1045)
* **electron-auto-updater:** uncaught SHA2 checksum mismatch exception ([cb87588](https://github.com/electron-userland/electron-builder/commit/cb8758802eb9a4add13897f366313284799baf82))
* electron-builder 17.5.0, 17.8.0: cannot find module 'debug' ([5835654](https://github.com/electron-userland/electron-builder/commit/5835654e48899d23cb97c7764476f2c314b3707e)), closes [#1564](https://github.com/electron-userland/electron-builder/issues/1564)
* electron-builder install-app-deps does not honor build.directories.app ([6db68be](https://github.com/electron-userland/electron-builder/commit/6db68beb64ca8f3ebfa6e0e2bb53b4d7d420e4c4)), closes [#1721](https://github.com/electron-userland/electron-builder/issues/1721)
* electron-builder loses *.h file ([04f51fc](https://github.com/electron-userland/electron-builder/commit/04f51fc868df7e690dc5ba2517f286c17765e08b)), closes [#1971](https://github.com/electron-userland/electron-builder/issues/1971)
* electron-builder loses *.o file ([970ba66](https://github.com/electron-userland/electron-builder/commit/970ba665fb16535a307ce11884e0c75c083aa88f)), closes [#1971](https://github.com/electron-userland/electron-builder/issues/1971)
* electron-builder loses *.obj file ([723441e](https://github.com/electron-userland/electron-builder/commit/723441e64d4291b5d5b7cb2f4d2061dd670eee50)), closes [#2022](https://github.com/electron-userland/electron-builder/issues/2022)
* electron-builder not generating "latest.yml" file ([0f1fc4d](https://github.com/electron-userland/electron-builder/commit/0f1fc4d1cb10b2c51d2e4da5e6c58390cd36ba66)), closes [#925](https://github.com/electron-userland/electron-builder/issues/925)
* electron-builder uploads null.blockmap file ([2a2d832](https://github.com/electron-userland/electron-builder/commit/2a2d83206069bc84008a2f9a5b0523ead527df7f)), closes [#2312](https://github.com/electron-userland/electron-builder/issues/2312)
* **electron-builder-http:** electron-auto-updater request can download so fast that the first few chunks arrive before ensureDirPromise has finished for configurePipes to run ([cb85790](https://github.com/electron-userland/electron-builder/commit/cb85790ce79abc6d495cb663e072008ca62d8cf5)), closes [#1081](https://github.com/electron-userland/electron-builder/issues/1081)
* **electron-builder-squirrel-windows:** peer dependency version of 7zip-bin is not correct ([f121f4b](https://github.com/electron-userland/electron-builder/commit/f121f4bdda332e39f94f0e44b6db8ae98aa8ddf5))
* electron-builder.* config file resolution ([481dfa2](https://github.com/electron-userland/electron-builder/commit/481dfa2c19c93b80a9b101b3fb0163af1f0ff3a7))
* **electron-builder:** Configuring yargs through package.json is deprecated [#3751](https://github.com/electron-userland/electron-builder/issues/3751) ([a127a61](https://github.com/electron-userland/electron-builder/commit/a127a61e0b3920d4f305791cd9d618546f018d83))
* **electron-publish:** Allow GH integration tokens ([#4225](https://github.com/electron-userland/electron-builder/issues/4225)) ([8e0a57d](https://github.com/electron-userland/electron-builder/commit/8e0a57d36a002fde5621f11edae17ee4eeeb8cba)), closes [#4176](https://github.com/electron-userland/electron-builder/issues/4176)
* **electron-publisher:** autoUpdater DigitalOcean spaces public-read ([35e15aa](https://github.com/electron-userland/electron-builder/commit/35e15aa224a07639e4ad28a1ba4e33b82379cb8e)), closes [#3089](https://github.com/electron-userland/electron-builder/issues/3089)
* **electron-publish:** socket hang up error 422 issues in github publish ([#6563](https://github.com/electron-userland/electron-builder/issues/6563)) ([39da9ed](https://github.com/electron-userland/electron-builder/commit/39da9edd2df5c147ef2d868f022484a8b2e0466a))
* **electron-publish:** Unable to publish assets to Github (ReleaseAsset asset_already_exists) ([1bd73c9](https://github.com/electron-userland/electron-builder/commit/1bd73c9ced651320e082b62b6e06c043bdb32750)), closes [#3559](https://github.com/electron-userland/electron-builder/issues/3559)
* **electron-publish:** wait after github error ([6fc9fc5](https://github.com/electron-userland/electron-builder/commit/6fc9fc5c3e7071f99e0b6e7493a18471efaf9604))
* electron-updater throws "Cannot find namespace 'debug'" on TypeScript compile ([0f0de81](https://github.com/electron-userland/electron-builder/commit/0f0de81a10ffc03b71d78c2fdecfd29443a5313c)), closes [#1405](https://github.com/electron-userland/electron-builder/issues/1405)
* **electron-updater:** `null` object error when MacUpdater logs server port before it is listening ([#6149](https://github.com/electron-userland/electron-builder/issues/6149)) ([ca0e845](https://github.com/electron-userland/electron-builder/commit/ca0e8454b876c9fa0c95dbadf2461419e3a8b697))
* **electron-updater:** Add better error handling for github releases ([#1114](https://github.com/electron-userland/electron-builder/issues/1114)) ([9dc5bc9](https://github.com/electron-userland/electron-builder/commit/9dc5bc95192e4526622c0599aa8fc7602b7859bd)), closes [#1112](https://github.com/electron-userland/electron-builder/issues/1112)
* **electron-updater:** add parameters to PowerShell invocation ([#2446](https://github.com/electron-userland/electron-builder/issues/2446)) ([72c48cd](https://github.com/electron-userland/electron-builder/commit/72c48cd9f353bc034c600a1305057e6384ef1a30)), closes [#2385](https://github.com/electron-userland/electron-builder/issues/2385) [#2421](https://github.com/electron-userland/electron-builder/issues/2421)
* **electron-updater:** add random query param to avoid caching ([254d7c5](https://github.com/electron-userland/electron-builder/commit/254d7c597b51aa5bf4cb9c8a6e6cbc28c74061d9)), closes [#2741](https://github.com/electron-userland/electron-builder/issues/2741)
* **electron-updater:** add response code to error message about Accept-Ranges ([62cf1df](https://github.com/electron-userland/electron-builder/commit/62cf1df0023dc4a3b9dfcc2424c4919149ea115c))
* **electron-updater:** Added electron 3(Node 10) support to nsis updater ([78a65d2](https://github.com/electron-userland/electron-builder/commit/78a65d2d2f0d0c76643479996e877f8febde1bd7)), closes [#3371](https://github.com/electron-userland/electron-builder/issues/3371)
* **electron-updater:** addRandomQueryToAvoidCaching breaks s3 provider for updater with private acl ([4c52f5c](https://github.com/electron-userland/electron-builder/commit/4c52f5c477e8e9f3386859c4ca04c45f79918afb)), closes [#3021](https://github.com/electron-userland/electron-builder/issues/3021)
* **electron-updater:** addRandomQueryToAvoidCaching does not respect query parameters ([fb1b93d](https://github.com/electron-userland/electron-builder/commit/fb1b93df1fde972f86b11ad068dd46ea92f8f8ce)), closes [#3076](https://github.com/electron-userland/electron-builder/issues/3076)
* **electron-updater:** Allow --package-file arg to escape spaces in filenames ([#2739](https://github.com/electron-userland/electron-builder/issues/2739)) ([24a585b](https://github.com/electron-userland/electron-builder/commit/24a585b826a505ed4d8a5e48d41dcedf6dea5966))
* **electron-updater:** AppImage quitAndInstall exception ([e409c0e](https://github.com/electron-userland/electron-builder/commit/e409c0e9a4542204ef3d16048700470edb4b02df)), closes [#2240](https://github.com/electron-userland/electron-builder/issues/2240)
* **electron-updater:** Auto update does not work on machines with Powershell version < 3 ([5e09db4](https://github.com/electron-userland/electron-builder/commit/5e09db44959e6d3dd32d955f66fff3f3640d763f)), closes [#1732](https://github.com/electron-userland/electron-builder/issues/1732)
* **electron-updater:** Autoupdater problem on mac if space in the URL ([e5d58e2](https://github.com/electron-userland/electron-builder/commit/e5d58e2897299b8d273be03e7a0541a4713a24c5)), closes [#1192](https://github.com/electron-userland/electron-builder/issues/1192)
* **electron-updater:** better escaping of package-path arg ([44c8fd0](https://github.com/electron-userland/electron-builder/commit/44c8fd0487530b30bb87dd0533006dceb35d6ba3))
* **electron-updater:** Bintray provider doesn't support macOS ([c06bf5c](https://github.com/electron-userland/electron-builder/commit/c06bf5ca91892db5403e171f66958cf1a1c03be2)), closes [#2228](https://github.com/electron-userland/electron-builder/issues/2228)
* **electron-updater:** cannot download differentially..: Error: Maximum allowed size is 5 MB ([c5c2eeb](https://github.com/electron-userland/electron-builder/commit/c5c2eeb80b9f357c18b486e94524580016009bd3)), closes [#3564](https://github.com/electron-userland/electron-builder/issues/3564)
* **electron-updater:** channel & channelFile mismatch for macOS GenericProvider publishing ([#1203](https://github.com/electron-userland/electron-builder/issues/1203)) ([#1206](https://github.com/electron-userland/electron-builder/issues/1206)) ([f23daff](https://github.com/electron-userland/electron-builder/commit/f23daff7ce8e7415ae33019b4ea18733f58765bc))
* **electron-updater:** check for EACCES error when try to install on auto updated windows ([#1636](https://github.com/electron-userland/electron-builder/issues/1636)) ([9ef77b9](https://github.com/electron-userland/electron-builder/commit/9ef77b9b4becb558f75e0c9fd80cc4896036a461))
* **electron-updater:** clear error if no channel file in the latest github release ([e292e29](https://github.com/electron-userland/electron-builder/commit/e292e297618aafad5c1aefdc72a260fcd4ef0db1))
* **electron-updater:** close files more reliably during differential download ([d37bacb](https://github.com/electron-userland/electron-builder/commit/d37bacbf83e8847d0fef6f31a1aa19a4bb08dcaf))
* **electron-updater:** Close opened parenthese in update checking log ([8f19ea9](https://github.com/electron-userland/electron-builder/commit/8f19ea99a9cc6fa4796f8057c268541a7b7f63b4)), closes [#2763](https://github.com/electron-userland/electron-builder/issues/2763)
* **electron-updater:** Differential updater: fix "To download" in percentage value calculation (cosmetic fix) ([3febeaf](https://github.com/electron-userland/electron-builder/commit/3febeaff92e04214d38d2b8869c956add4acedb4))
* **electron-updater:** disable differential download operation validation for now ([b7f8e8c](https://github.com/electron-userland/electron-builder/commit/b7f8e8c4c172500220aa254abda6774f352005da)), closes [#3485](https://github.com/electron-userland/electron-builder/issues/3485)
* **electron-updater:** do not dispatch error event for CancellationError [#1150](https://github.com/electron-userland/electron-builder/issues/1150) ([e7acbd9](https://github.com/electron-userland/electron-builder/commit/e7acbd9fc77d249b2ab8fe7e14c81de1f5764c47))
* **electron-updater:** do not install on quit when autoInstallOnAppQuit is set to false ([#5681](https://github.com/electron-userland/electron-builder/issues/5681)) ([8f84591](https://github.com/electron-userland/electron-builder/commit/8f845916d1f44e347fa36cfd95bc1fa1fe14c455))
* **electron-updater:** do not rename AppImage file if no version in the name ([48a0811](https://github.com/electron-userland/electron-builder/commit/48a081159fcdde8218423fd680b17f3e30a8de15)), closes [#2964](https://github.com/electron-userland/electron-builder/issues/2964)
* **electron-updater:** do not use API for GitHub to avoid limit, only for custom host or GitHub Enterprise ([4f7f66e](https://github.com/electron-userland/electron-builder/commit/4f7f66eafdcbccfcdb99838803a1eec37ff7e8ea))
* **electron-updater:** Do not use multiple HTTP ranges because S3 and Minio doesn't support it ([79b2ecc](https://github.com/electron-userland/electron-builder/commit/79b2eccd33d7b1e8a5f192a2267d485e50ce5f6a))
* **electron-updater:** downloading builds(updates) more than once even if downloaded already ([6500b35](https://github.com/electron-userland/electron-builder/commit/6500b35b5dd327c9f05c099a157e6ad20687aefd)), closes [#3007](https://github.com/electron-userland/electron-builder/issues/3007) [#3003](https://github.com/electron-userland/electron-builder/issues/3003)
* **electron-updater:** Electron update fails when using enterprise github ([21d5be5](https://github.com/electron-userland/electron-builder/commit/21d5be58c0af62518865fb8aad0f2fc88aaa9871)), closes [#1661](https://github.com/electron-userland/electron-builder/issues/1661)
* **electron-updater:** Electron updater 4.x problem with quitAndInstall ([e0dd818](https://github.com/electron-userland/electron-builder/commit/e0dd818ba8570173c0a7ee4e4a15dd0346ea7d1e)), closes [#3482](https://github.com/electron-userland/electron-builder/issues/3482)
* **electron-updater:** Electron Updater downloads update multiple times ([6e3581f](https://github.com/electron-userland/electron-builder/commit/6e3581fddd7f03a6ceee2449a692499305d47ad0)), closes [#1788](https://github.com/electron-userland/electron-builder/issues/1788)
* **electron-updater:** Electron-updater does not support enterprise Github ([c3c613b](https://github.com/electron-userland/electron-builder/commit/c3c613b93ab1c078f7c860657f067e7f4c840eeb)), closes [#1903](https://github.com/electron-userland/electron-builder/issues/1903)
* **electron-updater:** Electron-updater don't start downloading after update-available ([fca9e7b](https://github.com/electron-userland/electron-builder/commit/fca9e7b9756f877d23d71aac45fa24ed6124511c)), closes [#2377](https://github.com/electron-userland/electron-builder/issues/2377)
* **electron-updater:** Electron-updater don't start downloading after update-available [#2377](https://github.com/electron-userland/electron-builder/issues/2377) ([dc47ae9](https://github.com/electron-userland/electron-builder/commit/dc47ae9484349dc3016664295f58a5cc3521cd9a))
* **electron-updater:** electron-updater must not depend on builder-util ([1533909](https://github.com/electron-userland/electron-builder/commit/153390943433da0bb3229e585a1171255d240132))
* **electron-updater:** electron-updater v1.14.* throws cannot find module 'debug' ([78d9b33](https://github.com/electron-userland/electron-builder/commit/78d9b33dc0d7e223db2f562c2284354dd8c6bab2)), closes [#1521](https://github.com/electron-userland/electron-builder/issues/1521)
* **electron-updater:** expose "isUpdaterActive" ([b83f580](https://github.com/electron-userland/electron-builder/commit/b83f5801771585c18524c3cee74e59de5fa9ab30)), closes [#4028](https://github.com/electron-userland/electron-builder/issues/4028)
* **electron-updater:** fix backward compatibility for GitHub provider without channels ([#6998](https://github.com/electron-userland/electron-builder/issues/6998)) ([d6115bc](https://github.com/electron-userland/electron-builder/commit/d6115bc5d066d6eee2638015be0c804b31ffcc18))
* **electron-updater:** fix case of blockmap file extension, detect s3 urls on setFeedURL ([369e9c0](https://github.com/electron-userland/electron-builder/commit/369e9c0daaa598653d4ee6002b41e88db59eca8b))
* **electron-updater:** fix checkForUpdatesAndNotify regression in 4.0.0 ([0fa9096](https://github.com/electron-userland/electron-builder/commit/0fa90965f115d6626472c9ab4a1aa19e7d9690c2))
* **electron-updater:** Fix grammar in notification message ([#3410](https://github.com/electron-userland/electron-builder/issues/3410)) ([7953e56](https://github.com/electron-userland/electron-builder/commit/7953e5652067d0c250d9da26c1b123b0362f0259))
* **electron-updater:** fix import errors ([#6140](https://github.com/electron-userland/electron-builder/issues/6140)) ([a3f2cd1](https://github.com/electron-userland/electron-builder/commit/a3f2cd1565771c8ce6c5a4b40d1c88316a75dff3)), closes [#6134](https://github.com/electron-userland/electron-builder/issues/6134)
* **electron-updater:** fix missed path in the log messages ([8a75cbb](https://github.com/electron-userland/electron-builder/commit/8a75cbb6715665eac6437d8eed2f02a136a12306))
* **electron-updater:** fix recent differential update regression ([d9341d6](https://github.com/electron-userland/electron-builder/commit/d9341d62446a075110beaa8385e1f5493c62158e))
* **electron-updater:** fix the problem of redirect (private GitHub provider) ([c550248](https://github.com/electron-userland/electron-builder/commit/c55024847585e0f3d8034c4b32e73b4883f30519)), closes [#2375](https://github.com/electron-userland/electron-builder/issues/2375)
* **electron-updater:** forbid back tick ([82d6602](https://github.com/electron-userland/electron-builder/commit/82d66026fd04f8115d7a06221fbe058ff56a283a)), closes [#4701](https://github.com/electron-userland/electron-builder/issues/4701)
* **electron-updater:** Forbid using of quotes in a file names. ([dead150](https://github.com/electron-userland/electron-builder/commit/dead150769463adbff38b19e9099df6547db0e24))
* **electron-updater:** Github Update Fails Due to Undefined ([591873a](https://github.com/electron-userland/electron-builder/commit/591873a617edf3646c6005f0941d45f4fa522d26)), closes [#1228](https://github.com/electron-userland/electron-builder/issues/1228)
* **electron-updater:** handle null response if no valid GH release available ([ee939de](https://github.com/electron-userland/electron-builder/commit/ee939dec198a8937fdba959eff2f87ed86d61661)), closes [#1866](https://github.com/electron-userland/electron-builder/issues/1866)
* **electron-updater:** ignore unknown powershell errors ([a0026a7](https://github.com/electron-userland/electron-builder/commit/a0026a7422977b449709f8a662d9dd30600a31b1)), closes [#2949](https://github.com/electron-userland/electron-builder/issues/2949) [#2589](https://github.com/electron-userland/electron-builder/issues/2589)
* **electron-updater:** Include application name in update notification ([#2262](https://github.com/electron-userland/electron-builder/issues/2262)) ([1809c94](https://github.com/electron-userland/electron-builder/commit/1809c94e6428cd3398ce153a26a0f2927ac5fe18))
* **electron-updater:** Incorrect comparison of version numbers (electron-updater) ([17ac619](https://github.com/electron-userland/electron-builder/commit/17ac61964d01df46a15338867aec00dc605f1b5b)), closes [#1488](https://github.com/electron-userland/electron-builder/issues/1488)
* **electron-updater:** isSilent is optional ([12473d0](https://github.com/electron-userland/electron-builder/commit/12473d0e72234140f7bef40763c1e693bfb607fb))
* **electron-updater:** MacUpdater — close proxy server after download ([39ae0a4](https://github.com/electron-userland/electron-builder/commit/39ae0a4e6f9fe8705f654cb60b4f83a5810b141b))
* **electron-updater:** MacUpdater — set Content-Length for responses, write 200 only if request to origin server is ok ([af2f559](https://github.com/electron-userland/electron-builder/commit/af2f5595648dc9e4e554ca652b10854a2e35ce13)), closes [#1719](https://github.com/electron-userland/electron-builder/issues/1719)
* **electron-updater:** make "checkForUpdatesAndNotify" catchable promise ([#3531](https://github.com/electron-userland/electron-builder/issues/3531)) ([2c674df](https://github.com/electron-userland/electron-builder/commit/2c674df1333ae0e594ef99c9012d81cc8ddfa30d))
* **electron-updater:** No notification in case of an error during signature verification ([a9e03ce](https://github.com/electron-userland/electron-builder/commit/a9e03ce6d28dcd581dc1e659129f878afff787f0)), closes [#1680](https://github.com/electron-userland/electron-builder/issues/1680) [#1681](https://github.com/electron-userland/electron-builder/issues/1681)
* **electron-updater:** Nsis app from fall 2017 (electron-updater 2.10.0) won't update to new version ([ba2957e](https://github.com/electron-userland/electron-builder/commit/ba2957ef73780cdb652a440cf8b4fee39c34593e)), closes [#2583](https://github.com/electron-userland/electron-builder/issues/2583)
* **electron-updater:** nsis one-click per-machine auto-updating fails (Error: spawn [...].exe EACCES) ([cc63141](https://github.com/electron-userland/electron-builder/commit/cc63141ea818d379c277e69ac7df3391e18ae4bc)), closes [#3480](https://github.com/electron-userland/electron-builder/issues/3480) [#3367](https://github.com/electron-userland/electron-builder/issues/3367)
* **electron-updater:** nsis-web differential update fails ([1d5b408](https://github.com/electron-userland/electron-builder/commit/1d5b4082714dee7e9773a878fce8f9875e59dd8a)), closes [#2366](https://github.com/electron-userland/electron-builder/issues/2366)
* **electron-updater:** On autoupdate download failure, app becomes unresponsive ([451b5b1](https://github.com/electron-userland/electron-builder/commit/451b5b117932eb1992f03c127ffa13955a355f01)), closes [#1865](https://github.com/electron-userland/electron-builder/issues/1865) [#1660](https://github.com/electron-userland/electron-builder/issues/1660)
* **electron-updater:** partially restore sha256 support ([6f8e4ec](https://github.com/electron-userland/electron-builder/commit/6f8e4ec6c65d3a951f774276b5943c0e66704fb4)), closes [#3137](https://github.com/electron-userland/electron-builder/issues/3137)
* **electron-updater:** Pass requestHeaders to httpExecutor ([#3536](https://github.com/electron-userland/electron-builder/issues/3536)) ([f698f08](https://github.com/electron-userland/electron-builder/commit/f698f089f78ed05ff418ed525ba778e49f17669e))
* **electron-updater:** Prevent download notification queueing ([68804e4](https://github.com/electron-userland/electron-builder/commit/68804e4d8ce271f3d61fbd0d2ba908e6996dba40)), closes [#2850](https://github.com/electron-userland/electron-builder/issues/2850)
* **electron-updater:** PrivateGitHubProvider — Github Enterprise support ([becf9b4](https://github.com/electron-userland/electron-builder/commit/becf9b4ad10eb0f8f289c113e1262104c5305694)), closes [#2038](https://github.com/electron-userland/electron-builder/issues/2038)
* **electron-updater:** recurrent 404 Errors on GitHub Enterprise ([afc1a9e](https://github.com/electron-userland/electron-builder/commit/afc1a9eedf20785aef58f4f5ae1129acb8ba4f05))
* **electron-updater:** redirect event in electron.net ([e2ac601](https://github.com/electron-userland/electron-builder/commit/e2ac601bae13961801cb2017cded26b1ec571d40)), closes [#2374](https://github.com/electron-userland/electron-builder/issues/2374)
* **electron-updater:** reduce electron-updater size ([8025fb4](https://github.com/electron-userland/electron-builder/commit/8025fb49f27e01b7f5aeb4f5220270f031d5c3ce)), closes [#3953](https://github.com/electron-userland/electron-builder/issues/3953)
* **electron-updater:** remove escaping of package-path arg - node escapes it properly ([c7e07cc](https://github.com/electron-userland/electron-builder/commit/c7e07cc83280d72c74946d4537bbdfe3961a9901))
* **electron-updater:** Replace all occurrences of version in old blockmap file url ([#3120](https://github.com/electron-userland/electron-builder/issues/3120)) ([ca18b74](https://github.com/electron-userland/electron-builder/commit/ca18b74dfddb28bc0dbc485449738fa79589296f))
* **electron-updater:** response from Generic Provider getLatestVersion becomes [ 'Object object' ] ([eaca9b5](https://github.com/electron-userland/electron-builder/commit/eaca9b5818897f940df3040a0b3458d8cab89405)), closes [#1853](https://github.com/electron-userland/electron-builder/issues/1853)
* **electron-updater:** return correct release notes & name ([#2743](https://github.com/electron-userland/electron-builder/issues/2743)) ([37014be](https://github.com/electron-userland/electron-builder/commit/37014be76e2ea8e5183a68cc4a56ffca31c08df5)), closes [#2742](https://github.com/electron-userland/electron-builder/issues/2742)
* **electron-updater:** Rewrite block map builder in Go ([4dc71d7](https://github.com/electron-userland/electron-builder/commit/4dc71d743dbfc8d1c076a26e9bd8c3e6d9b37812))
* **electron-updater:** search 'arm64' in name and url to fix updates from Github private repos ([1580ea6](https://github.com/electron-userland/electron-builder/commit/1580ea691c4b82ea80c6420d806bc4bfaef5fd38))
* **electron-updater:** set _packageFile to null on clear ([7fe72da](https://github.com/electron-userland/electron-builder/commit/7fe72dafd22c3bdc3481ab4ba805a7c98724320e))
* **electron-updater:** set actual http status code instead of 404 [#2741](https://github.com/electron-userland/electron-builder/issues/2741) ([8453a77](https://github.com/electron-userland/electron-builder/commit/8453a7729daf928149fe147934f4cc1f068ca538))
* **electron-updater:** small cleanup and add more debug logging for MacUpdater to investigate [#6120](https://github.com/electron-userland/electron-builder/issues/6120) ([#6122](https://github.com/electron-userland/electron-builder/issues/6122)) ([ae81dfa](https://github.com/electron-userland/electron-builder/commit/ae81dfae519435355fc079c76fc16ac25216bf38))
* **electron-updater:** unify "update-downloaded" event on macOS ([86d64c2](https://github.com/electron-userland/electron-builder/commit/86d64c24eb480d92131d5691798cdff9d7926c3c))
* **electron-updater:** update sign verification error ([e713bbe](https://github.com/electron-userland/electron-builder/commit/e713bbe9284d3169aaa9539ba8d1d338e15a7dad)), closes [#1641](https://github.com/electron-userland/electron-builder/issues/1641)
* **electron-updater:** Updater crash on windows, fails on MacOS X ([76fdd42](https://github.com/electron-userland/electron-builder/commit/76fdd42336c41c35bedb56624e6947f339df653b)), closes [#3308](https://github.com/electron-userland/electron-builder/issues/3308) [#3377](https://github.com/electron-userland/electron-builder/issues/3377)
* **electron-updater:** url parameters, search is inside ([d553629](https://github.com/electron-userland/electron-builder/commit/d5536297dcb9ff4e306ed04b9f354fccbb490eee))
* **electron-updater:** use "NSAllowsLocalNetworking": true for macOS X ([10dd145](https://github.com/electron-userland/electron-builder/commit/10dd1456cdd8eb5b4092d5b1723ac3dcb188f435)), closes [#3377](https://github.com/electron-userland/electron-builder/issues/3377)
* **electron-updater:** use app version as version for blockmap url instead of parsed semver ([5efafa8](https://github.com/electron-userland/electron-builder/commit/5efafa84e3927f688e5843cd1306cbfe098bb6e7))
* **electron-updater:** use tag name instead of version when resolving GitHub files ([#6117](https://github.com/electron-userland/electron-builder/issues/6117)) ([dcf03a6](https://github.com/electron-userland/electron-builder/commit/dcf03a67a8a0d4cec4422cda0aa2585f7f54a384))
* **electron-updater:** vertical upgrading for channels ([b1f2272](https://github.com/electron-userland/electron-builder/commit/b1f2272b92adbe76a37164c107c5c7c4c26ca33c)), closes [#3111](https://github.com/electron-userland/electron-builder/issues/3111)
* **electron-updater:** web installer differential download perMachine ([82708a5](https://github.com/electron-userland/electron-builder/commit/82708a5d41b63ae147c5763aa81d4d765c4fe6e2)), closes [#2949](https://github.com/electron-userland/electron-builder/issues/2949)
* **electron-updater:** when AllowDowngrade is true and latest version is older, take the update ([#4218](https://github.com/electron-userland/electron-builder/issues/4218)) ([5bf4498](https://github.com/electron-userland/electron-builder/commit/5bf44987412189783e9b7ebbc35376ce471362c6))
* **electron-webpack:** resolve electron-webpack config ([eb9c1d6](https://github.com/electron-userland/electron-builder/commit/eb9c1d695eefb29922607e93bb32540514565243))
* **electron-webpack:** resolve electron-webpack config ([5c7a7f9](https://github.com/electron-userland/electron-builder/commit/5c7a7f9bcc90eedcd71ac148265b3dfdb250b142))
* enable NPM_NO_BIN_LINKS for yarn 1.x.x ([#4915](https://github.com/electron-userland/electron-builder/issues/4915)) ([873089e](https://github.com/electron-userland/electron-builder/commit/873089ec30937a628de7f7f6f5d76ce54d0c4f95))
* enable signing of .node modules in order to support WDAC ([#7421](https://github.com/electron-userland/electron-builder/issues/7421)) ([d1e0c34](https://github.com/electron-userland/electron-builder/commit/d1e0c348283b5f099217aa247f9af24c77a3e415)), closes [#7329](https://github.com/electron-userland/electron-builder/issues/7329)
* Ensure folder paths to have trailing path separator ([53d0b0a](https://github.com/electron-userland/electron-builder/commit/53d0b0a0b7556b39e43a177d9ec059507a0828aa)), closes [#1872](https://github.com/electron-userland/electron-builder/issues/1872)
* Ensure parent directories of symlinks are created ([#7327](https://github.com/electron-userland/electron-builder/issues/7327)) ([973a004](https://github.com/electron-userland/electron-builder/commit/973a0048b46b8367864241a903453f927c158304))
* ensure that `/` is not used as path and not added twice ([bc6a3a0](https://github.com/electron-userland/electron-builder/commit/bc6a3a049629bd47a87b6b5152386791df3f2eeb)), closes [#3092](https://github.com/electron-userland/electron-builder/issues/3092) [#3091](https://github.com/electron-userland/electron-builder/issues/3091)
* ensure that ELECTRON_BUILDER_CACHE resolved relative to current working directory ([aaab4cb](https://github.com/electron-userland/electron-builder/commit/aaab4cb048d308ba575af55f6628965a4878c168)), closes [#2924](https://github.com/electron-userland/electron-builder/issues/2924)
* ensure that generated temporary iconset is removed on exit ([fb23f48](https://github.com/electron-userland/electron-builder/commit/fb23f48cfebdccd2ce19e3623c544bd47179548e))
* ensure that ico image (from PNG) size is 256 ([efc1923](https://github.com/electron-userland/electron-builder/commit/efc1923f65f4c2ffd5a4f6cd5371b9ddcd09f5e8))
* ensure that out dir exists ([8dd6cd5](https://github.com/electron-userland/electron-builder/commit/8dd6cd545a9716abade7436ba3807e8f4864286f))
* ensure that proper electron version will be used ([9947dd9](https://github.com/electron-userland/electron-builder/commit/9947dd93f7a2ec4c2fb2322c51486b8d2966677b)), closes [#3984](https://github.com/electron-userland/electron-builder/issues/3984)
* ensure that setgid and setuid flags are cleared ([80b8d91](https://github.com/electron-userland/electron-builder/commit/80b8d919f861b57c98b08438da0c24b120821c82)), closes [#3608](https://github.com/electron-userland/electron-builder/issues/3608)
* Error during signing when running as Windows SYSTEM user ([688111e](https://github.com/electron-userland/electron-builder/commit/688111ea6314dedc3fdfd4d604a99587d9f6fa17)), closes [#1164](https://github.com/electron-userland/electron-builder/issues/1164)
* Error in app-builder-lib filter util with yarn workspace ([632f79d](https://github.com/electron-userland/electron-builder/commit/632f79d0ece9fe2082a77feeb65501366d75302f)), closes [#3223](https://github.com/electron-userland/electron-builder/issues/3223)
* escape instead of error ([#5116](https://github.com/electron-userland/electron-builder/issues/5116)) ([e2cc9f9](https://github.com/electron-userland/electron-builder/commit/e2cc9f95798df0db47412a5d94b032a8c6ad2882))
* Escape version in NSIS Updater during replace ([#5655](https://github.com/electron-userland/electron-builder/issues/5655)) ([77c215d](https://github.com/electron-userland/electron-builder/commit/77c215d1b1913982a7c9a62b1b5098d95a37272d))
* exclude .editorconfig ony for app root — use .yarnclean to clean node_modules ([2e86ac3](https://github.com/electron-userland/electron-builder/commit/2e86ac36ed27f20f74697ccabacb719b2e85b71d)), closes [#1969](https://github.com/electron-userland/electron-builder/issues/1969)
* exclude `electron-builder.env` file from app to avoid packaging env secrets ([#7792](https://github.com/electron-userland/electron-builder/issues/7792)) ([84906bc](https://github.com/electron-userland/electron-builder/commit/84906bc899c1b6ad2a9ec9bb9a249849e05133b5))
* execute `%SYSTEMROOT%` cmd.exe directly during NSIS installer ([#8059](https://github.com/electron-userland/electron-builder/issues/8059)) ([8f4acff](https://github.com/electron-userland/electron-builder/commit/8f4acff3c2d45c1cb07779bb3fe79644408ee387))
* Execute `afterSign` hook only when signing is complete (i.e. if the signing step wasn't explicitly skipped) (BREAKING) ([#7311](https://github.com/electron-userland/electron-builder/issues/7311)) ([fd93fce](https://github.com/electron-userland/electron-builder/commit/fd93fce96f476c09af3379d964bf9092bd20787e))
* expand macro for `${version}/.icon-ico/` dir on Window's installers ([#7763](https://github.com/electron-userland/electron-builder/issues/7763)) ([0cb1913](https://github.com/electron-userland/electron-builder/commit/0cb1913272c0cf24603233e2033d8fc3f33cb26d))
* Export type `ProgressInfo` ([ee1a86b](https://github.com/electron-userland/electron-builder/commit/ee1a86b08de80ce71f5bdc5e8c46fa8feb750223)), closes [#2520](https://github.com/electron-userland/electron-builder/issues/2520)
* extend http file limit ([#5843](https://github.com/electron-userland/electron-builder/issues/5843)) ([9305fef](https://github.com/electron-userland/electron-builder/commit/9305fefa1265ec1a244b0003bd4489731d5f15a4)), closes [#4676](https://github.com/electron-userland/electron-builder/issues/4676)
* Extract `NotarizeNotaryOptions` and `NotarizeLegacyOptions` to explicitly define required vars ([#7797](https://github.com/electron-userland/electron-builder/issues/7797)) ([efd48dc](https://github.com/electron-userland/electron-builder/commit/efd48dc07bdc12894e1494136448176dc8a6c4bb))
* Fails to parse JSON ([83ca284](https://github.com/electron-userland/electron-builder/commit/83ca284c4727bf48b45de56d27f9fe2da16e1b41)), closes [#1871](https://github.com/electron-userland/electron-builder/issues/1871)
* Fix electron-updater error handling when spawning a process asynchronously ([#7524](https://github.com/electron-userland/electron-builder/issues/7524)) ([1a13480](https://github.com/electron-userland/electron-builder/commit/1a13480036a2219007f866c64beea45292bc2946))
* fix husky not create hooks and improve lint when commit ([#5716](https://github.com/electron-userland/electron-builder/issues/5716)) ([18e0c24](https://github.com/electron-userland/electron-builder/commit/18e0c242ec879a0d9582f50a36ce5ea5d9834a51))
* fix incorrect rebuild target in install-app-deps ([88e52ad](https://github.com/electron-userland/electron-builder/commit/88e52add1d04b1708f0eb18ba1912417b9542d03))
* fixes for server auth for MacUpdater ([#6587](https://github.com/electron-userland/electron-builder/issues/6587)) ([8746f91](https://github.com/electron-userland/electron-builder/commit/8746f910d136fb9b531e688d0a646eeb9528adc6))
* fixing downloadPromise not resolving on Mac. ([#5802](https://github.com/electron-userland/electron-builder/issues/5802)) ([d57453c](https://github.com/electron-userland/electron-builder/commit/d57453cffc8e502fb1c95a9287dee2dd5cdd4b73))
* flatpak build failing due to too large icons ([#7875](https://github.com/electron-userland/electron-builder/issues/7875)) ([9883ab6](https://github.com/electron-userland/electron-builder/commit/9883ab60687b67c858b16f09eea6f8af76cf01b0))
* formatting of Code in the MacOS PKG docs ([#7142](https://github.com/electron-userland/electron-builder/issues/7142)) ([9338097](https://github.com/electron-userland/electron-builder/commit/9338097a9f6754dee8d87185154eaa7d9cffdec8))
* from as file and to as dir ([3bb2ab8](https://github.com/electron-userland/electron-builder/commit/3bb2ab8c78e749bb540181c35d4b19b7d46a1417)), closes [#1245](https://github.com/electron-userland/electron-builder/issues/1245)
* generate latest-mac.json for github in the github directory ([8670d5a](https://github.com/electron-userland/electron-builder/commit/8670d5a90ff7627b807cfc5caf97471672fff4ea))
* get CI tag in GitHub Actions ([#7231](https://github.com/electron-userland/electron-builder/issues/7231)) ([c21e3b3](https://github.com/electron-userland/electron-builder/commit/c21e3b37e0dd064c12dbd38065a548441d7c5a9e))
* github provider prerelease check incorrectly casts undefined to String. Fixes [#6809](https://github.com/electron-userland/electron-builder/issues/6809) ([#6810](https://github.com/electron-userland/electron-builder/issues/6810)) ([817e68b](https://github.com/electron-userland/electron-builder/commit/817e68ba54f4fa60fec789fcfcfb527473a610fc))
* handle aborted event ([a7ea361](https://github.com/electron-userland/electron-builder/commit/a7ea3615133278113b44eb2ad0ba328ef4ddfdca)), closes [#1975](https://github.com/electron-userland/electron-builder/issues/1975)
* handle differential downloads when the blockmap HTTP response is compressed ([#7544](https://github.com/electron-userland/electron-builder/issues/7544)) ([dab3aeb](https://github.com/electron-userland/electron-builder/commit/dab3aeba2240ead4300c8fdb35e3d9c16b04a23d))
* handle sync spawn error ([4351b56](https://github.com/electron-userland/electron-builder/commit/4351b569ce5d8263724982ec874d2ceb93931829)), closes [#1460](https://github.com/electron-userland/electron-builder/issues/1460)
* handle sync spawn error ([af14809](https://github.com/electron-userland/electron-builder/commit/af14809cc531361679453a58175303db364eaaa0)), closes [#1438](https://github.com/electron-userland/electron-builder/issues/1438)
* identity = null is not respected ([3df2638](https://github.com/electron-userland/electron-builder/commit/3df26389d2da7a8d28da48cbbb7b81295ab92c84)), closes [#1233](https://github.com/electron-userland/electron-builder/issues/1233)
* Identity validation option is incorrect ([97699b1](https://github.com/electron-userland/electron-builder/commit/97699b1b2ef44877ba611cf96cecb98708e0aee3)), closes [#1603](https://github.com/electron-userland/electron-builder/issues/1603)
* if cannot resolve win csc link, report as InvalidConfigurationError to make clear that it is user error ([88d8a6b](https://github.com/electron-userland/electron-builder/commit/88d8a6ba79318473318147560b7c539c17f6b5e0)), closes [#3502](https://github.com/electron-userland/electron-builder/issues/3502)
* ignore files in the node_modules during read_installed ([37f84b9](https://github.com/electron-userland/electron-builder/commit/37f84b94c0cfe6722f0de9abe6b5d2be2a53a4b8)), closes [#1424](https://github.com/electron-userland/electron-builder/issues/1424)
* ignore node_modules without package.json ([5e24859](https://github.com/electron-userland/electron-builder/commit/5e24859461b2583966c45a43f74160b673c28555)), closes [#1671](https://github.com/electron-userland/electron-builder/issues/1671)
* improve `downloadUpdate` typing to match the doc ([#7099](https://github.com/electron-userland/electron-builder/issues/7099)) ([cd21b09](https://github.com/electron-userland/electron-builder/commit/cd21b0918843fe1269ddaf8dde099c8faeb54b80))
* improve debuggability — print effective config if debug enabled ([927ac40](https://github.com/electron-userland/electron-builder/commit/927ac4039dabae0e2ac558ccee8a1e939fecb3ec))
* include SnapStoreOptions into schema ([7aed22e](https://github.com/electron-userland/electron-builder/commit/7aed22e44ef7adddf0e148cee2cf7c954b74b391))
* incompatible Windows sign tool in end user environment.  ([#6817](https://github.com/electron-userland/electron-builder/issues/6817)) ([2860d13](https://github.com/electron-userland/electron-builder/commit/2860d132fc837813627e6508e05b18ed5e5dedfc))
* Inconsistent versions of builder-util-runtime ([9ba8ade](https://github.com/electron-userland/electron-builder/commit/9ba8ade66593c3e15df72156379ab0858d88ff6b)), closes [#3887](https://github.com/electron-userland/electron-builder/issues/3887)
* Incorrect error message ([bc0952e](https://github.com/electron-userland/electron-builder/commit/bc0952e6675e6997b162ad85c2df52bf63a841f3)), closes [#1236](https://github.com/electron-userland/electron-builder/issues/1236)
* incorrect html comment in issue_template.md ([#7386](https://github.com/electron-userland/electron-builder/issues/7386)) ([d07b98a](https://github.com/electron-userland/electron-builder/commit/d07b98accba0c1afea12d18e850fde02dcf8ea51))
* Increase log buffer for 7zip exec ([#3760](https://github.com/electron-userland/electron-builder/issues/3760)) ([51d2534](https://github.com/electron-userland/electron-builder/commit/51d2534572d9ea4073566510040ca63082e48829))
* increase maxBuffer for xorriso child process ([#1274](https://github.com/electron-userland/electron-builder/issues/1274)) ([bce672e](https://github.com/electron-userland/electron-builder/commit/bce672e0b8cf70d2338f0428bb49d6efd5682ead))
* install-app-deps ([21a5be5](https://github.com/electron-userland/electron-builder/commit/21a5be52960dd0093a5f24f98c33fe391d25c639)), closes [#1626](https://github.com/electron-userland/electron-builder/issues/1626)
* install-app-deps / build command should accept any supported arch ([8474d7d](https://github.com/electron-userland/electron-builder/commit/8474d7d4d75f4ce17916de996e76fd27ccab0893)), closes [#2092](https://github.com/electron-userland/electron-builder/issues/2092)
* install-app-deps, attempt 2 ([8715f44](https://github.com/electron-userland/electron-builder/commit/8715f4433a976b47f46f2f542ec9718e30a174a2)), closes [#1626](https://github.com/electron-userland/electron-builder/issues/1626)
* **install-app-deps:** arm it is armv7l ([c8c0a9b](https://github.com/electron-userland/electron-builder/commit/c8c0a9b6c6b7fed535dbdd4502f026dd5639cd2c)), closes [#3110](https://github.com/electron-userland/electron-builder/issues/3110)
* Invalid code signing for MAS build due to ordering of certificate check ([#7040](https://github.com/electron-userland/electron-builder/issues/7040)) ([#7089](https://github.com/electron-userland/electron-builder/issues/7089)) ([a1d86fd](https://github.com/electron-userland/electron-builder/commit/a1d86fd75bbc7b252403c16966430a2e3562205d))
* Issue with extraFiles not being valid ([f137193](https://github.com/electron-userland/electron-builder/commit/f137193c0c510186abc394405838e98727145dcb)), closes [#1302](https://github.com/electron-userland/electron-builder/issues/1302)
* keep shortcuts only if old uninstaller app support it ([8660093](https://github.com/electron-userland/electron-builder/commit/8660093d41718f326d0e0f3dae6f6326fe7489d6)), closes [#1704](https://github.com/electron-userland/electron-builder/issues/1704)
* latest node-gyp with old Electron versions ([#6402](https://github.com/electron-userland/electron-builder/issues/6402)) ([f41d5f3](https://github.com/electron-userland/electron-builder/commit/f41d5f397ade8f6199d56bb4275b05a0a0e65bca))
* libglib-2.0.0.dylib missing ([5726a03](https://github.com/electron-userland/electron-builder/commit/5726a038fa0e45fd9f940aad03423142a9505f9b)), closes [#2204](https://github.com/electron-userland/electron-builder/issues/2204)
* linking CLI `version` output with package.json ([#6097](https://github.com/electron-userland/electron-builder/issues/6097)) ([a4eae34](https://github.com/electron-userland/electron-builder/commit/a4eae34f38444e0f30cf94af869e9e84c406a469))
* **linux:** Add dependencies for supporting Electron Tray (libappindicator) & Notifications (libnotify) for more Linux targets ([#1339](https://github.com/electron-userland/electron-builder/issues/1339)) ([79c94bd](https://github.com/electron-userland/electron-builder/commit/79c94bd285b08cff705a4ff63c4cd3cabe2caf2a)), closes [#1338](https://github.com/electron-userland/electron-builder/issues/1338)
* **linux:** correctly set size of icon converted using openjpeg2 ([99c1025](https://github.com/electron-userland/electron-builder/commit/99c1025cdeff9636182c50f26b7918217e50fe81)), closes [#2599](https://github.com/electron-userland/electron-builder/issues/2599)
* **linux:** depends for deb in LinuxOptions ([d58d323](https://github.com/electron-userland/electron-builder/commit/d58d32386221ad87c94acdf7d2cadbb7185d260e)), closes [#1420](https://github.com/electron-userland/electron-builder/issues/1420)
* **linux:** do not hide error on internal tar compression programm call ([3fbe118](https://github.com/electron-userland/electron-builder/commit/3fbe1180dc122625086367df73a3052ebfec4ae9))
* **linux:** do not set C.UTF-8 locale blindly ([41920bf](https://github.com/electron-userland/electron-builder/commit/41920bf4282495bc6c96d04085e44e00f256d050)), closes [#2340](https://github.com/electron-userland/electron-builder/issues/2340)
* **linux:** do not write empty Comment in desktop file ([3f90401](https://github.com/electron-userland/electron-builder/commit/3f904012b0073f52a2c6b58fc515da3757a56e96))
* **linux:** executable breakes if productName given ([2906227](https://github.com/electron-userland/electron-builder/commit/2906227d9cd41a3d2e131d5233ee897968c01b5b)), closes [#1060](https://github.com/electron-userland/electron-builder/issues/1060)
* **linux:** executable path in Debian postinst script ([#5941](https://github.com/electron-userland/electron-builder/issues/5941)) ([4a5132f](https://github.com/electron-userland/electron-builder/commit/4a5132f25f64e1d0907e77e6fc309edf01d1b04b)), closes [#5933](https://github.com/electron-userland/electron-builder/issues/5933)
* **linux:** icon.icns is not used for Linux icon ([2154934](https://github.com/electron-userland/electron-builder/commit/2154934eddbd6834c06fcd099cfeb5770de33819)), closes [#2617](https://github.com/electron-userland/electron-builder/issues/2617)
* **linux:** Include main category for inferred DEB desktop entries ([5771ffe](https://github.com/electron-userland/electron-builder/commit/5771ffe22028307b142a491d13830fdeb31365cb))
* **linux:** invalid default app icon used warning ([ceafebb](https://github.com/electron-userland/electron-builder/commit/ceafebbfda6c68dfb1da85879fd635ad1aae7f25)), closes [#3495](https://github.com/electron-userland/electron-builder/issues/3495)
* **linux:** Linux icon is not set if path is not explicitly defined in config ([#5385](https://github.com/electron-userland/electron-builder/issues/5385)) ([9fd950b](https://github.com/electron-userland/electron-builder/commit/9fd950bc046ca1748950f63894993947da8185c5))
* **linux:** make semver pre-release versions valid for "pacman" and "rpm" target ([#7630](https://github.com/electron-userland/electron-builder/issues/7630)) ([37db080](https://github.com/electron-userland/electron-builder/commit/37db080ffabf546132d278ff69532b0558ad0a41))
* **linux:** mutually exclusive exec command args ([#6384](https://github.com/electron-userland/electron-builder/issues/6384)) ([5468c18](https://github.com/electron-userland/electron-builder/commit/5468c188f30f65352ca651e1f5fa9f8915c48c6b))
* **linux:** remove 24/96 icon sizes - not required in general ([bb7d0f6](https://github.com/electron-userland/electron-builder/commit/bb7d0f6824d150183fe6ef13e242b59bc97c3f3d))
* **linux:** Use ~ as pre-release separator for deb targets ([#7978](https://github.com/electron-userland/electron-builder/issues/7978)) ([2773410](https://github.com/electron-userland/electron-builder/commit/277341000a87abaa65a7985854c06e88ed5938b9))
* **linux:** use executableName as specified and do not lowercase it ([79077bf](https://github.com/electron-userland/electron-builder/commit/79077bf81dc142cb87118780e3372c32f58dfc69)), closes [#1291](https://github.com/electron-userland/electron-builder/issues/1291)
* **linux:** xz on Travis CI macOS agent ([f1f82d0](https://github.com/electron-userland/electron-builder/commit/f1f82d012da7575cb824f04e18d2cd1a8b5e08f1))
* locale message ([#2805](https://github.com/electron-userland/electron-builder/issues/2805)) ([0fd945b](https://github.com/electron-userland/electron-builder/commit/0fd945b67927f2bd1bde5760a2cbe43442222618))
* Lock wine version to v6 in docker image ([#6816](https://github.com/electron-userland/electron-builder/issues/6816)) ([8f57a90](https://github.com/electron-userland/electron-builder/commit/8f57a90c885254bf442e7eea5b8f450bd400eac4)), closes [#6780](https://github.com/electron-userland/electron-builder/issues/6780)
* Look for the Amazon cred header to remove auth header ([#5594](https://github.com/electron-userland/electron-builder/issues/5594)) ([46a8840](https://github.com/electron-userland/electron-builder/commit/46a8840bb4b3ed9b81ac65d3351debc4e34f30ce))
* mac differential updater ([#8095](https://github.com/electron-userland/electron-builder/issues/8095)) ([53cec79](https://github.com/electron-userland/electron-builder/commit/53cec79bdc3f56c9371bdfb7901e97650d9ac4bc))
* mac notarization issue when checking env password ([#7884](https://github.com/electron-userland/electron-builder/issues/7884)) ([6fa8a27](https://github.com/electron-userland/electron-builder/commit/6fa8a27f9dd406c289f608c664c93b6ed9d1a9ee))
* **mac:** add needed helpers for electron 6.0.0 ([#4111](https://github.com/electron-userland/electron-builder/issues/4111)) ([c36f6c8](https://github.com/electron-userland/electron-builder/commit/c36f6c844692a8bb2e9f974fd0cd3fcdd79a444c))
* **mac:** add retry in mac code sign ([#8101](https://github.com/electron-userland/electron-builder/issues/8101)) ([9bcede8](https://github.com/electron-userland/electron-builder/commit/9bcede88f2083d41266e48dfa712adc2d223bd7f))
* **mac:** adding arch suffix to pkg target to enable non-universal pkg builds ([#5847](https://github.com/electron-userland/electron-builder/issues/5847)) ([#5897](https://github.com/electron-userland/electron-builder/issues/5897)) ([9f9e20c](https://github.com/electron-userland/electron-builder/commit/9f9e20c86bcaed94ff5d6c63e7480bd8163a0e0e))
* **mac:** Allow arm64 macs to update to x64 version if no arm64 version available ([#5524](https://github.com/electron-userland/electron-builder/issues/5524)) ([dc5c2f8](https://github.com/electron-userland/electron-builder/commit/dc5c2f8e772da4a9e6f1cf9578c70f60ddc36b37))
* **mac:** allow Mac Developer certs for non Mac App Store builds ([#6956](https://github.com/electron-userland/electron-builder/issues/6956)) ([4e90504](https://github.com/electron-userland/electron-builder/commit/4e905046e632b396735b78618fbc01331448f088)), closes [#6564](https://github.com/electron-userland/electron-builder/issues/6564)
* **mac:** always include a secure timestamp with your code-signing signature ([2e7ee22](https://github.com/electron-userland/electron-builder/commit/2e7ee226763a25e934958a065462a7d69fc020d8))
* **mac:** apply app version to helper apps ([#2773](https://github.com/electron-userland/electron-builder/issues/2773)) ([45b1231](https://github.com/electron-userland/electron-builder/commit/45b12311805a5ea479f8657d5c7d007b754df51a)), closes [#2772](https://github.com/electron-userland/electron-builder/issues/2772)
* **mac:** Cannot find module '../../electron-osx-sign/util-identities' ([4bc0559](https://github.com/electron-userland/electron-builder/commit/4bc0559b3957674ab4280dfc9197a9ebeb8fd53c)), closes [#4067](https://github.com/electron-userland/electron-builder/issues/4067)
* **mac:** clean macOsVersion before gte comparison ([#1733](https://github.com/electron-userland/electron-builder/issues/1733)) ([7ff95ca](https://github.com/electron-userland/electron-builder/commit/7ff95ca99858582b9a74e8a8348aa7d529db70cc))
* **mac:** dist app quit unexpectedly caused by productName ([3a1042a](https://github.com/electron-userland/electron-builder/commit/3a1042ab722bb143be9829cc3139f6a93f2725ed)), closes [#1278](https://github.com/electron-userland/electron-builder/issues/1278)
* **mac:** do not sign kext ([8180da8](https://github.com/electron-userland/electron-builder/commit/8180da82257ae872e39c3a13a2c7f0d4a35fe0cd))
* **mac:** don't notarize mas builds ([#7838](https://github.com/electron-userland/electron-builder/issues/7838)) ([87eae1c](https://github.com/electron-userland/electron-builder/commit/87eae1cc2f85f034f1543840b20d56e89a23c0df))
* **mac:** Enhance the usage boundary of iconTextSize ([#7769](https://github.com/electron-userland/electron-builder/issues/7769)) ([#7780](https://github.com/electron-userland/electron-builder/issues/7780)) ([a8b1f15](https://github.com/electron-userland/electron-builder/commit/a8b1f1592e14710977b036313c8a2cb551a29064))
* **mac:** ensure that codesign will not display a UI prompt for permission to access the keychain ([ed4d8d0](https://github.com/electron-userland/electron-builder/commit/ed4d8d055bfda22053d0bd4c2c7defa3a2cad5f1))
* **mac:** ensure that created temporary keychain doesn't pollute system even if not deleted correctly ([97684ca](https://github.com/electron-userland/electron-builder/commit/97684ca2c81c2b71d56a641c822f507a4d4accfc)), closes [#3685](https://github.com/electron-userland/electron-builder/issues/3685)
* **mac:** executables within app.asar.unpacked are not being signed correctly in OSX 10.14.5 ([519bb47](https://github.com/electron-userland/electron-builder/commit/519bb4762437eba1a153211c55e328debc04ffc2)), closes [#3940](https://github.com/electron-userland/electron-builder/issues/3940)
* **mac:** Exits with status=0 when signing fails ([fbfb8c6](https://github.com/electron-userland/electron-builder/commit/fbfb8c6a819ae771ec7a428910b27ce053f01efa)), closes [#2538](https://github.com/electron-userland/electron-builder/issues/2538)
* **mac:** fine-grained control [NSAllowsLocalNetworking] is not available in older operating systems (iOS 10.0 and older, or macOS 10.12 and older) ([930dc8d](https://github.com/electron-userland/electron-builder/commit/930dc8da1df2ad0f6317a1f061dde951102386ad)), closes [#3377](https://github.com/electron-userland/electron-builder/issues/3377)
* **mac:** fix "Contents/Info.plist" don't have identical SHAs when creating a universal build ([#5550](https://github.com/electron-userland/electron-builder/issues/5550)) ([0ba839b](https://github.com/electron-userland/electron-builder/commit/0ba839b72b6a13178ad5bc4b03a47f9aca980650))
* **mac:** fix errors using native modules that require rebuild when both mas and mac targets are specified ([#7744](https://github.com/electron-userland/electron-builder/issues/7744)) ([4fc7a3c](https://github.com/electron-userland/electron-builder/commit/4fc7a3c3b857380bcbdd2a10e26989e3b1af50a2))
* **mac:** fix recent regression - icon path without extension resolving ([820b5f8](https://github.com/electron-userland/electron-builder/commit/820b5f8597feb70e1a667643d72ba0da370c9807))
* **mac:** Framework symlinks are not created in app on macOS, leading to crash on launch ([7bf2b9a](https://github.com/electron-userland/electron-builder/commit/7bf2b9ad6365a9d226299b0b50eaba102c6ec480)), closes [#3435](https://github.com/electron-userland/electron-builder/issues/3435)
* **mac:** generate latest-mac.yml for zip target ([f545d1e](https://github.com/electron-userland/electron-builder/commit/f545d1e097366fa58727395a14d22e049c12e74d)), closes [#2313](https://github.com/electron-userland/electron-builder/issues/2313)
* **mac:** identifier missing from pkgbuild ([#4558](https://github.com/electron-userland/electron-builder/issues/4558)) ([d216473](https://github.com/electron-userland/electron-builder/commit/d2164732fee19b28018bf3a39c799be3c72bd8f7))
* **mac:** Invalid Bundle Identifier Electron Helper (GPU, Plugin, and Rende… ([#4154](https://github.com/electron-userland/electron-builder/issues/4154)) ([2eabee0](https://github.com/electron-userland/electron-builder/commit/2eabee08f6e53490dc0903ce3d01179c3e3ade59)), closes [#4151](https://github.com/electron-userland/electron-builder/issues/4151)
* **mac:** mac build fails against electron v4.0.0-beta.3 ([7fc9a29](https://github.com/electron-userland/electron-builder/commit/7fc9a2965358fdeff3d757633695609236d7759d)), closes [#3412](https://github.com/electron-userland/electron-builder/issues/3412)
* **mac:** mac ZIP root folder regression ([2df0e1c](https://github.com/electron-userland/electron-builder/commit/2df0e1cc03992bf74febcc76cb24206f2876239d)), closes [#3277](https://github.com/electron-userland/electron-builder/issues/3277)
* **mac:** MacOS Sierra Command failed: codesign; The specified item could not be found in the keychain ([239d16d](https://github.com/electron-userland/electron-builder/commit/239d16d5884d519ac2468ec108ba58f0b30a032e)), closes [#1457](https://github.com/electron-userland/electron-builder/issues/1457)
* **mac:** make tempFile unique for each call to getProvisioningProfileAsync ([#4269](https://github.com/electron-userland/electron-builder/issues/4269)) ([f858f9e](https://github.com/electron-userland/electron-builder/commit/f858f9e0b43de8d646cce7ac4e9c00f773c2f131)), closes [#4204](https://github.com/electron-userland/electron-builder/issues/4204)
* **mac:** merge `fileAssociations` with existing `CFBundleDocumentTypes` if defined in `mac.extendInfo` ([#8035](https://github.com/electron-userland/electron-builder/issues/8035)) ([94677f3](https://github.com/electron-userland/electron-builder/commit/94677f3d70866582635c717b042194f0c75bbf01))
* **mac:** normalize filename to NFD form ([#7901](https://github.com/electron-userland/electron-builder/issues/7901)) ([f83f05f](https://github.com/electron-userland/electron-builder/commit/f83f05f6f24a36b96d0e0c7786e1a12e5c762389))
* **mac:** only skip notarization step when `notarize` is explicitly false ([#8065](https://github.com/electron-userland/electron-builder/issues/8065)) ([5681777](https://github.com/electron-userland/electron-builder/commit/5681777a808d49756f3a95d18cc589218be44878))
* macOS Auto updater using old update ([4e63640](https://github.com/electron-userland/electron-builder/commit/4e63640831c8bb1bf868a48736ed7841d5a5b37c)), closes [#1200](https://github.com/electron-userland/electron-builder/issues/1200)
* macOS failing when there is no old icon ([#1658](https://github.com/electron-userland/electron-builder/issues/1658)) ([ac44fcd](https://github.com/electron-userland/electron-builder/commit/ac44fcd295c9812334db97cb98b89e7a701f8f9d))
* **macos:** added keychain flag to getProvisioningProfileAsync ([#4332](https://github.com/electron-userland/electron-builder/issues/4332)) ([965392b](https://github.com/electron-userland/electron-builder/commit/965392bd5e800d50b5ea8c647b1dc00ef1f31495))
* **mac:** Pass `buildOptions` down to notarization for platform-specific build options ([#7886](https://github.com/electron-userland/electron-builder/issues/7886)) ([d7e39f0](https://github.com/electron-userland/electron-builder/commit/d7e39f05c55287ea32fd0f978ecb41078931d6b6))
* **mac:** Pass platformName and options in doPack ([#5511](https://github.com/electron-userland/electron-builder/issues/5511)) ([f78e3f4](https://github.com/electron-userland/electron-builder/commit/f78e3f48d7cde71fd52fe1024c114bbe23f83562))
* **mac:** remove internet-enable from macOS 10.15 ([#4405](https://github.com/electron-userland/electron-builder/issues/4405)) ([#4531](https://github.com/electron-userland/electron-builder/issues/4531)) ([8dd587f](https://github.com/electron-userland/electron-builder/commit/8dd587facd5b57ab1c8f3ab10db1a77b01a8acf1))
* **mac:** remove not required com.apple.security.cs.allow-dyld-environment-variables ([f6b6e23](https://github.com/electron-userland/electron-builder/commit/f6b6e23d31a86737b61f10ca4dc19cbc95b99ab0))
* **mac:** Remove redundant signing op for mas and mas-dev targets ([#4321](https://github.com/electron-userland/electron-builder/issues/4321)) ([5692281](https://github.com/electron-userland/electron-builder/commit/56922819f0be39fffb31bbb50437ad4fcdde7365))
* **mac:** revert mac differential autoupdate ([#8091](https://github.com/electron-userland/electron-builder/issues/8091)) ([e2a181d](https://github.com/electron-userland/electron-builder/commit/e2a181d9fe3fbdd84690359e275daaef24584729)), closes [#7709](https://github.com/electron-userland/electron-builder/issues/7709)
* **mac:** should normalize unicode strings from file system before used in string compare ([#4841](https://github.com/electron-userland/electron-builder/issues/4841)) ([37a17f2](https://github.com/electron-userland/electron-builder/commit/37a17f222b4802282c0638c163f76df35983c8d3))
* **mac:** signing cert filter incorrectly selects certificates ([#6094](https://github.com/electron-userland/electron-builder/issues/6094)) ([#6101](https://github.com/electron-userland/electron-builder/issues/6101)) ([#6105](https://github.com/electron-userland/electron-builder/issues/6105)) ([4a177dc](https://github.com/electron-userland/electron-builder/commit/4a177dc01c9119443426f1eb500afb836fd4f381))
* **mac:** signing NSIS on mac  ([#8090](https://github.com/electron-userland/electron-builder/issues/8090)) ([2c147ad](https://github.com/electron-userland/electron-builder/commit/2c147addb09385008cf661c952e7ce390a254d8e))
* **mac:** Update entitlements.plist to be compliant with electron-notarize requirements ([#4491](https://github.com/electron-userland/electron-builder/issues/4491)) ([692091b](https://github.com/electron-userland/electron-builder/commit/692091b981f120274aa2941ab038137dceddef92))
* **mac:** Update mac notarize keychain env var to be optional. Fixes: [#8015](https://github.com/electron-userland/electron-builder/issues/8015) ([#8022](https://github.com/electron-userland/electron-builder/issues/8022)) ([9d1d150](https://github.com/electron-userland/electron-builder/commit/9d1d150896a763d3630418bf5be8fd3a070c0c40))
* **mac:** use `notarytool` with only api key auth ([#7896](https://github.com/electron-userland/electron-builder/issues/7896)) ([65817e0](https://github.com/electron-userland/electron-builder/commit/65817e0edc43a2e6707fab835b0bbe680bd0b1e4))
* **mac:** use `uname -a` to get arch before testing 'process.arch' on mac silicon  ([#6381](https://github.com/electron-userland/electron-builder/issues/6381)) ([828fcd3](https://github.com/electron-userland/electron-builder/commit/828fcd378c2df28763893ef68f92d5b1a72fead3))
* **mac:** use `zip` instead of `7z` if name contains NFD characters ([#7929](https://github.com/electron-userland/electron-builder/issues/7929)) ([0f43989](https://github.com/electron-userland/electron-builder/commit/0f439890229431f02c7f86d5bf523e940e217657))
* **mac:** use hash instead of identity name to sign ([ee90ff2](https://github.com/electron-userland/electron-builder/commit/ee90ff28246928cfb6a0e4364f0c527d77b697f7)), closes [#1629](https://github.com/electron-userland/electron-builder/issues/1629)
* **mac:** use Identity `hash` instead of `name` if it exists ([#7622](https://github.com/electron-userland/electron-builder/issues/7622)) ([4652416](https://github.com/electron-userland/electron-builder/commit/46524169cefbfa18e342d7fa19e79e710aae848e))
* **mac:** Workaround for hdiutil randomly failing ([#5431](https://github.com/electron-userland/electron-builder/issues/5431)) ([#5464](https://github.com/electron-userland/electron-builder/issues/5464)) ([53270cf](https://github.com/electron-userland/electron-builder/commit/53270cfe4eb2de1ac55e4b281c2c53483d4d1f2e))
* **mac:** Wrap hditutil detach in retry w/ backoff ([#7600](https://github.com/electron-userland/electron-builder/issues/7600)) ([4dce371](https://github.com/electron-userland/electron-builder/commit/4dce3718abd75b8d0e29f37f6ba0ee1e76353c65))
* Make BUILD_NUMBER higher priority than CI buildnumbers ([#2121](https://github.com/electron-userland/electron-builder/issues/2121)) ([6e1c48b](https://github.com/electron-userland/electron-builder/commit/6e1c48b857b1022b5dc443307ad8c5823f1521d7))
* make computeSignToolArgs usable in custom signing ([cfec5c6](https://github.com/electron-userland/electron-builder/commit/cfec5c6048d050333dd3a0422d082cb4808a2b87)), closes [#2397](https://github.com/electron-userland/electron-builder/issues/2397)
* make error output in case of app-builder failure more clear ([678d4c5](https://github.com/electron-userland/electron-builder/commit/678d4c5d5ac869358c947950546575798a200e24))
* make file association name optional ([248855c](https://github.com/electron-userland/electron-builder/commit/248855c1739bcf6ce972afb02deb9dc887df7e53)), closes [#1069](https://github.com/electron-userland/electron-builder/issues/1069)
* Make sure the documentation for this option clearly states the security implications of turning it on [#1524](https://github.com/electron-userland/electron-builder/issues/1524) ([b0ce309](https://github.com/electron-userland/electron-builder/commit/b0ce309d1496698942bbeed715262867f375eb39))
* Manually reseting `GYP_MSVS_VERSION` for multi-arch builds before `beforePack` ([#7387](https://github.com/electron-userland/electron-builder/issues/7387)) ([aeffe08](https://github.com/electron-userland/electron-builder/commit/aeffe080e07f11057134947e09021cd9d6712935))
* MAS builds should respect arch suffix per `defaultArch` config ([#7383](https://github.com/electron-userland/electron-builder/issues/7383)) ([e5748b3](https://github.com/electron-userland/electron-builder/commit/e5748b3df35676cf6e411c6c47fc4fc56e0a26f2))
* **mas:** Allow signing with "3rd Party Mac Developer Application" ([#6970](https://github.com/electron-userland/electron-builder/issues/6970)) ([28c07b4](https://github.com/electron-userland/electron-builder/commit/28c07b4392161732ee221dbb3f3a3633899cfa33))
* **mas:** Cannot create MAS build ([1acd5b3](https://github.com/electron-userland/electron-builder/commit/1acd5b315d742353c44a2d71e436ac28d0d8438d)), closes [#4048](https://github.com/electron-userland/electron-builder/issues/4048)
* **mas:** do not try to build pkg for mas-dev ([fe76099](https://github.com/electron-userland/electron-builder/commit/fe760991115566c705496a85e6b4e39c74c47ef7)), closes [#1196](https://github.com/electron-userland/electron-builder/issues/1196)
* **mas:** rename login helper and set unique id ([35c8cee](https://github.com/electron-userland/electron-builder/commit/35c8cee3e5a3cabcb9b33c8aad8f4902e5a87ac7)), closes [#2719](https://github.com/electron-userland/electron-builder/issues/2719)
* **mas:** set hardenedRuntime to false by default for mas and mas-dev ([#4548](https://github.com/electron-userland/electron-builder/issues/4548)) ([f1e3242](https://github.com/electron-userland/electron-builder/commit/f1e324204eb40b36b017bac4f9c873361325f0a3))
* Merge arrays from same config key in cascading electron-builder configs, such as `files` ([#6841](https://github.com/electron-userland/electron-builder/issues/6841)) ([9dc13ba](https://github.com/electron-userland/electron-builder/commit/9dc13ba2c1e7a852d3f743833f1bde17b62f1806))
* Migrate to electron-rebuild for handling native dependencies to fix compatibility with newer versions of electron ([#7196](https://github.com/electron-userland/electron-builder/issues/7196)) ([5616f23](https://github.com/electron-userland/electron-builder/commit/5616f23ce3d03a4e71c7b7bd515ec958b1631b8b))
* mime lib import is incorrect ([37b84fb](https://github.com/electron-userland/electron-builder/commit/37b84fb1b5d77390a7536a2def672d995a451580)), closes [#5861](https://github.com/electron-userland/electron-builder/issues/5861)
* missing [@types](https://github.com/types) dependencies for output d.ts files ([#7568](https://github.com/electron-userland/electron-builder/issues/7568)) ([c9d20db](https://github.com/electron-userland/electron-builder/commit/c9d20db964cce991dab137ec0105d40d8eacd95c))
* missing html extension for multi language license files in nsis target ([#7339](https://github.com/electron-userland/electron-builder/issues/7339)) ([8f94978](https://github.com/electron-userland/electron-builder/commit/8f94978c41d63e9fb4aa70a1df67f25804fdaf84))
* Missing peer dependency: ajv@>=5.0.3-beta.0 ([6d890ee](https://github.com/electron-userland/electron-builder/commit/6d890ee7393f2e5bb117048be80b4c456b2f9798)), closes [#1344](https://github.com/electron-userland/electron-builder/issues/1344)
* missing quote syntax error in nsis uninstaller ([#7490](https://github.com/electron-userland/electron-builder/issues/7490)) ([278a3df](https://github.com/electron-userland/electron-builder/commit/278a3df3c738dbe0d2240f338e901774b7d578c5))
* more clear error if cannot extract publisher name from code signing certificate ([1254197](https://github.com/electron-userland/electron-builder/commit/12541978d252f7c87679a134264865dbc71b1d94))
* more clear error if env required for macro is not defined ([00b1e0b](https://github.com/electron-userland/electron-builder/commit/00b1e0b694181d2e408496b2ddde575c1986aab6))
* more clear error if env required for macro is not defined ([773f726](https://github.com/electron-userland/electron-builder/commit/773f726c82f3a6fb83a0947efdcddb321da12a56))
* more clear handling of onTagOrDraft ([817340a](https://github.com/electron-userland/electron-builder/commit/817340a5f91e9d1e81bcd07a0c42a3f04d660f5b))
* move `disableSanityCheckAsar` to within `checkFileInPackage` for non-asar verification ([#8124](https://github.com/electron-userland/electron-builder/issues/8124)) ([e029258](https://github.com/electron-userland/electron-builder/commit/e02925818258954747188a5eb2ece5047452b89a))
* moving typed-emitter from devDependency to dependencies ([#6889](https://github.com/electron-userland/electron-builder/issues/6889)) ([869ec27](https://github.com/electron-userland/electron-builder/commit/869ec27fd1d99b9913875cb4d7ae7c733c1f3e25))
* **msi:** escape MSI directory id ([c65af10](https://github.com/electron-userland/electron-builder/commit/c65af10bf029fd63beb06141c70dafdc4f465d84)), closes [#2841](https://github.com/electron-userland/electron-builder/issues/2841)
* **msi:** fix broken shortcut icon when using msi target, adding msi option `iconId` ([#6247](https://github.com/electron-userland/electron-builder/issues/6247)) ([a9ec90d](https://github.com/electron-userland/electron-builder/commit/a9ec90d539fdbb5786692629275b1a89bfd7aec4))
* **msi:** Inconsistent installation folder names for NSIS & MSI builds resulting in 2 apps after msi app update ([657b43f](https://github.com/electron-userland/electron-builder/commit/657b43fd54a55ff55371f9f1dc08a27f1aeab852)), closes [#3100](https://github.com/electron-userland/electron-builder/issues/3100)
* **msi:** manually escape XML special characters when building project.wxs XML ([#6878](https://github.com/electron-userland/electron-builder/issues/6878)) ([2ece89a](https://github.com/electron-userland/electron-builder/commit/2ece89a08e7fb74a11ba3d0f5980b2a57c8b34ad))
* **msi:** msi target error ([734cbaf](https://github.com/electron-userland/electron-builder/commit/734cbaf9e8a1f783b1035277ca6e6c391fd708db)), closes [#2798](https://github.com/electron-userland/electron-builder/issues/2798)
* **msi:** Msi target separates files and subdirectories into different directories ([7f75b45](https://github.com/electron-userland/electron-builder/commit/7f75b4572f7254ab977c736467a07d5c3b7da554)), closes [#2272](https://github.com/electron-userland/electron-builder/issues/2272)
* **msi:** put appId in file shortcut to fix notifications in win8/win10 ([#2908](https://github.com/electron-userland/electron-builder/issues/2908)) ([f4212a6](https://github.com/electron-userland/electron-builder/commit/f4212a6ecb029c3e41b0cc197e91db886772aeec)), closes [#2906](https://github.com/electron-userland/electron-builder/issues/2906)
* **msi:** The Directory/[@id](https://github.com/id) attribute's value is too long for an identifier ([c01cc64](https://github.com/electron-userland/electron-builder/commit/c01cc649329e03192a291634c4f1c765aa1bad39)), closes [#3027](https://github.com/electron-userland/electron-builder/issues/3027)
* **multipleRangeDownloader:** when response ends nothing more happens ([#4817](https://github.com/electron-userland/electron-builder/issues/4817)) ([0443055](https://github.com/electron-userland/electron-builder/commit/0443055f0359e16d77837c3d46dd88e412129e62))
* node module copying - do not ignore optional deps ([70b44ca](https://github.com/electron-userland/electron-builder/commit/70b44caf062e4b828c5cd4b5f76521d2cc043e5c))
* node-pre-gyp stripped in packed dir ([2b1686b](https://github.com/electron-userland/electron-builder/commit/2b1686b8d0c6e7a883eaf8a7d99417f2dc95c810)), closes [#1815](https://github.com/electron-userland/electron-builder/issues/1815)
* notarization with an apple API key ([#7951](https://github.com/electron-userland/electron-builder/issues/7951)) ([869c7e4](https://github.com/electron-userland/electron-builder/commit/869c7e4652a5d5a3562e25723d6cedd622ab657b))
* nsis installer /D installation path override ([#2885](https://github.com/electron-userland/electron-builder/issues/2885)) ([2fb0ee2](https://github.com/electron-userland/electron-builder/commit/2fb0ee2b9f27e716e9e62a0690f76137c6394246))
* NSIS uninstaller doesn't kill child processes ([ad199c4](https://github.com/electron-userland/electron-builder/commit/ad199c45525814aba4c457254a2a259c44383486)), closes [#2516](https://github.com/electron-userland/electron-builder/issues/2516)
* nsis update fails for private github repos ([#4568](https://github.com/electron-userland/electron-builder/issues/4568)) ([beb2729](https://github.com/electron-userland/electron-builder/commit/beb272906c49175da4ae97746fcb5f72d5d0acf8))
* nsis web build ([#4620](https://github.com/electron-userland/electron-builder/issues/4620)) ([d5a00c3](https://github.com/electron-userland/electron-builder/commit/d5a00c3e519a995a1540c8b9e89a4be7432db7f8))
* **nsis:**  稍后 typo ([#3524](https://github.com/electron-userland/electron-builder/issues/3524)) ([947ae66](https://github.com/electron-userland/electron-builder/commit/947ae668633917dd940880ccc926c6843fe1f237))
* nsis-web target set APP_PACKAGE_URL_IS_INCOMPLETE when specifying appPackageUrl ([#6964](https://github.com/electron-userland/electron-builder/issues/6964)) ([b0e1b6f](https://github.com/electron-userland/electron-builder/commit/b0e1b6f8af95bc371c0bc91df65965f3f60f3a87))
* **nsis-web:** connectivity issues with nsis-web ([0ee226b](https://github.com/electron-userland/electron-builder/commit/0ee226baf89dd5f951dc3678e3b74c09df87385b)), closes [#2049](https://github.com/electron-userland/electron-builder/issues/2049)
* **nsis:** `runAfterFinish: false` not working when `oneClick: true` ([9da87b9](https://github.com/electron-userland/electron-builder/commit/9da87b99ebdf964a0810158fde9aaae34c156a49))
* **nsis:** add `+` as safe symbol for product name ([e7e2a82](https://github.com/electron-userland/electron-builder/commit/e7e2a82820da6e33609cb5240dbb38bc9d17b07b))
* **nsis:** allow file associations for assisted installer ([cdf03c8](https://github.com/electron-userland/electron-builder/commit/cdf03c8a655d3ea4a8e98a0c390712a30f96b4fa)), closes [#2496](https://github.com/electron-userland/electron-builder/issues/2496)
* **nsis:** allow use dot in the productName ([67305af](https://github.com/electron-userland/electron-builder/commit/67305af07ca018b7849d42638c3cead961f56bdf)), closes [#2291](https://github.com/electron-userland/electron-builder/issues/2291)
* **nsis:** Application Icon Missing from "Remove Programs" and "Settings->Apps & Features" ([9c62be9](https://github.com/electron-userland/electron-builder/commit/9c62be923d7be773d69e78a053cb5463c6c8c85f)), closes [#1108](https://github.com/electron-userland/electron-builder/issues/1108)
* **nsis:** AutoUpdate takes 60 seconds to fail validating signature on Windows 7 due to PowerShell version [#2421](https://github.com/electron-userland/electron-builder/issues/2421) ([da96e73](https://github.com/electron-userland/electron-builder/commit/da96e734205eee0a754c05df65b83e8316d10bb3))
* **nsis:** build portable in parallel to nsis ([918a317](https://github.com/electron-userland/electron-builder/commit/918a31730633da3bc8b5a8768e7732f97ba047e9)), closes [#1340](https://github.com/electron-userland/electron-builder/issues/1340)
* **nsis:** Building NSIS installers broken after switching from 22.10.5 to 22.11.1 ([#5873](https://github.com/electron-userland/electron-builder/issues/5873)) ([3e6c10f](https://github.com/electron-userland/electron-builder/commit/3e6c10f2d227c3de001170f1ea6e0b590b5a9794)), closes [#5863](https://github.com/electron-userland/electron-builder/issues/5863)
* **nsis:** change Russian locale from "game" to "application" ([#4743](https://github.com/electron-userland/electron-builder/issues/4743)) ([ffa2a4e](https://github.com/electron-userland/electron-builder/commit/ffa2a4e8328275fe03ec408b6c9909694bc7ae10))
* **nsis:** check that out file is not blocked ([39faac5](https://github.com/electron-userland/electron-builder/commit/39faac55ff669a0db2c4cae7e954b1252ed9c404))
* **nsis:** cleanup temporary 7z folder ([#6793](https://github.com/electron-userland/electron-builder/issues/6793)) ([85a3e55](https://github.com/electron-userland/electron-builder/commit/85a3e5595e64346514dd7f5fade42e3632a18ee0))
* **nsis:** Cloning packager.config to prevent override ([5b8abcb](https://github.com/electron-userland/electron-builder/commit/5b8abcb84c7e9e4b87c532ba823259520d2939e2)), closes [#1340](https://github.com/electron-userland/electron-builder/issues/1340) [#1340](https://github.com/electron-userland/electron-builder/issues/1340)
* **nsis:** CopyFiles requires CreateDirectory ([8ae6c01](https://github.com/electron-userland/electron-builder/commit/8ae6c0165317456f68cac0f5e5722b545d66c52e))
* **nsis:** correctly remove shortcut and only remove directory if its empty ([333a45d](https://github.com/electron-userland/electron-builder/commit/333a45d1866bceb1f4b780eaa7d2fef180d002a8)), closes [#2381](https://github.com/electron-userland/electron-builder/issues/2381)
* **nsis:** create appdata directory before copying installer ([#3400](https://github.com/electron-userland/electron-builder/issues/3400)) ([0c28515](https://github.com/electron-userland/electron-builder/commit/0c2851538fede0ce99508f4c4354a9f28f4f822d))
* **nsis:** cs locale typos in messages ([#5358](https://github.com/electron-userland/electron-builder/issues/5358)) ([0fb69b5](https://github.com/electron-userland/electron-builder/commit/0fb69b5d11e5c8aa707b7af709a0ab52f5019a9f))
* **nsis:** Custom NSIS Script !include could not find nsh file ([3fbf113](https://github.com/electron-userland/electron-builder/commit/3fbf11331a942e70a284240e61dde738249b0354)), closes [#1239](https://github.com/electron-userland/electron-builder/issues/1239)
* **nsis:** Decide to use elevate.exe for installer when update using nsis packElevateHelper option in electron-builder config ([#6787](https://github.com/electron-userland/electron-builder/issues/6787)) ([eb456a8](https://github.com/electron-userland/electron-builder/commit/eb456a87b0603dcc0e6d777c2b8e1c2e7b64d3a6))
* **nsis:** differential download ([#5948](https://github.com/electron-userland/electron-builder/issues/5948)) ([39ac82f](https://github.com/electron-userland/electron-builder/commit/39ac82f89a1a95b924bf1b9651ce143dd219687d))
* **nsis:** differential update support for empty files ([105d4d4](https://github.com/electron-userland/electron-builder/commit/105d4d42a8e2b9224a968681be6504bb0267c4e8)), closes [#2109](https://github.com/electron-userland/electron-builder/issues/2109)
* **nsis:** Do not abort when uninstaller fails ([#5292](https://github.com/electron-userland/electron-builder/issues/5292)) ([ea9281b](https://github.com/electron-userland/electron-builder/commit/ea9281b77bb484bce67cfc94ef5d85004927b124))
* **nsis:** do not add ` (only current user)` note to uninstall display name ([8c3ce8a](https://github.com/electron-userland/electron-builder/commit/8c3ce8a4597a7789f08c38fb432d1220f97cbd36))
* **nsis:** do not remove non-empty menu directory ([df13706](https://github.com/electron-userland/electron-builder/commit/df13706e43e6817d25fc846a65c2e4a765e2f924)), closes [#2381](https://github.com/electron-userland/electron-builder/issues/2381)
* **nsis:** do not schedule file to remove after reboot if removal failed ([07b11a2](https://github.com/electron-userland/electron-builder/commit/07b11a29581a8f16a852ca7917065e853ccf7fbc))
* **nsis:** don't force run assisted installer if not silent ([edb82af](https://github.com/electron-userland/electron-builder/commit/edb82afd328e51fe736da92cd389b5061bdf6318)), closes [#2902](https://github.com/electron-userland/electron-builder/issues/2902) [#2619](https://github.com/electron-userland/electron-builder/issues/2619)
* **nsis:** don't kill ourselves when upgrading ([#5445](https://github.com/electron-userland/electron-builder/issues/5445)) ([a1a3ef3](https://github.com/electron-userland/electron-builder/commit/a1a3ef325d0ea5d6dec250dc8b1e0007b890d28a))
* **nsis:** Ensure application name sub-folder on fresh installs. ([#7552](https://github.com/electron-userland/electron-builder/issues/7552)) ([e3fc9b5](https://github.com/electron-userland/electron-builder/commit/e3fc9b544cc8c6728ffd77a45408d6e0e87dbb46)), closes [#6885](https://github.com/electron-userland/electron-builder/issues/6885)
* **nsis:** ensure that installer process is not killed as child process ([51a7cff](https://github.com/electron-userland/electron-builder/commit/51a7cff53af2304969c580dba541d5c8085fc940)), closes [#2516](https://github.com/electron-userland/electron-builder/issues/2516)
* **nsis:** Error handling if uninstaller cannot be launched ([#4674](https://github.com/electron-userland/electron-builder/issues/4674)) ([442493b](https://github.com/electron-userland/electron-builder/commit/442493b0539d7e33a26d84cdcdd8ca687b0246d2))
* **nsis:** escape space in command ([b370006](https://github.com/electron-userland/electron-builder/commit/b3700063be377e474243852642a80df7fc2cc377)), closes [#1758](https://github.com/electron-userland/electron-builder/issues/1758)
* **nsis:** fix cli config error when use Boolean value in -c.nsis config ([#4528](https://github.com/electron-userland/electron-builder/issues/4528)) ([ac8e9aa](https://github.com/electron-userland/electron-builder/commit/ac8e9aa57d32940eb0c9566a89de57890a9df904))
* **nsis:** fix spawnAndWrite reject in util ([#4566](https://github.com/electron-userland/electron-builder/issues/4566)) ([2229b28](https://github.com/electron-userland/electron-builder/commit/2229b28107e8ce65461674a11f0c971feb961ec9))
* **nsis:** fix typo in German installer message ([#6960](https://github.com/electron-userland/electron-builder/issues/6960)) ([6e90c84](https://github.com/electron-userland/electron-builder/commit/6e90c8459111ec046b91f8ae5da1990af0bbe942))
* **nsis:** Fixed --force-run ([227d779](https://github.com/electron-userland/electron-builder/commit/227d7791aa6fc7a122ef7152e2fe478f46cb64a0)), closes [#2179](https://github.com/electron-userland/electron-builder/issues/2179)
* **nsis:** generate uninstaller without elevating ([#5575](https://github.com/electron-userland/electron-builder/issues/5575)) ([#6013](https://github.com/electron-userland/electron-builder/issues/6013)) ([b00aea3](https://github.com/electron-userland/electron-builder/commit/b00aea32107cd379b8489f7abea493d16fe38197))
* **nsis:** if allowToChangeInstallationDirectory enabled, do not show page if updated ([5b71f6d](https://github.com/electron-userland/electron-builder/commit/5b71f6d22689b0adf979e0e041e50fab8716f0fc)), closes [#1715](https://github.com/electron-userland/electron-builder/issues/1715)
* **nsis:** if unicode disabled, add only english custom translations ([88e36db](https://github.com/electron-userland/electron-builder/commit/88e36dbfcfed231127ba3af07c5ace4cec4bbf6d))
* **nsis:** Ignore other users processes during per-user installation ([#6472](https://github.com/electron-userland/electron-builder/issues/6472)) ([e3d06af](https://github.com/electron-userland/electron-builder/commit/e3d06afae1236d44e4b6e670b453b260b1f74d84)), closes [#6104](https://github.com/electron-userland/electron-builder/issues/6104)
* **nsis:** improve Windows installer task kill process (related to child processes) ([39e6783](https://github.com/electron-userland/electron-builder/commit/39e678333a7f2f79e6cbd840167adee1179b64db)), closes [#2894](https://github.com/electron-userland/electron-builder/issues/2894)
* **nsis:** include path must be quoted ([4e32e17](https://github.com/electron-userland/electron-builder/commit/4e32e1764abe5229d2fc1965310237b8cd176fb9)), closes [#2002](https://github.com/electron-userland/electron-builder/issues/2002)
* **nsis:** Incorrect app-update.yml for Windows 32bit ([5cfc693](https://github.com/electron-userland/electron-builder/commit/5cfc69353c2915566b8a9a148ccaa7a78e22219e)), closes [#1282](https://github.com/electron-userland/electron-builder/issues/1282)
* **nsis:** Installer not closed when 'runAfterFinish: false' ([#2974](https://github.com/electron-userland/electron-builder/issues/2974)) ([6a08b50](https://github.com/electron-userland/electron-builder/commit/6a08b50a8073bb8bf396da3933e7dbb1f047bc3a)), closes [#2951](https://github.com/electron-userland/electron-builder/issues/2951)
* **nsis:** Keep existing desktop/menu/taskbar shortcuts after update ([2f3d7d8](https://github.com/electron-userland/electron-builder/commit/2f3d7d8e631698d5e6ddccb90655a1ea707b7dc8)), closes [#1653](https://github.com/electron-userland/electron-builder/issues/1653)
* **nsis:** keep injected logger state ([#5596](https://github.com/electron-userland/electron-builder/issues/5596)) ([be4a1fb](https://github.com/electron-userland/electron-builder/commit/be4a1fb05b6734800aa97652e856de1308e4a2f2))
* **nsis:** KeepShortcuts mechanism is not functional ([#2085](https://github.com/electron-userland/electron-builder/issues/2085)) ([894ba6d](https://github.com/electron-userland/electron-builder/commit/894ba6dd48e9034c9de09799c81eece3dd6a3cf4)), closes [#2084](https://github.com/electron-userland/electron-builder/issues/2084)
* **nsis:** license file injection if html is not used ([78d5458](https://github.com/electron-userland/electron-builder/commit/78d5458e6b3c27a1fc9dc2d30a9cc460e141840e))
* **nsis:** make killing the running app silent ([#3624](https://github.com/electron-userland/electron-builder/issues/3624)) ([9cb0069](https://github.com/electron-userland/electron-builder/commit/9cb006971450820ff31fdbe5fb59e23c88340b86))
* **nsis:** missed "Installing, please wait" text ([c5d3441](https://github.com/electron-userland/electron-builder/commit/c5d34410157a569f3c48fc6c0c8d4ec3f3a3765f)), closes [#1630](https://github.com/electron-userland/electron-builder/issues/1630)
* **nsis:** Missing entry in Add / Remove window of Control panel when using custom GUID ([5ed7883](https://github.com/electron-userland/electron-builder/commit/5ed7883a9964e28f48c65c48884600df3c25d6eb)), closes [#2749](https://github.com/electron-userland/electron-builder/issues/2749)
* **nsis:** move generated custom messages to separate files (to avoid stdin encoding issues on Windows) ([5b83860](https://github.com/electron-userland/electron-builder/commit/5b8386088dadf4f947b20aca5edc08054dbadc5c)), closes [#1447](https://github.com/electron-userland/electron-builder/issues/1447)
* **nsis:** move useZip to common nsis options ([e7112d6](https://github.com/electron-userland/electron-builder/commit/e7112d6750433ecf0747b65f9993c0909951d9d3))
* **nsis:** Must be error if file association is set, but perMachine not ([96c8ed9](https://github.com/electron-userland/electron-builder/commit/96c8ed97157f89c789221191b46757e41cfbf961)), closes [#772](https://github.com/electron-userland/electron-builder/issues/772)
* **nsis:** new translations for various strings in nsis messages template ([#6827](https://github.com/electron-userland/electron-builder/issues/6827)) ([fa72861](https://github.com/electron-userland/electron-builder/commit/fa72861f6cd2de97d191f1b2bbfddc6edf48ab6d))
* **nsis:** NSIS installer is crashing on "Exit" (Admins on Win7) ([#2285](https://github.com/electron-userland/electron-builder/issues/2285)) ([d00ab96](https://github.com/electron-userland/electron-builder/commit/d00ab962ac58cb6ac4606d1994c1c44957dfcc8a)), closes [#2284](https://github.com/electron-userland/electron-builder/issues/2284)
* **nsis:** NSIS uninstaller doesn't kill child processes ([b6580d8](https://github.com/electron-userland/electron-builder/commit/b6580d83ec907e412efbdab708109ff5d325a246)), closes [#2516](https://github.com/electron-userland/electron-builder/issues/2516)
* **nsis:** NSIS Uninstaller registry entry format change ([#4069](https://github.com/electron-userland/electron-builder/issues/4069)) ([7518aee](https://github.com/electron-userland/electron-builder/commit/7518aee8e1abe0516071b350748e84dc47e35cf7))
* **nsis:** nsis-web ignoring the artifactName config parameter for GitHub ([8f4f443](https://github.com/electron-userland/electron-builder/commit/8f4f4439ee722055af79981c4c4b7ef1269cae72)), closes [#2162](https://github.com/electron-userland/electron-builder/issues/2162)
* **nsis:** nsis-web: Windows 7 and above is required when installing on Windows 7 ([d451308](https://github.com/electron-userland/electron-builder/commit/d4513087c4514d974865efd6b2f0f4e880491093)), closes [#2420](https://github.com/electron-userland/electron-builder/issues/2420)
* **nsis:** output files sometimes locked by virus scanners ([#5005](https://github.com/electron-userland/electron-builder/issues/5005)) ([#5143](https://github.com/electron-userland/electron-builder/issues/5143)) ([a6d00ab](https://github.com/electron-userland/electron-builder/commit/a6d00ab4f5b146f6e9669395f4dac5b5469804e4))
* **nsis:** per-machine installs must properly elevate during silent install/updates ([#6450](https://github.com/electron-userland/electron-builder/issues/6450)) ([661a652](https://github.com/electron-userland/electron-builder/commit/661a6522520e9ea59549cb7e18986fcfb58e873a)), closes [#6438](https://github.com/electron-userland/electron-builder/issues/6438) [#6073](https://github.com/electron-userland/electron-builder/issues/6073) [#6425](https://github.com/electron-userland/electron-builder/issues/6425) [#5468](https://github.com/electron-userland/electron-builder/issues/5468)
* **nsis:** prevent a missing package.7z from nuking the application ([e20bbdd](https://github.com/electron-userland/electron-builder/commit/e20bbdd1c8cd7caadc2dbf8af3d3243c68c0d564)), closes [#2929](https://github.com/electron-userland/electron-builder/issues/2929) [#2859](https://github.com/electron-userland/electron-builder/issues/2859)
* **NSIS:** prevent partial overwrites during `Nsis7z::Extract` ([#6547](https://github.com/electron-userland/electron-builder/issues/6547)) ([bea51d6](https://github.com/electron-userland/electron-builder/commit/bea51d6a8bb828d9b34734908f13b667aa55b0e9))
* **nsis:** regression since 20.40.0 - nsis uninstaller is not silent ([4d92abf](https://github.com/electron-userland/electron-builder/commit/4d92abfd5c7b4ee4774b3055c9752d75bcf5c423)), closes [#3813](https://github.com/electron-userland/electron-builder/issues/3813)
* **nsis:** replace `SYSTEMROOT` with `SYSDIR` ([#8133](https://github.com/electron-userland/electron-builder/issues/8133)) ([44b0446](https://github.com/electron-userland/electron-builder/commit/44b04463bf581b4c013586c9010733b518a802a4))
* **nsis:** Resource busy (elevate.exe) ([8738e18](https://github.com/electron-userland/electron-builder/commit/8738e18b32eeea58062205c15847bccaf6d5b42f)), closes [#2123](https://github.com/electron-userland/electron-builder/issues/2123) [#2103](https://github.com/electron-userland/electron-builder/issues/2103)
* **nsis:** respect --force-run when RUN_AFTER_FINISH is false ([3557aae](https://github.com/electron-userland/electron-builder/commit/3557aaef3e8def6b3a122cb537999933703d3ad9)), closes [#3093](https://github.com/electron-userland/electron-builder/issues/3093)
* **nsis:** respect multiLanguageInstaller option ([7a5338f](https://github.com/electron-userland/electron-builder/commit/7a5338f32ebc8b482e89ade59a87f7c8e2b142cc))
* **nsis:** retry closing the app until success ([#5902](https://github.com/electron-userland/electron-builder/issues/5902)) ([d307c21](https://github.com/electron-userland/electron-builder/commit/d307c21b34abee1cd2b8dcd3e705995914dda70f))
* **nsis:** revert NSIS to 3.0.1 since 3.0.2 leads to crash on Windows 10 ([1677629](https://github.com/electron-userland/electron-builder/commit/167762995b822db42d53c226b934229c20b9ec94)), closes [#2134](https://github.com/electron-userland/electron-builder/issues/2134)
* **nsis:** revert to 3.0.4.1 ([9c43cc3](https://github.com/electron-userland/electron-builder/commit/9c43cc369a764d361d9d9a22d607febd1d451d92)), closes [#4793](https://github.com/electron-userland/electron-builder/issues/4793)
* **nsis:** set npm_config_target_libc ([acfd68d](https://github.com/electron-userland/electron-builder/commit/acfd68dd5d7d59c2899ac278a0318d401b232418)), closes [#3049](https://github.com/electron-userland/electron-builder/issues/3049)
* **nsis:** setting item `preCompressedFileExtensions` is invalid ([c3d6de4](https://github.com/electron-userland/electron-builder/commit/c3d6de46ace5b10a1c85cabbebc029751077741e)), closes [#3967](https://github.com/electron-userland/electron-builder/issues/3967)
* **nsis:** should close app when `Silent` and `ONE_CLICK` ([#6100](https://github.com/electron-userland/electron-builder/issues/6100)) ([baf640d](https://github.com/electron-userland/electron-builder/commit/baf640da459dc667240e6015deaf11adb2155063))
* **nsis:** Single quote in a product name leads to NSIS failure ([7a9d220](https://github.com/electron-userland/electron-builder/commit/7a9d22046a887d19932fe3c6f482c424406c0931)), closes [#2686](https://github.com/electron-userland/electron-builder/issues/2686)
* **nsis:** specify full path to system's find ([#6771](https://github.com/electron-userland/electron-builder/issues/6771)) ([e6c2a62](https://github.com/electron-userland/electron-builder/commit/e6c2a629839184d4f9d3fa99b580d8c96911ea65))
* **nsis:** StartApp doesn't work if menuCategory used ([683d58c](https://github.com/electron-userland/electron-builder/commit/683d58c442f1677dd4d286d1a4ebed3d594c895d)), closes [#1151](https://github.com/electron-userland/electron-builder/issues/1151) [#1412](https://github.com/electron-userland/electron-builder/issues/1412)
* **nsis:** turkish lang - missed translation leads to error ([9748776](https://github.com/electron-userland/electron-builder/commit/974877669403f2aa30ab443053266b1cd28970df))
* **nsis:** Uninstaller permission on 2nd invocation of exe installer ([516bd6c](https://github.com/electron-userland/electron-builder/commit/516bd6c83774085f6990379fac73516a16a6f9e0)), closes [#2225](https://github.com/electron-userland/electron-builder/issues/2225)
* **nsis:** Update FR message.yml ([#2989](https://github.com/electron-userland/electron-builder/issues/2989)) ([82b542c](https://github.com/electron-userland/electron-builder/commit/82b542c399eb766c60c65ac7d72104a605e5be13))
* **nsis:** update metainfo for nsis-web doesn't use github safe artifact name ([965be90](https://github.com/electron-userland/electron-builder/commit/965be90b3bfe9b1e55e72744222567c5c4c69f44)), closes [#1227](https://github.com/electron-userland/electron-builder/issues/1227)
* **nsis:** Update zh-tw translation ([#6773](https://github.com/electron-userland/electron-builder/issues/6773)) ([5a0bab1](https://github.com/electron-userland/electron-builder/commit/5a0bab115f4ede3f21e23e847c0d2dd7ecc99b16))
* NsisUpdater - only resolving true if pid !== undefined ([#7503](https://github.com/electron-userland/electron-builder/issues/7503)) ([a2ab1ff](https://github.com/electron-userland/electron-builder/commit/a2ab1ff36dbe99a9c9d22bde15e83482eb5be340)), closes [#7502](https://github.com/electron-userland/electron-builder/issues/7502)
* **nsis:** use correct slash for portable ([0edb668](https://github.com/electron-userland/electron-builder/commit/0edb668025d1ae1631d5b54667bd66a7d45da21c))
* **nsis:** use revertible+atomic rmdir on update and add user-confirmed retry loop ([#6551](https://github.com/electron-userland/electron-builder/issues/6551)) ([7b2a5e1](https://github.com/electron-userland/electron-builder/commit/7b2a5e1f19921e9da4aaaea8c01c78740f29f9dd))
* **nsis:** Use zlib compressor instead of lzma since in any case we pack app package using nsis7z ([83384fc](https://github.com/electron-userland/electron-builder/commit/83384fc6097b304770fee53a5a64c91aea057ca2))
* **nsis:** when app is uninstalling, uninstaller does not ([4eb29d9](https://github.com/electron-userland/electron-builder/commit/4eb29d90a1d03511d419f172232d50d751ba74b1))
* **nsis:** Windows 7 32 bit crash ([#2695](https://github.com/electron-userland/electron-builder/issues/2695)) ([858967b](https://github.com/electron-userland/electron-builder/commit/858967b779169d46454c5726f9edf81c814a2d23)), closes [#2518](https://github.com/electron-userland/electron-builder/issues/2518)
* **nsis:** Windows automatic update prompts "Application is running ([b3fb876](https://github.com/electron-userland/electron-builder/commit/b3fb876daaeb7cec1947043f47ce00525bc05c7b)), closes [#2014](https://github.com/electron-userland/electron-builder/issues/2014)
* **nsis:** Windows NSIS installer defaults to German if system language is not supported by electron-builder ([4bc17b4](https://github.com/electron-userland/electron-builder/commit/4bc17b44baa1f032a5efb1ba13608cb6e6bad115)), closes [#2517](https://github.com/electron-userland/electron-builder/issues/2517)
* obtaining a certificate from the store when sha1 is not specified in the configuration ([#4666](https://github.com/electron-userland/electron-builder/issues/4666)) ([07693b3](https://github.com/electron-userland/electron-builder/commit/07693b3d528a6475888d60fb491c1bda139deb12))
* older version of app-builder-bin included ([ff85d0e](https://github.com/electron-userland/electron-builder/commit/ff85d0e3e77ad52eb0ea36a791ebc600cdf56adc)), closes [#3600](https://github.com/electron-userland/electron-builder/issues/3600)
* on read error provide file path [#2265](https://github.com/electron-userland/electron-builder/issues/2265) ([a1d4ee3](https://github.com/electron-userland/electron-builder/commit/a1d4ee39675a41879a06146d5edea3a64bf214ab))
* one file in asar archive got corrupted ([e208f53](https://github.com/electron-userland/electron-builder/commit/e208f53ddbc8cbc8a7eedfe687dd551874d1ed4b)), closes [#1400](https://github.com/electron-userland/electron-builder/issues/1400)
* Only schedule upload for unique files after `afterAllArtifactBuild` ([#7715](https://github.com/electron-userland/electron-builder/issues/7715)) ([66bef0f](https://github.com/electron-userland/electron-builder/commit/66bef0f7f1a0371ff924d29ed5453f9b3222c1ab))
* optionalDependencies seems broken in 19.39.0+ ([7c1622d](https://github.com/electron-userland/electron-builder/commit/7c1622dc5b8a0219199e46363b7527f269f16009)), closes [#2220](https://github.com/electron-userland/electron-builder/issues/2220)
* optionally package nested node_modules ([#3185](https://github.com/electron-userland/electron-builder/issues/3185)) ([#5911](https://github.com/electron-userland/electron-builder/issues/5911)) ([13bdf74](https://github.com/electron-userland/electron-builder/commit/13bdf74121168183a2484527e5a904db41c5c407))
* Optionally remove DISABLE_WAYLAND for snaps via allowNativeWayland option ([#6961](https://github.com/electron-userland/electron-builder/issues/6961)) ([4c867aa](https://github.com/electron-userland/electron-builder/commit/4c867aa017a7ce2bf88138634b6d1e9a3bf34854))
* order files in asar for optimized differential updates ([#8128](https://github.com/electron-userland/electron-builder/issues/8128)) ([555dc90](https://github.com/electron-userland/electron-builder/commit/555dc909a97cbaab5bc5df6cdf6f1176dff1e604))
* order of platform and arch npm env vars ([#1029](https://github.com/electron-userland/electron-builder/issues/1029)) ([f01a9f7](https://github.com/electron-userland/electron-builder/commit/f01a9f7ded3d8151df9daf4633483b5d8fa8105f)), closes [/github.com/electron-userland/electron-builder/issues/1027#issuecomment-268066701](https://github.com//github.com/electron-userland/electron-builder/issues/1027/issues/issuecomment-268066701)
* **osx:** Code signing might need proxy to reach internet ([#2702](https://github.com/electron-userland/electron-builder/issues/2702)) ([68f31dc](https://github.com/electron-userland/electron-builder/commit/68f31dc1e33279ab784ca0adec50b533aca1dade)), closes [#2701](https://github.com/electron-userland/electron-builder/issues/2701)
* **packager:** report the correct status result when `doSign` exits early ([4d3fdfc](https://github.com/electron-userland/electron-builder/commit/4d3fdfcfe5c6b75cdb8fa8e89f6169c986949bcb))
* **packager:** return success status from doSign function calls ([48747ac](https://github.com/electron-userland/electron-builder/commit/48747ac9e1fe08f84b2335a8263eebc8f4c35561))
* **packager:** return success status from doSign function calls ([#7431](https://github.com/electron-userland/electron-builder/issues/7431)) ([eb842f7](https://github.com/electron-userland/electron-builder/commit/eb842f7faee3a261635fb3e59230e09c98840e40))
* **packager:** wait for artifactCreated completion event before starting an upload ([#6625](https://github.com/electron-userland/electron-builder/issues/6625)) ([c561af8](https://github.com/electron-userland/electron-builder/commit/c561af810d5de52bec57709cbaebca2ac92c55fc))
* parallel release creation with keygen publisher ([#6989](https://github.com/electron-userland/electron-builder/issues/6989)) ([7ad5101](https://github.com/electron-userland/electron-builder/commit/7ad5101b4a72df411b76cc500a6a0dca85bf6540))
* parsing of CLI '-c' arguments when combining values with a config file path ([#2025](https://github.com/electron-userland/electron-builder/issues/2025)) ([c2838fe](https://github.com/electron-userland/electron-builder/commit/c2838fe893a8d3a32a99b384716c6952d7500d04))
* pass `publish` options to snap publisher ([#7908](https://github.com/electron-userland/electron-builder/issues/7908)) ([9fc5157](https://github.com/electron-userland/electron-builder/commit/9fc5157879bfa380a78003ff13cdbc26b5e8fd23))
* pass npm_config_update_binary for node-pre-gyp ([3186e0d](https://github.com/electron-userland/electron-builder/commit/3186e0d974eabf9e27210e0cf7834740033894cb))
* Permission problems when extracting electron-*-win32-x64.zip on travis+docker ([3b1526f](https://github.com/electron-userland/electron-builder/commit/3b1526f40d8aa83a6a6b609546898f00e19bd26f)), closes [#2139](https://github.com/electron-userland/electron-builder/issues/2139) [#2140](https://github.com/electron-userland/electron-builder/issues/2140)
* pin Keygen.io integration to v1.0 ([#6909](https://github.com/electron-userland/electron-builder/issues/6909)) ([0b6db59](https://github.com/electron-userland/electron-builder/commit/0b6db59ec10dfe05903f29d6790972f55746bef7))
* **pkg:** Add support for PKG background images in dark mode ([#4489](https://github.com/electron-userland/electron-builder/issues/4489)) ([a23e3d2](https://github.com/electron-userland/electron-builder/commit/a23e3d271708bd293bd39c16bafa7385780258cf))
* **pkg:** provide `BundlePreInstallScriptPath` and/or `BundlePostInstallScriptPath` when a pre/postinstall script is provided to pkg installer ([#8071](https://github.com/electron-userland/electron-builder/issues/8071)) ([eb296c9](https://github.com/electron-userland/electron-builder/commit/eb296c9b2afd77db799eadd472f9ec22f6fc4354))
* **pkg:** support electron 7 ([fc31199](https://github.com/electron-userland/electron-builder/commit/fc311995c196f1063ceb2d0bb0af61beac6038e8))
* Platform-specific build option targets ignored since 15.2.0 ([2e7b668](https://github.com/electron-userland/electron-builder/commit/2e7b6680a7cab45b660db71a11c8137b725a90fe)), closes [#1355](https://github.com/electron-userland/electron-builder/issues/1355)
* **portable:** Disable CRCCheck for portable windows executable ([ec937b2](https://github.com/electron-userland/electron-builder/commit/ec937b2764ba9d884232c72d5fc9db7699e0bb16))
* pre-gyp for darwin targets if build on Linux or in Docker ([#5193](https://github.com/electron-userland/electron-builder/issues/5193)) ([f44206d](https://github.com/electron-userland/electron-builder/commit/f44206dc177521a37ac17f0699bab9eae0412712))
* prefetch command for arm ([f12a090](https://github.com/electron-userland/electron-builder/commit/f12a090f7a9cfc23980599091834668db69da181))
* prevent infinite looping of overwriteArtifact during Github publishing ([#6958](https://github.com/electron-userland/electron-builder/issues/6958)) ([8ffd9d4](https://github.com/electron-userland/electron-builder/commit/8ffd9d42d89634be76fd4554f659f2b2512f2081))
* Problem building multiple mac targets: TypeError: pattern.startsWith is not a function ([#5739](https://github.com/electron-userland/electron-builder/issues/5739)) ([a89edcb](https://github.com/electron-userland/electron-builder/commit/a89edcb0ff39a1465237a97619519bf55c519b20)), closes [#3012](https://github.com/electron-userland/electron-builder/issues/3012)
* Problem with extra metadata arguments ([0684d65](https://github.com/electron-userland/electron-builder/commit/0684d6535bd20a80149b37e84a6540ad65db96cf)), closes [#2160](https://github.com/electron-userland/electron-builder/issues/2160)
* productName with utf8 characters cause dmg icon position error ([fbf787c](https://github.com/electron-userland/electron-builder/commit/fbf787cc32cd5047f93f2311f04b4c72c6b3d2b7)), closes [#1234](https://github.com/electron-userland/electron-builder/issues/1234)
* properly configure electron-rebuild for monorepos ([#7215](https://github.com/electron-userland/electron-builder/issues/7215)) ([0d3b87f](https://github.com/electron-userland/electron-builder/commit/0d3b87f7b89eb2e8f43613acec0e7e057bca88ab))
* Properly filter files that exist outside of the app directory (like hoisted modules) ([c31f6a1](https://github.com/electron-userland/electron-builder/commit/c31f6a1e6dd83cbf7170b89cf228f73c00a650ca)), closes [#2942](https://github.com/electron-userland/electron-builder/issues/2942) [#2948](https://github.com/electron-userland/electron-builder/issues/2948) [#2952](https://github.com/electron-userland/electron-builder/issues/2952) [#2892](https://github.com/electron-userland/electron-builder/issues/2892) [#2944](https://github.com/electron-userland/electron-builder/issues/2944) [#2945](https://github.com/electron-userland/electron-builder/issues/2945) [#2865](https://github.com/electron-userland/electron-builder/issues/2865) [#2953](https://github.com/electron-userland/electron-builder/issues/2953)
* **proton-native:** blurry window (NSHighResolutionCapable) ([770be3f](https://github.com/electron-userland/electron-builder/commit/770be3f672a1f5d10789de589e945fa97b9bd941)), closes [#2922](https://github.com/electron-userland/electron-builder/issues/2922)
* **proton-native:** macOS default icon missing ([f82341b](https://github.com/electron-userland/electron-builder/commit/f82341b39825c64f9479e6f3f56cbf373caa0ca6)), closes [#3481](https://github.com/electron-userland/electron-builder/issues/3481)
* **proton:** use babel only when installed ([#2943](https://github.com/electron-userland/electron-builder/issues/2943)) ([ac18da0](https://github.com/electron-userland/electron-builder/commit/ac18da011d70d4073951cb2e43d8058fd45aae4a)), closes [#2903](https://github.com/electron-userland/electron-builder/issues/2903) [parro-it/libui-node#108](https://github.com/parro-it/libui-node/issues/108)
* provide rabin bindings for nodejs 9 ([3bafe6b](https://github.com/electron-userland/electron-builder/commit/3bafe6b7b1195ab3beafc78ba3d63d20ac125542)), closes [#2260](https://github.com/electron-userland/electron-builder/issues/2260)
* Provide update command for project package manager ([#4167](https://github.com/electron-userland/electron-builder/issues/4167)) ([0348b9f](https://github.com/electron-userland/electron-builder/commit/0348b9f009d7f41c85e62e43f3163c0738c7edb4))
* **publish:** Bitbucket publish can have username different from owner ([#6293](https://github.com/electron-userland/electron-builder/issues/6293)) ([8ebfc96](https://github.com/electron-userland/electron-builder/commit/8ebfc96276bffe0bc1ad394c5ae6843976e01709))
* **publish:** cache publishers based on the target name ([#1958](https://github.com/electron-userland/electron-builder/issues/1958)) ([5e20529](https://github.com/electron-userland/electron-builder/commit/5e20529d1d53456a759a2534863d2cdb0f70f3cd)), closes [#1951](https://github.com/electron-userland/electron-builder/issues/1951)
* **publish:** isCi detection fails due to incorrect import ([#5876](https://github.com/electron-userland/electron-builder/issues/5876)) ([739721d](https://github.com/electron-userland/electron-builder/commit/739721d4ebbb94151634e3f84bb5e40f6258ed5c)), closes [#5875](https://github.com/electron-userland/electron-builder/issues/5875)
* **publish:** resolve any publish configuration — not only string ([98c2c8e](https://github.com/electron-userland/electron-builder/commit/98c2c8e6a889f108d1d8a03a223281335c36bc34))
* quit on decompression errors in NSIS ([#5888](https://github.com/electron-userland/electron-builder/issues/5888)) ([ef981ab](https://github.com/electron-userland/electron-builder/commit/ef981ab1f6d6494c25dceb90f882d991815ac396))
* quitAndInstall not working on macOS with autoInstallOnAppQuit=false ([#6390](https://github.com/electron-userland/electron-builder/issues/6390)) ([a5e8073](https://github.com/electron-userland/electron-builder/commit/a5e8073e21b1ff791905cdb4ab011a724533d8c1))
* re-add `--identifier` to mac pkg build to address issue [#7348](https://github.com/electron-userland/electron-builder/issues/7348) ([#7352](https://github.com/electron-userland/electron-builder/issues/7352)) ([c08db0a](https://github.com/electron-userland/electron-builder/commit/c08db0a92b5e251229a424c1c00559086d860dde))
* re-enable changeDir step for assisted, perMachine installs ([#7648](https://github.com/electron-userland/electron-builder/issues/7648)) ([84ed3ff](https://github.com/electron-userland/electron-builder/commit/84ed3ff123b5ae92cd3350d64677434f9b397b76))
* re-export some of "builder-util-runtime" types directly from "electron-updater". ([#5675](https://github.com/electron-userland/electron-builder/issues/5675)) ([#5869](https://github.com/electron-userland/electron-builder/issues/5869)) ([4a136a3](https://github.com/electron-userland/electron-builder/commit/4a136a3877e0c83d0b2d5441351b39e6340589c5))
* Re-fetch downloads if cache directory has changed ([#4958](https://github.com/electron-userland/electron-builder/issues/4958)) ([6827109](https://github.com/electron-userland/electron-builder/commit/6827109c007b16d486d57ae32bc262434e246089)), closes [#4955](https://github.com/electron-userland/electron-builder/issues/4955) [#4955](https://github.com/electron-userland/electron-builder/issues/4955)
* Reactivating bitbucket integration test for nsis updater ([#6680](https://github.com/electron-userland/electron-builder/issues/6680)) ([6fcd477](https://github.com/electron-userland/electron-builder/commit/6fcd47767af8a95ab018fe0d8a07d2c53a72067d))
* Rebuild stucks on Windows ([2c52ed2](https://github.com/electron-userland/electron-builder/commit/2c52ed27396114083e0f9c62ed9cf2adf9d4f4e5)), closes [#1472](https://github.com/electron-userland/electron-builder/issues/1472)
* **rebuild:** Log stdout and stderr ([#1450](https://github.com/electron-userland/electron-builder/issues/1450)) ([ada9cac](https://github.com/electron-userland/electron-builder/commit/ada9cace1dbbf66607fe8144cad00b53b885dac5)), closes [#1415](https://github.com/electron-userland/electron-builder/issues/1415)
* Reducing node version to be >=14 as opposed to explicitly 14.17.0 (the current max node 14 version) ([#5893](https://github.com/electron-userland/electron-builder/issues/5893)) ([#5896](https://github.com/electron-userland/electron-builder/issues/5896)) ([b6413a8](https://github.com/electron-userland/electron-builder/commit/b6413a85c6ca14861bc3521caafc6de317e2ecba))
* **refactor:** builder-util-runtime, separate newError to eliminate circular dependency ([#8251](https://github.com/electron-userland/electron-builder/issues/8251)) ([140e2f0](https://github.com/electron-userland/electron-builder/commit/140e2f0eb0df79c2a46e35024e96d0563355fc89))
* refactoring ffmpeg implementation and removing related npm dependency ([#7495](https://github.com/electron-userland/electron-builder/issues/7495)) ([91f86ae](https://github.com/electron-userland/electron-builder/commit/91f86aed093a78cd43e60126ebd48fa88ce7727a))
* regenerating docs and schema ([f70abf1](https://github.com/electron-userland/electron-builder/commit/f70abf1628223e1cc0d687471ad36b4a2ee66ebe))
* regenerating schema to account for electron-universal options `x64ArchFiles` ([#6983](https://github.com/electron-userland/electron-builder/issues/6983)) ([adeaa34](https://github.com/electron-userland/electron-builder/commit/adeaa347c03b8947b0812ecef23398c0822646bb))
* regression — EISDIR ([d0c6c04](https://github.com/electron-userland/electron-builder/commit/d0c6c04fbf82ee759c8b0f8ccb112e60297c969e)), closes [#2265](https://github.com/electron-userland/electron-builder/issues/2265)
* remote build doesn't work if native async is used ([17b85cc](https://github.com/electron-userland/electron-builder/commit/17b85cc773d6dfae7bb7c86fc5ddda0e85b751c3))
* remote building ([357d330](https://github.com/electron-userland/electron-builder/commit/357d330b2f13371b3492acfa47a84ee5389f6a62))
* **remote-build:** correctly pass repository info ([4767e8d](https://github.com/electron-userland/electron-builder/commit/4767e8da3de26527b94c53d81d5306137c1b9ee5))
* **remote-build:** set zstd compression level to 16 (reduce upload time from 40s to 20s) ([04787fa](https://github.com/electron-userland/electron-builder/commit/04787fa8f0081c412e15276a41086612d6123fd2))
* remove @electron-builder/test from changeset ([e101e8d](https://github.com/electron-userland/electron-builder/commit/e101e8d190d7e3046222e88c32a62d727dadd808))
* Remove `adapter` if core22+ is set as base on snapcraft ([#7378](https://github.com/electron-userland/electron-builder/issues/7378)) ([db69a18](https://github.com/electron-userland/electron-builder/commit/db69a1875d219310b3050b35cdc46c20ec45cc04))
* Remove additional xml closing tag ([#4078](https://github.com/electron-userland/electron-builder/issues/4078)) ([4076dc9](https://github.com/electron-userland/electron-builder/commit/4076dc985651d13fe2149f01e71617723e8b619a))
* remove deprecated --arch, --platform, --draft, --prerelease ([68ffd54](https://github.com/electron-userland/electron-builder/commit/68ffd54aca4dc65f3f932a6580d744ae656ecbaf))
* remove deprecated `build` bin script ([bea9db9](https://github.com/electron-userland/electron-builder/commit/bea9db9daf8463b41b52d0a0edae051110fc29e5))
* remove host property from headers when signed by aws4.sign ([#4848](https://github.com/electron-userland/electron-builder/issues/4848)) ([0f0363b](https://github.com/electron-userland/electron-builder/commit/0f0363bd902d64504586dad2af522d161dec56a2)), closes [#4758](https://github.com/electron-userland/electron-builder/issues/4758)
* remove react-scripts from knownAlwaysIgnoredDevDeps ([8bc0a27](https://github.com/electron-userland/electron-builder/commit/8bc0a27a2b64e7fbff5a250caf503ec3a2fbb7d6)), closes [#2449](https://github.com/electron-userland/electron-builder/issues/2449)
* Remove spctl check from Mac's notarization ([#7361](https://github.com/electron-userland/electron-builder/issues/7361)) ([f9f23be](https://github.com/electron-userland/electron-builder/commit/f9f23bef64efd429f6dfd1ec81f2d73927f63a8e))
* removeAuthHeader must strip auth only for AWS ([d7a6760](https://github.com/electron-userland/electron-builder/commit/d7a67605160050fb550ce66439bd5b4a33239162))
* removing devDependencies from package.json breaks levelup in electron ([0278efb](https://github.com/electron-userland/electron-builder/commit/0278efbd6bb65b1fa222d9eaeb4227dc1e4d6605)), closes [#1408](https://github.com/electron-userland/electron-builder/issues/1408)
* removing double exec of `checkForUpdates` that causes error thrown: "The command is disabled and cannot be executed" ([#5989](https://github.com/electron-userland/electron-builder/issues/5989)) ([71d3704](https://github.com/electron-userland/electron-builder/commit/71d37044d348ab0cd8f0f9f7754bf6ebaa4b996c))
* Removing file size from BuildTest smart unpack ([#7456](https://github.com/electron-userland/electron-builder/issues/7456)) ([25dc0bb](https://github.com/electron-userland/electron-builder/commit/25dc0bbb19637add4c47be88934f70b0e84a122e))
* removing stdio from spawnSync to fix crash on rpm/deb updaters ([#7628](https://github.com/electron-userland/electron-builder/issues/7628)) ([98f535e](https://github.com/electron-userland/electron-builder/commit/98f535e1f80b7f84dc3c2f135a4a5ea8cd142f31))
* Removing the abort trigger from httpExecutor ([#1040](https://github.com/electron-userland/electron-builder/issues/1040)) ([741df23](https://github.com/electron-userland/electron-builder/commit/741df23328bd6aa88187ff538b468a003fa6a199)), closes [#1039](https://github.com/electron-userland/electron-builder/issues/1039)
* rename EP_PRELEASE to EP_PRE_RELEASE ([4d223bf](https://github.com/electron-userland/electron-builder/commit/4d223bf2c280942eeba237c898f9571be3e078f6)), closes [#2878](https://github.com/electron-userland/electron-builder/issues/2878)
* rendering extended node_modules in jsdoc ([#6843](https://github.com/electron-userland/electron-builder/issues/6843)) ([481a7ed](https://github.com/electron-userland/electron-builder/commit/481a7ed2b77e7e1b448f27e58fedeac53b107ffc))
* replace deprecated --cache-min option ([#6165](https://github.com/electron-userland/electron-builder/issues/6165)) ([c02ccbb](https://github.com/electron-userland/electron-builder/commit/c02ccbb9739a6fb2840625a825f6be33136567f0))
* replace deprecated interface ([#5049](https://github.com/electron-userland/electron-builder/issues/5049)) ([11874be](https://github.com/electron-userland/electron-builder/commit/11874be71223c4a846cbbaca4c9046a4fd08cf99))
* replace update-notifier with simple-update notifier due to dependency vulnerability ([#7078](https://github.com/electron-userland/electron-builder/issues/7078)) ([48cbb12](https://github.com/electron-userland/electron-builder/commit/48cbb120dc11994889f4aa61c8431531ce274006))
* requireProviderClass should be aware about snapStore ([10e4383](https://github.com/electron-userland/electron-builder/commit/10e4383d468457dff0b874e0cd4217a26bea4641))
* rerunning test-linux to update snapshot for upstream dep that now uses additional depedencies ([#6403](https://github.com/electron-userland/electron-builder/issues/6403)) ([434d388](https://github.com/electron-userland/electron-builder/commit/434d3887cb651ef93ce214dc7b8edeab6a298096))
* resolve unstable unit test that is on latest mac ([#7626](https://github.com/electron-userland/electron-builder/issues/7626)) ([16d1430](https://github.com/electron-userland/electron-builder/commit/16d1430b6c3721f3a258a02b70897a9b2af25c28))
* respect ignore patterns for node modules if defined as file set filter ([f52ce37](https://github.com/electron-userland/electron-builder/commit/f52ce376d04317245c8d8a1a459c7cfaff680a0d))
* respect the signDlls flag ([#5133](https://github.com/electron-userland/electron-builder/issues/5133)) ([db6e762](https://github.com/electron-userland/electron-builder/commit/db6e7620260741a35557ba13429ac10a4f4cf5d9))
* restore support of project param ([0fcc99c](https://github.com/electron-userland/electron-builder/commit/0fcc99cb24ab93d5149c3e9f8cb7a013894ea477)), closes [#2633](https://github.com/electron-userland/electron-builder/issues/2633)
* Revert "feat: Support mjs files for lifecycle operations" ([#7461](https://github.com/electron-userland/electron-builder/issues/7461)) ([0f9da20](https://github.com/electron-userland/electron-builder/commit/0f9da20dbf8a229242ad9247ca89ef90241512f5)), closes [#7442](https://github.com/electron-userland/electron-builder/issues/7442)
* Revert "feat: Upgrade to Ubuntu 22.04 and python 3.10" ([#7109](https://github.com/electron-userland/electron-builder/issues/7109)) ([7d606af](https://github.com/electron-userland/electron-builder/commit/7d606aff59c964dc0af93c0f235abb0f3e258dea))
* reverting migration to electron-rebuild since Cxx flags were back-ported to latest versions of electron ([#7668](https://github.com/electron-userland/electron-builder/issues/7668)) ([9cfd35d](https://github.com/electron-userland/electron-builder/commit/9cfd35d5ad320255d88be67530ce5fe6e832f862))
* **rpm:** libxss is missing from rpm depends ([e0885fa](https://github.com/electron-userland/electron-builder/commit/e0885fa2392d95b6f8084ed9ea9eeca90d2c3b87)), closes [#2203](https://github.com/electron-userland/electron-builder/issues/2203)
* run nsis builds (and portable builds) sequentially ([#7798](https://github.com/electron-userland/electron-builder/issues/7798)) ([526e075](https://github.com/electron-userland/electron-builder/commit/526e075edddf908b9688e108a18fbb76e6f047be))
* Runtime error for a build on window feat. electron-compile (forge) ([89a55ee](https://github.com/electron-userland/electron-builder/commit/89a55ee7bd85ce7a00a4f756e5df5a8b709f7c58)), closes [#1686](https://github.com/electron-userland/electron-builder/issues/1686)
* S3 URLs ([#1373](https://github.com/electron-userland/electron-builder/issues/1373)) ([#1374](https://github.com/electron-userland/electron-builder/issues/1374)) ([ac75e8c](https://github.com/electron-userland/electron-builder/commit/ac75e8cfd0ef7e40a70614f4ab331a823ccee0c2))
* S3 urls on mac ([55ebed1](https://github.com/electron-userland/electron-builder/commit/55ebed1c595e412beb1b027b9414d6f051130937)), closes [#1386](https://github.com/electron-userland/electron-builder/issues/1386)
* **s3:** S3-DEPLOY with parenthesis / spaces in product name broken in 1.6.2 ([26ae6ec](https://github.com/electron-userland/electron-builder/commit/26ae6ec2e875c51679b2d6dd0fc554579bbb6a3a)), closes [#1439](https://github.com/electron-userland/electron-builder/issues/1439)
* set github release name to match the app version ([#6840](https://github.com/electron-userland/electron-builder/issues/6840)) ([e9ba750](https://github.com/electron-userland/electron-builder/commit/e9ba75005dda39f03c04e37a5d46a1bbe634c189))
* sha2 checksum error is not catchable ([c10531b](https://github.com/electron-userland/electron-builder/commit/c10531b26269f314b01c81c54b22db9160df081c)), closes [#1010](https://github.com/electron-userland/electron-builder/issues/1010)
* sign all exe and dll files, not only root ([37bb121](https://github.com/electron-userland/electron-builder/commit/37bb121d71c42b9ebf9b8c8c57381b534a7af85e))
* sign macOS objects depth-first (close [#4932](https://github.com/electron-userland/electron-builder/issues/4932)) ([#4993](https://github.com/electron-userland/electron-builder/issues/4993)) ([7f8d59c](https://github.com/electron-userland/electron-builder/commit/7f8d59cee5ae28699a21fbb5413e5ead0b5f3880))
* signing of playwright ([#5451](https://github.com/electron-userland/electron-builder/issues/5451)) ([5075068](https://github.com/electron-userland/electron-builder/commit/50750683b11d5670a182bd72f7cab14023e2b030))
* signing of user-defined binaries on mac when resolved as relative path ([#6660](https://github.com/electron-userland/electron-builder/issues/6660)) ([4c6d154](https://github.com/electron-userland/electron-builder/commit/4c6d1546d4942aa9d9a93b7309e8ed279f6378d2))
* skip unstable installer tests to unblock master CI pipeline ([#6544](https://github.com/electron-userland/electron-builder/issues/6544)) ([5648e05](https://github.com/electron-userland/electron-builder/commit/5648e05a9efa61f81e788ecf538a617df9f65fe1))
* snap - can't push to snapcraft anymore because of execstack ([24f2565](https://github.com/electron-userland/electron-builder/commit/24f2565d3c55b8da5809ab9c4e4b3d812aadd2a2)), closes [#2608](https://github.com/electron-userland/electron-builder/issues/2608)
* snap packages don't follow artifactName ([3f6f5b6](https://github.com/electron-userland/electron-builder/commit/3f6f5b6d82118c2c4ee084c49711c543fd3c2308)), closes [#2576](https://github.com/electron-userland/electron-builder/issues/2576)
* **snap:** add missing %U in desktop file of snap builds ([#5001](https://github.com/electron-userland/electron-builder/issues/5001)) ([df5d050](https://github.com/electron-userland/electron-builder/commit/df5d050e47f2030e48e65c0e3b542c3aec61e9de))
* **snap:** allow snapcraft edge version ([d11c760](https://github.com/electron-userland/electron-builder/commit/d11c7607228159dfdd756f000310ed463d62652b)), closes [#4142](https://github.com/electron-userland/electron-builder/issues/4142)
* **snap:** allow to set `classic` confinement ([f1d524a](https://github.com/electron-userland/electron-builder/commit/f1d524a7b36e555f2070583e057b795c1bca5078))
* **snap:** command line arguments are not supported ([a7e1aec](https://github.com/electron-userland/electron-builder/commit/a7e1aeccda23043325f482a64d9c8a74d96b2292)), closes [#2880](https://github.com/electron-userland/electron-builder/issues/2880) [#3035](https://github.com/electron-userland/electron-builder/issues/3035) [#3253](https://github.com/electron-userland/electron-builder/issues/3253)
* **snap:** confinement classic not allowed with plugs ([efbc41e](https://github.com/electron-userland/electron-builder/commit/efbc41e1359207391a9e70e436560f1fe22ef8d6)), closes [#2730](https://github.com/electron-userland/electron-builder/issues/2730)
* **snap:** detect snapcraft version if quoted ([d18909b](https://github.com/electron-userland/electron-builder/commit/d18909bd3afdbcdfb49850c286ffe2845b45e24c))
* **snap:** do not add "adapter: none" for prepacked snap [#2614](https://github.com/electron-userland/electron-builder/issues/2614) ([866ae11](https://github.com/electron-userland/electron-builder/commit/866ae114f67c40a69a945b90e7ec70558d031419))
* **snap:** do not set environment for classic ([9eec0a9](https://github.com/electron-userland/electron-builder/commit/9eec0a984ca6e68993e69109405c90c4a67da1cb)), closes [#3300](https://github.com/electron-userland/electron-builder/issues/3300)
* **snap:** do not use gtk3 for electron 1.8.3+ ([726706c](https://github.com/electron-userland/electron-builder/commit/726706c43b55d5b38e6bb59891e52f96fd53197c))
* **snap:** electron 1 template is broken ([9dced9c](https://github.com/electron-userland/electron-builder/commit/9dced9ceaf245a86f0ef33df373f3fd44871e80a)), closes [#2808](https://github.com/electron-userland/electron-builder/issues/2808)
* **snap:** electron-builder constructs snap squashfs files that are incompatible with the snap store ([cb5034d](https://github.com/electron-userland/electron-builder/commit/cb5034da4caa00e9d96850e8b7f365519cb9d52b)), closes [#2925](https://github.com/electron-userland/electron-builder/issues/2925) [#2888](https://github.com/electron-userland/electron-builder/issues/2888)
* **snap:** electron-builder uses mksquashfs options that are incompatible with snap store ([e828245](https://github.com/electron-userland/electron-builder/commit/e828245afd353565d979193a9df126323355b07a)), closes [#2803](https://github.com/electron-userland/electron-builder/issues/2803)
* **snap:** file permissions if umask is not 0 ([26632ff](https://github.com/electron-userland/electron-builder/commit/26632ffcbaa236cbb19db81e69985fe250188806)), closes [#2627](https://github.com/electron-userland/electron-builder/issues/2627) [#2614](https://github.com/electron-userland/electron-builder/issues/2614)
* **snap:** fix appindicator icons with snap build ([#1453](https://github.com/electron-userland/electron-builder/issues/1453)) ([2ab769d](https://github.com/electron-userland/electron-builder/commit/2ab769db11c472282376796fbf284fd099d0f251)), closes [#1452](https://github.com/electron-userland/electron-builder/issues/1452)
* **snap:** fix Exec path regression ([4b94597](https://github.com/electron-userland/electron-builder/commit/4b9459765b163bd0aa9b08cc26995759cf3761d9)), closes [#1948](https://github.com/electron-userland/electron-builder/issues/1948)
* **snap:** fix snapcraft version check for 3.0 ([0ba9c4f](https://github.com/electron-userland/electron-builder/commit/0ba9c4fae411cab520217f70fabdde05c5d1c226)), closes [#3549](https://github.com/electron-userland/electron-builder/issues/3549)
* **snap:** interface 'platform' doesn't exist ([ade922c](https://github.com/electron-userland/electron-builder/commit/ade922c4d72fab3af87bee40d14e8d506b933800)), closes [#1123](https://github.com/electron-userland/electron-builder/issues/1123)
* **snap:** Problem with armhf/armv7l (raspberry pi) when creating snaps ([9754269](https://github.com/electron-userland/electron-builder/commit/9754269a98f5b8baa3c06f23f827423fcc29c3f1)), closes [#3976](https://github.com/electron-userland/electron-builder/issues/3976)
* **snap:** reduce deps [#509](https://github.com/electron-userland/electron-builder/issues/509) ([1fc26a5](https://github.com/electron-userland/electron-builder/commit/1fc26a520e67c173553f9e551fb663fcf2d291e4))
* **snap:** remove snap debugging ([#4589](https://github.com/electron-userland/electron-builder/issues/4589)) ([0ca2ccc](https://github.com/electron-userland/electron-builder/commit/0ca2cccb6f007348e6ef0f9c6dddf752ac411314))
* **snap:** Snap builds do not have architectures key ([f799062](https://github.com/electron-userland/electron-builder/commit/f799062f8148af058683309e4b36f4d3e939adbb)), closes [#2596](https://github.com/electron-userland/electron-builder/issues/2596)
* **snap:** Snap does not launch when Ubuntu uses Wayland ([2278c2a](https://github.com/electron-userland/electron-builder/commit/2278c2a347bb9e6d00f2f59719eb784ac9857c10)), closes [#4007](https://github.com/electron-userland/electron-builder/issues/4007)
* SnapStoreOptions required properties ([#6327](https://github.com/electron-userland/electron-builder/issues/6327)) ([#6333](https://github.com/electron-userland/electron-builder/issues/6333)) ([54ee4e7](https://github.com/electron-userland/electron-builder/commit/54ee4e72c5db859b9a00104179786567a0e977ff))
* **snap:** stricter filtering for xcb libraries ([#5205](https://github.com/electron-userland/electron-builder/issues/5205)) ([#5206](https://github.com/electron-userland/electron-builder/issues/5206)) ([9164f4d](https://github.com/electron-userland/electron-builder/commit/9164f4d328efd03da6b8c2f17b3535dcbdbb9cca))
* **snap:** use correct arch triplet for arm ([5b1fa2e](https://github.com/electron-userland/electron-builder/commit/5b1fa2ef1d54dddcb366bd4efe604b128434c7fa))
* **snap:** use correct arch triplet for arm ([85c32f3](https://github.com/electron-userland/electron-builder/commit/85c32f392449627dfee014d5740df4f1d75db0e1)), closes [#3977](https://github.com/electron-userland/electron-builder/issues/3977)
* SOE on read node module tree ([1ce3a89](https://github.com/electron-userland/electron-builder/commit/1ce3a89c67962e25d0780977eea087a3d751e229)), closes [#3113](https://github.com/electron-userland/electron-builder/issues/3113)
* specify protocol as https to complete proxy support fix ([#6516](https://github.com/electron-userland/electron-builder/issues/6516)) ([344bb23](https://github.com/electron-userland/electron-builder/commit/344bb232d71e608b881a04fc98dca0858e42ddfc)), closes [#6286](https://github.com/electron-userland/electron-builder/issues/6286)
* **squirrel.windows:** Crash after autoupdate downloads nuget package ([d10ba78](https://github.com/electron-userland/electron-builder/commit/d10ba784efbbcef0f624646f3491b22a76207e33)), closes [#1101](https://github.com/electron-userland/electron-builder/issues/1101)
* **squirrel.windows:** Fixed Squirrel Windows Description Error ([#4292](https://github.com/electron-userland/electron-builder/issues/4292)) ([555fad2](https://github.com/electron-userland/electron-builder/commit/555fad24a0a4543e36900b3da9f321b862b4fd8c))
* **squirrel.windows:** pass 7za path via env ([ce1de01](https://github.com/electron-userland/electron-builder/commit/ce1de01fb394655a1058fb3ff66d638b66177767))
* **Squirrel.Windows:** regression after 19.17.0 ([dd80685](https://github.com/electron-userland/electron-builder/commit/dd80685e75350fc6c2fa582cb7b2e715a4e3379b)), closes [#1934](https://github.com/electron-userland/electron-builder/issues/1934)
* **Squirrel.Windows:** Remove encodeUri from squirrel-windows packaging ([7a37cef](https://github.com/electron-userland/electron-builder/commit/7a37cefc121c5ac307b6ceb4bc71f2645735acd1)), closes [#2557](https://github.com/electron-userland/electron-builder/issues/2557) [#2558](https://github.com/electron-userland/electron-builder/issues/2558)
* **squirrel.windows:** sign the Squirrel.Windows executableStub ([c732db2](https://github.com/electron-userland/electron-builder/commit/c732db258930d5f4f7c0ba59dfed0f24a3037e22)), closes [#1251](https://github.com/electron-userland/electron-builder/issues/1251)
* **Squirrel.Windows:** Squirrel Windows is not using productName for nupkg ([f63086d](https://github.com/electron-userland/electron-builder/commit/f63086d13558771508314a9620dbbdf0613f1210)), closes [#1879](https://github.com/electron-userland/electron-builder/issues/1879)
* **squirrel.windows:** Squirrel Windows mp3 and node ([7c8911e](https://github.com/electron-userland/electron-builder/commit/7c8911e6569a12c83e48de93e707211c886812b7)), closes [#1803](https://github.com/electron-userland/electron-builder/issues/1803)
* **Squirrel.Windows:** squirrel-windows/temp folder (regression since 19.43.0) ([a6f4789](https://github.com/electron-userland/electron-builder/commit/a6f47893551d3de646afc3ff1eb5fcfd73981e98)), closes [#2257](https://github.com/electron-userland/electron-builder/issues/2257)
* **Squirrel.Windows:** use convertVersion for version in squirrel packageFile ([#2178](https://github.com/electron-userland/electron-builder/issues/2178)) ([349f2d5](https://github.com/electron-userland/electron-builder/commit/349f2d54a9d1ddfdcc91d1feb2da30c7754b9935)), closes [#1999](https://github.com/electron-userland/electron-builder/issues/1999)
* stringify error ([be9a5f9](https://github.com/electron-userland/electron-builder/commit/be9a5f9c982f102f3a598eeceb4715b9e9867f26)), closes [#2469](https://github.com/electron-userland/electron-builder/issues/2469) [#2471](https://github.com/electron-userland/electron-builder/issues/2471)
* stringify error ([a6d2796](https://github.com/electron-userland/electron-builder/commit/a6d2796e3a0086b6105aecb741e6a7c165245e53)), closes [#2469](https://github.com/electron-userland/electron-builder/issues/2469)
* strip extra fields out that are not allowed when creating snap.yaml ([#7104](https://github.com/electron-userland/electron-builder/issues/7104)) ([#7110](https://github.com/electron-userland/electron-builder/issues/7110)) ([0a7025e](https://github.com/electron-userland/electron-builder/commit/0a7025e5184e3333d077db1f7e782d6a768ecdea))
* strip trailing slash from s3 endpoint ([d40a15c](https://github.com/electron-userland/electron-builder/commit/d40a15c3795e3a3302e48a9c5c495df44f30ba1d)), closes [#3091](https://github.com/electron-userland/electron-builder/issues/3091)
* Stub CircleCI config since we can't disable it from dashboard ([#6543](https://github.com/electron-userland/electron-builder/issues/6543)) ([22fb8c6](https://github.com/electron-userland/electron-builder/commit/22fb8c63ac196c61c6b449e6e5e95d91117f8894))
* Stub Executables missing in Squirrel.Windows 1.5.1 ([0ce1a3c](https://github.com/electron-userland/electron-builder/commit/0ce1a3c973ab9b8346b25edaa119bed06344be56)), closes [#1011](https://github.com/electron-userland/electron-builder/issues/1011)
* support `executableName` in main config ([#7828](https://github.com/electron-userland/electron-builder/issues/7828)) ([7c7db83](https://github.com/electron-userland/electron-builder/commit/7c7db837bdf650228594a30114975f1581c37130))
* support powershell constrained language mode ([#7230](https://github.com/electron-userland/electron-builder/issues/7230)) ([346af1d](https://github.com/electron-userland/electron-builder/commit/346af1d470ebbf12733a9619a2389bcfdf452bc6))
* Support Windows 11 in VMs ([#6185](https://github.com/electron-userland/electron-builder/issues/6185)) ([f6a3053](https://github.com/electron-userland/electron-builder/commit/f6a3053563bd50dc77010d2910086c81acdf613e))
* symlinks in asarUnpack are not copied ([13f21ee](https://github.com/electron-userland/electron-builder/commit/13f21eed0d700248776936294de8307da008c015)), closes [#1376](https://github.com/electron-userland/electron-builder/issues/1376)
* **tar:** fix invalid sym-/hardlink targets in archive ([#1614](https://github.com/electron-userland/electron-builder/issues/1614)) ([b31ebff](https://github.com/electron-userland/electron-builder/commit/b31ebffe006e1ea7dd7309fb00e10660a6999948))
* temporarily skip flaky test from transient dependency ([3f6757b](https://github.com/electron-userland/electron-builder/commit/3f6757b41720c0740886325431c18be81a23ebbf))
* test data ([01553c0](https://github.com/electron-userland/electron-builder/commit/01553c08daaac5c917f889a9868b2f956838c185))
* test snap update for abi_registry.json ([#5823](https://github.com/electron-userland/electron-builder/issues/5823)) ([6237e67](https://github.com/electron-userland/electron-builder/commit/6237e670a8ddd99ec8c076db86361c06c04eedd4))
* The path should be corrected in Windows that when the moduleName is Scoped packages named. ([#3002](https://github.com/electron-userland/electron-builder/issues/3002)) ([0cdb1c4](https://github.com/electron-userland/electron-builder/commit/0cdb1c4fcabb3c32daf97b80887182bd12e97e7f))
* The zip Windows target includes the application code inside a "win-unpacked" directory ([4e6ece4](https://github.com/electron-userland/electron-builder/commit/4e6ece47041a3262065f14a577e3511b1ab70475)), closes [#1666](https://github.com/electron-userland/electron-builder/issues/1666)
* to preserve compatibility with old electron-auto-updater (< 0.10.0), we upload file with path specific for GitHub ([c06f3f4](https://github.com/electron-userland/electron-builder/commit/c06f3f4c751d51a3f16383b834dedd7efa3bb168))
* treat cscLink empty string same as absent ([#8185](https://github.com/electron-userland/electron-builder/issues/8185)) ([5e41c5e](https://github.com/electron-userland/electron-builder/commit/5e41c5e8e440f7c6d139fc0e311efa46bc2846c3))
* trigger `app.relaunch()` if `isForceRunAfter = true` for rpm and deb updaters ([#7637](https://github.com/electron-userland/electron-builder/issues/7637)) ([b3dfe64](https://github.com/electron-userland/electron-builder/commit/b3dfe64b22dc51375861f6b8a3517ff9ab562aaf))
* Trim suffix from wine version ([#1033](https://github.com/electron-userland/electron-builder/issues/1033)) ([090150c](https://github.com/electron-userland/electron-builder/commit/090150cebf1d8ae56265e84380f5f968b821ece5)), closes [#1031](https://github.com/electron-userland/electron-builder/issues/1031) [#953](https://github.com/electron-userland/electron-builder/issues/953)
* trim the whole string, otherwise detection of windows-like path is not robust ([e63e8fa](https://github.com/electron-userland/electron-builder/commit/e63e8fa9bf2d5031f0f667eef1227aef48ac4159)), closes [#1596](https://github.com/electron-userland/electron-builder/issues/1596)
* TypeError: Cannot read property 'file' of undefined ([eb6e01a](https://github.com/electron-userland/electron-builder/commit/eb6e01a31f6683adbf19bcbf764bf0935431f941)), closes [#2823](https://github.com/electron-userland/electron-builder/issues/2823)
* TypeError: Cannot read property 'Z_BEST_COMPRESSION' of undefined ([b061710](https://github.com/electron-userland/electron-builder/commit/b061710f0126700ea8860d7db78441e8c7fcede2)), closes [#2079](https://github.com/electron-userland/electron-builder/issues/2079)
* TypeError: s.trim is not a function on rpm and deb target ([ab64a06](https://github.com/electron-userland/electron-builder/commit/ab64a06d29c1750c6dba571ff4f74f0000eca119)), closes [#1784](https://github.com/electron-userland/electron-builder/issues/1784)
* TypeError: stat.isSymbolicLink is not a function ([e44414a](https://github.com/electron-userland/electron-builder/commit/e44414a1a2ff203589a8895daf3c90b745362e50)), closes [#2288](https://github.com/electron-userland/electron-builder/issues/2288)
* typo in `fileMatcher`'s default patterns ([#5705](https://github.com/electron-userland/electron-builder/issues/5705)) ([c0ae89c](https://github.com/electron-userland/electron-builder/commit/c0ae89c004ea546ae6e0a73ec0f04e038169197c))
* Unable to exclude files from app.asar ([5226c21](https://github.com/electron-userland/electron-builder/commit/5226c21754974a1441f2c4ed7163c5489bbcb60a)), closes [#3446](https://github.com/electron-userland/electron-builder/issues/3446)
* Unable to find latest version on GitHub ([#6822](https://github.com/electron-userland/electron-builder/issues/6822)) ([bfe29a5](https://github.com/electron-userland/electron-builder/commit/bfe29a5e991c2719032877bd7225b15b6b836221))
* unacceptable kind of an object to dump [object AsyncFunction] ([2dda5fc](https://github.com/electron-userland/electron-builder/commit/2dda5fcb45d99a0a991d195a2f577e3dbca775eb))
* Unhandled rejection SyntaxError: Unexpected token ... ([0c81bf7](https://github.com/electron-userland/electron-builder/commit/0c81bf788b1933228bd6883d36e8b6055f299619)), closes [#1076](https://github.com/electron-userland/electron-builder/issues/1076)
* unknown option "draft" ([2b761e5](https://github.com/electron-userland/electron-builder/commit/2b761e525328d9402ba8ff0b310e91043a0d6db8)), closes [#3145](https://github.com/electron-userland/electron-builder/issues/3145)
* unknown option "p" ([2145fa1](https://github.com/electron-userland/electron-builder/commit/2145fa114ea0b173c22756e63f27b3ef7aa54a45)), closes [#3146](https://github.com/electron-userland/electron-builder/issues/3146)
* Unknown option "project" ([35def8d](https://github.com/electron-userland/electron-builder/commit/35def8d7b7ba1f377f29eb2ad0566bb60bbbebb7)), closes [#3155](https://github.com/electron-userland/electron-builder/issues/3155)
* unpack node module if there is `dylib` file ([daf6f59](https://github.com/electron-userland/electron-builder/commit/daf6f590eb19d11e7b632af8f5d3dcf5426ff32b)), closes [#2635](https://github.com/electron-userland/electron-builder/issues/2635)
* unzipping of the blockmap ([#5025](https://github.com/electron-userland/electron-builder/issues/5025)) ([a887d23](https://github.com/electron-userland/electron-builder/commit/a887d2371821827d59966fb72a9b9c3225bedd90))
* update `@electron/rebuild` version and update imports ([#7541](https://github.com/electron-userland/electron-builder/issues/7541)) ([a4888ac](https://github.com/electron-userland/electron-builder/commit/a4888ac490e4e5d3783858d27acd487b2b8444fd))
* Update assistedMessages.yml with korean entries ([#6309](https://github.com/electron-userland/electron-builder/issues/6309)) ([e29a6b8](https://github.com/electron-userland/electron-builder/commit/e29a6b8b36695a2ed9d2f9a57e4c1c74587d1b16))
* update autoupdate docs to describe module-based support. set `nativeRebuilder` default value to use electron/rebuild ([#8140](https://github.com/electron-userland/electron-builder/issues/8140)) ([99a6150](https://github.com/electron-userland/electron-builder/commit/99a6150ea02c91a7e7e657c667328eb734e29b8f))
* Update BintrayProvider.ts ([#4921](https://github.com/electron-userland/electron-builder/issues/4921)) ([65bb441](https://github.com/electron-userland/electron-builder/commit/65bb44168ee9c2be50905f7932a87bbde491f10b))
* Update certificate validation on Windows to check full DN ([#6576](https://github.com/electron-userland/electron-builder/issues/6576)) ([53467c7](https://github.com/electron-userland/electron-builder/commit/53467c724dacc11fc270cebaba22f8cf84dff24f))
* update check failing with TypeError ([#5877](https://github.com/electron-userland/electron-builder/issues/5877)) ([7884b50](https://github.com/electron-userland/electron-builder/commit/7884b502c1daa720857a4b8428ea2cdfd0e377d8))
* Update deprecated env var ([#4451](https://github.com/electron-userland/electron-builder/issues/4451)) ([e182787](https://github.com/electron-userland/electron-builder/commit/e18278707752363a9e46924d31046422f7f845b7))
* update docs for updated electron API ([b7a53d0](https://github.com/electron-userland/electron-builder/commit/b7a53d0f69f1350b47cef118b1ef4aaf9885f88f))
* Update MacOS signOptions on macPackager [#7317](https://github.com/electron-userland/electron-builder/issues/7317) ([#7351](https://github.com/electron-userland/electron-builder/issues/7351)) ([1e8dad8](https://github.com/electron-userland/electron-builder/commit/1e8dad8bc58f53780c9fac3b0c48e248a8b5467c))
* update repo in CONTRIBUTING.md ([#5726](https://github.com/electron-userland/electron-builder/issues/5726)) ([da85087](https://github.com/electron-userland/electron-builder/commit/da85087143d2c6a63faab4c44c28dc625326e9ee))
* update unit test snapshot to account for new package dependency files ([#7968](https://github.com/electron-userland/electron-builder/issues/7968)) ([9335c59](https://github.com/electron-userland/electron-builder/commit/9335c59e224b3cba57cba8822995a88f5349a927))
* Update version.ts to match package.json ([#5882](https://github.com/electron-userland/electron-builder/issues/5882)) ([e148234](https://github.com/electron-userland/electron-builder/commit/e1482347228896b0825737df045fffa6e688e7b6))
* Updater "Error: Could not connect to the server." in macOS ([#6743](https://github.com/electron-userland/electron-builder/issues/6743)) ([27f18aa](https://github.com/electron-userland/electron-builder/commit/27f18aa1d890f3a82e856f4834b8387066fb697f))
* **updater:** github private repo ([fb24e26](https://github.com/electron-userland/electron-builder/commit/fb24e26afac08b1b73c342beb07a0fbe33a6f067)), closes [#1370](https://github.com/electron-userland/electron-builder/issues/1370)
* **updater:** GitHub private repo for windows ([#1382](https://github.com/electron-userland/electron-builder/issues/1382)) ([51d6e41](https://github.com/electron-userland/electron-builder/commit/51d6e41a910464b46c7fed56b4007e50474b4f2e)), closes [#1370](https://github.com/electron-userland/electron-builder/issues/1370)
* **updater:** handle errors on responses in differential download ([#7542](https://github.com/electron-userland/electron-builder/issues/7542)) ([9123e31](https://github.com/electron-userland/electron-builder/commit/9123e31eb792211da717804e5a5b8029fe694d5f)), closes [#2398](https://github.com/electron-userland/electron-builder/issues/2398)
* **updater:** Remove checks for app-update.yml when auto-updates are not supported ([#6616](https://github.com/electron-userland/electron-builder/issues/6616)) ([86e6d15](https://github.com/electron-userland/electron-builder/commit/86e6d1509f9b9c76c559e9c3a12b7a1595fe3ac4)), closes [#6322](https://github.com/electron-userland/electron-builder/issues/6322)
* **updater:** Support Electron 11 and below (Node < 14) ([#6594](https://github.com/electron-userland/electron-builder/issues/6594)) ([edc4b03](https://github.com/electron-userland/electron-builder/commit/edc4b030703ee3929b31608a496798635169f5b1)), closes [#6000](https://github.com/electron-userland/electron-builder/issues/6000)
* updating electron-osx-sign ([#6021](https://github.com/electron-userland/electron-builder/issues/6021)) ([6f63092](https://github.com/electron-userland/electron-builder/commit/6f630927ca949d8bdcde06e4eafaa63ce3636d5a)), closes [#6010](https://github.com/electron-userland/electron-builder/issues/6010) [#5190](https://github.com/electron-userland/electron-builder/issues/5190)
* updating integration test for prerelease flag ([#7072](https://github.com/electron-userland/electron-builder/issues/7072)) ([f205998](https://github.com/electron-userland/electron-builder/commit/f205998999ff615c9ea63184520a1efbbff5a785))
* updating nsis script to properly identify arm64 vs x64 vs ia32 package files within universal installers. ([#5558](https://github.com/electron-userland/electron-builder/issues/5558)) ([60f7fe3](https://github.com/electron-userland/electron-builder/commit/60f7fe367c54f7c1274e2628534f43cb9a93fcf6))
* updating SignOptions typesafety and leverage `optionsForFile` for entitlements ([#7491](https://github.com/electron-userland/electron-builder/issues/7491)) ([c1deace](https://github.com/electron-userland/electron-builder/commit/c1deace1de707faacb02ae49cfaa59d60ab6ac06))
* updating simple-update-notifier version to resolve vulnerability ([#7673](https://github.com/electron-userland/electron-builder/issues/7673)) ([355e356](https://github.com/electron-userland/electron-builder/commit/355e35654510daded399ea31ed0bcd37effde935))
* Upload release failed. Response status: 401 Unauthorized ([257a7dd](https://github.com/electron-userland/electron-builder/commit/257a7ddd9451e75ebaa771755c6273a404eaf82f)), closes [#1385](https://github.com/electron-userland/electron-builder/issues/1385)
* use `pathToFileUrl` for hooks for Windows ES module support ([#8069](https://github.com/electron-userland/electron-builder/issues/8069)) ([538dd86](https://github.com/electron-userland/electron-builder/commit/538dd86bf52f0091dbb1120bdd30f56dfdbd5747))
* Use `update-alternatives` instead of symlinks for [#7500](https://github.com/electron-userland/electron-builder/issues/7500) ([#7501](https://github.com/electron-userland/electron-builder/issues/7501)) ([e83dc81](https://github.com/electron-userland/electron-builder/commit/e83dc814725f543c6b51721fdbfee83158d35084))
* use app-builder as xz-7za proxy ([e35846a](https://github.com/electron-userland/electron-builder/commit/e35846aac2fc6ca61d5259f9bc51cb2aaa26961d)), closes [#2523](https://github.com/electron-userland/electron-builder/issues/2523)
* use CI_COMMIT_TAG instead of CI_BUILD_TAG for Gitlab CI ([#8010](https://github.com/electron-userland/electron-builder/issues/8010)) ([f5340b7](https://github.com/electron-userland/electron-builder/commit/f5340b732dc0a303743a2a924750e9861e3a345f))
* use electron-rebuilder API directly so as to override the platform for cross-platform prebuild compilations ([#7629](https://github.com/electron-userland/electron-builder/issues/7629)) ([285aa76](https://github.com/electron-userland/electron-builder/commit/285aa766c2675448689f2e465b6fa2b2acacdbc6))
* Use fully-defined path `/usr/bin/___` to macOS signing utilities ([#7998](https://github.com/electron-userland/electron-builder/issues/7998)) ([61dfe7f](https://github.com/electron-userland/electron-builder/commit/61dfe7fbaa592785353348a16abd1525dcbfaf28))
* use http://sha256timestamp.ws.symantec.com/sha256/timestamp as timestamp server for sha256 ([20d7ca7](https://github.com/electron-userland/electron-builder/commit/20d7ca729992c1f3e1ca43a71ec52b18c8b6af33)), closes [#3059](https://github.com/electron-userland/electron-builder/issues/3059) [#3030](https://github.com/electron-userland/electron-builder/issues/3030)
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))
* use lowercased safe artifact name if app name is lowercased ([bfd6635](https://github.com/electron-userland/electron-builder/commit/bfd6635134a8ec10e05aaf0421647d94c5073102))
* use Muon version in the log message if pack for Muon ([4241521](https://github.com/electron-userland/electron-builder/commit/42415214ee28a0dff2cf22a3e3af792acb672208))
* use nullish coalescing operator for hardenedRuntime default value ([#7643](https://github.com/electron-userland/electron-builder/issues/7643)) ([5fec686](https://github.com/electron-userland/electron-builder/commit/5fec686412b23614bf17f76d03fecc66c220ac99))
* Use of extraResources prevents node_modules from being included in asar ([0fbad33](https://github.com/electron-userland/electron-builder/commit/0fbad33a93b138a06bf1ad7e4f98c526a22d49f0)), closes [#867](https://github.com/electron-userland/electron-builder/issues/867)
* use product name for helper apps ([#7900](https://github.com/electron-userland/electron-builder/issues/7900)) ([3b3a698](https://github.com/electron-userland/electron-builder/commit/3b3a69895f0caa3870219bc0bec7420de81a07ed)), closes [#6962](https://github.com/electron-userland/electron-builder/issues/6962)
* use product name for safe github artifact name if possible ([07b3caa](https://github.com/electron-userland/electron-builder/commit/07b3caa411fc821a56bfb476860c13dc3f413a11))
* use proper cache directory for `electron-updater` on macOS ([#7032](https://github.com/electron-userland/electron-builder/issues/7032)) ([caa32e0](https://github.com/electron-userland/electron-builder/commit/caa32e0708ba4347dd37e93174fce1d2c5660160))
* use transformer to notify about progress ([7fa56bc](https://github.com/electron-userland/electron-builder/commit/7fa56bc5058843fa18b2e94a2488925e6dc3ddb1)), closes [#1077](https://github.com/electron-userland/electron-builder/issues/1077)
* using regex to determine yarn version to account for newer releases of yarn (i.e. yarn 3). fixes: [#6069](https://github.com/electron-userland/electron-builder/issues/6069) ([#6071](https://github.com/electron-userland/electron-builder/issues/6071)) ([1e19aba](https://github.com/electron-userland/electron-builder/commit/1e19abaecb3fd7b6ff0932b46ee129e04d1496b3))
* utilizing frameworkInfo as primary manner of fetching electron version for installation. ([#7511](https://github.com/electron-userland/electron-builder/issues/7511)) ([16283cc](https://github.com/electron-userland/electron-builder/commit/16283ccaf5788b1a60c28f6d1424f72eebecea46))
* validate using semver.coerce() ([#3477](https://github.com/electron-userland/electron-builder/issues/3477)) ([a46f79a](https://github.com/electron-userland/electron-builder/commit/a46f79ad81001b9d096215ae2db1585dbaa096e2)), closes [#3475](https://github.com/electron-userland/electron-builder/issues/3475)
* Weird ref_0 lines being written in latest-mac.yml ([72c858c](https://github.com/electron-userland/electron-builder/commit/72c858cb24b00125b5ec1e56ce08d1299931f8f2)), closes [#2993](https://github.com/electron-userland/electron-builder/issues/2993)
* When error code is ENOENT, try to use `electron.shell.openPath` to open Windows installer ([#7767](https://github.com/electron-userland/electron-builder/issues/7767)) ([21f3069](https://github.com/electron-userland/electron-builder/commit/21f3069cb6dcad30959af4bfd8f3014133a3dfde))
* **win/mac:** Small security fixes for electron-updater ([#6589](https://github.com/electron-userland/electron-builder/issues/6589)) ([633ee5d](https://github.com/electron-userland/electron-builder/commit/633ee5dc292174ed1486c53af93320f20cf02169))
* **win:** add note about macos sharing. ([8979a5a](https://github.com/electron-userland/electron-builder/commit/8979a5a82a2692074c92084531e8ae4a22fb90ba))
* windows async signing ([9162711](https://github.com/electron-userland/electron-builder/commit/91627116fdffd5d5faec23e149392283b9979a22))
* windowsCodeSign - don't use osslsigncode in a vm! ([#7275](https://github.com/electron-userland/electron-builder/issues/7275)) ([5668dc2](https://github.com/electron-userland/electron-builder/commit/5668dc204b83ae0c1edf79a4998f41292007d230))
* **windows:** detect node path correctly on windows with cross-spawn ([#6069](https://github.com/electron-userland/electron-builder/issues/6069)) ([#6172](https://github.com/electron-userland/electron-builder/issues/6172)) ([6c945bd](https://github.com/electron-userland/electron-builder/commit/6c945bd59749d3fdd91f50ea4131ee22e82f72a2))
* **windows:** disable feature "sign dlls" by default ([f474ecb](https://github.com/electron-userland/electron-builder/commit/f474ecbab0ea5bf975a135830f8cfb573d2d77ab))
* **windows:** fix encoding issues while verifying signatures ([#5071](https://github.com/electron-userland/electron-builder/issues/5071)) ([70a0b80](https://github.com/electron-userland/electron-builder/commit/70a0b802b6225adb592f799c7cb129759d4b1c5c))
* **windows:** Get-PfxCertificate hangs ([6f8b94b](https://github.com/electron-userland/electron-builder/commit/6f8b94bdccb0fbfbae974b508b5de8f34f93201d)), closes [#1735](https://github.com/electron-userland/electron-builder/issues/1735)
* **windows:** signing hash algorithms 256 doesn't work EV Code Signing Certificate Windows 7 ([a224d67](https://github.com/electron-userland/electron-builder/commit/a224d67525d5f0ef69ed7f5ea5645083a3c80128)), closes [#2195](https://github.com/electron-userland/electron-builder/issues/2195)
* **windows:** use build number env only if numeric ([7532142](https://github.com/electron-userland/electron-builder/commit/7532142dc76f5a2febfbb12eb2a26f225039f2f7)), closes [#2635](https://github.com/electron-userland/electron-builder/issues/2635)
* **win:** Include swiftshader in signing directories for windows ([#6682](https://github.com/electron-userland/electron-builder/issues/6682)) ([e6312cb](https://github.com/electron-userland/electron-builder/commit/e6312cb54e5d957289d5c07b506491fcaea9e334))
* **win:** product file name is too long causing the find process exe failed ([#7955](https://github.com/electron-userland/electron-builder/issues/7955)) ([88e61bc](https://github.com/electron-userland/electron-builder/commit/88e61bc410fae8c0bea0b2029ee1347864af98ac))
* **win:** Relay exit code in portable app ([#3378](https://github.com/electron-userland/electron-builder/issues/3378)) ([56ddb8e](https://github.com/electron-userland/electron-builder/commit/56ddb8ee4c1d99582ee7864443c6b18e749df6f5))
* **win:** revert to timestamp.comodoca.com until code sign error not clear ([7d8fffe](https://github.com/electron-userland/electron-builder/commit/7d8fffe9c5353cd784bd1c1868e53a8ae6c80b1f))
* **win:** show raw result in error message ([74d8d68](https://github.com/electron-userland/electron-builder/commit/74d8d68ea03d1f5cfee53b58cfc1c3fb8ac95b70)), closes [#2458](https://github.com/electron-userland/electron-builder/issues/2458)
* **win:** Sign all your asar unpacked binaries ([771b081](https://github.com/electron-userland/electron-builder/commit/771b081a34bf20bd51547111b319c2a261728d85)), closes [#3997](https://github.com/electron-userland/electron-builder/issues/3997)
* **win:** SignTool Error ([bd06054](https://github.com/electron-userland/electron-builder/commit/bd0605407c0372d107bffb474bbf6146f6b4a54c)), closes [#3112](https://github.com/electron-userland/electron-builder/issues/3112) [#3228](https://github.com/electron-userland/electron-builder/issues/3228)
* **win:** use `resultOutputPath` to sign custom location for windows ([#7919](https://github.com/electron-userland/electron-builder/issues/7919)) ([4e930a7](https://github.com/electron-userland/electron-builder/commit/4e930a74d7c2e9b53d47e37997b444da95680a24)), closes [#7910](https://github.com/electron-userland/electron-builder/issues/7910)
* **win:** use appInfo `description` as primary entry for `FileDescription` ([#8125](https://github.com/electron-userland/electron-builder/issues/8125)) ([c6c9d59](https://github.com/electron-userland/electron-builder/commit/c6c9d59e4cc8444ab847a14bf64364b065a384ee))
* **win:** Windows update fails for custom paths that require admin rights ([#6073](https://github.com/electron-userland/electron-builder/issues/6073)) ([45fc0a0](https://github.com/electron-userland/electron-builder/commit/45fc0a003abc58969bb3a5d6ab1e3b61a9ad1a8d))
* workaround vite replacing process.env in updater ([#6160](https://github.com/electron-userland/electron-builder/issues/6160)) ([a3c72b2](https://github.com/electron-userland/electron-builder/commit/a3c72b2481ebaacfd717a7c492c119bcb9b7fc36))
* Wrap the nsProcess include in a !ifndef ([#6996](https://github.com/electron-userland/electron-builder/issues/6996)) ([5301525](https://github.com/electron-userland/electron-builder/commit/53015253939f450468a6d8e0405697ea70c2a138))
* write blockmap file for mac zip archives ([#6023](https://github.com/electron-userland/electron-builder/issues/6023)) ([0447b24](https://github.com/electron-userland/electron-builder/commit/0447b2457beb03648f1e7e841cd0a8d12d7e4aea)), closes [#4299](https://github.com/electron-userland/electron-builder/issues/4299)
* writeAsarFile — use close event instead of end ([3f41497](https://github.com/electron-userland/electron-builder/commit/3f41497e8db5e798f16a0138635983f299e624ec))
* wrong permissions on Linux results ([30c3904](https://github.com/electron-userland/electron-builder/commit/30c3904d3cff6e2166c49068b4f72ed47e3daf96)), closes [#2682](https://github.com/electron-userland/electron-builder/issues/2682)
* x64 prebuilt binaries get overridden by ia32 binaries during dependency rebuild ([c0ea484](https://github.com/electron-userland/electron-builder/commit/c0ea4849bf8bbbd4d210409b1b182d54f8697710)), closes [#3038](https://github.com/electron-userland/electron-builder/issues/3038)


### chore

* v23.0.0 alpha ([#6556](https://github.com/electron-userland/electron-builder/issues/6556)) ([a138a86](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)), closes [#4898](https://github.com/electron-userland/electron-builder/issues/4898) [#6232](https://github.com/electron-userland/electron-builder/issues/6232) [#6259](https://github.com/electron-userland/electron-builder/issues/6259) [#6511](https://github.com/electron-userland/electron-builder/issues/6511) [#6506](https://github.com/electron-userland/electron-builder/issues/6506) [#6507](https://github.com/electron-userland/electron-builder/issues/6507) [#6514](https://github.com/electron-userland/electron-builder/issues/6514) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#3683](https://github.com/electron-userland/electron-builder/issues/3683) [#6201](https://github.com/electron-userland/electron-builder/issues/6201) [#6530](https://github.com/electron-userland/electron-builder/issues/6530) [#6550](https://github.com/electron-userland/electron-builder/issues/6550)


### Code Refactoring

* extract electron-builder-squirrel-windows ([6256432](https://github.com/electron-userland/electron-builder/commit/625643283f4f5ec123ade4288ab02abc4e0d76ae))
* merge electron-builder-core into electron-builder, transform node-gyp-rebuild bin to subcommand ([a8c9ffd](https://github.com/electron-userland/electron-builder/commit/a8c9ffd9e3bb613a88360c51321318e8eb50aa76))
* **updater:** prepare to support private github repo, nuts and so on on macOS ([a41936b](https://github.com/electron-userland/electron-builder/commit/a41936b182300506fadfa3827b002e2fc903556f)), closes [#1575](https://github.com/electron-userland/electron-builder/issues/1575) [#1571](https://github.com/electron-userland/electron-builder/issues/1571) [#1577](https://github.com/electron-userland/electron-builder/issues/1577)


### Features

*  Added support for overriding ‘preAutoEntitlements’ for electron/osx-sign ([#7642](https://github.com/electron-userland/electron-builder/issues/7642)) ([2717282](https://github.com/electron-userland/electron-builder/commit/2717282cbff0dc0b6dee7e5af1fa0ecfcff1d5bf))
* --config option ([472ef7e](https://github.com/electron-userland/electron-builder/commit/472ef7e01e51dfd22aca08a127446294aeae21e4)), closes [#1229](https://github.com/electron-userland/electron-builder/issues/1229)
* --config option ([a9f2ad8](https://github.com/electron-userland/electron-builder/commit/a9f2ad8ea9eb933e80ad569727cf7c3c4692c876))
* ${buildVersion} macro in artifactName config ([23f0b37](https://github.com/electron-userland/electron-builder/commit/23f0b378103158ff17fbb07c138fd9b21010c2d3)), closes [#1527](https://github.com/electron-userland/electron-builder/issues/1527)
* ${os} and ${arch} in publish.url ([6863896](https://github.com/electron-userland/electron-builder/commit/68638962b45165c78bbcb25cfe8f66690f7f6b24)), closes [#1194](https://github.com/electron-userland/electron-builder/issues/1194)
* 32 bit appx  ([01604cf](https://github.com/electron-userland/electron-builder/commit/01604cf94880ccbaa370efb73c8b781f93f9d684))
* ability to specify compression per platform ([b223c96](https://github.com/electron-userland/electron-builder/commit/b223c96344036a757052583abf66905fcbb06069))
* add `afterExtract` hook for after electron distributable has been unpacked ([#8194](https://github.com/electron-userland/electron-builder/issues/8194)) ([588c5db](https://github.com/electron-userland/electron-builder/commit/588c5db47c97e06b540bdc7f7a6de9a936a7603b))
* add `beforePack` hook ([#6176](https://github.com/electron-userland/electron-builder/issues/6176)) ([6f42f64](https://github.com/electron-userland/electron-builder/commit/6f42f646c9d36405c9d69ca45dda51baabdec4bd))
* add `customUnWelcomePage` macro for nsis ([#7790](https://github.com/electron-userland/electron-builder/issues/7790)) ([1a412f4](https://github.com/electron-userland/electron-builder/commit/1a412f4d07304fcd0404ac04b5085ffd394db6cf))
* add afterPack call after macOS universal package is created ([#6887](https://github.com/electron-userland/electron-builder/issues/6887)) ([4d590d3](https://github.com/electron-userland/electron-builder/commit/4d590d302f6c3baacf9dabf338904fef337960a6))
* Add base option for snapcraft ([#7320](https://github.com/electron-userland/electron-builder/issues/7320)) ([2852cb5](https://github.com/electron-userland/electron-builder/commit/2852cb56a337709f8b7f0bcbf92b034ec8a07e7f))
* add beforeBuild callback ([#1085](https://github.com/electron-userland/electron-builder/issues/1085)) ([35a8cdf](https://github.com/electron-userland/electron-builder/commit/35a8cdfeb7656f88475fb1d1da09004d6746e0ad)), closes [#982](https://github.com/electron-userland/electron-builder/issues/982)
* add channel to file macros ([6aa3809](https://github.com/electron-userland/electron-builder/commit/6aa380950b8995873ed15371770910faaec4637e)), closes [#1701](https://github.com/electron-userland/electron-builder/issues/1701)
* Add CLI and API for only publishing assets (skipping `build` flow) ([#8150](https://github.com/electron-userland/electron-builder/issues/8150)) ([f4e6ae2](https://github.com/electron-userland/electron-builder/commit/f4e6ae2931cbf79670b5f2c252a91bed03d96546))
* add config options for setting `MinVersion` and `MaxVersionTested` fields in appx manifest ([#8142](https://github.com/electron-userland/electron-builder/issues/8142)) ([8160363](https://github.com/electron-userland/electron-builder/commit/8160363ac2821242ab22e225a9038b56e4798cc6))
* add custom download completed notification ([#4952](https://github.com/electron-userland/electron-builder/issues/4952)) ([3ffea83](https://github.com/electron-userland/electron-builder/commit/3ffea83eaf399a6cab0db460f9777fea4e1631bd))
* add custom macro for checking uninstallation results ([#5712](https://github.com/electron-userland/electron-builder/issues/5712)) ([e425020](https://github.com/electron-userland/electron-builder/commit/e4250206e936dbcad7ddd19f32e7688afce1239e))
* add disableSanityCheckPackage to asar to allow custom electron fork asar integrity implementations ([#8123](https://github.com/electron-userland/electron-builder/issues/8123)) ([031d7d5](https://github.com/electron-userland/electron-builder/commit/031d7d5bdf911cb6dc4b0b108f82df44f4c2b224))
* add Electron branding options ([#5727](https://github.com/electron-userland/electron-builder/issues/5727)) ([0de5f1f](https://github.com/electron-userland/electron-builder/commit/0de5f1f7d4496462726d1305ad0aeec43d337c30))
* add Github Actions environment variable to isPullRequest method ([#7152](https://github.com/electron-userland/electron-builder/issues/7152)) ([4583273](https://github.com/electron-userland/electron-builder/commit/4583273ebe5cabfd1c14f647dc9edb7bff3c3bf3))
* Add installDir property for NsisUpdater ([#6907](https://github.com/electron-userland/electron-builder/issues/6907)) ([e7f2867](https://github.com/electron-userland/electron-builder/commit/e7f286776643823f9c906738aade1d71eb1bdd9c))
* add minimumSystemVersion in electron updater ([#8108](https://github.com/electron-userland/electron-builder/issues/8108)) ([3d4cc7a](https://github.com/electron-userland/electron-builder/commit/3d4cc7ae01c4f6154d6ea59726578b1ff99b9daf))
* add nsis option `removeDefaultUninstallWelcomePage` to remove the default uninstall welcome page ([#7141](https://github.com/electron-userland/electron-builder/issues/7141)) ([d71a579](https://github.com/electron-userland/electron-builder/commit/d71a5790a94cd56b6e033b656b4892ec31f14b9d))
* add option `includePdb` to include PDB files ([c6f96d3](https://github.com/electron-userland/electron-builder/commit/c6f96d373459ac21a2e2bff32c117a90734151d5)), closes [#2433](https://github.com/electron-userland/electron-builder/issues/2433)
* add option for quitAndInstall for non-silent update without restart ([#7136](https://github.com/electron-userland/electron-builder/issues/7136)) ([4d989a8](https://github.com/electron-userland/electron-builder/commit/4d989a8a52bf7baac22742769abcc795ce193fbd))
* add option removePackageKeywords ([#5814](https://github.com/electron-userland/electron-builder/issues/5814)) ([dcf570f](https://github.com/electron-userland/electron-builder/commit/dcf570f5fedbd26e33fa58d8926609918b43b9a1))
* Add Support for a separate Github release token to the auto-update token ([#8173](https://github.com/electron-userland/electron-builder/issues/8173)) ([3ae3589](https://github.com/electron-userland/electron-builder/commit/3ae3589a63c2d915b8456d9dc81a965a1366c73b))
* add support for differential zip updates on macOS ([#7709](https://github.com/electron-userland/electron-builder/issues/7709)) ([79df542](https://github.com/electron-userland/electron-builder/commit/79df54238621fbe48ba20444129950ba2dc49983))
* add support for executableName to non-Linux Platforms ([#5409](https://github.com/electron-userland/electron-builder/issues/5409)) ([106b680](https://github.com/electron-userland/electron-builder/commit/106b68010f2daa0fb7d370c889b4a5494fa2887f))
* add support for gitlab ci pipeline ids as buildNumber ([#3838](https://github.com/electron-userland/electron-builder/issues/3838)) ([0972695](https://github.com/electron-userland/electron-builder/commit/09726952278c9977f81a530a10e9f87dcbfcc756))
* Add the accelerate option for s3 buckets ([#7314](https://github.com/electron-userland/electron-builder/issues/7314)) ([cc1ddab](https://github.com/electron-userland/electron-builder/commit/cc1ddabd45f239ee06fde9b2d1534467908791fa))
* added `ELECTRON_BUILDER_7Z_FILTER ` env variable for 7z filter ([#7609](https://github.com/electron-userland/electron-builder/issues/7609)) ([99f49cf](https://github.com/electron-userland/electron-builder/commit/99f49cf7a86afa33d35652ffc6329fefed2e5f75))
* added support for shortVersion and shortVersionWindows strings in package.json ([#4517](https://github.com/electron-userland/electron-builder/issues/4517)) ([71726a7](https://github.com/electron-userland/electron-builder/commit/71726a7849e2960884f0874003a3071e0e9713e3))
* adding Bitbucket publisher and autoupdater ([#6228](https://github.com/electron-userland/electron-builder/issues/6228)) ([a945321](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8))
* Adding download-progress event to AutoUpdater ([#1042](https://github.com/electron-userland/electron-builder/issues/1042)) ([b3a0be0](https://github.com/electron-userland/electron-builder/commit/b3a0be0dd316ac69562fa213894351e9922ef26e)), closes [#958](https://github.com/electron-userland/electron-builder/issues/958)
* Adding Keygen as an official publisher/updater for electron-builder ([#6167](https://github.com/electron-userland/electron-builder/issues/6167)) ([f45110c](https://github.com/electron-userland/electron-builder/commit/f45110cbf66572d5748d21fc24dc26cabd06f35f))
* Adding new downloadAlternateFFmpeg option to download non-proprietary ffmpeg library ([#7210](https://github.com/electron-userland/electron-builder/issues/7210)) ([#7477](https://github.com/electron-userland/electron-builder/issues/7477)) ([1dd26cc](https://github.com/electron-userland/electron-builder/commit/1dd26cc646c1a9708ff880920319bdaad17d20ba))
* Adding timeout to publisher config for api requests and uploads ([#7028](https://github.com/electron-userland/electron-builder/issues/7028)) ([e7179b5](https://github.com/electron-userland/electron-builder/commit/e7179b57bdba192acfdb439c03099e6629e98f6a))
* Advanced file copying supported for "files" ([2316381](https://github.com/electron-userland/electron-builder/commit/2316381d2c9a8107ed3010e7cca70faeb16c2698)), closes [#1096](https://github.com/electron-userland/electron-builder/issues/1096)
* afterAllArtifactBuild hook ([e7ff5e8](https://github.com/electron-userland/electron-builder/commit/e7ff5e85eaa307294ea6c99c143c4bbad5e73e01)), closes [#3116](https://github.com/electron-userland/electron-builder/issues/3116)
* afterSign hook ([#2452](https://github.com/electron-userland/electron-builder/issues/2452)) ([662d8ad](https://github.com/electron-userland/electron-builder/commit/662d8ad029d7bd9e263f3d5a1317dba5f976adb1))
* allow `./` in the file pattern ([1152f2b](https://github.com/electron-userland/electron-builder/commit/1152f2b7b0aab103adc52ab449e05f7352fefc0b))
* allow `onNodeModuleFile` to return a boolean to force include the package to be copied ([#8043](https://github.com/electron-userland/electron-builder/issues/8043)) ([bb4a8c0](https://github.com/electron-userland/electron-builder/commit/bb4a8c09318045938bfff5a0d1db8f17f0fa4e8c))
* allow api key and keychain for mac notarization ([#7861](https://github.com/electron-userland/electron-builder/issues/7861)) ([906ffb1](https://github.com/electron-userland/electron-builder/commit/906ffb1fcebe6aef4dc6c6a3fab10aa7d9378c3f))
* allow custom makensis and nsis logging ([#6024](https://github.com/electron-userland/electron-builder/issues/6024)) ([a99a7c8](https://github.com/electron-userland/electron-builder/commit/a99a7c87ffd7ffaaa5fae1a17f731a59aac60581)), closes [#5119](https://github.com/electron-userland/electron-builder/issues/5119)
* allow customization of bundleIdentifier for the new Electron 6+ renderer processes ([#4692](https://github.com/electron-userland/electron-builder/issues/4692)) ([8b1cebc](https://github.com/electron-userland/electron-builder/commit/8b1cebca3cc2e076c1bb95687938cfbecad4334b)), closes [#4691](https://github.com/electron-userland/electron-builder/issues/4691)
* Allow for NSIS windows installer to be wrapped in an MSI ([#7407](https://github.com/electron-userland/electron-builder/issues/7407)) ([a338730](https://github.com/electron-userland/electron-builder/commit/a3387309f0297cb824926bd7fa5cb653da9f24ca))
* allow python path to be configurable ([#5894](https://github.com/electron-userland/electron-builder/issues/5894)) ([529670d](https://github.com/electron-userland/electron-builder/commit/529670d5cebb1dc21cfdf129a68d38f36fb15f40)), closes [#5889](https://github.com/electron-userland/electron-builder/issues/5889)
* Allow specifying additional WiX compiler options ([#5813](https://github.com/electron-userland/electron-builder/issues/5813)) ([4e2909c](https://github.com/electron-userland/electron-builder/commit/4e2909cdf56aabd11330dc55f57993efadf55d87))
* allow specifying recommended dependencies for deb target ([#7558](https://github.com/electron-userland/electron-builder/issues/7558)) ([54c8537](https://github.com/electron-userland/electron-builder/commit/54c85374790f7a8e0dc520a20c716b4afe69be20))
* Allow the AppUpdater to be forced into dev mode, allowing it to be activated when the app is not packaged ([#7117](https://github.com/electron-userland/electron-builder/issues/7117)) ([0c52841](https://github.com/electron-userland/electron-builder/commit/0c528411fb8a7de23e974f44e36c5e69bd3bb167))
* allow to set electronDist as path to local folder with electron builds zipped ([e79a28c](https://github.com/electron-userland/electron-builder/commit/e79a28c647514d3d723f96504061880e0126c919)), closes [#1716](https://github.com/electron-userland/electron-builder/issues/1716)
* Allow to use ~/.aws/credentials file as alternative to env variables ([2e59959](https://github.com/electron-userland/electron-builder/commit/2e599598900763631ae8685b5548cc1d97a12d7e)), closes [#1320](https://github.com/electron-userland/electron-builder/issues/1320)
* allow to use files in the output directory to be included into the app ([af9844d](https://github.com/electron-userland/electron-builder/commit/af9844d666831abf16822f709bf61ed3b9a14711))
* Allow usage of environmental variables in extraFiles and extraResources ([cfc2715](https://github.com/electron-userland/electron-builder/commit/cfc27157f6a6d5b89db488d907f6efeea9a79b1d)), closes [#1307](https://github.com/electron-userland/electron-builder/issues/1307)
* ALLOW_ELECTRON_BUILDER_AS_PRODUCTION_DEPENDENCY to allow electron-builder as production dependency ([d519bfa](https://github.com/electron-userland/electron-builder/commit/d519bfaa8b6bfe3a19651f97700ab9cb6a50d51f))
* **app-builder-lib:** the pkg interface adds the must-close attribute ([#4380](https://github.com/electron-userland/electron-builder/issues/4380)) ([#4382](https://github.com/electron-userland/electron-builder/issues/4382)) ([4d88848](https://github.com/electron-userland/electron-builder/commit/4d8884867b66018cd97481a7759b39d11fe0e378))
* **appimage:** artifactName support for AppImage ([0ea43a3](https://github.com/electron-userland/electron-builder/commit/0ea43a32524111ec8775f957d71a8a7c953880a6)), closes [#775](https://github.com/electron-userland/electron-builder/issues/775)
* **AppImage:** ElementaryOS and libappindicator1 support by default ([580eeaa](https://github.com/electron-userland/electron-builder/commit/580eeaa433addc0f76435cb7518c4bf8155ce8bd)), closes [#1082](https://github.com/electron-userland/electron-builder/issues/1082)
* **AppImage:** EULA for AppImage ([77360ad](https://github.com/electron-userland/electron-builder/commit/77360ad8ba01210429008ad8771020a9ba1af85d))
* **AppImage:** Fedora support ([ca7745d](https://github.com/electron-userland/electron-builder/commit/ca7745d20a8c1a23bbcd76180db3a17128c5e2b1))
* **appimage:** ia32 prebundled libs ([57c32a7](https://github.com/electron-userland/electron-builder/commit/57c32a7b8bb230761336b62a76e31023599da380)), closes [#1983](https://github.com/electron-userland/electron-builder/issues/1983)
* **AppImage:** Linux supports only txt EULA ([c1d6184](https://github.com/electron-userland/electron-builder/commit/c1d61846c0bf2f7b8c4085580c0a216c92b69845))
* **appimage:** move logic to app-builder, improve linux icon resolving ([8f106a0](https://github.com/electron-userland/electron-builder/commit/8f106a0309a253c63d5be9ffbf8e132b4e80eeb9)), closes [#2570](https://github.com/electron-userland/electron-builder/issues/2570)
* **appImage:** option to disable "integrate $APPIMAGE with your system" prompt ([09b9fb4](https://github.com/electron-userland/electron-builder/commit/09b9fb4ed5773b9caf162c7c1f43ce3a65b2b5e1)), closes [#1962](https://github.com/electron-userland/electron-builder/issues/1962)
* **appimage:** remove desktop integration in favour of AppImageLauncher ([eb27d9c](https://github.com/electron-userland/electron-builder/commit/eb27d9c5802af0a90507df77846b426c8046e0a7))
* **AppImage:** support armv7l arch ([fd2a1f0](https://github.com/electron-userland/electron-builder/commit/fd2a1f0794d6f4ded47baa7091fe70fc1628f1b5)), closes [#1478](https://github.com/electron-userland/electron-builder/issues/1478)
* **AppImage:** support html EULA ([80eaf23](https://github.com/electron-userland/electron-builder/commit/80eaf2337f10b11ceaa8abbc05a6e8c771e4614f))
* **AppImage:** support type 2 image format ([c8cd76a](https://github.com/electron-userland/electron-builder/commit/c8cd76a921ff29197bda02cf9657c547c265d7fc)), closes [#2136](https://github.com/electron-userland/electron-builder/issues/2136) [#1998](https://github.com/electron-userland/electron-builder/issues/1998) [#832](https://github.com/electron-userland/electron-builder/issues/832) [#993](https://github.com/electron-userland/electron-builder/issues/993)
* Apple Silicon Universal Support ([#5481](https://github.com/electron-userland/electron-builder/issues/5481)) ([ca20151](https://github.com/electron-userland/electron-builder/commit/ca20151c3416324d2413f451dea0c9e3853bab79))
* **appx:** Add appx option to show app name on tiles. ([#3802](https://github.com/electron-userland/electron-builder/issues/3802)) ([fa90f49](https://github.com/electron-userland/electron-builder/commit/fa90f49d299a7398d0a9213a9fc331b2150c9735))
* **appx:** Add option to force set build number for AppX ([d6c9d8f](https://github.com/electron-userland/electron-builder/commit/d6c9d8fa704d0fe9bf3ed419c5dd4d59118695a8)), closes [#3875](https://github.com/electron-userland/electron-builder/issues/3875)
* **appx:** add support for custom extensions in appmanifest.xml ([6d7b25c](https://github.com/electron-userland/electron-builder/commit/6d7b25cf7c3ec89273b01d9b24003851b76a26c6)), closes [#4707](https://github.com/electron-userland/electron-builder/issues/4707)
* **appx:** add support for modifying .appx manifest ([#4613](https://github.com/electron-userland/electron-builder/issues/4613)) ([d5d21da](https://github.com/electron-userland/electron-builder/commit/d5d21da12f5efaf02659ce8d32c48440f6cf91ff))
* **appx:** added missing support for AppX fileAssociations ([#4302](https://github.com/electron-userland/electron-builder/issues/4302)) ([b16a890](https://github.com/electron-userland/electron-builder/commit/b16a89014adcd01e492670c3976dcf105e77a284))
* **appx:** Added support for Appx URL-Schemes ([931e605](https://github.com/electron-userland/electron-builder/commit/931e605b08980031947fb800623746e0e293ab8a)), closes [#3373](https://github.com/electron-userland/electron-builder/issues/3373)
* **appx:** applicationId option for AppX ([eb9e2ea](https://github.com/electron-userland/electron-builder/commit/eb9e2ea6274f7401ee4bb44c9ed82d6bf23afb5b)), closes [#2108](https://github.com/electron-userland/electron-builder/issues/2108)
* **appx:** build appx on macOS using Parallels Desktop for Mac ([909b840](https://github.com/electron-userland/electron-builder/commit/909b84012d10c7790fd21e275591506064a5fe25))
* **appx:** build appx on macOS using Parallels Desktop for Mac ([c91d3c0](https://github.com/electron-userland/electron-builder/commit/c91d3c0057e12b1266572d335b4ef353e5ffae7a))
* **appx:** Improve support for AppX assets ([666dec7](https://github.com/electron-userland/electron-builder/commit/666dec73c4d8c966a55a346fc1b365cf315a4193))
* **appx:** languages ([86af4cd](https://github.com/electron-userland/electron-builder/commit/86af4cd9da1c289c503cb062d5cfd9cb42983f28)), closes [#1684](https://github.com/electron-userland/electron-builder/issues/1684)
* **appx:** more customizable manifest fields ([cdc7219](https://github.com/electron-userland/electron-builder/commit/cdc72194c12b9709b3e1d9406a9c1142f030fefc))
* **appx:** support electron-winstore-auto-launch ([91d55da](https://github.com/electron-userland/electron-builder/commit/91d55da6009d23758be8a2b1916941e8f64d608c)), closes [#3072](https://github.com/electron-userland/electron-builder/issues/3072)
* **appx:** Update `identityName` for windows 10 ([#8206](https://github.com/electron-userland/electron-builder/issues/8206)) ([51111a8](https://github.com/electron-userland/electron-builder/commit/51111a87a541ccf826dcd11393b4b3a0e83ca368))
* **appx:** use identityName for app name ([#1941](https://github.com/electron-userland/electron-builder/issues/1941)) ([0be983e](https://github.com/electron-userland/electron-builder/commit/0be983e52c9477693e226cfb2354fa9a2adba7ae))
* **archive:** skip nsis compression step when archive is already up to date ([#7971](https://github.com/electron-userland/electron-builder/issues/7971)) ([8803852](https://github.com/electron-userland/electron-builder/commit/8803852c7aadf56771f537dc33ffd51c14830f50))
* arm64 support ([#2490](https://github.com/electron-userland/electron-builder/issues/2490)) ([23c594b](https://github.com/electron-userland/electron-builder/commit/23c594bc803be4951b717d71332d91d4dcc5d518)), closes [#2478](https://github.com/electron-userland/electron-builder/issues/2478)
* artifact file name pattern for pkg and dmg ([22746bd](https://github.com/electron-userland/electron-builder/commit/22746bd229c00cc7b42d1f11c8daa949f760d113)), closes [#966](https://github.com/electron-userland/electron-builder/issues/966)
* artifactBuildStarted event [#3493](https://github.com/electron-userland/electron-builder/issues/3493) ([e59f6c3](https://github.com/electron-userland/electron-builder/commit/e59f6c3b6155534fe2076fc1b8a0ba0bbc348f62))
* asar integrity (macos only for now) ([3e28ae2](https://github.com/electron-userland/electron-builder/commit/3e28ae28a0cf68adc0d1e6f809eae98d98e4fa5f))
* asar integrity: add externalAllowed option ([e0d7974](https://github.com/electron-userland/electron-builder/commit/e0d7974cbf0294524f47dbef62c9eb8398d2ecf0))
* asar integrity: base64, externalAllowed ([9a7ac65](https://github.com/electron-userland/electron-builder/commit/9a7ac6531b852549416ed740f1eb6f8a46653810))
* author macro ([7ed7289](https://github.com/electron-userland/electron-builder/commit/7ed7289d84bbfb28cdc3eba125d30a69cb69598f)), closes [#3006](https://github.com/electron-userland/electron-builder/issues/3006)
* automatically set channel to version prerelease component ([831186f](https://github.com/electron-userland/electron-builder/commit/831186f7c2fc9a26a75878e0a97cbf9ad5e2b653)), closes [#1182](https://github.com/electron-userland/electron-builder/issues/1182)
* build additional arch-specific nsis installers when ${arch} template is provided ([#5718](https://github.com/electron-userland/electron-builder/issues/5718)) ([7194c38](https://github.com/electron-userland/electron-builder/commit/7194c388f64cf9074e7ae14e74a7783da76ea284))
* build in distributable format prepackaged directory ([1c59534](https://github.com/electron-userland/electron-builder/commit/1c59534bb62c211217bc0fb9978a43b768ca84eb))
* build prepackaged app.asar ([60e1406](https://github.com/electron-userland/electron-builder/commit/60e1406a467b9aa7228936830d8ebda1570c7a1e)), closes [#1102](https://github.com/electron-userland/electron-builder/issues/1102)
* Build snap packages for Linux ([a7aa979](https://github.com/electron-userland/electron-builder/commit/a7aa97953bf2640674624bb32b56dc4b1add1eea)), closes [#509](https://github.com/electron-userland/electron-builder/issues/509)
* **build-service:** new electron-build-service ([2187ef3](https://github.com/electron-userland/electron-builder/commit/2187ef3a5dd9a951a964ebe089979b14d9def8d4))
* cancellable and progressable publishing ([a24f12c](https://github.com/electron-userland/electron-builder/commit/a24f12cbea90b17d394a9783152901a560d7d214))
* check that electron-builder version is not outdated for all subcommands ([d9ecfe5](https://github.com/electron-userland/electron-builder/commit/d9ecfe5246b6ffecf090957d906a14f6465e6064))
* clear error if rpmbuild is not installed, update deps for deb and rpm ([c605b6a](https://github.com/electron-userland/electron-builder/commit/c605b6ad1f787550d0088eafc11a678cf617de54))
* configurable electron-builder-binaries host ([#3761](https://github.com/electron-userland/electron-builder/issues/3761)) ([f3404d3](https://github.com/electron-userland/electron-builder/commit/f3404d32f029dfb63e83067012f15ef67838f326))
* Custom electronDist callback ([#5527](https://github.com/electron-userland/electron-builder/issues/5527)) ([4f4e018](https://github.com/electron-userland/electron-builder/commit/4f4e0187715a57a358ab8ccfefef3fd0f8186584))
* custom Windows sign tool timeout via env SIGNTOOL_TIMEOUT ([#1944](https://github.com/electron-userland/electron-builder/issues/1944)) ([dc107a4](https://github.com/electron-userland/electron-builder/commit/dc107a469cbdb8d5d8b4a3efd5c058f3439f0a6e))
* **deb:** "Priority" attribute for .deb packages ([6497678](https://github.com/electron-userland/electron-builder/commit/64976782e4bb3a87b205557681d6ec06eb791c47)), closes [#1088](https://github.com/electron-userland/electron-builder/issues/1088)
* **deployment:** Ability to configure S3 base url ([25be92f](https://github.com/electron-userland/electron-builder/commit/25be92f8fdf16325dc75aabcf61f71d4d7dbe772)), closes [#2233](https://github.com/electron-userland/electron-builder/issues/2233)
* **deployment:** Amazon S3 China region support ([33bb25c](https://github.com/electron-userland/electron-builder/commit/33bb25c84ee67a4b2656073216120865c6cf0f0d)), closes [#1799](https://github.com/electron-userland/electron-builder/issues/1799) [#1816](https://github.com/electron-userland/electron-builder/issues/1816)
* **deployment:** Building and Releasing using Channels ([42f2ba1](https://github.com/electron-userland/electron-builder/commit/42f2ba1f51cfca7053f60103edfae7ec1f1455f2)), closes [#1182](https://github.com/electron-userland/electron-builder/issues/1182)
* **deployment:** DigitalOcean Spaces support (publish & auto update) ([8a83577](https://github.com/electron-userland/electron-builder/commit/8a83577cfb9d13eb45826aac057808f6bb2388fa)), closes [#2101](https://github.com/electron-userland/electron-builder/issues/2101)
* **deployment:** do not publish if Pull Request — support APPVEYOR_PULL_REQUEST_NUMBER ([b0fb872](https://github.com/electron-userland/electron-builder/commit/b0fb8728e36f109f0107409e7831b2eb56eba19d))
* **deployment:** Do not upload auto-update files for the second configured provider ([cec3069](https://github.com/electron-userland/electron-builder/commit/cec30697912f56705fff42f7ac054fae4f4e735a)), closes [#2697](https://github.com/electron-userland/electron-builder/issues/2697)
* **deployment:** expand macros in all publish options ([#1349](https://github.com/electron-userland/electron-builder/issues/1349)) ([24fdf1d](https://github.com/electron-userland/electron-builder/commit/24fdf1d76bdcd15c8b64632cc12a66f219ac324e))
* **deployment:** Only first artifact is uploaded to GitHub ([e3ab55b](https://github.com/electron-userland/electron-builder/commit/e3ab55bdc4e453b97b7c58e07dd5df33ee5c46bc)), closes [#1133](https://github.com/electron-userland/electron-builder/issues/1133)
* **deployment:** publish patterned name if it conforms to GitHub rules ([e4430c5](https://github.com/electron-userland/electron-builder/commit/e4430c58dfca5a70da11782206864f73f496256d))
* **deployment:** releaseInfo per platform ([5e679b6](https://github.com/electron-userland/electron-builder/commit/5e679b6366e36b02e1e4a411bb03c014f97633a0))
* **deployment:** releaseType in the GitHub options ([c14a193](https://github.com/electron-userland/electron-builder/commit/c14a19300e426e6d99d20fdabb27ccbac529bb19))
* **deployment:** set electron-updater releaseNotes at build time ([f6a2fc8](https://github.com/electron-userland/electron-builder/commit/f6a2fc8e32ae5dbe15ca35702177fb83105efee0)), closes [#1511](https://github.com/electron-userland/electron-builder/issues/1511)
* **deployment:** support both GH_TOKEN and GITHUB_TOKEN ([#2503](https://github.com/electron-userland/electron-builder/issues/2503)) ([5e9d211](https://github.com/electron-userland/electron-builder/commit/5e9d21141d2ebc8629b1c3db133ea219f4a66ae8))
* **deployment:** support foo/bar repo as short form of owner foo and repo bar ([9d0e1fe](https://github.com/electron-userland/electron-builder/commit/9d0e1fe54c8374fcf08be64aadfeeb2136a54e2f)), closes [#1227](https://github.com/electron-userland/electron-builder/issues/1227)
* **deployment:** Upload of artifacts should be retried on failure ([7ffcd27](https://github.com/electron-userland/electron-builder/commit/7ffcd27e6304ee9584de880b269ca39f9e5f3182)), closes [#1749](https://github.com/electron-userland/electron-builder/issues/1749)
* Different architectures for different platforms ([f2056fa](https://github.com/electron-userland/electron-builder/commit/f2056fa89e42c9f271022d5ede94f64c44412be6)), closes [#1314](https://github.com/electron-userland/electron-builder/issues/1314)
* Different icons for application/file extension with same name on macOS and Windows ([04f11f6](https://github.com/electron-userland/electron-builder/commit/04f11f60733a7a51ed7ac2d48c28ec791c394061)), closes [#1268](https://github.com/electron-userland/electron-builder/issues/1268)
* differential update — use content defined chunking ([1dc2e49](https://github.com/electron-userland/electron-builder/commit/1dc2e495bebad68d9a5ff2b210ec29ae32bbe229))
* Disable adding meta-data to electron.exe on Windows ([97b0da4](https://github.com/electron-userland/electron-builder/commit/97b0da4d5b2b249272de84b4e64bbb3c73709717)), closes [#2323](https://github.com/electron-userland/electron-builder/issues/2323)
* **dmg:** Allow creation of file and dir in dmg, in addition to .app and link. ([#2064](https://github.com/electron-userland/electron-builder/issues/2064)) ([d1b3877](https://github.com/electron-userland/electron-builder/commit/d1b3877bbcc50aae8f358cf076bacdd3a9a33cca))
* **dmg:** dmg license ([d6f0c57](https://github.com/electron-userland/electron-builder/commit/d6f0c57f70751c4ff1d6ba548b5d3f9a0be03894)), closes [#1491](https://github.com/electron-userland/electron-builder/issues/1491)
* **dmg:** hide .VolumeIcon.icns ([d56326b](https://github.com/electron-userland/electron-builder/commit/d56326b6bd9b5f76457a63923150029b6b58cc37)), closes [#1121](https://github.com/electron-userland/electron-builder/issues/1121)
* **dmg:** Sign DMG ([351b0b4](https://github.com/electron-userland/electron-builder/commit/351b0b44a04e6eeadcbcd003745d6c2aab1cfe67))
* **dmg:** Support retina DMG background image ([67d224f](https://github.com/electron-userland/electron-builder/commit/67d224f5ae9d60ecd5f500d8a36339a0b92aa468)), closes [#1506](https://github.com/electron-userland/electron-builder/issues/1506)
* do not complain on node_modules missing when beforeBuild is set ([9d6eb96](https://github.com/electron-userland/electron-builder/commit/9d6eb9602522048597b185c604f02387820aa8d9)), closes [#2551](https://github.com/electron-userland/electron-builder/issues/2551) [#2556](https://github.com/electron-userland/electron-builder/issues/2556)
* do not force build from sources by default ([86be5d7](https://github.com/electron-userland/electron-builder/commit/86be5d7b5c8ef0633895132d80e99a56f333c1c5)), closes [#1703](https://github.com/electron-userland/electron-builder/issues/1703)
* do not include prebuild-install, nan into production build ([98dd77a](https://github.com/electron-userland/electron-builder/commit/98dd77a20872c0fced31d76d39423cc84a3f13df))
* do not override HOME env on reinstall deps, use devdir for nodegyp ([ae0f668](https://github.com/electron-userland/electron-builder/commit/ae0f66806c8f12f1d96a2417393a563d454254cd))
* do not require "author" ([e700b78](https://github.com/electron-userland/electron-builder/commit/e700b78a50ac17b2c791ba768c65921821499a90))
* docker with node 8 ([df1feb5](https://github.com/electron-userland/electron-builder/commit/df1feb51bc62ab47a97c17d45d9648aba5ee0eee))
* **docker:** Install chrome & xvfb to allow for e2e testing ([43add64](https://github.com/electron-userland/electron-builder/commit/43add64ebf0943287858301b334dac8b28aee770))
* **docker:** node v11 support for Docker images ([a47dbbb](https://github.com/electron-userland/electron-builder/commit/a47dbbbf7310ca2ef6d67472af688a86ea43e701))
* **docker:** smaller docker images ([d229335](https://github.com/electron-userland/electron-builder/commit/d229335f70595c74a08dc2c099b9c034489ae45f))
* **docker:** update nodejs to 14.17.0 ([#5900](https://github.com/electron-userland/electron-builder/issues/5900)) ([f53fa7f](https://github.com/electron-userland/electron-builder/commit/f53fa7fc2f3ead90a5fb075e5087bd7ea78a297f))
* **docker:** update to Ubuntu 20.04 LTS ([#5855](https://github.com/electron-userland/electron-builder/issues/5855)) ([ca81c65](https://github.com/electron-userland/electron-builder/commit/ca81c6502e8def93e2178d34b767647a445819cc))
* **docker:** upgrade to zesty ([da1734e](https://github.com/electron-userland/electron-builder/commit/da1734e445931263c0fc4e668950c225115822e6))
* **dog:** License btns config ([#2089](https://github.com/electron-userland/electron-builder/issues/2089)) ([1e38221](https://github.com/electron-userland/electron-builder/commit/1e38221a18ab0281f1326cc8b0e14ad9b9728e04))
* Don't build when CI run is a pull request ([e1dda14](https://github.com/electron-userland/electron-builder/commit/e1dda14822071d5b04e82bc58ba33b088b96fbe1)), closes [#1354](https://github.com/electron-userland/electron-builder/issues/1354)
* **electon-updater:** autoUpdater download-progress event is not called on macOS ([a75bac8](https://github.com/electron-userland/electron-builder/commit/a75bac8691f85ed590d814d36204da2c1910a838)), closes [#1167](https://github.com/electron-userland/electron-builder/issues/1167)
* electron-builder bin executable ([54ac796](https://github.com/electron-userland/electron-builder/commit/54ac796fe0a19f94372b3b6faacc680f8a096b24))
* electron-compile support ([0b9b1fd](https://github.com/electron-userland/electron-builder/commit/0b9b1fdbabffefbfd4d479c49d3d502dc8674060)), closes [#807](https://github.com/electron-userland/electron-builder/issues/807)
* electron-forge support ([d99a27e](https://github.com/electron-userland/electron-builder/commit/d99a27e13649233c3dd43206142dcbf0b5853aac))
* **electron-publisher:** Allow pass configuration to custom electron-publisher provider ([6570e4b](https://github.com/electron-userland/electron-builder/commit/6570e4b0d2f6d33648a4b25c69467cb4327248ec)), closes [#3261](https://github.com/electron-userland/electron-builder/issues/3261)
* **electron-updated, nsis:** cache downloaded update and reuse if valid later ([ba4809a](https://github.com/electron-userland/electron-builder/commit/ba4809aeb3bd3b27f66ee684c3e6e8ab0cf55186))
* **electron-updater:** abort download ([91613a9](https://github.com/electron-userland/electron-builder/commit/91613a9648a3c7175a30cafc409c77324258a635)), closes [#1150](https://github.com/electron-userland/electron-builder/issues/1150)
* **electron-updater:** add error codes ([2822049](https://github.com/electron-userland/electron-builder/commit/28220494ff60ba1ebe82505e6f87c4d90c835dea)), closes [#2415](https://github.com/electron-userland/electron-builder/issues/2415)
* **electron-updater:** add proxy authentication support to electron-updater ([a892a5b](https://github.com/electron-userland/electron-builder/commit/a892a5b85139a5c9a3662ae07f891c74a5cf3bd2)), closes [#1530](https://github.com/electron-userland/electron-builder/issues/1530)
* **electron-updater:** add releaseNotes and releaseName to autoUpdate ([45c93bf](https://github.com/electron-userland/electron-builder/commit/45c93bfc9051c04814be7508a68601dda0e31fc6)), closes [#1174](https://github.com/electron-userland/electron-builder/issues/1174)
* **electron-updater:** add requestHeaders option ([dd1320d](https://github.com/electron-userland/electron-builder/commit/dd1320d631006b7a6e7d677941c21877226ce086)), closes [#1175](https://github.com/electron-userland/electron-builder/issues/1175)
* **electron-updater:** allow absolute path ([53b3581](https://github.com/electron-userland/electron-builder/commit/53b3581d7609d932ec5590540fa62e4b49feb978)), closes [#1678](https://github.com/electron-userland/electron-builder/issues/1678)
* **electron-updater:** allow custom update providers ([#5984](https://github.com/electron-userland/electron-builder/issues/5984)) ([86a538b](https://github.com/electron-userland/electron-builder/commit/86a538b9b8bed87628772174c66e40aa7dcb4a99)), closes [#3656](https://github.com/electron-userland/electron-builder/issues/3656)
* **electron-updater:** Allow to more friendly set autoUpdater.channel ([9c6843f](https://github.com/electron-userland/electron-builder/commit/9c6843f5e41e916be1c05f18da90e72916614491)), closes [#2172](https://github.com/electron-userland/electron-builder/issues/2172)
* **electron-updater:** cannot use updater without administrator privileges ([7c2973d](https://github.com/electron-userland/electron-builder/commit/7c2973dda46434827fc43a1c330bbf9da3923053)), closes [#1133](https://github.com/electron-userland/electron-builder/issues/1133)
* **electron-updater:** checkForUpdatesAndNotify — do nothing if no APPIMAGE env ([247c18a](https://github.com/electron-userland/electron-builder/commit/247c18af95d165ebdb6c434f7765493a9ad6b4a7))
* **electron-updater:** decouple Electron API to support Proton and other frameworks ([9422251](https://github.com/electron-userland/electron-builder/commit/9422251ec1535a9fded552940d021eb2ba4ffc4e))
* **electron-updater:** Delta updates for NSIS target ([7dd59fb](https://github.com/electron-userland/electron-builder/commit/7dd59fb0ab2a6094583f2cc980b57e04f8fe0dc6)), closes [#2217](https://github.com/electron-userland/electron-builder/issues/2217) [#3042](https://github.com/electron-userland/electron-builder/issues/3042) [#3000](https://github.com/electron-userland/electron-builder/issues/3000) [#2977](https://github.com/electron-userland/electron-builder/issues/2977)
* **electron-updater:** download update on macOS in the same way as for other OS ([f966f1a](https://github.com/electron-userland/electron-builder/commit/f966f1a22bd7577e493595ac261e4b38ec0ce233)), closes [#3168](https://github.com/electron-userland/electron-builder/issues/3168)
* **electron-updater:** Electron Auto Updater MacOS support ([067d5c7](https://github.com/electron-userland/electron-builder/commit/067d5c7ad8095d6ff1039bf89086d97a593ec819))
* **electron-updater:** electron-updater will update even I don't call quitAndInstall after app quit ([29f1c10](https://github.com/electron-userland/electron-builder/commit/29f1c10761d2b66592a8e01ed3496dfe1efbeb8c)), closes [#2493](https://github.com/electron-userland/electron-builder/issues/2493)
* **electron-updater:** ensure that update only to the application signed with same cert ([66771d3](https://github.com/electron-userland/electron-builder/commit/66771d32e04ba1719cc0f0a81d480ddfdc9f237c)), closes [#1187](https://github.com/electron-userland/electron-builder/issues/1187)
* **electron-updater:** export updaters for configurability ([#4250](https://github.com/electron-userland/electron-builder/issues/4250)) ([9df845e](https://github.com/electron-userland/electron-builder/commit/9df845e30180fc984e7098f3ed3d3b0fa9415558))
* **electron-updater:** expose downloaded file in update-downloaded event ([7cdece3](https://github.com/electron-userland/electron-builder/commit/7cdece32a5f1d86f276a5f3a0cc85c7b30c530a4)), closes [#3070](https://github.com/electron-userland/electron-builder/issues/3070) [#3345](https://github.com/electron-userland/electron-builder/issues/3345)
* **electron-updater:** find installer exe in bintray artifacts not so strict ([9ac818f](https://github.com/electron-userland/electron-builder/commit/9ac818f34105b3f7be87452a8ae13c5904a04b47)), closes [#1305](https://github.com/electron-userland/electron-builder/issues/1305)
* **electron-updater:** follow `autoInstallOnAppQuit = false` on macOS ([#5271](https://github.com/electron-userland/electron-builder/issues/5271)) ([1643d56](https://github.com/electron-userland/electron-builder/commit/1643d569600a197858585e895e3176948d3eec85))
* **electron-updater:** full changelog for all versions from current to latest ([67fe9ff](https://github.com/electron-userland/electron-builder/commit/67fe9ff10db67d7ec66c1149a704e7395064b350))
* **electron-updater:** GitHub: Allow pre-release builds to be auto updated ([f275831](https://github.com/electron-userland/electron-builder/commit/f275831ddda3911ed03eaf1c260e83fe17305d3f)), closes [#1391](https://github.com/electron-userland/electron-builder/issues/1391)
* **electron-updater:** include full GitHub request url in the error message ([a7d2992](https://github.com/electron-userland/electron-builder/commit/a7d2992225e6e1da9ae9adc6f67c9a6dad43de59))
* **electron-updater:** isSilent param of quitAndInstall method [#1545](https://github.com/electron-userland/electron-builder/issues/1545) ([daeefa6](https://github.com/electron-userland/electron-builder/commit/daeefa6e77576c54e17b1d27f04f293e853ea5be))
* **electron-updater:** Linux auto-update ([2a54c69](https://github.com/electron-userland/electron-builder/commit/2a54c6935b1d445e67df881ae5f42584ae450e89)), closes [#1138](https://github.com/electron-userland/electron-builder/issues/1138)
* **electron-updater:** Linux electron-updater — multiple archs support ([fc8fb9e](https://github.com/electron-userland/electron-builder/commit/fc8fb9e13e28207aaacaf438b97b6412865a0333)), closes [#2216](https://github.com/electron-userland/electron-builder/issues/2216)
* **electron-updater:** Location of app-update.yml in the dev mode ([8c73f57](https://github.com/electron-userland/electron-builder/commit/8c73f57f6ac6f9ee98aa7310e6418bf5093b11ed)), closes [#1254](https://github.com/electron-userland/electron-builder/issues/1254)
* **electron-updater:** MacOS delta update ([a6c5bc4](https://github.com/electron-userland/electron-builder/commit/a6c5bc4ad4c9f9894bffe349fd55bd708a6262e8)), closes [#2995](https://github.com/electron-userland/electron-builder/issues/2995) [#3269](https://github.com/electron-userland/electron-builder/issues/3269)
* **electron-updater:** Make it possible to "auto-downgrade" the application on channel change ([a3c4a9e](https://github.com/electron-userland/electron-builder/commit/a3c4a9e6977cf4b08329db5128602ad1c832a3fc)), closes [#1149](https://github.com/electron-userland/electron-builder/issues/1149)
* **electron-updater:** NSIS autoUpdater.setFeedURL throws error ([eb6a453](https://github.com/electron-userland/electron-builder/commit/eb6a4536295a09d9ef2f3f39cd1475886520b40e)), closes [#1105](https://github.com/electron-userland/electron-builder/issues/1105)
* **electron-updater:** Port support for downloads, Protocol support for generic backend ([8d883f1](https://github.com/electron-userland/electron-builder/commit/8d883f131bb96bf552f053196e0ca18e9487e445))
* **electron-updater:** PrivateGitHub provider uses new `redirect` option instead of session ([13091d6](https://github.com/electron-userland/electron-builder/commit/13091d690094034f21326aa39d84065e8e79de1d)), closes [#2342](https://github.com/electron-userland/electron-builder/issues/2342)
* **electron-updater:** staged rollouts ([5bae61e](https://github.com/electron-userland/electron-builder/commit/5bae61e699d2ffc3bac46743b29a6c74ac4db64d)), closes [#1639](https://github.com/electron-userland/electron-builder/issues/1639)
* **electron-updater:** support prereleases in a Github private repository ([59aac66](https://github.com/electron-userland/electron-builder/commit/59aac664a7ea9c595fe3e11c38eb972b29d74bf1)), closes [#3005](https://github.com/electron-userland/electron-builder/issues/3005) [#3037](https://github.com/electron-userland/electron-builder/issues/3037)
* **electron-updater:** use cache dir for electron-updater cache data ([c01b7c0](https://github.com/electron-userland/electron-builder/commit/c01b7c0b55d3466b826ea9cc9a11ad34118801c1)), closes [#3451](https://github.com/electron-userland/electron-builder/issues/3451) [#3467](https://github.com/electron-userland/electron-builder/issues/3467)
* **electron-updater:** useMultipleRangeRequest option to disable using of multiple ranges request ([0dda076](https://github.com/electron-userland/electron-builder/commit/0dda076c8d9a99db8eca14c78aea686cb281016f))
* electron/universal has a new minimatch option 'x64ArchFiles' ([#6913](https://github.com/electron-userland/electron-builder/issues/6913)) ([f3a56ef](https://github.com/electron-userland/electron-builder/commit/f3a56ef6f8132e0a7cc18ec58d1d6103683916dd))
* electronCompile option to disable electron-compile integration ([b4462a2](https://github.com/electron-userland/electron-builder/commit/b4462a293db71af69889646d12ff024156db3923))
* Enable ESM support for hooks by using dynamic `import()` when `package.json` is set to type `module` ([#7936](https://github.com/electron-userland/electron-builder/issues/7936)) ([664a09c](https://github.com/electron-userland/electron-builder/commit/664a09c4471f46a5b88be0b8e26f24b1a0b2bcc1))
* enable having vendor information in `releaseInfo` ([#7373](https://github.com/electron-userland/electron-builder/issues/7373)) ([9700c75](https://github.com/electron-userland/electron-builder/commit/9700c75331e7d8de4efd257d8774b8c2a422538b))
* enabling support for typescript config files (i.e. electron-builder.ts) ([#7180](https://github.com/electron-userland/electron-builder/issues/7180)) ([edb28c0](https://github.com/electron-userland/electron-builder/commit/edb28c093ab251470e9f1579cd58b4f2ed89e21d))
* Enforce a proper application location ([958a7ae](https://github.com/electron-userland/electron-builder/commit/958a7ae2bfe1b86cb7318e12c60bff25d65c9221)), closes [#1301](https://github.com/electron-userland/electron-builder/issues/1301) [#1298](https://github.com/electron-userland/electron-builder/issues/1298)
* exclude *.suo files ([7cfee12](https://github.com/electron-userland/electron-builder/commit/7cfee122a038c108f2c1894a8ce9af66f16fcd3e))
* expand macro for copyright field ([06d1582](https://github.com/electron-userland/electron-builder/commit/06d1582099cfb2e14ad937eb2a9f466f04290823)), closes [#3273](https://github.com/electron-userland/electron-builder/issues/3273)
* export Packager sub-classes from main electron-builder types ([#8153](https://github.com/electron-userland/electron-builder/issues/8153)) ([8e36be1](https://github.com/electron-userland/electron-builder/commit/8e36be113489c1afa6ce5ee6cdda73049bc619a6))
* Extending `linux` executableArgs option to be utilized for Snap target (fixes [#4587](https://github.com/electron-userland/electron-builder/issues/4587)) ([#7198](https://github.com/electron-userland/electron-builder/issues/7198)) ([a2ce9a7](https://github.com/electron-userland/electron-builder/commit/a2ce9a77c04868e9c01ad76b10955499f1f42eb3))
* Feature request: read environment variables from file ([b75c4ad](https://github.com/electron-userland/electron-builder/commit/b75c4ade1cbf365973a93e07cc51cebe85598cf4)), closes [#1898](https://github.com/electron-userland/electron-builder/issues/1898) [#1896](https://github.com/electron-userland/electron-builder/issues/1896)
* file mappings ([55e2f0d](https://github.com/electron-userland/electron-builder/commit/55e2f0dcee6e09980df98dca40fdc1f2fc5586b0)), closes [#1119](https://github.com/electron-userland/electron-builder/issues/1119)
* **forge:** makers for forge should use electron-builder-lib to reduce number of dependencies ([d3aa530](https://github.com/electron-userland/electron-builder/commit/d3aa530397f3021a1ef20adcd71805a34320452b))
* **forge:** support electron-forge 3.0 API ([002a714](https://github.com/electron-userland/electron-builder/commit/002a7149ca71d931e061b42f5520458ac60262f0))
* get rid of graphicsmagick usage ([d91d2d2](https://github.com/electron-userland/electron-builder/commit/d91d2d2de10eaa7ab4fb1a401e307c18dd000944)), closes [#1855](https://github.com/electron-userland/electron-builder/issues/1855)
* GitHub Enterprise support ([7cae06a](https://github.com/electron-userland/electron-builder/commit/7cae06ad9bf2f4798501ad160328e9facb212a32)), closes [#1225](https://github.com/electron-userland/electron-builder/issues/1225)
* grab latest electron version from github if not specified ([a826df2](https://github.com/electron-userland/electron-builder/commit/a826df23eaabe4372e79c1b6dc32b8d18b7c9b15))
* How to set build_number/FileVersion manually ([3ee8a59](https://github.com/electron-userland/electron-builder/commit/3ee8a5988b6e7bfdf977b6dca4c61e9737ad9d97)), closes [#1337](https://github.com/electron-userland/electron-builder/issues/1337)
* icon relative or to build resources, or to project ([3f3419a](https://github.com/electron-userland/electron-builder/commit/3f3419a483bcc43018ddb0c9fdeb38f6abdba84a)), closes [#1276](https://github.com/electron-userland/electron-builder/issues/1276)
* ignore dll/exe files from node_modules if target platform not windows ([945a517](https://github.com/electron-userland/electron-builder/commit/945a517c32f6a9c5bcc2307766fbdd4582413cd7)), closes [#1738](https://github.com/electron-userland/electron-builder/issues/1738)
* install-app-deps.ts subcommand ([5e0a646](https://github.com/electron-userland/electron-builder/commit/5e0a646250def577dccec7eee31d915cccc61814))
* integrating @electron/notarize into mac signing flow ([#7310](https://github.com/electron-userland/electron-builder/issues/7310)) ([00d0dbc](https://github.com/electron-userland/electron-builder/commit/00d0dbc2d74fbac3e9ce7a046427c1e1d9a11301))
* Introducing deb and rpm auto-updates ([#7060](https://github.com/electron-userland/electron-builder/issues/7060)) ([1d13001](https://github.com/electron-userland/electron-builder/commit/1d130012737e77b57c8923fcc0e6ad2cbc5da0e8))
* isDefaultAppIconProvided for Proton and LibUI ([cd68897](https://github.com/electron-userland/electron-builder/commit/cd6889794238f7c219441e3ed62c1280e89cec69))
* linked dirs outside of projects (e.g. linked modules) ([2364a1c](https://github.com/electron-userland/electron-builder/commit/2364a1c1e2502e18df276ed8c526f67c17fde244)), closes [#675](https://github.com/electron-userland/electron-builder/issues/675)
* **linux:** ability to specify custom path to linux icon set ([a2f64bb](https://github.com/electron-userland/electron-builder/commit/a2f64bbe1cc77c042692343c2b90bb0176fdb29a)), closes [#1176](https://github.com/electron-userland/electron-builder/issues/1176)
* **linux:** accept distribution and component Bintray options ([#1885](https://github.com/electron-userland/electron-builder/issues/1885)) ([22b7422](https://github.com/electron-userland/electron-builder/commit/22b7422925592c860041756afb68d218bde12c6e))
* **linux:** add fileAssociation support for fpm target ([c11fa1f](https://github.com/electron-userland/electron-builder/commit/c11fa1f1033aeb7c378856d7db93369282d363f5))
* **linux:** add missing Exec variable for passing URLs as arguments ([4a87e67](https://github.com/electron-userland/electron-builder/commit/4a87e67610a132e4fc50f1f7e5ec54896ad7842f)), closes [#1592](https://github.com/electron-userland/electron-builder/issues/1592)
* **linux:** add music mac to linux category ([#8182](https://github.com/electron-userland/electron-builder/issues/8182)) ([b43490a](https://github.com/electron-userland/electron-builder/commit/b43490a274722aba398594bcf0156d1b3687e0d2))
* **linux:** add slots option for snap builds ([#5047](https://github.com/electron-userland/electron-builder/issues/5047)) ([e87bd28](https://github.com/electron-userland/electron-builder/commit/e87bd281cf27c0f86cb0f2541033b96fcb1bc64d))
* **linux:** assert that linux.icon is a directory ([5352b8c](https://github.com/electron-userland/electron-builder/commit/5352b8cf341fc1dde8273ccdd081f1e5fa5fe391)), closes [#1242](https://github.com/electron-userland/electron-builder/issues/1242)
* **linux:** check required fields before build ([fbc59e8](https://github.com/electron-userland/electron-builder/commit/fbc59e8bacb5ce26b13a320f485bf2303ca86e9c))
* **linux:** compute app category by mac category ([022d542](https://github.com/electron-userland/electron-builder/commit/022d5422f94bc02f45b9c9e5fc9548e720da9aae))
* **linux:** file associations ([18d18f7](https://github.com/electron-userland/electron-builder/commit/18d18f712d6ef15ba3682d0a6917ca9579e72c77)), closes [#1143](https://github.com/electron-userland/electron-builder/issues/1143) [#2872](https://github.com/electron-userland/electron-builder/issues/2872) [#1413](https://github.com/electron-userland/electron-builder/issues/1413) [#2597](https://github.com/electron-userland/electron-builder/issues/2597) [#2732](https://github.com/electron-userland/electron-builder/issues/2732) [#2873](https://github.com/electron-userland/electron-builder/issues/2873)
* **linux:** forbid desktop.Exec ([0f2c25f](https://github.com/electron-userland/electron-builder/commit/0f2c25fab49ac2a9e584ecb9dcadadcb01242e88)), closes [#3418](https://github.com/electron-userland/electron-builder/issues/3418)
* **linux:** map category public.app-category.social-networking to Chat ([9ff96f7](https://github.com/electron-userland/electron-builder/commit/9ff96f796ad337876629efc2d541c470f03a8ba1))
* **linux:** Package name can be specified using packageName option ([#5530](https://github.com/electron-userland/electron-builder/issues/5530)) ([#5588](https://github.com/electron-userland/electron-builder/issues/5588)) ([622aaef](https://github.com/electron-userland/electron-builder/commit/622aaefd1537f0bfdcf15fc6204b3eea97dc64ce))
* **linux:** Set Linux category for `public.app-category.finance` ([c050b52](https://github.com/electron-userland/electron-builder/commit/c050b5206fc86584271644674590c31292d41f14)), closes [#2426](https://github.com/electron-userland/electron-builder/issues/2426)
* **linux:** support any icon name ([5a2631c](https://github.com/electron-userland/electron-builder/commit/5a2631c4614d9d7322e8490c64da311d6986bab0)), closes [#1399](https://github.com/electron-userland/electron-builder/issues/1399)
* **linux:** support to set executableArgs in linux config ([#4364](https://github.com/electron-userland/electron-builder/issues/4364)) ([7cf6894](https://github.com/electron-userland/electron-builder/commit/7cf6894c0be7781e3e714987cdcb2e0b4d939d2d))
* **linux:** use ${macro} syntax for linux templates ([fe137fc](https://github.com/electron-userland/electron-builder/commit/fe137fc221f46683433cc7dc86984caeab281d84))
* **linux:** use icon.png as linux icon ([a900cf8](https://github.com/electron-userland/electron-builder/commit/a900cf8642cbe8f300a604ae58e14ac43cecf0fb)), closes [#2477](https://github.com/electron-userland/electron-builder/issues/2477)
* local path to custom electron build (windows support) ([521aea6](https://github.com/electron-userland/electron-builder/commit/521aea6e87e440d49d19812ea0536223cc040eac)), closes [#1534](https://github.com/electron-userland/electron-builder/issues/1534) [#1342](https://github.com/electron-userland/electron-builder/issues/1342)
* LSTypeIsPackage for file associations ([dcf3dbb](https://github.com/electron-userland/electron-builder/commit/dcf3dbb48979291fb91301610de9e417e0ab7b79)), closes [#995](https://github.com/electron-userland/electron-builder/issues/995)
* **mac:** add loginhelper entitlement option ([#5023](https://github.com/electron-userland/electron-builder/issues/5023)) ([7109e88](https://github.com/electron-userland/electron-builder/commit/7109e88e7fc0200185c23b27944eb340f132a319))
* **mac:** add LSHandlerRank ([5129266](https://github.com/electron-userland/electron-builder/commit/512926648068deaab8d0a2ce8085ab63de999412)), closes [#4614](https://github.com/electron-userland/electron-builder/issues/4614)
* **mac:** add option to disable gatekeeper assessment in electron-osx-sign ([ef0028d](https://github.com/electron-userland/electron-builder/commit/ef0028d331f912a708abb6cd8afe2337794b9040))
* **mac:** Add option to enable hardened-runtime ([7d5f952](https://github.com/electron-userland/electron-builder/commit/7d5f952b12406683fd77a5eaac45e8d6b0b9f257)), closes [#3858](https://github.com/electron-userland/electron-builder/issues/3858)
* **mac:** Add support for a custom 'sign' function in mac/mas config ([#8002](https://github.com/electron-userland/electron-builder/issues/8002)) ([adf97dc](https://github.com/electron-userland/electron-builder/commit/adf97dccd0146288ab482a261b749d67a458868a))
* **mac:** Add timestamp authority server to osx-sign options ([#6074](https://github.com/electron-userland/electron-builder/issues/6074)) ([41cb248](https://github.com/electron-userland/electron-builder/commit/41cb24869381de73a9663a17ec91d2747e099cf9))
* **mac:** allow build for pull requests / code sign artifacts ([9dbc789](https://github.com/electron-userland/electron-builder/commit/9dbc7895b08b39c3a473d7537b8c4e97538bf650)), closes [#1524](https://github.com/electron-userland/electron-builder/issues/1524)
* **mac:** allow passing through binaries and requirements options ([a2e58c0](https://github.com/electron-userland/electron-builder/commit/a2e58c0ad4e9124d28e51df0189e635fb4166a4e)), closes [#1574](https://github.com/electron-userland/electron-builder/issues/1574)
* **mac:** control the localization files ([ab664ac](https://github.com/electron-userland/electron-builder/commit/ab664ac726f5d7df0d8e35db6d14796ce0afabf3)), closes [#708](https://github.com/electron-userland/electron-builder/issues/708)
* **mac:** customize CFBundleShortVersionString ([2029766](https://github.com/electron-userland/electron-builder/commit/20297666316d2714200a16d0307dd23dc4348e9c))
* **mac:** extra dist files ([efb40da](https://github.com/electron-userland/electron-builder/commit/efb40dabc608f9787e6ef9420e0fe71cfa97acf7)), closes [#3148](https://github.com/electron-userland/electron-builder/issues/3148)
* **mac:** generate icns from png of png file set [#1682](https://github.com/electron-userland/electron-builder/issues/1682) ([1586f7f](https://github.com/electron-userland/electron-builder/commit/1586f7f3e59e2e6ca69759b20f60123bea4edbb3))
* **mac:** Ignore Contents/PlugIns ([a4b76b4](https://github.com/electron-userland/electron-builder/commit/a4b76b411e759c2f4d05c893fa993ed836e83fe8)), closes [#1699](https://github.com/electron-userland/electron-builder/issues/1699)
* **mac:** implement signApp function for macPackager ([#3912](https://github.com/electron-userland/electron-builder/issues/3912)) ([99ac3d4](https://github.com/electron-userland/electron-builder/commit/99ac3d47af2ff9a7407763703f4ad228aabc7b32))
* **mac:** mac build zip file name does not follow build.artifactName ([1affc61](https://github.com/electron-userland/electron-builder/commit/1affc618534008ca51a00d476689fe46d8ae2381)), closes [#1398](https://github.com/electron-userland/electron-builder/issues/1398)
* **mac:** Non-default keychain for signing on OSX ([88a70a3](https://github.com/electron-userland/electron-builder/commit/88a70a3a301cca2a546b917907107ef5ee377ad2)), closes [#2209](https://github.com/electron-userland/electron-builder/issues/2209)
* **mac:** option to set minimum macOS version the app is supported on ([14fbed1](https://github.com/electron-userland/electron-builder/commit/14fbed1491654dce260509910134bb3c316d3334)), closes [#2472](https://github.com/electron-userland/electron-builder/issues/2472)
* macOS default architecture ([#5495](https://github.com/electron-userland/electron-builder/issues/5495)) ([#5504](https://github.com/electron-userland/electron-builder/issues/5504)) ([5203d7e](https://github.com/electron-userland/electron-builder/commit/5203d7eb15726605e8987aeed7a5ccedc8152e04))
* **mac:** pass the provisioning profile path to electron-osx-sign ([2a707cc](https://github.com/electron-userland/electron-builder/commit/2a707cca01ad9bf6439450eca22c4f0e0204198d)), closes [#2166](https://github.com/electron-userland/electron-builder/issues/2166) [#2782](https://github.com/electron-userland/electron-builder/issues/2782)
* **mac:** resize icons for Linux using sips on macOS to avoid graphicsmagick dependency ([e5817bc](https://github.com/electron-userland/electron-builder/commit/e5817bc51726185a605d13c772c52dbd48aa451e))
* **mac:** set hardenedRuntime to true by default, set gatekeeper-assess by default to false ([c8c37f2](https://github.com/electron-userland/electron-builder/commit/c8c37f20c624e5d73298d6bfa02660bb03ccbcea)), closes [#3383](https://github.com/electron-userland/electron-builder/issues/3383)
* **mac:** supplying a value for the ‘ignore’ electron-osx-sign property ([aa3625d](https://github.com/electron-userland/electron-builder/commit/aa3625d5f6b719b6a7634c4c7ba0aad1ffe7d3d6)), closes [#5262](https://github.com/electron-userland/electron-builder/issues/5262)
* **mac:** Support macOS Mojave Dark Mode ([e85ef88](https://github.com/electron-userland/electron-builder/commit/e85ef881de122bc5c599e07673696e1e029b17ba)), closes [#3496](https://github.com/electron-userland/electron-builder/issues/3496)
* **mac:** support macos signature `additionalArguments` parameter  ([#8218](https://github.com/electron-userland/electron-builder/issues/8218)) ([22737b2](https://github.com/electron-userland/electron-builder/commit/22737b2b2db5a10785b1ed3fd05fd9d237fcd731))
* **mac:** The extra entries for `Info.plist` ([1a33a34](https://github.com/electron-userland/electron-builder/commit/1a33a3453f5c53f23fddaa453e79300ee4f30fdf))
* **mac:** upgrade osslsigncode, do not require wine ([ed662e8](https://github.com/electron-userland/electron-builder/commit/ed662e8adbfd046cccb87cf93c177c8fd3d74d9f)), closes [#1713](https://github.com/electron-userland/electron-builder/issues/1713) [#1707](https://github.com/electron-userland/electron-builder/issues/1707)
* make `--no-sandbox` optional for building with AppImage ([#6429](https://github.com/electron-userland/electron-builder/issues/6429)) ([e95afc1](https://github.com/electron-userland/electron-builder/commit/e95afc1ab8c1a09fc8c9496084fc9f49b185469e))
* make description optional (just a warning) ([ae036c6](https://github.com/electron-userland/electron-builder/commit/ae036c6ff2c7db2b1127748b47d8fddd1afda248))
* Make electron-builder compatible with electron-nightly. ([#4473](https://github.com/electron-userland/electron-builder/issues/4473)) ([35bff8c](https://github.com/electron-userland/electron-builder/commit/35bff8cb87ba5d92687853604b751cfb7abc77bc)), closes [#1](https://github.com/electron-userland/electron-builder/issues/1)
* make it possible to ignore release time when publish to github ([#5179](https://github.com/electron-userland/electron-builder/issues/5179)) ([fca50ae](https://github.com/electron-userland/electron-builder/commit/fca50aea42fc054b87bbe943bbe5c1c235a186e1))
* Make notarization with Apple ID more usable (`altool` is no longer supported) ([#8159](https://github.com/electron-userland/electron-builder/issues/8159)) ([15bffa0](https://github.com/electron-userland/electron-builder/commit/15bffa00d429d9f333b737712fb3a13f5d26ea53))
* **mas:** Apple Silicon support ([#5484](https://github.com/electron-userland/electron-builder/issues/5484)) ([6b7d305](https://github.com/electron-userland/electron-builder/commit/6b7d30555d8f88a3a908a25adb3e8836ccdf5bc8))
* more clear logging using Apex-inspired logger ([fd70412](https://github.com/electron-userland/electron-builder/commit/fd7041259a9df043761306e152835fbf348bbca2))
* Moved `electronLanguages` to global config to support win/linux ([#7516](https://github.com/electron-userland/electron-builder/issues/7516)) ([1533501](https://github.com/electron-userland/electron-builder/commit/1533501f999b364b656cdaa2048a1a7fd5e7c361))
* **msi:** build emulated arm64 MSI installers ([#8086](https://github.com/electron-userland/electron-builder/issues/8086)) ([e6f1beb](https://github.com/electron-userland/electron-builder/commit/e6f1bebd96cbc54f7455cd9bd48bb1eadc5648f5)), closes [#6077](https://github.com/electron-userland/electron-builder/issues/6077)
* **msi:** make MSI per-user by default ([da82097](https://github.com/electron-userland/electron-builder/commit/da820977047e59a958c4b1c9adaa733d25d51425))
* **msi:** per-machine one-click MSI installer ([2d803bb](https://github.com/electron-userland/electron-builder/commit/2d803bbbab1244ac34a8e8011d8179b5c46902b9)), closes [#2093](https://github.com/electron-userland/electron-builder/issues/2093) [#723](https://github.com/electron-userland/electron-builder/issues/723)
* **msi:** per-user one-click MSI installer ([9770851](https://github.com/electron-userland/electron-builder/commit/9770851c1a8c1d543bbe20d8b80d9867b28fe099))
* **msi:** support for menuCategory sub-directory in programFilesDir ([5308531](https://github.com/electron-userland/electron-builder/commit/53085311d4d4f3863a3c731e7a4f2958e31b297a))
* Multi language support for LICENCES ([bbdc29a](https://github.com/electron-userland/electron-builder/commit/bbdc29a5390917b1c8140ab1274e1ed15e42a665))
* muon support ([4f555da](https://github.com/electron-userland/electron-builder/commit/4f555da2e2fe4d17d35fcf692abf939e965fe06b)), closes [#1394](https://github.com/electron-userland/electron-builder/issues/1394)
* **muon:** Rebuilding the native dependencies for muon ([3232f65](https://github.com/electron-userland/electron-builder/commit/3232f657daf0f9823a895c58dfa6779b72b822d8)), closes [#1404](https://github.com/electron-userland/electron-builder/issues/1404)
* **nsins:** create pre initialization hook in installer.nsi ([#1255](https://github.com/electron-userland/electron-builder/issues/1255)) ([7ed9d7a](https://github.com/electron-userland/electron-builder/commit/7ed9d7ad8b88e1d21150a7dd9d6eb2d28679f3f9))
* nsis install method - exposed as public to avoid quit the app for the install ([#7533](https://github.com/electron-userland/electron-builder/issues/7533)) ([4786d41](https://github.com/electron-userland/electron-builder/commit/4786d41575c638137c7016c905d089ab74bf5e28))
* NSIS template translation lang code with region ([7755fa4](https://github.com/electron-userland/electron-builder/commit/7755fa4bae2eb5b1b7d3665caa2a1db9320d45c3)), closes [#1904](https://github.com/electron-userland/electron-builder/issues/1904)
* NSIS uninstaller reader ([#4305](https://github.com/electron-userland/electron-builder/issues/4305)) ([#4355](https://github.com/electron-userland/electron-builder/issues/4355)) ([6443179](https://github.com/electron-userland/electron-builder/commit/64431790c1f0483a5094ce962efd3b4bffaab2ec))
* NSIS uninstaller uncompressed support ([#4305](https://github.com/electron-userland/electron-builder/issues/4305)) ([#4415](https://github.com/electron-userland/electron-builder/issues/4415)) ([eb32b22](https://github.com/electron-userland/electron-builder/commit/eb32b227e659eba62c308bf28ff59803d2c434d8))
* NSIS Updater API to Start Downloading ([eff85c3](https://github.com/electron-userland/electron-builder/commit/eff85c38e99a7e11c47c1e40464258dfcae069bd)), closes [#972](https://github.com/electron-userland/electron-builder/issues/972)
* **nsis:** ability to recreate desktop shortcut on fresh install ([432b3e9](https://github.com/electron-userland/electron-builder/commit/432b3e9d31860f1fca9242d2b7510454f5f2f90a)), closes [#2725](https://github.com/electron-userland/electron-builder/issues/2725)
* **nsis:** add --no-desktop-shortcut argument ([#1432](https://github.com/electron-userland/electron-builder/issues/1432)) ([e1e3832](https://github.com/electron-userland/electron-builder/commit/e1e3832ef9d34ec8e18548d73b42f40035c4466f))
* **nsis:** add APP_EXECUTABLE_DIR ([8e957c8](https://github.com/electron-userland/electron-builder/commit/8e957c8a2e1aa4b6b12adc11939f66b8252eb2d1)), closes [#1612](https://github.com/electron-userland/electron-builder/issues/1612)
* **nsis:** add cutomWelcomePage macro ([#2384](https://github.com/electron-userland/electron-builder/issues/2384)) ([1ec4ba2](https://github.com/electron-userland/electron-builder/commit/1ec4ba287664a54faa5d6d03aeafefeed9a204f3)), closes [#1501](https://github.com/electron-userland/electron-builder/issues/1501)
* **nsis:** add de, it, fr, hu, pl translations for one-click installer ([d8aa078](https://github.com/electron-userland/electron-builder/commit/d8aa0783bc8f877c65b8fc7da92c601e07a67eb9))
* **nsis:** Add flag to force start on silent install ([f24c389](https://github.com/electron-userland/electron-builder/commit/f24c3895ace9585fc591ed1686a44e41841b0f53)), closes [#1545](https://github.com/electron-userland/electron-builder/issues/1545) [#1712](https://github.com/electron-userland/electron-builder/issues/1712)
* **nsis:** add ja translation for one-click installer ([#1543](https://github.com/electron-userland/electron-builder/issues/1543)) ([90d0da1](https://github.com/electron-userland/electron-builder/commit/90d0da116734a989855e88a0b3c9ad8f980d46f1))
* **nsis:** add japanese language ([#3304](https://github.com/electron-userland/electron-builder/issues/3304)) ([ba035ea](https://github.com/electron-userland/electron-builder/commit/ba035ea35151b55bd7d1b3997bc6a22de8c083dc))
* **nsis:** add korean messages for one-click installer ([#1556](https://github.com/electron-userland/electron-builder/issues/1556)) ([9fce636](https://github.com/electron-userland/electron-builder/commit/9fce636d813113d32f9b9c41cc66d5b83ff2b909))
* **nsis:** add languages sv_SE, no, da, fi, es, nl_NL and complete ru, it, pl, hu, fr ([#3411](https://github.com/electron-userland/electron-builder/issues/3411)) ([e101832](https://github.com/electron-userland/electron-builder/commit/e1018324a0bb02c0979e68dac21f0e8cdce718a5))
* **nsis:** add new interface to show custom page after change installation directory and before install start, like other running options. ([#4219](https://github.com/electron-userland/electron-builder/issues/4219)) ([a9a4c53](https://github.com/electron-userland/electron-builder/commit/a9a4c53d3182bc0e2a504331429976afe778a3d0))
* **nsis:** add NsisOption to specify selectPerMachineByDefault ([#7967](https://github.com/electron-userland/electron-builder/issues/7967)) ([28e5b5d](https://github.com/electron-userland/electron-builder/commit/28e5b5ddb6bb2d77ef6847fc0c93e62c97174156))
* **nsis:** Add option to define custom files to be removed instead of just nuking installation directory ([09f7fde](https://github.com/electron-userland/electron-builder/commit/09f7fdee776b02e19a77330c755d66af17cd52b3)), closes [#1298](https://github.com/electron-userland/electron-builder/issues/1298) [#1300](https://github.com/electron-userland/electron-builder/issues/1300)
* **nsis:** add option to disable differential download ([#7950](https://github.com/electron-userland/electron-builder/issues/7950)) ([03c9451](https://github.com/electron-userland/electron-builder/commit/03c94516ef3b1b31b2f5b7bcdb9c6d3753d36b8d))
* **nsis:** add possibility to force an install mode  programmatically ([ab244b4](https://github.com/electron-userland/electron-builder/commit/ab244b4c810bfa2d4217bb33d64337dad9c92531))
* **nsis:** add ShutdownBlockReasonCreate for blocking Win Shutdown prompt ([#7251](https://github.com/electron-userland/electron-builder/issues/7251)) ([45a0f82](https://github.com/electron-userland/electron-builder/commit/45a0f82ac3a14fedfb03880fb43d525a51cec864))
* **nsis:** allow submenu in start menu in programfiles ([e3faaf1](https://github.com/electron-userland/electron-builder/commit/e3faaf1d50e985edcd030b95a70fcfcd108580f4)), closes [#1063](https://github.com/electron-userland/electron-builder/issues/1063)
* **nsis:** always add plugin dir to override nsis plugins ([e8d1d0d](https://github.com/electron-userland/electron-builder/commit/e8d1d0d508c7fc099f6ad700e5e35c5b40b3ad7d))
* **nsis:** app requestedExecutionLevel ([ad3a2df](https://github.com/electron-userland/electron-builder/commit/ad3a2dfba7d357f9284d25f08b9d44682f77d18d)), closes [#1932](https://github.com/electron-userland/electron-builder/issues/1932)
* **nsis:** Arabic translation (only core nsis) ([d92ae2e](https://github.com/electron-userland/electron-builder/commit/d92ae2e62270786678481d0cf0dfd33562ad7dfa))
* **nsis:** artifact file name pattern ([3d39fa6](https://github.com/electron-userland/electron-builder/commit/3d39fa6cde4664353b2eeecbbc2033e24c16d988)), closes [#1221](https://github.com/electron-userland/electron-builder/issues/1221) [#1219](https://github.com/electron-userland/electron-builder/issues/1219)
* **nsis:** brazilian portuguese language ([#2095](https://github.com/electron-userland/electron-builder/issues/2095)) ([f7fee7d](https://github.com/electron-userland/electron-builder/commit/f7fee7d86d069bdac99ca0eed4a34a7fd1597445))
* **nsis:** bundle brazilian portuguese language ([c68abc3](https://github.com/electron-userland/electron-builder/commit/c68abc3dd5d6bf17f4c347c6626896872347681f))
* **nsis:** Change installation directory when not using 'oneClick' with NSIS ([06b0103](https://github.com/electron-userland/electron-builder/commit/06b0103969111d990e1bab6b1d5066ea00dc96c9)), closes [#596](https://github.com/electron-userland/electron-builder/issues/596)
* **nsis:** compute EstimatedSize on build time to reduce installation time ([b8f93d1](https://github.com/electron-userland/electron-builder/commit/b8f93d17132d82a0e8c282a34076d3acea0c626d))
* **nsis:** custom uninstall application icon ([e4e5cc7](https://github.com/electron-userland/electron-builder/commit/e4e5cc7ab511eac3472e11699b8ed63dca709290)), closes [#1585](https://github.com/electron-userland/electron-builder/issues/1585)
* **nsis:** custom uninstall application icon ([eb181b9](https://github.com/electron-userland/electron-builder/commit/eb181b93401381def679d92f1a4788d53f69e23e)), closes [#1550](https://github.com/electron-userland/electron-builder/issues/1550)
* **nsis:** custom uninstaller display name in the control panel ([fda6ee9](https://github.com/electron-userland/electron-builder/commit/fda6ee91fbd0cfdec8a70d13c362bb953c1dd1e7))
* **nsis:** czech language for nsis scripts ([#5270](https://github.com/electron-userland/electron-builder/issues/5270)) ([16c81a0](https://github.com/electron-userland/electron-builder/commit/16c81a098b90def5f302618d8207c123c2a88dbb))
* **nsis:** Define custom shortcuts name, Remove runAfterFinish dependency on shortcuts ([fd7898c](https://github.com/electron-userland/electron-builder/commit/fd7898c4d68f5d3376c17e94622cb8df090e915b)), closes [#1827](https://github.com/electron-userland/electron-builder/issues/1827) [#1917](https://github.com/electron-userland/electron-builder/issues/1917) [#1767](https://github.com/electron-userland/electron-builder/issues/1767)
* **nsis:** Delta updates for NSIS ([f6fe96f](https://github.com/electron-userland/electron-builder/commit/f6fe96ff08e9f2d57e645c5c6e89d0d628530f9a)), closes [#1523](https://github.com/electron-userland/electron-builder/issues/1523)
* **nsis:** disable 7-zip compression for specific static assets ([e77769a](https://github.com/electron-userland/electron-builder/commit/e77769a4627a7aae65284dbeea5ac0ea83bddd21)), closes [#2628](https://github.com/electron-userland/electron-builder/issues/2628)
* **nsis:** display "Space Required" text for NSIS installer ([#7531](https://github.com/electron-userland/electron-builder/issues/7531)) ([0db9c66](https://github.com/electron-userland/electron-builder/commit/0db9c66f0fff9a482d34aeaafaf11f542b786bf8))
* **nsis:** do not prompt user to close app before installing on update ([e5682a0](https://github.com/electron-userland/electron-builder/commit/e5682a0a9e005f6b29177c32263793014169b7b6)), closes [#1368](https://github.com/electron-userland/electron-builder/issues/1368)
* **nsis:** enable custom check if app is running ([de36d5e](https://github.com/electron-userland/electron-builder/commit/de36d5e3ff45c885cd58c43365e3adfc9784ec87))
* **nsis:** env ELECTRON_BUILDER_NSIS_DIR to customize NSIS binaries location ([48d7280](https://github.com/electron-userland/electron-builder/commit/48d7280ab96787299a24e0304bc2b3747f4ee88d)), closes [#3054](https://github.com/electron-userland/electron-builder/issues/3054)
* **nsis:** Feature/do not ignore uninstall errors ([#3782](https://github.com/electron-userland/electron-builder/issues/3782)) ([c84ecff](https://github.com/electron-userland/electron-builder/commit/c84ecff171dac128a1d5552a1287a375dc57df07))
* **nsis:** finnish nsis lang ([c88d991](https://github.com/electron-userland/electron-builder/commit/c88d99193f72361215defbeb33119a7340536034))
* **nsis:** German translation ([dcfac87](https://github.com/electron-userland/electron-builder/commit/dcfac878b5a864b6f619559e2c084f38b25f42d3))
* **nsis:** html support for one-language licenses ([b635674](https://github.com/electron-userland/electron-builder/commit/b6356749ba95470f05b5831317ac6579660035ea))
* **nsis:** implement file associations per user ([4adfbdd](https://github.com/electron-userland/electron-builder/commit/4adfbddd20013240cdea9c30d617a6734cb54c02)), closes [#2861](https://github.com/electron-userland/electron-builder/issues/2861) [#2860](https://github.com/electron-userland/electron-builder/issues/2860)
* **nsis:** ko lang ([89a5233](https://github.com/electron-userland/electron-builder/commit/89a52332985b19fef72b8ca0db18a2a49c45d386)), closes [#1504](https://github.com/electron-userland/electron-builder/issues/1504)
* **nsis:** metro sidebar, customizable sidebar ([969c0eb](https://github.com/electron-userland/electron-builder/commit/969c0ebc7dcb16980bd9781ae01c7dcfee147657)), closes [#1248](https://github.com/electron-userland/electron-builder/issues/1248)
* **nsis:** multi-lang one-click installer (including custom string) ([f01415a](https://github.com/electron-userland/electron-builder/commit/f01415a31e1ed4a5c9f840a43dce6f25277d7d32))
* **nsis:** multiUserUi.nsh — i18n ([5169b8b](https://github.com/electron-userland/electron-builder/commit/5169b8b85490819722234366f63108bec8da4b85)), closes [#1753](https://github.com/electron-userland/electron-builder/issues/1753)
* **nsis:** NSIS - nested start menu folders ([fafc7ba](https://github.com/electron-userland/electron-builder/commit/fafc7baeda9c19795ae46420028a8e2d16dda03a)), closes [#1538](https://github.com/electron-userland/electron-builder/issues/1538)
* **nsis:** NSIS Special Builds set NSIS_MAX_STRLEN flag ([498db5d](https://github.com/electron-userland/electron-builder/commit/498db5dc61bd5a7431815764fa6524db9b9f3246)), closes [#1267](https://github.com/electron-userland/electron-builder/issues/1267)
* **nsis:** Nsis turkish template updated ([#2718](https://github.com/electron-userland/electron-builder/issues/2718)) ([0900a01](https://github.com/electron-userland/electron-builder/commit/0900a0156b72f279f99221914b9bde1b16ca2c8c))
* **nsis:** NSIS Web Installer ([7041b5d](https://github.com/electron-userland/electron-builder/commit/7041b5d3e2b17983973d5cea41215b5c371609d7)), closes [#1207](https://github.com/electron-userland/electron-builder/issues/1207)
* **nsis:** option to delete app data on manual uninstall ([2e1b21e](https://github.com/electron-userland/electron-builder/commit/2e1b21e088e975d6209dc947dafcc040aae1eb0d)), closes [#885](https://github.com/electron-userland/electron-builder/issues/885)
* **nsis:** option to not create desktop shortcut ([350e241](https://github.com/electron-userland/electron-builder/commit/350e24106aba4882bb63e184ce9a964092728b79)), closes [#1597](https://github.com/electron-userland/electron-builder/issues/1597)
* **nsis:** Option to not pack "elevate.exe" ([69c3614](https://github.com/electron-userland/electron-builder/commit/69c3614eba276d8b194118a7ae632b9d5139ee86)), closes [#1620](https://github.com/electron-userland/electron-builder/issues/1620) [#1621](https://github.com/electron-userland/electron-builder/issues/1621)
* **nsis:** Pass --update flag to uninstaller when auto updating an application ([505a63d](https://github.com/electron-userland/electron-builder/commit/505a63d742f9f695cf2bce0198f2d96cd1114cff)), closes [#1162](https://github.com/electron-userland/electron-builder/issues/1162)
* **nsis:** provide Simplified Chinese version of messages during installation ([#2506](https://github.com/electron-userland/electron-builder/issues/2506)) ([fd996b5](https://github.com/electron-userland/electron-builder/commit/fd996b5577ac8d98e19c9a0bde808bc6e90e012e)), closes [#2486](https://github.com/electron-userland/electron-builder/issues/2486)
* **nsis:** remove "runAfterFinish" checkbox ([439ea2c](https://github.com/electron-userland/electron-builder/commit/439ea2c3fafd3a212c9a5abbbd6b0b641adad2b9)), closes [#2811](https://github.com/electron-userland/electron-builder/issues/2811)
* **nsis:** Show welcome and finish page duing uninstall ([#1173](https://github.com/electron-userland/electron-builder/issues/1173)) ([aa43344](https://github.com/electron-userland/electron-builder/commit/aa433443b1cca004e7b46f7ea40885623ea6a0e2))
* **nsis:** Slovak(sk) translation ([09495f9](https://github.com/electron-userland/electron-builder/commit/09495f9ddb4fcb59a654e64ceffbe2db90b40182))
* **nsis:** Slovak(sk) translation for boring installer ([63f019f](https://github.com/electron-userland/electron-builder/commit/63f019f3be4ce58e3c0e490e1d3e875cee3f0391)), closes [#1617](https://github.com/electron-userland/electron-builder/issues/1617)
* **nsis:** support Thai language ([bba7a15](https://github.com/electron-userland/electron-builder/commit/bba7a1505a3324b07e52e7394442ac1befb15456)), closes [#2515](https://github.com/electron-userland/electron-builder/issues/2515)
* **nsis:** traditional Chinese version of messages during installation ([#4571](https://github.com/electron-userland/electron-builder/issues/4571)) ([bc68444](https://github.com/electron-userland/electron-builder/commit/bc68444e1dd9a1a4d905a659ee9f9980713201e3))
* **nsis:** Turkish updated ([#2729](https://github.com/electron-userland/electron-builder/issues/2729)) ([f339278](https://github.com/electron-userland/electron-builder/commit/f339278d6c27cc33b68d71f9debc64f2272347a9))
* **nsis:** unicode option High Windows defender CPU usage when accessing NSIS installer ([0e9059c](https://github.com/electron-userland/electron-builder/commit/0e9059c4db04dd169d6f591530567976c3fbed57)), closes [#1165](https://github.com/electron-userland/electron-builder/issues/1165)
* **nsis:** update to 3.0.5 ([071cf47](https://github.com/electron-userland/electron-builder/commit/071cf47da102f32a106c34bf236bbb704515990f))
* **nsis:** use productName rather than name for install path if matches /^[-_0-9a-zA-Z ]+$/ ([2539cfb](https://github.com/electron-userland/electron-builder/commit/2539cfba20dc639128e75c5b786651b652bb4b78)), closes [#1100](https://github.com/electron-userland/electron-builder/issues/1100) [#767](https://github.com/electron-userland/electron-builder/issues/767) [#1104](https://github.com/electron-userland/electron-builder/issues/1104)
* **nsis:** vi langs ([78a0425](https://github.com/electron-userland/electron-builder/commit/78a0425458d4fc00526d0a0d9207dcb2af2e830e)), closes [#2983](https://github.com/electron-userland/electron-builder/issues/2983)
* **nsis:** Web Installer detects local package file in the same directory where installer located ([45e13f9](https://github.com/electron-userland/electron-builder/commit/45e13f93c5f82ac44fe3ca8fe6ce539e7ebb5c7d))
* **nsis:** Windows on ARM support ([#4228](https://github.com/electron-userland/electron-builder/issues/4228)) ([d738644](https://github.com/electron-userland/electron-builder/commit/d738644d6e55b027c81e9b7cdd27dc5af9189b0a))
* on macOS and windows build x64 snap and appimage regardless of machine arch ([72dd264](https://github.com/electron-userland/electron-builder/commit/72dd264b4e545070b88affcc7653a6546b562869))
* onNodeModuleFile ([6b2d3dc](https://github.com/electron-userland/electron-builder/commit/6b2d3dccca8330be54b4e3f794ea97f587b10ecf))
* option `removePackageScripts` ([d6455d1](https://github.com/electron-userland/electron-builder/commit/d6455d137066e7b6e9c651aa889265258384172b)), closes [#2461](https://github.com/electron-userland/electron-builder/issues/2461)
* per platform appId ([4d96956](https://github.com/electron-userland/electron-builder/commit/4d969569e74c8e1c67c7ff2c320949fc44ef0001))
* **pkg:** add more pkg configuration options ([#3449](https://github.com/electron-userland/electron-builder/issues/3449)) ([b6d4dcd](https://github.com/electron-userland/electron-builder/commit/b6d4dcd3662d9b13342cae9d7e34986d8f1f68c9))
* **pkg:** build pkg that doesn't require admin install ([a3a23f2](https://github.com/electron-userland/electron-builder/commit/a3a23f2f7f6c410ce7d052537e4262e1b0bc1790))
* **pkg:** customize macOS PKG component plist ([3415445](https://github.com/electron-userland/electron-builder/commit/3415445a4bc0223a87650608b7a2cf465902fc83)), closes [#1838](https://github.com/electron-userland/electron-builder/issues/1838) [#2991](https://github.com/electron-userland/electron-builder/issues/2991)
* **pkg:** pkg license ([a0cb477](https://github.com/electron-userland/electron-builder/commit/a0cb477ecea34fdd70f0b8113b57ad0650b5e794)), closes [#1547](https://github.com/electron-userland/electron-builder/issues/1547) [#2212](https://github.com/electron-userland/electron-builder/issues/2212)
* **pkg:** preinstall and postinstall scripts ([2eb1298](https://github.com/electron-userland/electron-builder/commit/2eb12987ce1842a8291595ea9cdcf4db3e8fe298)), closes [#1166](https://github.com/electron-userland/electron-builder/issues/1166)
* **portable:** `unpackDirName` option for portable ([4ee4be6](https://github.com/electron-userland/electron-builder/commit/4ee4be63159472d621abc30d5fbe017d7a88981a)), closes [#3799](https://github.com/electron-userland/electron-builder/issues/3799)
* **portable:** add `PORTABLE_EXECUTABLE_APP_FILENAME` env ([8d966f8](https://github.com/electron-userland/electron-builder/commit/8d966f8239ab240fc22aa173bab33bfdd095492e)), closes [#3186](https://github.com/electron-userland/electron-builder/issues/3186)
* **portable:** adding splash image to portable nsis package ([91e6183](https://github.com/electron-userland/electron-builder/commit/91e6183bfd27191083872bcf07a0db51f9470e1e)), closes [#4425](https://github.com/electron-userland/electron-builder/issues/4425)
* **portable:** Adding support for unique dir on each portable app launch ([#6093](https://github.com/electron-userland/electron-builder/issues/6093)) ([f8e16db](https://github.com/electron-userland/electron-builder/commit/f8e16db5393f663724e9c03ceab87698a252c934)), closes [#5764](https://github.com/electron-userland/electron-builder/issues/5764) [#5382](https://github.com/electron-userland/electron-builder/issues/5382) [#4105](https://github.com/electron-userland/electron-builder/issues/4105)
* **portable:** constant unpack path across all launches of the same executable ([3be0181](https://github.com/electron-userland/electron-builder/commit/3be0181514b88f16386aab1b7645d7e89d493147)), closes [#3799](https://github.com/electron-userland/electron-builder/issues/3799)
* **portable:** ExecutionLevel for nsis portable ([3f8caab](https://github.com/electron-userland/electron-builder/commit/3f8caab0cd7e403c4124882a53da1a7929399a98)), closes [#1440](https://github.com/electron-userland/electron-builder/issues/1440)
* **portable:** expose `$EXEPATH` as `PORTABLE_EXECUTABLE_FILE` env ([dfa9f7d](https://github.com/electron-userland/electron-builder/commit/dfa9f7d36ee3b5bb8de56607cb0a2f4362815b4e)), closes [#3186](https://github.com/electron-userland/electron-builder/issues/3186)
* private GitHub provider ([ce1df10](https://github.com/electron-userland/electron-builder/commit/ce1df10449116815942781faf34892dd81828baf)), closes [#1266](https://github.com/electron-userland/electron-builder/issues/1266)
* product name for AppImage file ([68e5573](https://github.com/electron-userland/electron-builder/commit/68e55733421199048a2c89b255c1361f4c4814a3)), closes [#1895](https://github.com/electron-userland/electron-builder/issues/1895) [#3334](https://github.com/electron-userland/electron-builder/issues/3334)
* proton support (part 1) ([52cd3f4](https://github.com/electron-userland/electron-builder/commit/52cd3f46d7fc322c6c3dcbad2670670ba478af1f))
* proton support (part 2) ([4c16123](https://github.com/electron-userland/electron-builder/commit/4c1612396a0fde0ce973fe8189541fe1ff578a4e))
* proton support (part 3) ([0ae220e](https://github.com/electron-userland/electron-builder/commit/0ae220ebb46056251c0d96d20ec3cf9b70f68a00))
* **proton-native:** fix app icon, provide default proton icon ([319c1fc](https://github.com/electron-userland/electron-builder/commit/319c1fc549f98a829b355e23b80dbfeca09898c2))
* **proton-native:** package proton-native for Windows ([fd86d92](https://github.com/electron-userland/electron-builder/commit/fd86d92079c1b31aa54299cd44316867086968ad)), closes [#3444](https://github.com/electron-userland/electron-builder/issues/3444) [#3472](https://github.com/electron-userland/electron-builder/issues/3472) [#3113](https://github.com/electron-userland/electron-builder/issues/3113)
* **proton-native:** use custom executable name instead of hardcoded `main` ([2021841](https://github.com/electron-userland/electron-builder/commit/2021841828db35962a75d77108466e7d0cd6e695))
* Provide a custom verify function interface in NsisUpdater for native verification of nsis signatures ([#7337](https://github.com/electron-userland/electron-builder/issues/7337)) ([9c0c422](https://github.com/electron-userland/electron-builder/commit/9c0c422834369f42b311b5d9ecd301f8b50bccfa))
* Provide a new file macro matching Node.js "process.platform" property ([5f39a05](https://github.com/electron-userland/electron-builder/commit/5f39a053cf2cfd403a7719d790f2fd125400fd5e)), closes [#2652](https://github.com/electron-userland/electron-builder/issues/2652) [#2661](https://github.com/electron-userland/electron-builder/issues/2661) [#2636](https://github.com/electron-userland/electron-builder/issues/2636)
* prune submodule package.json dependencies ([1145cb9](https://github.com/electron-userland/electron-builder/commit/1145cb90455891be4c2156d15128e7fd067d8584)), closes [#1539](https://github.com/electron-userland/electron-builder/issues/1539)
* PUBLISH_FOR_PULL_REQUEST ([7d8e097](https://github.com/electron-userland/electron-builder/commit/7d8e0976c34a7219c7a41b95978f0890663e3d83))
* react-cra detection, shareable config support — extends ([28f0266](https://github.com/electron-userland/electron-builder/commit/28f02665b8c633085cb8400a83c6b1cbff16bea3))
* rebuild native node modules using prebuild-install directly if possible, do not build from sources if paltform/arch is not compatible ([d55e830](https://github.com/electron-userland/electron-builder/commit/d55e8301eb718cff5ebfe1b367f7fd8208d83e9f))
* **remote-build:** download file using several connections to minimize latency effect ([d8079e8](https://github.com/electron-userland/electron-builder/commit/d8079e8daa421023c0b028d85492dca86bbb1484))
* remove "Space required" text for NSIS installer ([565740c](https://github.com/electron-userland/electron-builder/commit/565740c2ce8a359ced1d76b464dcaa8b0ff36e42)), closes [#1566](https://github.com/electron-userland/electron-builder/issues/1566)
* remove `./` prefix from file pattern ([946dfb6](https://github.com/electron-userland/electron-builder/commit/946dfb6e5d78e0110142865cfd145e69ea2a7ef0))
* remove jspm, ava, babel keys from package metadata ([c020401](https://github.com/electron-userland/electron-builder/commit/c0204010579c22ecddf76c2186ac3c3106ebb873)), closes [#1764](https://github.com/electron-userland/electron-builder/issues/1764)
* Remove scripts, devDependencies and build from package.json ([ab41fcf](https://github.com/electron-userland/electron-builder/commit/ab41fcf1df922f6d60b259472e2adad56f545725)), closes [#1212](https://github.com/electron-userland/electron-builder/issues/1212)
* resolve electron version if specified as `latest` ([0f6cef6](https://github.com/electron-userland/electron-builder/commit/0f6cef6ce36aa2c7ab69e7a261b3b6f68b541da4)), closes [#1766](https://github.com/electron-userland/electron-builder/issues/1766)
* retry code sign if failed due to network failure ([9b60518](https://github.com/electron-userland/electron-builder/commit/9b60518f4db37f6f8a378dbc9749c98ba154ed39)), closes [#1414](https://github.com/electron-userland/electron-builder/issues/1414)
* rewrite remote build client in Go, avoid NodeJS ([5503cee](https://github.com/electron-userland/electron-builder/commit/5503cee42fae3531fc87f73417c7f850e3764687))
* S3 AWS Publishing ([fd4fc0f](https://github.com/electron-userland/electron-builder/commit/fd4fc0f6af0032d28799357001192997aa59cd44))
* **s3-publisher:** add server-side encryption option for s3 publish ([#2443](https://github.com/electron-userland/electron-builder/issues/2443)) ([1ac8ab2](https://github.com/electron-userland/electron-builder/commit/1ac8ab276697ea4e9d3c36e55999647b79f12276))
* **s3:** Ability to not add ` "x-amz-acl": "public-read"` to the header when uploading artefacts to S3 bucket ([203c8c4](https://github.com/electron-userland/electron-builder/commit/203c8c4a81e4e57fc6717222a9b62e76e9874d24)), closes [#1822](https://github.com/electron-userland/electron-builder/issues/1822) [#1618](https://github.com/electron-userland/electron-builder/issues/1618)
* search for react-script in package dependencies as well as devDependencies ([20c12be](https://github.com/electron-userland/electron-builder/commit/20c12be3622d8c4b95e4f50d6b758ea79cca1021)), closes [#2532](https://github.com/electron-userland/electron-builder/issues/2532)
* Separate build config from package.json ([ecfdc65](https://github.com/electron-userland/electron-builder/commit/ecfdc652b793d50a0a803c98ba16646047265640)), closes [#1109](https://github.com/electron-userland/electron-builder/issues/1109)
* Set platform npm environment variable ([9249fcd](https://github.com/electron-userland/electron-builder/commit/9249fcd30b67281fb109aebbb08d01c47b102356)), closes [#1027](https://github.com/electron-userland/electron-builder/issues/1027)
* skip file copying if source directory doesn't exists ([4709439](https://github.com/electron-userland/electron-builder/commit/47094394206787bfccd614fb7c52f1da27b5485a))
* **snap:** ability to specify plug options ([e488bfc](https://github.com/electron-userland/electron-builder/commit/e488bfc22453a915bb6475cb6b3bacc053b68409)), closes [#2100](https://github.com/electron-userland/electron-builder/issues/2100)
* **snap:** ability to specify slot properties ([#5313](https://github.com/electron-userland/electron-builder/issues/5313)) ([1235c4e](https://github.com/electron-userland/electron-builder/commit/1235c4e4b372fef90409d8f60ea9886e41ffdb87))
* **snap:** add appPartStage and layout options for Snap Store ([#5073](https://github.com/electron-userland/electron-builder/issues/5073)) ([ff117bc](https://github.com/electron-userland/electron-builder/commit/ff117bc81904b5219b84ec2cfc464d7c99c8e90c))
* **snap:** add desktop and desktop-legacy to the default interfaces for snap builds. ([#2463](https://github.com/electron-userland/electron-builder/issues/2463)) ([1998095](https://github.com/electron-userland/electron-builder/commit/1998095367b855f7d4b03981ab6ec7de7f35396c))
* **snap:** add option to not use template app ([10ccea8](https://github.com/electron-userland/electron-builder/commit/10ccea8439a55fa931e05e797f99004126f3323a))
* **snap:** add Snap `title` option ([#5350](https://github.com/electron-userland/electron-builder/issues/5350)) ([2801de7](https://github.com/electron-userland/electron-builder/commit/2801de7f6c8cc5a89534d983f39807f21e0cc94f))
* **snap:** add support for snap autostart option ([#4237](https://github.com/electron-userland/electron-builder/issues/4237)) ([9a5b950](https://github.com/electron-userland/electron-builder/commit/9a5b95058b40b12fdcf9df5089d16535806cfe75))
* **snap:** build snap on macOS ([138b229](https://github.com/electron-userland/electron-builder/commit/138b22933a8a1d14fcdcb2fd33801ee16a72116a))
* **snap:** build snap on macOS, make snap default target for Linux (in addition to appimage) ([b5258ba](https://github.com/electron-userland/electron-builder/commit/b5258ba59244473a8353f38e74327596d67d108b))
* **snap:** custom plugs ([3aed0b5](https://github.com/electron-userland/electron-builder/commit/3aed0b5a35f242d1e2550c516e29a497b1b3371f)), closes [#1226](https://github.com/electron-userland/electron-builder/issues/1226)
* **snap:** do not all apt-get install and update if build packages already installed ([ba9e9da](https://github.com/electron-userland/electron-builder/commit/ba9e9da3587a63133d6f1a6d59a6fd7e34edf12a))
* **snap:** electron 5 support ([66b1225](https://github.com/electron-userland/electron-builder/commit/66b1225ab67cb9778c973c2a626ceffff12ec4c3)), closes [#3872](https://github.com/electron-userland/electron-builder/issues/3872) [#3923](https://github.com/electron-userland/electron-builder/issues/3923)
* **snap:** electron 5 support (part 2) ([48f5878](https://github.com/electron-userland/electron-builder/commit/48f58788693ae664035862bdb7d120fead3732a1)), closes [#3701](https://github.com/electron-userland/electron-builder/issues/3701) [#3677](https://github.com/electron-userland/electron-builder/issues/3677) [#3608](https://github.com/electron-userland/electron-builder/issues/3608) [#3326](https://github.com/electron-userland/electron-builder/issues/3326) [#2887](https://github.com/electron-userland/electron-builder/issues/2887)
* **snap:** environment option ([d8c0df0](https://github.com/electron-userland/electron-builder/commit/d8c0df0e9f8b095b5a9dda4187a44596d5c2df25))
* **snap:** hooks ([6faf828](https://github.com/electron-userland/electron-builder/commit/6faf828713607ae49a4061fa524f9123969c16ce))
* **snap:** initialize db and icons for faster startup and remove fonts ([#2715](https://github.com/electron-userland/electron-builder/issues/2715)) ([5f0dd86](https://github.com/electron-userland/electron-builder/commit/5f0dd868a1620f4db8765e11b5220a8c126aab32))
* **snap:** initialize db and icons for faster startup and remove fonts [#2715](https://github.com/electron-userland/electron-builder/issues/2715) ([7800ce1](https://github.com/electron-userland/electron-builder/commit/7800ce1301154281564a23b5707e9a79bf3aa52d))
* **snap:** publishing to Snapcraft ([ff242ab](https://github.com/electron-userland/electron-builder/commit/ff242ab865f65987da4d95183a99c6fbaa7d3b78)), closes [#3187](https://github.com/electron-userland/electron-builder/issues/3187)
* **snaps:** build snaps on macOs [#509](https://github.com/electron-userland/electron-builder/issues/509) ([f343def](https://github.com/electron-userland/electron-builder/commit/f343def050d78f22978c9224c054d0501ea4d21c))
* **snap:** Snap for extra after parts and build packages support ([#1565](https://github.com/electron-userland/electron-builder/issues/1565)) ([22b5ba5](https://github.com/electron-userland/electron-builder/commit/22b5ba517d63f110a0c8865a7b37843ea8bd0cb6))
* **snap:** snapcraft 2.26 support ([9c69ce4](https://github.com/electron-userland/electron-builder/commit/9c69ce4f3e36b9848103e8b18275345e98da89bd)), closes [#1265](https://github.com/electron-userland/electron-builder/issues/1265)
* **snap:** support electron 2 ([43e23c8](https://github.com/electron-userland/electron-builder/commit/43e23c8cd7af4e88388b8596e6fefac119fb546b))
* **snap:** template for armhf (arm 32-bit) ([6853b37](https://github.com/electron-userland/electron-builder/commit/6853b37b321bbf34b3bd6c9ec7ff88545b37291f))
* **snap:** ubuntu-app-platform (disabled by default) ([a0c0d8e](https://github.com/electron-userland/electron-builder/commit/a0c0d8ee9dae740287f4c6c5a2e3a0115627e4e4))
* **snap:** update the default stage-packages and change the default desktop helper to desktop-gtk2 ([78f2919](https://github.com/electron-userland/electron-builder/commit/78f2919868de453ac3e4a95641ea9ac5448c5712)), closes [#2432](https://github.com/electron-userland/electron-builder/issues/2432)
* **snap:** Use `core20` as default base for snap target ([#7902](https://github.com/electron-userland/electron-builder/issues/7902)) ([843d501](https://github.com/electron-userland/electron-builder/commit/843d5017f0303cf6d5a71564aad73dd15ca75d88))
* **snap:** use template snap app if no custom stage/build packages ([e7b9a9e](https://github.com/electron-userland/electron-builder/commit/e7b9a9eab9248d2c21896e2e644cbd5661683f6d))
* **Squirrel.Windows:** Add the possibility to specify setup exe name in squirrel windows packaging ([217fc0e](https://github.com/electron-userland/electron-builder/commit/217fc0ee8a39005004bb50772adab7ac0b7d6612)), closes [#1802](https://github.com/electron-userland/electron-builder/issues/1802)
* **Squirrel.Windows:** name option ([02dd8a1](https://github.com/electron-userland/electron-builder/commit/02dd8a15dd6ad2e5a56535c9e806c9ee81362967)), closes [#1743](https://github.com/electron-userland/electron-builder/issues/1743)
* **squirrel.windows:** Update Squirrel.Windows to 1.6.0 ([c4bb492](https://github.com/electron-userland/electron-builder/commit/c4bb4929f974c7976cb292955d032931ce44f7a4)), closes [#1535](https://github.com/electron-userland/electron-builder/issues/1535)
* **squirrel.windows:** Update Squirrel.Windows to 1.7.8 ([e574db8](https://github.com/electron-userland/electron-builder/commit/e574db8c7f436aa90483658f88dcd693db6160be)), closes [#1762](https://github.com/electron-userland/electron-builder/issues/1762)
* **squirrel.windows:** update Squirrel.Windows to 1.9.0 ([bcf0947](https://github.com/electron-userland/electron-builder/commit/bcf094791f575ea4d9c4e110869a1ea6dee3d288)), closes [#3409](https://github.com/electron-userland/electron-builder/issues/3409) [#2543](https://github.com/electron-userland/electron-builder/issues/2543)
* start command ([7da827e](https://github.com/electron-userland/electron-builder/commit/7da827efbb12bcdc3dec1cbf031cf13d586b4efc))
* support ${os} macro in output dir ([f629b52](https://github.com/electron-userland/electron-builder/commit/f629b52ee616d00ec19e483a0ce44de743175048)), closes [#3314](https://github.com/electron-userland/electron-builder/issues/3314)
* support additional certificate file ([#1467](https://github.com/electron-userland/electron-builder/issues/1467)) ([19c8ee4](https://github.com/electron-userland/electron-builder/commit/19c8ee4385f65bd1a8f838e7faac1039e01671a1))
* support additionalLightArgs for msi target ([#8120](https://github.com/electron-userland/electron-builder/issues/8120)) ([00f46e6](https://github.com/electron-userland/electron-builder/commit/00f46e6f60a8a762a2094264c2f2473f0a6334be))
* support file transformers not only for asar ([58061ec](https://github.com/electron-userland/electron-builder/commit/58061eca10d69205d223caa8fac448e7a78b4cc7))
* Support for hoisted node_modules (lerna + yarn workspaces) ([b0fa409](https://github.com/electron-userland/electron-builder/commit/b0fa409e2fc2d209a9c676442064fb4675c13d57)), closes [#2205](https://github.com/electron-userland/electron-builder/issues/2205)
* Support for sibling packages (lerna + yarn workspaces) ([cde9845](https://github.com/electron-userland/electron-builder/commit/cde9845e9597e4bd16c71161adcaaabfea217d62)), closes [#2222](https://github.com/electron-userland/electron-builder/issues/2222)
* support functions in js config files ([ebd9f0f](https://github.com/electron-userland/electron-builder/commit/ebd9f0f59afabf5af25705f0a2cb3f41984593bd))
* support macros in output option ([afec1dd](https://github.com/electron-userland/electron-builder/commit/afec1dde17994f6e5907726032f6c8e86e5e381f)), closes [#2833](https://github.com/electron-userland/electron-builder/issues/2833)
* Support mjs files for lifecycle operations ([#7442](https://github.com/electron-userland/electron-builder/issues/7442)) ([37d6db3](https://github.com/electron-userland/electron-builder/commit/37d6db389e76c61462cb3578ec4abece1a07d0c2)), closes [#7441](https://github.com/electron-userland/electron-builder/issues/7441)
* support nested node_modules ([#4371](https://github.com/electron-userland/electron-builder/issues/4371)) ([e9c70d5](https://github.com/electron-userland/electron-builder/commit/e9c70d50bb3b824e6ffe99965ec6acede55d2844)), closes [#4366](https://github.com/electron-userland/electron-builder/issues/4366)
* support relative (to project dir) path in the CSC_LINK ([381e8c0](https://github.com/electron-userland/electron-builder/commit/381e8c0dfd079a1bc6485797789a9da78a51f1e6)), closes [#1596](https://github.com/electron-userland/electron-builder/issues/1596)
* support resolving of `latest` version for electron-nightly ([244abfb](https://github.com/electron-userland/electron-builder/commit/244abfbaaed2999bdf2c7ae688f7db99c1cba2c2))
* Support setting boolean properties with --extraMetadata ([9e77231](https://github.com/electron-userland/electron-builder/commit/9e772313e29de77f9c44eb18ab0f8726d815fd7a)), closes [#1674](https://github.com/electron-userland/electron-builder/issues/1674)
* support using app-builder on arm64 ([dd5c33a](https://github.com/electron-userland/electron-builder/commit/dd5c33ae8cc5e701379f0ab9c8228ef17aeaf2a9))
* throw error when GH/BT token contains invalid characters ([#1771](https://github.com/electron-userland/electron-builder/issues/1771)) ([142d154](https://github.com/electron-userland/electron-builder/commit/142d1544b96dfb84bc52750bc0dd210bf05131cf))
* twice smaller block map file (use md5 instead of sha256 and remove base64 padding) ([5ef0cbc](https://github.com/electron-userland/electron-builder/commit/5ef0cbc3f29931a1ffafc0efbc8e78293b25ef15))
* unpack electron on remote server ([76b92e0](https://github.com/electron-userland/electron-builder/commit/76b92e0a928e7f93212089954a1eb66366920d6d))
* update app-builder-bin to 5.0-alpha release ([#8190](https://github.com/electron-userland/electron-builder/issues/8190)) ([503da26](https://github.com/electron-userland/electron-builder/commit/503da26f1ef71bff19bd173bdce4052c48ddc5cc))
* update linux osslsigncode (ability to sign MSI) and rcedit (1.0) ([c68741e](https://github.com/electron-userland/electron-builder/commit/c68741e41adc9cf1c980d46aecc139cbe95c6945))
* update makeappx tool, use powershell on Windows to get publisher name, allow to build appx on Windows Server 2012 R2 ([4d7e1b5](https://github.com/electron-userland/electron-builder/commit/4d7e1b56f8d977c27d7d0694e7185a9d41adcc4b))
* update rcedit to 1.1.0 ([2263cb8](https://github.com/electron-userland/electron-builder/commit/2263cb8f573bd32d702f63d68867e7c58fdb8d8c)), closes [#2864](https://github.com/electron-userland/electron-builder/issues/2864)
* update rcedit, use rcedit x64 on Windows x64 ([5cb085d](https://github.com/electron-userland/electron-builder/commit/5cb085de5cabd3cc6335d79fcc0caeb3c7993b4a)), closes [#3889](https://github.com/electron-userland/electron-builder/issues/3889)
* update win tools (win 10 sdk 10.0.17134.0) ([7ee601c](https://github.com/electron-userland/electron-builder/commit/7ee601c6a71ce7350798b50d8458cbd32fc79e0f))
* **updater:** Add Channel Support for Github with PreRelease ([#6505](https://github.com/electron-userland/electron-builder/issues/6505)) ([#1722](https://github.com/electron-userland/electron-builder/issues/1722)) ([#4988](https://github.com/electron-userland/electron-builder/issues/4988)) ([1de0adb](https://github.com/electron-userland/electron-builder/commit/1de0adbd615b3b3d26faeb6a449f522355b36041))
* Upgrade docker images to Ubuntu 22.04 and python 3.10 ([#6922](https://github.com/electron-userland/electron-builder/issues/6922)) ([03cc9b9](https://github.com/electron-userland/electron-builder/commit/03cc9b96e0be07ef3450e3992eafcb7fe903a853))
* upgrade keygen integration to v1.1 ([#6941](https://github.com/electron-userland/electron-builder/issues/6941)) ([14503ce](https://github.com/electron-userland/electron-builder/commit/14503ceb99c1a31c54a261a1ae60a34980f36a50))
* use `mergeASARs` API by @electron/universal ([#6578](https://github.com/electron-userland/electron-builder/issues/6578)) ([81132a8](https://github.com/electron-userland/electron-builder/commit/81132a857b24bfdb01fc44eba75fc89fa2885545))
* use base64 to encode sha512 checksum in the update info ([4451107](https://github.com/electron-userland/electron-builder/commit/44511071075fc55c3f7fa461a3cc71b8fdb47ac7))
* use blake2s 18 output length to compute checksums ([129c2c4](https://github.com/electron-userland/electron-builder/commit/129c2c49acb8a36865cf74eec2dbb4c63002c2ae))
* Use BUILD_BUILDNUMBER env var as buildNumber for VSTS CI ([#2161](https://github.com/electron-userland/electron-builder/issues/2161)) ([65fcb71](https://github.com/electron-userland/electron-builder/commit/65fcb71d0142360d01738fdb65b96dfd71b480bf))
* Use Electron.Net to send http requests for auto updater ([569dd8b](https://github.com/electron-userland/electron-builder/commit/569dd8bb4e3e073e6bbcfda70c2fa34571ec5a41)), closes [#959](https://github.com/electron-userland/electron-builder/issues/959) [#1024](https://github.com/electron-userland/electron-builder/issues/1024)
* use go multi-part downloader to download big files (much more faster and reliable compared to node due to obvious reasons) ([22ee3e9](https://github.com/electron-userland/electron-builder/commit/22ee3e9cc5608a9f7d7cbcc6d22fba403a0aa435))
* use NodeJS 9 in the docker images ([e4a2ede](https://github.com/electron-userland/electron-builder/commit/e4a2ede74af46ad131526eb74c9cd418b7a54723))
* use solid compression for web installer package ([63fdecb](https://github.com/electron-userland/electron-builder/commit/63fdecb6a3c221ba1075743e875b149ade15fd58))
* Use tar instead of 7zip to preserve file permissions in tar.gz packages ([#6791](https://github.com/electron-userland/electron-builder/issues/6791)) ([95910f8](https://github.com/electron-userland/electron-builder/commit/95910f87195f501eadda95c52cfa8e1816d211b6))
* use wine64 on macOS ([dbcbaf3](https://github.com/electron-userland/electron-builder/commit/dbcbaf3fb670c6d0e7af1c240f73d80252fd9dc8))
* validate build options ([c35b315](https://github.com/electron-userland/electron-builder/commit/c35b3150536be66a9e1c2aae75f7e8f7f610699d))
* validate config using JSON schema ([d65f8c3](https://github.com/electron-userland/electron-builder/commit/d65f8c385d00294acf09d90f147d19636586da14)), closes [#1292](https://github.com/electron-userland/electron-builder/issues/1292) [#1290](https://github.com/electron-userland/electron-builder/issues/1290)
* validate icon permissions ([c03ad38](https://github.com/electron-userland/electron-builder/commit/c03ad3851cf8849ef59c1f78898bbebe8a715c6f)), closes [#2654](https://github.com/electron-userland/electron-builder/issues/2654)
* win custom sign should have same signature of doSign ([#4833](https://github.com/electron-userland/electron-builder/issues/4833)) ([f938de5](https://github.com/electron-userland/electron-builder/commit/f938de5aae09cb832a6f7f742e64a0d6c025fb9f))
* **win:** code sign .dlls on Windows ([#3057](https://github.com/electron-userland/electron-builder/issues/3057)) ([296af36](https://github.com/electron-userland/electron-builder/commit/296af36208b531924805b1bca0166dcda0a82622))
* **windows:** Portable Build ([6292855](https://github.com/electron-userland/electron-builder/commit/6292855cc5e0210a617b0b0ae0ab73f3c1682315)), closes [#1157](https://github.com/electron-userland/electron-builder/issues/1157)
* **windows:** Possible to delegate code signing ([64f18a6](https://github.com/electron-userland/electron-builder/commit/64f18a6cfade753bb2d8e43ba3655ad86f7b17dd)), closes [#2106](https://github.com/electron-userland/electron-builder/issues/2106)
* **windows:** Sign resources/*.exe and *.exe files and elevate.exe ([821320c](https://github.com/electron-userland/electron-builder/commit/821320c1d2d40b1d5da540583eb2d7046e9ef3d0)), closes [#2853](https://github.com/electron-userland/electron-builder/issues/2853)
* **windows:** Support passing the `sha1` of a certificate in Windows codesign ([4be81dc](https://github.com/electron-userland/electron-builder/commit/4be81dc268332540d4ac6d94f443e502b0ba6ae7)), closes [#1297](https://github.com/electron-userland/electron-builder/issues/1297)
* **windows:** ZIP compression for portable ([e23cecb](https://github.com/electron-userland/electron-builder/commit/e23cecb4e335ea89840e28965f48099c936e93ef)), closes [#2548](https://github.com/electron-userland/electron-builder/issues/2548)
* **win:** generate icns from png of png file set [#1682](https://github.com/electron-userland/electron-builder/issues/1682) ([339b950](https://github.com/electron-userland/electron-builder/commit/339b95048a1f49d488998e7d2ff0421fd6768ac0))
* **win:** Windows Code Signing using Parallels Desktop ([d0da2f7](https://github.com/electron-userland/electron-builder/commit/d0da2f7c62ceb0026c173a3aa4c90dc861bf8b03)), closes [#1717](https://github.com/electron-userland/electron-builder/issues/1717) [#1299](https://github.com/electron-userland/electron-builder/issues/1299)
* **win:** windows icon from macOS icns ([a832ba7](https://github.com/electron-userland/electron-builder/commit/a832ba70ffed1640d2a92a1fd0d0f9256804b387))
* **win:** windows icon from macOS icns ([0958618](https://github.com/electron-userland/electron-builder/commit/0958618dea23955fd4a2a7aa278e6b34ea72d0e8))
* write asar integrity resource on windows ([#8245](https://github.com/electron-userland/electron-builder/issues/8245)) ([13e0e0d](https://github.com/electron-userland/electron-builder/commit/13e0e0d2a272e6111024a28e1c3619dd1769366c))
* yarn 3 support for native modules via new electron/rebuild compilation ([#8112](https://github.com/electron-userland/electron-builder/issues/8112)) ([9edfee6](https://github.com/electron-userland/electron-builder/commit/9edfee6da2de0cfedafebceef0dbfea1a0a17644))


### Performance Improvements

* **appx:** Use File Mappings instead of copy ([f06324a](https://github.com/electron-userland/electron-builder/commit/f06324a5c0e4fba8b6853056a8b1e93650df180c))
* **electron-updater:** a little bit more compact blockmap data ([c92bc38](https://github.com/electron-userland/electron-builder/commit/c92bc38a46e890358bbdd40d3e3d73e4c72ce812))
* get rid of JS S3 SDK ([f0d76c0](https://github.com/electron-userland/electron-builder/commit/f0d76c037d13a4bec75106863dcc05607ea6641e))
* get rid of nugget (request) — use multi-part downloader in go instead, get rid of JS S3 SDK ([d200378](https://github.com/electron-userland/electron-builder/commit/d200378ad114be2f701f2aaf70e1215c2d04f2a3))
* get rid of xz ([83b1cd7](https://github.com/electron-userland/electron-builder/commit/83b1cd7674a8274dee7a27a885acd69523df9d4b))
* get rid of xz on Linux ([44fdded](https://github.com/electron-userland/electron-builder/commit/44fdded759997ed31b4e88ace4c8b977b064640b))
* **nsis:** run tasks in parallel ([6f56905](https://github.com/electron-userland/electron-builder/commit/6f56905ff53ff0ec92f4483bb964d721bfe4d4fe))
* **snap:** avoid file copying during creation snap from template ([d49693c](https://github.com/electron-userland/electron-builder/commit/d49693c8e3d3029f05ab39cdb3848875ed1a9966))
* use fcopy ([d9a8015](https://github.com/electron-userland/electron-builder/commit/d9a801590899acaf1b23f802c97037ac525ec9f3))
* **zip:** Use default compression level ([1b674e4](https://github.com/electron-userland/electron-builder/commit/1b674e4563217ff78cd5c44aad15200630558d0f)), closes [#3032](https://github.com/electron-userland/electron-builder/issues/3032)


### Reverts

* Revert "fix(appx): Update `identityName` validation for windows 10 (#8203)" (#8205) ([48e6b14](https://github.com/electron-userland/electron-builder/commit/48e6b14b767817f20af47df568423765cc5421d0)), closes [#8203](https://github.com/electron-userland/electron-builder/issues/8203) [#8205](https://github.com/electron-userland/electron-builder/issues/8205)
* Revert "chore(deps): update actions/labeler action to v5 (#7937)" (#7947) ([6c4d17c](https://github.com/electron-userland/electron-builder/commit/6c4d17cc7811307a6685c766bac72a5397073e58)), closes [#7937](https://github.com/electron-userland/electron-builder/issues/7937) [#7947](https://github.com/electron-userland/electron-builder/issues/7947)
* Revert "chore: update pnpm version for tests and docker images (#7640)" ([014397b](https://github.com/electron-userland/electron-builder/commit/014397b798047b0afda7d5f04d7a8e13036b351a)), closes [#7640](https://github.com/electron-userland/electron-builder/issues/7640)
* Revert "fix: codesign all binary-like files (#5322)" (#5488) ([0262278](https://github.com/electron-userland/electron-builder/commit/026227888f8c537855abf6d6aa2141a692a6bc8e)), closes [#5322](https://github.com/electron-userland/electron-builder/issues/5322) [#5488](https://github.com/electron-userland/electron-builder/issues/5488)
* Revert "fix: Update BintrayProvider.ts (#4921)" (#4973) ([ee59eed](https://github.com/electron-userland/electron-builder/commit/ee59eed4b48eff87786715a30d1865d9186c24d9)), closes [#4921](https://github.com/electron-userland/electron-builder/issues/4921) [#4973](https://github.com/electron-userland/electron-builder/issues/4973)
* Revert "fix(nsis): NSIS Uninstaller registry entry format change (#4069)" (#4443) ([b8d6905](https://github.com/electron-userland/electron-builder/commit/b8d6905582b28a9b36f11308f9a72ebc32dc2c86)), closes [#4069](https://github.com/electron-userland/electron-builder/issues/4069) [#4443](https://github.com/electron-userland/electron-builder/issues/4443)
* Revert "fix(appx): App sandbox not enabled (ITMS-90296) (#4244)" (#4414) ([d55f880](https://github.com/electron-userland/electron-builder/commit/d55f8803034afe594c875b5aed8d4b29b510f1f7)), closes [#4244](https://github.com/electron-userland/electron-builder/issues/4244) [#4414](https://github.com/electron-userland/electron-builder/issues/4414)
* fix(mac): should normalize unicode strings from file system before used in string compare ([#4841](https://github.com/electron-userland/electron-builder/issues/4841)) ([#7905](https://github.com/electron-userland/electron-builder/issues/7905)) ([d1347a0](https://github.com/electron-userland/electron-builder/commit/d1347a06e5bd14f7811a543d2e8929b2ca3cdc39))


### BREAKING CHANGES

* Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/

* fix: force strip path separators for backslashes on Windows

* fix: Force authentication for local Mac Squirrel update server
* Fail-fast for signature verification failures. Adding `-LiteralPath` to update file for injected wildcards

* Adding changeset and eslint

* Fix error: `-OUTPUTCHARSET is disabled for non Win32 platforms.`
* Admins using advertisement must apply an MST to re-enable it. See #6508.
* remove MSI option `iconId`

* fix: stabilizing tests by moving updater tests to its own node to explicitly segment env.___TOKEN integration tests from other standard unit tests

* chore: synchronizing docs and schema plus prettier

* Adding changset to set as alpha

* Updating changeset documentation
* **appx:** if identityName is specified in your config and differs from your app name, appx id will be changed to identify name.


It is very useful to set a custom `identityName` when the name of the
app in package.json contains hyphens (which are not permitted in
`appxmanifest.yml`).

Even if you set a non-hyphenated name as `identityName`,
electron-builder will still use the package.json's `name` property for
the `name` appxmanifest.yml value.

Thus, we attempt to re-use `identityName` for that case as well.

Signed-off-by: Juan Cruz Viotti <jv@jviotti.com>
* Please use `node-gyp-rebuild` as `electron-buider node-gyp-rebuild` now
* **updater:** remove compatibility with very old electron-updater version (< 0.10.0)
* if app version is `0.12.1-alpha.1`, file `alpha.yml` will be generated instead of `latest.yml`
* dmg/pkg in the out dir, not in the subdir mac
* `scripts`, `devDependencies` and `build` automatically removed from package.json
* **nsis:** installation path change
* To use Squirrel.Windows please install `electron-builder-squirrel-windows` dependency.



# [](https://github.com/electron-userland/electron-builder/compare/v25.0.0-alpha.8...v) (2024-06-02)


### Bug Fixes

* **deps:** update dependency ejs to v3.1.10 [security] ([#8192](https://github.com/electron-userland/electron-builder/issues/8192)) ([77f9774](https://github.com/electron-userland/electron-builder/commit/77f977435c99247d5db395895618b150f5006e8f))
* **docs:** update autoupdate docs noting that `channels` work with Github ([#8227](https://github.com/electron-userland/electron-builder/issues/8227)) ([48c5953](https://github.com/electron-userland/electron-builder/commit/48c59535f84cd16fb2e44d71f6b75c25c739b993))


### Features

* update app-builder-bin to 5.0-alpha release ([#8190](https://github.com/electron-userland/electron-builder/issues/8190)) ([503da26](https://github.com/electron-userland/electron-builder/commit/503da26f1ef71bff19bd173bdce4052c48ddc5cc))



# [](https://github.com/electron-userland/electron-builder/compare/v25.0.0-alpha.7...v) (2024-05-20)


### Bug Fixes

* **deps:** update dependency tar to v6.2.1 [security] ([#8171](https://github.com/electron-userland/electron-builder/issues/8171)) ([393f140](https://github.com/electron-userland/electron-builder/commit/393f140459dc4a7d6008750dc48de83c8e8d33a7))


### Features

* add `afterExtract` hook for after electron distributable has been unpacked ([#8194](https://github.com/electron-userland/electron-builder/issues/8194)) ([588c5db](https://github.com/electron-userland/electron-builder/commit/588c5db47c97e06b540bdc7f7a6de9a936a7603b))
* **mac:** support macos signature `additionalArguments` parameter  ([#8218](https://github.com/electron-userland/electron-builder/issues/8218)) ([22737b2](https://github.com/electron-userland/electron-builder/commit/22737b2b2db5a10785b1ed3fd05fd9d237fcd731))



# [](https://github.com/electron-userland/electron-builder/compare/v25.0.0-alpha.6...v) (2024-05-06)


### Bug Fixes

* **appx:** Update `identityName` validation for windows 10 ([#8203](https://github.com/electron-userland/electron-builder/issues/8203)) ([66d6d6c](https://github.com/electron-userland/electron-builder/commit/66d6d6c73776b8a62ec30d569bf68c0f1eb83ce2))
* disable broken test, needs further debugging. It's broken on all previous versions of electron-builder, seems MacOS related ([ac6d887](https://github.com/electron-userland/electron-builder/commit/ac6d8875463cba89c02a35baf347a1c2f76697e9))
* disable broken test, needs further debugging. It's broken on all previous versions of electron-builder, seems MacOS related ([01a9c08](https://github.com/electron-userland/electron-builder/commit/01a9c08f2ddbd8d1b96c58089771a93fd695c753))
* disable broken test, needs further debugging. It's broken on all previous versions of electron-builder, seems MacOS related ([dbd1fc5](https://github.com/electron-userland/electron-builder/commit/dbd1fc5510dca1da90a199fb34407573e464dba3))
* **docs/multi-platform-build.md:** broken link of build.sh ([#8193](https://github.com/electron-userland/electron-builder/issues/8193)) ([3a2ccdd](https://github.com/electron-userland/electron-builder/commit/3a2ccdd9483afa3134198b3ef56ba6163b2aaec9))
* treat cscLink empty string same as absent ([#8185](https://github.com/electron-userland/electron-builder/issues/8185)) ([5e41c5e](https://github.com/electron-userland/electron-builder/commit/5e41c5e8e440f7c6d139fc0e311efa46bc2846c3))


### Features

* Add Support for a separate Github release token to the auto-update token ([#8173](https://github.com/electron-userland/electron-builder/issues/8173)) ([3ae3589](https://github.com/electron-userland/electron-builder/commit/3ae3589a63c2d915b8456d9dc81a965a1366c73b))
* **linux:** add music mac to linux category ([#8182](https://github.com/electron-userland/electron-builder/issues/8182)) ([b43490a](https://github.com/electron-userland/electron-builder/commit/b43490a274722aba398594bcf0156d1b3687e0d2))


### Reverts

* Revert "fix(appx): Update `identityName` validation for windows 10 (#8203)" (#8205) ([48e6b14](https://github.com/electron-userland/electron-builder/commit/48e6b14b767817f20af47df568423765cc5421d0)), closes [#8203](https://github.com/electron-userland/electron-builder/issues/8203) [#8205](https://github.com/electron-userland/electron-builder/issues/8205)



# [](https://github.com/electron-userland/electron-builder/compare/v25.0.0-alpha.5...v) (2024-04-03)


### Bug Fixes

* do not chmod for 7za when `process.env.USE_SYSTEM_7ZA` is true ([#8152](https://github.com/electron-userland/electron-builder/issues/8152)) ([a999da4](https://github.com/electron-userland/electron-builder/commit/a999da48480b5024d97c3028a655bb33b00fc3bc))


### Features

* Add CLI and API for only publishing assets (skipping `build` flow) ([#8150](https://github.com/electron-userland/electron-builder/issues/8150)) ([f4e6ae2](https://github.com/electron-userland/electron-builder/commit/f4e6ae2931cbf79670b5f2c252a91bed03d96546))
* add config options for setting `MinVersion` and `MaxVersionTested` fields in appx manifest ([#8142](https://github.com/electron-userland/electron-builder/issues/8142)) ([8160363](https://github.com/electron-userland/electron-builder/commit/8160363ac2821242ab22e225a9038b56e4798cc6))
* export Packager sub-classes from main electron-builder types ([#8153](https://github.com/electron-userland/electron-builder/issues/8153)) ([8e36be1](https://github.com/electron-userland/electron-builder/commit/8e36be113489c1afa6ce5ee6cdda73049bc619a6))
* Make notarization with Apple ID more usable (`altool` is no longer supported) ([#8159](https://github.com/electron-userland/electron-builder/issues/8159)) ([15bffa0](https://github.com/electron-userland/electron-builder/commit/15bffa00d429d9f333b737712fb3a13f5d26ea53))



# [](https://github.com/electron-userland/electron-builder/compare/v25.0.0-alpha.4...v) (2024-03-18)


### Bug Fixes

* update autoupdate docs to describe module-based support. set `nativeRebuilder` default value to use electron/rebuild ([#8140](https://github.com/electron-userland/electron-builder/issues/8140)) ([99a6150](https://github.com/electron-userland/electron-builder/commit/99a6150ea02c91a7e7e657c667328eb734e29b8f))



# [](https://github.com/electron-userland/electron-builder/compare/v25.0.0-alpha.3...v) (2024-03-15)


### Bug Fixes

* attempting to wrap all `hdiutil`'s in a common retry mechanism for CI stability ([#8135](https://github.com/electron-userland/electron-builder/issues/8135)) ([c2392de](https://github.com/electron-userland/electron-builder/commit/c2392de71a8f7abc092a00452eac63dd24b34e88))
* **nsis:** replace `SYSTEMROOT` with `SYSDIR` ([#8133](https://github.com/electron-userland/electron-builder/issues/8133)) ([44b0446](https://github.com/electron-userland/electron-builder/commit/44b04463bf581b4c013586c9010733b518a802a4))



# [](https://github.com/electron-userland/electron-builder/compare/v25.0.0-alpha.2...v) (2024-03-12)


### Bug Fixes

* order files in asar for optimized differential updates ([#8128](https://github.com/electron-userland/electron-builder/issues/8128)) ([555dc90](https://github.com/electron-userland/electron-builder/commit/555dc909a97cbaab5bc5df6cdf6f1176dff1e604))
* **win:** use appInfo `description` as primary entry for `FileDescription` ([#8125](https://github.com/electron-userland/electron-builder/issues/8125)) ([c6c9d59](https://github.com/electron-userland/electron-builder/commit/c6c9d59e4cc8444ab847a14bf64364b065a384ee))



# [](https://github.com/electron-userland/electron-builder/compare/v25.0.0-alpha.1...v) (2024-03-11)


### Bug Fixes

* **deps:** update dependency @electron/notarize to v2.3.0 ([#8114](https://github.com/electron-userland/electron-builder/issues/8114)) ([0e8e7f6](https://github.com/electron-userland/electron-builder/commit/0e8e7f6524f0f00b28348fc47c57db8f801692b1))
* **deps:** update dependency @electron/universal to v2 ([#8115](https://github.com/electron-userland/electron-builder/issues/8115)) ([f8602aa](https://github.com/electron-userland/electron-builder/commit/f8602aa222ad8b85eb0b91a11f359580203ba024))
* move `disableSanityCheckAsar` to within `checkFileInPackage` for non-asar verification ([#8124](https://github.com/electron-userland/electron-builder/issues/8124)) ([e029258](https://github.com/electron-userland/electron-builder/commit/e02925818258954747188a5eb2ece5047452b89a))


### Features

* add disableSanityCheckPackage to asar to allow custom electron fork asar integrity implementations ([#8123](https://github.com/electron-userland/electron-builder/issues/8123)) ([031d7d5](https://github.com/electron-userland/electron-builder/commit/031d7d5bdf911cb6dc4b0b108f82df44f4c2b224))
* support additionalLightArgs for msi target ([#8120](https://github.com/electron-userland/electron-builder/issues/8120)) ([00f46e6](https://github.com/electron-userland/electron-builder/commit/00f46e6f60a8a762a2094264c2f2473f0a6334be))



# [](https://github.com/electron-userland/electron-builder/compare/v24.13.4-alpha.0...v) (2024-03-09)


### Features

* add minimumSystemVersion in electron updater ([#8108](https://github.com/electron-userland/electron-builder/issues/8108)) ([3d4cc7a](https://github.com/electron-userland/electron-builder/commit/3d4cc7ae01c4f6154d6ea59726578b1ff99b9daf))
* yarn 3 support for native modules via new electron/rebuild compilation ([#8112](https://github.com/electron-userland/electron-builder/issues/8112)) ([9edfee6](https://github.com/electron-userland/electron-builder/commit/9edfee6da2de0cfedafebceef0dbfea1a0a17644))



# [](https://github.com/electron-userland/electron-builder/compare/v24.13.3...v) (2024-03-08)


### Bug Fixes

* mac differential updater ([#8095](https://github.com/electron-userland/electron-builder/issues/8095)) ([53cec79](https://github.com/electron-userland/electron-builder/commit/53cec79bdc3f56c9371bdfb7901e97650d9ac4bc))
* **mac:** add retry in mac code sign ([#8101](https://github.com/electron-userland/electron-builder/issues/8101)) ([9bcede8](https://github.com/electron-userland/electron-builder/commit/9bcede88f2083d41266e48dfa712adc2d223bd7f))
* **mac:** revert mac differential autoupdate ([#8091](https://github.com/electron-userland/electron-builder/issues/8091)) ([e2a181d](https://github.com/electron-userland/electron-builder/commit/e2a181d9fe3fbdd84690359e275daaef24584729)), closes [#7709](https://github.com/electron-userland/electron-builder/issues/7709)



# [](https://github.com/electron-userland/electron-builder/compare/v24.13.3...v) (2024-03-03)


### Bug Fixes

* **mac:** revert mac differential autoupdate ([#8091](https://github.com/electron-userland/electron-builder/issues/8091)) ([e2a181d](https://github.com/electron-userland/electron-builder/commit/e2a181d9fe3fbdd84690359e275daaef24584729)), closes [#7709](https://github.com/electron-userland/electron-builder/issues/7709)



# [](https://github.com/electron-userland/electron-builder/compare/v24.13.2...v) (2024-03-02)


### Bug Fixes

* **deb:** only execute `update-desktop-database` and `update-mime-database` when exists on the system ([#8067](https://github.com/electron-userland/electron-builder/issues/8067)) ([18340ee](https://github.com/electron-userland/electron-builder/commit/18340eef6d8e9ee6efbf528508bac7972168bedb))
* **mac:** signing NSIS on mac  ([#8090](https://github.com/electron-userland/electron-builder/issues/8090)) ([2c147ad](https://github.com/electron-userland/electron-builder/commit/2c147addb09385008cf661c952e7ce390a254d8e))


### Features

* add support for differential zip updates on macOS ([#7709](https://github.com/electron-userland/electron-builder/issues/7709)) ([79df542](https://github.com/electron-userland/electron-builder/commit/79df54238621fbe48ba20444129950ba2dc49983))
* **msi:** build emulated arm64 MSI installers ([#8086](https://github.com/electron-userland/electron-builder/issues/8086)) ([e6f1beb](https://github.com/electron-userland/electron-builder/commit/e6f1bebd96cbc54f7455cd9bd48bb1eadc5648f5)), closes [#6077](https://github.com/electron-userland/electron-builder/issues/6077)



# [](https://github.com/electron-userland/electron-builder/compare/v24.13.1...v) (2024-02-22)


### Bug Fixes

* execute `%SYSTEMROOT%` cmd.exe directly during NSIS installer ([#8059](https://github.com/electron-userland/electron-builder/issues/8059)) ([8f4acff](https://github.com/electron-userland/electron-builder/commit/8f4acff3c2d45c1cb07779bb3fe79644408ee387))
* **mac:** only skip notarization step when `notarize` is explicitly false ([#8065](https://github.com/electron-userland/electron-builder/issues/8065)) ([5681777](https://github.com/electron-userland/electron-builder/commit/5681777a808d49756f3a95d18cc589218be44878))
* **pkg:** provide `BundlePreInstallScriptPath` and/or `BundlePostInstallScriptPath` when a pre/postinstall script is provided to pkg installer ([#8071](https://github.com/electron-userland/electron-builder/issues/8071)) ([eb296c9](https://github.com/electron-userland/electron-builder/commit/eb296c9b2afd77db799eadd472f9ec22f6fc4354))
* use `pathToFileUrl` for hooks for Windows ES module support ([#8069](https://github.com/electron-userland/electron-builder/issues/8069)) ([538dd86](https://github.com/electron-userland/electron-builder/commit/538dd86bf52f0091dbb1120bdd30f56dfdbd5747))



# [](https://github.com/electron-userland/electron-builder/compare/v24.13.0...v) (2024-02-17)


### Bug Fixes

* add dmg-builder and squirrel-windows to peerDependencies for pnpm ([#8052](https://github.com/electron-userland/electron-builder/issues/8052)) ([6a4f605](https://github.com/electron-userland/electron-builder/commit/6a4f605f9ae1a1de02a8260ffe054f74fbd097a5))
* auto-update powershell script requires reset of `PSModulePath` ([#8051](https://github.com/electron-userland/electron-builder/issues/8051)) ([48603ba](https://github.com/electron-userland/electron-builder/commit/48603ba09dc7103849a2975799c19068fd08fc07))



# [](https://github.com/electron-userland/electron-builder/compare/v24.12.0...v) (2024-02-09)


### Bug Fixes

* Attempt dynamically importing hook as a module if package.json `type=module`, if fail, fallback to default `require` ([#8042](https://github.com/electron-userland/electron-builder/issues/8042)) ([63a0044](https://github.com/electron-userland/electron-builder/commit/63a00443cf4bae9d7406f7e879ea607632da08b8))
* **deps:** update dependency @electron/notarize to v2.2.1 ([#8029](https://github.com/electron-userland/electron-builder/issues/8029)) ([2248134](https://github.com/electron-userland/electron-builder/commit/2248134068e035ec76fe696385bb467a94dd384d))
* **deps:** update dependency @electron/universal to v1.5.1 ([#8030](https://github.com/electron-userland/electron-builder/issues/8030)) ([db3b18e](https://github.com/electron-userland/electron-builder/commit/db3b18e799a6579bbc36c41b3125a062ebf075ec))
* **mac:** merge `fileAssociations` with existing `CFBundleDocumentTypes` if defined in `mac.extendInfo` ([#8035](https://github.com/electron-userland/electron-builder/issues/8035)) ([94677f3](https://github.com/electron-userland/electron-builder/commit/94677f3d70866582635c717b042194f0c75bbf01))
* **mac:** Update mac notarize keychain env var to be optional. Fixes: [#8015](https://github.com/electron-userland/electron-builder/issues/8015) ([#8022](https://github.com/electron-userland/electron-builder/issues/8022)) ([9d1d150](https://github.com/electron-userland/electron-builder/commit/9d1d150896a763d3630418bf5be8fd3a070c0c40))
* use CI_COMMIT_TAG instead of CI_BUILD_TAG for Gitlab CI ([#8010](https://github.com/electron-userland/electron-builder/issues/8010)) ([f5340b7](https://github.com/electron-userland/electron-builder/commit/f5340b732dc0a303743a2a924750e9861e3a345f))


### Features

* allow `onNodeModuleFile` to return a boolean to force include the package to be copied ([#8043](https://github.com/electron-userland/electron-builder/issues/8043)) ([bb4a8c0](https://github.com/electron-userland/electron-builder/commit/bb4a8c09318045938bfff5a0d1db8f17f0fa4e8c))



# [](https://github.com/electron-userland/electron-builder/compare/v24.11.0...v) (2024-01-23)


### Bug Fixes

* **linux:** Use ~ as pre-release separator for deb targets ([#7978](https://github.com/electron-userland/electron-builder/issues/7978)) ([2773410](https://github.com/electron-userland/electron-builder/commit/277341000a87abaa65a7985854c06e88ed5938b9))
* Use fully-defined path `/usr/bin/___` to macOS signing utilities ([#7998](https://github.com/electron-userland/electron-builder/issues/7998)) ([61dfe7f](https://github.com/electron-userland/electron-builder/commit/61dfe7fbaa592785353348a16abd1525dcbfaf28))


### Features

* **mac:** Add support for a custom 'sign' function in mac/mas config ([#8002](https://github.com/electron-userland/electron-builder/issues/8002)) ([adf97dc](https://github.com/electron-userland/electron-builder/commit/adf97dccd0146288ab482a261b749d67a458868a))



# [](https://github.com/electron-userland/electron-builder/compare/v24.10.0...v) (2024-01-09)


### Bug Fixes

* **docs/configuration:** broken links ([#7949](https://github.com/electron-userland/electron-builder/issues/7949)) ([98624c9](https://github.com/electron-userland/electron-builder/commit/98624c93ae5063886e82eaa81f67317d5e79f26c))
* notarization with an apple API key ([#7951](https://github.com/electron-userland/electron-builder/issues/7951)) ([869c7e4](https://github.com/electron-userland/electron-builder/commit/869c7e4652a5d5a3562e25723d6cedd622ab657b))
* update unit test snapshot to account for new package dependency files ([#7968](https://github.com/electron-userland/electron-builder/issues/7968)) ([9335c59](https://github.com/electron-userland/electron-builder/commit/9335c59e224b3cba57cba8822995a88f5349a927))
* **win:** product file name is too long causing the find process exe failed ([#7955](https://github.com/electron-userland/electron-builder/issues/7955)) ([88e61bc](https://github.com/electron-userland/electron-builder/commit/88e61bc410fae8c0bea0b2029ee1347864af98ac))


### Features

* **archive:** skip nsis compression step when archive is already up to date ([#7971](https://github.com/electron-userland/electron-builder/issues/7971)) ([8803852](https://github.com/electron-userland/electron-builder/commit/8803852c7aadf56771f537dc33ffd51c14830f50))
* **nsis:** add NsisOption to specify selectPerMachineByDefault ([#7967](https://github.com/electron-userland/electron-builder/issues/7967)) ([28e5b5d](https://github.com/electron-userland/electron-builder/commit/28e5b5ddb6bb2d77ef6847fc0c93e62c97174156))
* **nsis:** add option to disable differential download ([#7950](https://github.com/electron-userland/electron-builder/issues/7950)) ([03c9451](https://github.com/electron-userland/electron-builder/commit/03c94516ef3b1b31b2f5b7bcdb9c6d3753d36b8d))



# [](https://github.com/electron-userland/electron-builder/compare/v24.9.4...v) (2023-12-13)


### Features

* Enable ESM support for hooks by using dynamic `import()` when `package.json` is set to type `module` ([#7936](https://github.com/electron-userland/electron-builder/issues/7936)) ([664a09c](https://github.com/electron-userland/electron-builder/commit/664a09c4471f46a5b88be0b8e26f24b1a0b2bcc1))
* **snap:** Use `core20` as default base for snap target ([#7902](https://github.com/electron-userland/electron-builder/issues/7902)) ([843d501](https://github.com/electron-userland/electron-builder/commit/843d5017f0303cf6d5a71564aad73dd15ca75d88))


### Reverts

* Revert "chore(deps): update actions/labeler action to v5 (#7937)" (#7947) ([6c4d17c](https://github.com/electron-userland/electron-builder/commit/6c4d17cc7811307a6685c766bac72a5397073e58)), closes [#7937](https://github.com/electron-userland/electron-builder/issues/7937) [#7947](https://github.com/electron-userland/electron-builder/issues/7947)



# [](https://github.com/electron-userland/electron-builder/compare/v24.9.3...v) (2023-12-08)


### Bug Fixes

* Allowing `test.js` in compiled asar to allow testing mechanisms like Playwright ([#7931](https://github.com/electron-userland/electron-builder/issues/7931)) ([f7aacab](https://github.com/electron-userland/electron-builder/commit/f7aacabd9cc1b98e365134004aafa31566c7d801))
* **mac:** use `zip` instead of `7z` if name contains NFD characters ([#7929](https://github.com/electron-userland/electron-builder/issues/7929)) ([0f43989](https://github.com/electron-userland/electron-builder/commit/0f439890229431f02c7f86d5bf523e940e217657))
* **win:** use `resultOutputPath` to sign custom location for windows ([#7919](https://github.com/electron-userland/electron-builder/issues/7919)) ([4e930a7](https://github.com/electron-userland/electron-builder/commit/4e930a74d7c2e9b53d47e37997b444da95680a24)), closes [#7910](https://github.com/electron-userland/electron-builder/issues/7910)



# [](https://github.com/electron-userland/electron-builder/compare/v24.9.2...v) (2023-11-29)


### Bug Fixes

* pass `publish` options to snap publisher ([#7908](https://github.com/electron-userland/electron-builder/issues/7908)) ([9fc5157](https://github.com/electron-userland/electron-builder/commit/9fc5157879bfa380a78003ff13cdbc26b5e8fd23))


### Reverts

* fix(mac): should normalize unicode strings from file system before used in string compare ([#4841](https://github.com/electron-userland/electron-builder/issues/4841)) ([#7905](https://github.com/electron-userland/electron-builder/issues/7905)) ([d1347a0](https://github.com/electron-userland/electron-builder/commit/d1347a06e5bd14f7811a543d2e8929b2ca3cdc39))



# [](https://github.com/electron-userland/electron-builder/compare/v24.9.1...v) (2023-11-27)


### Bug Fixes

* **mac:** normalize filename to NFD form ([#7901](https://github.com/electron-userland/electron-builder/issues/7901)) ([f83f05f](https://github.com/electron-userland/electron-builder/commit/f83f05f6f24a36b96d0e0c7786e1a12e5c762389))
* **mac:** use `notarytool` with only api key auth ([#7896](https://github.com/electron-userland/electron-builder/issues/7896)) ([65817e0](https://github.com/electron-userland/electron-builder/commit/65817e0edc43a2e6707fab835b0bbe680bd0b1e4))
* use product name for helper apps ([#7900](https://github.com/electron-userland/electron-builder/issues/7900)) ([3b3a698](https://github.com/electron-userland/electron-builder/commit/3b3a69895f0caa3870219bc0bec7420de81a07ed)), closes [#6962](https://github.com/electron-userland/electron-builder/issues/6962)



# [](https://github.com/electron-userland/electron-builder/compare/v24.9.0...v) (2023-11-19)


### Bug Fixes

* mac notarization issue when checking env password ([#7884](https://github.com/electron-userland/electron-builder/issues/7884)) ([6fa8a27](https://github.com/electron-userland/electron-builder/commit/6fa8a27f9dd406c289f608c664c93b6ed9d1a9ee))
* **mac:** Pass `buildOptions` down to notarization for platform-specific build options ([#7886](https://github.com/electron-userland/electron-builder/issues/7886)) ([d7e39f0](https://github.com/electron-userland/electron-builder/commit/d7e39f05c55287ea32fd0f978ecb41078931d6b6))



# [](https://github.com/electron-userland/electron-builder/compare/v24.8.1...v) (2023-11-13)


### Bug Fixes

* flatpak build failing due to too large icons ([#7875](https://github.com/electron-userland/electron-builder/issues/7875)) ([9883ab6](https://github.com/electron-userland/electron-builder/commit/9883ab60687b67c858b16f09eea6f8af76cf01b0))
* temporarily skip flaky test from transient dependency ([3f6757b](https://github.com/electron-userland/electron-builder/commit/3f6757b41720c0740886325431c18be81a23ebbf))


### Features

* allow api key and keychain for mac notarization ([#7861](https://github.com/electron-userland/electron-builder/issues/7861)) ([906ffb1](https://github.com/electron-userland/electron-builder/commit/906ffb1fcebe6aef4dc6c6a3fab10aa7d9378c3f))



# [](https://github.com/electron-userland/electron-builder/compare/v24.8.0...v) (2023-11-04)


### Bug Fixes

* compat with newest @types/node to leverage `OutgoingHttpHeader` for httpExecutor's `RequestHeaders` ([#7806](https://github.com/electron-userland/electron-builder/issues/7806)) ([db424e8](https://github.com/electron-userland/electron-builder/commit/db424e8e876e6ac1985668bf78bd52a02824dd7f))
* **deps:** Update 7zip-bin to support Windows on ARM ([#7829](https://github.com/electron-userland/electron-builder/issues/7829)) ([1af7447](https://github.com/electron-userland/electron-builder/commit/1af7447edf47303de03ca2924727c78118161c60))
* **mac:** don't notarize mas builds ([#7838](https://github.com/electron-userland/electron-builder/issues/7838)) ([87eae1c](https://github.com/electron-userland/electron-builder/commit/87eae1cc2f85f034f1543840b20d56e89a23c0df))



# [](https://github.com/electron-userland/electron-builder/compare/v24.7.0...v) (2023-10-19)


### Bug Fixes

* display product names with an `&` properly ([#7831](https://github.com/electron-userland/electron-builder/issues/7831)) ([6e41480](https://github.com/electron-userland/electron-builder/commit/6e41480e6221693f6fec46ae813d513935e05f66))
* run nsis builds (and portable builds) sequentially ([#7798](https://github.com/electron-userland/electron-builder/issues/7798)) ([526e075](https://github.com/electron-userland/electron-builder/commit/526e075edddf908b9688e108a18fbb76e6f047be))
* support `executableName` in main config ([#7828](https://github.com/electron-userland/electron-builder/issues/7828)) ([7c7db83](https://github.com/electron-userland/electron-builder/commit/7c7db837bdf650228594a30114975f1581c37130))



# [](https://github.com/electron-userland/electron-builder/compare/v24.6.5...v) (2023-09-26)


### Bug Fixes

* exclude `electron-builder.env` file from app to avoid packaging env secrets ([#7792](https://github.com/electron-userland/electron-builder/issues/7792)) ([84906bc](https://github.com/electron-userland/electron-builder/commit/84906bc899c1b6ad2a9ec9bb9a249849e05133b5))
* expand macro for `${version}/.icon-ico/` dir on Window's installers ([#7763](https://github.com/electron-userland/electron-builder/issues/7763)) ([0cb1913](https://github.com/electron-userland/electron-builder/commit/0cb1913272c0cf24603233e2033d8fc3f33cb26d))
* Extract `NotarizeNotaryOptions` and `NotarizeLegacyOptions` to explicitly define required vars ([#7797](https://github.com/electron-userland/electron-builder/issues/7797)) ([efd48dc](https://github.com/electron-userland/electron-builder/commit/efd48dc07bdc12894e1494136448176dc8a6c4bb))


### Features

* add `customUnWelcomePage` macro for nsis ([#7790](https://github.com/electron-userland/electron-builder/issues/7790)) ([1a412f4](https://github.com/electron-userland/electron-builder/commit/1a412f4d07304fcd0404ac04b5085ffd394db6cf))



# [](https://github.com/electron-userland/electron-builder/compare/v24.6.4...v) (2023-09-18)


### Bug Fixes

* **mac:** Enhance the usage boundary of iconTextSize ([#7769](https://github.com/electron-userland/electron-builder/issues/7769)) ([#7780](https://github.com/electron-userland/electron-builder/issues/7780)) ([a8b1f15](https://github.com/electron-userland/electron-builder/commit/a8b1f1592e14710977b036313c8a2cb551a29064))
* **mac:** fix errors using native modules that require rebuild when both mas and mac targets are specified ([#7744](https://github.com/electron-userland/electron-builder/issues/7744)) ([4fc7a3c](https://github.com/electron-userland/electron-builder/commit/4fc7a3c3b857380bcbdd2a10e26989e3b1af50a2))
* When error code is ENOENT, try to use `electron.shell.openPath` to open Windows installer ([#7767](https://github.com/electron-userland/electron-builder/issues/7767)) ([21f3069](https://github.com/electron-userland/electron-builder/commit/21f3069cb6dcad30959af4bfd8f3014133a3dfde))



# [](https://github.com/electron-userland/electron-builder/compare/v24.6.3...v) (2023-08-19)


### Bug Fixes

* adding `IMAGE_VERSION` arg for docker `node` image so that it force rebuilds when pnpm is updated on any date ([#7690](https://github.com/electron-userland/electron-builder/issues/7690)) ([47c1fd7](https://github.com/electron-userland/electron-builder/commit/47c1fd71080f8079f97f6513dd037a5a617f3809))
* **docs:** typos in CONTRIBUTING.md ([#7691](https://github.com/electron-userland/electron-builder/issues/7691)) ([6bcea7f](https://github.com/electron-userland/electron-builder/commit/6bcea7f8a449daf9af09095b93bee71e22682488))
* Only schedule upload for unique files after `afterAllArtifactBuild` ([#7715](https://github.com/electron-userland/electron-builder/issues/7715)) ([66bef0f](https://github.com/electron-userland/electron-builder/commit/66bef0f7f1a0371ff924d29ed5453f9b3222c1ab))



# [](https://github.com/electron-userland/electron-builder/compare/v24.6.2...v) (2023-07-24)


### Bug Fixes

* add `signExts` configuration option to not sign `.node` files by default ([#7685](https://github.com/electron-userland/electron-builder/issues/7685)) ([78448af](https://github.com/electron-userland/electron-builder/commit/78448af062e2ce70c1eb590c05cce01919933e26))



# [](https://github.com/electron-userland/electron-builder/compare/v24.6.1...v) (2023-07-20)


### Bug Fixes

* add back missing `createLazyProductionDeps` that was missed during revert ([#7679](https://github.com/electron-userland/electron-builder/issues/7679)) ([f5d23ef](https://github.com/electron-userland/electron-builder/commit/f5d23ef4edce6096759a3e25dfe453366ab72da2))
* check null for `isCustomChannel` in GitHubProvider.ts [#7665](https://github.com/electron-userland/electron-builder/issues/7665) ([#7666](https://github.com/electron-userland/electron-builder/issues/7666)) ([441da40](https://github.com/electron-userland/electron-builder/commit/441da40d814d90154ed9b120684e7c1a7d919c52))



# [](https://github.com/electron-userland/electron-builder/compare/v24.6.0...v) (2023-07-19)


### Bug Fixes

* reverting migration to electron-rebuild since Cxx flags were back-ported to latest versions of electron ([#7668](https://github.com/electron-userland/electron-builder/issues/7668)) ([9cfd35d](https://github.com/electron-userland/electron-builder/commit/9cfd35d5ad320255d88be67530ce5fe6e832f862))
* updating simple-update-notifier version to resolve vulnerability ([#7673](https://github.com/electron-userland/electron-builder/issues/7673)) ([355e356](https://github.com/electron-userland/electron-builder/commit/355e35654510daded399ea31ed0bcd37effde935))



# [](https://github.com/electron-userland/electron-builder/compare/v24.5.2...v) (2023-07-10)


### Bug Fixes

* re-enable changeDir step for assisted, perMachine installs ([#7648](https://github.com/electron-userland/electron-builder/issues/7648)) ([84ed3ff](https://github.com/electron-userland/electron-builder/commit/84ed3ff123b5ae92cd3350d64677434f9b397b76))
* use nullish coalescing operator for hardenedRuntime default value ([#7643](https://github.com/electron-userland/electron-builder/issues/7643)) ([5fec686](https://github.com/electron-userland/electron-builder/commit/5fec686412b23614bf17f76d03fecc66c220ac99))


### Features

*  Added support for overriding ‘preAutoEntitlements’ for electron/osx-sign ([#7642](https://github.com/electron-userland/electron-builder/issues/7642)) ([2717282](https://github.com/electron-userland/electron-builder/commit/2717282cbff0dc0b6dee7e5af1fa0ecfcff1d5bf))


### Reverts

* Revert "chore: update pnpm version for tests and docker images (#7640)" ([014397b](https://github.com/electron-userland/electron-builder/commit/014397b798047b0afda7d5f04d7a8e13036b351a)), closes [#7640](https://github.com/electron-userland/electron-builder/issues/7640)



# [](https://github.com/electron-userland/electron-builder/compare/v24.5.1...v) (2023-06-27)


### Bug Fixes

* change typed-emitter to tiny-typed-emitter to remove rxjs dependency ([#7633](https://github.com/electron-userland/electron-builder/issues/7633)) ([531a630](https://github.com/electron-userland/electron-builder/commit/531a6309283ea1b2b262817a170e2c030735f8b6))
* **linux:** make semver pre-release versions valid for "pacman" and "rpm" target ([#7630](https://github.com/electron-userland/electron-builder/issues/7630)) ([37db080](https://github.com/electron-userland/electron-builder/commit/37db080ffabf546132d278ff69532b0558ad0a41))
* trigger `app.relaunch()` if `isForceRunAfter = true` for rpm and deb updaters ([#7637](https://github.com/electron-userland/electron-builder/issues/7637)) ([b3dfe64](https://github.com/electron-userland/electron-builder/commit/b3dfe64b22dc51375861f6b8a3517ff9ab562aaf))



# [](https://github.com/electron-userland/electron-builder/compare/v24.5.0...v) (2023-06-24)


### Bug Fixes

* **mac:** use Identity `hash` instead of `name` if it exists ([#7622](https://github.com/electron-userland/electron-builder/issues/7622)) ([4652416](https://github.com/electron-userland/electron-builder/commit/46524169cefbfa18e342d7fa19e79e710aae848e))
* removing stdio from spawnSync to fix crash on rpm/deb updaters ([#7628](https://github.com/electron-userland/electron-builder/issues/7628)) ([98f535e](https://github.com/electron-userland/electron-builder/commit/98f535e1f80b7f84dc3c2f135a4a5ea8cd142f31))
* resolve unstable unit test that is on latest mac ([#7626](https://github.com/electron-userland/electron-builder/issues/7626)) ([16d1430](https://github.com/electron-userland/electron-builder/commit/16d1430b6c3721f3a258a02b70897a9b2af25c28))
* use electron-rebuilder API directly so as to override the platform for cross-platform prebuild compilations ([#7629](https://github.com/electron-userland/electron-builder/issues/7629)) ([285aa76](https://github.com/electron-userland/electron-builder/commit/285aa766c2675448689f2e465b6fa2b2acacdbc6))



# [](https://github.com/electron-userland/electron-builder/compare/v24.4.0...v) (2023-06-16)


### Bug Fixes

* Allow building MAS and MAC targets with different appId ([#7603](https://github.com/electron-userland/electron-builder/issues/7603)) ([f464e3e](https://github.com/electron-userland/electron-builder/commit/f464e3ee6b8a6330a9be2961afaaec150777f91c))
* default the downloaded update file name to `fileInfo.info.url` ([#7597](https://github.com/electron-userland/electron-builder/issues/7597)) ([cd15e16](https://github.com/electron-userland/electron-builder/commit/cd15e161031e180200ab772f01198a5b68fa42fe))
* **mac:** Wrap hditutil detach in retry w/ backoff ([#7600](https://github.com/electron-userland/electron-builder/issues/7600)) ([4dce371](https://github.com/electron-userland/electron-builder/commit/4dce3718abd75b8d0e29f37f6ba0ee1e76353c65))
* **nsis:** Ensure application name sub-folder on fresh installs. ([#7552](https://github.com/electron-userland/electron-builder/issues/7552)) ([e3fc9b5](https://github.com/electron-userland/electron-builder/commit/e3fc9b544cc8c6728ffd77a45408d6e0e87dbb46)), closes [#6885](https://github.com/electron-userland/electron-builder/issues/6885)


### Features

* added `ELECTRON_BUILDER_7Z_FILTER ` env variable for 7z filter ([#7609](https://github.com/electron-userland/electron-builder/issues/7609)) ([99f49cf](https://github.com/electron-userland/electron-builder/commit/99f49cf7a86afa33d35652ffc6329fefed2e5f75))



# [](https://github.com/electron-userland/electron-builder/compare/v24.3.0...v) (2023-05-08)


### Bug Fixes

* missing [@types](https://github.com/types) dependencies for output d.ts files ([#7568](https://github.com/electron-userland/electron-builder/issues/7568)) ([c9d20db](https://github.com/electron-userland/electron-builder/commit/c9d20db964cce991dab137ec0105d40d8eacd95c))


### Features

* allow specifying recommended dependencies for deb target ([#7558](https://github.com/electron-userland/electron-builder/issues/7558)) ([54c8537](https://github.com/electron-userland/electron-builder/commit/54c85374790f7a8e0dc520a20c716b4afe69be20))



# [](https://github.com/electron-userland/electron-builder/compare/v24.2.1...v) (2023-04-25)


### Bug Fixes

* handle differential downloads when the blockmap HTTP response is compressed ([#7544](https://github.com/electron-userland/electron-builder/issues/7544)) ([dab3aeb](https://github.com/electron-userland/electron-builder/commit/dab3aeba2240ead4300c8fdb35e3d9c16b04a23d))


### Features

* nsis install method - exposed as public to avoid quit the app for the install ([#7533](https://github.com/electron-userland/electron-builder/issues/7533)) ([4786d41](https://github.com/electron-userland/electron-builder/commit/4786d41575c638137c7016c905d089ab74bf5e28))
* **nsis:** display "Space Required" text for NSIS installer ([#7531](https://github.com/electron-userland/electron-builder/issues/7531)) ([0db9c66](https://github.com/electron-userland/electron-builder/commit/0db9c66f0fff9a482d34aeaafaf11f542b786bf8))



# [](https://github.com/electron-userland/electron-builder/compare/v24.2.0...v) (2023-04-13)


### Bug Fixes

* update `@electron/rebuild` version and update imports ([#7541](https://github.com/electron-userland/electron-builder/issues/7541)) ([a4888ac](https://github.com/electron-userland/electron-builder/commit/a4888ac490e4e5d3783858d27acd487b2b8444fd))
* **updater:** handle errors on responses in differential download ([#7542](https://github.com/electron-userland/electron-builder/issues/7542)) ([9123e31](https://github.com/electron-userland/electron-builder/commit/9123e31eb792211da717804e5a5b8029fe694d5f)), closes [#2398](https://github.com/electron-userland/electron-builder/issues/2398)
* Use `update-alternatives` instead of symlinks for [#7500](https://github.com/electron-userland/electron-builder/issues/7500) ([#7501](https://github.com/electron-userland/electron-builder/issues/7501)) ([e83dc81](https://github.com/electron-userland/electron-builder/commit/e83dc814725f543c6b51721fdbfee83158d35084))



# [](https://github.com/electron-userland/electron-builder/compare/v24.1.3...v) (2023-04-06)


### Bug Fixes

* Fix electron-updater error handling when spawning a process asynchronously ([#7524](https://github.com/electron-userland/electron-builder/issues/7524)) ([1a13480](https://github.com/electron-userland/electron-builder/commit/1a13480036a2219007f866c64beea45292bc2946))


### Features

* Moved `electronLanguages` to global config to support win/linux ([#7516](https://github.com/electron-userland/electron-builder/issues/7516)) ([1533501](https://github.com/electron-userland/electron-builder/commit/1533501f999b364b656cdaa2048a1a7fd5e7c361))



# [](https://github.com/electron-userland/electron-builder/compare/v24.1.2...v) (2023-04-05)


### Bug Fixes

* "Can't reconcile two non-macho files" due to new Pre-Gyp-Copy functionality in electron/rebuild integration ([#7519](https://github.com/electron-userland/electron-builder/issues/7519)) ([abf3703](https://github.com/electron-userland/electron-builder/commit/abf370395f45e4005f12131c532325a1e3232309))



# [](https://github.com/electron-userland/electron-builder/compare/v24.1.1...v) (2023-03-30)


### Bug Fixes

* NsisUpdater - only resolving true if pid !== undefined ([#7503](https://github.com/electron-userland/electron-builder/issues/7503)) ([a2ab1ff](https://github.com/electron-userland/electron-builder/commit/a2ab1ff36dbe99a9c9d22bde15e83482eb5be340)), closes [#7502](https://github.com/electron-userland/electron-builder/issues/7502)
* utilizing frameworkInfo as primary manner of fetching electron version for installation. ([#7511](https://github.com/electron-userland/electron-builder/issues/7511)) ([16283cc](https://github.com/electron-userland/electron-builder/commit/16283ccaf5788b1a60c28f6d1424f72eebecea46))



# [](https://github.com/electron-userland/electron-builder/compare/v24.1.1...v) (2023-03-26)


### Bug Fixes

* NsisUpdater - only resolving true if pid !== undefined ([#7503](https://github.com/electron-userland/electron-builder/issues/7503)) ([a2ab1ff](https://github.com/electron-userland/electron-builder/commit/a2ab1ff36dbe99a9c9d22bde15e83482eb5be340)), closes [#7502](https://github.com/electron-userland/electron-builder/issues/7502)



# [](https://github.com/electron-userland/electron-builder/compare/v24.1.0...v) (2023-03-24)


### Bug Fixes

* refactoring ffmpeg implementation and removing related npm dependency ([#7495](https://github.com/electron-userland/electron-builder/issues/7495)) ([91f86ae](https://github.com/electron-userland/electron-builder/commit/91f86aed093a78cd43e60126ebd48fa88ce7727a))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0...v) (2023-03-22)


### Bug Fixes

* **arm64:** set RPM architecture as `aarch64` in name ([#7466](https://github.com/electron-userland/electron-builder/issues/7466)) ([1342f87](https://github.com/electron-userland/electron-builder/commit/1342f872f98229cf6c31069253fcf0f435bfd9df))
* missing quote syntax error in nsis uninstaller ([#7490](https://github.com/electron-userland/electron-builder/issues/7490)) ([278a3df](https://github.com/electron-userland/electron-builder/commit/278a3df3c738dbe0d2240f338e901774b7d578c5))
* updating SignOptions typesafety and leverage `optionsForFile` for entitlements ([#7491](https://github.com/electron-userland/electron-builder/issues/7491)) ([c1deace](https://github.com/electron-userland/electron-builder/commit/c1deace1de707faacb02ae49cfaa59d60ab6ac06))


### Features

* Adding new downloadAlternateFFmpeg option to download non-proprietary ffmpeg library ([#7210](https://github.com/electron-userland/electron-builder/issues/7210)) ([#7477](https://github.com/electron-userland/electron-builder/issues/7477)) ([1dd26cc](https://github.com/electron-userland/electron-builder/commit/1dd26cc646c1a9708ff880920319bdaad17d20ba))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.13...v) (2023-03-04)


### Bug Fixes

* **packager:** return success status from doSign function calls ([48747ac](https://github.com/electron-userland/electron-builder/commit/48747ac9e1fe08f84b2335a8263eebc8f4c35561))
* **packager:** return success status from doSign function calls ([#7431](https://github.com/electron-userland/electron-builder/issues/7431)) ([eb842f7](https://github.com/electron-userland/electron-builder/commit/eb842f7faee3a261635fb3e59230e09c98840e40))
* Removing file size from BuildTest smart unpack ([#7456](https://github.com/electron-userland/electron-builder/issues/7456)) ([25dc0bb](https://github.com/electron-userland/electron-builder/commit/25dc0bbb19637add4c47be88934f70b0e84a122e))
* Revert "feat: Support mjs files for lifecycle operations" ([#7461](https://github.com/electron-userland/electron-builder/issues/7461)) ([0f9da20](https://github.com/electron-userland/electron-builder/commit/0f9da20dbf8a229242ad9247ca89ef90241512f5)), closes [#7442](https://github.com/electron-userland/electron-builder/issues/7442)


### Features

* Support mjs files for lifecycle operations ([#7442](https://github.com/electron-userland/electron-builder/issues/7442)) ([37d6db3](https://github.com/electron-userland/electron-builder/commit/37d6db389e76c61462cb3578ec4abece1a07d0c2)), closes [#7441](https://github.com/electron-userland/electron-builder/issues/7441)



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.12...v) (2023-02-21)


### Bug Fixes

* **packager:** report the correct status result when `doSign` exits early ([4d3fdfc](https://github.com/electron-userland/electron-builder/commit/4d3fdfcfe5c6b75cdb8fa8e89f6169c986949bcb))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.11...v) (2023-02-15)


### Bug Fixes

* `inherit` stdio for electron-updater `exec` ([#7393](https://github.com/electron-userland/electron-builder/issues/7393)) ([#7394](https://github.com/electron-userland/electron-builder/issues/7394)) ([1bbcfb3](https://github.com/electron-userland/electron-builder/commit/1bbcfb3dc5f36b0803c69e9170db16ded52a0043))
* **docs:** PlatformSpecificBuildOptions.md broken link ([#7405](https://github.com/electron-userland/electron-builder/issues/7405)) ([ece7f88](https://github.com/electron-userland/electron-builder/commit/ece7f889f93921894cbbcb02b924dc90d793be7c))
* enable signing of .node modules in order to support WDAC ([#7421](https://github.com/electron-userland/electron-builder/issues/7421)) ([d1e0c34](https://github.com/electron-userland/electron-builder/commit/d1e0c348283b5f099217aa247f9af24c77a3e415)), closes [#7329](https://github.com/electron-userland/electron-builder/issues/7329)
* update docs for updated electron API ([b7a53d0](https://github.com/electron-userland/electron-builder/commit/b7a53d0f69f1350b47cef118b1ef4aaf9885f88f))


### Features

* Allow for NSIS windows installer to be wrapped in an MSI ([#7407](https://github.com/electron-userland/electron-builder/issues/7407)) ([a338730](https://github.com/electron-userland/electron-builder/commit/a3387309f0297cb824926bd7fa5cb653da9f24ca))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.10...v) (2023-01-24)


### Bug Fixes

* add reject in handleError in Windows `verifySignature` function ([#7380](https://github.com/electron-userland/electron-builder/issues/7380)) ([7862e38](https://github.com/electron-userland/electron-builder/commit/7862e388a2049ccbe1e01a5624c6a8a5f2942d54))
* adding log warning in case `afterSign` exists but no signing occurred ([#7388](https://github.com/electron-userland/electron-builder/issues/7388)) ([1cb8f50](https://github.com/electron-userland/electron-builder/commit/1cb8f50c3551b398e20b798aba0c60bb34860b49))
* Allow MAS builds to be unsigned if `identity: null` is explicitly passed ([#7382](https://github.com/electron-userland/electron-builder/issues/7382)) ([bb37687](https://github.com/electron-userland/electron-builder/commit/bb37687540aa254bce6a92a86c56b606cc16f2be))
* Execute `afterSign` hook only when signing is complete (i.e. if the signing step wasn't explicitly skipped) (BREAKING) ([#7311](https://github.com/electron-userland/electron-builder/issues/7311)) ([fd93fce](https://github.com/electron-userland/electron-builder/commit/fd93fce96f476c09af3379d964bf9092bd20787e))
* incorrect html comment in issue_template.md ([#7386](https://github.com/electron-userland/electron-builder/issues/7386)) ([d07b98a](https://github.com/electron-userland/electron-builder/commit/d07b98accba0c1afea12d18e850fde02dcf8ea51))
* Manually reseting `GYP_MSVS_VERSION` for multi-arch builds before `beforePack` ([#7387](https://github.com/electron-userland/electron-builder/issues/7387)) ([aeffe08](https://github.com/electron-userland/electron-builder/commit/aeffe080e07f11057134947e09021cd9d6712935))
* MAS builds should respect arch suffix per `defaultArch` config ([#7383](https://github.com/electron-userland/electron-builder/issues/7383)) ([e5748b3](https://github.com/electron-userland/electron-builder/commit/e5748b3df35676cf6e411c6c47fc4fc56e0a26f2))
* Remove `adapter` if core22+ is set as base on snapcraft ([#7378](https://github.com/electron-userland/electron-builder/issues/7378)) ([db69a18](https://github.com/electron-userland/electron-builder/commit/db69a1875d219310b3050b35cdc46c20ec45cc04))


### Features

* enable having vendor information in `releaseInfo` ([#7373](https://github.com/electron-userland/electron-builder/issues/7373)) ([9700c75](https://github.com/electron-userland/electron-builder/commit/9700c75331e7d8de4efd257d8774b8c2a422538b))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.9...v) (2023-01-10)


### Bug Fixes

* Remove spctl check from Mac's notarization ([#7361](https://github.com/electron-userland/electron-builder/issues/7361)) ([f9f23be](https://github.com/electron-userland/electron-builder/commit/f9f23bef64efd429f6dfd1ec81f2d73927f63a8e))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.8...v) (2023-01-07)


### Bug Fixes

* Ensure parent directories of symlinks are created ([#7327](https://github.com/electron-userland/electron-builder/issues/7327)) ([973a004](https://github.com/electron-userland/electron-builder/commit/973a0048b46b8367864241a903453f927c158304))
* missing html extension for multi language license files in nsis target ([#7339](https://github.com/electron-userland/electron-builder/issues/7339)) ([8f94978](https://github.com/electron-userland/electron-builder/commit/8f94978c41d63e9fb4aa70a1df67f25804fdaf84))
* re-add `--identifier` to mac pkg build to address issue [#7348](https://github.com/electron-userland/electron-builder/issues/7348) ([#7352](https://github.com/electron-userland/electron-builder/issues/7352)) ([c08db0a](https://github.com/electron-userland/electron-builder/commit/c08db0a92b5e251229a424c1c00559086d860dde))
* Update MacOS signOptions on macPackager [#7317](https://github.com/electron-userland/electron-builder/issues/7317) ([#7351](https://github.com/electron-userland/electron-builder/issues/7351)) ([1e8dad8](https://github.com/electron-userland/electron-builder/commit/1e8dad8bc58f53780c9fac3b0c48e248a8b5467c))


### Features

* Provide a custom verify function interface in NsisUpdater for native verification of nsis signatures ([#7337](https://github.com/electron-userland/electron-builder/issues/7337)) ([9c0c422](https://github.com/electron-userland/electron-builder/commit/9c0c422834369f42b311b5d9ecd301f8b50bccfa))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.7...v) (2022-12-19)


### Features

* Add base option for snapcraft ([#7320](https://github.com/electron-userland/electron-builder/issues/7320)) ([2852cb5](https://github.com/electron-userland/electron-builder/commit/2852cb56a337709f8b7f0bcbf92b034ec8a07e7f))
* Add the accelerate option for s3 buckets ([#7314](https://github.com/electron-userland/electron-builder/issues/7314)) ([cc1ddab](https://github.com/electron-userland/electron-builder/commit/cc1ddabd45f239ee06fde9b2d1534467908791fa))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.6...v) (2022-12-10)


### Features

* integrating @electron/notarize into mac signing flow ([#7310](https://github.com/electron-userland/electron-builder/issues/7310)) ([00d0dbc](https://github.com/electron-userland/electron-builder/commit/00d0dbc2d74fbac3e9ce7a046427c1e1d9a11301))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.5...v) (2022-12-07)



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.4...v) (2022-12-01)


### Bug Fixes

* **app-builder-lib:** export missing TS types ([#7297](https://github.com/electron-userland/electron-builder/issues/7297)) ([9ce7448](https://github.com/electron-userland/electron-builder/commit/9ce74482ef0f4abc1206dc96dca559eb9f03d50c))


### Features

* Introducing deb and rpm auto-updates ([#7060](https://github.com/electron-userland/electron-builder/issues/7060)) ([1d13001](https://github.com/electron-userland/electron-builder/commit/1d130012737e77b57c8923fcc0e6ad2cbc5da0e8))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.3...v) (2022-11-22)


### Bug Fixes

* get CI tag in GitHub Actions ([#7231](https://github.com/electron-userland/electron-builder/issues/7231)) ([c21e3b3](https://github.com/electron-userland/electron-builder/commit/c21e3b37e0dd064c12dbd38065a548441d7c5a9e))
* support powershell constrained language mode ([#7230](https://github.com/electron-userland/electron-builder/issues/7230)) ([346af1d](https://github.com/electron-userland/electron-builder/commit/346af1d470ebbf12733a9619a2389bcfdf452bc6))
* windowsCodeSign - don't use osslsigncode in a vm! ([#7275](https://github.com/electron-userland/electron-builder/issues/7275)) ([5668dc2](https://github.com/electron-userland/electron-builder/commit/5668dc204b83ae0c1edf79a4998f41292007d230))


### Features

* **nsis:** add ShutdownBlockReasonCreate for blocking Win Shutdown prompt ([#7251](https://github.com/electron-userland/electron-builder/issues/7251)) ([45a0f82](https://github.com/electron-userland/electron-builder/commit/45a0f82ac3a14fedfb03880fb43d525a51cec864))



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.2...v) (2022-11-01)



# [](https://github.com/electron-userland/electron-builder/compare/v24.0.0-alpha.1...v) (2022-10-26)


### Bug Fixes

* properly configure electron-rebuild for monorepos ([#7215](https://github.com/electron-userland/electron-builder/issues/7215)) ([0d3b87f](https://github.com/electron-userland/electron-builder/commit/0d3b87f7b89eb2e8f43613acec0e7e057bca88ab))



# [](https://github.com/electron-userland/electron-builder/compare/v23.6.0...v) (2022-10-21)


### Bug Fixes

* Allow non-semver versions in getVersionInWeirdWindowsForm ([#7174](https://github.com/electron-userland/electron-builder/issues/7174)) ([0f9865d](https://github.com/electron-userland/electron-builder/commit/0f9865dc0775f9d80d3bd64cf3e2131be3ae9acb)), closes [#7173](https://github.com/electron-userland/electron-builder/issues/7173)
* Migrate to electron-rebuild for handling native dependencies to fix compatibility with newer versions of electron ([#7196](https://github.com/electron-userland/electron-builder/issues/7196)) ([5616f23](https://github.com/electron-userland/electron-builder/commit/5616f23ce3d03a4e71c7b7bd515ec958b1631b8b))
* use proper cache directory for `electron-updater` on macOS ([#7032](https://github.com/electron-userland/electron-builder/issues/7032)) ([caa32e0](https://github.com/electron-userland/electron-builder/commit/caa32e0708ba4347dd37e93174fce1d2c5660160))


### Features

* enabling support for typescript config files (i.e. electron-builder.ts) ([#7180](https://github.com/electron-userland/electron-builder/issues/7180)) ([edb28c0](https://github.com/electron-userland/electron-builder/commit/edb28c093ab251470e9f1579cd58b4f2ed89e21d))
* Extending `linux` executableArgs option to be utilized for Snap target (fixes [#4587](https://github.com/electron-userland/electron-builder/issues/4587)) ([#7198](https://github.com/electron-userland/electron-builder/issues/7198)) ([a2ce9a7](https://github.com/electron-userland/electron-builder/commit/a2ce9a77c04868e9c01ad76b10955499f1f42eb3))



# [](https://github.com/electron-userland/electron-builder/compare/v23.6.0...v) (2022-10-21)


### Bug Fixes

* Migrate to electron-rebuild for handling native dependencies to fix compatibility with newer versions of electron ([#7196](https://github.com/electron-userland/electron-builder/issues/7196)) ([5616f23](https://github.com/electron-userland/electron-builder/commit/5616f23ce3d03a4e71c7b7bd515ec958b1631b8b))
* use proper cache directory for `electron-updater` on macOS ([#7032](https://github.com/electron-userland/electron-builder/issues/7032)) ([caa32e0](https://github.com/electron-userland/electron-builder/commit/caa32e0708ba4347dd37e93174fce1d2c5660160))


### Features

* enabling support for typescript config files (i.e. electron-builder.ts) ([#7180](https://github.com/electron-userland/electron-builder/issues/7180)) ([edb28c0](https://github.com/electron-userland/electron-builder/commit/edb28c093ab251470e9f1579cd58b4f2ed89e21d))
* Extending `linux` executableArgs option to be utilized for Snap target (fixes [#4587](https://github.com/electron-userland/electron-builder/issues/4587)) ([#7198](https://github.com/electron-userland/electron-builder/issues/7198)) ([a2ce9a7](https://github.com/electron-userland/electron-builder/commit/a2ce9a77c04868e9c01ad76b10955499f1f42eb3))



# [](https://github.com/electron-userland/electron-builder/compare/v23.5.1...v) (2022-10-03)


### Bug Fixes

* **ci:** GitHub Workflows security hardening ([#7156](https://github.com/electron-userland/electron-builder/issues/7156)) ([50d126e](https://github.com/electron-userland/electron-builder/commit/50d126e43de83e4bb4e6e2c700ddca6a4dbef569))
* formatting of Code in the MacOS PKG docs ([#7142](https://github.com/electron-userland/electron-builder/issues/7142)) ([9338097](https://github.com/electron-userland/electron-builder/commit/9338097a9f6754dee8d87185154eaa7d9cffdec8))


### Features

* add Github Actions environment variable to isPullRequest method ([#7152](https://github.com/electron-userland/electron-builder/issues/7152)) ([4583273](https://github.com/electron-userland/electron-builder/commit/4583273ebe5cabfd1c14f647dc9edb7bff3c3bf3))
* add nsis option `removeDefaultUninstallWelcomePage` to remove the default uninstall welcome page ([#7141](https://github.com/electron-userland/electron-builder/issues/7141)) ([d71a579](https://github.com/electron-userland/electron-builder/commit/d71a5790a94cd56b6e033b656b4892ec31f14b9d))
* add option for quitAndInstall for non-silent update without restart ([#7136](https://github.com/electron-userland/electron-builder/issues/7136)) ([4d989a8](https://github.com/electron-userland/electron-builder/commit/4d989a8a52bf7baac22742769abcc795ce193fbd))



# [](https://github.com/electron-userland/electron-builder/compare/v23.5.0...v) (2022-09-08)


### Bug Fixes

* allow CSC_LINK to have a mime-type prefix before extracting it to a p12 ([#7119](https://github.com/electron-userland/electron-builder/issues/7119)) ([323618f](https://github.com/electron-userland/electron-builder/commit/323618f79108a8bb829dc1e84e933ace90940010))
* **docs:** typo of docs/generated/NsisOptions.md ([#7120](https://github.com/electron-userland/electron-builder/issues/7120)) ([740c411](https://github.com/electron-userland/electron-builder/commit/740c41146f875feaa730d18f8353b11416dab1e0))
* Revert "feat: Upgrade to Ubuntu 22.04 and python 3.10" ([#7109](https://github.com/electron-userland/electron-builder/issues/7109)) ([7d606af](https://github.com/electron-userland/electron-builder/commit/7d606aff59c964dc0af93c0f235abb0f3e258dea))
* strip extra fields out that are not allowed when creating snap.yaml ([#7104](https://github.com/electron-userland/electron-builder/issues/7104)) ([#7110](https://github.com/electron-userland/electron-builder/issues/7110)) ([0a7025e](https://github.com/electron-userland/electron-builder/commit/0a7025e5184e3333d077db1f7e782d6a768ecdea))


### Features

* Allow the AppUpdater to be forced into dev mode, allowing it to be activated when the app is not packaged ([#7117](https://github.com/electron-userland/electron-builder/issues/7117)) ([0c52841](https://github.com/electron-userland/electron-builder/commit/0c528411fb8a7de23e974f44e36c5e69bd3bb167))



# [](https://github.com/electron-userland/electron-builder/compare/v23.4.0...v) (2022-08-31)


### Bug Fixes

* allow user to define explicit `buildNumber` in config, useful for fpm `--iteration` flag ([#7075](https://github.com/electron-userland/electron-builder/issues/7075)) ([8166267](https://github.com/electron-userland/electron-builder/commit/8166267d487cd26b154e28cf60d89102a487a353))
* close file stream when error in httpExecutor ([#7094](https://github.com/electron-userland/electron-builder/issues/7094)) ([1023a93](https://github.com/electron-userland/electron-builder/commit/1023a93e92eaa26bf33b52edda5b22e56ed1ec18))
* improve `downloadUpdate` typing to match the doc ([#7099](https://github.com/electron-userland/electron-builder/issues/7099)) ([cd21b09](https://github.com/electron-userland/electron-builder/commit/cd21b0918843fe1269ddaf8dde099c8faeb54b80))
* Invalid code signing for MAS build due to ordering of certificate check ([#7040](https://github.com/electron-userland/electron-builder/issues/7040)) ([#7089](https://github.com/electron-userland/electron-builder/issues/7089)) ([a1d86fd](https://github.com/electron-userland/electron-builder/commit/a1d86fd75bbc7b252403c16966430a2e3562205d))
* replace update-notifier with simple-update notifier due to dependency vulnerability ([#7078](https://github.com/electron-userland/electron-builder/issues/7078)) ([48cbb12](https://github.com/electron-userland/electron-builder/commit/48cbb120dc11994889f4aa61c8431531ce274006))
* updating integration test for prerelease flag ([#7072](https://github.com/electron-userland/electron-builder/issues/7072)) ([f205998](https://github.com/electron-userland/electron-builder/commit/f205998999ff615c9ea63184520a1efbbff5a785))



# [](https://github.com/electron-userland/electron-builder/compare/v23.3.3...v) (2022-07-28)


### Features

* Adding timeout to publisher config for api requests and uploads ([#7028](https://github.com/electron-userland/electron-builder/issues/7028)) ([e7179b5](https://github.com/electron-userland/electron-builder/commit/e7179b57bdba192acfdb439c03099e6629e98f6a))



# [](https://github.com/electron-userland/electron-builder/compare/v23.3.2...v) (2022-07-21)


### Bug Fixes

* Duplicate values during deep assign of extra files ([#7019](https://github.com/electron-userland/electron-builder/issues/7019)) ([98d3a63](https://github.com/electron-userland/electron-builder/commit/98d3a6361d500e85e443ee292529c27f0b4a0b59))



# [](https://github.com/electron-userland/electron-builder/compare/v23.3.1...v) (2022-07-16)


### Bug Fixes

* **electron-updater:** fix backward compatibility for GitHub provider without channels ([#6998](https://github.com/electron-userland/electron-builder/issues/6998)) ([d6115bc](https://github.com/electron-userland/electron-builder/commit/d6115bc5d066d6eee2638015be0c804b31ffcc18))
* Wrap the nsProcess include in a !ifndef ([#6996](https://github.com/electron-userland/electron-builder/issues/6996)) ([5301525](https://github.com/electron-userland/electron-builder/commit/53015253939f450468a6d8e0405697ea70c2a138))



# [](https://github.com/electron-userland/electron-builder/compare/v23.3.0...v) (2022-07-07)


### Bug Fixes

* add product scope to keygen publisher ([#6990](https://github.com/electron-userland/electron-builder/issues/6990)) ([c3407a2](https://github.com/electron-userland/electron-builder/commit/c3407a202d4dc1599b2cb90a7ff3d56e8e32309e))
* parallel release creation with keygen publisher ([#6989](https://github.com/electron-userland/electron-builder/issues/6989)) ([7ad5101](https://github.com/electron-userland/electron-builder/commit/7ad5101b4a72df411b76cc500a6a0dca85bf6540))


### Features

* Add installDir property for NsisUpdater ([#6907](https://github.com/electron-userland/electron-builder/issues/6907)) ([e7f2867](https://github.com/electron-userland/electron-builder/commit/e7f286776643823f9c906738aade1d71eb1bdd9c))



# [](https://github.com/electron-userland/electron-builder/compare/v23.2.0...v) (2022-07-04)


### Bug Fixes

* add product scope to keygen provider ([#6975](https://github.com/electron-userland/electron-builder/issues/6975)) ([8279d05](https://github.com/electron-userland/electron-builder/commit/8279d053d520e7506d84bf9710972b998e70b752))
* automatically regenerate schema if any config option changes in app-builder-lib ([51f5d49](https://github.com/electron-userland/electron-builder/commit/51f5d4915c4aa69f3253a41e1d7b4ab9f2328732))
* **mac:** allow Mac Developer certs for non Mac App Store builds ([#6956](https://github.com/electron-userland/electron-builder/issues/6956)) ([4e90504](https://github.com/electron-userland/electron-builder/commit/4e905046e632b396735b78618fbc01331448f088)), closes [#6564](https://github.com/electron-userland/electron-builder/issues/6564)
* **mas:** Allow signing with "3rd Party Mac Developer Application" ([#6970](https://github.com/electron-userland/electron-builder/issues/6970)) ([28c07b4](https://github.com/electron-userland/electron-builder/commit/28c07b4392161732ee221dbb3f3a3633899cfa33))
* nsis-web target set APP_PACKAGE_URL_IS_INCOMPLETE when specifying appPackageUrl ([#6964](https://github.com/electron-userland/electron-builder/issues/6964)) ([b0e1b6f](https://github.com/electron-userland/electron-builder/commit/b0e1b6f8af95bc371c0bc91df65965f3f60f3a87))
* **nsis:** fix typo in German installer message ([#6960](https://github.com/electron-userland/electron-builder/issues/6960)) ([6e90c84](https://github.com/electron-userland/electron-builder/commit/6e90c8459111ec046b91f8ae5da1990af0bbe942))
* Optionally remove DISABLE_WAYLAND for snaps via allowNativeWayland option ([#6961](https://github.com/electron-userland/electron-builder/issues/6961)) ([4c867aa](https://github.com/electron-userland/electron-builder/commit/4c867aa017a7ce2bf88138634b6d1e9a3bf34854))
* prevent infinite looping of overwriteArtifact during Github publishing ([#6958](https://github.com/electron-userland/electron-builder/issues/6958)) ([8ffd9d4](https://github.com/electron-userland/electron-builder/commit/8ffd9d42d89634be76fd4554f659f2b2512f2081))
* regenerating docs and schema ([f70abf1](https://github.com/electron-userland/electron-builder/commit/f70abf1628223e1cc0d687471ad36b4a2ee66ebe))
* regenerating schema to account for electron-universal options `x64ArchFiles` ([#6983](https://github.com/electron-userland/electron-builder/issues/6983)) ([adeaa34](https://github.com/electron-userland/electron-builder/commit/adeaa347c03b8947b0812ecef23398c0822646bb))


### Features

* upgrade keygen integration to v1.1 ([#6941](https://github.com/electron-userland/electron-builder/issues/6941)) ([14503ce](https://github.com/electron-userland/electron-builder/commit/14503ceb99c1a31c54a261a1ae60a34980f36a50))



# [](https://github.com/electron-userland/electron-builder/compare/v23.1.0...v) (2022-06-17)


### Bug Fixes

* pin Keygen.io integration to v1.0 ([#6909](https://github.com/electron-userland/electron-builder/issues/6909)) ([0b6db59](https://github.com/electron-userland/electron-builder/commit/0b6db59ec10dfe05903f29d6790972f55746bef7))


### Features

* electron/universal has a new minimatch option 'x64ArchFiles' ([#6913](https://github.com/electron-userland/electron-builder/issues/6913)) ([f3a56ef](https://github.com/electron-userland/electron-builder/commit/f3a56ef6f8132e0a7cc18ec58d1d6103683916dd))
* Upgrade docker images to Ubuntu 22.04 and python 3.10 ([#6922](https://github.com/electron-userland/electron-builder/issues/6922)) ([03cc9b9](https://github.com/electron-userland/electron-builder/commit/03cc9b96e0be07ef3450e3992eafcb7fe903a853))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.9...v) (2022-05-29)


### Bug Fixes

* moving typed-emitter from devDependency to dependencies ([#6889](https://github.com/electron-userland/electron-builder/issues/6889)) ([869ec27](https://github.com/electron-userland/electron-builder/commit/869ec27fd1d99b9913875cb4d7ae7c733c1f3e25))
* **msi:** manually escape XML special characters when building project.wxs XML ([#6878](https://github.com/electron-userland/electron-builder/issues/6878)) ([2ece89a](https://github.com/electron-userland/electron-builder/commit/2ece89a08e7fb74a11ba3d0f5980b2a57c8b34ad))
* **nsis:** new translations for various strings in nsis messages template ([#6827](https://github.com/electron-userland/electron-builder/issues/6827)) ([fa72861](https://github.com/electron-userland/electron-builder/commit/fa72861f6cd2de97d191f1b2bbfddc6edf48ab6d))


### Features

* add afterPack call after macOS universal package is created ([#6887](https://github.com/electron-userland/electron-builder/issues/6887)) ([4d590d3](https://github.com/electron-userland/electron-builder/commit/4d590d302f6c3baacf9dabf338904fef337960a6))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.8...v) (2022-05-06)


### Bug Fixes

* Add "arm" as an alias for armv7l as process.arch outputs arm on armv7l hosts ([#6845](https://github.com/electron-userland/electron-builder/issues/6845)) ([d3452b0](https://github.com/electron-userland/electron-builder/commit/d3452b0427cb45035f6ed7f1266691db4accd5c4))
* incompatible Windows sign tool in end user environment.  ([#6817](https://github.com/electron-userland/electron-builder/issues/6817)) ([2860d13](https://github.com/electron-userland/electron-builder/commit/2860d132fc837813627e6508e05b18ed5e5dedfc))
* Lock wine version to v6 in docker image ([#6816](https://github.com/electron-userland/electron-builder/issues/6816)) ([8f57a90](https://github.com/electron-userland/electron-builder/commit/8f57a90c885254bf442e7eea5b8f450bd400eac4)), closes [#6780](https://github.com/electron-userland/electron-builder/issues/6780)
* Merge arrays from same config key in cascading electron-builder configs, such as `files` ([#6841](https://github.com/electron-userland/electron-builder/issues/6841)) ([9dc13ba](https://github.com/electron-userland/electron-builder/commit/9dc13ba2c1e7a852d3f743833f1bde17b62f1806))
* rendering extended node_modules in jsdoc ([#6843](https://github.com/electron-userland/electron-builder/issues/6843)) ([481a7ed](https://github.com/electron-userland/electron-builder/commit/481a7ed2b77e7e1b448f27e58fedeac53b107ffc))
* set github release name to match the app version ([#6840](https://github.com/electron-userland/electron-builder/issues/6840)) ([e9ba750](https://github.com/electron-userland/electron-builder/commit/e9ba75005dda39f03c04e37a5d46a1bbe634c189))
* Unable to find latest version on GitHub ([#6822](https://github.com/electron-userland/electron-builder/issues/6822)) ([bfe29a5](https://github.com/electron-userland/electron-builder/commit/bfe29a5e991c2719032877bd7225b15b6b836221))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.7...v) (2022-04-24)


### Bug Fixes

* github provider prerelease check incorrectly casts undefined to String. Fixes [#6809](https://github.com/electron-userland/electron-builder/issues/6809) ([#6810](https://github.com/electron-userland/electron-builder/issues/6810)) ([817e68b](https://github.com/electron-userland/electron-builder/commit/817e68ba54f4fa60fec789fcfcfb527473a610fc))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.6...v) (2022-04-19)


### Bug Fixes

* **nsis:** cleanup temporary 7z folder ([#6793](https://github.com/electron-userland/electron-builder/issues/6793)) ([85a3e55](https://github.com/electron-userland/electron-builder/commit/85a3e5595e64346514dd7f5fade42e3632a18ee0))
* **nsis:** Decide to use elevate.exe for installer when update using nsis packElevateHelper option in electron-builder config ([#6787](https://github.com/electron-userland/electron-builder/issues/6787)) ([eb456a8](https://github.com/electron-userland/electron-builder/commit/eb456a87b0603dcc0e6d777c2b8e1c2e7b64d3a6))


### Features

* Use tar instead of 7zip to preserve file permissions in tar.gz packages ([#6791](https://github.com/electron-userland/electron-builder/issues/6791)) ([95910f8](https://github.com/electron-userland/electron-builder/commit/95910f87195f501eadda95c52cfa8e1816d211b6))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.4...v) (2022-04-13)


### Bug Fixes

* **app-builder-lib:** Overriding OutgoingHttpHeaders schema props ([#6775](https://github.com/electron-userland/electron-builder/issues/6775)) ([e9a87a7](https://github.com/electron-userland/electron-builder/commit/e9a87a738ceb2b9e14cbc85b4c62e11edab3d0cf)), closes [#6635](https://github.com/electron-userland/electron-builder/issues/6635)
* **dmg-builder:** exec python fail on Macos12.3 ([#6789](https://github.com/electron-userland/electron-builder/issues/6789)) ([76f3a1d](https://github.com/electron-userland/electron-builder/commit/76f3a1d102be04c0517a08826b8b1337478f766d))
* **nsis:** Update zh-tw translation ([#6773](https://github.com/electron-userland/electron-builder/issues/6773)) ([5a0bab1](https://github.com/electron-userland/electron-builder/commit/5a0bab115f4ede3f21e23e847c0d2dd7ecc99b16))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.4...v) (2022-04-11)


### Bug Fixes

* **app-builder-lib:** Overriding OutgoingHttpHeaders schema props ([#6775](https://github.com/electron-userland/electron-builder/issues/6775)) ([e9a87a7](https://github.com/electron-userland/electron-builder/commit/e9a87a738ceb2b9e14cbc85b4c62e11edab3d0cf)), closes [#6635](https://github.com/electron-userland/electron-builder/issues/6635)
* **nsis:** Update zh-tw translation ([#6773](https://github.com/electron-userland/electron-builder/issues/6773)) ([5a0bab1](https://github.com/electron-userland/electron-builder/commit/5a0bab115f4ede3f21e23e847c0d2dd7ecc99b16))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.3...v) (2022-04-08)


### Bug Fixes

* **app-builder-lib:** bump @electron/universal to 1.2.1 ([#6750](https://github.com/electron-userland/electron-builder/issues/6750)) ([370f84b](https://github.com/electron-userland/electron-builder/commit/370f84bb2f32f28c374b63e1c795e4850f971274))
* **app-builder-lib:** change slash to backslash in NSIS's APP_PACKAGE_NAME ([#6772](https://github.com/electron-userland/electron-builder/issues/6772)) ([e861352](https://github.com/electron-userland/electron-builder/commit/e86135236908961b1269708ca645a66c7ff19287))
* **nsis:** specify full path to system's find ([#6771](https://github.com/electron-userland/electron-builder/issues/6771)) ([e6c2a62](https://github.com/electron-userland/electron-builder/commit/e6c2a629839184d4f9d3fa99b580d8c96911ea65))
* Updater "Error: Could not connect to the server." in macOS ([#6743](https://github.com/electron-userland/electron-builder/issues/6743)) ([27f18aa](https://github.com/electron-userland/electron-builder/commit/27f18aa1d890f3a82e856f4834b8387066fb697f))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.2...v) (2022-03-19)


### Bug Fixes

* Change DEBUG_LOGGING env var for nsis installers as part of `customNsisBinary` config ([#6729](https://github.com/electron-userland/electron-builder/issues/6729)) ([0a30846](https://github.com/electron-userland/electron-builder/commit/0a308469f269dc5294f29f2c422d9936175c0880)), closes [#6715](https://github.com/electron-userland/electron-builder/issues/6715)
* **docs:** link to SquirrelWindowsOptions in configuration ([#6724](https://github.com/electron-userland/electron-builder/issues/6724)) ([4eaab19](https://github.com/electron-userland/electron-builder/commit/4eaab1936429ac69dafcc7cfbf53caa85c241a11))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.1...v) (2022-03-05)


### Bug Fixes

* **app-builder-lib:** export missing TS types ([#6692](https://github.com/electron-userland/electron-builder/issues/6692)) ([93181a7](https://github.com/electron-userland/electron-builder/commit/93181a78f2893ea4929aea8878343336931b3a04))
* Reactivating bitbucket integration test for nsis updater ([#6680](https://github.com/electron-userland/electron-builder/issues/6680)) ([6fcd477](https://github.com/electron-userland/electron-builder/commit/6fcd47767af8a95ab018fe0d8a07d2c53a72067d))
* **win:** Include swiftshader in signing directories for windows ([#6682](https://github.com/electron-userland/electron-builder/issues/6682)) ([e6312cb](https://github.com/electron-userland/electron-builder/commit/e6312cb54e5d957289d5c07b506491fcaea9e334))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.0...v) (2022-02-25)


### Bug Fixes

* **dmg-builder:** the "import" unbound issue for python 2/3 ([#6672](https://github.com/electron-userland/electron-builder/issues/6672)) ([3a4b64a](https://github.com/electron-userland/electron-builder/commit/3a4b64abb58f01e8a80e496b6c4681455b2434ca))
* signing of user-defined binaries on mac when resolved as relative path ([#6660](https://github.com/electron-userland/electron-builder/issues/6660)) ([4c6d154](https://github.com/electron-userland/electron-builder/commit/4c6d1546d4942aa9d9a93b7309e8ed279f6378d2))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.0-alpha.4...v) (2022-02-19)



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.0-alpha.3...v) (2022-02-17)


### Bug Fixes

* **packager:** wait for artifactCreated completion event before starting an upload ([#6625](https://github.com/electron-userland/electron-builder/issues/6625)) ([c561af8](https://github.com/electron-userland/electron-builder/commit/c561af810d5de52bec57709cbaebca2ac92c55fc))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.0-alpha.2...v) (2022-02-06)


### Bug Fixes

* **dmg-builder:** Support python 3 since python 2 was removed from MacOS 12.3 ([#6617](https://github.com/electron-userland/electron-builder/issues/6617)) ([2def112](https://github.com/electron-userland/electron-builder/commit/2def112bc1ac42046b921206825871b82ebf0955)), closes [#6606](https://github.com/electron-userland/electron-builder/issues/6606)
* **docs:** Fixing formatting of code groups and previews ([#6601](https://github.com/electron-userland/electron-builder/issues/6601)) ([b01d522](https://github.com/electron-userland/electron-builder/commit/b01d5225631115f6f301cb113b044fd10ebb5256)), closes [#6597](https://github.com/electron-userland/electron-builder/issues/6597) [#6574](https://github.com/electron-userland/electron-builder/issues/6574)
* fixes for server auth for MacUpdater ([#6587](https://github.com/electron-userland/electron-builder/issues/6587)) ([8746f91](https://github.com/electron-userland/electron-builder/commit/8746f910d136fb9b531e688d0a646eeb9528adc6))
* **updater:** Remove checks for app-update.yml when auto-updates are not supported ([#6616](https://github.com/electron-userland/electron-builder/issues/6616)) ([86e6d15](https://github.com/electron-userland/electron-builder/commit/86e6d1509f9b9c76c559e9c3a12b7a1595fe3ac4)), closes [#6322](https://github.com/electron-userland/electron-builder/issues/6322)
* **updater:** Support Electron 11 and below (Node < 14) ([#6594](https://github.com/electron-userland/electron-builder/issues/6594)) ([edc4b03](https://github.com/electron-userland/electron-builder/commit/edc4b030703ee3929b31608a496798635169f5b1)), closes [#6000](https://github.com/electron-userland/electron-builder/issues/6000)
* **win/mac:** Small security fixes for electron-updater ([#6589](https://github.com/electron-userland/electron-builder/issues/6589)) ([633ee5d](https://github.com/electron-userland/electron-builder/commit/633ee5dc292174ed1486c53af93320f20cf02169))


### Features

* **updater:** Add Channel Support for Github with PreRelease ([#6505](https://github.com/electron-userland/electron-builder/issues/6505)) ([#1722](https://github.com/electron-userland/electron-builder/issues/1722)) ([#4988](https://github.com/electron-userland/electron-builder/issues/4988)) ([1de0adb](https://github.com/electron-userland/electron-builder/commit/1de0adbd615b3b3d26faeb6a449f522355b36041))



# [](https://github.com/electron-userland/electron-builder/compare/v23.0.0-alpha.2...v) (2022-01-31)


### Bug Fixes

* fixes for server auth for MacUpdater ([#6587](https://github.com/electron-userland/electron-builder/issues/6587)) ([8746f91](https://github.com/electron-userland/electron-builder/commit/8746f910d136fb9b531e688d0a646eeb9528adc6))
* **updater:** Support Electron 11 and below (Node < 14) ([#6594](https://github.com/electron-userland/electron-builder/issues/6594)) ([edc4b03](https://github.com/electron-userland/electron-builder/commit/edc4b030703ee3929b31608a496798635169f5b1)), closes [#6000](https://github.com/electron-userland/electron-builder/issues/6000)
* **win/mac:** Small security fixes for electron-updater ([#6589](https://github.com/electron-userland/electron-builder/issues/6589)) ([633ee5d](https://github.com/electron-userland/electron-builder/commit/633ee5dc292174ed1486c53af93320f20cf02169))


### Features

* **updater:** Add Channel Support for Github with PreRelease ([#6505](https://github.com/electron-userland/electron-builder/issues/6505)) ([#1722](https://github.com/electron-userland/electron-builder/issues/1722)) ([#4988](https://github.com/electron-userland/electron-builder/issues/4988)) ([1de0adb](https://github.com/electron-userland/electron-builder/commit/1de0adbd615b3b3d26faeb6a449f522355b36041))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.12...v) (2022-01-28)


### Bug Fixes

* Allow disabling of webinstaller files to avoid confusion with actual installers ([#6575](https://github.com/electron-userland/electron-builder/issues/6575)) ([5e381c5](https://github.com/electron-userland/electron-builder/commit/5e381c556d12ce185bb7ea720380509c1ddc5cf7))
* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* **electron-publish:** socket hang up error 422 issues in github publish ([#6563](https://github.com/electron-userland/electron-builder/issues/6563)) ([39da9ed](https://github.com/electron-userland/electron-builder/commit/39da9edd2df5c147ef2d868f022484a8b2e0466a))
* fixes for server auth for MacUpdater ([#6587](https://github.com/electron-userland/electron-builder/issues/6587)) ([8746f91](https://github.com/electron-userland/electron-builder/commit/8746f910d136fb9b531e688d0a646eeb9528adc6))
* **NSIS:** prevent partial overwrites during `Nsis7z::Extract` ([#6547](https://github.com/electron-userland/electron-builder/issues/6547)) ([bea51d6](https://github.com/electron-userland/electron-builder/commit/bea51d6a8bb828d9b34734908f13b667aa55b0e9))
* **nsis:** use revertible+atomic rmdir on update and add user-confirmed retry loop ([#6551](https://github.com/electron-userland/electron-builder/issues/6551)) ([7b2a5e1](https://github.com/electron-userland/electron-builder/commit/7b2a5e1f19921e9da4aaaea8c01c78740f29f9dd))
* skip unstable installer tests to unblock master CI pipeline ([#6544](https://github.com/electron-userland/electron-builder/issues/6544)) ([5648e05](https://github.com/electron-userland/electron-builder/commit/5648e05a9efa61f81e788ecf538a617df9f65fe1))
* Stub CircleCI config since we can't disable it from dashboard ([#6543](https://github.com/electron-userland/electron-builder/issues/6543)) ([22fb8c6](https://github.com/electron-userland/electron-builder/commit/22fb8c63ac196c61c6b449e6e5e95d91117f8894))
* Update certificate validation on Windows to check full DN ([#6576](https://github.com/electron-userland/electron-builder/issues/6576)) ([53467c7](https://github.com/electron-userland/electron-builder/commit/53467c724dacc11fc270cebaba22f8cf84dff24f))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))


### chore

* v23.0.0 alpha ([#6556](https://github.com/electron-userland/electron-builder/issues/6556)) ([a138a86](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)), closes [#4898](https://github.com/electron-userland/electron-builder/issues/4898) [#6232](https://github.com/electron-userland/electron-builder/issues/6232) [#6259](https://github.com/electron-userland/electron-builder/issues/6259) [#6511](https://github.com/electron-userland/electron-builder/issues/6511) [#6506](https://github.com/electron-userland/electron-builder/issues/6506) [#6507](https://github.com/electron-userland/electron-builder/issues/6507) [#6514](https://github.com/electron-userland/electron-builder/issues/6514) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#3683](https://github.com/electron-userland/electron-builder/issues/3683) [#6201](https://github.com/electron-userland/electron-builder/issues/6201) [#6530](https://github.com/electron-userland/electron-builder/issues/6530) [#6550](https://github.com/electron-userland/electron-builder/issues/6550)


### Features

* **updater:** Add Channel Support for Github with PreRelease ([#6505](https://github.com/electron-userland/electron-builder/issues/6505)) ([#1722](https://github.com/electron-userland/electron-builder/issues/1722)) ([#4988](https://github.com/electron-userland/electron-builder/issues/4988)) ([1de0adb](https://github.com/electron-userland/electron-builder/commit/1de0adbd615b3b3d26faeb6a449f522355b36041))
* use `mergeASARs` API by @electron/universal ([#6578](https://github.com/electron-userland/electron-builder/issues/6578)) ([81132a8](https://github.com/electron-userland/electron-builder/commit/81132a857b24bfdb01fc44eba75fc89fa2885545))


### BREAKING CHANGES

* Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/

* fix: force strip path separators for backslashes on Windows

* fix: Force authentication for local Mac Squirrel update server
* Fail-fast for signature verification failures. Adding `-LiteralPath` to update file for injected wildcards

* Adding changeset and eslint

* Fix error: `-OUTPUTCHARSET is disabled for non Win32 platforms.`
* Admins using advertisement must apply an MST to re-enable it. See #6508.
* remove MSI option `iconId`

* fix: stabilizing tests by moving updater tests to its own node to explicitly segment env.___TOKEN integration tests from other standard unit tests

* chore: synchronizing docs and schema plus prettier

* Adding changset to set as alpha

* Updating changeset documentation



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.12...v) (2022-01-26)


### Bug Fixes

* Allow disabling of webinstaller files to avoid confusion with actual installers ([#6575](https://github.com/electron-userland/electron-builder/issues/6575)) ([5e381c5](https://github.com/electron-userland/electron-builder/commit/5e381c556d12ce185bb7ea720380509c1ddc5cf7))
* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* **electron-publish:** socket hang up error 422 issues in github publish ([#6563](https://github.com/electron-userland/electron-builder/issues/6563)) ([39da9ed](https://github.com/electron-userland/electron-builder/commit/39da9edd2df5c147ef2d868f022484a8b2e0466a))
* **NSIS:** prevent partial overwrites during `Nsis7z::Extract` ([#6547](https://github.com/electron-userland/electron-builder/issues/6547)) ([bea51d6](https://github.com/electron-userland/electron-builder/commit/bea51d6a8bb828d9b34734908f13b667aa55b0e9))
* **nsis:** use revertible+atomic rmdir on update and add user-confirmed retry loop ([#6551](https://github.com/electron-userland/electron-builder/issues/6551)) ([7b2a5e1](https://github.com/electron-userland/electron-builder/commit/7b2a5e1f19921e9da4aaaea8c01c78740f29f9dd))
* skip unstable installer tests to unblock master CI pipeline ([#6544](https://github.com/electron-userland/electron-builder/issues/6544)) ([5648e05](https://github.com/electron-userland/electron-builder/commit/5648e05a9efa61f81e788ecf538a617df9f65fe1))
* Stub CircleCI config since we can't disable it from dashboard ([#6543](https://github.com/electron-userland/electron-builder/issues/6543)) ([22fb8c6](https://github.com/electron-userland/electron-builder/commit/22fb8c63ac196c61c6b449e6e5e95d91117f8894))
* Update certificate validation on Windows to check full DN ([#6576](https://github.com/electron-userland/electron-builder/issues/6576)) ([53467c7](https://github.com/electron-userland/electron-builder/commit/53467c724dacc11fc270cebaba22f8cf84dff24f))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))


### chore

* v23.0.0 alpha ([#6556](https://github.com/electron-userland/electron-builder/issues/6556)) ([a138a86](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)), closes [#4898](https://github.com/electron-userland/electron-builder/issues/4898) [#6232](https://github.com/electron-userland/electron-builder/issues/6232) [#6259](https://github.com/electron-userland/electron-builder/issues/6259) [#6511](https://github.com/electron-userland/electron-builder/issues/6511) [#6506](https://github.com/electron-userland/electron-builder/issues/6506) [#6507](https://github.com/electron-userland/electron-builder/issues/6507) [#6514](https://github.com/electron-userland/electron-builder/issues/6514) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#3683](https://github.com/electron-userland/electron-builder/issues/3683) [#6201](https://github.com/electron-userland/electron-builder/issues/6201) [#6530](https://github.com/electron-userland/electron-builder/issues/6530) [#6550](https://github.com/electron-userland/electron-builder/issues/6550)


### Features

* use `mergeASARs` API by @electron/universal ([#6578](https://github.com/electron-userland/electron-builder/issues/6578)) ([81132a8](https://github.com/electron-userland/electron-builder/commit/81132a857b24bfdb01fc44eba75fc89fa2885545))


### BREAKING CHANGES

* Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/

* fix: force strip path separators for backslashes on Windows

* fix: Force authentication for local Mac Squirrel update server
* Fail-fast for signature verification failures. Adding `-LiteralPath` to update file for injected wildcards

* Adding changeset and eslint

* Fix error: `-OUTPUTCHARSET is disabled for non Win32 platforms.`
* Admins using advertisement must apply an MST to re-enable it. See #6508.
* remove MSI option `iconId`

* fix: stabilizing tests by moving updater tests to its own node to explicitly segment env.___TOKEN integration tests from other standard unit tests

* chore: synchronizing docs and schema plus prettier

* Adding changset to set as alpha

* Updating changeset documentation



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.12...v) (2022-01-19)


### Bug Fixes

* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* **electron-publish:** socket hang up error 422 issues in github publish ([#6563](https://github.com/electron-userland/electron-builder/issues/6563)) ([39da9ed](https://github.com/electron-userland/electron-builder/commit/39da9edd2df5c147ef2d868f022484a8b2e0466a))
* **NSIS:** prevent partial overwrites during `Nsis7z::Extract` ([#6547](https://github.com/electron-userland/electron-builder/issues/6547)) ([bea51d6](https://github.com/electron-userland/electron-builder/commit/bea51d6a8bb828d9b34734908f13b667aa55b0e9))
* **nsis:** use revertible+atomic rmdir on update and add user-confirmed retry loop ([#6551](https://github.com/electron-userland/electron-builder/issues/6551)) ([7b2a5e1](https://github.com/electron-userland/electron-builder/commit/7b2a5e1f19921e9da4aaaea8c01c78740f29f9dd))
* skip unstable installer tests to unblock master CI pipeline ([#6544](https://github.com/electron-userland/electron-builder/issues/6544)) ([5648e05](https://github.com/electron-userland/electron-builder/commit/5648e05a9efa61f81e788ecf538a617df9f65fe1))
* Stub CircleCI config since we can't disable it from dashboard ([#6543](https://github.com/electron-userland/electron-builder/issues/6543)) ([22fb8c6](https://github.com/electron-userland/electron-builder/commit/22fb8c63ac196c61c6b449e6e5e95d91117f8894))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))


### chore

* v23.0.0 alpha ([#6556](https://github.com/electron-userland/electron-builder/issues/6556)) ([a138a86](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)), closes [#4898](https://github.com/electron-userland/electron-builder/issues/4898) [#6232](https://github.com/electron-userland/electron-builder/issues/6232) [#6259](https://github.com/electron-userland/electron-builder/issues/6259) [#6511](https://github.com/electron-userland/electron-builder/issues/6511) [#6506](https://github.com/electron-userland/electron-builder/issues/6506) [#6507](https://github.com/electron-userland/electron-builder/issues/6507) [#6514](https://github.com/electron-userland/electron-builder/issues/6514) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#3683](https://github.com/electron-userland/electron-builder/issues/3683) [#6201](https://github.com/electron-userland/electron-builder/issues/6201) [#6530](https://github.com/electron-userland/electron-builder/issues/6530) [#6550](https://github.com/electron-userland/electron-builder/issues/6550)


### BREAKING CHANGES

* Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/

* fix: force strip path separators for backslashes on Windows

* fix: Force authentication for local Mac Squirrel update server
* Fail-fast for signature verification failures. Adding `-LiteralPath` to update file for injected wildcards

* Adding changeset and eslint

* Fix error: `-OUTPUTCHARSET is disabled for non Win32 platforms.`
* Admins using advertisement must apply an MST to re-enable it. See #6508.
* remove MSI option `iconId`

* fix: stabilizing tests by moving updater tests to its own node to explicitly segment env.___TOKEN integration tests from other standard unit tests

* chore: synchronizing docs and schema plus prettier

* Adding changset to set as alpha

* Updating changeset documentation



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.12...v) (2022-01-17)


### Bug Fixes

* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* **NSIS:** prevent partial overwrites during `Nsis7z::Extract` ([#6547](https://github.com/electron-userland/electron-builder/issues/6547)) ([bea51d6](https://github.com/electron-userland/electron-builder/commit/bea51d6a8bb828d9b34734908f13b667aa55b0e9))
* **nsis:** use revertible+atomic rmdir on update and add user-confirmed retry loop ([#6551](https://github.com/electron-userland/electron-builder/issues/6551)) ([7b2a5e1](https://github.com/electron-userland/electron-builder/commit/7b2a5e1f19921e9da4aaaea8c01c78740f29f9dd))
* skip unstable installer tests to unblock master CI pipeline ([#6544](https://github.com/electron-userland/electron-builder/issues/6544)) ([5648e05](https://github.com/electron-userland/electron-builder/commit/5648e05a9efa61f81e788ecf538a617df9f65fe1))
* Stub CircleCI config since we can't disable it from dashboard ([#6543](https://github.com/electron-userland/electron-builder/issues/6543)) ([22fb8c6](https://github.com/electron-userland/electron-builder/commit/22fb8c63ac196c61c6b449e6e5e95d91117f8894))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))


### chore

* v23.0.0 alpha ([#6556](https://github.com/electron-userland/electron-builder/issues/6556)) ([a138a86](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)), closes [#4898](https://github.com/electron-userland/electron-builder/issues/4898) [#6232](https://github.com/electron-userland/electron-builder/issues/6232) [#6259](https://github.com/electron-userland/electron-builder/issues/6259) [#6511](https://github.com/electron-userland/electron-builder/issues/6511) [#6506](https://github.com/electron-userland/electron-builder/issues/6506) [#6507](https://github.com/electron-userland/electron-builder/issues/6507) [#6514](https://github.com/electron-userland/electron-builder/issues/6514) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#6508](https://github.com/electron-userland/electron-builder/issues/6508) [#3683](https://github.com/electron-userland/electron-builder/issues/3683) [#6201](https://github.com/electron-userland/electron-builder/issues/6201) [#6530](https://github.com/electron-userland/electron-builder/issues/6530) [#6550](https://github.com/electron-userland/electron-builder/issues/6550)


### BREAKING CHANGES

* Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/

* fix: force strip path separators for backslashes on Windows

* fix: Force authentication for local Mac Squirrel update server
* Fail-fast for signature verification failures. Adding `-LiteralPath` to update file for injected wildcards

* Adding changeset and eslint

* Fix error: `-OUTPUTCHARSET is disabled for non Win32 platforms.`
* Admins using advertisement must apply an MST to re-enable it. See #6508.
* remove MSI option `iconId`

* fix: stabilizing tests by moving updater tests to its own node to explicitly segment env.___TOKEN integration tests from other standard unit tests

* chore: synchronizing docs and schema plus prettier

* Adding changset to set as alpha

* Updating changeset documentation



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.12...v) (2022-01-11)


### Bug Fixes

* **docs:** Update link for "Desktop File" ([#6532](https://github.com/electron-userland/electron-builder/issues/6532)) ([cd79c53](https://github.com/electron-userland/electron-builder/commit/cd79c53828759cf19cd361a48ef6fd57fff0e2f1))
* use junction in windows to solve Error: EPERM: operation not per… ([#6529](https://github.com/electron-userland/electron-builder/issues/6529)) ([f7b3869](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.11...v) (2021-12-31)


### Bug Fixes

* add warning to macCodeSign when skipping code signing on M1 macOS device ([#6522](https://github.com/electron-userland/electron-builder/issues/6522)) ([8730027](https://github.com/electron-userland/electron-builder/commit/87300278d24e8304caa4b053b883843a2447dab2))
* specify protocol as https to complete proxy support fix ([#6516](https://github.com/electron-userland/electron-builder/issues/6516)) ([344bb23](https://github.com/electron-userland/electron-builder/commit/344bb232d71e608b881a04fc98dca0858e42ddfc)), closes [#6286](https://github.com/electron-userland/electron-builder/issues/6286)



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.10...v) (2021-12-21)


### Bug Fixes

* **nsis:** Ignore other users processes during per-user installation ([#6472](https://github.com/electron-userland/electron-builder/issues/6472)) ([e3d06af](https://github.com/electron-userland/electron-builder/commit/e3d06afae1236d44e4b6e670b453b260b1f74d84)), closes [#6104](https://github.com/electron-userland/electron-builder/issues/6104)



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.8...v) (2021-11-30)


### Bug Fixes

* **app-builder-lib:** channel alternation for github is not working ([#6449](https://github.com/electron-userland/electron-builder/issues/6449)) ([df7a425](https://github.com/electron-userland/electron-builder/commit/df7a4255d219aea7a1236fd5693f7c13460099ad))
* **mac:** use `uname -a` to get arch before testing 'process.arch' on mac silicon  ([#6381](https://github.com/electron-userland/electron-builder/issues/6381)) ([828fcd3](https://github.com/electron-userland/electron-builder/commit/828fcd378c2df28763893ef68f92d5b1a72fead3))
* **nsis:** per-machine installs must properly elevate during silent install/updates ([#6450](https://github.com/electron-userland/electron-builder/issues/6450)) ([661a652](https://github.com/electron-userland/electron-builder/commit/661a6522520e9ea59549cb7e18986fcfb58e873a)), closes [#6438](https://github.com/electron-userland/electron-builder/issues/6438) [#6073](https://github.com/electron-userland/electron-builder/issues/6073) [#6425](https://github.com/electron-userland/electron-builder/issues/6425) [#5468](https://github.com/electron-userland/electron-builder/issues/5468)



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.8...v) (2021-11-30)


### Bug Fixes

* **nsis:** per-machine installs must properly elevate during silent install/updates ([#6450](https://github.com/electron-userland/electron-builder/issues/6450)) ([661a652](https://github.com/electron-userland/electron-builder/commit/661a6522520e9ea59549cb7e18986fcfb58e873a)), closes [#6438](https://github.com/electron-userland/electron-builder/issues/6438) [#6073](https://github.com/electron-userland/electron-builder/issues/6073) [#6425](https://github.com/electron-userland/electron-builder/issues/6425) [#5468](https://github.com/electron-userland/electron-builder/issues/5468)



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.7...v) (2021-11-26)


### Bug Fixes

* Downgrading nsis to v3.0.4.1 since v3.0.4.2 throws false virus positives ([#6334](https://github.com/electron-userland/electron-builder/issues/6334)) ([#6447](https://github.com/electron-userland/electron-builder/issues/6447)) ([d20bcf0](https://github.com/electron-userland/electron-builder/commit/d20bcf0cea4e4cb49aab08f820131a2d6b083a2c))


### Features

* make `--no-sandbox` optional for building with AppImage ([#6429](https://github.com/electron-userland/electron-builder/issues/6429)) ([e95afc1](https://github.com/electron-userland/electron-builder/commit/e95afc1ab8c1a09fc8c9496084fc9f49b185469e))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.6...v) (2021-11-11)


### Bug Fixes

* **builder-util:** enable proxy handling in NodeHttpExecutor ([#6410](https://github.com/electron-userland/electron-builder/issues/6410)) ([#6286](https://github.com/electron-userland/electron-builder/issues/6286)) ([#5906](https://github.com/electron-userland/electron-builder/issues/5906)) ([04a8435](https://github.com/electron-userland/electron-builder/commit/04a84352b2b3fbb3c54533a8428bfd103df0af21))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.5...v) (2021-11-09)


### Bug Fixes

* latest node-gyp with old Electron versions ([#6402](https://github.com/electron-userland/electron-builder/issues/6402)) ([f41d5f3](https://github.com/electron-userland/electron-builder/commit/f41d5f397ade8f6199d56bb4275b05a0a0e65bca))
* **linux:** mutually exclusive exec command args ([#6384](https://github.com/electron-userland/electron-builder/issues/6384)) ([5468c18](https://github.com/electron-userland/electron-builder/commit/5468c188f30f65352ca651e1f5fa9f8915c48c6b))
* quitAndInstall not working on macOS with autoInstallOnAppQuit=false ([#6390](https://github.com/electron-userland/electron-builder/issues/6390)) ([a5e8073](https://github.com/electron-userland/electron-builder/commit/a5e8073e21b1ff791905cdb4ab011a724533d8c1))
* rerunning test-linux to update snapshot for upstream dep that now uses additional depedencies ([#6403](https://github.com/electron-userland/electron-builder/issues/6403)) ([434d388](https://github.com/electron-userland/electron-builder/commit/434d3887cb651ef93ce214dc7b8edeab6a298096))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.4...v) (2021-10-13)


### Bug Fixes

* SnapStoreOptions required properties ([#6327](https://github.com/electron-userland/electron-builder/issues/6327)) ([#6333](https://github.com/electron-userland/electron-builder/issues/6333)) ([54ee4e7](https://github.com/electron-userland/electron-builder/commit/54ee4e72c5db859b9a00104179786567a0e977ff))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.3...v) (2021-10-03)


### Bug Fixes

* add appCannotBeClosed text for zh_CN ([#6287](https://github.com/electron-userland/electron-builder/issues/6287)) ([10b4727](https://github.com/electron-userland/electron-builder/commit/10b47273c32c32df17dfb910feb4a7704c83da91))
* **app-builder-lib:** macOS packager uses static icon name ([#6308](https://github.com/electron-userland/electron-builder/issues/6308)) ([fce1a1f](https://github.com/electron-userland/electron-builder/commit/fce1a1fab66e3f5cd741a4cecc4af8377aea9dd8))
* **publish:** Bitbucket publish can have username different from owner ([#6293](https://github.com/electron-userland/electron-builder/issues/6293)) ([8ebfc96](https://github.com/electron-userland/electron-builder/commit/8ebfc96276bffe0bc1ad394c5ae6843976e01709))
* Update assistedMessages.yml with korean entries ([#6309](https://github.com/electron-userland/electron-builder/issues/6309)) ([e29a6b8](https://github.com/electron-userland/electron-builder/commit/e29a6b8b36695a2ed9d2f9a57e4c1c74587d1b16))



# [](https://github.com/electron-userland/electron-builder/compare/v22.14.2...v) (2021-09-25)


### Bug Fixes

* **msi:** fix broken shortcut icon when using msi target, adding msi option `iconId` ([#6247](https://github.com/electron-userland/electron-builder/issues/6247)) ([a9ec90d](https://github.com/electron-userland/electron-builder/commit/a9ec90d539fdbb5786692629275b1a89bfd7aec4))



# [](https://github.com/electron-userland/electron-builder/compare/v22.13.1...v) (2021-09-10)


### Bug Fixes

* (mac) Fix intel mac upgrade flow when both x64 and arm64 published ([#6212](https://github.com/electron-userland/electron-builder/issues/6212)) ([0c21cd6](https://github.com/electron-userland/electron-builder/commit/0c21cd69663a7eebe0687eaba9eea851cc2fea9e))
* Add support for nested file extensions (such as `.dmg.blockmap`) to Keygen publisher ([#6234](https://github.com/electron-userland/electron-builder/issues/6234)) ([369f1fa](https://github.com/electron-userland/electron-builder/commit/369f1fa793c28d8743e19ef07ce6eb091c191fb0)), closes [#6229](https://github.com/electron-userland/electron-builder/issues/6229)
* **deploy:** Removing schema generation since it doesn't compile during release ([7e28c11](https://github.com/electron-userland/electron-builder/commit/7e28c11ec894c9ce7664a2ea3bfdb3e96f09d983))
* **deploy:** Update package.json script name ([e22fc16](https://github.com/electron-userland/electron-builder/commit/e22fc16cd196ab0f3cc7b2f9bdaae237e64121a8))
* dmg-license optional dependency ([#6244](https://github.com/electron-userland/electron-builder/issues/6244)) ([8ccb2da](https://github.com/electron-userland/electron-builder/commit/8ccb2da5d4c641b971f6a7403d3b2e3a3b844a05))
* dmg-license-dependency ([#6248](https://github.com/electron-userland/electron-builder/issues/6248)) ([f359035](https://github.com/electron-userland/electron-builder/commit/f3590355c61dab05a6c92c5951aae8e59503d693))


### Features

* adding Bitbucket publisher and autoupdater ([#6228](https://github.com/electron-userland/electron-builder/issues/6228)) ([a945321](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8))



# [](https://github.com/electron-userland/electron-builder/compare/v22.13.1...v) (2021-09-09)


### Bug Fixes

* (mac) Fix intel mac upgrade flow when both x64 and arm64 published ([#6212](https://github.com/electron-userland/electron-builder/issues/6212)) ([0c21cd6](https://github.com/electron-userland/electron-builder/commit/0c21cd69663a7eebe0687eaba9eea851cc2fea9e))
* Add support for nested file extensions (such as `.dmg.blockmap`) to Keygen publisher ([#6234](https://github.com/electron-userland/electron-builder/issues/6234)) ([369f1fa](https://github.com/electron-userland/electron-builder/commit/369f1fa793c28d8743e19ef07ce6eb091c191fb0)), closes [#6229](https://github.com/electron-userland/electron-builder/issues/6229)
* **deploy:** Removing schema generation since it doesn't compile during release ([7e28c11](https://github.com/electron-userland/electron-builder/commit/7e28c11ec894c9ce7664a2ea3bfdb3e96f09d983))
* **deploy:** Update package.json script name ([e22fc16](https://github.com/electron-userland/electron-builder/commit/e22fc16cd196ab0f3cc7b2f9bdaae237e64121a8))
* dmg-license optional dependency ([#6244](https://github.com/electron-userland/electron-builder/issues/6244)) ([8ccb2da](https://github.com/electron-userland/electron-builder/commit/8ccb2da5d4c641b971f6a7403d3b2e3a3b844a05))


### Features

* adding Bitbucket publisher and autoupdater ([#6228](https://github.com/electron-userland/electron-builder/issues/6228)) ([a945321](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8))



# [](https://github.com/electron-userland/electron-builder/compare/v22.13.1...v) (2021-09-08)


### Bug Fixes

* (mac) Fix intel mac upgrade flow when both x64 and arm64 published ([#6212](https://github.com/electron-userland/electron-builder/issues/6212)) ([0c21cd6](https://github.com/electron-userland/electron-builder/commit/0c21cd69663a7eebe0687eaba9eea851cc2fea9e))
* Add support for nested file extensions (such as `.dmg.blockmap`) to Keygen publisher ([#6234](https://github.com/electron-userland/electron-builder/issues/6234)) ([369f1fa](https://github.com/electron-userland/electron-builder/commit/369f1fa793c28d8743e19ef07ce6eb091c191fb0)), closes [#6229](https://github.com/electron-userland/electron-builder/issues/6229)
* **deploy:** Removing schema generation since it doesn't compile during release ([7e28c11](https://github.com/electron-userland/electron-builder/commit/7e28c11ec894c9ce7664a2ea3bfdb3e96f09d983))
* **deploy:** Update package.json script name ([e22fc16](https://github.com/electron-userland/electron-builder/commit/e22fc16cd196ab0f3cc7b2f9bdaae237e64121a8))


### Features

* adding Bitbucket publisher and autoupdater ([#6228](https://github.com/electron-userland/electron-builder/issues/6228)) ([a945321](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8))



# [](https://github.com/electron-userland/electron-builder/compare/v22.13.1...v) (2021-09-01)


### Bug Fixes

* (mac) Fix intel mac upgrade flow when both x64 and arm64 published ([#6212](https://github.com/electron-userland/electron-builder/issues/6212)) ([0c21cd6](https://github.com/electron-userland/electron-builder/commit/0c21cd69663a7eebe0687eaba9eea851cc2fea9e))



# [](https://github.com/electron-userland/electron-builder/compare/v22.13.0...v) (2021-08-27)


### Bug Fixes

* Adding snapStore to AllPublishOptions for generating Configuration schema ([#6193](https://github.com/electron-userland/electron-builder/issues/6193)) ([7f933d0](https://github.com/electron-userland/electron-builder/commit/7f933d0004a0a5f808a2a1c71dca7362cab2728e))
* Support Windows 11 in VMs ([#6185](https://github.com/electron-userland/electron-builder/issues/6185)) ([f6a3053](https://github.com/electron-userland/electron-builder/commit/f6a3053563bd50dc77010d2910086c81acdf613e))



# [](https://github.com/electron-userland/electron-builder/compare/v22.12.1...v) (2021-08-25)


### Features

* add `beforePack` hook ([#6176](https://github.com/electron-userland/electron-builder/issues/6176)) ([6f42f64](https://github.com/electron-userland/electron-builder/commit/6f42f646c9d36405c9d69ca45dda51baabdec4bd))
* Adding Keygen as an official publisher/updater for electron-builder ([#6167](https://github.com/electron-userland/electron-builder/issues/6167)) ([f45110c](https://github.com/electron-userland/electron-builder/commit/f45110cbf66572d5748d21fc24dc26cabd06f35f))



# [](https://github.com/electron-userland/electron-builder/compare/v22.12.0...v) (2021-08-22)


### Bug Fixes

* console log data for electron-updater blockmaps are far too large ([#6143](https://github.com/electron-userland/electron-builder/issues/6143)) ([ae363e5](https://github.com/electron-userland/electron-builder/commit/ae363e51957d0abfc7d848f51aa23c7e5faf5f33))
* **deploy:** remove zulip release message ([695f89a](https://github.com/electron-userland/electron-builder/commit/695f89a7b18e100c15ac47f837ae10ee600710ac))
* **electron-updater:** `null` object error when MacUpdater logs server port before it is listening ([#6149](https://github.com/electron-userland/electron-builder/issues/6149)) ([ca0e845](https://github.com/electron-userland/electron-builder/commit/ca0e8454b876c9fa0c95dbadf2461419e3a8b697))
* **electron-updater:** fix import errors ([#6140](https://github.com/electron-userland/electron-builder/issues/6140)) ([a3f2cd1](https://github.com/electron-userland/electron-builder/commit/a3f2cd1565771c8ce6c5a4b40d1c88316a75dff3)), closes [#6134](https://github.com/electron-userland/electron-builder/issues/6134)
* replace deprecated --cache-min option ([#6165](https://github.com/electron-userland/electron-builder/issues/6165)) ([c02ccbb](https://github.com/electron-userland/electron-builder/commit/c02ccbb9739a6fb2840625a825f6be33136567f0))
* **windows:** detect node path correctly on windows with cross-spawn ([#6069](https://github.com/electron-userland/electron-builder/issues/6069)) ([#6172](https://github.com/electron-userland/electron-builder/issues/6172)) ([6c945bd](https://github.com/electron-userland/electron-builder/commit/6c945bd59749d3fdd91f50ea4131ee22e82f72a2))
* workaround vite replacing process.env in updater ([#6160](https://github.com/electron-userland/electron-builder/issues/6160)) ([a3c72b2](https://github.com/electron-userland/electron-builder/commit/a3c72b2481ebaacfd717a7c492c119bcb9b7fc36))



# [](https://github.com/electron-userland/electron-builder/compare/v22.12.0...v) (2021-08-12)


### Bug Fixes

* console log data for electron-updater blockmaps are far too large ([#6143](https://github.com/electron-userland/electron-builder/issues/6143)) ([ae363e5](https://github.com/electron-userland/electron-builder/commit/ae363e51957d0abfc7d848f51aa23c7e5faf5f33))
* **electron-updater:** fix import errors ([#6140](https://github.com/electron-userland/electron-builder/issues/6140)) ([a3f2cd1](https://github.com/electron-userland/electron-builder/commit/a3f2cd1565771c8ce6c5a4b40d1c88316a75dff3)), closes [#6134](https://github.com/electron-userland/electron-builder/issues/6134)



# [](https://github.com/electron-userland/electron-builder/compare/v22.11.11...v) (2021-08-09)


### Bug Fixes

* **electron-updater:** search 'arm64' in name and url to fix updates from Github private repos ([1580ea6](https://github.com/electron-userland/electron-builder/commit/1580ea691c4b82ea80c6420d806bc4bfaef5fd38))
* **electron-updater:** small cleanup and add more debug logging for MacUpdater to investigate [#6120](https://github.com/electron-userland/electron-builder/issues/6120) ([#6122](https://github.com/electron-userland/electron-builder/issues/6122)) ([ae81dfa](https://github.com/electron-userland/electron-builder/commit/ae81dfae519435355fc079c76fc16ac25216bf38))
* **electron-updater:** use tag name instead of version when resolving GitHub files ([#6117](https://github.com/electron-userland/electron-builder/issues/6117)) ([dcf03a6](https://github.com/electron-userland/electron-builder/commit/dcf03a67a8a0d4cec4422cda0aa2585f7f54a384))
* **nsis:** should close app when `Silent` and `ONE_CLICK` ([#6100](https://github.com/electron-userland/electron-builder/issues/6100)) ([baf640d](https://github.com/electron-userland/electron-builder/commit/baf640da459dc667240e6015deaf11adb2155063))


### Features

* allow custom makensis and nsis logging ([#6024](https://github.com/electron-userland/electron-builder/issues/6024)) ([a99a7c8](https://github.com/electron-userland/electron-builder/commit/a99a7c87ffd7ffaaa5fae1a17f731a59aac60581)), closes [#5119](https://github.com/electron-userland/electron-builder/issues/5119)
* **portable:** Adding support for unique dir on each portable app launch ([#6093](https://github.com/electron-userland/electron-builder/issues/6093)) ([f8e16db](https://github.com/electron-userland/electron-builder/commit/f8e16db5393f663724e9c03ceab87698a252c934)), closes [#5764](https://github.com/electron-userland/electron-builder/issues/5764) [#5382](https://github.com/electron-userland/electron-builder/issues/5382) [#4105](https://github.com/electron-userland/electron-builder/issues/4105)



#  (2021-07-29)


### Bug Fixes

* **deploy:** Fixing zulip send message action ([41d5cae](https://github.com/electron-userland/electron-builder/commit/41d5cae325cba3031bc25148b1ff5927bc441913))
* **docs:** minor grammar/formatting fixes ([#6107](https://github.com/electron-userland/electron-builder/issues/6107)) ([b9b275f](https://github.com/electron-userland/electron-builder/commit/b9b275fff0763faf110a8dcb3c8313963710bbeb))
* linking CLI `version` output with package.json ([#6097](https://github.com/electron-userland/electron-builder/issues/6097)) ([a4eae34](https://github.com/electron-userland/electron-builder/commit/a4eae34f38444e0f30cf94af869e9e84c406a469))
* **mac:** signing cert filter incorrectly selects certificates ([#6094](https://github.com/electron-userland/electron-builder/issues/6094)) ([#6101](https://github.com/electron-userland/electron-builder/issues/6101)) ([#6105](https://github.com/electron-userland/electron-builder/issues/6105)) ([4a177dc](https://github.com/electron-userland/electron-builder/commit/4a177dc01c9119443426f1eb500afb836fd4f381))



# [](https://github.com/electron-userland/electron-builder/compare/v22.11.9...v) (2021-07-24)


### Bug Fixes

* any "node_module/____" glob pattern selects far too many node dependencies ([#6080](https://github.com/electron-userland/electron-builder/issues/6080)) ([72ffc25](https://github.com/electron-userland/electron-builder/commit/72ffc25063fc6d8f67e941ed7fc3b5991efb5448)), closes [#6045](https://github.com/electron-userland/electron-builder/issues/6045)
* remove @electron-builder/test from changeset ([e101e8d](https://github.com/electron-userland/electron-builder/commit/e101e8d190d7e3046222e88c32a62d727dadd808))
* using regex to determine yarn version to account for newer releases of yarn (i.e. yarn 3). fixes: [#6069](https://github.com/electron-userland/electron-builder/issues/6069) ([#6071](https://github.com/electron-userland/electron-builder/issues/6071)) ([1e19aba](https://github.com/electron-userland/electron-builder/commit/1e19abaecb3fd7b6ff0932b46ee129e04d1496b3))
* **win:** Windows update fails for custom paths that require admin rights ([#6073](https://github.com/electron-userland/electron-builder/issues/6073)) ([45fc0a0](https://github.com/electron-userland/electron-builder/commit/45fc0a003abc58969bb3a5d6ab1e3b61a9ad1a8d))


### Features

* **mac:** Add timestamp authority server to osx-sign options ([#6074](https://github.com/electron-userland/electron-builder/issues/6074)) ([41cb248](https://github.com/electron-userland/electron-builder/commit/41cb24869381de73a9663a17ec91d2747e099cf9))



# [](https://github.com/electron-userland/electron-builder/compare/v22.11.8...v) (2021-07-14)


### Bug Fixes

* **deploy:** consolidating versioning commands into package.json ([6066681](https://github.com/electron-userland/electron-builder/commit/6066681077c8ba730155751b83b4550add9b0dcf))
* **deploy:** deactivate husky hooks for automatic versioning PR ([#6041](https://github.com/electron-userland/electron-builder/issues/6041)) ([0d4d305](https://github.com/electron-userland/electron-builder/commit/0d4d3056b440cc45a1f1a15ea4a27c688cb0e96e))
* do not show MessageBox when app was killed (on not running) ([#6043](https://github.com/electron-userland/electron-builder/issues/6043)) ([0561674](https://github.com/electron-userland/electron-builder/commit/0561674b6c491ee1cfa0ba838f5c5d59ce205124))
* **nsis:** generate uninstaller without elevating ([#5575](https://github.com/electron-userland/electron-builder/issues/5575)) ([#6013](https://github.com/electron-userland/electron-builder/issues/6013)) ([b00aea3](https://github.com/electron-userland/electron-builder/commit/b00aea32107cd379b8489f7abea493d16fe38197))
* updating electron-osx-sign ([#6021](https://github.com/electron-userland/electron-builder/issues/6021)) ([6f63092](https://github.com/electron-userland/electron-builder/commit/6f630927ca949d8bdcde06e4eafaa63ce3636d5a)), closes [#6010](https://github.com/electron-userland/electron-builder/issues/6010) [#5190](https://github.com/electron-userland/electron-builder/issues/5190)
* write blockmap file for mac zip archives ([#6023](https://github.com/electron-userland/electron-builder/issues/6023)) ([0447b24](https://github.com/electron-userland/electron-builder/commit/0447b2457beb03648f1e7e841cd0a8d12d7e4aea)), closes [#4299](https://github.com/electron-userland/electron-builder/issues/4299)



**Here changelog only for previous major releases and without detailed explanations.**
To see changes for current major release, please use [GiHub releases](https://github.com/electron-userland/electron-builder/releases).

<a name=""></a>
# [19.10.0](https://github.com/electron-userland/electron-builder/compare/v19.9.1...v) (2017-06-28)


### Bug Fixes

* 19.8.0 broke ignoring folders ([50fe277](https://github.com/electron-userland/electron-builder/commit/50fe277)), closes [#1741](https://github.com/electron-userland/electron-builder/issues/1741)


### Features

* **Squirrel.Windows:** name option ([02dd8a1](https://github.com/electron-userland/electron-builder/commit/02dd8a1)), closes [#1743](https://github.com/electron-userland/electron-builder/issues/1743)
* **nsis:** option to not create desktop shortcut ([350e241](https://github.com/electron-userland/electron-builder/commit/350e241)), closes [#1597](https://github.com/electron-userland/electron-builder/issues/1597)
* allow to use files in the output directory to be included into the app ([95c75fc](https://github.com/electron-userland/electron-builder/commit/95c75fc))
* do not force build from sources by default ([86be5d7](https://github.com/electron-userland/electron-builder/commit/86be5d7)), closes [#1703](https://github.com/electron-userland/electron-builder/issues/1703)



<a name="19.9.1"></a>
## [19.9.1](https://github.com/electron-userland/electron-builder/compare/v19.9.0...v19.9.1) (2017-06-24)


### Features

* Support setting boolean properties with --extraMetadata ([9e77231](https://github.com/electron-userland/electron-builder/commit/9e77231)), closes [#1674](https://github.com/electron-userland/electron-builder/issues/1674)



<a name="19.9.0"></a>
# [19.9.0](https://github.com/electron-userland/electron-builder/compare/v19.8.0...v19.9.0) (2017-06-24)


### Bug Fixes

* **electron-updater:** MacUpdater — set Content-Length for responses, write 200 only if request to origin server is ok ([af2f559](https://github.com/electron-userland/electron-builder/commit/af2f559)), closes [#1719](https://github.com/electron-userland/electron-builder/issues/1719)


### Features

* add channel to file macros ([6aa3809](https://github.com/electron-userland/electron-builder/commit/6aa3809)), closes [#1701](https://github.com/electron-userland/electron-builder/issues/1701)



<a name="19.8.0"></a>
# [19.8.0](https://github.com/electron-userland/electron-builder/compare/v19.7.3...v19.8.0) (2017-06-23)


### Features

* ignore dll/exe files from node_modules if target platform not windows ([945a517](https://github.com/electron-userland/electron-builder/commit/945a517)), closes [#1738](https://github.com/electron-userland/electron-builder/issues/1738)



<a name="19.7.3"></a>
## [19.7.3](https://github.com/electron-userland/electron-builder/compare/v19.7.2...v19.7.3) (2017-06-22)


### Bug Fixes

* **AppImage:** AppImage artifact name does not use `artifactName` template ([a02fbd7](https://github.com/electron-userland/electron-builder/commit/a02fbd7)), closes [#1726](https://github.com/electron-userland/electron-builder/issues/1726)



<a name="19.7.2"></a>
## [19.7.2](https://github.com/electron-userland/electron-builder/compare/v19.7.0...v19.7.2) (2017-06-22)


### Bug Fixes

* electron-builder install-app-deps does not honor build.directories.app ([6db68be](https://github.com/electron-userland/electron-builder/commit/6db68be)), closes [#1721](https://github.com/electron-userland/electron-builder/issues/1721)
* **electron-updater:** Auto update does not work on machines with Powershell version < 3 ([5e09db4](https://github.com/electron-userland/electron-builder/commit/5e09db4)), closes [#1732](https://github.com/electron-userland/electron-builder/issues/1732)
* **mac:** clean macOsVersion before gte comparison (#1733) ([7ff95ca](https://github.com/electron-userland/electron-builder/commit/7ff95ca))
* **windows:** Get-PfxCertificate hangs ([6f8b94b](https://github.com/electron-userland/electron-builder/commit/6f8b94b)), closes [#1735](https://github.com/electron-userland/electron-builder/issues/1735)


### Features

* allow to set electronDist as path to local folder with electron builds zipped ([e79a28c](https://github.com/electron-userland/electron-builder/commit/e79a28c)), closes [#1716](https://github.com/electron-userland/electron-builder/issues/1716)



<a name="19.7.0"></a>
# [19.7.0](https://github.com/electron-userland/electron-builder/compare/v19.6.3...v19.7.0) (2017-06-21)


### Bug Fixes

* **auto-updater:** do not require app-update.yml file ([c03d98f](https://github.com/electron-userland/electron-builder/commit/c03d98f))


### Features

* **deployment:** set electron-updater releaseNotes at build time ([f6a2fc8](https://github.com/electron-userland/electron-builder/commit/f6a2fc8)), closes [#1511](https://github.com/electron-userland/electron-builder/issues/1511)



<a name="19.6.3"></a>
## [19.6.3](https://github.com/electron-userland/electron-builder/compare/v19.6.2...v19.6.3) (2017-06-21)


### Bug Fixes

* Runtime error for a build on window feat. electron-compile (forge) ([89a55ee](https://github.com/electron-userland/electron-builder/commit/89a55ee)), closes [#1686](https://github.com/electron-userland/electron-builder/issues/1686)



<a name="19.6.2"></a>
## [19.6.2](https://github.com/electron-userland/electron-builder/compare/v19.6.1...v19.6.2) (2017-06-21)


### Features

* **mac:** Ignore Contents/PlugIns ([a4b76b4](https://github.com/electron-userland/electron-builder/commit/a4b76b4)), closes [#1699](https://github.com/electron-userland/electron-builder/issues/1699)



<a name="19.6.1"></a>
## [19.6.1](https://github.com/electron-userland/electron-builder/compare/v19.6.0...v19.6.1) (2017-06-20)


### Bug Fixes

* keep shortcuts only if old uninstaller app support it ([8660093](https://github.com/electron-userland/electron-builder/commit/8660093)), closes [#1704](https://github.com/electron-userland/electron-builder/issues/1704)



<a name="19.6.0"></a>
# [19.6.0](https://github.com/electron-userland/electron-builder/compare/v19.5.1...v19.6.0) (2017-06-20)


### Features

* **mac:** upgrade osslsigncode, do not require wine ([ed662e8](https://github.com/electron-userland/electron-builder/commit/ed662e8)), closes [#1713](https://github.com/electron-userland/electron-builder/issues/1713) [#1707](https://github.com/electron-userland/electron-builder/issues/1707)
* **nsis:** Add flag to force start on silent install ([f24c389](https://github.com/electron-userland/electron-builder/commit/f24c389)), closes [#1545](https://github.com/electron-userland/electron-builder/issues/1545) [#1712](https://github.com/electron-userland/electron-builder/issues/1712)



<a name="19.5.1"></a>
## [19.5.1](https://github.com/electron-userland/electron-builder/compare/v19.5.0...v19.5.1) (2017-06-18)


### Bug Fixes

* **mac:** MacOS Sierra Command failed: codesign; The specified item could not be found in the keychain ([239d16d](https://github.com/electron-userland/electron-builder/commit/239d16d)), closes [#1457](https://github.com/electron-userland/electron-builder/issues/1457)


### Features

* **mac:** resize icons for Linux using sips on macOS to avoid graphicsmagick dependency ([e5817bc](https://github.com/electron-userland/electron-builder/commit/e5817bc))



<a name="19.5.0"></a>
# [19.5.0](https://github.com/electron-userland/electron-builder/compare/v19.4.2...v19.5.0) (2017-06-17)


### Bug Fixes

* **mac:** use hash instead of identity name to sign ([ee90ff2](https://github.com/electron-userland/electron-builder/commit/ee90ff2)), closes [#1629](https://github.com/electron-userland/electron-builder/issues/1629)


### Features

* **appx:** languages ([86af4cd](https://github.com/electron-userland/electron-builder/commit/86af4cd)), closes [#1684](https://github.com/electron-userland/electron-builder/issues/1684)
* **electron-updater:** staged rollouts ([5bae61e](https://github.com/electron-userland/electron-builder/commit/5bae61e)), closes [#1639](https://github.com/electron-userland/electron-builder/issues/1639)
* **pkg:** build pkg that doesn't require admin install ([a3a23f2](https://github.com/electron-userland/electron-builder/commit/a3a23f2))



<a name="19.4.2"></a>
## [19.4.2](https://github.com/electron-userland/electron-builder/compare/v19.4.1...v19.4.2) (2017-06-16)


### Bug Fixes

* **nsis:** missed "Installing, please wait" text ([c5d3441](https://github.com/electron-userland/electron-builder/commit/c5d3441)), closes [#1630](https://github.com/electron-userland/electron-builder/issues/1630)


### Features

* **deployment:** do not publish if Pull Request — support APPVEYOR_PULL_REQUEST_NUMBER ([b0fb872](https://github.com/electron-userland/electron-builder/commit/b0fb872))



<a name="19.4.1"></a>
## [19.4.1](https://github.com/electron-userland/electron-builder/compare/v19.4.0...v19.4.1) (2017-06-16)


### Bug Fixes

* **electron-updater:** No notification in case of an error during signature verification ([a9e03ce](https://github.com/electron-userland/electron-builder/commit/a9e03ce)), closes [#1680](https://github.com/electron-userland/electron-builder/issues/1680) [#1681](https://github.com/electron-userland/electron-builder/issues/1681)


### Code Refactoring

* merge electron-builder-core into electron-builder, transform node-gyp-rebuild bin to subcommand ([a8c9ffd](https://github.com/electron-userland/electron-builder/commit/a8c9ffd))


### Features

* **appx:** Improve support for AppX assets ([666dec7](https://github.com/electron-userland/electron-builder/commit/666dec7))


### BREAKING CHANGES

* Please use `node-gyp-rebuild` as `electron-buider node-gyp-rebuild` now



<a name="19.3.0"></a>
# [19.3.0](https://github.com/electron-userland/electron-builder/compare/v19.2.7...v19.3.0) (2017-06-15)


### Features

* **nsis:** custom uninstaller display name in the control panel ([fda6ee9](https://github.com/electron-userland/electron-builder/commit/fda6ee9))
* react-cra detection, shareable config support — extends ([28f0266](https://github.com/electron-userland/electron-builder/commit/28f0266))



<a name="19.2.7"></a>
## [19.2.7](https://github.com/electron-userland/electron-builder/compare/v19.2.3...v19.2.7) (2017-06-14)


### Bug Fixes

* The zip Windows target includes the application code inside a "win-unpacked" directory ([4e6ece4](https://github.com/electron-userland/electron-builder/commit/4e6ece4)), closes [#1666](https://github.com/electron-userland/electron-builder/issues/1666)
* correctly pack cache folder for electron-compile ([419cf91](https://github.com/electron-userland/electron-builder/commit/419cf91)), closes [#1465](https://github.com/electron-userland/electron-builder/issues/1465)
* ignore node_modules without package.json ([5e24859](https://github.com/electron-userland/electron-builder/commit/5e24859)), closes [#1671](https://github.com/electron-userland/electron-builder/issues/1671)



<a name="19.2.3"></a>
## [19.2.3](https://github.com/electron-userland/electron-builder/compare/v19.2.2...v19.2.3) (2017-06-14)


### Bug Fixes

* do not copy electronDist using hard links ([c04dd20](https://github.com/electron-userland/electron-builder/commit/c04dd20)), closes [#1670](https://github.com/electron-userland/electron-builder/issues/1670)


### Features

* check that electron-builder version is not outdated for all subcommands ([d9ecfe5](https://github.com/electron-userland/electron-builder/commit/d9ecfe5))



<a name="19.2.2"></a>
## [19.2.2](https://github.com/electron-userland/electron-builder/compare/v19.1.0...v19.2.2) (2017-06-13)


### Bug Fixes

* macOS failing when there is no old icon (#1658) ([ac44fcd](https://github.com/electron-userland/electron-builder/commit/ac44fcd))
* **nsis:** Keep existing desktop/menu/taskbar shortcuts after update ([2f3d7d8](https://github.com/electron-userland/electron-builder/commit/2f3d7d8)), closes [#1653](https://github.com/electron-userland/electron-builder/issues/1653)


### Features

* install-app-deps.ts subcommand ([5e0a646](https://github.com/electron-userland/electron-builder/commit/5e0a646))



<a name="19.1.0"></a>
# [19.1.0](https://github.com/electron-userland/electron-builder/compare/v19.0.2...v19.1.0) (2017-06-12)


### Features

* electron-builder bin executable ([54ac796](https://github.com/electron-userland/electron-builder/commit/54ac796))



<a name="19.0.2"></a>
## [19.0.2](https://github.com/electron-userland/electron-builder/compare/v19.0.0...v19.0.2) (2017-06-12)


### Bug Fixes

* **electron-updater:** update sign verification error ([e713bbe](https://github.com/electron-userland/electron-builder/commit/e713bbe)), closes [#1641](https://github.com/electron-userland/electron-builder/issues/1641)
* Appx name changed ([dd0b208](https://github.com/electron-userland/electron-builder/commit/dd0b208)), closes [#1650](https://github.com/electron-userland/electron-builder/issues/1650)



<a name="19.0.0"></a>
# [19.0.0](https://github.com/electron-userland/electron-builder/compare/v18.8.0...v19.0.0) (2017-06-12)


### Features

* prune submodule package.json dependencies ([1145cb9](https://github.com/electron-userland/electron-builder/commit/1145cb9)), closes [#1539](https://github.com/electron-userland/electron-builder/issues/1539)
* **nsis:** add APP_EXECUTABLE_DIR ([8e957c8](https://github.com/electron-userland/electron-builder/commit/8e957c8)), closes [#1612](https://github.com/electron-userland/electron-builder/issues/1612)



<a name="18.8.0"></a>
# [18.8.0](https://github.com/electron-userland/electron-builder/compare/v18.7.0...v18.8.0) (2017-06-12)


### Features

* update makeappx tool, use powershell on Windows to get publisher name, allow to build appx on Windows Server 2012 R2 ([4d7e1b5](https://github.com/electron-userland/electron-builder/commit/4d7e1b5))



<a name="18.7.0"></a>
# [18.7.0](https://github.com/electron-userland/electron-builder/compare/v18.6.2...v18.7.0) (2017-06-08)


### Bug Fixes

* **electron-updater:** check for EACCES error when try to install on auto updated windows (#1636) ([9ef77b9](https://github.com/electron-userland/electron-builder/commit/9ef77b9))


### Features

* do not require "author" ([e700b78](https://github.com/electron-userland/electron-builder/commit/e700b78))
* **nsis:** Option to not pack "elevate.exe" ([69c3614](https://github.com/electron-userland/electron-builder/commit/69c3614)), closes [#1620](https://github.com/electron-userland/electron-builder/issues/1620) [#1621](https://github.com/electron-userland/electron-builder/issues/1621)


### Performance Improvements

* use fcopy ([d9a8015](https://github.com/electron-userland/electron-builder/commit/d9a8015))



<a name="18.6.2"></a>
## [18.6.2](https://github.com/electron-userland/electron-builder/compare/v18.6.0...v18.6.2) (2017-06-07)


### Bug Fixes

* install-app-deps, attempt 2 ([8715f44](https://github.com/electron-userland/electron-builder/commit/8715f44)), closes [#1626](https://github.com/electron-userland/electron-builder/issues/1626)
* **electron-updater:** isSilent is optional ([12473d0](https://github.com/electron-userland/electron-builder/commit/12473d0))



<a name="18.6.0"></a>
# [18.6.0](https://github.com/electron-userland/electron-builder/compare/v18.5.1...v18.6.0) (2017-06-06)


### Bug Fixes

* **electron-updater:** MacUpdater — close proxy server after download ([39ae0a4](https://github.com/electron-userland/electron-builder/commit/39ae0a4))
* **nsis:** Cloning packager.config to prevent override ([5b8abcb](https://github.com/electron-userland/electron-builder/commit/5b8abcb)), closes [#1340](https://github.com/electron-userland/electron-builder/issues/1340) [#1340](https://github.com/electron-userland/electron-builder/issues/1340)
* install-app-deps ([21a5be5](https://github.com/electron-userland/electron-builder/commit/21a5be5)), closes [#1626](https://github.com/electron-userland/electron-builder/issues/1626)


### Features

* grab latest electron version from github if not specified ([a826df2](https://github.com/electron-userland/electron-builder/commit/a826df2))
* **appimage:** artifactName support for AppImage ([0ea43a3](https://github.com/electron-userland/electron-builder/commit/0ea43a3)), closes [#775](https://github.com/electron-userland/electron-builder/issues/775)
* **docker:** upgrade to zesty ([da1734e](https://github.com/electron-userland/electron-builder/commit/da1734e))
* **electron-updater:** ensure that update only to the application signed with same cert ([66771d3](https://github.com/electron-userland/electron-builder/commit/66771d3)), closes [#1187](https://github.com/electron-userland/electron-builder/issues/1187)



<a name="18.5.1"></a>
## [18.5.1](https://github.com/electron-userland/electron-builder/compare/v18.5.0...v18.5.1) (2017-06-05)


### Features

* **electon-updater:** autoUpdater download-progress event is not called on macOS ([a75bac8](https://github.com/electron-userland/electron-builder/commit/a75bac8)), closes [#1167](https://github.com/electron-userland/electron-builder/issues/1167)



<a name="18.5.0"></a>
# [18.5.0](https://github.com/electron-userland/electron-builder/compare/v18.4.0...v18.5.0) (2017-06-05)


### Features

* **nsis:** Slovak(sk) translation ([09495f9](https://github.com/electron-userland/electron-builder/commit/09495f9))
* do not override HOME env on reinstall deps, use devdir for nodegyp ([ae0f668](https://github.com/electron-userland/electron-builder/commit/ae0f668))
* use base64 to encode sha512 checksum in the update info ([4451107](https://github.com/electron-userland/electron-builder/commit/4451107))
* **nsis:** Slovak(sk) translation for assisted installer ([63f019f](https://github.com/electron-userland/electron-builder/commit/63f019f)), closes [#1617](https://github.com/electron-userland/electron-builder/issues/1617)



<a name="18.4.0"></a>
# [18.4.0](https://github.com/electron-userland/electron-builder/compare/v18.3.5...v18.4.0) (2017-06-04)


### Bug Fixes

* **deployment:** latest.yml is completely empty when uploaded to S3 bucket ([4b25ca2](https://github.com/electron-userland/electron-builder/commit/4b25ca2)), closes [#1582](https://github.com/electron-userland/electron-builder/issues/1582)
* **deployment:** s3 publisher md5 integrity ([b57dc8a](https://github.com/electron-userland/electron-builder/commit/b57dc8a))
* **tar:** fix invalid sym-/hardlink targets in archive (#1614) ([b31ebff](https://github.com/electron-userland/electron-builder/commit/b31ebff)), closes [#1614](https://github.com/electron-userland/electron-builder/issues/1614)


### Features

* asar integrity (macos only for now) ([3e28ae2](https://github.com/electron-userland/electron-builder/commit/3e28ae2))
* asar integrity: add externalAllowed option ([e0d7974](https://github.com/electron-userland/electron-builder/commit/e0d7974))
* asar integrity: base64, externalAllowed ([9a7ac65](https://github.com/electron-userland/electron-builder/commit/9a7ac65))
* docker with node 8 ([df1feb5](https://github.com/electron-userland/electron-builder/commit/df1feb5))



<a name="18.3.5"></a>
## [18.3.5](https://github.com/electron-userland/electron-builder/compare/v18.3.0...v18.3.5) (2017-06-01)


### Bug Fixes

* **deployment:** check for errors ([4c71fc0](https://github.com/electron-userland/electron-builder/commit/4c71fc0))
* Identity validation option is incorrect ([97699b1](https://github.com/electron-userland/electron-builder/commit/97699b1)), closes [#1603](https://github.com/electron-userland/electron-builder/issues/1603)
* **dmg:** move hidden directories out of view ([452085b](https://github.com/electron-userland/electron-builder/commit/452085b)), closes [#1121](https://github.com/electron-userland/electron-builder/issues/1121)



<a name="18.3.0"></a>
# [18.3.0](https://github.com/electron-userland/electron-builder/compare/v18.2.1...v18.3.0) (2017-05-31)


### Bug Fixes

* more clear handling of onTagOrDraft ([817340a](https://github.com/electron-userland/electron-builder/commit/817340a))
* **deployment:** different channels for different publish providers ([81fd398](https://github.com/electron-userland/electron-builder/commit/81fd398))


### Features

* **linux:** add missing Exec variable for passing URLs as arguments ([4a87e67](https://github.com/electron-userland/electron-builder/commit/4a87e67)), closes [#1592](https://github.com/electron-userland/electron-builder/issues/1592)



<a name="18.2.1"></a>
## [18.2.1](https://github.com/electron-userland/electron-builder/compare/v18.1.1...v18.2.1) (2017-05-30)


### Bug Fixes

* trim the whole string, otherwise detection of windows-like path is not robust ([e63e8fa](https://github.com/electron-userland/electron-builder/commit/e63e8fa)), closes [#1596](https://github.com/electron-userland/electron-builder/issues/1596)


### Features

* support relative (to project dir) path in the CSC_LINK ([381e8c0](https://github.com/electron-userland/electron-builder/commit/381e8c0)), closes [#1596](https://github.com/electron-userland/electron-builder/issues/1596)



<a name="18.1.1"></a>
## [18.1.1](https://github.com/electron-userland/electron-builder/compare/v18.1.0...v18.1.1) (2017-05-30)


### Bug Fixes

* **appx:** AppX build fails ([9e9ed4f](https://github.com/electron-userland/electron-builder/commit/9e9ed4f)), closes [#1515](https://github.com/electron-userland/electron-builder/issues/1515)


### Features

* PUBLISH_FOR_PULL_REQUEST ([7d8e097](https://github.com/electron-userland/electron-builder/commit/7d8e097))



<a name="18.1.0"></a>
# [18.1.0](https://github.com/electron-userland/electron-builder/compare/v18.0.1...v18.1.0) (2017-05-27)


### Features

* remove "Space required" text for NSIS installer ([565740c](https://github.com/electron-userland/electron-builder/commit/565740c)), closes [#1566](https://github.com/electron-userland/electron-builder/issues/1566)
* **nsis:** custom uninstall application icon ([e4e5cc7](https://github.com/electron-userland/electron-builder/commit/e4e5cc7)), closes [#1585](https://github.com/electron-userland/electron-builder/issues/1585)



<a name="18.0.1"></a>
## [18.0.1](https://github.com/electron-userland/electron-builder/compare/v18.0.0...v18.0.1) (2017-05-24)


### Bug Fixes

* "status 401: Unauthorized" issue with dl.bintray.com ([52995df](https://github.com/electron-userland/electron-builder/commit/52995df)), closes [#1581](https://github.com/electron-userland/electron-builder/issues/1581)



<a name="18.0.0"></a>
# [18.0.0](https://github.com/electron-userland/electron-builder/compare/v17.10.0...v18.0.0) (2017-05-23)


### Bug Fixes

* **config:** use json5 parser for json5 build configs ([94d89eb](https://github.com/electron-userland/electron-builder/commit/94d89eb)), closes [#1569](https://github.com/electron-userland/electron-builder/issues/1569) [#1578](https://github.com/electron-userland/electron-builder/issues/1578)


### Code Refactoring

* **updater:** prepare to support private github repo, nuts and so on on macOS ([a41936b](https://github.com/electron-userland/electron-builder/commit/a41936b)), closes [#1575](https://github.com/electron-userland/electron-builder/issues/1575) [#1571](https://github.com/electron-userland/electron-builder/issues/1571) [#1577](https://github.com/electron-userland/electron-builder/issues/1577)


### Features

* **mac:** allow passing through binaries and requirements options ([a2e58c0](https://github.com/electron-userland/electron-builder/commit/a2e58c0)), closes [#1574](https://github.com/electron-userland/electron-builder/issues/1574)
* **snap:** Snap for extra after parts and build packages support (#1565) ([22b5ba5](https://github.com/electron-userland/electron-builder/commit/22b5ba5))


### BREAKING CHANGES

* **updater:** remove compatibility with very old electron-updater version (< 0.10.0)



<a name="17.10.0"></a>
# [17.10.0](https://github.com/electron-userland/electron-builder/compare/v17.9.0...v17.10.0) (2017-05-21)


### Features

* **nsis:** custom uninstall application icon ([eb181b9](https://github.com/electron-userland/electron-builder/commit/eb181b9)), closes [#1550](https://github.com/electron-userland/electron-builder/issues/1550)



<a name="17.9.0"></a>
# [17.9.0](https://github.com/electron-userland/electron-builder/compare/v17.8.0...v17.9.0) (2017-05-20)


### Bug Fixes

* electron-builder 17.5.0, 17.8.0: cannot find module 'debug' ([5835654](https://github.com/electron-userland/electron-builder/commit/5835654)), closes [#1564](https://github.com/electron-userland/electron-builder/issues/1564)


### Features

* **electron-updater:** isSilent param of quitAndInstall method #1545 ([daeefa6](https://github.com/electron-userland/electron-builder/commit/daeefa6))
* **nsis:** add korean messages for one-click installer (#1556) ([9fce636](https://github.com/electron-userland/electron-builder/commit/9fce636))



<a name="17.8.0"></a>
# [17.8.0](https://github.com/electron-userland/electron-builder/compare/v17.7.0...v17.8.0) (2017-05-15)


### Bug Fixes

* Automatic unpack detection in scoped packages unpacks the entire scope ([3558b22](https://github.com/electron-userland/electron-builder/commit/3558b22)), closes [#1540](https://github.com/electron-userland/electron-builder/issues/1540)


### Features

* **nsis:** finnish nsis lang ([c88d991](https://github.com/electron-userland/electron-builder/commit/c88d991))
* **squirrel.windows:** Update Squirrel.Windows to 1.6.0 ([c4bb492](https://github.com/electron-userland/electron-builder/commit/c4bb492)), closes [#1535](https://github.com/electron-userland/electron-builder/issues/1535)



<a name="17.7.0"></a>
# [17.7.0](https://github.com/electron-userland/electron-builder/compare/v17.6.0...v17.7.0) (2017-05-13)


### Features

* **nsis:** add ja translation for one-click installer (#1543) ([90d0da1](https://github.com/electron-userland/electron-builder/commit/90d0da1))



<a name="17.6.0"></a>
# [17.6.0](https://github.com/electron-userland/electron-builder/compare/v17.5.0...v17.6.0) (2017-05-13)


### Features

* **nsis:** NSIS - nested start menu folders ([fafc7ba](https://github.com/electron-userland/electron-builder/commit/fafc7ba)), closes [#1538](https://github.com/electron-userland/electron-builder/issues/1538)
* **nsis:** ko lang ([89a5233](https://github.com/electron-userland/electron-builder/commit/89a5233)), closes [#1504](https://github.com/electron-userland/electron-builder/issues/1504)



<a name="17.5.0"></a>
# [17.5.0](https://github.com/electron-userland/electron-builder/compare/v17.4.0...v17.5.0) (2017-05-08)


### Features

* local path to custom electron build (windows support) ([521aea6](https://github.com/electron-userland/electron-builder/commit/521aea6)), closes [#1534](https://github.com/electron-userland/electron-builder/issues/1534) [#1342](https://github.com/electron-userland/electron-builder/issues/1342)



<a name="17.4.0"></a>
# [17.4.0](https://github.com/electron-userland/electron-builder/compare/v17.3.1...v17.4.0) (2017-05-08)


### Features

* **electron-updater:** add proxy authentication support to electron-updater ([a892a5b](https://github.com/electron-userland/electron-builder/commit/a892a5b)), closes [#1530](https://github.com/electron-userland/electron-builder/issues/1530)
* **nsis:** add de, it, fr, hu, pl translations for one-click installer ([d8aa078](https://github.com/electron-userland/electron-builder/commit/d8aa078))



<a name="17.3.1"></a>
## [17.3.1](https://github.com/electron-userland/electron-builder/compare/v17.3.0...v17.3.1) (2017-05-05)


### Bug Fixes

* Make sure the documentation for this option clearly states the security implications of turning it on #1524 ([b0ce309](https://github.com/electron-userland/electron-builder/commit/b0ce309))
* Use of extraResources prevents node_modules from being included in asar ([0fbad33](https://github.com/electron-userland/electron-builder/commit/0fbad33)), closes [#867](https://github.com/electron-userland/electron-builder/issues/867)



<a name="17.3.0"></a>
# [17.3.0](https://github.com/electron-userland/electron-builder/compare/v17.2.0...v17.3.0) (2017-05-04)


### Bug Fixes

* **electron-updater:** electron-updater v1.14.* throws cannot find module 'debug' ([78d9b33](https://github.com/electron-userland/electron-builder/commit/78d9b33)), closes [#1521](https://github.com/electron-userland/electron-builder/issues/1521)


### Features

* ${buildVersion} macro in artifactName config ([23f0b37](https://github.com/electron-userland/electron-builder/commit/23f0b37)), closes [#1527](https://github.com/electron-userland/electron-builder/issues/1527)
* **mac:** allow build for pull requests / code sign artifacts ([9dbc789](https://github.com/electron-userland/electron-builder/commit/9dbc789)), closes [#1524](https://github.com/electron-userland/electron-builder/issues/1524)



<a name="17.2.0"></a>
# [17.2.0](https://github.com/electron-userland/electron-builder/compare/v17.1.2...v17.2.0) (2017-05-02)


### Features

* **forge:** support electron-forge 3.0 API ([002a714](https://github.com/electron-userland/electron-builder/commit/002a714))
* **nsis:** multi-lang one-click installer (including custom string) ([f01415a](https://github.com/electron-userland/electron-builder/commit/f01415a))



<a name="17.1.2"></a>
## [17.1.2](https://github.com/electron-userland/electron-builder/compare/v17.1.1...v17.1.2) (2017-04-26)


### Bug Fixes

* Cannot copy files from parent directory of build output ([7f00714](https://github.com/electron-userland/electron-builder/commit/7f00714)), closes [#1482](https://github.com/electron-userland/electron-builder/issues/1482)



<a name="17.1.1"></a>
## [17.1.1](https://github.com/electron-userland/electron-builder/compare/v17.1.0...v17.1.1) (2017-04-24)


### Bug Fixes

* **auto-updater:** Autoupdates to lower version with allowPrerelease=true using GitHub releases ([36fc3db](https://github.com/electron-userland/electron-builder/commit/36fc3db)), closes [#1497](https://github.com/electron-userland/electron-builder/issues/1497)
* **dmg:** license ([5a163df](https://github.com/electron-userland/electron-builder/commit/5a163df)), closes [#1491](https://github.com/electron-userland/electron-builder/issues/1491)



<a name="17.1.0"></a>
# [17.1.0](https://github.com/electron-userland/electron-builder/compare/v17.0.3...v17.1.0) (2017-04-23)


### Features

* **dmg:** dmg license ([d6f0c57](https://github.com/electron-userland/electron-builder/commit/d6f0c57)), closes [#1491](https://github.com/electron-userland/electron-builder/issues/1491)



<a name="17.0.3"></a>
## [17.0.3](https://github.com/electron-userland/electron-builder/compare/v17.0.1...v17.0.3) (2017-04-22)


### Bug Fixes

* Upload release failed. Response status: 401 Unauthorized ([257a7dd](https://github.com/electron-userland/electron-builder/commit/257a7dd)), closes [#1385](https://github.com/electron-userland/electron-builder/issues/1385)
* **electron-updater:** Incorrect comparison of version numbers (electron-updater) ([17ac619](https://github.com/electron-userland/electron-builder/commit/17ac619)), closes [#1488](https://github.com/electron-userland/electron-builder/issues/1488)


### Features

* **electron-updater:** GitHub: Allow pre-release builds to be auto updated ([f275831](https://github.com/electron-userland/electron-builder/commit/f275831)), closes [#1391](https://github.com/electron-userland/electron-builder/issues/1391)
* support additional certificate file (#1467) ([19c8ee4](https://github.com/electron-userland/electron-builder/commit/19c8ee4))



<a name="17.0.1"></a>
## [17.0.1](https://github.com/electron-userland/electron-builder/compare/v17.0.0...v17.0.1) (2017-04-16)


### Bug Fixes

* handle sync spawn error ([4351b56](https://github.com/electron-userland/electron-builder/commit/4351b56)), closes [#1460](https://github.com/electron-userland/electron-builder/issues/1460)
* handle sync spawn error ([af14809](https://github.com/electron-userland/electron-builder/commit/af14809)), closes [#1438](https://github.com/electron-userland/electron-builder/issues/1438)


### Features

* **electron-updater:** Make it possible to "auto-downgrade" the application on channel change ([a3c4a9e](https://github.com/electron-userland/electron-builder/commit/a3c4a9e)), closes [#1149](https://github.com/electron-userland/electron-builder/issues/1149)



<a name="17.0.0"></a>
# [17.0.0](https://github.com/electron-userland/electron-builder/compare/v16.8.4...v17.0.0) (2017-04-15)


### Features

* automatically set channel to version prerelease component ([831186f](https://github.com/electron-userland/electron-builder/commit/831186f)), closes [#1182](https://github.com/electron-userland/electron-builder/issues/1182)


### BREAKING CHANGES

* if app version is `0.12.1-alpha.1`, file `alpha.yml` will be generated instead of `latest.yml`



<a name="16.8.4"></a>
## [16.8.4](https://github.com/electron-userland/electron-builder/compare/v16.8.3...v16.8.4) (2017-04-15)


### Bug Fixes

* Rebuild stucks on Windows ([2c52ed2](https://github.com/electron-userland/electron-builder/commit/2c52ed2)), closes [#1472](https://github.com/electron-userland/electron-builder/issues/1472)



<a name="16.8.3"></a>
## [16.8.3](https://github.com/electron-userland/electron-builder/compare/v16.8.2...v16.8.3) (2017-04-12)


### Bug Fixes

* **rebuild:** Log stdout and stderr (#1450) ([ada9cac](https://github.com/electron-userland/electron-builder/commit/ada9cac))
* **snap:** fix appindicator icons with snap build (#1453) ([2ab769d](https://github.com/electron-userland/electron-builder/commit/2ab769d)), closes [#1453](https://github.com/electron-userland/electron-builder/issues/1453) [#1452](https://github.com/electron-userland/electron-builder/issues/1452)
* do not use scoped electron-download ([8c79f60](https://github.com/electron-userland/electron-builder/commit/8c79f60)), closes [#1458](https://github.com/electron-userland/electron-builder/issues/1458)


### Features

* **electron-updater:** Location of app-update.yml in the dev mode ([8c73f57](https://github.com/electron-userland/electron-builder/commit/8c73f57)), closes [#1254](https://github.com/electron-userland/electron-builder/issues/1254)


### Performance Improvements

* **nsis:** run tasks in parallel ([6f56905](https://github.com/electron-userland/electron-builder/commit/6f56905))



<a name="16.8.2"></a>
## [16.8.2](https://github.com/electron-userland/electron-builder/compare/v16.8.1...v16.8.2) (2017-04-09)


### Bug Fixes

* **nsis:** move generated custom messages to separate files (to avoid stdin encoding issues on Windows) ([5b83860](https://github.com/electron-userland/electron-builder/commit/5b83860)), closes [#1447](https://github.com/electron-userland/electron-builder/issues/1447)



<a name="16.8.1"></a>
## [16.8.1](https://github.com/electron-userland/electron-builder/compare/v16.8.0...v16.8.1) (2017-04-09)


### Bug Fixes

* fix incorrect rebuild target in install-app-deps ([88e52ad](https://github.com/electron-userland/electron-builder/commit/88e52ad))



<a name="16.8.0"></a>
# [16.8.0](https://github.com/electron-userland/electron-builder/compare/v16.7.1...v16.8.0) (2017-04-08)


### Bug Fixes

* **nsis:** build portable in parallel to nsis ([918a317](https://github.com/electron-userland/electron-builder/commit/918a317)), closes [#1340](https://github.com/electron-userland/electron-builder/issues/1340)


### Features

* **muon:** Rebuilding the native dependencies for muon ([3232f65](https://github.com/electron-userland/electron-builder/commit/3232f65)), closes [#1404](https://github.com/electron-userland/electron-builder/issues/1404)
* **portable:** ExecutionLevel for nsis portable ([3f8caab](https://github.com/electron-userland/electron-builder/commit/3f8caab)), closes [#1440](https://github.com/electron-userland/electron-builder/issues/1440)



<a name="16.7.1"></a>
## [16.7.1](https://github.com/electron-userland/electron-builder/compare/v16.7.0...v16.7.1) (2017-04-07)


### Bug Fixes

* **deb:** add libxss1 to depends by default ([897fcf2](https://github.com/electron-userland/electron-builder/commit/897fcf2))
* **s3:** S3-DEPLOY with parenthesis / spaces in product name broken in 1.6.2 ([26ae6ec](https://github.com/electron-userland/electron-builder/commit/26ae6ec)), closes [#1439](https://github.com/electron-userland/electron-builder/issues/1439)



<a name="16.7.0"></a>
# [16.7.0](https://github.com/electron-userland/electron-builder/compare/v16.6.2...v16.7.0) (2017-04-05)


### Bug Fixes

* **linux:** depends for deb in LinuxOptions ([d58d323](https://github.com/electron-userland/electron-builder/commit/d58d323)), closes [#1420](https://github.com/electron-userland/electron-builder/issues/1420)


### Features

* **nsis:** add --no-desktop-shortcut argument (#1432) ([e1e3832](https://github.com/electron-userland/electron-builder/commit/e1e3832))



<a name="16.6.2"></a>
## [16.6.2](https://github.com/electron-userland/electron-builder/compare/v16.6.1...v16.6.2) (2017-04-04)


### Bug Fixes

* **deployment:** S3 won't upload app files ([4149031](https://github.com/electron-userland/electron-builder/commit/4149031)), closes [#1331](https://github.com/electron-userland/electron-builder/issues/1331)



<a name="16.6.1"></a>
## [16.6.1](https://github.com/electron-userland/electron-builder/compare/v16.6.0...v16.6.1) (2017-04-01)


### Bug Fixes

* **auto-updater:** respect vPrefixedTagName for auto update ([624311b](https://github.com/electron-userland/electron-builder/commit/624311b)), closes [#1417](https://github.com/electron-userland/electron-builder/issues/1417)
* ignore files in the node_modules during read_installed ([37f84b9](https://github.com/electron-userland/electron-builder/commit/37f84b9)), closes [#1424](https://github.com/electron-userland/electron-builder/issues/1424)


### Features

* **mac:** mac build zip file name does not follow build.artifactName ([1affc61](https://github.com/electron-userland/electron-builder/commit/1affc61)), closes [#1398](https://github.com/electron-userland/electron-builder/issues/1398)
* retry code sign if failed due to network failure ([9b60518](https://github.com/electron-userland/electron-builder/commit/9b60518)), closes [#1414](https://github.com/electron-userland/electron-builder/issues/1414)



<a name="16.6.0"></a>
# [16.6.0](https://github.com/electron-userland/electron-builder/compare/v16.5.1...v16.6.0) (2017-03-29)



<a name="16.5.1"></a>
## [16.5.1](https://github.com/electron-userland/electron-builder/compare/v16.5.0...v16.5.1) (2017-03-28)


### Bug Fixes

* **nsis:** StartApp doesn't work if menuCategory used ([683d58c](https://github.com/electron-userland/electron-builder/commit/683d58c)), closes [#1151](https://github.com/electron-userland/electron-builder/issues/1151) [#1412](https://github.com/electron-userland/electron-builder/issues/1412)



<a name="16.5.0"></a>
# [16.5.0](https://github.com/electron-userland/electron-builder/compare/v16.4.2...v16.5.0) (2017-03-28)


### Features

* Enforce a proper application location ([958a7ae](https://github.com/electron-userland/electron-builder/commit/958a7ae)), closes [#1301](https://github.com/electron-userland/electron-builder/issues/1301) [#1298](https://github.com/electron-userland/electron-builder/issues/1298)
* **linux:** support any icon name ([5a2631c](https://github.com/electron-userland/electron-builder/commit/5a2631c)), closes [#1399](https://github.com/electron-userland/electron-builder/issues/1399)



<a name="16.4.2"></a>
## [16.4.2](https://github.com/electron-userland/electron-builder/compare/v16.4.1...v16.4.2) (2017-03-27)


### Bug Fixes

* Asar: false, causing exception on app startup with v16.4.0 ([7c6b4ab](https://github.com/electron-userland/electron-builder/commit/7c6b4ab)), closes [#1409](https://github.com/electron-userland/electron-builder/issues/1409)



<a name="16.4.1"></a>
## [16.4.1](https://github.com/electron-userland/electron-builder/compare/v16.4.0...v16.4.1) (2017-03-27)


### Bug Fixes

* removing devDependencies from package.json breaks levelup in electron ([0278efb](https://github.com/electron-userland/electron-builder/commit/0278efb)), closes [#1408](https://github.com/electron-userland/electron-builder/issues/1408)



<a name="16.4.0"></a>
# [16.4.0](https://github.com/electron-userland/electron-builder/compare/v16.3.0...v16.4.0) (2017-03-25)


### Bug Fixes

* ${arch} missing from app-update.yml ([77558e6](https://github.com/electron-userland/electron-builder/commit/77558e6)), closes [#1389](https://github.com/electron-userland/electron-builder/issues/1389)
* Builds fail on building .deb using packaged fpm on Travis ([037fba6](https://github.com/electron-userland/electron-builder/commit/037fba6)), closes [#1402](https://github.com/electron-userland/electron-builder/issues/1402)
* electron-updater throws "Cannot find namespace 'debug'" on TypeScript compile ([0f0de81](https://github.com/electron-userland/electron-builder/commit/0f0de81)), closes [#1405](https://github.com/electron-userland/electron-builder/issues/1405)


### Features

* electronCompile option to disable electron-compile integration ([b4462a2](https://github.com/electron-userland/electron-builder/commit/b4462a2))



<a name="16.3.0"></a>
# [16.3.0](https://github.com/electron-userland/electron-builder/compare/v16.2.1...v16.3.0) (2017-03-24)


### Bug Fixes

* compile using electron-compile not in place, but using cache ([08893e3](https://github.com/electron-userland/electron-builder/commit/08893e3)), closes [#807](https://github.com/electron-userland/electron-builder/issues/807)


### Features

* Allow to use ~/.aws/credentials file as alternative to env variables ([2e59959](https://github.com/electron-userland/electron-builder/commit/2e59959)), closes [#1320](https://github.com/electron-userland/electron-builder/issues/1320)



<a name="16.2.1"></a>
## [16.2.1](https://github.com/electron-userland/electron-builder/compare/v16.2.0...v16.2.1) (2017-03-23)


### Bug Fixes

* one file in asar archive got corrupted ([e208f53](https://github.com/electron-userland/electron-builder/commit/e208f53)), closes [#1400](https://github.com/electron-userland/electron-builder/issues/1400)
* use Muon version in the log message if pack for Muon ([4241521](https://github.com/electron-userland/electron-builder/commit/4241521))



<a name="16.2.0"></a>
# [16.2.0](https://github.com/electron-userland/electron-builder/compare/v16.1.0...v16.2.0) (2017-03-22)


### Bug Fixes

* use lowercased safe artifact name if app name is lowercased ([bfd6635](https://github.com/electron-userland/electron-builder/commit/bfd6635))


### Features

* electron-forge support ([d99a27e](https://github.com/electron-userland/electron-builder/commit/d99a27e))



<a name="16.1.0"></a>
# [16.1.0](https://github.com/electron-userland/electron-builder/compare/v16.0.1...v16.1.0) (2017-03-22)


### Bug Fixes

* Download update from public Github repo failed on Mac ([16bc53c](https://github.com/electron-userland/electron-builder/commit/16bc53c)), closes [#1388](https://github.com/electron-userland/electron-builder/issues/1388)


### Features

* muon support ([4f555da](https://github.com/electron-userland/electron-builder/commit/4f555da)), closes [#1394](https://github.com/electron-userland/electron-builder/issues/1394)
* support file transformers not only for asar ([58061ec](https://github.com/electron-userland/electron-builder/commit/58061ec))



<a name="16.0.1"></a>
## [16.0.1](https://github.com/electron-userland/electron-builder/compare/v16.0.0...v16.0.1) (2017-03-21)


### Bug Fixes

* detect electron-compile in the dev deps ([0b8bff4](https://github.com/electron-userland/electron-builder/commit/0b8bff4))



<a name="16.0.0"></a>
# [16.0.0](https://github.com/electron-userland/electron-builder/compare/v15.6.3...v16.0.0) (2017-03-21)


### Bug Fixes

* S3 urls on mac ([55ebed1](https://github.com/electron-userland/electron-builder/commit/55ebed1)), closes [#1386](https://github.com/electron-userland/electron-builder/issues/1386)


### Features

* electron-compile support ([0b9b1fd](https://github.com/electron-userland/electron-builder/commit/0b9b1fd)), closes [#807](https://github.com/electron-userland/electron-builder/issues/807)



<a name="15.6.3"></a>
## [15.6.3](https://github.com/electron-userland/electron-builder/compare/v15.6.1...v15.6.3) (2017-03-18)


### Bug Fixes

* **updater:** GitHub private repo for windows (#1382) ([51d6e41](https://github.com/electron-userland/electron-builder/commit/51d6e41))
* improve debuggability — print effective config if debug enabled ([927ac40](https://github.com/electron-userland/electron-builder/commit/927ac40))



<a name="15.6.1"></a>
## [15.6.1](https://github.com/electron-userland/electron-builder/compare/v15.6.0...v15.6.1) (2017-03-17)


### Bug Fixes

* S3 URLs (#1373) (#1374) ([ac75e8c](https://github.com/electron-userland/electron-builder/commit/ac75e8c)), closes [#1373](https://github.com/electron-userland/electron-builder/issues/1373)



<a name="15.6.0"></a>
# [15.6.0](https://github.com/electron-userland/electron-builder/compare/v15.5.0...v15.6.0) (2017-03-16)


### Bug Fixes

* productName with utf8 characters cause dmg icon position error ([fbf787c](https://github.com/electron-userland/electron-builder/commit/fbf787c)), closes [#1234](https://github.com/electron-userland/electron-builder/issues/1234)
* removeAuthHeader must strip auth only for AWS ([d7a6760](https://github.com/electron-userland/electron-builder/commit/d7a6760))


### Features

* Multi language support for LICENCES ([bbdc29a](https://github.com/electron-userland/electron-builder/commit/bbdc29a))



<a name="15.5.0"></a>
# [15.5.0](https://github.com/electron-userland/electron-builder/compare/v15.4.3...v15.5.0) (2017-03-15)


### Bug Fixes

* **updater:** github private repo ([fb24e26](https://github.com/electron-userland/electron-builder/commit/fb24e26)), closes [#1370](https://github.com/electron-userland/electron-builder/issues/1370)


### Features

* private GitHub provider ([ce1df10](https://github.com/electron-userland/electron-builder/commit/ce1df10)), closes [#1266](https://github.com/electron-userland/electron-builder/issues/1266)
* **nsis:** do not prompt user to close app before installing on update ([e5682a0](https://github.com/electron-userland/electron-builder/commit/e5682a0)), closes [#1368](https://github.com/electron-userland/electron-builder/issues/1368)



<a name="15.4.3"></a>
## [15.4.3](https://github.com/electron-userland/electron-builder/compare/v15.4.2...v15.4.3) (2017-03-13)


### Bug Fixes

* --ia32 parameter not working as expected anymore ([c37bd00](https://github.com/electron-userland/electron-builder/commit/c37bd00)), closes [#1348](https://github.com/electron-userland/electron-builder/issues/1348)



<a name="15.4.2"></a>
## [15.4.2](https://github.com/electron-userland/electron-builder/compare/v15.4.1...v15.4.2) (2017-03-13)


### Bug Fixes

* artifactName for portable ([8f6247a](https://github.com/electron-userland/electron-builder/commit/8f6247a)), closes [#1340](https://github.com/electron-userland/electron-builder/issues/1340)



<a name="15.4.1"></a>
## [15.4.1](https://github.com/electron-userland/electron-builder/compare/v15.4.0...v15.4.1) (2017-03-13)


### Bug Fixes

* Platform-specific build option targets ignored since 15.2.0 ([2e7b668](https://github.com/electron-userland/electron-builder/commit/2e7b668)), closes [#1355](https://github.com/electron-userland/electron-builder/issues/1355)



<a name="15.4.0"></a>
# [15.4.0](https://github.com/electron-userland/electron-builder/compare/v15.3.0...v15.4.0) (2017-03-12)


### Features

* Don't build when CI run is a pull request ([e1dda14](https://github.com/electron-userland/electron-builder/commit/e1dda14)), closes [#1354](https://github.com/electron-userland/electron-builder/issues/1354)



<a name="15.3.0"></a>
# [15.3.0](https://github.com/electron-userland/electron-builder/compare/v15.2.0...v15.3.0) (2017-03-11)


### Bug Fixes

* **AppImage:** remove nss lib ([0601352](https://github.com/electron-userland/electron-builder/commit/0601352))
* Missing peer dependency: ajv@>=5.0.3-beta.0 ([6d890ee](https://github.com/electron-userland/electron-builder/commit/6d890ee)), closes [#1344](https://github.com/electron-userland/electron-builder/issues/1344)


### Features

* **deployment:** expand macros in all publish options (#1349) ([24fdf1d](https://github.com/electron-userland/electron-builder/commit/24fdf1d))
* **nsis:** always add plugin dir to override nsis plugins ([e8d1d0d](https://github.com/electron-userland/electron-builder/commit/e8d1d0d))



<a name="15.2.0"></a>
# [15.2.0](https://github.com/electron-userland/electron-builder/compare/v15.1.1...v15.2.0) (2017-03-08)


### Bug Fixes

* **linux:** Add dependencies for supporting Electron Tray (libappindicator) & Notifications (libnotify) for more Linux targets (#1339) ([79c94bd](https://github.com/electron-userland/electron-builder/commit/79c94bd)), closes [#1338](https://github.com/electron-userland/electron-builder/issues/1338)


### Features

* Different architectures for different platforms ([f2056fa](https://github.com/electron-userland/electron-builder/commit/f2056fa)), closes [#1314](https://github.com/electron-userland/electron-builder/issues/1314)



<a name="15.1.1"></a>
## [15.1.1](https://github.com/electron-userland/electron-builder/compare/v15.1.0...v15.1.1) (2017-03-06)


### Bug Fixes

* **deployment:** disable automatic detection for S3 ([c4744af](https://github.com/electron-userland/electron-builder/commit/c4744af)), closes [#1334](https://github.com/electron-userland/electron-builder/issues/1334)



<a name="15.1.0"></a>
# [15.1.0](https://github.com/electron-userland/electron-builder/compare/v15.0.1...v15.1.0) (2017-03-06)


### Features

* How to set build_number/FileVersion manually ([3ee8a59](https://github.com/electron-userland/electron-builder/commit/3ee8a59)), closes [#1337](https://github.com/electron-userland/electron-builder/issues/1337)



<a name="15.0.1"></a>
## [15.0.1](https://github.com/electron-userland/electron-builder/compare/v15.0.0...v15.0.1) (2017-03-05)


### Bug Fixes

* writeAsarFile — use close event instead of end ([3f41497](https://github.com/electron-userland/electron-builder/commit/3f41497))



<a name="15.0.0"></a>
# [15.0.0](https://github.com/electron-userland/electron-builder/compare/v14.5.2...v15.0.0) (2017-02-28)


### Bug Fixes

* dmg/pkg in the out dir, not in the subdir mac ([0bba4fe](https://github.com/electron-userland/electron-builder/commit/0bba4fe))
* ensure that out dir exists ([8dd6cd5](https://github.com/electron-userland/electron-builder/commit/8dd6cd5))
* **auto-updater:** handle errors during emit ([ef9b5a6](https://github.com/electron-userland/electron-builder/commit/ef9b5a6)), closes [#1310](https://github.com/electron-userland/electron-builder/issues/1310)


### Features

* **deployment:** support foo/bar repo as short form of owner foo and repo bar ([9d0e1fe](https://github.com/electron-userland/electron-builder/commit/9d0e1fe)), closes [#1227](https://github.com/electron-userland/electron-builder/issues/1227)
* **electron-updater:** find installer exe in bintray artifacts not so strict ([9ac818f](https://github.com/electron-userland/electron-builder/commit/9ac818f)), closes [#1305](https://github.com/electron-userland/electron-builder/issues/1305)


### BREAKING CHANGES

* dmg/pkg in the out dir, not in the subdir mac



<a name="14.5.2"></a>
## [14.5.2](https://github.com/electron-userland/electron-builder/compare/v14.5.1...v14.5.2) (2017-02-28)


### Bug Fixes

* **dmg:** pass -ov flag to overwrite existing dmg ([f4398a7](https://github.com/electron-userland/electron-builder/commit/f4398a7)), closes [#1308](https://github.com/electron-userland/electron-builder/issues/1308)



<a name="14.5.1"></a>
## [14.5.1](https://github.com/electron-userland/electron-builder/compare/v14.5.0...v14.5.1) (2017-02-27)


### Bug Fixes

* directories.output is ignored when building .dmg for a prepackaged app ([3e2798f](https://github.com/electron-userland/electron-builder/commit/3e2798f)), closes [#1308](https://github.com/electron-userland/electron-builder/issues/1308)



<a name="14.5.0"></a>
# [14.5.0](https://github.com/electron-userland/electron-builder/compare/v14.4.2...v14.5.0) (2017-02-27)


### Features

* Allow usage of environmental variables in extraFiles and extraResources ([cfc2715](https://github.com/electron-userland/electron-builder/commit/cfc2715)), closes [#1307](https://github.com/electron-userland/electron-builder/issues/1307)



<a name="14.4.2"></a>
## [14.4.2](https://github.com/electron-userland/electron-builder/compare/v14.4.1...v14.4.2) (2017-02-26)


### Bug Fixes

* **nsis:** update metainfo for nsis-web doesn't use github safe artifact name ([965be90](https://github.com/electron-userland/electron-builder/commit/965be90)), closes [#1227](https://github.com/electron-userland/electron-builder/issues/1227)



<a name="14.4.1"></a>
## [14.4.1](https://github.com/electron-userland/electron-builder/compare/v14.4.0...v14.4.1) (2017-02-25)


### Bug Fixes

* **deployment:** Publishing always fails on circleci #1303 (#1304) ([81b7e46](https://github.com/electron-userland/electron-builder/commit/81b7e46)), closes [#1303](https://github.com/electron-userland/electron-builder/issues/1303)



<a name="14.4.0"></a>
# [14.4.0](https://github.com/electron-userland/electron-builder/compare/v14.3.0...v14.4.0) (2017-02-24)


### Bug Fixes

* Issue with extraFiles not being valid ([f137193](https://github.com/electron-userland/electron-builder/commit/f137193)), closes [#1302](https://github.com/electron-userland/electron-builder/issues/1302)


### Features

* **windows:** Portable Build ([6292855](https://github.com/electron-userland/electron-builder/commit/6292855)), closes [#1157](https://github.com/electron-userland/electron-builder/issues/1157)



<a name="14.3.0"></a>
# [14.3.0](https://github.com/electron-userland/electron-builder/compare/v14.2.0...v14.3.0) (2017-02-24)


### Bug Fixes

* **snap:** allow to set `classic` confinement ([f1d524a](https://github.com/electron-userland/electron-builder/commit/f1d524a))


### Features

* **nsis:** Add option to define custom files to be removed instead of just nuking installation directory ([09f7fde](https://github.com/electron-userland/electron-builder/commit/09f7fde))



<a name="14.2.0"></a>
# [14.2.0](https://github.com/electron-userland/electron-builder/compare/v14.1.1...v14.2.0) (2017-02-24)


### Bug Fixes

* **deployment:** warn if cannot resolve repository ([3fa6259](https://github.com/electron-userland/electron-builder/commit/3fa6259))
* **linux:** use executableName as specified and do not lowercase it ([79077bf](https://github.com/electron-userland/electron-builder/commit/79077bf)), closes [#1291](https://github.com/electron-userland/electron-builder/issues/1291)
* **nsis:** Incorrect app-update.yml for Windows 32bit ([5cfc693](https://github.com/electron-userland/electron-builder/commit/5cfc693)), closes [#1282](https://github.com/electron-userland/electron-builder/issues/1282)


### Features

* **windows:** Support passing the `sha1` of a certificate in Windows codesign ([4be81dc](https://github.com/electron-userland/electron-builder/commit/4be81dc)), closes [#1297](https://github.com/electron-userland/electron-builder/issues/1297)



<a name="14.1.1"></a>
## [14.1.1](https://github.com/electron-userland/electron-builder/compare/v14.1.0...v14.1.1) (2017-02-22)


### Bug Fixes

* Build with prepackaged app doesn't do anything for mac #1284 ([0be724d](https://github.com/electron-userland/electron-builder/commit/0be724d))



<a name="14.1.0"></a>
# [14.1.0](https://github.com/electron-userland/electron-builder/compare/v14.0.1...v14.1.0) (2017-02-22)


### Features

* **AppImage:** Fedora support ([ca7745d](https://github.com/electron-userland/electron-builder/commit/ca7745d))



<a name="14.0.1"></a>
## [14.0.1](https://github.com/electron-userland/electron-builder/compare/v14.0.0...v14.0.1) (2017-02-22)


### Features

* validate config using JSON schema ([d65f8c3](https://github.com/electron-userland/electron-builder/commit/d65f8c3)), closes [#1292](https://github.com/electron-userland/electron-builder/issues/1292) [#1290](https://github.com/electron-userland/electron-builder/issues/1290)



<a name="14.0.0"></a>
# [14.0.0](https://github.com/electron-userland/electron-builder/compare/v13.11.1...v14.0.0) (2017-02-21)


### Features

* **AppImage:** ElementaryOS and libappindicator1 support by default ([580eeaa](https://github.com/electron-userland/electron-builder/commit/580eeaa)), closes [#1082](https://github.com/electron-userland/electron-builder/issues/1082)



<a name="13.11.1"></a>
## [13.11.1](https://github.com/electron-userland/electron-builder/compare/v13.11.0...v13.11.1) (2017-02-20)


### Bug Fixes

* **mac:** dist app quit unexpectedly caused by productName ([3a1042a](https://github.com/electron-userland/electron-builder/commit/3a1042a)), closes [#1278](https://github.com/electron-userland/electron-builder/issues/1278)



<a name="13.11.0"></a>
# [13.11.0](https://github.com/electron-userland/electron-builder/compare/v13.10.1...v13.11.0) (2017-02-19)


### Features

* icon relative or to build resources, or to project ([3f3419a](https://github.com/electron-userland/electron-builder/commit/3f3419a)), closes [#1276](https://github.com/electron-userland/electron-builder/issues/1276)



<a name="13.10.1"></a>
## [13.10.1](https://github.com/electron-userland/electron-builder/compare/v13.10.0...v13.10.1) (2017-02-18)



<a name="13.10.0"></a>
# [13.10.0](https://github.com/electron-userland/electron-builder/compare/v13.9.0...v13.10.0) (2017-02-17)


### Bug Fixes

* increase maxBuffer for xorriso child process (#1274) ([bce672e](https://github.com/electron-userland/electron-builder/commit/bce672e))


### Features

* make description optional (just a warning) ([ae036c6](https://github.com/electron-userland/electron-builder/commit/ae036c6))
* **electron-updater:** abort download ([91613a9](https://github.com/electron-userland/electron-builder/commit/91613a9)), closes [#1150](https://github.com/electron-userland/electron-builder/issues/1150)
* **nsis:** NSIS Special Builds set NSIS_MAX_STRLEN flag ([498db5d](https://github.com/electron-userland/electron-builder/commit/498db5d)), closes [#1267](https://github.com/electron-userland/electron-builder/issues/1267)



<a name="13.9.0"></a>
# [13.9.0](https://github.com/electron-userland/electron-builder/compare/v13.8.2...v13.9.0) (2017-02-15)


### Features

* **snap:** snapcraft 2.26 support ([9c69ce4](https://github.com/electron-userland/electron-builder/commit/9c69ce4)), closes [#1265](https://github.com/electron-userland/electron-builder/issues/1265)
* Different icons for application/file extension with same name on macOS and Windows ([04f11f6](https://github.com/electron-userland/electron-builder/commit/04f11f6)), closes [#1268](https://github.com/electron-userland/electron-builder/issues/1268)



<a name="13.8.2"></a>
## [13.8.2](https://github.com/electron-userland/electron-builder/compare/v13.8.1...v13.8.2) (2017-02-15)


### Bug Fixes

* electron-builder.* config file resolution ([481dfa2](https://github.com/electron-userland/electron-builder/commit/481dfa2))



<a name="13.8.1"></a>
## [13.8.1](https://github.com/electron-userland/electron-builder/compare/v13.8.0...v13.8.1) (2017-02-15)


### Bug Fixes

* ${os} pattern in artifactName does not follow wiki ([38339b9](https://github.com/electron-userland/electron-builder/commit/38339b9)), closes [#1263](https://github.com/electron-userland/electron-builder/issues/1263)
* artifactName option does not work in build section ([6224060](https://github.com/electron-userland/electron-builder/commit/6224060)), closes [#1262](https://github.com/electron-userland/electron-builder/issues/1262)


### Features

* **mac:** The extra entries for `Info.plist` ([1a33a34](https://github.com/electron-userland/electron-builder/commit/1a33a34))



<a name="13.8.0"></a>
# [13.8.0](https://github.com/electron-userland/electron-builder/compare/v13.7.0...v13.8.0) (2017-02-15)


### Bug Fixes

* from as file and to as dir ([3bb2ab8](https://github.com/electron-userland/electron-builder/commit/3bb2ab8)), closes [#1245](https://github.com/electron-userland/electron-builder/issues/1245)


### Features

* **nsis:** metro sidebar, customizable sidebar ([969c0eb](https://github.com/electron-userland/electron-builder/commit/969c0eb)), closes [#1248](https://github.com/electron-userland/electron-builder/issues/1248)



<a name="13.7.0"></a>
# [13.7.0](https://github.com/electron-userland/electron-builder/compare/v13.6.0...v13.7.0) (2017-02-14)


### Bug Fixes

* **electron-updater:** fix missed path in the log messages ([8a75cbb](https://github.com/electron-userland/electron-builder/commit/8a75cbb))
* **squirrel.windows:** sign the Squirrel.Windows executableStub ([c732db2](https://github.com/electron-userland/electron-builder/commit/c732db2)), closes [#1251](https://github.com/electron-userland/electron-builder/issues/1251)


### Features

* **nsins:** create pre initialization hook in installer.nsi (#1255) ([7ed9d7a](https://github.com/electron-userland/electron-builder/commit/7ed9d7a))
* **nsis:** option to delete app data on manual uninstall ([2e1b21e](https://github.com/electron-userland/electron-builder/commit/2e1b21e)), closes [#885](https://github.com/electron-userland/electron-builder/issues/885)



<a name="13.6.0"></a>
# [13.6.0](https://github.com/electron-userland/electron-builder/compare/v13.5.0...v13.6.0) (2017-02-13)


### Bug Fixes

* Incorrect error message ([bc0952e](https://github.com/electron-userland/electron-builder/commit/bc0952e)), closes [#1236](https://github.com/electron-userland/electron-builder/issues/1236)
* **deployment:** NSIS Web Installer update info is not generated #1207 ([9f7c825](https://github.com/electron-userland/electron-builder/commit/9f7c825))
* **electron-updater:** Github Update Fails Due to Undefined ([591873a](https://github.com/electron-userland/electron-builder/commit/591873a)), closes [#1228](https://github.com/electron-userland/electron-builder/issues/1228)
* **nsis:** Custom NSIS Script !include could not find nsh file ([3fbf113](https://github.com/electron-userland/electron-builder/commit/3fbf113)), closes [#1239](https://github.com/electron-userland/electron-builder/issues/1239)


### Features

* **electron-updater:** include full GitHub request url in the error message ([a7d2992](https://github.com/electron-userland/electron-builder/commit/a7d2992))
* **linux:** assert that linux.icon is a directory ([5352b8c](https://github.com/electron-userland/electron-builder/commit/5352b8c)), closes [#1242](https://github.com/electron-userland/electron-builder/issues/1242)
* --config option ([472ef7e](https://github.com/electron-userland/electron-builder/commit/472ef7e)), closes [#1229](https://github.com/electron-userland/electron-builder/issues/1229)
* --config option ([a9f2ad8](https://github.com/electron-userland/electron-builder/commit/a9f2ad8))



<a name="13.5.0"></a>
# [13.5.0](https://github.com/electron-userland/electron-builder/compare/v13.4.0...v13.5.0) (2017-02-10)


### Features

* **nsis:** unicode option High Windows defender CPU usage when accessing NSIS installer ([0e9059c](https://github.com/electron-userland/electron-builder/commit/0e9059c)), closes [#1165](https://github.com/electron-userland/electron-builder/issues/1165)



<a name="13.4.0"></a>
# [13.4.0](https://github.com/electron-userland/electron-builder/compare/v13.3.1...v13.4.0) (2017-02-10)


### Bug Fixes

* identity = null is not respected ([3df2638](https://github.com/electron-userland/electron-builder/commit/3df2638)), closes [#1233](https://github.com/electron-userland/electron-builder/issues/1233)


### Features

* artifact file name pattern for pkg and dmg ([22746bd](https://github.com/electron-userland/electron-builder/commit/22746bd)), closes [#966](https://github.com/electron-userland/electron-builder/issues/966)
* **nsis:** NSIS Web Installer ([7041b5d](https://github.com/electron-userland/electron-builder/commit/7041b5d)), closes [#1207](https://github.com/electron-userland/electron-builder/issues/1207)



<a name="13.3.1"></a>
## [13.3.1](https://github.com/electron-userland/electron-builder/compare/v13.2.0...v13.3.1) (2017-02-09)


### Features

* **deb:** "Priority" attribute for .deb packages ([6497678](https://github.com/electron-userland/electron-builder/commit/6497678)), closes [#1088](https://github.com/electron-userland/electron-builder/issues/1088)
* **pkg:** preinstall and postinstall scripts ([2eb1298](https://github.com/electron-userland/electron-builder/commit/2eb1298)), closes [#1166](https://github.com/electron-userland/electron-builder/issues/1166)
* GitHub Enterprise support ([7cae06a](https://github.com/electron-userland/electron-builder/commit/7cae06a)), closes [#1225](https://github.com/electron-userland/electron-builder/issues/1225)
* **snap:** custom plugs ([3aed0b5](https://github.com/electron-userland/electron-builder/commit/3aed0b5)), closes [#1226](https://github.com/electron-userland/electron-builder/issues/1226)



<a name="13.2.0"></a>
# [13.2.0](https://github.com/electron-userland/electron-builder/compare/v13.1.0...v13.2.0) (2017-02-08)


### Bug Fixes

* **deployment:** log about uploading if non TTY stream ([4546b1c](https://github.com/electron-userland/electron-builder/commit/4546b1c))


### Features

* **nsis:** artifact file name pattern ([3d39fa6](https://github.com/electron-userland/electron-builder/commit/3d39fa6)), closes [#1221](https://github.com/electron-userland/electron-builder/issues/1221) [#1219](https://github.com/electron-userland/electron-builder/issues/1219)



<a name="13.1.0"></a>
# [13.1.0](https://github.com/electron-userland/electron-builder/compare/v13.0.0...v13.1.0) (2017-02-07)


### Features

* S3 AWS Publishing ([fd4fc0f](https://github.com/electron-userland/electron-builder/commit/fd4fc0f))
* cancellable and progressable publishing ([a24f12c](https://github.com/electron-userland/electron-builder/commit/a24f12c))



<a name="13.0.0"></a>
# [13.0.0](https://github.com/electron-userland/electron-builder/compare/v12.3.1...v13.0.0) (2017-02-04)


### Bug Fixes

* **nsis:** Application Icon Missing from "Remove Programs" and "Settings->Apps & Features" ([9c62be9](https://github.com/electron-userland/electron-builder/commit/9c62be9)), closes [#1108](https://github.com/electron-userland/electron-builder/issues/1108)


### Features

* Remove scripts, devDependencies and build from package.json ([ab41fcf](https://github.com/electron-userland/electron-builder/commit/ab41fcf)), closes [#1212](https://github.com/electron-userland/electron-builder/issues/1212)


### BREAKING CHANGES

* `scripts`, `devDependencies` and `build` automatically removed from package.json



<a name="12.3.1"></a>
## [12.3.1](https://github.com/electron-userland/electron-builder/compare/v12.3.0...v12.3.1) (2017-02-03)


### Bug Fixes

* macOS Auto updater using old update ([4e63640](https://github.com/electron-userland/electron-builder/commit/4e63640)), closes [#1200](https://github.com/electron-userland/electron-builder/issues/1200)
* **electron-updater:** channel & channelFile mismatch for macOS GenericProvider publishing (#1203) (#1206) ([f23daff](https://github.com/electron-userland/electron-builder/commit/f23daff))



<a name="12.3.0"></a>
# [12.3.0](https://github.com/electron-userland/electron-builder/compare/v12.2.0...v12.3.0) (2017-02-02)


### Bug Fixes

* **deployment:** Artifacts still get pushed to github releases marked as published ([3987b06](https://github.com/electron-userland/electron-builder/commit/3987b06)), closes [#1197](https://github.com/electron-userland/electron-builder/issues/1197)


### Features

* **electron-updater:** add releaseNotes and releaseName to autoUpdate ([45c93bf](https://github.com/electron-userland/electron-builder/commit/45c93bf)), closes [#1174](https://github.com/electron-userland/electron-builder/issues/1174)
* build prepackaged app.asar ([60e1406](https://github.com/electron-userland/electron-builder/commit/60e1406)), closes [#1102](https://github.com/electron-userland/electron-builder/issues/1102)



<a name="12.2.0"></a>
# [12.2.0](https://github.com/electron-userland/electron-builder/compare/v12.1.0...v12.2.0) (2017-02-01)


### Bug Fixes

* **electron-updater:** Autoupdater problem on mac if space in the URL ([e5d58e2](https://github.com/electron-userland/electron-builder/commit/e5d58e2)), closes [#1192](https://github.com/electron-userland/electron-builder/issues/1192)


### Features

* **linux:** ability to specify custom path to linux icon set ([a2f64bb](https://github.com/electron-userland/electron-builder/commit/a2f64bb)), closes [#1176](https://github.com/electron-userland/electron-builder/issues/1176)
* ${os} and ${arch} in publish.url ([6863896](https://github.com/electron-userland/electron-builder/commit/6863896)), closes [#1194](https://github.com/electron-userland/electron-builder/issues/1194)



<a name="12.1.0"></a>
# [12.1.0](https://github.com/electron-userland/electron-builder/compare/v12.0.3...v12.1.0) (2017-01-31)


### Bug Fixes

* always revalidate cache ([02a96f4](https://github.com/electron-userland/electron-builder/commit/02a96f4)), closes [#1186](https://github.com/electron-userland/electron-builder/issues/1186)


### Features

* allow `./` in the file pattern ([1152f2b](https://github.com/electron-userland/electron-builder/commit/1152f2b))
* file mappings ([55e2f0d](https://github.com/electron-userland/electron-builder/commit/55e2f0d)), closes [#1119](https://github.com/electron-userland/electron-builder/issues/1119)



<a name="12.0.3"></a>
## [12.0.3](https://github.com/electron-userland/electron-builder/compare/v12.0.2...v12.0.3) (2017-01-29)


### Features

* **nsis:** Pass --update flag to uninstaller when auto updating an application ([505a63d](https://github.com/electron-userland/electron-builder/commit/505a63d)), closes [#1162](https://github.com/electron-userland/electron-builder/issues/1162)



<a name="12.0.2"></a>
## [12.0.2](https://github.com/electron-userland/electron-builder/compare/v12.0.1...v12.0.2) (2017-01-29)


### Bug Fixes

* **deployment:** warn "A release is already published" instead of error ([5d64693](https://github.com/electron-userland/electron-builder/commit/5d64693)), closes [#1183](https://github.com/electron-userland/electron-builder/issues/1183)
* **nsis:** add `+` as safe symbol for product name ([e7e2a82](https://github.com/electron-userland/electron-builder/commit/e7e2a82))
* deepAssign error without config ([5d72c10](https://github.com/electron-userland/electron-builder/commit/5d72c10)), closes [#1177](https://github.com/electron-userland/electron-builder/issues/1177)


### Features

* **electron-updater:** add requestHeaders option ([dd1320d](https://github.com/electron-userland/electron-builder/commit/dd1320d)), closes [#1175](https://github.com/electron-userland/electron-builder/issues/1175)



<a name="12.0.1"></a>
## [12.0.1](https://github.com/electron-userland/electron-builder/compare/v12.0.0...v12.0.1) (2017-01-27)


### Bug Fixes

* **deployment:** Error on CI build when GH_TOKEN not set for external PRs ([ee32575](https://github.com/electron-userland/electron-builder/commit/ee32575)), closes [#1178](https://github.com/electron-userland/electron-builder/issues/1178)



<a name="12.0.0"></a>
# [12.0.0](https://github.com/electron-userland/electron-builder/compare/v11.7.0...v12.0.0) (2017-01-26)


### Features

* **nsis:** use productName rather than name for install path if matches /^[-_0-9a-zA-Z ]+$/ ([2539cfb](https://github.com/electron-userland/electron-builder/commit/2539cfb)), closes [#1100](https://github.com/electron-userland/electron-builder/issues/1100) [#767](https://github.com/electron-userland/electron-builder/issues/767) [#1104](https://github.com/electron-userland/electron-builder/issues/1104)


### BREAKING CHANGES

* **nsis:** installation path change



<a name="11.7.0"></a>
# [11.7.0](https://github.com/electron-userland/electron-builder/compare/v11.6.1...v11.7.0) (2017-01-26)


### Features

* **nsis:** Show welcome and finish page duing uninstall (#1173) ([aa43344](https://github.com/electron-userland/electron-builder/commit/aa43344))



<a name="11.6.1"></a>
## [11.6.1](https://github.com/electron-userland/electron-builder/compare/v11.6.0...v11.6.1) (2017-01-25)


### Bug Fixes

* Error during signing when running as Windows SYSTEM user ([688111e](https://github.com/electron-userland/electron-builder/commit/688111e)), closes [#1164](https://github.com/electron-userland/electron-builder/issues/1164)



<a name="11.6.0"></a>
# [11.6.0](https://github.com/electron-userland/electron-builder/compare/v11.5.2...v11.6.0) (2017-01-25)


### Features

* **electron-updater:** cannot use updater without administrator privileges ([7c2973d](https://github.com/electron-userland/electron-builder/commit/7c2973d)), closes [#1133](https://github.com/electron-userland/electron-builder/issues/1133)



<a name="11.5.2"></a>
## [11.5.2](https://github.com/electron-userland/electron-builder/compare/v11.5.1...v11.5.2) (2017-01-24)


### Bug Fixes

* **deployment:** another fix for "only first artifact is uploaded to GitHub" ([93b4d59](https://github.com/electron-userland/electron-builder/commit/93b4d59)), closes [#1133](https://github.com/electron-userland/electron-builder/issues/1133)
* **nsis:** Must be error if file association is set, but perMachine not ([96c8ed9](https://github.com/electron-userland/electron-builder/commit/96c8ed9)), closes [#772](https://github.com/electron-userland/electron-builder/issues/772)



<a name="11.5.1"></a>
## [11.5.1](https://github.com/electron-userland/electron-builder/compare/v11.5.0...v11.5.1) (2017-01-21)


### Bug Fixes

* Arch & pacman use i686 instead of i386 and pkg.tar.xz (#1148) ([5fe94ee](https://github.com/electron-userland/electron-builder/commit/5fe94ee))


### Features

* **deployment:** Only first artifact is uploaded to GitHub ([e3ab55b](https://github.com/electron-userland/electron-builder/commit/e3ab55b)), closes [#1133](https://github.com/electron-userland/electron-builder/issues/1133)
* **electron-updater:** NSIS autoUpdater.setFeedURL throws error ([eb6a453](https://github.com/electron-userland/electron-builder/commit/eb6a453)), closes [#1105](https://github.com/electron-userland/electron-builder/issues/1105)



<a name="11.5.0"></a>
# [11.5.0](https://github.com/electron-userland/electron-builder/compare/v11.4.4...v11.5.0) (2017-01-18)


### Bug Fixes

* make file association name optional ([248855c](https://github.com/electron-userland/electron-builder/commit/248855c)), closes [#1069](https://github.com/electron-userland/electron-builder/issues/1069)


### Features

* **electron-updater:** Port support for downloads, Protocol support for generic backend ([8d883f1](https://github.com/electron-userland/electron-builder/commit/8d883f1))



<a name="11.4.4"></a>
## [11.4.4](https://github.com/electron-userland/electron-builder/compare/v11.4.3...v11.4.4) (2017-01-17)


### Bug Fixes

* **publish:** resolve any publish configuration — not only string ([98c2c8e](https://github.com/electron-userland/electron-builder/commit/98c2c8e))



<a name="11.4.3"></a>
## [11.4.3](https://github.com/electron-userland/electron-builder/compare/v11.4.1...v11.4.3) (2017-01-16)


### Bug Fixes

* generate latest-mac.json for github in the github directory ([8670d5a](https://github.com/electron-userland/electron-builder/commit/8670d5a))
* **snap:** interface 'platform' doesn't exist ([ade922c](https://github.com/electron-userland/electron-builder/commit/ade922c)), closes [#1123](https://github.com/electron-userland/electron-builder/issues/1123)



<a name="11.4.1"></a>
## [11.4.1](https://github.com/electron-userland/electron-builder/compare/v11.4.0...v11.4.1) (2017-01-16)


### Bug Fixes

* **AppImage:** include libappindicator1 in AppImage ([df7d316](https://github.com/electron-userland/electron-builder/commit/df7d316)), closes [#1082](https://github.com/electron-userland/electron-builder/issues/1082)



<a name="11.4.0"></a>
# [11.4.0](https://github.com/electron-userland/electron-builder/compare/v11.3.0...v11.4.0) (2017-01-15)


### Bug Fixes

* **squirrel.windows:** Crash after autoupdate downloads nuget package ([d10ba78](https://github.com/electron-userland/electron-builder/commit/d10ba78)), closes [#1101](https://github.com/electron-userland/electron-builder/issues/1101)


### Features

* **electron-updater:** Electron Auto Updater MacOS support ([067d5c7](https://github.com/electron-userland/electron-builder/commit/067d5c7))
* Separate build config from package.json ([ecfdc65](https://github.com/electron-userland/electron-builder/commit/ecfdc65)), closes [#1109](https://github.com/electron-userland/electron-builder/issues/1109)



<a name="11.3.0"></a>
# [11.3.0](https://github.com/electron-userland/electron-builder/compare/v11.2.5...v11.3.0) (2017-01-14)


### Bug Fixes

* **docker:** add missing libcurl3 for osslsigncode (#1116) ([f0a553a](https://github.com/electron-userland/electron-builder/commit/f0a553a))
* **electron-updater:** Add better error handling for github releases (#1114) ([9dc5bc9](https://github.com/electron-userland/electron-builder/commit/9dc5bc9)), closes [#1112](https://github.com/electron-userland/electron-builder/issues/1112)



<a name="11.2.5"></a>
## [11.2.5](https://github.com/electron-userland/electron-builder/compare/v11.2.4...v11.2.5) (2017-01-12)


### Bug Fixes

* **codeSign:** signing with "Mac Developer" failed #1103 ([88682e8](https://github.com/electron-userland/electron-builder/commit/88682e8))



<a name="11.2.4"></a>
## [11.2.4](https://github.com/electron-userland/electron-builder/compare/v11.2.1...v11.2.4) (2017-01-11)



<a name="11.2.1"></a>
## [11.2.1](https://github.com/electron-userland/electron-builder/compare/v11.2.0...v11.2.1) (2017-01-09)


### Bug Fixes

* do not fail if cannot rebuild optional dep ([f67b7d2](https://github.com/electron-userland/electron-builder/commit/f67b7d2)), closes [#1075](https://github.com/electron-userland/electron-builder/issues/1075)



<a name="11.2.0"></a>
# [11.2.0](https://github.com/electron-userland/electron-builder/compare/v11.1.1...v11.2.0) (2017-01-08)


### Bug Fixes

* **electron-auto-updater:** uncaught SHA2 checksum mismatch exception ([cb87588](https://github.com/electron-userland/electron-builder/commit/cb87588))


### Features

* linked dirs outside of projects (e.g. linked modules) ([2364a1c](https://github.com/electron-userland/electron-builder/commit/2364a1c)), closes [#675](https://github.com/electron-userland/electron-builder/issues/675)



<a name="11.1.1"></a>
## [11.1.1](https://github.com/electron-userland/electron-builder/compare/v1.1.1...v11.1.1) (2017-01-06)


### Bug Fixes

* to preserve compatibility with old electron-auto-updater (< 0.10.0), we upload file with path specific for GitHub ([c06f3f4](https://github.com/electron-userland/electron-builder/commit/c06f3f4))



<a name="11.1.0"></a>
# [11.1.0](https://github.com/electron-userland/electron-builder/compare/v11.0.0...v11.1.0) (2017-01-05)


### Features

* **nsis:** Change installation directory when not using 'oneClick' with NSIS ([06b0103](https://github.com/electron-userland/electron-builder/commit/06b0103)), closes [#596](https://github.com/electron-userland/electron-builder/issues/596)



<a name="11.0.0"></a>
# [11.0.0](https://github.com/electron-userland/electron-builder/compare/v10.17.2...v11.0.0) (2017-01-05)


### Bug Fixes

* **electron-builder-http:** electron-auto-updater request can download so fast that the first few chunks arrive before ensureDirPromise has finished for configurePipes to run ([cb85790](https://github.com/electron-userland/electron-builder/commit/cb85790)), closes [#1081](https://github.com/electron-userland/electron-builder/issues/1081)
* electron-builder not generating "latest.yml" file ([0f1fc4d](https://github.com/electron-userland/electron-builder/commit/0f1fc4d)), closes [#925](https://github.com/electron-userland/electron-builder/issues/925)


### Code Refactoring

* extract electron-builder-squirrel-windows ([6256432](https://github.com/electron-userland/electron-builder/commit/6256432))


### Features

* add beforeBuild callback (#1085) ([35a8cdf](https://github.com/electron-userland/electron-builder/commit/35a8cdf)), closes [#982](https://github.com/electron-userland/electron-builder/issues/982)


### BREAKING CHANGES

* To use Squirrel.Windows please install `electron-builder-squirrel-windows` dependency.



<a name="10.17.2"></a>
## [10.17.2](https://github.com/electron-userland/electron-builder/compare/v10.17.0...v10.17.2) (2017-01-04)


### Bug Fixes

* Unhandled rejection SyntaxError: Unexpected token ... ([0c81bf7](https://github.com/electron-userland/electron-builder/commit/0c81bf7)), closes [#1076](https://github.com/electron-userland/electron-builder/issues/1076)
* use transformer to notify about progress ([7fa56bc](https://github.com/electron-userland/electron-builder/commit/7fa56bc)), closes [#1077](https://github.com/electron-userland/electron-builder/issues/1077)
* **dmg:** Can't locate Mac/Finder/DSStore.pm in [@INC](https://github.com/INC) ([8d0e230](https://github.com/electron-userland/electron-builder/commit/8d0e230)), closes [#1079](https://github.com/electron-userland/electron-builder/issues/1079)



<a name="10.17.0"></a>
# [10.17.0](https://github.com/electron-userland/electron-builder/compare/v10.16.0...v10.17.0) (2017-01-03)


### Bug Fixes

* asarUnpack unpacks parent directory when file is specified ([82f16d1](https://github.com/electron-userland/electron-builder/commit/82f16d1)), closes [#1071](https://github.com/electron-userland/electron-builder/issues/1071)


### Features

* **linux:** use ${macro} syntax for linux templates ([fe137fc](https://github.com/electron-userland/electron-builder/commit/fe137fc))



<a name="10.16.0"></a>
# [10.16.0](https://github.com/electron-userland/electron-builder/compare/v10.15.2...v10.16.0) (2017-01-02)


### Features

* **nsis:** allow submenu in start menu in programfiles ([e3faaf1](https://github.com/electron-userland/electron-builder/commit/e3faaf1)), closes [#1063](https://github.com/electron-userland/electron-builder/issues/1063)



<a name="10.15.2"></a>
## [10.15.2](https://github.com/electron-userland/electron-builder/compare/v10.15.1...v10.15.2) (2016-12-31)


### Bug Fixes

* **dmg:** Unable to build with custom path ([3bf8c93](https://github.com/electron-userland/electron-builder/commit/3bf8c93)), closes [#847](https://github.com/electron-userland/electron-builder/issues/847) [#1054](https://github.com/electron-userland/electron-builder/issues/1054)
* **docker:** Docker - wine - bad exe format for rcedit.exe ([920c230](https://github.com/electron-userland/electron-builder/commit/920c230))
* **electron-auto-updater:** Checking for updates from github was failing ([3401630](https://github.com/electron-userland/electron-builder/commit/3401630)), closes [#1038](https://github.com/electron-userland/electron-builder/issues/1038)


### Features

* **docker:** Install chrome & xvfb to allow for e2e testing ([43add64](https://github.com/electron-userland/electron-builder/commit/43add64))



<a name="10.15.1"></a>
## [10.15.1](https://github.com/electron-userland/electron-builder/compare/v10.15.0...v10.15.1) (2016-12-29)


### Bug Fixes

* **linux:** executable breakes if productName given ([2906227](https://github.com/electron-userland/electron-builder/commit/2906227)), closes [#1060](https://github.com/electron-userland/electron-builder/issues/1060)



<a name="10.15.0"></a>
# [10.15.0](https://github.com/electron-userland/electron-builder/compare/v10.14.0...v10.15.0) (2016-12-28)


### Features

* build in distributable format prepackaged directory ([1c59534](https://github.com/electron-userland/electron-builder/commit/1c59534))



<a name="10.14.0"></a>
# [10.14.0](https://github.com/electron-userland/electron-builder/compare/v10.13.1...v10.14.0) (2016-12-28)


### Features

* Adding download-progress event to AutoUpdater (#1042) ([b3a0be0](https://github.com/electron-userland/electron-builder/commit/b3a0be0)), closes [#958](https://github.com/electron-userland/electron-builder/issues/958)



<a name="10.13.1"></a>
## [10.13.1](https://github.com/electron-userland/electron-builder/compare/v10.13.0...v10.13.1) (2016-12-27)


### Bug Fixes

* **appimage:** Linux AppImage target doesn't reuse the launcher icon ([96895cf](https://github.com/electron-userland/electron-builder/commit/96895cf)), closes [#1003](https://github.com/electron-userland/electron-builder/issues/1003)
* **appimage:** USE_SYSTEM_XORRISO env to force usage of system xorriso ([03e43d1](https://github.com/electron-userland/electron-builder/commit/03e43d1))



<a name="10.13.0"></a>
# [10.13.0](https://github.com/electron-userland/electron-builder/compare/v10.12.0...v10.13.0) (2016-12-26)


### Bug Fixes

* **electron-auto-updater:** queue checkForUpdates ([62e0bcb](https://github.com/electron-userland/electron-builder/commit/62e0bcb)), closes [#1045](https://github.com/electron-userland/electron-builder/issues/1045)


### Features

* **snaps:** build snaps on macOs #509 ([f343def](https://github.com/electron-userland/electron-builder/commit/f343def))



<a name="10.12.0"></a>
# [10.12.0](https://github.com/electron-userland/electron-builder/compare/v10.11.0...v10.12.0) (2016-12-25)


### Bug Fixes

* **snap:** reduce deps #509 ([1fc26a5](https://github.com/electron-userland/electron-builder/commit/1fc26a5))


### Features

* **snap:** ubuntu-app-platform (disabled by default) ([a0c0d8e](https://github.com/electron-userland/electron-builder/commit/a0c0d8e))



<a name="10.11.0"></a>
# [10.11.0](https://github.com/electron-userland/electron-builder/compare/v10.10.0...v10.11.0) (2016-12-24)


### Bug Fixes

* Removing the abort trigger from httpExecutor (#1040) ([741df23](https://github.com/electron-userland/electron-builder/commit/741df23)), closes [#1039](https://github.com/electron-userland/electron-builder/issues/1039)
* sha2 checksum error is not catchable ([c10531b](https://github.com/electron-userland/electron-builder/commit/c10531b)), closes [#1010](https://github.com/electron-userland/electron-builder/issues/1010)


### Features

* Build snap packages for Linux ([a7aa979](https://github.com/electron-userland/electron-builder/commit/a7aa979)), closes [#509](https://github.com/electron-userland/electron-builder/issues/509)
* NSIS Updater API to Start Downloading ([eff85c3](https://github.com/electron-userland/electron-builder/commit/eff85c3)), closes [#972](https://github.com/electron-userland/electron-builder/issues/972)



<a name="10.10.0"></a>
# [10.10.0](https://github.com/electron-userland/electron-builder/compare/v10.9.3...v10.10.0) (2016-12-21)


### Features

* LSTypeIsPackage for file associations ([dcf3dbb](https://github.com/electron-userland/electron-builder/commit/dcf3dbb)), closes [#995](https://github.com/electron-userland/electron-builder/issues/995)



<a name="10.9.3"></a>
## [10.9.3](https://github.com/electron-userland/electron-builder/compare/v10.9.2...v10.9.3) (2016-12-21)


### Bug Fixes

* Trim suffix from wine version (#1033) ([090150c](https://github.com/electron-userland/electron-builder/commit/090150c)), closes [#1033](https://github.com/electron-userland/electron-builder/issues/1033) [#1031](https://github.com/electron-userland/electron-builder/issues/1031) [#953](https://github.com/electron-userland/electron-builder/issues/953)



<a name="10.9.2"></a>
## [10.9.2](https://github.com/electron-userland/electron-builder/compare/v10.9.1...v10.9.2) (2016-12-20)


### Bug Fixes

* Stub Executables missing in Squirrel.Windows 1.5.1 ([0ce1a3c](https://github.com/electron-userland/electron-builder/commit/0ce1a3c)), closes [#1011](https://github.com/electron-userland/electron-builder/issues/1011)



<a name="10.9.1"></a>
## [10.9.1](https://github.com/electron-userland/electron-builder/compare/v10.9.0...v10.9.1) (2016-12-20)


### Bug Fixes

* order of platform and arch npm env vars (#1029) ([f01a9f7](https://github.com/electron-userland/electron-builder/commit/f01a9f7)), closes [/github.com/electron-userland/electron-builder/issues/1027#issuecomment-268066701](https://github.com//github.com/electron-userland/electron-builder/issues/1027/issues/issuecomment-268066701)



<a name="10.9.0"></a>
# [10.9.0](https://github.com/electron-userland/electron-builder/compare/v10.8.1...v10.9.0) (2016-12-19)


### Features

* 32 bit appx  ([01604cf](https://github.com/electron-userland/electron-builder/commit/01604cf))
* **appx:** more customizable manifest fields ([cdc7219](https://github.com/electron-userland/electron-builder/commit/cdc7219))
* Set platform npm environment variable ([9249fcd](https://github.com/electron-userland/electron-builder/commit/9249fcd)), closes [#1027](https://github.com/electron-userland/electron-builder/issues/1027)
* Use Electron.Net to send http requests for auto updater ([569dd8b](https://github.com/electron-userland/electron-builder/commit/569dd8b)), closes [#959](https://github.com/electron-userland/electron-builder/issues/959) [#1024](https://github.com/electron-userland/electron-builder/issues/1024)



<a name="10.8.1"></a>
## [10.8.1](https://github.com/electron-userland/electron-builder/compare/v10.8.0...v10.8.1) (2016-12-15)


### Bug Fixes

* yarn detection ([1aaeb30](https://github.com/electron-userland/electron-builder/commit/1aaeb30))



<a name="10.8.0"></a>
# [10.8.0](https://github.com/electron-userland/electron-builder/compare/v10.7.1...v10.8.0) (2016-12-14)


### Bug Fixes

* update nsis to 3.0.1 ([f32d2dc](https://github.com/electron-userland/electron-builder/commit/f32d2dc)), closes [#850](https://github.com/electron-userland/electron-builder/issues/850)
* update nsis to 3.0.1 ([c6044a3](https://github.com/electron-userland/electron-builder/commit/c6044a3)), closes [#850](https://github.com/electron-userland/electron-builder/issues/850)


### Features

* update Squirrel.Windows to 1.5.1 ([97f6e0e](https://github.com/electron-userland/electron-builder/commit/97f6e0e))



<a name="10.7.1"></a>
## [10.7.1](https://github.com/electron-userland/electron-builder/compare/v10.7.0...v10.7.1) (2016-12-14)


### Bug Fixes

* **electron-auto-updater:** load default provider only if custom was not set ([a457d0d](https://github.com/electron-userland/electron-builder/commit/a457d0d))
* ENOENT for symlinks because directory was not created ([76de8f7](https://github.com/electron-userland/electron-builder/commit/76de8f7)), closes [#1002](https://github.com/electron-userland/electron-builder/issues/1002) [#998](https://github.com/electron-userland/electron-builder/issues/998)



<a name="10.7.0"></a>
# [10.7.0](https://github.com/electron-userland/electron-builder/compare/v10.6.1...v10.7.0) (2016-12-12)


### Features

* force application signing ([4faa3fb](https://github.com/electron-userland/electron-builder/commit/4faa3fb)), closes [#975](https://github.com/electron-userland/electron-builder/issues/975)



<a name="10.6.1"></a>
## [10.6.1](https://github.com/electron-userland/electron-builder/compare/v10.6.0...v10.6.1) (2016-12-07)


### Bug Fixes

* improve error message for case of wrongly set electron* dependencies (#986) ([4635ab0](https://github.com/electron-userland/electron-builder/commit/4635ab0))



<a name="10.6.0"></a>
# [10.6.0](https://github.com/electron-userland/electron-builder/compare/v10.5.0...v10.6.0) (2016-12-06)


### Features

* First start after update will start with a flag (#979) ([cb85297](https://github.com/electron-userland/electron-builder/commit/cb85297)), closes [#970](https://github.com/electron-userland/electron-builder/issues/970)



<a name="10.5.0"></a>
# [10.5.0](https://github.com/electron-userland/electron-builder/compare/v10.4.3...v10.5.0) (2016-12-03)


### Features

* custom NSIS installer icon (#969) ([75dd2cb](https://github.com/electron-userland/electron-builder/commit/75dd2cb)), closes [#964](https://github.com/electron-userland/electron-builder/issues/964)



<a name="10.4.3"></a>
## [10.4.3](https://github.com/electron-userland/electron-builder/compare/v10.4.2...v10.4.3) (2016-12-02)


### Bug Fixes

* use productName for FileDescription on Windows (#965) ([3b6af52](https://github.com/electron-userland/electron-builder/commit/3b6af52)), closes [#783](https://github.com/electron-userland/electron-builder/issues/783)



<a name="10.4.2"></a>
## [10.4.2](https://github.com/electron-userland/electron-builder/compare/v10.4.1...v10.4.2) (2016-12-02)


### Bug Fixes

* write remaining files to unpack (#961) ([cbf4e04](https://github.com/electron-userland/electron-builder/commit/cbf4e04))



<a name="10.4.1"></a>
## [10.4.1](https://github.com/electron-userland/electron-builder/compare/v10.4.0...v10.4.1) (2016-12-01)


### Bug Fixes

* **mac:** build.fileAssociations icon links to original file in output ([d289f4b](https://github.com/electron-userland/electron-builder/commit/d289f4b)), closes [#954](https://github.com/electron-userland/electron-builder/issues/954)



<a name="10.4.0"></a>
# [10.4.0](https://github.com/electron-userland/electron-builder/compare/v10.3.0...v10.4.0) (2016-11-30)


### Bug Fixes

* wine version processing (#955) ([da16181](https://github.com/electron-userland/electron-builder/commit/da16181))


### Features

* win code sign timestamp server option ([c2eb8c2](https://github.com/electron-userland/electron-builder/commit/c2eb8c2)), closes [#951](https://github.com/electron-userland/electron-builder/issues/951)



<a name="10.3.0"></a>
# [10.3.0](https://github.com/electron-userland/electron-builder/compare/v10.2.0...v10.3.0) (2016-11-30)


### Bug Fixes

* Not a valid Win32 application ([5d4b747](https://github.com/electron-userland/electron-builder/commit/5d4b747)), closes [#844](https://github.com/electron-userland/electron-builder/issues/844)


### Features

* ability to disable hard links on a CI server ([92af262](https://github.com/electron-userland/electron-builder/commit/92af262))
* exclude yarn-error.log and .jshintrc, remove LICENSE outside of .app ([6c90f30](https://github.com/electron-userland/electron-builder/commit/6c90f30))



<a name="10.2.0"></a>
# [10.2.0](https://github.com/electron-userland/electron-builder/compare/v10.1.0...v10.2.0) (2016-11-29)


### Features

* **nsis:** use name instead of product name as inst dir ([640fea0](https://github.com/electron-userland/electron-builder/commit/640fea0)), closes [#926](https://github.com/electron-userland/electron-builder/issues/926) [#941](https://github.com/electron-userland/electron-builder/issues/941) [#810](https://github.com/electron-userland/electron-builder/issues/810) [#928](https://github.com/electron-userland/electron-builder/issues/928)



<a name="10.1.0"></a>
# [10.1.0](https://github.com/electron-userland/electron-builder/compare/v10.0.0...v10.1.0) (2016-11-28)


### Features

* use hardlinks if possible, do not create empty dirs ([3f97b86](https://github.com/electron-userland/electron-builder/commit/3f97b86)), closes [#732](https://github.com/electron-userland/electron-builder/issues/732)



<a name="10.0.0"></a>
# [10.0.0](https://github.com/electron-userland/electron-builder/compare/v9.2.0...v10.0.0) (2016-11-26)


### Bug Fixes

* Unable to build package because of asarUnpack ([e3cfa8e](https://github.com/electron-userland/electron-builder/commit/e3cfa8e)), closes [#937](https://github.com/electron-userland/electron-builder/issues/937)


### Features

* if only ignored patterns are specified — all not ignored files is copied ([a55c573](https://github.com/electron-userland/electron-builder/commit/a55c573)), closes [#927](https://github.com/electron-userland/electron-builder/issues/927)


### BREAKING CHANGES

* asar.unpackDir, asar.unpack, asar-unpack-dir, asar-unpack were removed — please use build.asarUnpack instead



<a name="9.2.0"></a>
# [9.2.0](https://github.com/electron-userland/electron-builder/compare/v9.1.0...v9.2.0) (2016-11-25)


### Features

* **nsis:** NSIS with oneClick set to true does not relaunch the app after update ([00a8d36](https://github.com/electron-userland/electron-builder/commit/00a8d36)), closes [#884](https://github.com/electron-userland/electron-builder/issues/884)
* **windows:** Windows Store support (AppX target) ([f4d7a2e](https://github.com/electron-userland/electron-builder/commit/f4d7a2e)), closes [#782](https://github.com/electron-userland/electron-builder/issues/782)



<a name="9.1.0"></a>
# [9.1.0](https://github.com/electron-userland/electron-builder/compare/v9.0.1...v9.1.0) (2016-11-19)


### Features

* electronDownload instead of download #921 ([8463bef](https://github.com/electron-userland/electron-builder/commit/8463bef))
* rename LICENSE from electron dist to LICENSE.electron.txt ([e05cd17](https://github.com/electron-userland/electron-builder/commit/e05cd17)), closes [#916](https://github.com/electron-userland/electron-builder/issues/916)



<a name="9.0.1"></a>
## [9.0.1](https://github.com/electron-userland/electron-builder/compare/v9.0.0...v9.0.1) (2016-11-19)


### Bug Fixes

* snap support, desktop integration attempt #509 ([223a6aa](https://github.com/electron-userland/electron-builder/commit/223a6aa))



<a name="9.0.0"></a>
# [9.0.0](https://github.com/electron-userland/electron-builder/compare/v8.7.0...v9.0.0) (2016-11-19)


### Bug Fixes

* **mac:** App rejected when Mac Developer certificate is in keychain #890 ([386853a](https://github.com/electron-userland/electron-builder/commit/386853a))


### Features

* **deb:** Replace ia32 arch name with i386 in package filename ([73e54c4](https://github.com/electron-userland/electron-builder/commit/73e54c4)), closes [#915](https://github.com/electron-userland/electron-builder/issues/915)
* **linux:** lowercased linux executable ([ff7a8c3](https://github.com/electron-userland/electron-builder/commit/ff7a8c3))


### BREAKING CHANGES

* **deb:** Replace ia32 arch name with i386 in package filename
* **linux:** Linux executable name is always lowercased



<a name="8.7.0"></a>
# [8.7.0](https://github.com/electron-userland/electron-builder/compare/v8.6.0...v8.7.0) (2016-11-18)


### Features

* **linux:** Build snap packages for Linux #509 ([1bd54f7](https://github.com/electron-userland/electron-builder/commit/1bd54f7))



<a name="8.6.0"></a>
# [8.6.0](https://github.com/electron-userland/electron-builder/compare/v8.5.3...v8.6.0) (2016-11-15)


### Bug Fixes

* Auto updater "error" event does not contain error message ([7be5391](https://github.com/electron-userland/electron-builder/commit/7be5391)), closes [#900](https://github.com/electron-userland/electron-builder/issues/900)
* auto-unpacked files are not copied ([5f2a1c6](https://github.com/electron-userland/electron-builder/commit/5f2a1c6)), closes [#843](https://github.com/electron-userland/electron-builder/issues/843)


### Features

* Surround [version]-[revision] with underscores rather than dashes in filenames ([1057499](https://github.com/electron-userland/electron-builder/commit/1057499)), closes [#803](https://github.com/electron-userland/electron-builder/issues/803)


### BREAKING CHANGES

* Debian binary package naming convention is [name]_[version]-[revision]_[arch].deb



<a name="8.5.3"></a>
## [8.5.3](https://github.com/electron-userland/electron-builder/compare/v8.5.2...v8.5.3) (2016-11-13)


### Bug Fixes

* **mas:** mas app crashing after signing ([87f5ea7](https://github.com/electron-userland/electron-builder/commit/87f5ea7)), closes [#897](https://github.com/electron-userland/electron-builder/issues/897)



<a name="8.5.2"></a>
## [8.5.2](https://github.com/electron-userland/electron-builder/compare/v8.5.1...v8.5.2) (2016-11-12)


### Bug Fixes

* **nsis:** NSIS installer "CHECK_APP_RUNNING" breaks if installer has same executable file name as app ([ec3c15d](https://github.com/electron-userland/electron-builder/commit/ec3c15d)), closes [#894](https://github.com/electron-userland/electron-builder/issues/894)



<a name="8.5.1"></a>
## [8.5.1](https://github.com/electron-userland/electron-builder/compare/v8.5.0...v8.5.1) (2016-11-12)


### Bug Fixes

* regression — additionalArgs is not passed to npm rebuild ([92ad554](https://github.com/electron-userland/electron-builder/commit/92ad554))



<a name="8.5.0"></a>
# [8.5.0](https://github.com/electron-userland/electron-builder/compare/v8.4.1...v8.5.0) (2016-11-12)


### Bug Fixes

* Auto updater "error" event does not contain error message ([1b52c94](https://github.com/electron-userland/electron-builder/commit/1b52c94)), closes [#900](https://github.com/electron-userland/electron-builder/issues/900)


### Features

* **api:** Get or Specify Final Build exe or dmg file names ([f31a20d](https://github.com/electron-userland/electron-builder/commit/f31a20d)), closes [#899](https://github.com/electron-userland/electron-builder/issues/899)



<a name="8.4.1"></a>
## [8.4.1](https://github.com/electron-userland/electron-builder/compare/v8.4.0...v8.4.1) (2016-11-12)


### Bug Fixes

* Changing Icons (not updating on dist output) ([b6951ad](https://github.com/electron-userland/electron-builder/commit/b6951ad)), closes [#840](https://github.com/electron-userland/electron-builder/issues/840)



<a name="8.4.0"></a>
# [8.4.0](https://github.com/electron-userland/electron-builder/compare/v8.3.0...v8.4.0) (2016-11-12)


### Features

* more performant and reliable npm rebuild ([20026f1](https://github.com/electron-userland/electron-builder/commit/20026f1))



<a name="8.3.0"></a>
# [8.3.0](https://github.com/electron-userland/electron-builder/compare/v8.2.1...v8.3.0) (2016-11-11)


### Features

* asarUnpack ([8a8ccad](https://github.com/electron-userland/electron-builder/commit/8a8ccad))



<a name="8.2.1"></a>
## [8.2.1](https://github.com/electron-userland/electron-builder/compare/v8.2.0...v8.2.1) (2016-11-11)


### Bug Fixes

* **linux:** report "Building ..." ([ff8a436](https://github.com/electron-userland/electron-builder/commit/ff8a436))
* No error if no valid cert to sign mac app ([22f73c0](https://github.com/electron-userland/electron-builder/commit/22f73c0)), closes [#897](https://github.com/electron-userland/electron-builder/issues/897)



<a name="8.2.0"></a>
# [8.2.0](https://github.com/electron-userland/electron-builder/compare/v8.1.0...v8.2.0) (2016-11-11)


### Bug Fixes

* App rejected when Mac Developer certificate is in keychain ([9edadb5](https://github.com/electron-userland/electron-builder/commit/9edadb5)), closes [#890](https://github.com/electron-userland/electron-builder/issues/890)


### Features

* ignore *.d.ts by default, include package.json in any case ([6ce683f](https://github.com/electron-userland/electron-builder/commit/6ce683f))



<a name="8.1.0"></a>
# [8.1.0](https://github.com/electron-userland/electron-builder/compare/v8.0.0...v8.1.0) (2016-11-10)


### Bug Fixes

* flatDependencies regression ([edc39a8](https://github.com/electron-userland/electron-builder/commit/edc39a8)), closes [#895](https://github.com/electron-userland/electron-builder/issues/895)


### Features

* install-app-deps rebuilds native deps for any project structure ([6532e9f](https://github.com/electron-userland/electron-builder/commit/6532e9f))



<a name="8.0.0"></a>
# [8.0.0](https://github.com/electron-userland/electron-builder/compare/v7.26.0...v8.0.0) (2016-11-10)


### Chores

* remove "osx" name support — use "mac" instead ([aa05ac0](https://github.com/electron-userland/electron-builder/commit/aa05ac0))


### Features

* nsis target for windows by default ([1bc8d57](https://github.com/electron-userland/electron-builder/commit/1bc8d57))
* rebuild native dependencies for any project structure ([b1ea8cd](https://github.com/electron-userland/electron-builder/commit/b1ea8cd))


### BREAKING CHANGES

* "nsis" target is default now. Not "squirrel" (Squirrel.Windows)
If you have existing app, please set "build.win.target" to "squirrel".
Auto-update — please see https://github.com/electron-userland/electron-builder/wiki/Auto-Update
* remove "osx" name support — use "mac" instead
* rebuild native dependencies for any project structure



<a name="7.26.0"></a>
# [7.26.0](https://github.com/electron-userland/electron-builder/compare/v7.25.0...v7.26.0) (2016-11-09)


### Features

* Yarn Support (rebuild) ([94cc7be](https://github.com/electron-userland/electron-builder/commit/94cc7be)), closes [#861](https://github.com/electron-userland/electron-builder/issues/861)


### Performance Improvements

* dev or extra deps ([e89934d](https://github.com/electron-userland/electron-builder/commit/e89934d))
* walk dir ([525bb91](https://github.com/electron-userland/electron-builder/commit/525bb91))



<a name="7.25.0"></a>
# [7.25.0](https://github.com/electron-userland/electron-builder/compare/v7.24.2...v7.25.0) (2016-11-08)


### Features

* **nsis:** Specify install dir based on architecture (#889) ([895411f](https://github.com/electron-userland/electron-builder/commit/895411f))



<a name="7.24.2"></a>
## [7.24.2](https://github.com/electron-userland/electron-builder/compare/v7.24.1...v7.24.2) (2016-11-07)


### Bug Fixes

* Cannot use NSIS StrFunc header ([4cbdc31](https://github.com/electron-userland/electron-builder/commit/4cbdc31)), closes [#888](https://github.com/electron-userland/electron-builder/issues/888)



<a name="7.24.1"></a>
## [7.24.1](https://github.com/electron-userland/electron-builder/compare/v7.24.0...v7.24.1) (2016-11-07)


### Bug Fixes

* github as a provider — latest.yml is not published ([e920584](https://github.com/electron-userland/electron-builder/commit/e920584)), closes [#868](https://github.com/electron-userland/electron-builder/issues/868)



<a name="7.24.0"></a>
# [7.24.0](https://github.com/electron-userland/electron-builder/compare/v7.23.2...v7.24.0) (2016-11-06)


### Features

* **mac:** macOS pkg installer ([265ad20](https://github.com/electron-userland/electron-builder/commit/265ad20)), closes [#52](https://github.com/electron-userland/electron-builder/issues/52)


### Performance Improvements

* **mas:** flat on electron-builder side ([adacf1e](https://github.com/electron-userland/electron-builder/commit/adacf1e))



<a name="7.23.2"></a>
## [7.23.2](https://github.com/electron-userland/electron-builder/compare/v7.23.1...v7.23.2) (2016-11-06)


### Bug Fixes

* github as a provider — latest.yml is not generated ([9d31b42](https://github.com/electron-userland/electron-builder/commit/9d31b42)), closes [#868](https://github.com/electron-userland/electron-builder/issues/868)



<a name="7.23.1"></a>
## [7.23.1](https://github.com/electron-userland/electron-builder/compare/v7.23.0...v7.23.1) (2016-11-05)


### Bug Fixes

* typo in handling of npmArgs (#883) ([f4728c3](https://github.com/electron-userland/electron-builder/commit/f4728c3))



<a name="7.23.0"></a>
# [7.23.0](https://github.com/electron-userland/electron-builder/compare/v7.22.1...v7.23.0) (2016-11-05)


### Bug Fixes

* "contains executable code" — change log to debug ([08913b6](https://github.com/electron-userland/electron-builder/commit/08913b6)), closes [#879](https://github.com/electron-userland/electron-builder/issues/879)


### Features

* add ability to specify additional npm rebuild args (#881) ([eec5b32](https://github.com/electron-userland/electron-builder/commit/eec5b32))
* use cache dir per OS convention ([786250c](https://github.com/electron-userland/electron-builder/commit/786250c))
* use cache dir per OS convention ([20a247c](https://github.com/electron-userland/electron-builder/commit/20a247c))


### Performance Improvements

* walk dir, limit concurrency to 8 (was 32) ([540ee5e](https://github.com/electron-userland/electron-builder/commit/540ee5e))



<a name="7.22.1"></a>
## [7.22.1](https://github.com/electron-userland/electron-builder/compare/v7.22.0...v7.22.1) (2016-11-05)


### Bug Fixes

* update v8 headers URL (#878) ([3bc99e1](https://github.com/electron-userland/electron-builder/commit/3bc99e1))



<a name="7.22.0"></a>
# [7.22.0](https://github.com/electron-userland/electron-builder/compare/v7.21.0...v7.22.0) (2016-11-04)


### Features

* ignore __tests__, tests, example, examples by default ([970caf4](https://github.com/electron-userland/electron-builder/commit/970caf4)), closes [#823](https://github.com/electron-userland/electron-builder/issues/823)



<a name="7.21.0"></a>
# [7.21.0](https://github.com/electron-userland/electron-builder/compare/v7.20.0...v7.21.0) (2016-11-04)


### Bug Fixes

* do not use --no-bin-links by default due to npm bug ([7ab1ba1](https://github.com/electron-userland/electron-builder/commit/7ab1ba1)), closes [#869](https://github.com/electron-userland/electron-builder/issues/869)


### Features

* GitHub publish provider ([9e18cb1](https://github.com/electron-userland/electron-builder/commit/9e18cb1)), closes [#868](https://github.com/electron-userland/electron-builder/issues/868)



<a name="7.20.0"></a>
# [7.20.0](https://github.com/electron-userland/electron-builder/compare/v7.19.1...v7.20.0) (2016-11-03)


### Bug Fixes

* RangeError: Maximum call stack size exceeded ([c5627f8](https://github.com/electron-userland/electron-builder/commit/c5627f8)), closes [#826](https://github.com/electron-userland/electron-builder/issues/826)


### Features

* **linux:** be more restrictive with executable name ([c3136ad](https://github.com/electron-userland/electron-builder/commit/c3136ad)), closes [#806](https://github.com/electron-userland/electron-builder/issues/806)



<a name="7.19.1"></a>
## [7.19.1](https://github.com/electron-userland/electron-builder/compare/v7.19.0...v7.19.1) (2016-11-03)


### Bug Fixes

* **nsis:** machine-wide assisted NSIS installer launches application as administrator ([7ea3d62](https://github.com/electron-userland/electron-builder/commit/7ea3d62)), closes [#864](https://github.com/electron-userland/electron-builder/issues/864)



<a name="7.19.0"></a>
# [7.19.0](https://github.com/electron-userland/electron-builder/compare/v7.18.1...v7.19.0) (2016-11-03)


### Features

* rebuild with --no-bin-links option ([cf24b01](https://github.com/electron-userland/electron-builder/commit/cf24b01)), closes [#869](https://github.com/electron-userland/electron-builder/issues/869)



<a name="7.18.1"></a>
## [7.18.1](https://github.com/electron-userland/electron-builder/compare/v7.18.0...v7.18.1) (2016-11-02)


### Bug Fixes

* **AppImage:** AppImages fail to run if appimaged process is running ([224c00e](https://github.com/electron-userland/electron-builder/commit/224c00e)), closes [#827](https://github.com/electron-userland/electron-builder/issues/827)



<a name="7.18.0"></a>
# [7.18.0](https://github.com/electron-userland/electron-builder/compare/v7.17.1...v7.18.0) (2016-11-02)


### Features

* **nsis:** assisted installer — respect /allusers ([4536e91](https://github.com/electron-userland/electron-builder/commit/4536e91)), closes [#845](https://github.com/electron-userland/electron-builder/issues/845)



<a name="7.17.1"></a>
## [7.17.1](https://github.com/electron-userland/electron-builder/compare/v7.17.0...v7.17.1) (2016-11-02)


### Bug Fixes

* restore dmg.title support ([bc64791](https://github.com/electron-userland/electron-builder/commit/bc64791)), closes [#834](https://github.com/electron-userland/electron-builder/issues/834)
* **nsis:** machine-wide one-click NSIS installer launches application as administrator ([4ac12bf](https://github.com/electron-userland/electron-builder/commit/4ac12bf)), closes [#864](https://github.com/electron-userland/electron-builder/issues/864)



<a name="7.17.0"></a>
# [7.17.0](https://github.com/electron-userland/electron-builder/compare/v7.16.0...v7.17.0) (2016-11-01)


### Features

* generic publish provider ([ad3f299](https://github.com/electron-userland/electron-builder/commit/ad3f299)), closes [#529](https://github.com/electron-userland/electron-builder/issues/529)



<a name="7.16.0"></a>
# [7.16.0](https://github.com/electron-userland/electron-builder/compare/v7.15.2...v7.16.0) (2016-10-31)


### Bug Fixes

* Code Sign with Mac Developer certificates ([7ab9ca6](https://github.com/electron-userland/electron-builder/commit/7ab9ca6)), closes [#812](https://github.com/electron-userland/electron-builder/issues/812)
* attempt to fix "old version dir is empty" ([5c7c4ac](https://github.com/electron-userland/electron-builder/commit/5c7c4ac))


### Features

* **nsis-auto-updater:** auto install on quit ([a3bba92](https://github.com/electron-userland/electron-builder/commit/a3bba92))
* initial yarn support (avoid --cache-min) ([ba1cd4b](https://github.com/electron-userland/electron-builder/commit/ba1cd4b)), closes [#861](https://github.com/electron-userland/electron-builder/issues/861)
* use warning emoji instead of plain text ([772b297](https://github.com/electron-userland/electron-builder/commit/772b297))



<a name="7.15.2"></a>
## [7.15.2](https://github.com/electron-userland/electron-builder/compare/v7.15.1...v7.15.2) (2016-10-28)


### Bug Fixes

* DMG background resource must be resolved using project dir ([8d37b7e](https://github.com/electron-userland/electron-builder/commit/8d37b7e)), closes [#858](https://github.com/electron-userland/electron-builder/issues/858)
* prevent ".directories.output option ignored in package.json" ([e748369](https://github.com/electron-userland/electron-builder/commit/e748369)), closes [#852](https://github.com/electron-userland/electron-builder/issues/852)



<a name="7.15.1"></a>
## [7.15.1](https://github.com/electron-userland/electron-builder/compare/v7.15.0...v7.15.1) (2016-10-28)


### Bug Fixes

* bintray repo setting has no effect, always defaults to generic ([48051cb](https://github.com/electron-userland/electron-builder/commit/48051cb)), closes [#857](https://github.com/electron-userland/electron-builder/issues/857)



<a name="7.15.0"></a>
# [7.15.0](https://github.com/electron-userland/electron-builder/compare/v7.14.2...v7.15.0) (2016-10-27)


### Bug Fixes

* rename .app-update.json to app-update.yml #529 ([f69d202](https://github.com/electron-userland/electron-builder/commit/f69d202))
* use own copy of bluebird library (scoped) ([686dc6b](https://github.com/electron-userland/electron-builder/commit/686dc6b))
* **dmg:** do not use -quiet #854 ([74e2006](https://github.com/electron-userland/electron-builder/commit/74e2006))


### Features

*  add ability to specify bintray user ([716ebc6](https://github.com/electron-userland/electron-builder/commit/716ebc6)), closes [#848](https://github.com/electron-userland/electron-builder/issues/848)
* WIN_CSC_KEY_PASSWORD #822 ([99a5f0a](https://github.com/electron-userland/electron-builder/commit/99a5f0a))
* handle available native deps when building on non-native platforms ([81c6bdf](https://github.com/electron-userland/electron-builder/commit/81c6bdf)), closes [#842](https://github.com/electron-userland/electron-builder/issues/842)
* warn when skipping mac app signing due to unsupported platform ([7c810a7](https://github.com/electron-userland/electron-builder/commit/7c810a7)), closes [#849](https://github.com/electron-userland/electron-builder/issues/849)


### Performance Improvements

* lazy imports, get rid of tsAwaiter ([a33e004](https://github.com/electron-userland/electron-builder/commit/a33e004))



<a name="7.14.2"></a>
## [7.14.2](https://github.com/electron-userland/electron-builder/compare/v7.14.1...v7.14.2) (2016-10-18)


### Bug Fixes

* **nsis:** EULA ([a0e7131](https://github.com/electron-userland/electron-builder/commit/a0e7131)), closes [#829](https://github.com/electron-userland/electron-builder/issues/829)



<a name="7.14.1"></a>
## [7.14.1](https://github.com/electron-userland/electron-builder/compare/v7.14.0...v7.14.1) (2016-10-17)


### Bug Fixes

* **bintray:** do not require explicit publish=always (regression) #529 ([6f20e8d](https://github.com/electron-userland/electron-builder/commit/6f20e8d))



<a name="7.14.0"></a>
# [7.14.0](https://github.com/electron-userland/electron-builder/compare/v7.13.1...v7.14.0) (2016-10-17)


### Features

* Code signing for windows and mac in macOS ([d238635](https://github.com/electron-userland/electron-builder/commit/d238635)), closes [#822](https://github.com/electron-userland/electron-builder/issues/822)



<a name="7.13.1"></a>
## [7.13.1](https://github.com/electron-userland/electron-builder/compare/v7.13.0...v7.13.1) (2016-10-16)


### Bug Fixes

* **nsis:** correctly await update info writing and archive creation #529 ([b1ae7d5](https://github.com/electron-userland/electron-builder/commit/b1ae7d5))



<a name="7.13.0"></a>
# [7.13.0](https://github.com/electron-userland/electron-builder/compare/v7.12.2...v7.13.0) (2016-10-13)


### Features

* **dmg:** check appId, dmg.icon, dmg.contents.path ([36ed865](https://github.com/electron-userland/electron-builder/commit/36ed865)), closes [#821](https://github.com/electron-userland/electron-builder/issues/821)



<a name="7.12.2"></a>
## [7.12.2](https://github.com/electron-userland/electron-builder/compare/v7.12.1...v7.12.2) (2016-10-11)


### Bug Fixes

* **dmg:** Perl error when building DMG ([2f1a6e7](https://github.com/electron-userland/electron-builder/commit/2f1a6e7)), closes [#815](https://github.com/electron-userland/electron-builder/issues/815)



<a name="7.12.1"></a>
## [7.12.1](https://github.com/electron-userland/electron-builder/compare/v7.12.0...v7.12.1) (2016-10-10)


### Bug Fixes

* **squirrel.windows:** include output to error message #804 ([5762d0f](https://github.com/electron-userland/electron-builder/commit/5762d0f))



<a name="7.12.0"></a>
# [7.12.0](https://github.com/electron-userland/electron-builder/compare/v7.11.4...v7.12.0) (2016-10-10)


### Features

* bintray publisher configuration ([1a9caa8](https://github.com/electron-userland/electron-builder/commit/1a9caa8))



<a name="7.11.4"></a>
## [7.11.4](https://github.com/electron-userland/electron-builder/compare/v7.11.3...v7.11.4) (2016-10-07)


### Bug Fixes

* **dmg:** type: "file" is not required anymore for app file ([96d9206](https://github.com/electron-userland/electron-builder/commit/96d9206))



<a name="7.11.3"></a>
## [7.11.3](https://github.com/electron-userland/electron-builder/compare/v7.11.2...v7.11.3) (2016-10-07)


### Bug Fixes

* **nsis:** broken nsis ([993dac7](https://github.com/electron-userland/electron-builder/commit/993dac7)), closes [#800](https://github.com/electron-userland/electron-builder/issues/800)



<a name="7.11.2"></a>
## [7.11.2](https://github.com/electron-userland/electron-builder/compare/v7.11.1...v7.11.2) (2016-10-06)


### Bug Fixes

* make install-app-deps also handle skip build flag ([3e34110](https://github.com/electron-userland/electron-builder/commit/3e34110)), closes [#797](https://github.com/electron-userland/electron-builder/issues/797)



<a name="7.11.1"></a>
## [7.11.1](https://github.com/electron-userland/electron-builder/compare/v7.11.0...v7.11.1) (2016-10-06)


### Bug Fixes

* **mac:** Mac archive tar.* doesn't run after extraction ([a185040](https://github.com/electron-userland/electron-builder/commit/a185040)), closes [#784](https://github.com/electron-userland/electron-builder/issues/784)



<a name="7.11.0"></a>
# [7.11.0](https://github.com/electron-userland/electron-builder/compare/v7.10.3...v7.11.0) (2016-10-06)


### Features

* make a setting for --build-from-option flag ([4898eb1](https://github.com/electron-userland/electron-builder/commit/4898eb1)), closes [#787](https://github.com/electron-userland/electron-builder/issues/787) [#790](https://github.com/electron-userland/electron-builder/issues/790)



<a name="7.10.3"></a>
## [7.10.3](https://github.com/electron-userland/electron-builder/compare/v7.10.2...v7.10.3) (2016-10-05)


### Bug Fixes

* **mac:** background image isn't displayed in macOS sierra ([c16ecad](https://github.com/electron-userland/electron-builder/commit/c16ecad)), closes [#789](https://github.com/electron-userland/electron-builder/issues/789)



<a name="7.10.2"></a>
## [7.10.2](https://github.com/electron-userland/electron-builder/compare/v7.10.1...v7.10.2) (2016-10-02)


### Bug Fixes

* **deb:** Can't run generated app due to wrong permission ([c45adca](https://github.com/electron-userland/electron-builder/commit/c45adca)), closes [#786](https://github.com/electron-userland/electron-builder/issues/786)
* **nsis:** do not delete app data by default ([64937b2](https://github.com/electron-userland/electron-builder/commit/64937b2)), closes [#769](https://github.com/electron-userland/electron-builder/issues/769)



<a name="7.10.1"></a>
## [7.10.1](https://github.com/electron-userland/electron-builder/compare/v7.10.0...v7.10.1) (2016-09-30)


### Bug Fixes

* update fpm to 1.6.3 ([7a5252c](https://github.com/electron-userland/electron-builder/commit/7a5252c))



<a name="7.10.0"></a>
# [7.10.0](https://github.com/electron-userland/electron-builder/compare/v7.9.0...v7.10.0) (2016-09-25)


### Features

* Support for Electron for ARM ([6735da5](https://github.com/electron-userland/electron-builder/commit/6735da5)), closes [#778](https://github.com/electron-userland/electron-builder/issues/778)



<a name="7.9.0"></a>
# [7.9.0](https://github.com/electron-userland/electron-builder/compare/v7.8.0...v7.9.0) (2016-09-23)


### Features

* support --extraMetadata.directories ([1a310e3](https://github.com/electron-userland/electron-builder/commit/1a310e3))



<a name="7.8.0"></a>
# [7.8.0](https://github.com/electron-userland/electron-builder/compare/v7.7.0...v7.8.0) (2016-09-23)


### Features

* prune even if two-package.json structure not used ([26b8dac](https://github.com/electron-userland/electron-builder/commit/26b8dac)), closes [#770](https://github.com/electron-userland/electron-builder/issues/770)



<a name="7.7.0"></a>
# [7.7.0](https://github.com/electron-userland/electron-builder/compare/v7.6.0...v7.7.0) (2016-09-23)


### Features

* option to use appId to identify package instead of name #773 ([6f3d365](https://github.com/electron-userland/electron-builder/commit/6f3d365)), closes [#753](https://github.com/electron-userland/electron-builder/issues/753)



<a name="7.6.0"></a>
# [7.6.0](https://github.com/electron-userland/electron-builder/compare/v7.5.0...v7.6.0) (2016-09-22)


### Features

* support --extraMetadata.build.directories ([44ad719](https://github.com/electron-userland/electron-builder/commit/44ad719))



<a name="7.5.0"></a>
# [7.5.0](https://github.com/electron-userland/electron-builder/compare/v7.4.0...v7.5.0) (2016-09-21)


### Features

* **nsis:** option NSIS warnings as errors ([9762991](https://github.com/electron-userland/electron-builder/commit/9762991)), closes [#763](https://github.com/electron-userland/electron-builder/issues/763)



<a name="7.4.0"></a>
# [7.4.0](https://github.com/electron-userland/electron-builder/compare/v7.3.0...v7.4.0) (2016-09-20)


### Features

* specify path to custom Electron build (Electron.app) ([3132610](https://github.com/electron-userland/electron-builder/commit/3132610)), closes [#760](https://github.com/electron-userland/electron-builder/issues/760)



<a name="7.3.0"></a>
# [7.3.0](https://github.com/electron-userland/electron-builder/compare/v7.2.0...v7.3.0) (2016-09-19)


### Features

* support asar in package.json's `main` even when not packaging to asar during the build ([d9bc4e0](https://github.com/electron-userland/electron-builder/commit/d9bc4e0)), closes [#759](https://github.com/electron-userland/electron-builder/issues/759)



<a name="7.2.0"></a>
# [7.2.0](https://github.com/electron-userland/electron-builder/compare/v7.1.0...v7.2.0) (2016-09-19)


### Features

* ignore .gitignore,.gitattributes,.editorconfig,.idea by default ([70abaa3](https://github.com/electron-userland/electron-builder/commit/70abaa3))



<a name="7.1.0"></a>
# [7.1.0](https://github.com/electron-userland/electron-builder/compare/v7.0.1...v7.1.0) (2016-09-19)


### Bug Fixes

* **mac:** forbid "Mac Developer" cert ([32a59f7](https://github.com/electron-userland/electron-builder/commit/32a59f7))


### Features

* use iconutil on macOS to convert icns to iconset ([1ad417f](https://github.com/electron-userland/electron-builder/commit/1ad417f))



<a name="7.0.1"></a>
## [7.0.1](https://github.com/electron-userland/electron-builder/compare/v7.0.0...v7.0.1) (2016-09-18)


### Bug Fixes

* Don't throw an error if version doesn't start with `v´ ([ec8e69e](https://github.com/electron-userland/electron-builder/commit/ec8e69e)), closes [#743](https://github.com/electron-userland/electron-builder/issues/743)



<a name="7.0.0"></a>
# [7.0.0](https://github.com/electron-userland/electron-builder/compare/v6.7.7...v7.0.0) (2016-09-16)


### Bug Fixes

* **deb:** 64 bit deb release artifact filename ([84225d7](https://github.com/electron-userland/electron-builder/commit/84225d7)), closes [#747](https://github.com/electron-userland/electron-builder/issues/747)


### BREAKING CHANGES

* **deb:** x64 deb now has `amd64` arch suffix (previously was no prefix for x64).



<a name="6.7.7"></a>
## [6.7.7](https://github.com/electron-userland/electron-builder/compare/v6.7.6...v6.7.7) (2016-09-16)


### Bug Fixes

* **nsis:** handle unquoted UninstallString #735 ([77f3277](https://github.com/electron-userland/electron-builder/commit/77f3277))



<a name="6.7.6"></a>
## [6.7.6](https://github.com/electron-userland/electron-builder/compare/v6.7.5...v6.7.6) (2016-09-15)


### Bug Fixes

* **nsis:** apostrophe in product name ([63c67ef](https://github.com/electron-userland/electron-builder/commit/63c67ef)), closes [#750](https://github.com/electron-userland/electron-builder/issues/750)



<a name="6.7.5"></a>
## [6.7.5](https://github.com/electron-userland/electron-builder/compare/v6.7.4...v6.7.5) (2016-09-14)


### Bug Fixes

* **nsis:** _? must be last #735 ([517a90b](https://github.com/electron-userland/electron-builder/commit/517a90b))



<a name="6.7.4"></a>
## [6.7.4](https://github.com/electron-userland/electron-builder/compare/v6.7.3...v6.7.4) (2016-09-14)


### Bug Fixes

* **mac:** throw sign error correctly ([cca23b4](https://github.com/electron-userland/electron-builder/commit/cca23b4)), closes [#737](https://github.com/electron-userland/electron-builder/issues/737)
* **nsis:** get InstallLocation from UninstallerString if not found #735 ([431922e](https://github.com/electron-userland/electron-builder/commit/431922e))



<a name="6.7.3"></a>
## [6.7.3](https://github.com/electron-userland/electron-builder/compare/v6.7.2...v6.7.3) (2016-09-11)


### Bug Fixes

* proxy config from npm #585 ([29f6436](https://github.com/electron-userland/electron-builder/commit/29f6436))
* **nsis:** correct fix of #722 (NSIS Installer Not Working on Second Invocation) ([e35933d](https://github.com/electron-userland/electron-builder/commit/e35933d)), closes [#722](https://github.com/electron-userland/electron-builder/issues/722)



<a name="6.7.2"></a>
## [6.7.2](https://github.com/electron-userland/electron-builder/compare/v6.7.1...v6.7.2) (2016-09-11)


### Bug Fixes

* Build fails with TimeOut exception: proxy ([dd61408](https://github.com/electron-userland/electron-builder/commit/dd61408)), closes [#585](https://github.com/electron-userland/electron-builder/issues/585)



<a name="6.7.1"></a>
## [6.7.1](https://github.com/electron-userland/electron-builder/compare/v6.7.0...v6.7.1) (2016-09-10)


### Bug Fixes

* **nsis:** remove old < 6.4.1 versions ([cb538c1](https://github.com/electron-userland/electron-builder/commit/cb538c1)), closes [#735](https://github.com/electron-userland/electron-builder/issues/735)



<a name="6.7.0"></a>
# [6.7.0](https://github.com/electron-userland/electron-builder/compare/v6.6.1...v6.7.0) (2016-09-10)


### Features

* Hidden 'dotfiles' within an extraResources folder aren't copied ([7877f71](https://github.com/electron-userland/electron-builder/commit/7877f71)), closes [#733](https://github.com/electron-userland/electron-builder/issues/733)



<a name="6.6.1"></a>
## [6.6.1](https://github.com/electron-userland/electron-builder/compare/v6.6.0...v6.6.1) (2016-09-09)


### Bug Fixes

* **nsis:** no app icon in Add/Remove program ([e6c1efe](https://github.com/electron-userland/electron-builder/commit/e6c1efe)), closes [#738](https://github.com/electron-userland/electron-builder/issues/738)



<a name="6.6.0"></a>
# [6.6.0](https://github.com/electron-userland/electron-builder/compare/v6.5.2...v6.6.0) (2016-09-09)


### Features

* support CFBundleTypeRole for MacOS CFBundleURLTypes ([888581a](https://github.com/electron-userland/electron-builder/commit/888581a)), closes [#736](https://github.com/electron-userland/electron-builder/issues/736)



<a name="6.5.2"></a>
## [6.5.2](https://github.com/electron-userland/electron-builder/compare/v6.5.1...v6.5.2) (2016-09-08)


### Bug Fixes

* Version `6.3.5` makes build pass even when it fails ([a1b2b0e](https://github.com/electron-userland/electron-builder/commit/a1b2b0e)), closes [#721](https://github.com/electron-userland/electron-builder/issues/721)
* **mas:** Warning when using entitlements.mas.plist ([5031116](https://github.com/electron-userland/electron-builder/commit/5031116)), closes [#729](https://github.com/electron-userland/electron-builder/issues/729)



<a name="6.5.1"></a>
## [6.5.1](https://github.com/electron-userland/electron-builder/compare/v6.5.0...v6.5.1) (2016-09-07)


### Bug Fixes

* **nsis:** uninstaller path should be not quoted #722 ([63ee4cf](https://github.com/electron-userland/electron-builder/commit/63ee4cf))



<a name="6.5.0"></a>
# [6.5.0](https://github.com/electron-userland/electron-builder/compare/v6.4.1...v6.5.0) (2016-09-07)


### Bug Fixes

* Cleanup fail after build ([2e35205](https://github.com/electron-userland/electron-builder/commit/2e35205)), closes [#724](https://github.com/electron-userland/electron-builder/issues/724)
* **nsis:** finally — NSIS Installer Not Working on Second Invocation ([211d63f](https://github.com/electron-userland/electron-builder/commit/211d63f)), closes [#722](https://github.com/electron-userland/electron-builder/issues/722)


### Features

* **linux:** Categories desktop entry ([87616c0](https://github.com/electron-userland/electron-builder/commit/87616c0)), closes [#727](https://github.com/electron-userland/electron-builder/issues/727) [#641](https://github.com/electron-userland/electron-builder/issues/641)



<a name="6.4.1"></a>
## [6.4.1](https://github.com/electron-userland/electron-builder/compare/v6.4.0...v6.4.1) (2016-09-04)


### Bug Fixes

* NSIS Installer Not Working on Second Invocation ([0f1869b](https://github.com/electron-userland/electron-builder/commit/0f1869b))
* NSIS Installer Not Working on Second Invocation #722 ([1b90ec6](https://github.com/electron-userland/electron-builder/commit/1b90ec6))



<a name="6.4.0"></a>
# [6.4.0](https://github.com/electron-userland/electron-builder/compare/v6.3.5...v6.4.0) (2016-09-02)


### Features

* bintray publisher ([138e8e2](https://github.com/electron-userland/electron-builder/commit/138e8e2)), closes [#577](https://github.com/electron-userland/electron-builder/issues/577)



<a name="6.3.5"></a>
## [6.3.5](https://github.com/electron-userland/electron-builder/compare/v6.3.4...v6.3.5) (2016-09-02)


### Bug Fixes

* incorrect log message "ci detected" ([eb827ea](https://github.com/electron-userland/electron-builder/commit/eb827ea))



<a name="6.3.4"></a>
## [6.3.4](https://github.com/electron-userland/electron-builder/compare/v6.3.3...v6.3.4) (2016-09-02)


### Bug Fixes

* **squirrel.windows:** remove RELEASES because Squirrel.Windows doesn't check ([0c592e8](https://github.com/electron-userland/electron-builder/commit/0c592e8)), closes [#713](https://github.com/electron-userland/electron-builder/issues/713)



<a name="6.3.3"></a>
## [6.3.3](https://github.com/electron-userland/electron-builder/compare/v6.3.2...v6.3.3) (2016-09-01)


### Bug Fixes

* **squirrel.windows:** use GH_TOKEN ([e102e3e](https://github.com/electron-userland/electron-builder/commit/e102e3e)), closes [#714](https://github.com/electron-userland/electron-builder/issues/714)



<a name="6.3.2"></a>
## [6.3.2](https://github.com/electron-userland/electron-builder/compare/v6.3.1...v6.3.2) (2016-09-01)


### Bug Fixes

* **mac:** build mac targets on non-macOs ([1398af4](https://github.com/electron-userland/electron-builder/commit/1398af4))
* **squirrel.windows:** The base package release does not exist ([3b1ad57](https://github.com/electron-userland/electron-builder/commit/3b1ad57)), closes [#713](https://github.com/electron-userland/electron-builder/issues/713)



<a name="6.3.1"></a>
## [6.3.1](https://github.com/electron-userland/electron-builder/compare/v6.3.0...v6.3.1) (2016-08-30)


### Bug Fixes

* **nsis:** NSIS perMachine fails if UAC prompt is enabled ([b739f42](https://github.com/electron-userland/electron-builder/commit/b739f42)), closes [#712](https://github.com/electron-userland/electron-builder/issues/712)
* **nsis:** set locale id for legalTrademarks ([91addfe](https://github.com/electron-userland/electron-builder/commit/91addfe)), closes [#672](https://github.com/electron-userland/electron-builder/issues/672)



<a name="6.3.0"></a>
# [6.3.0](https://github.com/electron-userland/electron-builder/compare/v6.2.0...v6.3.0) (2016-08-29)


### Bug Fixes

* **nsis:** no custom icon ([b7b18bc](https://github.com/electron-userland/electron-builder/commit/b7b18bc))


### Features

* **nsis:** assisted per-machine only installer ([a4eeade](https://github.com/electron-userland/electron-builder/commit/a4eeade))



<a name="6.2.0"></a>
# [6.2.0](https://github.com/electron-userland/electron-builder/compare/v6.1.0...v6.2.0) (2016-08-29)


### Features

* **mac:** rename electron.icns to productName.icns ([8fa482e](https://github.com/electron-userland/electron-builder/commit/8fa482e))



<a name="6.1.0"></a>
# [6.1.0](https://github.com/electron-userland/electron-builder/compare/v6.0.3...v6.1.0) (2016-08-29)


### Features

* A crossplatform way to create file associations ([f8840e1](https://github.com/electron-userland/electron-builder/commit/f8840e1)), closes [#409](https://github.com/electron-userland/electron-builder/issues/409)



<a name="6.0.3"></a>
## [6.0.3](https://github.com/electron-userland/electron-builder/compare/v6.0.2...v6.0.3) (2016-08-29)


### Bug Fixes

* **squirrel.windows:** stdout maxBuffer exceeded ([0b84868](https://github.com/electron-userland/electron-builder/commit/0b84868)), closes [#709](https://github.com/electron-userland/electron-builder/issues/709)



<a name="6.0.2"></a>
## [6.0.2](https://github.com/electron-userland/electron-builder/compare/v6.0.1...v6.0.2) (2016-08-27)


### Bug Fixes

* pattern **/*.js still copies all files ([51309bf](https://github.com/electron-userland/electron-builder/commit/51309bf)), closes [#701](https://github.com/electron-userland/electron-builder/issues/701)



<a name="6.0.1"></a>
## [6.0.1](https://github.com/electron-userland/electron-builder/compare/v6.0.0...v6.0.1) (2016-08-27)


### Bug Fixes

* close write steam on finish ([a6b7573](https://github.com/electron-userland/electron-builder/commit/a6b7573)), closes [#706](https://github.com/electron-userland/electron-builder/issues/706)



<a name="6.0.0"></a>
# [6.0.0](https://github.com/electron-userland/electron-builder/compare/v5.35.0...v6.0.0) (2016-08-27)


### Bug Fixes

* add undocumented dereference as workaround of #675 ([9fe326d](https://github.com/electron-userland/electron-builder/commit/9fe326d))
* rename linux to linux-unpacked #670 ([5d404ea](https://github.com/electron-userland/electron-builder/commit/5d404ea))


### Features

* set AppImage as default target for Linux ([8f55a2d](https://github.com/electron-userland/electron-builder/commit/8f55a2d))


### BREAKING CHANGES

* default target for Linux changed from `deb` to `AppImage`



<a name="5.35.0"></a>
# [5.35.0](https://github.com/electron-userland/electron-builder/compare/v5.34.1...v5.35.0) (2016-08-26)


### Features

* support from/to paths in file patterns for extraFiles and extraResources ([308438f](https://github.com/electron-userland/electron-builder/commit/308438f)), closes [#650](https://github.com/electron-userland/electron-builder/issues/650)



<a name="5.34.1"></a>
## [5.34.1](https://github.com/electron-userland/electron-builder/compare/v5.34.0...v5.34.1) (2016-08-22)


### Bug Fixes

* auto-unpack doesn't create file parent dirs ([26c8360](https://github.com/electron-userland/electron-builder/commit/26c8360)), closes [#689](https://github.com/electron-userland/electron-builder/issues/689)



<a name="5.34.0"></a>
# [5.34.0](https://github.com/electron-userland/electron-builder/compare/v5.33.0...v5.34.0) (2016-08-22)


### Bug Fixes

* Getting AppVeyor to Generate an Installer (Build Artifacts) ([bc9d437](https://github.com/electron-userland/electron-builder/commit/bc9d437)), closes [#674](https://github.com/electron-userland/electron-builder/issues/674)


### Features

* custom app scheme ([b7121c5](https://github.com/electron-userland/electron-builder/commit/b7121c5)), closes [#575](https://github.com/electron-userland/electron-builder/issues/575)



<a name="5.33.0"></a>
# [5.33.0](https://github.com/electron-userland/electron-builder/compare/v5.32.1...v5.33.0) (2016-08-22)


### Features

* add node-gyp-rebuild #683 ([e3a5899](https://github.com/electron-userland/electron-builder/commit/e3a5899))



<a name="5.32.1"></a>
## [5.32.1](https://github.com/electron-userland/electron-builder/compare/v5.32.0...v5.32.1) (2016-08-20)


### Bug Fixes

* XDG_DATA_DIRS is missing when starting AppImage on Fedora 24 ([92d4895](https://github.com/electron-userland/electron-builder/commit/92d4895)), closes [#682](https://github.com/electron-userland/electron-builder/issues/682)



<a name="5.32.0"></a>
# [5.32.0](https://github.com/electron-userland/electron-builder/compare/v5.31.1...v5.32.0) (2016-08-20)


### Features

* nodeGypRebuild ([6d433ad](https://github.com/electron-userland/electron-builder/commit/6d433ad)), closes [#683](https://github.com/electron-userland/electron-builder/issues/683)



<a name="5.31.1"></a>
## [5.31.1](https://github.com/electron-userland/electron-builder/compare/v5.31.0...v5.31.1) (2016-08-20)


### Bug Fixes

* pass --build-from-source to force native dep compilation ([ef5f146](https://github.com/electron-userland/electron-builder/commit/ef5f146)), closes [#647](https://github.com/electron-userland/electron-builder/issues/647)



<a name="5.31.0"></a>
# [5.31.0](https://github.com/electron-userland/electron-builder/compare/v5.30.0...v5.31.0) (2016-08-20)


### Features

* **nsis:** per-machine installer automatically removes per-user installation ([834434c](https://github.com/electron-userland/electron-builder/commit/834434c)), closes [#621](https://github.com/electron-userland/electron-builder/issues/621) [#672](https://github.com/electron-userland/electron-builder/issues/672)



<a name="5.30.0"></a>
# [5.30.0](https://github.com/electron-userland/electron-builder/compare/v5.29.0...v5.30.0) (2016-08-19)


### Features

* **nsis:** one-click installer automatically removes old version #621 ([682ddde](https://github.com/electron-userland/electron-builder/commit/682ddde))



<a name="5.29.0"></a>
# [5.29.0](https://github.com/electron-userland/electron-builder/compare/v5.28.2...v5.29.0) (2016-08-17)


### Features

* **nsis:** per-machine installer automatically removes old version #621 ([2c3d8c2](https://github.com/electron-userland/electron-builder/commit/2c3d8c2))



<a name="5.28.2"></a>
## [5.28.2](https://github.com/electron-userland/electron-builder/compare/v5.28.1...v5.28.2) (2016-08-17)


### Bug Fixes

* skip rcedit for .msi installer ([d40e0b5](https://github.com/electron-userland/electron-builder/commit/d40e0b5)), closes [#677](https://github.com/electron-userland/electron-builder/issues/677)



<a name="5.28.1"></a>
## [5.28.1](https://github.com/electron-userland/electron-builder/compare/v5.28.0...v5.28.1) (2016-08-17)


### Bug Fixes

* disable dual-signing for .msi installer ([903148b](https://github.com/electron-userland/electron-builder/commit/903148b))



<a name="5.28.0"></a>
# [5.28.0](https://github.com/electron-userland/electron-builder/compare/v5.27.0...v5.28.0) (2016-08-16)


### Features

* **nsis:** custom icon for file association #409 ([09497cc](https://github.com/electron-userland/electron-builder/commit/09497cc))



<a name="5.27.0"></a>
# [5.27.0](https://github.com/electron-userland/electron-builder/compare/v5.26.0...v5.27.0) (2016-08-16)


### Features

* NSIS sign uninstaller ([17c0a82](https://github.com/electron-userland/electron-builder/commit/17c0a82)), closes [#526](https://github.com/electron-userland/electron-builder/issues/526)



<a name="5.26.0"></a>
# [5.26.0](https://github.com/electron-userland/electron-builder/compare/v5.25.1...v5.26.0) (2016-08-12)


### Bug Fixes

* Build fails due to peer dependency errors ([fcecbf0](https://github.com/electron-userland/electron-builder/commit/fcecbf0)), closes [#611](https://github.com/electron-userland/electron-builder/issues/611)
* Do not trash old build artifacts ([361b369](https://github.com/electron-userland/electron-builder/commit/361b369)), closes [#586](https://github.com/electron-userland/electron-builder/issues/586)
* do not required email for all Linux targets ([ddfa6fc](https://github.com/electron-userland/electron-builder/commit/ddfa6fc))


### Features

* Changing build attributes for different environment ([b9d0139](https://github.com/electron-userland/electron-builder/commit/b9d0139)), closes [#639](https://github.com/electron-userland/electron-builder/issues/639)



<a name="5.25.1"></a>
## [5.25.1](https://github.com/electron-userland/electron-builder/compare/v5.25.0...v5.25.1) (2016-08-12)


### Bug Fixes

* Bump electron-wininstaller-fixed to Squirrel 1.4.4 ([8008734](https://github.com/electron-userland/electron-builder/commit/8008734))



<a name="5.25.0"></a>
# [5.25.0](https://github.com/electron-userland/electron-builder/compare/v5.24.1...v5.25.0) (2016-08-11)


### Bug Fixes

* remove outdated license check ([8665ef4](https://github.com/electron-userland/electron-builder/commit/8665ef4))


### Features

* bundle osslsigncode for Linux ([fc8d6c6](https://github.com/electron-userland/electron-builder/commit/fc8d6c6))



<a name="5.24.1"></a>
## [5.24.1](https://github.com/electron-userland/electron-builder/compare/v5.24.0...v5.24.1) (2016-08-10)


### Bug Fixes

* Some files in app.asar get corrupted ([ee2f7c8](https://github.com/electron-userland/electron-builder/commit/ee2f7c8)), closes [#662](https://github.com/electron-userland/electron-builder/issues/662)



<a name="5.24.0"></a>
# [5.24.0](https://github.com/electron-userland/electron-builder/compare/v5.23.2...v5.24.0) (2016-08-09)


### Features

* **nsis:** multilang installer ([50d27bf](https://github.com/electron-userland/electron-builder/commit/50d27bf)), closes [#643](https://github.com/electron-userland/electron-builder/issues/643) [#646](https://github.com/electron-userland/electron-builder/issues/646)
*  EV certificate code signing (custom /n and /tr) ([e008c19](https://github.com/electron-userland/electron-builder/commit/e008c19)), closes [#627](https://github.com/electron-userland/electron-builder/issues/627) [#590](https://github.com/electron-userland/electron-builder/issues/590)
*  remove OriginalFilename, add LegalTrademarks, add ProductVersion for NSIS ([6a906ac](https://github.com/electron-userland/electron-builder/commit/6a906ac)), closes [#655](https://github.com/electron-userland/electron-builder/issues/655)



<a name="5.23.2"></a>
## [5.23.2](https://github.com/electron-userland/electron-builder/compare/v5.23.1...v5.23.2) (2016-08-05)


### Bug Fixes

* **AppImage:** app bin detection ([06def89](https://github.com/electron-userland/electron-builder/commit/06def89))



<a name="5.23.1"></a>
## [5.23.1](https://github.com/electron-userland/electron-builder/compare/v5.23.0...v5.23.1) (2016-08-05)


### Bug Fixes

* one-click CHECK_APP_RUNNING before SetSilent ([282fc72](https://github.com/electron-userland/electron-builder/commit/282fc72))
* one-click installer — Uninstall Confirm Dialog Option for One-click Windows NSIS #618 ([b3c49cb](https://github.com/electron-userland/electron-builder/commit/b3c49cb))



<a name="5.23.0"></a>
# [5.23.0](https://github.com/electron-userland/electron-builder/compare/v5.22.2...v5.23.0) (2016-08-04)


### Features

* prevent error "Unable to find a valid app" ([1778a8d](https://github.com/electron-userland/electron-builder/commit/1778a8d)), closes [#633](https://github.com/electron-userland/electron-builder/issues/633)
* support electron package https://github.com/electron-userland/electron-prebuilt/issues/160 ([aa0682f](https://github.com/electron-userland/electron-builder/commit/aa0682f))



<a name="5.22.2"></a>
## [5.22.2](https://github.com/electron-userland/electron-builder/compare/v5.22.1...v5.22.2) (2016-08-04)


### Bug Fixes

* Can't build on OSX (x64) since electron-builder 5.19.0 ([753cd08](https://github.com/electron-userland/electron-builder/commit/753cd08)), closes [#635](https://github.com/electron-userland/electron-builder/issues/635)



<a name="5.22.1"></a>
## [5.22.1](https://github.com/electron-userland/electron-builder/compare/v5.20.0...v5.22.1) (2016-08-02)


### Bug Fixes

* AppImage does not run when invoked in unpacked form ([9731225](https://github.com/electron-userland/electron-builder/commit/9731225)), closes [#592](https://github.com/electron-userland/electron-builder/issues/592)
* Failing to sign the Windows build on Linux ([a6a0cd6](https://github.com/electron-userland/electron-builder/commit/a6a0cd6)), closes [#578](https://github.com/electron-userland/electron-builder/issues/578)
* NSIS Installer hangs when being run silently ([d0a4f90](https://github.com/electron-userland/electron-builder/commit/d0a4f90)), closes [#616](https://github.com/electron-userland/electron-builder/issues/616)
* Windows NSIS One-Click Setup Launched while App already running in background ([918a6c0](https://github.com/electron-userland/electron-builder/commit/918a6c0)), closes [#617](https://github.com/electron-userland/electron-builder/issues/617)
* don't take in account just directory `app` without `package.json` ([3418239](https://github.com/electron-userland/electron-builder/commit/3418239))
* extraMetadata — deep assign ([6a5c4bb](https://github.com/electron-userland/electron-builder/commit/6a5c4bb))


### Features

* --extraMetadata for conditional compilation ([da700d4](https://github.com/electron-userland/electron-builder/commit/da700d4)), closes [#494](https://github.com/electron-userland/electron-builder/issues/494)
* Uninstall Confirm Dialog Option for One-click Windows NSIS ([e99047d](https://github.com/electron-userland/electron-builder/commit/e99047d)), closes [#618](https://github.com/electron-userland/electron-builder/issues/618)



<a name="5.20.0"></a>
# [5.20.0](https://github.com/electron-userland/electron-builder/compare/v5.19.1...v5.20.0) (2016-07-29)


### Features

* Make sure compiled app has same hash on different computers ([d773077](https://github.com/electron-userland/electron-builder/commit/d773077)), closes [#604](https://github.com/electron-userland/electron-builder/issues/604)



<a name="5.19.1"></a>
## [5.19.1](https://github.com/electron-userland/electron-builder/compare/v5.19.0...v5.19.1) (2016-07-29)


### Bug Fixes

* Certificate file for sign was gone (provides with file://) under windows ([04a88b0](https://github.com/electron-userland/electron-builder/commit/04a88b0)), closes [#619](https://github.com/electron-userland/electron-builder/issues/619)



<a name="5.19.0"></a>
# [5.19.0](https://github.com/electron-userland/electron-builder/compare/v5.18.0...v5.19.0) (2016-07-28)


### Features

* don't pack into asar node module that contains executable/binary files ([e975881](https://github.com/electron-userland/electron-builder/commit/e975881)), closes [#602](https://github.com/electron-userland/electron-builder/issues/602)



<a name="5.18.0"></a>
# [5.18.0](https://github.com/electron-userland/electron-builder/compare/v5.17.1...v5.18.0) (2016-07-28)


### Bug Fixes

* remove "Warning: homepage" ([0fd6a3e](https://github.com/electron-userland/electron-builder/commit/0fd6a3e))


### Features

* NSIS script customization — script option ([a807b17](https://github.com/electron-userland/electron-builder/commit/a807b17)), closes [#583](https://github.com/electron-userland/electron-builder/issues/583)



<a name="5.17.1"></a>
## [5.17.1](https://github.com/electron-userland/electron-builder/compare/v5.17.0...v5.17.1) (2016-07-27)


### Bug Fixes

* do not use scoped asara package ([c53074c](https://github.com/electron-userland/electron-builder/commit/c53074c)), closes [#610](https://github.com/electron-userland/electron-builder/issues/610)



<a name="5.17.0"></a>
# [5.17.0](https://github.com/electron-userland/electron-builder/compare/v5.16.0...v5.17.0) (2016-07-27)


### Features

* NSIS script customization #583 ([63beaaf](https://github.com/electron-userland/electron-builder/commit/63beaaf))



<a name="5.16.0"></a>
# [5.16.0](https://github.com/electron-userland/electron-builder/compare/v5.15.0...v5.16.0) (2016-07-22)


### Features

* exclude **/node_modules/*/{README.md,README,readme.md,readme,test} by default ([5895583](https://github.com/electron-userland/electron-builder/commit/5895583)), closes [#591](https://github.com/electron-userland/electron-builder/issues/591) [#606](https://github.com/electron-userland/electron-builder/issues/606)
* exclude extraResources/extraFiles for one-package dir ([3aaf025](https://github.com/electron-userland/electron-builder/commit/3aaf025)), closes [#599](https://github.com/electron-userland/electron-builder/issues/599)



<a name="5.15.0"></a>
# [5.15.0](https://github.com/electron-userland/electron-builder/compare/v5.14.2...v5.15.0) (2016-07-21)


### Features

* **Linux:** app icon is not required ([ec0bda5](https://github.com/electron-userland/electron-builder/commit/ec0bda5)), closes [#593](https://github.com/electron-userland/electron-builder/issues/593)



<a name="5.14.2"></a>
## [5.14.2](https://github.com/electron-userland/electron-builder/compare/v5.14.1...v5.14.2) (2016-07-20)


### Bug Fixes

* **nsis:** fix all nsis warnings ([9a3fd5e](https://github.com/electron-userland/electron-builder/commit/9a3fd5e))



<a name="5.14.1"></a>
## [5.14.1](https://github.com/electron-userland/electron-builder/compare/v5.14.0...v5.14.1) (2016-07-19)


### Bug Fixes

* **AppImage:** AppImage should have arch in filename ([e7d4f76](https://github.com/electron-userland/electron-builder/commit/e7d4f76)), closes [#594](https://github.com/electron-userland/electron-builder/issues/594)



<a name="5.14.0"></a>
# [5.14.0](https://github.com/electron-userland/electron-builder/compare/v5.13.1...v5.14.0) (2016-07-18)


### Features

* file associations ([fd1e7da](https://github.com/electron-userland/electron-builder/commit/fd1e7da)), closes [#563](https://github.com/electron-userland/electron-builder/issues/563)



<a name="5.13.1"></a>
## [5.13.1](https://github.com/electron-userland/electron-builder/compare/v5.13.0...v5.13.1) (2016-07-14)


### Bug Fixes

* win codesign on windows 7 ([d78c69c](https://github.com/electron-userland/electron-builder/commit/d78c69c)), closes [#581](https://github.com/electron-userland/electron-builder/issues/581) [#584](https://github.com/electron-userland/electron-builder/issues/584)



<a name="5.13.0"></a>
# [5.13.0](https://github.com/electron-userland/electron-builder/compare/v5.12.1...v5.13.0) (2016-07-13)


### Features

* **Squirrel.Windows:** Automatic remoteReleases configuration ([d6aa555](https://github.com/electron-userland/electron-builder/commit/d6aa555)), closes [#561](https://github.com/electron-userland/electron-builder/issues/561)
* **nsis:** run after finish flag for one-click installer ([50039ea](https://github.com/electron-userland/electron-builder/commit/50039ea)), closes [#574](https://github.com/electron-userland/electron-builder/issues/574)



<a name="5.12.1"></a>
## [5.12.1](https://github.com/electron-userland/electron-builder/compare/v5.12.0...v5.12.1) (2016-07-11)


### Bug Fixes

* **nsis:** per machine assisted installer ([1bd32a7](https://github.com/electron-userland/electron-builder/commit/1bd32a7)), closes [#564](https://github.com/electron-userland/electron-builder/issues/564)



<a name="5.12.0"></a>
# [5.12.0](https://github.com/electron-userland/electron-builder/compare/v5.11.3...v5.12.0) (2016-07-09)


### Bug Fixes

* **nsis:** install per current user even if run as administrator ([a01f481](https://github.com/electron-userland/electron-builder/commit/a01f481))


### Features

* **nsis:** per machine one-click installer #564 ([9f52848](https://github.com/electron-userland/electron-builder/commit/9f52848))



<a name="5.11.3"></a>
## [5.11.3](https://github.com/electron-userland/electron-builder/compare/v5.11.2...v5.11.3) (2016-07-09)


### Bug Fixes

* **AppImage:** bundle xorriso ([a1bf645](https://github.com/electron-userland/electron-builder/commit/a1bf645))



<a name="5.11.2"></a>
## [5.11.2](https://github.com/electron-userland/electron-builder/compare/v5.11.1...v5.11.2) (2016-07-07)


### Bug Fixes

* **AppImage:** do not pack into archive, add `.AppImage` suffix ([f59c7bd](https://github.com/electron-userland/electron-builder/commit/f59c7bd))



<a name="5.11.1"></a>
## [5.11.1](https://github.com/electron-userland/electron-builder/compare/v5.11.0...v5.11.1) (2016-07-07)


### Bug Fixes

* **nsis:** ia32 Extracting wrong archive ([56b3450](https://github.com/electron-userland/electron-builder/commit/56b3450)), closes [#567](https://github.com/electron-userland/electron-builder/issues/567)



<a name="5.11.0"></a>
# [5.11.0](https://github.com/electron-userland/electron-builder/compare/v5.10.5...v5.11.0) (2016-07-07)


### Bug Fixes

* AppImage desktop icons ([9a69286](https://github.com/electron-userland/electron-builder/commit/9a69286))
* **AppImage:** use app name as a executable name ([159446b](https://github.com/electron-userland/electron-builder/commit/159446b))


### Features

* Build AppImage for Linux ([a9afdd4](https://github.com/electron-userland/electron-builder/commit/a9afdd4)), closes [#504](https://github.com/electron-userland/electron-builder/issues/504)
* multi-cert p12 ([de01c6d](https://github.com/electron-userland/electron-builder/commit/de01c6d)), closes [#560](https://github.com/electron-userland/electron-builder/issues/560)
* **mac:** Add build-version override property ([0b0ed62](https://github.com/electron-userland/electron-builder/commit/0b0ed62)), closes [#565](https://github.com/electron-userland/electron-builder/issues/565)



<a name="5.10.5"></a>
## [5.10.5](https://github.com/electron-userland/electron-builder/compare/v5.10.4...v5.10.5) (2016-07-03)


### Bug Fixes

* CSC_INSTALLER_KEY_PASSWORD environment variable isn't picked up #560 ([3fdd1f8](https://github.com/electron-userland/electron-builder/commit/3fdd1f8))
* CSC_INSTALLER_LINK environment variable isn't picked up #560 ([1c2632d](https://github.com/electron-userland/electron-builder/commit/1c2632d))



<a name="5.10.4"></a>
## [5.10.4](https://github.com/electron-userland/electron-builder/compare/v5.10.3...v5.10.4) (2016-07-02)


### Bug Fixes

* non-English characters confuse rcedit: Unable to load file on windows build (from linux) ([233fafe](https://github.com/electron-userland/electron-builder/commit/233fafe)), closes [#384](https://github.com/electron-userland/electron-builder/issues/384)



<a name="5.10.3"></a>
## [5.10.3](https://github.com/electron-userland/electron-builder/compare/v5.10.2...v5.10.3) (2016-07-01)


### Bug Fixes

* Ignore .DS_Store Files ([152b987](https://github.com/electron-userland/electron-builder/commit/152b987)), closes [#545](https://github.com/electron-userland/electron-builder/issues/545)
* dereference copied app files only for windows targets ([bf2aafb](https://github.com/electron-userland/electron-builder/commit/bf2aafb))



<a name="5.10.2"></a>
## [5.10.2](https://github.com/electron-userland/electron-builder/compare/v5.10.1...v5.10.2) (2016-06-28)


### Bug Fixes

* **nsis:** installerHeaderIcon ([00e8da8](https://github.com/electron-userland/electron-builder/commit/00e8da8)), closes [#525](https://github.com/electron-userland/electron-builder/issues/525)



<a name="5.10.1"></a>
## [5.10.1](https://github.com/electron-userland/electron-builder/compare/v5.10.0...v5.10.1) (2016-06-27)


### Bug Fixes

* Build failing when productName contains a slash ([726e574](https://github.com/electron-userland/electron-builder/commit/726e574)), closes [#539](https://github.com/electron-userland/electron-builder/issues/539)



<a name="5.10.0"></a>
# [5.10.0](https://github.com/electron-userland/electron-builder/compare/v5.9.0...v5.10.0) (2016-06-26)


### Features

* **publisher:** Check that tag name starts with "v" #340 ([bb71621](https://github.com/electron-userland/electron-builder/commit/bb71621))



<a name="5.9.0"></a>
# [5.9.0](https://github.com/electron-userland/electron-builder/compare/v5.8.0...v5.9.0) (2016-06-26)


### Features

* **nsis:** Different Icon for installer / App ? (Windows) ([65650ea](https://github.com/electron-userland/electron-builder/commit/65650ea)), closes [#525](https://github.com/electron-userland/electron-builder/issues/525)



<a name="5.8.0"></a>
# [5.8.0](https://github.com/electron-userland/electron-builder/compare/v5.7.0...v5.8.0) (2016-06-26)


### Bug Fixes

* **mas:** cannot find mas installer ([5ba6276](https://github.com/electron-userland/electron-builder/commit/5ba6276)), closes [#535](https://github.com/electron-userland/electron-builder/issues/535)


### Features

* **nsis:** 32 bit + 64 bit installer ([bbd0bd6](https://github.com/electron-userland/electron-builder/commit/bbd0bd6)), closes [#528](https://github.com/electron-userland/electron-builder/issues/528) [#536](https://github.com/electron-userland/electron-builder/issues/536)



<a name="5.7.0"></a>
# [5.7.0](https://github.com/electron-userland/electron-builder/compare/v5.6.3...v5.7.0) (2016-06-24)


### Bug Fixes

* don't throw release must be a draft if onTag policy was guessed ([26c89f0](https://github.com/electron-userland/electron-builder/commit/26c89f0))


### Features

* **nsis:** MUI_HEADERIMAGE #525 ([3f43c0a](https://github.com/electron-userland/electron-builder/commit/3f43c0a))



<a name="5.6.3"></a>
## [5.6.3](https://github.com/electron-userland/electron-builder/compare/v5.6.2...v5.6.3) (2016-06-23)


### Bug Fixes

* Installation Has Failed - Seems to be an issue with the RELEASES file ([7c84f5f](https://github.com/electron-userland/electron-builder/commit/7c84f5f)), closes [#534](https://github.com/electron-userland/electron-builder/issues/534)



<a name="5.6.2"></a>
## [5.6.2](https://github.com/electron-userland/electron-builder/compare/v5.6.1...v5.6.2) (2016-06-23)


### Bug Fixes

* Creating an MSI on Windows fails ([d1ee7de](https://github.com/electron-userland/electron-builder/commit/d1ee7de)), closes [#485](https://github.com/electron-userland/electron-builder/issues/485)



<a name="5.6.1"></a>
## [5.6.1](https://github.com/electron-userland/electron-builder/compare/v5.6.0...v5.6.1) (2016-06-22)


### Bug Fixes

* `build --target dir` doesn't work ([f880157](https://github.com/electron-userland/electron-builder/commit/f880157)), closes [#531](https://github.com/electron-userland/electron-builder/issues/531)



<a name="5.6.0"></a>
# [5.6.0](https://github.com/electron-userland/electron-builder/compare/v5.5.0...v5.6.0) (2016-06-21)


### Features

* specified icon not being used when generating osx build ([74388bb](https://github.com/electron-userland/electron-builder/commit/74388bb)), closes [#519](https://github.com/electron-userland/electron-builder/issues/519)



<a name="5.5.0"></a>
# [5.5.0](https://github.com/electron-userland/electron-builder/compare/v5.4.4...v5.5.0) (2016-06-19)


### Features

* finish NSIS installer look and feel ([e50e3c8](https://github.com/electron-userland/electron-builder/commit/e50e3c8))



<a name="5.4.4"></a>
## [5.4.4](https://github.com/electron-userland/electron-builder/compare/v5.4.3...v5.4.4) (2016-06-17)


### Bug Fixes

* NSIS LZMA compression is slower and worse then external 7z compression ([e1e6d67](https://github.com/electron-userland/electron-builder/commit/e1e6d67))
* ignore dev deps if ignore func specified ([0944985](https://github.com/electron-userland/electron-builder/commit/0944985))
* validate bin checksum ([0f9d2e1](https://github.com/electron-userland/electron-builder/commit/0f9d2e1))


### Performance Improvements

* create asar without intermediate copy ([95c8a0c](https://github.com/electron-userland/electron-builder/commit/95c8a0c))



<a name="5.4.3"></a>
## [5.4.3](https://github.com/electron-userland/electron-builder/compare/v5.4.2...v5.4.3) (2016-06-16)


### Bug Fixes

* allow passing absolute and relative path as userAppDir option (#515) ([df096f0](https://github.com/electron-userland/electron-builder/commit/df096f0))



<a name="5.4.2"></a>
## [5.4.2](https://github.com/electron-userland/electron-builder/compare/v5.4.1...v5.4.2) (2016-06-16)


### Bug Fixes

* ignore com.apple.idms.appleid.prd. certs ([b69d3ab](https://github.com/electron-userland/electron-builder/commit/b69d3ab)), closes [#510](https://github.com/electron-userland/electron-builder/issues/510)



<a name="5.4.1"></a>
## [5.4.1](https://github.com/electron-userland/electron-builder/compare/v5.4.0...v5.4.1) (2016-06-14)


### Bug Fixes

* don't use deb default deps for other targets #502 ([c3679e7](https://github.com/electron-userland/electron-builder/commit/c3679e7))



<a name="5.4.0"></a>
# [5.4.0](https://github.com/electron-userland/electron-builder/compare/v5.3.0...v5.4.0) (2016-06-14)


### Features

* NSIS target (#495) ([d8762db](https://github.com/electron-userland/electron-builder/commit/d8762db)), closes [#472](https://github.com/electron-userland/electron-builder/issues/472) [#493](https://github.com/electron-userland/electron-builder/issues/493)



<a name="5.3.0"></a>
# [5.3.0](https://github.com/electron-userland/electron-builder/compare/v5.2.1...v5.3.0) (2016-06-14)


### Features

* adding dot asar option (#496) ([3fc7a89](https://github.com/electron-userland/electron-builder/commit/3fc7a89))



<a name="5.2.1"></a>
## [5.2.1](https://github.com/electron-userland/electron-builder/compare/v5.2.0...v5.2.1) (2016-06-12)


### Bug Fixes

* don't try to build OS X x64 ([ee64432](https://github.com/electron-userland/electron-builder/commit/ee64432))



<a name="5.2.0"></a>
# [5.2.0](https://github.com/electron-userland/electron-builder/compare/v5.1.0...v5.2.0) (2016-06-11)


### Features

* Ability to set author/CompanyName programmatically ([63c2529](https://github.com/electron-userland/electron-builder/commit/63c2529)), closes [#455](https://github.com/electron-userland/electron-builder/issues/455)
* Add Ability to Create Pre-Releases and Releases ([e5b0c04](https://github.com/electron-userland/electron-builder/commit/e5b0c04)), closes [#446](https://github.com/electron-userland/electron-builder/issues/446)



<a name="5.1.0"></a>
# [5.1.0](https://github.com/electron-userland/electron-builder/compare/v5.0.3...v5.1.0) (2016-06-10)


### Bug Fixes

* Builder attempts to sign OSX app even though no signing is specified ([24f6045](https://github.com/electron-userland/electron-builder/commit/24f6045)), closes [#481](https://github.com/electron-userland/electron-builder/issues/481) [#484](https://github.com/electron-userland/electron-builder/issues/484)


### Features

* Windows targets `7z`, `zip`, `tar.xz`, `tar.lz`, `tar.gz`, `tar.bz2` ([1c983d4](https://github.com/electron-userland/electron-builder/commit/1c983d4))



<a name="5.0.3"></a>
## [5.0.3](https://github.com/electron-userland/electron-builder/compare/v5.0.2...v5.0.3) (2016-06-10)


### Bug Fixes

* Asar: true failing on Windows for electron-builder 5.x ([317a330](https://github.com/electron-userland/electron-builder/commit/317a330)), closes [#482](https://github.com/electron-userland/electron-builder/issues/482)



<a name="5.0.2"></a>
## [5.0.2](https://github.com/electron-userland/electron-builder/compare/v5.0.1...v5.0.2) (2016-06-09)


### Bug Fixes

* mas target — Identity name is specified, but no valid identity with this name in the keychain ([b091a13](https://github.com/electron-userland/electron-builder/commit/b091a13)), closes [#479](https://github.com/electron-userland/electron-builder/issues/479)



<a name="5.0.1"></a>
## [5.0.1](https://github.com/electron-userland/electron-builder/compare/v5.0.0...v5.0.1) (2016-06-09)


### Bug Fixes

* restore `--platform` and `--arch` CLI ([7f9e6e3](https://github.com/electron-userland/electron-builder/commit/7f9e6e3))



<a name="5.0.0"></a>
# [5.0.0](https://github.com/electron-userland/electron-builder/compare/v4.2.6...v5.0.0) (2016-06-08)


### Bug Fixes

* efficient implementation of copy extra files/resources ([5853514](https://github.com/electron-userland/electron-builder/commit/5853514))


### Features

* Development dependencies are never copied in any case ([6d4ab11](https://github.com/electron-userland/electron-builder/commit/6d4ab11))
* files option ([0f7624d](https://github.com/electron-userland/electron-builder/commit/0f7624d))


### BREAKING CHANGES

* prune by default, hidden files are not copied by default anymore



<a name="4.2.6"></a>
## [4.2.6](https://github.com/electron-userland/electron-builder/compare/v4.2.5...v4.2.6) (2016-06-06)


### Bug Fixes

* OS X code signing — cert type prefix must be added, restore non-Apple cert support ([97e16a2](https://github.com/electron-userland/electron-builder/commit/97e16a2)), closes [#458](https://github.com/electron-userland/electron-builder/issues/458)



<a name="4.2.5"></a>
## [4.2.5](https://github.com/electron-userland/electron-builder/compare/v4.2.4...v4.2.5) (2016-06-06)


### Bug Fixes

* Fallback to CSC_KEY_PASSWORD if certificatePassword not given ([aea6505](https://github.com/electron-userland/electron-builder/commit/aea6505)), closes [#475](https://github.com/electron-userland/electron-builder/issues/475)



<a name="4.2.4"></a>
## [4.2.4](https://github.com/electron-userland/electron-builder/compare/v4.2.3...v4.2.4) (2016-06-06)


### Bug Fixes

* Squirrel-packed executable not signed ([eb10afb](https://github.com/electron-userland/electron-builder/commit/eb10afb)), closes [#449](https://github.com/electron-userland/electron-builder/issues/449)



<a name="4.2.3"></a>
## [4.2.3](https://github.com/electron-userland/electron-builder/compare/v4.2.2...v4.2.3) (2016-06-05)


### Bug Fixes

* building windows 32 bit and 64 bit simultaneously ([cec4b3d](https://github.com/electron-userland/electron-builder/commit/cec4b3d)), closes [#470](https://github.com/electron-userland/electron-builder/issues/470)



<a name="4.2.2"></a>
## [4.2.2](https://github.com/electron-userland/electron-builder/compare/v4.2.1...v4.2.2) (2016-06-03)


### Bug Fixes

* 4.2.1 Doesn't Include `.node` Files ([12ba8b7](https://github.com/electron-userland/electron-builder/commit/12ba8b7)), closes [#468](https://github.com/electron-userland/electron-builder/issues/468)



<a name="4.2.1"></a>
## [4.2.1](https://github.com/electron-userland/electron-builder/compare/v4.2.0...v4.2.1) (2016-06-03)


### Bug Fixes

* Application entry can't be found ([a7b2932](https://github.com/electron-userland/electron-builder/commit/a7b2932)), closes [#371](https://github.com/electron-userland/electron-builder/issues/371)
* icudtl.dat: file changed as we read it ([567c813](https://github.com/electron-userland/electron-builder/commit/567c813)), closes [#460](https://github.com/electron-userland/electron-builder/issues/460)
* warn "It is not possible to build OS X app on Windows" ([f6c47f7](https://github.com/electron-userland/electron-builder/commit/f6c47f7)), closes [#422](https://github.com/electron-userland/electron-builder/issues/422)



<a name="4.2.0"></a>
# [4.2.0](https://github.com/electron-userland/electron-builder/compare/v4.1.0...v4.2.0) (2016-06-02)


### Bug Fixes

* Don´t throw error if Release is not a Draft and build triggered by Tag ([0f060c1](https://github.com/electron-userland/electron-builder/commit/0f060c1)), closes [#429](https://github.com/electron-userland/electron-builder/issues/429)
* entitlements file names according to new electron-osx-sign conventions ([ecdff3c](https://github.com/electron-userland/electron-builder/commit/ecdff3c))
* log github publisher user and project #425 ([c2c3ef6](https://github.com/electron-userland/electron-builder/commit/c2c3ef6))
* move npmRebuild to build ([1110596](https://github.com/electron-userland/electron-builder/commit/1110596))
* update electron-osx-sign to 0.4 beta ([bf93b24](https://github.com/electron-userland/electron-builder/commit/bf93b24))
* windows codesign on Linux ([7166580](https://github.com/electron-userland/electron-builder/commit/7166580))


### Features

* `--dist` by default ([ae3f1bb](https://github.com/electron-userland/electron-builder/commit/ae3f1bb)), closes [#413](https://github.com/electron-userland/electron-builder/issues/413)


### BREAKING CHANGES

* See new entitlements paths in the wiki



<a name="4.1.0"></a>
# [4.1.0](https://github.com/electron-userland/electron-builder/compare/v4.0.0...v4.1.0) (2016-05-30)


### Features

* user-friendly MAS code signing ([fe53388](https://github.com/electron-userland/electron-builder/commit/fe53388))



<a name="4.0.0"></a>
# [4.0.0](https://github.com/electron-userland/electron-builder/compare/v3.27.0...v4.0.0) (2016-05-29)


### Features

* `--dist` by default and remove this flag in favour of `--target=dir #413 ([a5e4571](https://github.com/electron-userland/electron-builder/commit/a5e4571))
* extraFiles ([ca120e3](https://github.com/electron-userland/electron-builder/commit/ca120e3))
* option to skip installAppDependencies ([67ed60b](https://github.com/electron-userland/electron-builder/commit/67ed60b)), closes [#442](https://github.com/electron-userland/electron-builder/issues/442)


### BREAKING CHANGES

* `extraResources` copying files to `resources` on Linux/Windows, not to root directory as before. To copy to the root please use new option `extraFiles`.
* `appDir` CLI is removed — use [directories.app](https://github.com/electron-userland/electron-builder/wiki/Options#MetadataDirectories-app) in the development package.json. `sign` CLI is removed — use [build.osx.identity](https://github.com/electron-userland/electron-builder/wiki/Options#OsXBuildOptions-identity) in the development package.json.



<a name="3.27.0"></a>
# [3.27.0](https://github.com/electron-userland/electron-builder/compare/v3.26.3...v3.27.0) (2016-05-26)


### Features

* **windows:** specification of signing algorithms (#435) ([73e7c14](https://github.com/electron-userland/electron-builder/commit/73e7c14)), closes [#374](https://github.com/electron-userland/electron-builder/issues/374) [#416](https://github.com/electron-userland/electron-builder/issues/416)
* support finding electron version in build.electronVersion or electron-prebuilt-compile ([4c1f06d](https://github.com/electron-userland/electron-builder/commit/4c1f06d))



<a name="3.26.3"></a>
## [3.26.3](https://github.com/electron-userland/electron-builder/compare/v3.26.2...v3.26.3) (2016-05-23)


### Bug Fixes

* import bundled certs into login.keychain ([bffbbf1](https://github.com/electron-userland/electron-builder/commit/bffbbf1)), closes [#398](https://github.com/electron-userland/electron-builder/issues/398)



<a name="3.26.2"></a>
## [3.26.2](https://github.com/electron-userland/electron-builder/compare/v3.26.1...v3.26.2) (2016-05-23)


### Bug Fixes

* check that description is not empty ([a3bbb3f](https://github.com/electron-userland/electron-builder/commit/a3bbb3f)), closes [#392](https://github.com/electron-userland/electron-builder/issues/392)



<a name="3.26.1"></a>
## [3.26.1](https://github.com/electron-userland/electron-builder/compare/v3.26.0...v3.26.1) (2016-05-23)


### Bug Fixes

* forbid name in the build ([e4eefb2](https://github.com/electron-userland/electron-builder/commit/e4eefb2)), closes [#360](https://github.com/electron-userland/electron-builder/issues/360)



<a name="3.26.0"></a>
# [3.26.0](https://github.com/electron-userland/electron-builder/compare/v3.25.0...v3.26.0) (2016-05-23)


### Features

* **linux:** sh, rpm, freebsd, pacman, p5p, apk, 7z, zip, tar.xz, tar.gz, tar.bz2, tar.lz ([50d31f1](https://github.com/electron-userland/electron-builder/commit/50d31f1)), closes [#414](https://github.com/electron-userland/electron-builder/issues/414)



<a name="3.25.0"></a>
# [3.25.0](https://github.com/electron-userland/electron-builder/compare/v3.24.0...v3.25.0) (2016-05-18)


### Bug Fixes

* Trouble building delta package for Squirrel.Windows on OSX ([cc8278a](https://github.com/electron-userland/electron-builder/commit/cc8278a)), closes [#407](https://github.com/electron-userland/electron-builder/issues/407)


### Features

* **osx:** Optional DMG background ([4088b13](https://github.com/electron-userland/electron-builder/commit/4088b13))
* The function to be run after pack (but before pack into distributable format and sign) ([7f32573](https://github.com/electron-userland/electron-builder/commit/7f32573)), closes [#397](https://github.com/electron-userland/electron-builder/issues/397)
* check asar existence and integrity (#401) ([4a9af55](https://github.com/electron-userland/electron-builder/commit/4a9af55))



<a name="3.24.0"></a>
# [3.24.0](https://github.com/electron-userland/electron-builder/compare/v3.23.0...v3.24.0) (2016-05-15)


### Features

* **linux:** Install libappindicator1 and libnotify as a dependency of the linux package ([05baad5](https://github.com/electron-userland/electron-builder/commit/05baad5))



<a name="3.23.0"></a>
# [3.23.0](https://github.com/electron-userland/electron-builder/compare/v3.22.2...v3.23.0) (2016-05-14)


### Features

* bundle Certum cert ([2e0894f](https://github.com/electron-userland/electron-builder/commit/2e0894f)), closes [#398](https://github.com/electron-userland/electron-builder/issues/398)



<a name="3.22.2"></a>
## [3.22.2](https://github.com/electron-userland/electron-builder/compare/v3.22.1...v3.22.2) (2016-05-14)


### Bug Fixes

* **linux:** use full path in .desktop file (#405) ([1164ca1](https://github.com/electron-userland/electron-builder/commit/1164ca1))
* incorrect nupkg file if created on windows ([a5a23ae](https://github.com/electron-userland/electron-builder/commit/a5a23ae)), closes [#402](https://github.com/electron-userland/electron-builder/issues/402) [#351](https://github.com/electron-userland/electron-builder/issues/351)



<a name="3.22.1"></a>
## [3.22.1](https://github.com/electron-userland/electron-builder/compare/v3.22.0...v3.22.1) (2016-05-13)


### Bug Fixes

* win ia32 out dir name — unexpanded $arch ([8d9b952](https://github.com/electron-userland/electron-builder/commit/8d9b952))



<a name="3.22.0"></a>
# [3.22.0](https://github.com/electron-userland/electron-builder/compare/v3.21.0...v3.22.0) (2016-05-13)


### Features

* revert "Releases file for Windows not uploaded to Github #190" ([079989a](https://github.com/electron-userland/electron-builder/commit/079989a))



<a name="3.21.0"></a>
# [3.21.0](https://github.com/electron-userland/electron-builder/compare/v3.20.0...v3.21.0) (2016-05-12)


### Bug Fixes

* Cannot upload prerelease version ([05121df](https://github.com/electron-userland/electron-builder/commit/05121df)), closes [#395](https://github.com/electron-userland/electron-builder/issues/395)


### Features

* Squirrel.Windows doesn't escape " in the description ([6977557](https://github.com/electron-userland/electron-builder/commit/6977557)), closes [#378](https://github.com/electron-userland/electron-builder/issues/378)



<a name="3.20.0"></a>
# [3.20.0](https://github.com/electron-userland/electron-builder/compare/v3.19.0...v3.20.0) (2016-05-11)


### Bug Fixes

* http download to destination if no parent dirs created ([b5505fc](https://github.com/electron-userland/electron-builder/commit/b5505fc))


### Features

* dual code-sign windows app + timestamped ([b71d2f3](https://github.com/electron-userland/electron-builder/commit/b71d2f3))



<a name="3.19.0"></a>
# [3.19.0](https://github.com/electron-userland/electron-builder/compare/v3.18.0...v3.19.0) (2016-05-10)


### Features

* Code signing windows app using SHA256 ([032ba05](https://github.com/electron-userland/electron-builder/commit/032ba05)), closes [#386](https://github.com/electron-userland/electron-builder/issues/386)



<a name="3.18.0"></a>
# [3.18.0](https://github.com/electron-userland/electron-builder/compare/v3.17.1...v3.18.0) (2016-05-09)


### Bug Fixes

* user-friendly error message "Error: buffer is not ico" ([7ac6ca2](https://github.com/electron-userland/electron-builder/commit/7ac6ca2)), closes [#349](https://github.com/electron-userland/electron-builder/issues/349)


### Features

* base64-encoded P12 file instead of https link ([3ab0e57](https://github.com/electron-userland/electron-builder/commit/3ab0e57))
* cleanup unused fpm versions ([633d006](https://github.com/electron-userland/electron-builder/commit/633d006))
* use self-contained fpm on Linux — don't need to install ruby anymore ([7d5b747](https://github.com/electron-userland/electron-builder/commit/7d5b747))



<a name="3.17.1"></a>
## [3.17.1](https://github.com/electron-userland/electron-builder/compare/v3.17.0...v3.17.1) (2016-05-05)


### Bug Fixes

* bundle StartSSL certs ([16d3805](https://github.com/electron-userland/electron-builder/commit/16d3805))
* osx code sign regression ([2d0f5f1](https://github.com/electron-userland/electron-builder/commit/2d0f5f1)), closes [#377](https://github.com/electron-userland/electron-builder/issues/377)



<a name="3.17.0"></a>
# [3.17.0](https://github.com/electron-userland/electron-builder/compare/v3.16.1...v3.17.0) (2016-05-04)


### Features

* use self-containe fpm on OS X — don't need to install ruby anymore ([e7cee5e](https://github.com/electron-userland/electron-builder/commit/e7cee5e))



<a name="3.16.1"></a>
## [3.16.1](https://github.com/electron-userland/electron-builder/compare/v3.16.0...v3.16.1) (2016-05-03)


### Bug Fixes

* check wine version ([d77c8da](https://github.com/electron-userland/electron-builder/commit/d77c8da)), closes [#352](https://github.com/electron-userland/electron-builder/issues/352)



<a name="3.16.0"></a>
# [3.16.0](https://github.com/electron-userland/electron-builder/compare/v3.15.0...v3.16.0) (2016-05-02)


### Features

* add Jenkins build number support (#373) ([eebe882](https://github.com/electron-userland/electron-builder/commit/eebe882))



<a name="3.15.0"></a>
# [3.15.0](https://github.com/electron-userland/electron-builder/compare/v3.14.0...v3.15.0) (2016-05-02)


### Features

* iconUrl git-lfs support, os x identity/installerIdentity options ([974f7f3](https://github.com/electron-userland/electron-builder/commit/974f7f3)), closes [#332](https://github.com/electron-userland/electron-builder/issues/332)
* osx entitlements location by convention ([af1165b](https://github.com/electron-userland/electron-builder/commit/af1165b))



<a name="3.14.0"></a>
# [3.14.0](https://github.com/electron-userland/electron-builder/compare/v3.13.1...v3.14.0) (2016-04-29)


### Features

* build mas + other targets, osx 7z ([c46e1f5](https://github.com/electron-userland/electron-builder/commit/c46e1f5))



<a name="3.13.1"></a>
## [3.13.1](https://github.com/electron-userland/electron-builder/compare/v3.13.0...v3.13.1) (2016-04-28)


### Bug Fixes

* statFileInPackage in platformPackager.js creates wrong path ([7373131](https://github.com/electron-userland/electron-builder/commit/7373131)), closes [#365](https://github.com/electron-userland/electron-builder/issues/365)



<a name="3.13.0"></a>
# [3.13.0](https://github.com/electron-userland/electron-builder/compare/v3.12.0...v3.13.0) (2016-04-28)


### Bug Fixes

* add debug log to investigate "Cannot build app with 3.6.2+" #360 ([1970550](https://github.com/electron-userland/electron-builder/commit/1970550))


### Features

* DMG — use bzip2 compression (old: 40MB, new: 36MB) ([e0c3b92](https://github.com/electron-userland/electron-builder/commit/e0c3b92))



<a name="3.12.0"></a>
# [3.12.0](https://github.com/electron-userland/electron-builder/compare/v3.11.0...v3.12.0) (2016-04-27)


### Bug Fixes

* Windows shortcut doesn't work when `productName` contains a space ([f99d61e](https://github.com/electron-userland/electron-builder/commit/f99d61e)), closes [#339](https://github.com/electron-userland/electron-builder/issues/339)


### Features

* check application package ([27faf73](https://github.com/electron-userland/electron-builder/commit/27faf73)), closes [#303](https://github.com/electron-userland/electron-builder/issues/303)



<a name="3.11.0"></a>
# [3.11.0](https://github.com/electron-userland/electron-builder/compare/v3.10.0...v3.11.0) (2016-04-25)


### Features

* mac app store ([260ca0b](https://github.com/electron-userland/electron-builder/commit/260ca0b)), closes [#332](https://github.com/electron-userland/electron-builder/issues/332)



<a name="3.10.0"></a>
# [3.10.0](https://github.com/electron-userland/electron-builder/compare/v3.9.0...v3.10.0) (2016-04-23)


### Features

* import startssl certs by default ([0f19455](https://github.com/electron-userland/electron-builder/commit/0f19455))



<a name="3.9.0"></a>
# [3.9.0](https://github.com/electron-userland/electron-builder/compare/v3.8.0...v3.9.0) (2016-04-21)


### Features

* build.osx.target to specify dmg, zip or both ([23df6a1](https://github.com/electron-userland/electron-builder/commit/23df6a1)), closes [#322](https://github.com/electron-userland/electron-builder/issues/322)



<a name="3.8.0"></a>
# [3.8.0](https://github.com/electron-userland/electron-builder/compare/v3.7.0...v3.8.0) (2016-04-20)


### Features

* accept multiple default app dirs ([ea5f842](https://github.com/electron-userland/electron-builder/commit/ea5f842)), closes [#344](https://github.com/electron-userland/electron-builder/issues/344)



<a name="3.7.0"></a>
# [3.7.0](https://github.com/electron-userland/electron-builder/compare/v3.6.3...v3.7.0) (2016-04-20)


### Features

* Windows code signing from OS X ([9134f61](https://github.com/electron-userland/electron-builder/commit/9134f61)), closes [#314](https://github.com/electron-userland/electron-builder/issues/314)



<a name="3.6.3"></a>
## [3.6.3](https://github.com/electron-userland/electron-builder/compare/v3.6.2...v3.6.3) (2016-04-19)


### Bug Fixes

* Looks for linux homepage in the development package.json not in the application package.json ([3da6893](https://github.com/electron-userland/electron-builder/commit/3da6893)), closes [#334](https://github.com/electron-userland/electron-builder/issues/334)



<a name="3.6.2"></a>
## [3.6.2](https://github.com/electron-userland/electron-builder/compare/v3.6.1...v3.6.2) (2016-04-19)


### Bug Fixes

* get rid of nuget to pack win ([c987439](https://github.com/electron-userland/electron-builder/commit/c987439))



<a name="3.6.1"></a>
## [3.6.1](https://github.com/electron-userland/electron-builder/compare/v3.6.0...v3.6.1) (2016-04-17)


### Bug Fixes

* deb package description according to spec ([3c6ec3f](https://github.com/electron-userland/electron-builder/commit/3c6ec3f)), closes [#327](https://github.com/electron-userland/electron-builder/issues/327)



<a name="3.6.0"></a>
# [3.6.0](https://github.com/electron-userland/electron-builder/compare/v3.5.2...v3.6.0) (2016-04-16)


### Bug Fixes

* check that noMsi specified as bool ([8266b22](https://github.com/electron-userland/electron-builder/commit/8266b22)), closes [#316](https://github.com/electron-userland/electron-builder/issues/316)


### Features

* Allow to specify custom build-version for electron-packager ([c866084](https://github.com/electron-userland/electron-builder/commit/c866084)), closes [#323](https://github.com/electron-userland/electron-builder/issues/323)



<a name="3.5.2"></a>
## [3.5.2](https://github.com/electron-userland/electron-builder/compare/v3.5.1...v3.5.2) (2016-04-15)


### Bug Fixes

* check that electron-packager create out directory ([e015b61](https://github.com/electron-userland/electron-builder/commit/e015b61)), closes [#301](https://github.com/electron-userland/electron-builder/issues/301)



<a name="3.5.1"></a>
## [3.5.1](https://github.com/electron-userland/electron-builder/compare/v3.5.0...v3.5.1) (2016-04-14)


### Bug Fixes

* Error while creating delta nupkg for Windows: System.DllNotFoundException: msdelta.dl #294 ([574add7](https://github.com/electron-userland/electron-builder/commit/574add7)), closes [#294](https://github.com/electron-userland/electron-builder/issues/294)



<a name="3.5.0"></a>
# [3.5.0](https://github.com/electron-userland/electron-builder/compare/v3.4.0...v3.5.0) (2016-04-10)


### Features

* if build/install-spinner.gif exists, set loadingGif to it ([85a6fba](https://github.com/electron-userland/electron-builder/commit/85a6fba)), closes [#292](https://github.com/electron-userland/electron-builder/issues/292)



<a name="3.4.0"></a>
# [3.4.0](https://github.com/electron-userland/electron-builder/compare/v3.3.1...v3.4.0) (2016-04-09)


### Features

* Ability to customize the output directory ([78bddc7](https://github.com/electron-userland/electron-builder/commit/78bddc7)), closes [#272](https://github.com/electron-userland/electron-builder/issues/272)



<a name="3.3.1"></a>
## [3.3.1](https://github.com/electron-userland/electron-builder/compare/v3.3.0...v3.3.1) (2016-04-08)


### Bug Fixes

* vendor/osx/7za seems to be broken ([422a032](https://github.com/electron-userland/electron-builder/commit/422a032)), closes [#296](https://github.com/electron-userland/electron-builder/issues/296)



<a name="3.3.0"></a>
# [3.3.0](https://github.com/electron-userland/electron-builder/compare/v3.2.0...v3.3.0) (2016-04-05)


### Features

* use 7za to produce Squirrel.mac zip (smaller size — the same time to compress) ([2dd5d7c](https://github.com/electron-userland/electron-builder/commit/2dd5d7c))



<a name="3.2.0"></a>
# [3.2.0](https://github.com/electron-userland/electron-builder/compare/v3.1.2...v3.2.0) (2016-04-02)


### Features

* Linux deb — specify license, package url #242 ([c62683a](https://github.com/electron-userland/electron-builder/commit/c62683a))



<a name="3.1.2"></a>
## [3.1.2](https://github.com/electron-userland/electron-builder/compare/v3.1.1...v3.1.2) (2016-04-01)


### Bug Fixes

* Windows installer metadata is incorrect #278 ([b151ffc](https://github.com/electron-userland/electron-builder/commit/b151ffc)), closes [#278](https://github.com/electron-userland/electron-builder/issues/278)
* check windows icon to avoid unclear error messages in the 3rd-part tools ([6ad853d](https://github.com/electron-userland/electron-builder/commit/6ad853d)), closes [#243](https://github.com/electron-userland/electron-builder/issues/243)



<a name="3.1.0"></a>
# [3.1.0](https://github.com/electron-userland/electron-builder/compare/v3.0.2...v3.1.0) (2016-03-25)


### Features

* prefix dist: as marker to package in a distributable format ([fa7cc85](https://github.com/electron-userland/electron-builder/commit/fa7cc85)), closes [#267](https://github.com/electron-userland/electron-builder/issues/267)



<a name="3.0.2"></a>
## [3.0.2](https://github.com/electron-userland/electron-builder/compare/v3.0.1...v3.0.2) (2016-03-25)


### Bug Fixes

* Error publishing to github when building on travis #261 ([92f7a38](https://github.com/electron-userland/electron-builder/commit/92f7a38)), closes [#261](https://github.com/electron-userland/electron-builder/issues/261)



<a name="3.0.1"></a>
## [3.0.1](https://github.com/electron-userland/electron-builder/compare/v3.0.0...v3.0.1) (2016-03-24)


### Bug Fixes

* copy extra resources to NuGet package ([65d8126](https://github.com/electron-userland/electron-builder/commit/65d8126)), closes [#230](https://github.com/electron-userland/electron-builder/issues/230)



<a name="3.0.0"></a>
# [3.0.0](https://github.com/electron-userland/electron-builder/compare/v2.11.0...v3.0.0) (2016-03-23)


### Bug Fixes

* Linux build fails at icon conversion #239 ([c778e2b](https://github.com/electron-userland/electron-builder/commit/c778e2b)), closes [#239](https://github.com/electron-userland/electron-builder/issues/239)
* Problems downloading electron #180 ([0265db9](https://github.com/electron-userland/electron-builder/commit/0265db9)), closes [#180](https://github.com/electron-userland/electron-builder/issues/180)
* update winstaller to fix build windows on OS X ([c2bd66b](https://github.com/electron-userland/electron-builder/commit/c2bd66b))
* zip, dmg and exe filenames do not use productName as intended ([bfca0a7](https://github.com/electron-userland/electron-builder/commit/bfca0a7))


### Code Refactoring

* remove deprecated API (<2.8) ([eadd09b](https://github.com/electron-userland/electron-builder/commit/eadd09b))


### Features

* copy extra resources to packaged app ([cbe3ff8](https://github.com/electron-userland/electron-builder/commit/cbe3ff8))
* linux icons from custom dir, generate missing from ICNS ([7ac4b84](https://github.com/electron-userland/electron-builder/commit/7ac4b84))
* remove support of `build` in the application package.json ([46dbfe1](https://github.com/electron-userland/electron-builder/commit/46dbfe1)), closes [#251](https://github.com/electron-userland/electron-builder/issues/251)


### BREAKING CHANGES

* `build` is allowed since 3.0 only in the development package.json
* Deprecated <2.8 API has been removed



<a name="2.9.5"></a>
## [2.9.5](https://github.com/electron-userland/electron-builder/compare/v2.9.4...v2.9.5) (2016-03-13)


### Bug Fixes

* Windows nupkg downloaded twice each time / also keeps downloading latest release #234 ([3c90af6](https://github.com/electron-userland/electron-builder/commit/3c90af6)), closes [#234](https://github.com/electron-userland/electron-builder/issues/234)



<a name="2.9.4"></a>
## [2.9.4](https://github.com/electron-userland/electron-builder/compare/v2.9.3...v2.9.4) (2016-03-13)


### Bug Fixes

* Github publishing not working on Linux #229 ([841f397](https://github.com/electron-userland/electron-builder/commit/841f397))
* delete release again if failed with "405 Not Allowed" (3 times) ([ebf783c](https://github.com/electron-userland/electron-builder/commit/ebf783c))
* ignore newline when parsing common name in .p12 certificates ([dee8303](https://github.com/electron-userland/electron-builder/commit/dee8303))
* npm install doesn't rebuild native dependencies if arch changed — rebuild must be used ([5bcc95a](https://github.com/electron-userland/electron-builder/commit/5bcc95a))
* reupload again if failed with "502 Bad Gateway" (3 times) ([f131e33](https://github.com/electron-userland/electron-builder/commit/f131e33))



<a name="2.9.0"></a>
# [2.9.0](https://github.com/electron-userland/electron-builder/compare/v2.8.6...v2.9.0) (2016-03-09)


### Bug Fixes

* **windows:** Releases file for Windows not uploaded to Github ([9f4fba9](https://github.com/electron-userland/electron-builder/commit/9f4fba9)), closes [#190](https://github.com/electron-userland/electron-builder/issues/190)
* **windows:** do not rename artifacts twice ([9c87ffd](https://github.com/electron-userland/electron-builder/commit/9c87ffd))
* Getting "no such file or directory, rename ..." #208 ([1b6012e](https://github.com/electron-userland/electron-builder/commit/1b6012e)), closes [#208](https://github.com/electron-userland/electron-builder/issues/208)


### Features

* Allow custom .p12 certificates ([6918916](https://github.com/electron-userland/electron-builder/commit/6918916)), closes [#216](https://github.com/electron-userland/electron-builder/issues/216)
* use productName from app/package.json if present #204 ([5d376e1](https://github.com/electron-userland/electron-builder/commit/5d376e1)), closes [#204](https://github.com/electron-userland/electron-builder/issues/204) [#223](https://github.com/electron-userland/electron-builder/issues/223)



<a name="2.8.4"></a>
## [2.8.4](https://github.com/electron-userland/electron-builder/compare/v2.8.3...v2.8.4) (2016-03-03)


### Bug Fixes

* Configure build resources directory #184 ([5df87d3](https://github.com/electron-userland/electron-builder/commit/5df87d3)), closes [#184](https://github.com/electron-userland/electron-builder/issues/184) [#196](https://github.com/electron-userland/electron-builder/issues/196)



<a name="2.8.3"></a>
## [2.8.3](https://github.com/electron-userland/electron-builder/compare/v2.8.2...v2.8.3) (2016-02-25)


### Bug Fixes

* **nsis:** error on win when APP_OUT_FILE has spaces ([f4e1b41](https://github.com/electron-userland/electron-builder/commit/f4e1b41))



<a name="2.8.2"></a>
## [2.8.2](https://github.com/electron-userland/electron-builder/compare/v2.8.1...v2.8.2) (2016-02-23)


### Bug Fixes

* remove unused dependency lodash.camelcase ([c7be41b](https://github.com/electron-userland/electron-builder/commit/c7be41b))



<a name="2.8.1"></a>
## [2.8.1](https://github.com/electron-userland/electron-builder/compare/v2.8.0...v2.8.1) (2016-02-23)


### Bug Fixes

* move read-package-json to production dependencies ([ac10716](https://github.com/electron-userland/electron-builder/commit/ac10716))



<a name="2.8.0"></a>
# [2.8.0](https://github.com/electron-userland/electron-builder/compare/v2.7.2...v2.8.0) (2016-02-23)


### Features

* use read-package-json as a correct fix of Linux maintainer .deb package field ([3fba451](https://github.com/electron-userland/electron-builder/commit/3fba451))

