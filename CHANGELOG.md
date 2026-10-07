# Changelog

## [0.0.1](https://github.com/GhostMaintainers/Tubeless/compare/v0.0.1...v0.0.1) (2026-10-07)


### ⚠ BREAKING CHANGES

* bump major version for first release

### Features

* add a Time Format setting to switch between 12h and 24h ([cd91c46](https://github.com/GhostMaintainers/Tubeless/commit/cd91c465cef8c834c9bbc35aaff8ab1bf0cc18a0))
* add database insights and safe compaction maintenance to the diagnostics page ([ee741db](https://github.com/GhostMaintainers/Tubeless/commit/ee741db6c2935299d5f5216a0ee22b6a7e872745))
* Add Dependabot configuration for GitHub Actions and Docker ([003a652](https://github.com/GhostMaintainers/Tubeless/commit/003a652fca244c64864812472f80f88901fe747b))
* add GitHub Releases to Discord workflow ([#61](https://github.com/GhostMaintainers/Tubeless/issues/61)) ([a07217e](https://github.com/GhostMaintainers/Tubeless/commit/a07217e626b558cbe0f2b327e3684389e493f85f))
* add library size display to diagnostics page ([#40](https://github.com/GhostMaintainers/Tubeless/issues/40)) ([c75a5b3](https://github.com/GhostMaintainers/Tubeless/commit/c75a5b358386229c1446625e75e44ebaf84ff2a4))
* add offline database maintenance mode for backups and repairs ([bc81886](https://github.com/GhostMaintainers/Tubeless/commit/bc81886a36207760111b338b4b57b35b580c1ec5))
* add orphaned job to agnostics ([944b1d3](https://github.com/GhostMaintainers/Tubeless/commit/944b1d3679385624ecd90ba3534afcb7c5f99b4b))
* add proxy support ([8d10c52](https://github.com/GhostMaintainers/Tubeless/commit/8d10c529e34710ad799b5c7255deee9a7b18d2ca))
* Add queue diagnostics page ([#48](https://github.com/GhostMaintainers/Tubeless/issues/48)) ([578f698](https://github.com/GhostMaintainers/Tubeless/commit/578f698712339bcb5ad3186fb39db0618286cbac))
* add queue visibility and discarded job management to diagnostics ([5343985](https://github.com/GhostMaintainers/Tubeless/commit/5343985e6614d448cd0e3b1e56e78569be008800))
* add release-please, change versioning to SemVer ([67c85f3](https://github.com/GhostMaintainers/Tubeless/commit/67c85f314d25d49d60205b600da5b791ff314332))
* add setting to ignore unavailable/members-only media ([eff8c0c](https://github.com/GhostMaintainers/Tubeless/commit/eff8c0c075b287fbee19fbbcbc7a2ad234a27b64))
* add SQLite and connection pool telemetry ([876a904](https://github.com/GhostMaintainers/Tubeless/commit/876a904f9cdef921fca82dbdc761670969f10f17))
* add system status summary to the home page ([7019007](https://github.com/GhostMaintainers/Tubeless/commit/7019007a045baa75828a60dce1a1a8690b2c073e))
* add table density setting, add profile filter and pagination controls ([dc9f635](https://github.com/GhostMaintainers/Tubeless/commit/dc9f6357c7373fdfbdf2d0441a96e93be8749419))
* Add YouTube API key testing in Settings ([#47](https://github.com/GhostMaintainers/Tubeless/issues/47)) ([90303c1](https://github.com/GhostMaintainers/Tubeless/commit/90303c15108a45f22c4fffbd31f15a99ade1f24c))
* allow SponsorBlock to both remove and mark selected categories ([ba09ff9](https://github.com/GhostMaintainers/Tubeless/commit/ba09ff933301d48ae7ed72a54cb901db8955f72a))
* bump major version for first release ([1bedbe4](https://github.com/GhostMaintainers/Tubeless/commit/1bedbe4c1bd6edab107af5e529b03f2df4ecb2b6))
* bump release ([914dbd3](https://github.com/GhostMaintainers/Tubeless/commit/914dbd3c1f0caea4e3238a64a4ad4b7df424c5c2))
* check the database for corruption from the diagnostics page ([ade672b](https://github.com/GhostMaintainers/Tubeless/commit/ade672bc6cb7778672d9005c955e901915f95ed1))
* control yt-dlp update behavior from settings ([058ba47](https://github.com/GhostMaintainers/Tubeless/commit/058ba4762a5415246cf73f4e68cddda68bc1f295))
* let media profiles ignore YouTube AI-upscaled videos ([8e2f334](https://github.com/GhostMaintainers/Tubeless/commit/8e2f334c4556353bbb12e6addd24f739181a44d8))
* let new sources default to a configurable Cookie Behavior ([42f2245](https://github.com/GhostMaintainers/Tubeless/commit/42f224503d52ea69facb11c90b20d38373dd791d))
* let sources stop indexing large channels at a cutoff date ([6b6a249](https://github.com/GhostMaintainers/Tubeless/commit/6b6a2492fa5d67d48f04f9b13e707ddc4a95ff59))
* let templates mark where channel artwork and NFOs are stored ([279bebf](https://github.com/GhostMaintainers/Tubeless/commit/279bebfdc8ce1f3fa4f6d69f772c58ea356c6ac9))
* mask YouTube API key and add cookies file management ([#53](https://github.com/GhostMaintainers/Tubeless/issues/53)) ([343a630](https://github.com/GhostMaintainers/Tubeless/commit/343a630638bdf099a786e9022e3f3f6daf712a92))
* publish sources as static podcast feeds servable without exposing Tubeless ([#55](https://github.com/GhostMaintainers/Tubeless/issues/55)) ([ee5ed6a](https://github.com/GhostMaintainers/Tubeless/commit/ee5ed6a39a2c584436cd91d0bafdab8293b988af))
* rebrand user-facing product name to Tubeless ([739d82a](https://github.com/GhostMaintainers/Tubeless/commit/739d82a3665566cec21f60daaec1b7890321d3f0))
* recover jobs stuck with retries exhausted from diagnostics ([773e6c1](https://github.com/GhostMaintainers/Tubeless/commit/773e6c198415e5d8572fb7f93c94d7050d12e458))
* refresh Queue Health on the diagnostics page without a full page reload ([85cea6b](https://github.com/GhostMaintainers/Tubeless/commit/85cea6ba0505153b7a79f857fc546561a5ed1f35))
* relocate and true up downloaded files after settings changes, without re-downloading ([ad2a66e](https://github.com/GhostMaintainers/Tubeless/commit/ad2a66ec152133866a6f413cd3903b68496129e2))
* remove Pro unlock and Donate button — every feature is available out of the box ([7daad33](https://github.com/GhostMaintainers/Tubeless/commit/7daad33ab360962308c3c6a98024b1d0bb9af3ae))
* reorganize settings into task-based cards that auto-save inline ([223a038](https://github.com/GhostMaintainers/Tubeless/commit/223a03868bf625086d38d0f9d88a3f31f3ac4856))
* report accurate status for non-downloaded media in Other tab ([8c188ac](https://github.com/GhostMaintainers/Tubeless/commit/8c188aca346a873e31ee2b8296c3e20f09615cf9))
* requeue stuck jobs from the Diagnostics page instead of cancelling them ([cbabc68](https://github.com/GhostMaintainers/Tubeless/commit/cbabc68414a12ee4c42acecec62c6e0fe08e5cba))
* require accepting a user agreement before first use ([58122eb](https://github.com/GhostMaintainers/Tubeless/commit/58122eb75c0639aec555d7d6d9379b2a783f628a))
* separate downloads that are queued from those still pending on the home page ([de1d474](https://github.com/GhostMaintainers/Tubeless/commit/de1d474cd1ebd5921a1509e383ab0d2389c25a4d))
* Set retention to keep 5 most recent images ([8229782](https://github.com/GhostMaintainers/Tubeless/commit/82297829a85453b902a5fbeb2aca2e7b46a7ce6e))
* show live progress while a reconcile plan applies ([87a27c8](https://github.com/GhostMaintainers/Tubeless/commit/87a27c82cde86c74a06731f72ef1375acfb19c89))
* speed up reconcile by fetching online backfills in parallel ([05049fc](https://github.com/GhostMaintainers/Tubeless/commit/05049fc7a299fd6b4ad794ab7529a94ea7707b24))
* surface auto-skipped unavailable media as a distinct status ([e88d403](https://github.com/GhostMaintainers/Tubeless/commit/e88d403c4d3b655ee08b5785298313e3fb6f3df8))
* **ui:** redesign the source detail page ([fb74813](https://github.com/GhostMaintainers/Tubeless/commit/fb74813049ca2acd26c17343dbdf022533107f20))
* **ui:** rework the media profiles list and detail pages ([98b2856](https://github.com/GhostMaintainers/Tubeless/commit/98b285692123cea4bb94eaa1783e171e81091bb8))


### Bug Fixes

* add link in Cookie Behaviour help to the YouTube Cookies wiki page ([2c1f9cf](https://github.com/GhostMaintainers/Tubeless/commit/2c1f9cf97bd6103cbba2095d34dc9cf6a2acb7fc))
* assigng correct tags to dev builds ([36709df](https://github.com/GhostMaintainers/Tubeless/commit/36709df589050e2f2787d505c43f551872ca6c9b))
* auto-refresh Media History on job state changes ([98d654f](https://github.com/GhostMaintainers/Tubeless/commit/98d654fb32736da9948bb1d11ccdf94c43aed537))
* avoid length/1 check and reformat mix.exs deps ([4d3986a](https://github.com/GhostMaintainers/Tubeless/commit/4d3986acfee4a5762f2357518b2db6f1008b1e87))
* Change CI base image to latest version ([34642de](https://github.com/GhostMaintainers/Tubeless/commit/34642dea3564d02886541ab498231321b7b5d963))
* **ci:** correct casing for ghcr ([e08570b](https://github.com/GhostMaintainers/Tubeless/commit/e08570bb7d50fa9df6e372459d0cb58f64f1b7a5))
* **ci:** correct job deps in release ([a03f71a](https://github.com/GhostMaintainers/Tubeless/commit/a03f71acb8172b6944fb4ef65d81b5eb414eebd9))
* **ci:** ignore prettier in changelog ([de54801](https://github.com/GhostMaintainers/Tubeless/commit/de548018f7d17e1c2db6d7e8d466ea4de24e9f83))
* **ci:** move discord notification to release-please workflow ([fa8ddfd](https://github.com/GhostMaintainers/Tubeless/commit/fa8ddfdc890abe28d249f1c91e138a5463591208))
* **ci:** remove CalVer, build version needs to be semver compliant ([55dece8](https://github.com/GhostMaintainers/Tubeless/commit/55dece8e63f77520e3a55d1a587415d7661b2b3d))
* clarify main page storage usage ([b0cdcad](https://github.com/GhostMaintainers/Tubeless/commit/b0cdcada979182a46695c6f852d05a50bcd6075b))
* configure Oban PG notifier and incomplete unique states for 2.23 ([0fb0183](https://github.com/GhostMaintainers/Tubeless/commit/0fb018302e699e106c5c8d0e552e3c69b08509b6))
* correct pending count for sources with no downloaded media ([8675262](https://github.com/GhostMaintainers/Tubeless/commit/8675262eebc7dad00f229d850fad9f50d3b09ef1))
* correct static Size values in sources table on re-sort ([a876bcd](https://github.com/GhostMaintainers/Tubeless/commit/a876bcd817847a87e44bbbc9f50b366202186b0a)), closes [#112](https://github.com/GhostMaintainers/Tubeless/issues/112)
* **deps:** add sctp1 module for otp 29 ([7a520d5](https://github.com/GhostMaintainers/Tubeless/commit/7a520d5088c3095669f0b77ad78ebbe4fc18044f))
* Disable Docker Hub login in release workflow ([48f1af9](https://github.com/GhostMaintainers/Tubeless/commit/48f1af9e8067dbc27df68cd370d616e6a61c9d57))
* Disable Docker Hub login in release workflow ([3a92d31](https://github.com/GhostMaintainers/Tubeless/commit/3a92d31b3286731be0b8b89b82ec8cab754536a0))
* fetch sqlean extension when a stale version marker has no binaries ([e9fe03c](https://github.com/GhostMaintainers/Tubeless/commit/e9fe03c4125b391244d641c45fab72f703d976be))
* further db access optimizations ([0a9990c](https://github.com/GhostMaintainers/Tubeless/commit/0a9990c9485cb91b87e31618cf9680f954292573))
* handle suffix Range requests and missing files when streaming media ([e4c5a32](https://github.com/GhostMaintainers/Tubeless/commit/e4c5a3293f7c6cf4fc5e3d13324e8cc27f0606d5))
* handle unparseable yt-dlp source metadata responses gracefully ([813c8ad](https://github.com/GhostMaintainers/Tubeless/commit/813c8adcda43a6885dde19b4e2496526810417f8))
* increase db conn pool and cache to help with reconcile responsivity ([cd55489](https://github.com/GhostMaintainers/Tubeless/commit/cd55489049625681940e15119886c7f2d8257785))
* index channel tabs separately so new shorts are found on repeat indexes ([13a160a](https://github.com/GhostMaintainers/Tubeless/commit/13a160a0a8b84d2c0f7b7214e73ba305acb58365)), closes [#59](https://github.com/GhostMaintainers/Tubeless/issues/59)
* keep indexing reschedule from deduping against its own executing job ([115f8db](https://github.com/GhostMaintainers/Tubeless/commit/115f8db8ef6e6b1a7edf72844536a8ade2f9e0a1))
* label binary byte sizes with IEC units eg. KiB/MiB/GiB ([47fde1f](https://github.com/GhostMaintainers/Tubeless/commit/47fde1f81a992d4b0c8d7634a4c11ba6075330a1))
* label File Reconciliation jobs in the Active Tasks list ([552de57](https://github.com/GhostMaintainers/Tubeless/commit/552de5750acf43d29c219dd21b4124fe76e224fe))
* linter ([7b29408](https://github.com/GhostMaintainers/Tubeless/commit/7b29408165bfca80d6c0c344dd275a1c880fd799))
* match the Queue Health refresh button to the other action buttons ([668999e](https://github.com/GhostMaintainers/Tubeless/commit/668999eb346d3ab1650128a915e3a306b69a2366))
* name episode thumbnails to match the media file so Plex displays them ([5d27ea6](https://github.com/GhostMaintainers/Tubeless/commit/5d27ea6c03ca8a83ecb8a37190bfb3a90b25c420))
* pin Deno and Apprise in selfhosted runner to match ci-base ([b9b372c](https://github.com/GhostMaintainers/Tubeless/commit/b9b372cbabf956fd4eabecf82de6c843cda7cae4))
* prettier'd new code ([ba41fb2](https://github.com/GhostMaintainers/Tubeless/commit/ba41fb22cd5f954d9033efcfec4c94838be8c462))
* re-download existing media by forcing the download job ([f47a6e0](https://github.com/GhostMaintainers/Tubeless/commit/f47a6e03e2780cc67b6646560410085adb90e453))
* re-index a source when its indexing cutoff reaches further into the past ([aa2fc43](https://github.com/GhostMaintainers/Tubeless/commit/aa2fc4329eda2d6e4f60fbf8afd20bb5a7064971))
* recover a reconcile apply interrupted by a restart instead of deadlocking ([221643f](https://github.com/GhostMaintainers/Tubeless/commit/221643f82eb767b78e4ceb3990e1a8e902f6c818))
* reflect new github org in webui ([2b8faeb](https://github.com/GhostMaintainers/Tubeless/commit/2b8faeb29f342cc2d4382f0caee0add8a0046dbd))
* Remove Docker Hub login from release workflow ([20acd9a](https://github.com/GhostMaintainers/Tubeless/commit/20acd9ab9a7404f78bcfac33c81c8d12248de238))
* render NFO aired date as plain date for Jellyfin ([#60](https://github.com/GhostMaintainers/Tubeless/issues/60)) ([0282c19](https://github.com/GhostMaintainers/Tubeless/commit/0282c19789d3154bf4eff92a74c8d7c90186ba5f)), closes [#57](https://github.com/GhostMaintainers/Tubeless/issues/57)
* reschedule missing source indexing jobs on boot ([beb6a16](https://github.com/GhostMaintainers/Tubeless/commit/beb6a16ea25a94e9c68d9560bba035debaa5e113))
* resolve Elixir 1.20 compiler warnings ([43ea35d](https://github.com/GhostMaintainers/Tubeless/commit/43ea35dcf9ee8ef8b73ddd861b16326230af4320))
* restore the media search box after a LiveView reconnect ([c447d21](https://github.com/GhostMaintainers/Tubeless/commit/c447d21d413fd64875c91a47228ea5b9559fdce6))
* route ecto.migrate ERD guard through sh for Elixir 1.20 ([04cf3f3](https://github.com/GhostMaintainers/Tubeless/commit/04cf3f3ccfac71f5c8f17472b8eba20ca54d8439))
* serialize quiet-window workers to prevent deadlock situation ([4e7ac31](https://github.com/GhostMaintainers/Tubeless/commit/4e7ac3140548e8f92a63dc7ec36ba03898b394b4))
* serve apple-touch-icon to avoid 404 probes from iOS ([451123b](https://github.com/GhostMaintainers/Tubeless/commit/451123b108bf2dfa14c6b87577a261f4c739d0f3))
* show log timestamps in the configured timezone ([af8e3a7](https://github.com/GhostMaintainers/Tubeless/commit/af8e3a74ef02f29b8dcc9dd1fa931ba1f70419bf))
* show more useful precision on disk space and file sizes ([85e6acb](https://github.com/GhostMaintainers/Tubeless/commit/85e6acb7f9be515b729ce6452f18f74680faeb82))
* show time using the configured timezone ([fba9c3c](https://github.com/GhostMaintainers/Tubeless/commit/fba9c3c78cc1e353ac4a49077fa9cb96711ebcf4))
* skip download archive when the archive file cannot be written ([5aac447](https://github.com/GhostMaintainers/Tubeless/commit/5aac4477f36d291b27045434eedf6aaf8f08e246))
* stop bold+italic text from loading a broken Satoshi font glyph ([49f7fd4](https://github.com/GhostMaintainers/Tubeless/commit/49f7fd40843c49dd37bdac27d67d72c912a34345))
* stop counting actively-downloading videos as Queued on the dashboard ([172dc5f](https://github.com/GhostMaintainers/Tubeless/commit/172dc5f37ac6b9b611b82f43713331a61b333dfe))
* stop crashing when rendering 404 and 500 error pages ([#154](https://github.com/GhostMaintainers/Tubeless/issues/154)) ([7b0bd7f](https://github.com/GhostMaintainers/Tubeless/commit/7b0bd7f37668a6428172a471c843d6a582cebb36))
* stop disabled form fields from flashing white on the dark theme ([c0c3d0f](https://github.com/GhostMaintainers/Tubeless/commit/c0c3d0f074ad55d02121bd63a9168e9ad55863fa))
* stop logging YouTube API keys ([515eabf](https://github.com/GhostMaintainers/Tubeless/commit/515eabf1a5a59abffe32c2d18ffc98c47ab1e222))
* stop losing in-flight source enable toggles on LiveView reconnect ([6d9d184](https://github.com/GhostMaintainers/Tubeless/commit/6d9d184d9d973ffa4fbda4d16d8e4d268018cff2))
* stop the diagnostics page crashing when job queues aren't running ([779080c](https://github.com/GhostMaintainers/Tubeless/commit/779080c20b1ee0809bbdd770bc3f82fc7002633c))
* test all YouTube API keys and report which fail ([347f0be](https://github.com/GhostMaintainers/Tubeless/commit/347f0be760933ac546766f24bed689f475d69d6f))
* throttle job state broadcasts to reduce dashboard query load ([21555ae](https://github.com/GhostMaintainers/Tubeless/commit/21555aef88e33be75b0af3e7ec374a9483a5f2c9))
* **tooling:** abort container startup when database migration fails ([3fc0dd9](https://github.com/GhostMaintainers/Tubeless/commit/3fc0dd959fce68f7ac0d688639d2a6f00f1fc203))
* **ui:** don't underline trailing white space past link text ([692890d](https://github.com/GhostMaintainers/Tubeless/commit/692890d97d373ef0321ac7bd514be68d7b096f75))
* unlock-pro modal button stuck disabled ([#125](https://github.com/GhostMaintainers/Tubeless/issues/125)) ([5c26116](https://github.com/GhostMaintainers/Tubeless/commit/5c261160f79ea9fccaea8cafd3096d1954ddd1c0))
* Update base image in dev Dockerfile ([8393437](https://github.com/GhostMaintainers/Tubeless/commit/8393437d16cef5d56fcd17b6c78071716fb395c3))
* Update CI base image reference in Dockerfile ([29bcdff](https://github.com/GhostMaintainers/Tubeless/commit/29bcdff2ce3d60e17feeda99ceaa5ce7f65f0ba2))
* Update CI_BASE_IMAGE and comment out Discord job ([bbf1a0c](https://github.com/GhostMaintainers/Tubeless/commit/bbf1a0cf758a92e6131d81be7b3a32559d49180e))
* Update FFMPEG_RELEASE and FFMPEG_BUILD arguments ([07254e2](https://github.com/GhostMaintainers/Tubeless/commit/07254e24a8824105e27844c6213f42962634f70b))
* Update FFMPEG_RELEASE and FFMPEG_BUILD arguments ([27bf8f7](https://github.com/GhostMaintainers/Tubeless/commit/27bf8f7d3694614613035ab74c972b6df5cd3e8d))
* update formatting for phoenix ([cd6cc8b](https://github.com/GhostMaintainers/Tubeless/commit/cd6cc8b542ac405074ed773dc34314bdc3d89300))
* Update image cleanup workflow account name ([471351e](https://github.com/GhostMaintainers/Tubeless/commit/471351eabaeec0c39e7faafb530894ce9cbd1187))
* update image name ([122503d](https://github.com/GhostMaintainers/Tubeless/commit/122503de2f03d1c57eb7d117b3ae88928f028538))
* Update image repository in CI workflow ([dc0fb25](https://github.com/GhostMaintainers/Tubeless/commit/dc0fb25e1cdddba8bf9a09ff80d63e119170f925))
* warn on malformed output-path templates in the UI ([c4bb94a](https://github.com/GhostMaintainers/Tubeless/commit/c4bb94a0f7af07023d295e8bd9f7a990ab9aa376))


### Reverts

* Move Active Tasks to tab in Media History section ([#836](https://github.com/GhostMaintainers/Tubeless/issues/836)) ([59849e3](https://github.com/GhostMaintainers/Tubeless/commit/59849e342817d1961feb147c6c0b0aa325a993e3))


### Chores

* add fast Docker test runner for local iteration ([b976cf2](https://github.com/GhostMaintainers/Tubeless/commit/b976cf2aad014fc6fb43ee9a97a15b57daa18b12))
* add local CI lint/test script ([6b5bc79](https://github.com/GhostMaintainers/Tubeless/commit/6b5bc7926e3037a70417714548db9f05a13e5463))
* add sqlite to final image ([c1cbdb2](https://github.com/GhostMaintainers/Tubeless/commit/c1cbdb2c7ad112e7fd1f44634ff7246c8262c89e))
* add tooling script ([460fbd1](https://github.com/GhostMaintainers/Tubeless/commit/460fbd1c6ce7783bbae8932ed64ee24ea4325a2e))
* bump sqleton ([6ecadf7](https://github.com/GhostMaintainers/Tubeless/commit/6ecadf74edc09fdd580f5d36110365313588070f))
* **ci:** break out ci-build into phases ([2060ab9](https://github.com/GhostMaintainers/Tubeless/commit/2060ab956abcc97cc4b9d11c517ca6a81f45ab9f))
* **ci:** bump ci-base image to sha-93af908 ([6d29a27](https://github.com/GhostMaintainers/Tubeless/commit/6d29a276522c034fdf6f824a14e096431488ff35))
* **ci:** bump ci-base image to sha-ba3e559 ([a13ac24](https://github.com/GhostMaintainers/Tubeless/commit/a13ac24d9a81d804234bd024b4a789c793bb0492))
* **ci:** bump pinned ci-base image to sha-1629079 ([65789d1](https://github.com/GhostMaintainers/Tubeless/commit/65789d1b04a80bb6d80ac3fabf87bd77f60783e1))
* **ci:** fetch sqlean extensions at build time instead of vendoring ([053064b](https://github.com/GhostMaintainers/Tubeless/commit/053064b8d6abe262a96131715240020da92f2600))
* **ci:** improve local docker script ([d339fff](https://github.com/GhostMaintainers/Tubeless/commit/d339fff4e9e8fd626c1cdb6ac48a2eb31ed47bb0))
* **ci:** lint and and local run docker ([#62](https://github.com/GhostMaintainers/Tubeless/issues/62)) ([622f5e0](https://github.com/GhostMaintainers/Tubeless/commit/622f5e03c7c5ad7e8a50d1c24be7a9a000b3c305))
* **ci:** release config updates ([4bf8cf2](https://github.com/GhostMaintainers/Tubeless/commit/4bf8cf26ea3620eb1330b30cf6afba8ba74a8dad))
* **ci:** run lint/test jobs natively in ci-base container ([e5430f2](https://github.com/GhostMaintainers/Tubeless/commit/e5430f2a96cf58bc13f7ea8d904b8ffe86ab963b))
* **ci:** switch from Github issue templates to the new issue forms ([#34](https://github.com/GhostMaintainers/Tubeless/issues/34)) ([61c54f3](https://github.com/GhostMaintainers/Tubeless/commit/61c54f35a8b1ecf8a34b5eb83b053ddc4b229d13))
* **ci:** track hexpm/elixir base image versions with Renovate ([ba3e559](https://github.com/GhostMaintainers/Tubeless/commit/ba3e559ec54cc2e925312e0cec3ee07e18bf88a0))
* **ci:** use ci-build image sha-2060ab9 ([129609d](https://github.com/GhostMaintainers/Tubeless/commit/129609dd2cb5cccbc17f202685451a0133569f49))
* **ci:** use main as default branch ([ea68a7c](https://github.com/GhostMaintainers/Tubeless/commit/ea68a7c0daa1c9bb0e7ebead34a9c1e9112997df))
* **ci:** use new ci image ([1dc9b2b](https://github.com/GhostMaintainers/Tubeless/commit/1dc9b2b467a91cb564ae1f6985f187be6ce08bbe))
* clarify migration paths ([7ac7551](https://github.com/GhostMaintainers/Tubeless/commit/7ac755108ae88d3c7407068dd13aaf07c6284bb3))
* **deps:** alpinejs 3.15.12 ([a12f722](https://github.com/GhostMaintainers/Tubeless/commit/a12f72252945aa5fcb50f7f2af77c470aaacd64b))
* **deps:** bump docker/build-push-action from 7.3.0 to 7.4.0 ([9915aea](https://github.com/GhostMaintainers/Tubeless/commit/9915aea95b593d55a4508b0978eb4473e4683a29))
* **deps:** bump docker/build-push-action from 7.3.0 to 7.4.0 ([9b5fc94](https://github.com/GhostMaintainers/Tubeless/commit/9b5fc94cccb5b62bef1580ff4a93337a5064165b))
* **deps:** bump docker/login-action from 4.5.1 to 4.6.0 ([19faeb4](https://github.com/GhostMaintainers/Tubeless/commit/19faeb4e6a5928950a8c61899c28b8c374e912e4))
* **deps:** bump docker/login-action from 4.5.1 to 4.6.0 ([c8b620b](https://github.com/GhostMaintainers/Tubeless/commit/c8b620bb6ccd341e35d6bf3bf88465c757a2ee54))
* **deps:** bump docker/setup-buildx-action from 4.2.0 to 4.4.1 ([07dddbf](https://github.com/GhostMaintainers/Tubeless/commit/07dddbf1e610a06a8080b53570c419e751d5e5ff))
* **deps:** bump docker/setup-buildx-action from 4.2.0 to 4.4.1 ([7dbd6e9](https://github.com/GhostMaintainers/Tubeless/commit/7dbd6e9004f5769b583c6bf70e09ebaa822500b6))
* **deps:** bump docker/setup-qemu-action from 4.2.0 to 4.4.0 ([8077a44](https://github.com/GhostMaintainers/Tubeless/commit/8077a4487e04093ff62dccef056106282e48b245))
* **deps:** bump docker/setup-qemu-action from 4.2.0 to 4.4.0 ([56c0e98](https://github.com/GhostMaintainers/Tubeless/commit/56c0e98ea6b29fa5d02425800fd6ef4fb4a13e68))
* **deps:** bump Elixir 1.20.2, OTP 28.5.0.2, Debian trixie-20260623 in ci-base ([95b825a](https://github.com/GhostMaintainers/Tubeless/commit/95b825afc7bf93dc96d469f30252d6db0157bd48))
* **deps:** bump elixir deps ([e31b3ab](https://github.com/GhostMaintainers/Tubeless/commit/e31b3abb802510ceaafdaab67a1eef6f87977362))
* **deps:** bump Erlang/OTP to 28.5.0.3 ([cf681a2](https://github.com/GhostMaintainers/Tubeless/commit/cf681a2962a6247aab5ceafd3e003d7df2db697c))
* **deps:** bump esbuild and tailwind pinned binary versions ([300478d](https://github.com/GhostMaintainers/Tubeless/commit/300478d3cb2fec585f702268d2269a42a03770e3))
* **deps:** bump ffmpeg build ([de3f25a](https://github.com/GhostMaintainers/Tubeless/commit/de3f25a040f52bccabe1be54436a3ae28c02c822))
* **deps:** bump Node 20 -&gt; 24 in ci-base, add renovate tracking, sync CODEBASE versions ([f22adc4](https://github.com/GhostMaintainers/Tubeless/commit/f22adc49c18a5734476dee61165b3496368e4501))
* **deps:** bump otp to 29.0.4 ([c623288](https://github.com/GhostMaintainers/Tubeless/commit/c623288d3edae4fa0090fe60fe460fbbb41cba6d))
* **deps:** faker to work with elixir 1.20; update misc deps ([edbff35](https://github.com/GhostMaintainers/Tubeless/commit/edbff3587d58f72023e4685e114f1700d7fbbe50))
* **deps:** pin dependencies ([caa7379](https://github.com/GhostMaintainers/Tubeless/commit/caa7379dc73b34f6cb8759971ae5150711bce443))
* **deps:** pin dependencies ([e002b75](https://github.com/GhostMaintainers/Tubeless/commit/e002b7547bf9f374069a7983d79b0d68d541aaa8))
* **deps:** pin elixir in renovate ([cb55b03](https://github.com/GhostMaintainers/Tubeless/commit/cb55b0300e14b513e86374e199f9787415e21731))
* **deps:** replace floki with lazy_html ([13d7924](https://github.com/GhostMaintainers/Tubeless/commit/13d79242daf9b7a16a4358ccf82369d4a38782a7))
* **deps:** tighten ecto_sqlite3 and prom_ex constraints and bump locked deps ([768b120](https://github.com/GhostMaintainers/Tubeless/commit/768b12051b0578d92e06d36e464af0779e60e842))
* **deps:** update actions/cache action to v6 ([271b43b](https://github.com/GhostMaintainers/Tubeless/commit/271b43b1de7de7926c7c78636ca590e802d00d80))
* **deps:** update actions/checkout action to v7 ([bb1a5e3](https://github.com/GhostMaintainers/Tubeless/commit/bb1a5e35e9eaa4684bfcd53630e3c5a15626550d))
* **deps:** update Debian snapshot to trixie-20260713-slim ([f3a5e12](https://github.com/GhostMaintainers/Tubeless/commit/f3a5e12f60d200cc1c03353c879e3658dacf3ead))
* **deps:** update dependency alpinejs to v3.15.12 ([a753ff8](https://github.com/GhostMaintainers/Tubeless/commit/a753ff8f4cd2535ce0a216b58c9e2f248b007801))
* **deps:** update dependency apprise to v1.12.0 ([945105b](https://github.com/GhostMaintainers/Tubeless/commit/945105be5544cfd911b161d560cebac010b91b46))
* **deps:** update dependency exqlite to 0.38.0 ([6e2dc17](https://github.com/GhostMaintainers/Tubeless/commit/6e2dc17dc7d0b7dcfbcff8d15fce4228713180d6))
* **deps:** update dependency phoenix to ~&gt; 1.8.0 ([9c0f74d](https://github.com/GhostMaintainers/Tubeless/commit/9c0f74dcdcc53059a86a4639eff7ef6aee440bd9))
* **deps:** update dependency phoenix_live_view to v1.2.4 ([a239149](https://github.com/GhostMaintainers/Tubeless/commit/a2391491ece970bb80fb15ecc87d14c75624ac41))
* **deps:** update dependency phoenix_live_view to v1.2.5 ([b2d638e](https://github.com/GhostMaintainers/Tubeless/commit/b2d638e6016be4fbd97211354e18e5b2213214f8))
* **deps:** update dependency prettier to v3.8.4 ([cd0456d](https://github.com/GhostMaintainers/Tubeless/commit/cd0456de4ae71f4385c62d342086c043eabef421))
* **deps:** update dependency prettier to v3.8.5 ([9389279](https://github.com/GhostMaintainers/Tubeless/commit/93892793013fe284804494867fe81a38fa99c3ea))
* **deps:** update dependency prettier to v3.9.0 ([2e9301a](https://github.com/GhostMaintainers/Tubeless/commit/2e9301a1bd3f4430a1ad53cea9aa74f318aae252))
* **deps:** update dependency prettier to v3.9.1 ([a66decb](https://github.com/GhostMaintainers/Tubeless/commit/a66decb323fe6c1480a18f0f1fe20bcaf96dbaa8))
* **deps:** update dependency prettier to v3.9.3 ([8130c84](https://github.com/GhostMaintainers/Tubeless/commit/8130c84d5372f3f56210bdb8c4480447041864f5))
* **deps:** update dependency prettier to v3.9.4 ([d2c4d45](https://github.com/GhostMaintainers/Tubeless/commit/d2c4d45215b4874fdbdd6321a9f3317e6aaf4ade))
* **deps:** update dependency prettier to v3.9.5 ([a6359e0](https://github.com/GhostMaintainers/Tubeless/commit/a6359e07f4d33fc5be75861e39d4546eee4744b2))
* **deps:** update dependency prettier to v3.9.6 ([a1980d1](https://github.com/GhostMaintainers/Tubeless/commit/a1980d10a93ba48584b7e8a73675ee1f19dbc1af))
* **deps:** update dependency sobelow to ~&gt; 0.14 ([1bcaeeb](https://github.com/GhostMaintainers/Tubeless/commit/1bcaeeb80d0086661726d2784a06ec770fd69326))
* **deps:** update dependency sqleton to v2.3.0 ([74ef149](https://github.com/GhostMaintainers/Tubeless/commit/74ef149c7f7ac76cbed707188c84379a39bff742))
* **deps:** update dependency sqleton to v4 ([3143550](https://github.com/GhostMaintainers/Tubeless/commit/31435505b4cd892f23a7bbeba4ad646f6a82b0bc))
* **deps:** update dependency tailwind to ~&gt; 0.5.0 ([9e38148](https://github.com/GhostMaintainers/Tubeless/commit/9e38148d894629d3deb52e95935dcc69564e6d57))
* **deps:** update docker/login-action digest to abd2ef4 ([8461f41](https://github.com/GhostMaintainers/Tubeless/commit/8461f4102c891a8bb0640052f7bb7d8e0370e088))
* **deps:** update github actions ([8003703](https://github.com/GhostMaintainers/Tubeless/commit/800370390b385ba5f65b3b5b060d7c49429d5cf4))
* **deps:** update github actions ([c487511](https://github.com/GhostMaintainers/Tubeless/commit/c487511b27d2efc3927edec026f752f049143f7d))
* **deps:** update github actions ([fa27ffe](https://github.com/GhostMaintainers/Tubeless/commit/fa27ffefd790a351133be05cc413fe656cf07bab))
* **deps:** update github actions to v7 ([#52](https://github.com/GhostMaintainers/Tubeless/issues/52)) ([7429586](https://github.com/GhostMaintainers/Tubeless/commit/742958666e59b82e8b17710c9e3dfa6de36da3f3))
* **deps:** update OTP to 29.0.3 in ci-base image ([1629079](https://github.com/GhostMaintainers/Tubeless/commit/1629079b7ffdce615e1e7be8e74183ae1d35fe02))
* **deps:** update phoenix_live_view ([e0651b6](https://github.com/GhostMaintainers/Tubeless/commit/e0651b68765431dcb5bdfde5ec6463b41d545e24))
* **deps:** update renovate constraints ([7051c58](https://github.com/GhostMaintainers/Tubeless/commit/7051c58c92809767826639f5ad9bcf6f2ac7ea19))
* **deps:** update timex digest to 3.7.13 ([e4f9983](https://github.com/GhostMaintainers/Tubeless/commit/e4f99831d2540f7cf98e05d68daea740b1f1c1b1))
* **deps:** update timex digest to 5ad1b82 ([83710dc](https://github.com/GhostMaintainers/Tubeless/commit/83710dcb75b88ede0e97451883424bc6d8920665))
* **deps:** update to 2026-07-01-16-32 ffmpeg build ([93af908](https://github.com/GhostMaintainers/Tubeless/commit/93af908ee245665899331600b464d6f88e462f28))
* **deps:** use new elixir/otp ([f5e830b](https://github.com/GhostMaintainers/Tubeless/commit/f5e830b97a7e553c3660e14f93d8b76316b98b1a))
* **deps:** use published faker instead of private git fork ([792da4a](https://github.com/GhostMaintainers/Tubeless/commit/792da4abc49c7e55b58081cb10fedbf4f4e57a03))
* **doc:** reformat CHANGELOG ([9170c6c](https://github.com/GhostMaintainers/Tubeless/commit/9170c6c2fb0b00b39182b630493f8683aa7f936b))
* drop unused settings_backup table ([1bc6c28](https://github.com/GhostMaintainers/Tubeless/commit/1bc6c280b4107a5ee11977e8e44cf70be179d9a3))
* ignore runtime wiring and test support in coverage reporting ([a8f6d76](https://github.com/GhostMaintainers/Tubeless/commit/a8f6d76d4da44a3c44ada129957daaa6090cc78b))
* **master:** release 1.0.0 ([5776d49](https://github.com/GhostMaintainers/Tubeless/commit/5776d49c7d4bd343ab96eb563e0ad03579c5ebca))
* **master:** release 1.1.0 ([#26](https://github.com/GhostMaintainers/Tubeless/issues/26)) ([9d4c7e6](https://github.com/GhostMaintainers/Tubeless/commit/9d4c7e64a73e6b6486dd408bd849d0b2bee900c6))
* **master:** release 1.2.0 ([3f7ad33](https://github.com/GhostMaintainers/Tubeless/commit/3f7ad33dacb2cf61b508ad940a9dd9a8f3da0484))
* move to debain trixie ([8103c96](https://github.com/GhostMaintainers/Tubeless/commit/8103c9676f48f4605e7ed3bcd80104dc512f1fa8))
* prettify satoshi.css to pass lint ([067b4c1](https://github.com/GhostMaintainers/Tubeless/commit/067b4c1bc806b6415d4ea11e982bbbe464fcbd18))
* schedule renovate biweekly, remove PR rate limits, enable dependency dashboard ([efe8668](https://github.com/GhostMaintainers/Tubeless/commit/efe8668216c4070ad443935958157f8466f9f6b5))
* set app version to 1.0.0 (2026.6.14) [skip ci] ([ac12ace](https://github.com/GhostMaintainers/Tubeless/commit/ac12ace16959ba823e978239999f726b0508ae9e))
* track ci-base pip requirements with Renovate ([8f1194d](https://github.com/GhostMaintainers/Tubeless/commit/8f1194dc50d0484f9bd6fe944e86ed77d039064c))
* tune release-please changelog sections ([5e1fa12](https://github.com/GhostMaintainers/Tubeless/commit/5e1fa12cb63113ac3a283d0b8f4b07ac483e9b78))
* update images ([77ab2e5](https://github.com/GhostMaintainers/Tubeless/commit/77ab2e56942eaa6233110d0c21dbd0ab66ecf717))
* upgrade Tailwind CSS to v4.3.3 ([97ccb64](https://github.com/GhostMaintainers/Tubeless/commit/97ccb64f29147bfde4a8f911c5869734dcac87e6))


### Documentation

* Add `error` to LOG_LEVEL options in README.md ([1ab61dd](https://github.com/GhostMaintainers/Tubeless/commit/1ab61dd6a3dd1f47bf642c9f4a66825f18dd53e7))
* Add audio & video codec preference to features list ([6c9b083](https://github.com/GhostMaintainers/Tubeless/commit/6c9b083a191b9771ff7ad81374ba4c5e8645854d))
* add Caddy config example ([2a476a0](https://github.com/GhostMaintainers/Tubeless/commit/2a476a0e6bf723a54e922e21c41f79e817e33302))
* add CI instructions ([77119c5](https://github.com/GhostMaintainers/Tubeless/commit/77119c5929389a390785fbe052901d16b93b4e16))
* add comparison section for Pinchflat vs Tubeless to README.md file ([#41](https://github.com/GhostMaintainers/Tubeless/issues/41)) ([73d2462](https://github.com/GhostMaintainers/Tubeless/commit/73d2462853b0050df93f0de67afcc647e803a071))
* add CONTRIBUTING.md ([a27f0d2](https://github.com/GhostMaintainers/Tubeless/commit/a27f0d24f69fdc8fa3e4a2689c704272e929c2e5))
* add details about tubeless vs pinchflat ([4fb55ed](https://github.com/GhostMaintainers/Tubeless/commit/4fb55ed2ebfe224cb0672c444938a2839a0f5408))
* add Discord link, legal use disclaimer, and responsible use guidelines ([b8e6b28](https://github.com/GhostMaintainers/Tubeless/commit/b8e6b28c036a6c5eb46a27ec409a34e875827670))
* add shorts channel ([1b77e9d](https://github.com/GhostMaintainers/Tubeless/commit/1b77e9d29cf2941dd7e6265ceec612ee4ecc9b7b))
* Add Star History section to README ([48711c2](https://github.com/GhostMaintainers/Tubeless/commit/48711c2116103a56b7143ae21ed6057f2cb3bb45))
* Add Subreddit to README ([77db710](https://github.com/GhostMaintainers/Tubeless/commit/77db7108aea0d0fe978862ce312ff3cd2da50e99))
* adopt project ([d96f211](https://github.com/GhostMaintainers/Tubeless/commit/d96f2119ae78423a8f457cc3ff78cf7c5f8d001c))
* Clarify database integrity check description ([02d0d94](https://github.com/GhostMaintainers/Tubeless/commit/02d0d947ce2e147c33b1ad986622a9bc9797c6ce))
* clarify metadata/NFO toggle labels in media profile form ([7680d06](https://github.com/GhostMaintainers/Tubeless/commit/7680d065ddd5ccb66adf49d03c3a86580110fcb6))
* clarify migration steps ([bf9defa](https://github.com/GhostMaintainers/Tubeless/commit/bf9defadc0c25e4c3c3da5d5ee93dc0f78f09b49))
* correct boot sequence responsibilities in CLAUDE.md ([241be98](https://github.com/GhostMaintainers/Tubeless/commit/241be98e3c0584f151a5849007378712b11227bc))
* fix docker compose example ([c7d00f7](https://github.com/GhostMaintainers/Tubeless/commit/c7d00f7177876b1f6d3834d1c7d6cd66659fb652))
* Fix formatting in README.md for LOG_LEVEL note ([c780241](https://github.com/GhostMaintainers/Tubeless/commit/c78024170cec5ec9125d67b2d9599ab8902f4736))
* Fix formatting issues in README.md ([3065484](https://github.com/GhostMaintainers/Tubeless/commit/3065484341484cceb61cb7a9b409e81a1e5c7778))
* Fix grammatical error in pull request template ([69fa2e4](https://github.com/GhostMaintainers/Tubeless/commit/69fa2e48fe977b653cb303dba5b2dcba1747726a))
* Fix grammatical issues in README.md ([d8eec32](https://github.com/GhostMaintainers/Tubeless/commit/d8eec32f1f7f61609681c3d2b33a931b0c6d08e0))
* Fix typos and validation in bug report template ([bfdce33](https://github.com/GhostMaintainers/Tubeless/commit/bfdce33af9e10a8710ae1188b3042dea90daa2cc))
* Improve README environment variables section ([d1606fd](https://github.com/GhostMaintainers/Tubeless/commit/d1606fd3a518b796f91fd9047e9ff43616cecdf5))
* prettify ([6a13000](https://github.com/GhostMaintainers/Tubeless/commit/6a1300073e1f6deab01b7232764ade0c6e481fce))
* reference yt-dlp faq ([80529fc](https://github.com/GhostMaintainers/Tubeless/commit/80529fc7d3b32dcc831e5918ebf7029f66932792))
* refreshed DB schema visualization ([d181df3](https://github.com/GhostMaintainers/Tubeless/commit/d181df38eab5f1f1a9a6addb85ab2c67af98629e))
* Rewrite README for a cleaner look ([cd93074](https://github.com/GhostMaintainers/Tubeless/commit/cd930748835a24fe71d5e40f662a34e6f96076f6))
* stop labeling Shorts controls as experimental ([29413d9](https://github.com/GhostMaintainers/Tubeless/commit/29413d9877490ccd133abb707f731e9d87472a52))
* update comparison in README ([a6715cb](https://github.com/GhostMaintainers/Tubeless/commit/a6715cbb2375e8c06fd0942a4f0cb73ef282138d))
* update cookie help URL in cookie_file_live.ex from Pinchflat to Tubeless' Wiki ([#32](https://github.com/GhostMaintainers/Tubeless/issues/32)) ([0707097](https://github.com/GhostMaintainers/Tubeless/commit/07070970b6c18eddc2d31f3b26d279e5587860dd))
* Update Discord server link in README to a permant invite pointing to #welcome channel ([1134289](https://github.com/GhostMaintainers/Tubeless/commit/1134289fe9b64b5d7616496a126973dc3ea803d9))
* Update Discord webhook avatar URL to GitHub logo ([31f308e](https://github.com/GhostMaintainers/Tubeless/commit/31f308eec72b495864cbcebfc5577ee70b8af13a))
* Update Discord webhook mention role id ([6da398e](https://github.com/GhostMaintainers/Tubeless/commit/6da398ee137589dce0dcbfb9537d1034a0c2c61c))
* update README ([7391a7f](https://github.com/GhostMaintainers/Tubeless/commit/7391a7fc0e343ee1c4929c3d844f125ea291716c))
* update README ([2d2d141](https://github.com/GhostMaintainers/Tubeless/commit/2d2d1416656922f5629172922d40516a8853a9bf))
* Update README ([#130](https://github.com/GhostMaintainers/Tubeless/issues/130)) ([1da0995](https://github.com/GhostMaintainers/Tubeless/commit/1da0995719c327982c67783a93b6f2bc383be40f))
* Update README for repo name and links changes ([8671c1c](https://github.com/GhostMaintainers/Tubeless/commit/8671c1cc1e8f46453ff0636f6372ad9f9a542399))
* Update README for repo name and links changes ([349a782](https://github.com/GhostMaintainers/Tubeless/commit/349a78255e238cd47de854ef98e85539599442e5))
* Update README with new features for Tubeless ([352c34d](https://github.com/GhostMaintainers/Tubeless/commit/352c34dfbaebec2e3113fc9a3a6dfcdb910331c7))
* Update README with project caution and forking information ([dbc409a](https://github.com/GhostMaintainers/Tubeless/commit/dbc409a66c37c1cdbf6fd832e618abdc0e5df07f))


### Refactors

* **assets:** drop unused Tailwind theme tokens ([b5f626c](https://github.com/GhostMaintainers/Tubeless/commit/b5f626c9f216b874a975575c117340b7413a3fb5))
* remove dead components and unused context functions ([5a864ac](https://github.com/GhostMaintainers/Tubeless/commit/5a864acc16e50f7e6ec6b8603c93cf86fe856052))
* remove unused Sources.IndexTableLive module ([ba498c9](https://github.com/GhostMaintainers/Tubeless/commit/ba498c9c227ce9ca8f3340fcbb07bc8bfb3dec2c))

## [0.0.1](https://github.com/GhostMaintainers/Tubeless/compare/v0.5.0...v0.0.1) (2026-10-06)


### ⚠ BREAKING CHANGES

* bump major version for first release

### Features

* add a Time Format setting to switch between 12h and 24h ([cd91c46](https://github.com/GhostMaintainers/Tubeless/commit/cd91c465cef8c834c9bbc35aaff8ab1bf0cc18a0))
* add database insights and safe compaction maintenance to the diagnostics page ([ee741db](https://github.com/GhostMaintainers/Tubeless/commit/ee741db6c2935299d5f5216a0ee22b6a7e872745))
* Add Dependabot configuration for GitHub Actions and Docker ([003a652](https://github.com/GhostMaintainers/Tubeless/commit/003a652fca244c64864812472f80f88901fe747b))
* add GitHub Releases to Discord workflow ([#61](https://github.com/GhostMaintainers/Tubeless/issues/61)) ([a07217e](https://github.com/GhostMaintainers/Tubeless/commit/a07217e626b558cbe0f2b327e3684389e493f85f))
* add library size display to diagnostics page ([#40](https://github.com/GhostMaintainers/Tubeless/issues/40)) ([c75a5b3](https://github.com/GhostMaintainers/Tubeless/commit/c75a5b358386229c1446625e75e44ebaf84ff2a4))
* add offline database maintenance mode for backups and repairs ([bc81886](https://github.com/GhostMaintainers/Tubeless/commit/bc81886a36207760111b338b4b57b35b580c1ec5))
* add orphaned job to agnostics ([944b1d3](https://github.com/GhostMaintainers/Tubeless/commit/944b1d3679385624ecd90ba3534afcb7c5f99b4b))
* add proxy support ([8d10c52](https://github.com/GhostMaintainers/Tubeless/commit/8d10c529e34710ad799b5c7255deee9a7b18d2ca))
* Add queue diagnostics page ([#48](https://github.com/GhostMaintainers/Tubeless/issues/48)) ([578f698](https://github.com/GhostMaintainers/Tubeless/commit/578f698712339bcb5ad3186fb39db0618286cbac))
* add queue visibility and discarded job management to diagnostics ([5343985](https://github.com/GhostMaintainers/Tubeless/commit/5343985e6614d448cd0e3b1e56e78569be008800))
* add release-please, change versioning to SemVer ([67c85f3](https://github.com/GhostMaintainers/Tubeless/commit/67c85f314d25d49d60205b600da5b791ff314332))
* add setting to ignore unavailable/members-only media ([eff8c0c](https://github.com/GhostMaintainers/Tubeless/commit/eff8c0c075b287fbee19fbbcbc7a2ad234a27b64))
* add SQLite and connection pool telemetry ([876a904](https://github.com/GhostMaintainers/Tubeless/commit/876a904f9cdef921fca82dbdc761670969f10f17))
* add system status summary to the home page ([7019007](https://github.com/GhostMaintainers/Tubeless/commit/7019007a045baa75828a60dce1a1a8690b2c073e))
* add table density setting, add profile filter and pagination controls ([dc9f635](https://github.com/GhostMaintainers/Tubeless/commit/dc9f6357c7373fdfbdf2d0441a96e93be8749419))
* Add YouTube API key testing in Settings ([#47](https://github.com/GhostMaintainers/Tubeless/issues/47)) ([90303c1](https://github.com/GhostMaintainers/Tubeless/commit/90303c15108a45f22c4fffbd31f15a99ade1f24c))
* allow SponsorBlock to both remove and mark selected categories ([ba09ff9](https://github.com/GhostMaintainers/Tubeless/commit/ba09ff933301d48ae7ed72a54cb901db8955f72a))
* bump major version for first release ([1bedbe4](https://github.com/GhostMaintainers/Tubeless/commit/1bedbe4c1bd6edab107af5e529b03f2df4ecb2b6))
* bump release ([914dbd3](https://github.com/GhostMaintainers/Tubeless/commit/914dbd3c1f0caea4e3238a64a4ad4b7df424c5c2))
* check the database for corruption from the diagnostics page ([ade672b](https://github.com/GhostMaintainers/Tubeless/commit/ade672bc6cb7778672d9005c955e901915f95ed1))
* control yt-dlp update behavior from settings ([058ba47](https://github.com/GhostMaintainers/Tubeless/commit/058ba4762a5415246cf73f4e68cddda68bc1f295))
* let media profiles ignore YouTube AI-upscaled videos ([8e2f334](https://github.com/GhostMaintainers/Tubeless/commit/8e2f334c4556353bbb12e6addd24f739181a44d8))
* let new sources default to a configurable Cookie Behavior ([42f2245](https://github.com/GhostMaintainers/Tubeless/commit/42f224503d52ea69facb11c90b20d38373dd791d))
* let sources stop indexing large channels at a cutoff date ([6b6a249](https://github.com/GhostMaintainers/Tubeless/commit/6b6a2492fa5d67d48f04f9b13e707ddc4a95ff59))
* let templates mark where channel artwork and NFOs are stored ([279bebf](https://github.com/GhostMaintainers/Tubeless/commit/279bebfdc8ce1f3fa4f6d69f772c58ea356c6ac9))
* mask YouTube API key and add cookies file management ([#53](https://github.com/GhostMaintainers/Tubeless/issues/53)) ([343a630](https://github.com/GhostMaintainers/Tubeless/commit/343a630638bdf099a786e9022e3f3f6daf712a92))
* publish sources as static podcast feeds servable without exposing Tubeless ([#55](https://github.com/GhostMaintainers/Tubeless/issues/55)) ([ee5ed6a](https://github.com/GhostMaintainers/Tubeless/commit/ee5ed6a39a2c584436cd91d0bafdab8293b988af))
* rebrand user-facing product name to Tubeless ([739d82a](https://github.com/GhostMaintainers/Tubeless/commit/739d82a3665566cec21f60daaec1b7890321d3f0))
* recover jobs stuck with retries exhausted from diagnostics ([773e6c1](https://github.com/GhostMaintainers/Tubeless/commit/773e6c198415e5d8572fb7f93c94d7050d12e458))
* refresh Queue Health on the diagnostics page without a full page reload ([85cea6b](https://github.com/GhostMaintainers/Tubeless/commit/85cea6ba0505153b7a79f857fc546561a5ed1f35))
* relocate and true up downloaded files after settings changes, without re-downloading ([ad2a66e](https://github.com/GhostMaintainers/Tubeless/commit/ad2a66ec152133866a6f413cd3903b68496129e2))
* remove Pro unlock and Donate button — every feature is available out of the box ([7daad33](https://github.com/GhostMaintainers/Tubeless/commit/7daad33ab360962308c3c6a98024b1d0bb9af3ae))
* reorganize settings into task-based cards that auto-save inline ([223a038](https://github.com/GhostMaintainers/Tubeless/commit/223a03868bf625086d38d0f9d88a3f31f3ac4856))
* report accurate status for non-downloaded media in Other tab ([8c188ac](https://github.com/GhostMaintainers/Tubeless/commit/8c188aca346a873e31ee2b8296c3e20f09615cf9))
* requeue stuck jobs from the Diagnostics page instead of cancelling them ([cbabc68](https://github.com/GhostMaintainers/Tubeless/commit/cbabc68414a12ee4c42acecec62c6e0fe08e5cba))
* require accepting a user agreement before first use ([58122eb](https://github.com/GhostMaintainers/Tubeless/commit/58122eb75c0639aec555d7d6d9379b2a783f628a))
* separate downloads that are queued from those still pending on the home page ([de1d474](https://github.com/GhostMaintainers/Tubeless/commit/de1d474cd1ebd5921a1509e383ab0d2389c25a4d))
* show live progress while a reconcile plan applies ([87a27c8](https://github.com/GhostMaintainers/Tubeless/commit/87a27c82cde86c74a06731f72ef1375acfb19c89))
* speed up reconcile by fetching online backfills in parallel ([05049fc](https://github.com/GhostMaintainers/Tubeless/commit/05049fc7a299fd6b4ad794ab7529a94ea7707b24))
* surface auto-skipped unavailable media as a distinct status ([e88d403](https://github.com/GhostMaintainers/Tubeless/commit/e88d403c4d3b655ee08b5785298313e3fb6f3df8))
* **ui:** redesign the source detail page ([fb74813](https://github.com/GhostMaintainers/Tubeless/commit/fb74813049ca2acd26c17343dbdf022533107f20))
* **ui:** rework the media profiles list and detail pages ([98b2856](https://github.com/GhostMaintainers/Tubeless/commit/98b285692123cea4bb94eaa1783e171e81091bb8))


### Bug Fixes

* add link in Cookie Behaviour help to the YouTube Cookies wiki page ([2c1f9cf](https://github.com/GhostMaintainers/Tubeless/commit/2c1f9cf97bd6103cbba2095d34dc9cf6a2acb7fc))
* assigng correct tags to dev builds ([36709df](https://github.com/GhostMaintainers/Tubeless/commit/36709df589050e2f2787d505c43f551872ca6c9b))
* auto-refresh Media History on job state changes ([98d654f](https://github.com/GhostMaintainers/Tubeless/commit/98d654fb32736da9948bb1d11ccdf94c43aed537))
* avoid length/1 check and reformat mix.exs deps ([4d3986a](https://github.com/GhostMaintainers/Tubeless/commit/4d3986acfee4a5762f2357518b2db6f1008b1e87))
* Change CI base image to latest version ([34642de](https://github.com/GhostMaintainers/Tubeless/commit/34642dea3564d02886541ab498231321b7b5d963))
* **ci:** correct casing for ghcr ([e08570b](https://github.com/GhostMaintainers/Tubeless/commit/e08570bb7d50fa9df6e372459d0cb58f64f1b7a5))
* **ci:** correct job deps in release ([a03f71a](https://github.com/GhostMaintainers/Tubeless/commit/a03f71acb8172b6944fb4ef65d81b5eb414eebd9))
* **ci:** ignore prettier in changelog ([de54801](https://github.com/GhostMaintainers/Tubeless/commit/de548018f7d17e1c2db6d7e8d466ea4de24e9f83))
* **ci:** move discord notification to release-please workflow ([fa8ddfd](https://github.com/GhostMaintainers/Tubeless/commit/fa8ddfdc890abe28d249f1c91e138a5463591208))
* **ci:** remove CalVer, build version needs to be semver compliant ([55dece8](https://github.com/GhostMaintainers/Tubeless/commit/55dece8e63f77520e3a55d1a587415d7661b2b3d))
* clarify main page storage usage ([b0cdcad](https://github.com/GhostMaintainers/Tubeless/commit/b0cdcada979182a46695c6f852d05a50bcd6075b))
* configure Oban PG notifier and incomplete unique states for 2.23 ([0fb0183](https://github.com/GhostMaintainers/Tubeless/commit/0fb018302e699e106c5c8d0e552e3c69b08509b6))
* correct pending count for sources with no downloaded media ([8675262](https://github.com/GhostMaintainers/Tubeless/commit/8675262eebc7dad00f229d850fad9f50d3b09ef1))
* correct static Size values in sources table on re-sort ([a876bcd](https://github.com/GhostMaintainers/Tubeless/commit/a876bcd817847a87e44bbbc9f50b366202186b0a)), closes [#112](https://github.com/GhostMaintainers/Tubeless/issues/112)
* **deps:** add sctp1 module for otp 29 ([7a520d5](https://github.com/GhostMaintainers/Tubeless/commit/7a520d5088c3095669f0b77ad78ebbe4fc18044f))
* Disable Docker Hub login in release workflow ([48f1af9](https://github.com/GhostMaintainers/Tubeless/commit/48f1af9e8067dbc27df68cd370d616e6a61c9d57))
* Disable Docker Hub login in release workflow ([3a92d31](https://github.com/GhostMaintainers/Tubeless/commit/3a92d31b3286731be0b8b89b82ec8cab754536a0))
* fetch sqlean extension when a stale version marker has no binaries ([e9fe03c](https://github.com/GhostMaintainers/Tubeless/commit/e9fe03c4125b391244d641c45fab72f703d976be))
* further db access optimizations ([0a9990c](https://github.com/GhostMaintainers/Tubeless/commit/0a9990c9485cb91b87e31618cf9680f954292573))
* handle suffix Range requests and missing files when streaming media ([e4c5a32](https://github.com/GhostMaintainers/Tubeless/commit/e4c5a3293f7c6cf4fc5e3d13324e8cc27f0606d5))
* handle unparseable yt-dlp source metadata responses gracefully ([813c8ad](https://github.com/GhostMaintainers/Tubeless/commit/813c8adcda43a6885dde19b4e2496526810417f8))
* increase db conn pool and cache to help with reconcile responsivity ([cd55489](https://github.com/GhostMaintainers/Tubeless/commit/cd55489049625681940e15119886c7f2d8257785))
* index channel tabs separately so new shorts are found on repeat indexes ([13a160a](https://github.com/GhostMaintainers/Tubeless/commit/13a160a0a8b84d2c0f7b7214e73ba305acb58365)), closes [#59](https://github.com/GhostMaintainers/Tubeless/issues/59)
* keep indexing reschedule from deduping against its own executing job ([115f8db](https://github.com/GhostMaintainers/Tubeless/commit/115f8db8ef6e6b1a7edf72844536a8ade2f9e0a1))
* label binary byte sizes with IEC units eg. KiB/MiB/GiB ([47fde1f](https://github.com/GhostMaintainers/Tubeless/commit/47fde1f81a992d4b0c8d7634a4c11ba6075330a1))
* label File Reconciliation jobs in the Active Tasks list ([552de57](https://github.com/GhostMaintainers/Tubeless/commit/552de5750acf43d29c219dd21b4124fe76e224fe))
* linter ([7b29408](https://github.com/GhostMaintainers/Tubeless/commit/7b29408165bfca80d6c0c344dd275a1c880fd799))
* match the Queue Health refresh button to the other action buttons ([668999e](https://github.com/GhostMaintainers/Tubeless/commit/668999eb346d3ab1650128a915e3a306b69a2366))
* name episode thumbnails to match the media file so Plex displays them ([5d27ea6](https://github.com/GhostMaintainers/Tubeless/commit/5d27ea6c03ca8a83ecb8a37190bfb3a90b25c420))
* pin Deno and Apprise in selfhosted runner to match ci-base ([b9b372c](https://github.com/GhostMaintainers/Tubeless/commit/b9b372cbabf956fd4eabecf82de6c843cda7cae4))
* prettier'd new code ([ba41fb2](https://github.com/GhostMaintainers/Tubeless/commit/ba41fb22cd5f954d9033efcfec4c94838be8c462))
* re-download existing media by forcing the download job ([f47a6e0](https://github.com/GhostMaintainers/Tubeless/commit/f47a6e03e2780cc67b6646560410085adb90e453))
* re-index a source when its indexing cutoff reaches further into the past ([aa2fc43](https://github.com/GhostMaintainers/Tubeless/commit/aa2fc4329eda2d6e4f60fbf8afd20bb5a7064971))
* recover a reconcile apply interrupted by a restart instead of deadlocking ([221643f](https://github.com/GhostMaintainers/Tubeless/commit/221643f82eb767b78e4ceb3990e1a8e902f6c818))
* reflect new github org in webui ([2b8faeb](https://github.com/GhostMaintainers/Tubeless/commit/2b8faeb29f342cc2d4382f0caee0add8a0046dbd))
* Remove Docker Hub login from release workflow ([20acd9a](https://github.com/GhostMaintainers/Tubeless/commit/20acd9ab9a7404f78bcfac33c81c8d12248de238))
* render NFO aired date as plain date for Jellyfin ([#60](https://github.com/GhostMaintainers/Tubeless/issues/60)) ([0282c19](https://github.com/GhostMaintainers/Tubeless/commit/0282c19789d3154bf4eff92a74c8d7c90186ba5f)), closes [#57](https://github.com/GhostMaintainers/Tubeless/issues/57)
* reschedule missing source indexing jobs on boot ([beb6a16](https://github.com/GhostMaintainers/Tubeless/commit/beb6a16ea25a94e9c68d9560bba035debaa5e113))
* resolve Elixir 1.20 compiler warnings ([43ea35d](https://github.com/GhostMaintainers/Tubeless/commit/43ea35dcf9ee8ef8b73ddd861b16326230af4320))
* restore the media search box after a LiveView reconnect ([c447d21](https://github.com/GhostMaintainers/Tubeless/commit/c447d21d413fd64875c91a47228ea5b9559fdce6))
* route ecto.migrate ERD guard through sh for Elixir 1.20 ([04cf3f3](https://github.com/GhostMaintainers/Tubeless/commit/04cf3f3ccfac71f5c8f17472b8eba20ca54d8439))
* serialize quiet-window workers to prevent deadlock situation ([4e7ac31](https://github.com/GhostMaintainers/Tubeless/commit/4e7ac3140548e8f92a63dc7ec36ba03898b394b4))
* serve apple-touch-icon to avoid 404 probes from iOS ([451123b](https://github.com/GhostMaintainers/Tubeless/commit/451123b108bf2dfa14c6b87577a261f4c739d0f3))
* show log timestamps in the configured timezone ([af8e3a7](https://github.com/GhostMaintainers/Tubeless/commit/af8e3a74ef02f29b8dcc9dd1fa931ba1f70419bf))
* show more useful precision on disk space and file sizes ([85e6acb](https://github.com/GhostMaintainers/Tubeless/commit/85e6acb7f9be515b729ce6452f18f74680faeb82))
* show time using the configured timezone ([fba9c3c](https://github.com/GhostMaintainers/Tubeless/commit/fba9c3c78cc1e353ac4a49077fa9cb96711ebcf4))
* skip download archive when the archive file cannot be written ([5aac447](https://github.com/GhostMaintainers/Tubeless/commit/5aac4477f36d291b27045434eedf6aaf8f08e246))
* stop bold+italic text from loading a broken Satoshi font glyph ([49f7fd4](https://github.com/GhostMaintainers/Tubeless/commit/49f7fd40843c49dd37bdac27d67d72c912a34345))
* stop counting actively-downloading videos as Queued on the dashboard ([172dc5f](https://github.com/GhostMaintainers/Tubeless/commit/172dc5f37ac6b9b611b82f43713331a61b333dfe))
* stop crashing when rendering 404 and 500 error pages ([#154](https://github.com/GhostMaintainers/Tubeless/issues/154)) ([7b0bd7f](https://github.com/GhostMaintainers/Tubeless/commit/7b0bd7f37668a6428172a471c843d6a582cebb36))
* stop disabled form fields from flashing white on the dark theme ([c0c3d0f](https://github.com/GhostMaintainers/Tubeless/commit/c0c3d0f074ad55d02121bd63a9168e9ad55863fa))
* stop logging YouTube API keys ([515eabf](https://github.com/GhostMaintainers/Tubeless/commit/515eabf1a5a59abffe32c2d18ffc98c47ab1e222))
* stop losing in-flight source enable toggles on LiveView reconnect ([6d9d184](https://github.com/GhostMaintainers/Tubeless/commit/6d9d184d9d973ffa4fbda4d16d8e4d268018cff2))
* stop the diagnostics page crashing when job queues aren't running ([779080c](https://github.com/GhostMaintainers/Tubeless/commit/779080c20b1ee0809bbdd770bc3f82fc7002633c))
* test all YouTube API keys and report which fail ([347f0be](https://github.com/GhostMaintainers/Tubeless/commit/347f0be760933ac546766f24bed689f475d69d6f))
* throttle job state broadcasts to reduce dashboard query load ([21555ae](https://github.com/GhostMaintainers/Tubeless/commit/21555aef88e33be75b0af3e7ec374a9483a5f2c9))
* **tooling:** abort container startup when database migration fails ([3fc0dd9](https://github.com/GhostMaintainers/Tubeless/commit/3fc0dd959fce68f7ac0d688639d2a6f00f1fc203))
* **ui:** don't underline trailing white space past link text ([692890d](https://github.com/GhostMaintainers/Tubeless/commit/692890d97d373ef0321ac7bd514be68d7b096f75))
* unlock-pro modal button stuck disabled ([#125](https://github.com/GhostMaintainers/Tubeless/issues/125)) ([5c26116](https://github.com/GhostMaintainers/Tubeless/commit/5c261160f79ea9fccaea8cafd3096d1954ddd1c0))
* Update base image in dev Dockerfile ([8393437](https://github.com/GhostMaintainers/Tubeless/commit/8393437d16cef5d56fcd17b6c78071716fb395c3))
* Update CI base image reference in Dockerfile ([29bcdff](https://github.com/GhostMaintainers/Tubeless/commit/29bcdff2ce3d60e17feeda99ceaa5ce7f65f0ba2))
* Update CI_BASE_IMAGE and comment out Discord job ([bbf1a0c](https://github.com/GhostMaintainers/Tubeless/commit/bbf1a0cf758a92e6131d81be7b3a32559d49180e))
* Update FFMPEG_RELEASE and FFMPEG_BUILD arguments ([07254e2](https://github.com/GhostMaintainers/Tubeless/commit/07254e24a8824105e27844c6213f42962634f70b))
* Update FFMPEG_RELEASE and FFMPEG_BUILD arguments ([27bf8f7](https://github.com/GhostMaintainers/Tubeless/commit/27bf8f7d3694614613035ab74c972b6df5cd3e8d))
* update formatting for phoenix ([cd6cc8b](https://github.com/GhostMaintainers/Tubeless/commit/cd6cc8b542ac405074ed773dc34314bdc3d89300))
* Update image cleanup workflow account name ([471351e](https://github.com/GhostMaintainers/Tubeless/commit/471351eabaeec0c39e7faafb530894ce9cbd1187))
* update image name ([122503d](https://github.com/GhostMaintainers/Tubeless/commit/122503de2f03d1c57eb7d117b3ae88928f028538))
* Update image repository in CI workflow ([dc0fb25](https://github.com/GhostMaintainers/Tubeless/commit/dc0fb25e1cdddba8bf9a09ff80d63e119170f925))
* warn on malformed output-path templates in the UI ([c4bb94a](https://github.com/GhostMaintainers/Tubeless/commit/c4bb94a0f7af07023d295e8bd9f7a990ab9aa376))


### Reverts

* Move Active Tasks to tab in Media History section ([#836](https://github.com/GhostMaintainers/Tubeless/issues/836)) ([59849e3](https://github.com/GhostMaintainers/Tubeless/commit/59849e342817d1961feb147c6c0b0aa325a993e3))


### Chores

* add fast Docker test runner for local iteration ([b976cf2](https://github.com/GhostMaintainers/Tubeless/commit/b976cf2aad014fc6fb43ee9a97a15b57daa18b12))
* add local CI lint/test script ([6b5bc79](https://github.com/GhostMaintainers/Tubeless/commit/6b5bc7926e3037a70417714548db9f05a13e5463))
* add sqlite to final image ([c1cbdb2](https://github.com/GhostMaintainers/Tubeless/commit/c1cbdb2c7ad112e7fd1f44634ff7246c8262c89e))
* add tooling script ([460fbd1](https://github.com/GhostMaintainers/Tubeless/commit/460fbd1c6ce7783bbae8932ed64ee24ea4325a2e))
* bump sqleton ([6ecadf7](https://github.com/GhostMaintainers/Tubeless/commit/6ecadf74edc09fdd580f5d36110365313588070f))
* **ci:** break out ci-build into phases ([2060ab9](https://github.com/GhostMaintainers/Tubeless/commit/2060ab956abcc97cc4b9d11c517ca6a81f45ab9f))
* **ci:** bump ci-base image to sha-93af908 ([6d29a27](https://github.com/GhostMaintainers/Tubeless/commit/6d29a276522c034fdf6f824a14e096431488ff35))
* **ci:** bump ci-base image to sha-ba3e559 ([a13ac24](https://github.com/GhostMaintainers/Tubeless/commit/a13ac24d9a81d804234bd024b4a789c793bb0492))
* **ci:** bump pinned ci-base image to sha-1629079 ([65789d1](https://github.com/GhostMaintainers/Tubeless/commit/65789d1b04a80bb6d80ac3fabf87bd77f60783e1))
* **ci:** fetch sqlean extensions at build time instead of vendoring ([053064b](https://github.com/GhostMaintainers/Tubeless/commit/053064b8d6abe262a96131715240020da92f2600))
* **ci:** improve local docker script ([d339fff](https://github.com/GhostMaintainers/Tubeless/commit/d339fff4e9e8fd626c1cdb6ac48a2eb31ed47bb0))
* **ci:** lint and and local run docker ([#62](https://github.com/GhostMaintainers/Tubeless/issues/62)) ([622f5e0](https://github.com/GhostMaintainers/Tubeless/commit/622f5e03c7c5ad7e8a50d1c24be7a9a000b3c305))
* **ci:** release config updates ([4bf8cf2](https://github.com/GhostMaintainers/Tubeless/commit/4bf8cf26ea3620eb1330b30cf6afba8ba74a8dad))
* **ci:** run lint/test jobs natively in ci-base container ([e5430f2](https://github.com/GhostMaintainers/Tubeless/commit/e5430f2a96cf58bc13f7ea8d904b8ffe86ab963b))
* **ci:** switch from Github issue templates to the new issue forms ([#34](https://github.com/GhostMaintainers/Tubeless/issues/34)) ([61c54f3](https://github.com/GhostMaintainers/Tubeless/commit/61c54f35a8b1ecf8a34b5eb83b053ddc4b229d13))
* **ci:** track hexpm/elixir base image versions with Renovate ([ba3e559](https://github.com/GhostMaintainers/Tubeless/commit/ba3e559ec54cc2e925312e0cec3ee07e18bf88a0))
* **ci:** use ci-build image sha-2060ab9 ([129609d](https://github.com/GhostMaintainers/Tubeless/commit/129609dd2cb5cccbc17f202685451a0133569f49))
* **ci:** use main as default branch ([ea68a7c](https://github.com/GhostMaintainers/Tubeless/commit/ea68a7c0daa1c9bb0e7ebead34a9c1e9112997df))
* **ci:** use new ci image ([1dc9b2b](https://github.com/GhostMaintainers/Tubeless/commit/1dc9b2b467a91cb564ae1f6985f187be6ce08bbe))
* clarify migration paths ([7ac7551](https://github.com/GhostMaintainers/Tubeless/commit/7ac755108ae88d3c7407068dd13aaf07c6284bb3))
* **deps:** alpinejs 3.15.12 ([a12f722](https://github.com/GhostMaintainers/Tubeless/commit/a12f72252945aa5fcb50f7f2af77c470aaacd64b))
* **deps:** bump docker/build-push-action from 7.3.0 to 7.4.0 ([9915aea](https://github.com/GhostMaintainers/Tubeless/commit/9915aea95b593d55a4508b0978eb4473e4683a29))
* **deps:** bump docker/build-push-action from 7.3.0 to 7.4.0 ([9b5fc94](https://github.com/GhostMaintainers/Tubeless/commit/9b5fc94cccb5b62bef1580ff4a93337a5064165b))
* **deps:** bump docker/login-action from 4.5.1 to 4.6.0 ([19faeb4](https://github.com/GhostMaintainers/Tubeless/commit/19faeb4e6a5928950a8c61899c28b8c374e912e4))
* **deps:** bump docker/login-action from 4.5.1 to 4.6.0 ([c8b620b](https://github.com/GhostMaintainers/Tubeless/commit/c8b620bb6ccd341e35d6bf3bf88465c757a2ee54))
* **deps:** bump docker/setup-buildx-action from 4.2.0 to 4.4.1 ([07dddbf](https://github.com/GhostMaintainers/Tubeless/commit/07dddbf1e610a06a8080b53570c419e751d5e5ff))
* **deps:** bump docker/setup-buildx-action from 4.2.0 to 4.4.1 ([7dbd6e9](https://github.com/GhostMaintainers/Tubeless/commit/7dbd6e9004f5769b583c6bf70e09ebaa822500b6))
* **deps:** bump docker/setup-qemu-action from 4.2.0 to 4.4.0 ([8077a44](https://github.com/GhostMaintainers/Tubeless/commit/8077a4487e04093ff62dccef056106282e48b245))
* **deps:** bump docker/setup-qemu-action from 4.2.0 to 4.4.0 ([56c0e98](https://github.com/GhostMaintainers/Tubeless/commit/56c0e98ea6b29fa5d02425800fd6ef4fb4a13e68))
* **deps:** bump Elixir 1.20.2, OTP 28.5.0.2, Debian trixie-20260623 in ci-base ([95b825a](https://github.com/GhostMaintainers/Tubeless/commit/95b825afc7bf93dc96d469f30252d6db0157bd48))
* **deps:** bump elixir deps ([e31b3ab](https://github.com/GhostMaintainers/Tubeless/commit/e31b3abb802510ceaafdaab67a1eef6f87977362))
* **deps:** bump Erlang/OTP to 28.5.0.3 ([cf681a2](https://github.com/GhostMaintainers/Tubeless/commit/cf681a2962a6247aab5ceafd3e003d7df2db697c))
* **deps:** bump esbuild and tailwind pinned binary versions ([300478d](https://github.com/GhostMaintainers/Tubeless/commit/300478d3cb2fec585f702268d2269a42a03770e3))
* **deps:** bump ffmpeg build ([de3f25a](https://github.com/GhostMaintainers/Tubeless/commit/de3f25a040f52bccabe1be54436a3ae28c02c822))
* **deps:** bump Node 20 -&gt; 24 in ci-base, add renovate tracking, sync CODEBASE versions ([f22adc4](https://github.com/GhostMaintainers/Tubeless/commit/f22adc49c18a5734476dee61165b3496368e4501))
* **deps:** bump otp to 29.0.4 ([c623288](https://github.com/GhostMaintainers/Tubeless/commit/c623288d3edae4fa0090fe60fe460fbbb41cba6d))
* **deps:** faker to work with elixir 1.20; update misc deps ([edbff35](https://github.com/GhostMaintainers/Tubeless/commit/edbff3587d58f72023e4685e114f1700d7fbbe50))
* **deps:** pin dependencies ([caa7379](https://github.com/GhostMaintainers/Tubeless/commit/caa7379dc73b34f6cb8759971ae5150711bce443))
* **deps:** pin dependencies ([e002b75](https://github.com/GhostMaintainers/Tubeless/commit/e002b7547bf9f374069a7983d79b0d68d541aaa8))
* **deps:** pin elixir in renovate ([cb55b03](https://github.com/GhostMaintainers/Tubeless/commit/cb55b0300e14b513e86374e199f9787415e21731))
* **deps:** replace floki with lazy_html ([13d7924](https://github.com/GhostMaintainers/Tubeless/commit/13d79242daf9b7a16a4358ccf82369d4a38782a7))
* **deps:** tighten ecto_sqlite3 and prom_ex constraints and bump locked deps ([768b120](https://github.com/GhostMaintainers/Tubeless/commit/768b12051b0578d92e06d36e464af0779e60e842))
* **deps:** update actions/cache action to v6 ([271b43b](https://github.com/GhostMaintainers/Tubeless/commit/271b43b1de7de7926c7c78636ca590e802d00d80))
* **deps:** update actions/checkout action to v7 ([bb1a5e3](https://github.com/GhostMaintainers/Tubeless/commit/bb1a5e35e9eaa4684bfcd53630e3c5a15626550d))
* **deps:** update Debian snapshot to trixie-20260713-slim ([f3a5e12](https://github.com/GhostMaintainers/Tubeless/commit/f3a5e12f60d200cc1c03353c879e3658dacf3ead))
* **deps:** update dependency alpinejs to v3.15.12 ([a753ff8](https://github.com/GhostMaintainers/Tubeless/commit/a753ff8f4cd2535ce0a216b58c9e2f248b007801))
* **deps:** update dependency apprise to v1.12.0 ([945105b](https://github.com/GhostMaintainers/Tubeless/commit/945105be5544cfd911b161d560cebac010b91b46))
* **deps:** update dependency exqlite to 0.38.0 ([6e2dc17](https://github.com/GhostMaintainers/Tubeless/commit/6e2dc17dc7d0b7dcfbcff8d15fce4228713180d6))
* **deps:** update dependency phoenix to ~&gt; 1.8.0 ([9c0f74d](https://github.com/GhostMaintainers/Tubeless/commit/9c0f74dcdcc53059a86a4639eff7ef6aee440bd9))
* **deps:** update dependency phoenix_live_view to v1.2.4 ([a239149](https://github.com/GhostMaintainers/Tubeless/commit/a2391491ece970bb80fb15ecc87d14c75624ac41))
* **deps:** update dependency phoenix_live_view to v1.2.5 ([b2d638e](https://github.com/GhostMaintainers/Tubeless/commit/b2d638e6016be4fbd97211354e18e5b2213214f8))
* **deps:** update dependency prettier to v3.8.4 ([cd0456d](https://github.com/GhostMaintainers/Tubeless/commit/cd0456de4ae71f4385c62d342086c043eabef421))
* **deps:** update dependency prettier to v3.8.5 ([9389279](https://github.com/GhostMaintainers/Tubeless/commit/93892793013fe284804494867fe81a38fa99c3ea))
* **deps:** update dependency prettier to v3.9.0 ([2e9301a](https://github.com/GhostMaintainers/Tubeless/commit/2e9301a1bd3f4430a1ad53cea9aa74f318aae252))
* **deps:** update dependency prettier to v3.9.1 ([a66decb](https://github.com/GhostMaintainers/Tubeless/commit/a66decb323fe6c1480a18f0f1fe20bcaf96dbaa8))
* **deps:** update dependency prettier to v3.9.3 ([8130c84](https://github.com/GhostMaintainers/Tubeless/commit/8130c84d5372f3f56210bdb8c4480447041864f5))
* **deps:** update dependency prettier to v3.9.4 ([d2c4d45](https://github.com/GhostMaintainers/Tubeless/commit/d2c4d45215b4874fdbdd6321a9f3317e6aaf4ade))
* **deps:** update dependency prettier to v3.9.5 ([a6359e0](https://github.com/GhostMaintainers/Tubeless/commit/a6359e07f4d33fc5be75861e39d4546eee4744b2))
* **deps:** update dependency prettier to v3.9.6 ([a1980d1](https://github.com/GhostMaintainers/Tubeless/commit/a1980d10a93ba48584b7e8a73675ee1f19dbc1af))
* **deps:** update dependency sobelow to ~&gt; 0.14 ([1bcaeeb](https://github.com/GhostMaintainers/Tubeless/commit/1bcaeeb80d0086661726d2784a06ec770fd69326))
* **deps:** update dependency sqleton to v2.3.0 ([74ef149](https://github.com/GhostMaintainers/Tubeless/commit/74ef149c7f7ac76cbed707188c84379a39bff742))
* **deps:** update dependency sqleton to v4 ([3143550](https://github.com/GhostMaintainers/Tubeless/commit/31435505b4cd892f23a7bbeba4ad646f6a82b0bc))
* **deps:** update dependency tailwind to ~&gt; 0.5.0 ([9e38148](https://github.com/GhostMaintainers/Tubeless/commit/9e38148d894629d3deb52e95935dcc69564e6d57))
* **deps:** update docker/login-action digest to abd2ef4 ([8461f41](https://github.com/GhostMaintainers/Tubeless/commit/8461f4102c891a8bb0640052f7bb7d8e0370e088))
* **deps:** update github actions ([8003703](https://github.com/GhostMaintainers/Tubeless/commit/800370390b385ba5f65b3b5b060d7c49429d5cf4))
* **deps:** update github actions ([c487511](https://github.com/GhostMaintainers/Tubeless/commit/c487511b27d2efc3927edec026f752f049143f7d))
* **deps:** update github actions ([fa27ffe](https://github.com/GhostMaintainers/Tubeless/commit/fa27ffefd790a351133be05cc413fe656cf07bab))
* **deps:** update github actions to v7 ([#52](https://github.com/GhostMaintainers/Tubeless/issues/52)) ([7429586](https://github.com/GhostMaintainers/Tubeless/commit/742958666e59b82e8b17710c9e3dfa6de36da3f3))
* **deps:** update OTP to 29.0.3 in ci-base image ([1629079](https://github.com/GhostMaintainers/Tubeless/commit/1629079b7ffdce615e1e7be8e74183ae1d35fe02))
* **deps:** update phoenix_live_view ([e0651b6](https://github.com/GhostMaintainers/Tubeless/commit/e0651b68765431dcb5bdfde5ec6463b41d545e24))
* **deps:** update renovate constraints ([7051c58](https://github.com/GhostMaintainers/Tubeless/commit/7051c58c92809767826639f5ad9bcf6f2ac7ea19))
* **deps:** update timex digest to 3.7.13 ([e4f9983](https://github.com/GhostMaintainers/Tubeless/commit/e4f99831d2540f7cf98e05d68daea740b1f1c1b1))
* **deps:** update timex digest to 5ad1b82 ([83710dc](https://github.com/GhostMaintainers/Tubeless/commit/83710dcb75b88ede0e97451883424bc6d8920665))
* **deps:** update to 2026-07-01-16-32 ffmpeg build ([93af908](https://github.com/GhostMaintainers/Tubeless/commit/93af908ee245665899331600b464d6f88e462f28))
* **deps:** use new elixir/otp ([f5e830b](https://github.com/GhostMaintainers/Tubeless/commit/f5e830b97a7e553c3660e14f93d8b76316b98b1a))
* **deps:** use published faker instead of private git fork ([792da4a](https://github.com/GhostMaintainers/Tubeless/commit/792da4abc49c7e55b58081cb10fedbf4f4e57a03))
* **doc:** reformat CHANGELOG ([9170c6c](https://github.com/GhostMaintainers/Tubeless/commit/9170c6c2fb0b00b39182b630493f8683aa7f936b))
* drop unused settings_backup table ([1bc6c28](https://github.com/GhostMaintainers/Tubeless/commit/1bc6c280b4107a5ee11977e8e44cf70be179d9a3))
* ignore runtime wiring and test support in coverage reporting ([a8f6d76](https://github.com/GhostMaintainers/Tubeless/commit/a8f6d76d4da44a3c44ada129957daaa6090cc78b))
* **master:** release 1.0.0 ([5776d49](https://github.com/GhostMaintainers/Tubeless/commit/5776d49c7d4bd343ab96eb563e0ad03579c5ebca))
* **master:** release 1.1.0 ([#26](https://github.com/GhostMaintainers/Tubeless/issues/26)) ([9d4c7e6](https://github.com/GhostMaintainers/Tubeless/commit/9d4c7e64a73e6b6486dd408bd849d0b2bee900c6))
* **master:** release 1.2.0 ([3f7ad33](https://github.com/GhostMaintainers/Tubeless/commit/3f7ad33dacb2cf61b508ad940a9dd9a8f3da0484))
* move to debain trixie ([8103c96](https://github.com/GhostMaintainers/Tubeless/commit/8103c9676f48f4605e7ed3bcd80104dc512f1fa8))
* prettify satoshi.css to pass lint ([067b4c1](https://github.com/GhostMaintainers/Tubeless/commit/067b4c1bc806b6415d4ea11e982bbbe464fcbd18))
* schedule renovate biweekly, remove PR rate limits, enable dependency dashboard ([efe8668](https://github.com/GhostMaintainers/Tubeless/commit/efe8668216c4070ad443935958157f8466f9f6b5))
* set app version to 1.0.0 (2026.6.14) [skip ci] ([ac12ace](https://github.com/GhostMaintainers/Tubeless/commit/ac12ace16959ba823e978239999f726b0508ae9e))
* track ci-base pip requirements with Renovate ([8f1194d](https://github.com/GhostMaintainers/Tubeless/commit/8f1194dc50d0484f9bd6fe944e86ed77d039064c))
* tune release-please changelog sections ([5e1fa12](https://github.com/GhostMaintainers/Tubeless/commit/5e1fa12cb63113ac3a283d0b8f4b07ac483e9b78))
* update images ([77ab2e5](https://github.com/GhostMaintainers/Tubeless/commit/77ab2e56942eaa6233110d0c21dbd0ab66ecf717))
* upgrade Tailwind CSS to v4.3.3 ([97ccb64](https://github.com/GhostMaintainers/Tubeless/commit/97ccb64f29147bfde4a8f911c5869734dcac87e6))


### Documentation

* Add `error` to LOG_LEVEL options in README.md ([1ab61dd](https://github.com/GhostMaintainers/Tubeless/commit/1ab61dd6a3dd1f47bf642c9f4a66825f18dd53e7))
* Add audio & video codec preference to features list ([6c9b083](https://github.com/GhostMaintainers/Tubeless/commit/6c9b083a191b9771ff7ad81374ba4c5e8645854d))
* add Caddy config example ([2a476a0](https://github.com/GhostMaintainers/Tubeless/commit/2a476a0e6bf723a54e922e21c41f79e817e33302))
* add CI instructions ([77119c5](https://github.com/GhostMaintainers/Tubeless/commit/77119c5929389a390785fbe052901d16b93b4e16))
* add comparison section for Pinchflat vs Tubeless to README.md file ([#41](https://github.com/GhostMaintainers/Tubeless/issues/41)) ([73d2462](https://github.com/GhostMaintainers/Tubeless/commit/73d2462853b0050df93f0de67afcc647e803a071))
* add CONTRIBUTING.md ([a27f0d2](https://github.com/GhostMaintainers/Tubeless/commit/a27f0d24f69fdc8fa3e4a2689c704272e929c2e5))
* add details about tubeless vs pinchflat ([4fb55ed](https://github.com/GhostMaintainers/Tubeless/commit/4fb55ed2ebfe224cb0672c444938a2839a0f5408))
* add Discord link, legal use disclaimer, and responsible use guidelines ([b8e6b28](https://github.com/GhostMaintainers/Tubeless/commit/b8e6b28c036a6c5eb46a27ec409a34e875827670))
* add shorts channel ([1b77e9d](https://github.com/GhostMaintainers/Tubeless/commit/1b77e9d29cf2941dd7e6265ceec612ee4ecc9b7b))
* Add Star History section to README ([48711c2](https://github.com/GhostMaintainers/Tubeless/commit/48711c2116103a56b7143ae21ed6057f2cb3bb45))
* Add Subreddit to README ([77db710](https://github.com/GhostMaintainers/Tubeless/commit/77db7108aea0d0fe978862ce312ff3cd2da50e99))
* adopt project ([d96f211](https://github.com/GhostMaintainers/Tubeless/commit/d96f2119ae78423a8f457cc3ff78cf7c5f8d001c))
* Clarify database integrity check description ([02d0d94](https://github.com/GhostMaintainers/Tubeless/commit/02d0d947ce2e147c33b1ad986622a9bc9797c6ce))
* clarify metadata/NFO toggle labels in media profile form ([7680d06](https://github.com/GhostMaintainers/Tubeless/commit/7680d065ddd5ccb66adf49d03c3a86580110fcb6))
* clarify migration steps ([bf9defa](https://github.com/GhostMaintainers/Tubeless/commit/bf9defadc0c25e4c3c3da5d5ee93dc0f78f09b49))
* correct boot sequence responsibilities in CLAUDE.md ([241be98](https://github.com/GhostMaintainers/Tubeless/commit/241be98e3c0584f151a5849007378712b11227bc))
* fix docker compose example ([c7d00f7](https://github.com/GhostMaintainers/Tubeless/commit/c7d00f7177876b1f6d3834d1c7d6cd66659fb652))
* Fix formatting in README.md for LOG_LEVEL note ([c780241](https://github.com/GhostMaintainers/Tubeless/commit/c78024170cec5ec9125d67b2d9599ab8902f4736))
* Fix formatting issues in README.md ([3065484](https://github.com/GhostMaintainers/Tubeless/commit/3065484341484cceb61cb7a9b409e81a1e5c7778))
* Fix grammatical error in pull request template ([69fa2e4](https://github.com/GhostMaintainers/Tubeless/commit/69fa2e48fe977b653cb303dba5b2dcba1747726a))
* Fix grammatical issues in README.md ([d8eec32](https://github.com/GhostMaintainers/Tubeless/commit/d8eec32f1f7f61609681c3d2b33a931b0c6d08e0))
* Fix typos and validation in bug report template ([bfdce33](https://github.com/GhostMaintainers/Tubeless/commit/bfdce33af9e10a8710ae1188b3042dea90daa2cc))
* Improve README environment variables section ([d1606fd](https://github.com/GhostMaintainers/Tubeless/commit/d1606fd3a518b796f91fd9047e9ff43616cecdf5))
* prettify ([6a13000](https://github.com/GhostMaintainers/Tubeless/commit/6a1300073e1f6deab01b7232764ade0c6e481fce))
* reference yt-dlp faq ([80529fc](https://github.com/GhostMaintainers/Tubeless/commit/80529fc7d3b32dcc831e5918ebf7029f66932792))
* refreshed DB schema visualization ([d181df3](https://github.com/GhostMaintainers/Tubeless/commit/d181df38eab5f1f1a9a6addb85ab2c67af98629e))
* Rewrite README for a cleaner look ([cd93074](https://github.com/GhostMaintainers/Tubeless/commit/cd930748835a24fe71d5e40f662a34e6f96076f6))
* stop labeling Shorts controls as experimental ([29413d9](https://github.com/GhostMaintainers/Tubeless/commit/29413d9877490ccd133abb707f731e9d87472a52))
* update comparison in README ([a6715cb](https://github.com/GhostMaintainers/Tubeless/commit/a6715cbb2375e8c06fd0942a4f0cb73ef282138d))
* update cookie help URL in cookie_file_live.ex from Pinchflat to Tubeless' Wiki ([#32](https://github.com/GhostMaintainers/Tubeless/issues/32)) ([0707097](https://github.com/GhostMaintainers/Tubeless/commit/07070970b6c18eddc2d31f3b26d279e5587860dd))
* Update Discord server link in README to a permant invite pointing to #welcome channel ([1134289](https://github.com/GhostMaintainers/Tubeless/commit/1134289fe9b64b5d7616496a126973dc3ea803d9))
* Update Discord webhook avatar URL to GitHub logo ([31f308e](https://github.com/GhostMaintainers/Tubeless/commit/31f308eec72b495864cbcebfc5577ee70b8af13a))
* Update Discord webhook mention role id ([6da398e](https://github.com/GhostMaintainers/Tubeless/commit/6da398ee137589dce0dcbfb9537d1034a0c2c61c))
* update README ([7391a7f](https://github.com/GhostMaintainers/Tubeless/commit/7391a7fc0e343ee1c4929c3d844f125ea291716c))
* update README ([2d2d141](https://github.com/GhostMaintainers/Tubeless/commit/2d2d1416656922f5629172922d40516a8853a9bf))
* Update README ([#130](https://github.com/GhostMaintainers/Tubeless/issues/130)) ([1da0995](https://github.com/GhostMaintainers/Tubeless/commit/1da0995719c327982c67783a93b6f2bc383be40f))
* Update README with new features for Tubeless ([352c34d](https://github.com/GhostMaintainers/Tubeless/commit/352c34dfbaebec2e3113fc9a3a6dfcdb910331c7))
* Update README with project caution and forking information ([dbc409a](https://github.com/GhostMaintainers/Tubeless/commit/dbc409a66c37c1cdbf6fd832e618abdc0e5df07f))


### Refactors

* **assets:** drop unused Tailwind theme tokens ([b5f626c](https://github.com/GhostMaintainers/Tubeless/commit/b5f626c9f216b874a975575c117340b7413a3fb5))
* remove dead components and unused context functions ([5a864ac](https://github.com/GhostMaintainers/Tubeless/commit/5a864acc16e50f7e6ec6b8603c93cf86fe856052))
* remove unused Sources.IndexTableLive module ([ba498c9](https://github.com/GhostMaintainers/Tubeless/commit/ba498c9c227ce9ca8f3340fcbb07bc8bfb3dec2c))

## [0.5.0](https://github.com/CommunityMaintained/tubeless/compare/v0.4.0...v0.5.0) (2026-08-02)


### Features

* add a Time Format setting to switch between 12h and 24h ([cd91c46](https://github.com/CommunityMaintained/tubeless/commit/cd91c465cef8c834c9bbc35aaff8ab1bf0cc18a0))
* add SQLite and connection pool telemetry ([876a904](https://github.com/CommunityMaintained/tubeless/commit/876a904f9cdef921fca82dbdc761670969f10f17))
* let new sources default to a configurable Cookie Behavior ([42f2245](https://github.com/CommunityMaintained/tubeless/commit/42f224503d52ea69facb11c90b20d38373dd791d))
* reorganize settings into task-based cards that auto-save inline ([223a038](https://github.com/CommunityMaintained/tubeless/commit/223a03868bf625086d38d0f9d88a3f31f3ac4856))


### Bug Fixes

* add link in Cookie Behaviour help to the YouTube Cookies wiki page ([2c1f9cf](https://github.com/CommunityMaintained/tubeless/commit/2c1f9cf97bd6103cbba2095d34dc9cf6a2acb7fc))
* clarify main page storage usage ([b0cdcad](https://github.com/CommunityMaintained/tubeless/commit/b0cdcada979182a46695c6f852d05a50bcd6075b))
* further db access optimizations ([0a9990c](https://github.com/CommunityMaintained/tubeless/commit/0a9990c9485cb91b87e31618cf9680f954292573))
* increase db conn pool and cache to help with reconcile responsivity ([cd55489](https://github.com/CommunityMaintained/tubeless/commit/cd55489049625681940e15119886c7f2d8257785))
* show log timestamps in the configured timezone ([af8e3a7](https://github.com/CommunityMaintained/tubeless/commit/af8e3a74ef02f29b8dcc9dd1fa931ba1f70419bf))
* show time using the configured timezone ([fba9c3c](https://github.com/CommunityMaintained/tubeless/commit/fba9c3c78cc1e353ac4a49077fa9cb96711ebcf4))


### Chores

* **ci:** break out ci-build into phases ([2060ab9](https://github.com/CommunityMaintained/tubeless/commit/2060ab956abcc97cc4b9d11c517ca6a81f45ab9f))
* **ci:** use ci-build image sha-2060ab9 ([129609d](https://github.com/CommunityMaintained/tubeless/commit/129609dd2cb5cccbc17f202685451a0133569f49))
* **deps:** bump elixir deps ([e31b3ab](https://github.com/CommunityMaintained/tubeless/commit/e31b3abb802510ceaafdaab67a1eef6f87977362))
* **deps:** bump ffmpeg build ([de3f25a](https://github.com/CommunityMaintained/tubeless/commit/de3f25a040f52bccabe1be54436a3ae28c02c822))
* **deps:** bump otp to 29.0.4 ([c623288](https://github.com/CommunityMaintained/tubeless/commit/c623288d3edae4fa0090fe60fe460fbbb41cba6d))
* drop unused settings_backup table ([1bc6c28](https://github.com/CommunityMaintained/tubeless/commit/1bc6c280b4107a5ee11977e8e44cf70be179d9a3))


### Documentation

* Add Subreddit to README ([77db710](https://github.com/CommunityMaintained/tubeless/commit/77db7108aea0d0fe978862ce312ff3cd2da50e99))
* Clarify database integrity check description ([02d0d94](https://github.com/CommunityMaintained/tubeless/commit/02d0d947ce2e147c33b1ad986622a9bc9797c6ce))
* Update Discord webhook avatar URL to GitHub logo ([31f308e](https://github.com/CommunityMaintained/tubeless/commit/31f308eec72b495864cbcebfc5577ee70b8af13a))
* Update Discord webhook mention role id ([6da398e](https://github.com/CommunityMaintained/tubeless/commit/6da398ee137589dce0dcbfb9537d1034a0c2c61c))
* update README ([7391a7f](https://github.com/CommunityMaintained/tubeless/commit/7391a7fc0e343ee1c4929c3d844f125ea291716c))
* Update README ([#130](https://github.com/CommunityMaintained/tubeless/issues/130)) ([1da0995](https://github.com/CommunityMaintained/tubeless/commit/1da0995719c327982c67783a93b6f2bc383be40f))

## [0.4.0](https://github.com/CommunityMaintained/tubeless/compare/v0.3.0...v0.4.0) (2026-07-30)


### Features

* add proxy support ([8d10c52](https://github.com/CommunityMaintained/tubeless/commit/8d10c529e34710ad799b5c7255deee9a7b18d2ca))
* add system status summary to the home page ([7019007](https://github.com/CommunityMaintained/tubeless/commit/7019007a045baa75828a60dce1a1a8690b2c073e))
* separate downloads that are queued from those still pending on the home page ([de1d474](https://github.com/CommunityMaintained/tubeless/commit/de1d474cd1ebd5921a1509e383ab0d2389c25a4d))
* show live progress while a reconcile plan applies ([87a27c8](https://github.com/CommunityMaintained/tubeless/commit/87a27c82cde86c74a06731f72ef1375acfb19c89))
* speed up reconcile by fetching online backfills in parallel ([05049fc](https://github.com/CommunityMaintained/tubeless/commit/05049fc7a299fd6b4ad794ab7529a94ea7707b24))


### Bug Fixes

* label File Reconciliation jobs in the Active Tasks list ([552de57](https://github.com/CommunityMaintained/tubeless/commit/552de5750acf43d29c219dd21b4124fe76e224fe))
* recover a reconcile apply interrupted by a restart instead of deadlocking ([221643f](https://github.com/CommunityMaintained/tubeless/commit/221643f82eb767b78e4ceb3990e1a8e902f6c818))
* serialize quiet-window workers to prevent deadlock situation ([4e7ac31](https://github.com/CommunityMaintained/tubeless/commit/4e7ac3140548e8f92a63dc7ec36ba03898b394b4))
* stop counting actively-downloading videos as Queued on the dashboard ([172dc5f](https://github.com/CommunityMaintained/tubeless/commit/172dc5f37ac6b9b611b82f43713331a61b333dfe))


### Chores

* upgrade Tailwind CSS to v4.3.3 ([97ccb64](https://github.com/CommunityMaintained/tubeless/commit/97ccb64f29147bfde4a8f911c5869734dcac87e6))


### Documentation

* Fix formatting in README.md for LOG_LEVEL note ([c780241](https://github.com/CommunityMaintained/tubeless/commit/c78024170cec5ec9125d67b2d9599ab8902f4736))
* Fix grammatical error in pull request template ([69fa2e4](https://github.com/CommunityMaintained/tubeless/commit/69fa2e48fe977b653cb303dba5b2dcba1747726a))
* Fix grammatical issues in README.md ([d8eec32](https://github.com/CommunityMaintained/tubeless/commit/d8eec32f1f7f61609681c3d2b33a931b0c6d08e0))
* update comparison in README ([a6715cb](https://github.com/CommunityMaintained/tubeless/commit/a6715cbb2375e8c06fd0942a4f0cb73ef282138d))
* Update Discord server link in README to a permant invite pointing to #welcome channel ([1134289](https://github.com/CommunityMaintained/tubeless/commit/1134289fe9b64b5d7616496a126973dc3ea803d9))

## [0.3.0](https://github.com/CommunityMaintained/tubeless/compare/v0.2.0...v0.3.0) (2026-07-26)


### Features

* add offline database maintenance mode for backups and repairs ([bc81886](https://github.com/CommunityMaintained/tubeless/commit/bc81886a36207760111b338b4b57b35b580c1ec5))
* add orphaned job to agnostics ([944b1d3](https://github.com/CommunityMaintained/tubeless/commit/944b1d3679385624ecd90ba3534afcb7c5f99b4b))
* check the database for corruption from the diagnostics page ([ade672b](https://github.com/CommunityMaintained/tubeless/commit/ade672bc6cb7778672d9005c955e901915f95ed1))
* recover jobs stuck with retries exhausted from diagnostics ([773e6c1](https://github.com/CommunityMaintained/tubeless/commit/773e6c198415e5d8572fb7f93c94d7050d12e458))


### Bug Fixes

* **ci:** move discord notification to release-please workflow ([fa8ddfd](https://github.com/CommunityMaintained/tubeless/commit/fa8ddfdc890abe28d249f1c91e138a5463591208))
* fetch sqlean extension when a stale version marker has no binaries ([e9fe03c](https://github.com/CommunityMaintained/tubeless/commit/e9fe03c4125b391244d641c45fab72f703d976be))
* match the Queue Health refresh button to the other action buttons ([668999e](https://github.com/CommunityMaintained/tubeless/commit/668999eb346d3ab1650128a915e3a306b69a2366))
* stop bold+italic text from loading a broken Satoshi font glyph ([49f7fd4](https://github.com/CommunityMaintained/tubeless/commit/49f7fd40843c49dd37bdac27d67d72c912a34345))
* **tooling:** abort container startup when database migration fails ([3fc0dd9](https://github.com/CommunityMaintained/tubeless/commit/3fc0dd959fce68f7ac0d688639d2a6f00f1fc203))


### Chores

* **deps:** bump esbuild and tailwind pinned binary versions ([300478d](https://github.com/CommunityMaintained/tubeless/commit/300478d3cb2fec585f702268d2269a42a03770e3))


### Documentation

* refreshed DB schema visualization ([d181df3](https://github.com/CommunityMaintained/tubeless/commit/d181df38eab5f1f1a9a6addb85ab2c67af98629e))

## [0.2.0](https://github.com/CommunityMaintained/tubeless/compare/v0.1.0...v0.2.0) (2026-07-24)


### Features

* add GitHub Releases to Discord workflow ([#61](https://github.com/CommunityMaintained/tubeless/issues/61)) ([a07217e](https://github.com/CommunityMaintained/tubeless/commit/a07217e626b558cbe0f2b327e3684389e493f85f))
* add library size display to diagnostics page ([#40](https://github.com/CommunityMaintained/tubeless/issues/40)) ([c75a5b3](https://github.com/CommunityMaintained/tubeless/commit/c75a5b358386229c1446625e75e44ebaf84ff2a4))
* publish sources as static podcast feeds servable without exposing Tubeless ([#55](https://github.com/CommunityMaintained/tubeless/issues/55)) ([ee5ed6a](https://github.com/CommunityMaintained/tubeless/commit/ee5ed6a39a2c584436cd91d0bafdab8293b988af))
* relocate and true up downloaded files after settings changes, without re-downloading ([ad2a66e](https://github.com/CommunityMaintained/tubeless/commit/ad2a66ec152133866a6f413cd3903b68496129e2))


### Bug Fixes

* re-index a source when its indexing cutoff reaches further into the past ([aa2fc43](https://github.com/CommunityMaintained/tubeless/commit/aa2fc4329eda2d6e4f60fbf8afd20bb5a7064971))
* **ui:** don't underline trailing white space past link text ([692890d](https://github.com/CommunityMaintained/tubeless/commit/692890d97d373ef0321ac7bd514be68d7b096f75))


### Chores

* **ci:** improve local docker script ([d339fff](https://github.com/CommunityMaintained/tubeless/commit/d339fff4e9e8fd626c1cdb6ac48a2eb31ed47bb0))
* **ci:** lint and and local run docker ([#62](https://github.com/CommunityMaintained/tubeless/issues/62)) ([622f5e0](https://github.com/CommunityMaintained/tubeless/commit/622f5e03c7c5ad7e8a50d1c24be7a9a000b3c305))
* **ci:** switch from Github issue templates to the new issue forms ([#34](https://github.com/CommunityMaintained/tubeless/issues/34)) ([61c54f3](https://github.com/CommunityMaintained/tubeless/commit/61c54f35a8b1ecf8a34b5eb83b053ddc4b229d13))
* **deps:** pin dependencies ([caa7379](https://github.com/CommunityMaintained/tubeless/commit/caa7379dc73b34f6cb8759971ae5150711bce443))
* **deps:** update actions/checkout action to v7 ([bb1a5e3](https://github.com/CommunityMaintained/tubeless/commit/bb1a5e35e9eaa4684bfcd53630e3c5a15626550d))
* **deps:** update dependency prettier to v3.9.6 ([a1980d1](https://github.com/CommunityMaintained/tubeless/commit/a1980d10a93ba48584b7e8a73675ee1f19dbc1af))
* **deps:** update docker/login-action digest to abd2ef4 ([8461f41](https://github.com/CommunityMaintained/tubeless/commit/8461f4102c891a8bb0640052f7bb7d8e0370e088))


### Documentation

* add comparison section for Pinchflat vs Tubeless to README.md file ([#41](https://github.com/CommunityMaintained/tubeless/issues/41)) ([73d2462](https://github.com/CommunityMaintained/tubeless/commit/73d2462853b0050df93f0de67afcc647e803a071))

## [0.1.0](https://github.com/CommunityMaintained/tubeless/compare/v0.0.2...v0.1.0) (2026-07-19)


### Features

* add database insights and safe compaction maintenance to the diagnostics page ([ee741db](https://github.com/CommunityMaintained/tubeless/commit/ee741db6c2935299d5f5216a0ee22b6a7e872745))
* allow SponsorBlock to both remove and mark selected categories ([ba09ff9](https://github.com/CommunityMaintained/tubeless/commit/ba09ff933301d48ae7ed72a54cb901db8955f72a))
* let media profiles ignore YouTube AI-upscaled videos ([8e2f334](https://github.com/CommunityMaintained/tubeless/commit/8e2f334c4556353bbb12e6addd24f739181a44d8))
* let sources stop indexing large channels at a cutoff date ([6b6a249](https://github.com/CommunityMaintained/tubeless/commit/6b6a2492fa5d67d48f04f9b13e707ddc4a95ff59))
* refresh Queue Health on the diagnostics page without a full page reload ([85cea6b](https://github.com/CommunityMaintained/tubeless/commit/85cea6ba0505153b7a79f857fc546561a5ed1f35))
* remove Pro unlock and Donate button — every feature is available out of the box ([7daad33](https://github.com/CommunityMaintained/tubeless/commit/7daad33ab360962308c3c6a98024b1d0bb9af3ae))


### Bug Fixes

* name episode thumbnails to match the media file so Plex displays them ([5d27ea6](https://github.com/CommunityMaintained/tubeless/commit/5d27ea6c03ca8a83ecb8a37190bfb3a90b25c420))
* stop disabled form fields from flashing white on the dark theme ([c0c3d0f](https://github.com/CommunityMaintained/tubeless/commit/c0c3d0f074ad55d02121bd63a9168e9ad55863fa))


### Documentation

* stop labeling Shorts controls as experimental ([29413d9](https://github.com/CommunityMaintained/tubeless/commit/29413d9877490ccd133abb707f731e9d87472a52))
* update cookie help URL in cookie_file_live.ex from Pinchflat to Tubeless' Wiki ([#32](https://github.com/CommunityMaintained/tubeless/issues/32)) ([0707097](https://github.com/CommunityMaintained/tubeless/commit/07070970b6c18eddc2d31f3b26d279e5587860dd))

## [0.0.2](https://github.com/CommunityMaintained/tubeless/compare/v0.0.1...v0.0.2) (2026-07-17)


### Bug Fixes

* **deps:** add sctp1 module for otp 29 ([7a520d5](https://github.com/CommunityMaintained/tubeless/commit/7a520d5088c3095669f0b77ad78ebbe4fc18044f))


### Chores

* **ci:** bump pinned ci-base image to sha-1629079 ([65789d1](https://github.com/CommunityMaintained/tubeless/commit/65789d1b04a80bb6d80ac3fabf87bd77f60783e1))
* **deps:** update Debian snapshot to trixie-20260713-slim ([f3a5e12](https://github.com/CommunityMaintained/tubeless/commit/f3a5e12f60d200cc1c03353c879e3658dacf3ead))
* **deps:** update OTP to 29.0.3 in ci-base image ([1629079](https://github.com/CommunityMaintained/tubeless/commit/1629079b7ffdce615e1e7be8e74183ae1d35fe02))
* **doc:** reformat CHANGELOG ([9170c6c](https://github.com/CommunityMaintained/tubeless/commit/9170c6c2fb0b00b39182b630493f8683aa7f936b))


### Documentation

* add details about tubeless vs pinchflat ([4fb55ed](https://github.com/CommunityMaintained/tubeless/commit/4fb55ed2ebfe224cb0672c444938a2839a0f5408))

## 0.0.1 (2026-07-15)


### ⚠ BREAKING CHANGES

* rebrand from Pinchflat to Tubeless
* new repo, new image name
* all features released under CommunityMaintained/pinchflat carried over until release 1.4.0
* migration from Pinchflat (both upstream and fork) are supported
* migration back to Pinchflat is no longer guaranteed

## Changes originally released as Pinchflat fork

### Pinchflat 1.4.0 (2026-07-10)


#### Features

* let templates mark where channel artwork and NFOs are stored ([279bebf](https://github.com/CommunityMaintained/tubeless/commit/279bebfdc8ce1f3fa4f6d69f772c58ea356c6ac9))
* requeue stuck jobs from the Diagnostics page instead of cancelling them ([cbabc68](https://github.com/CommunityMaintained/tubeless/commit/cbabc68414a12ee4c42acecec62c6e0fe08e5cba))


#### Bug Fixes

* correct pending count for sources with no downloaded media ([8675262](https://github.com/CommunityMaintained/tubeless/commit/8675262eebc7dad00f229d850fad9f50d3b09ef1))
* handle suffix Range requests and missing files when streaming media ([e4c5a32](https://github.com/CommunityMaintained/tubeless/commit/e4c5a3293f7c6cf4fc5e3d13324e8cc27f0606d5))
* reschedule missing source indexing jobs on boot ([beb6a16](https://github.com/CommunityMaintained/tubeless/commit/beb6a16ea25a94e9c68d9560bba035debaa5e113))
* restore the media search box after a LiveView reconnect ([c447d21](https://github.com/CommunityMaintained/tubeless/commit/c447d21d413fd64875c91a47228ea5b9559fdce6))
* skip download archive when the archive file cannot be written ([5aac447](https://github.com/CommunityMaintained/tubeless/commit/5aac4477f36d291b27045434eedf6aaf8f08e246))
* stop crashing when rendering 404 and 500 error pages ([#154](https://github.com/CommunityMaintained/tubeless/issues/154)) ([7b0bd7f](https://github.com/CommunityMaintained/tubeless/commit/7b0bd7f37668a6428172a471c843d6a582cebb36))
* stop logging YouTube API keys ([515eabf](https://github.com/CommunityMaintained/tubeless/commit/515eabf1a5a59abffe32c2d18ffc98c47ab1e222))
* stop losing in-flight source enable toggles on LiveView reconnect ([6d9d184](https://github.com/CommunityMaintained/tubeless/commit/6d9d184d9d973ffa4fbda4d16d8e4d268018cff2))
* stop the diagnostics page crashing when job queues aren't running ([779080c](https://github.com/CommunityMaintained/tubeless/commit/779080c20b1ee0809bbdd770bc3f82fc7002633c))
* test all YouTube API keys and report which fail ([347f0be](https://github.com/CommunityMaintained/tubeless/commit/347f0be760933ac546766f24bed689f475d69d6f))
* throttle job state broadcasts to reduce dashboard query load ([21555ae](https://github.com/CommunityMaintained/tubeless/commit/21555aef88e33be75b0af3e7ec374a9483a5f2c9))


#### Chores

* add fast Docker test runner for local iteration ([b976cf2](https://github.com/CommunityMaintained/tubeless/commit/b976cf2aad014fc6fb43ee9a97a15b57daa18b12))
* **ci:** bump ci-base image to sha-ba3e559 ([a13ac24](https://github.com/CommunityMaintained/tubeless/commit/a13ac24d9a81d804234bd024b4a789c793bb0492))
* **ci:** track hexpm/elixir base image versions with Renovate ([ba3e559](https://github.com/CommunityMaintained/tubeless/commit/ba3e559ec54cc2e925312e0cec3ee07e18bf88a0))
* **deps:** bump Erlang/OTP to 28.5.0.3 ([cf681a2](https://github.com/CommunityMaintained/tubeless/commit/cf681a2962a6247aab5ceafd3e003d7df2db697c))
* **deps:** update dependency apprise to v1.12.0 ([945105b](https://github.com/CommunityMaintained/tubeless/commit/945105be5544cfd911b161d560cebac010b91b46))
* ignore runtime wiring and test support in coverage reporting ([a8f6d76](https://github.com/CommunityMaintained/tubeless/commit/a8f6d76d4da44a3c44ada129957daaa6090cc78b))


#### Documentation

* correct boot sequence responsibilities in CLAUDE.md ([241be98](https://github.com/CommunityMaintained/tubeless/commit/241be98e3c0584f151a5849007378712b11227bc))


#### Refactors

* remove unused Sources.IndexTableLive module ([ba498c9](https://github.com/CommunityMaintained/tubeless/commit/ba498c9c227ce9ca8f3340fcbb07bc8bfb3dec2c))

### Pinchflat 1.3.1 (2026-07-05)


#### Bug Fixes

* auto-refresh Media History on job state changes ([98d654f](https://github.com/CommunityMaintained/tubeless/commit/98d654fb32736da9948bb1d11ccdf94c43aed537))
* correct static Size values in sources table on re-sort ([a876bcd](https://github.com/CommunityMaintained/tubeless/commit/a876bcd817847a87e44bbbc9f50b366202186b0a)), closes [#112](https://github.com/CommunityMaintained/tubeless/issues/112)
* handle unparseable yt-dlp source metadata responses gracefully ([813c8ad](https://github.com/CommunityMaintained/tubeless/commit/813c8adcda43a6885dde19b4e2496526810417f8))
* index channel tabs separately so new shorts are found on repeat indexes ([13a160a](https://github.com/CommunityMaintained/tubeless/commit/13a160a0a8b84d2c0f7b7214e73ba305acb58365)), closes [#59](https://github.com/CommunityMaintained/tubeless/issues/59)
* label binary byte sizes with IEC units eg. KiB/MiB/GiB ([47fde1f](https://github.com/CommunityMaintained/tubeless/commit/47fde1f81a992d4b0c8d7634a4c11ba6075330a1))
* unlock-pro modal button stuck disabled ([#125](https://github.com/CommunityMaintained/tubeless/issues/125)) ([5c26116](https://github.com/CommunityMaintained/tubeless/commit/5c261160f79ea9fccaea8cafd3096d1954ddd1c0))
* warn on malformed output-path templates in the UI ([c4bb94a](https://github.com/CommunityMaintained/tubeless/commit/c4bb94a0f7af07023d295e8bd9f7a990ab9aa376))


#### Chores

* add local CI lint/test script ([6b5bc79](https://github.com/CommunityMaintained/tubeless/commit/6b5bc7926e3037a70417714548db9f05a13e5463))
* **ci:** bump ci-base image to sha-93af908 ([6d29a27](https://github.com/CommunityMaintained/tubeless/commit/6d29a276522c034fdf6f824a14e096431488ff35))
* **ci:** fetch sqlean extensions at build time instead of vendoring ([053064b](https://github.com/CommunityMaintained/tubeless/commit/053064b8d6abe262a96131715240020da92f2600))
* **ci:** release config updates ([4bf8cf2](https://github.com/CommunityMaintained/tubeless/commit/4bf8cf26ea3620eb1330b30cf6afba8ba74a8dad))
* **deps:** update actions/cache action to v6 ([271b43b](https://github.com/CommunityMaintained/tubeless/commit/271b43b1de7de7926c7c78636ca590e802d00d80))
* **deps:** update github actions ([8003703](https://github.com/CommunityMaintained/tubeless/commit/800370390b385ba5f65b3b5b060d7c49429d5cf4))
* **deps:** update to 2026-07-01-16-32 ffmpeg build ([93af908](https://github.com/CommunityMaintained/tubeless/commit/93af908ee245665899331600b464d6f88e462f28))
* **deps:** use published faker instead of private git fork ([792da4a](https://github.com/CommunityMaintained/tubeless/commit/792da4abc49c7e55b58081cb10fedbf4f4e57a03))
* track ci-base pip requirements with Renovate ([8f1194d](https://github.com/CommunityMaintained/tubeless/commit/8f1194dc50d0484f9bd6fe944e86ed77d039064c))


#### Documentation

* clarify metadata/NFO toggle labels in media profile form ([7680d06](https://github.com/CommunityMaintained/tubeless/commit/7680d065ddd5ccb66adf49d03c3a86580110fcb6))
* update README ([2d2d141](https://github.com/CommunityMaintained/tubeless/commit/2d2d1416656922f5629172922d40516a8853a9bf))

### Pinchflat 1.3.0 (2026-06-30)


#### Features

* add queue visibility and discarded job management to diagnostics ([5343985](https://github.com/CommunityMaintained/tubeless/commit/5343985e6614d448cd0e3b1e56e78569be008800))
* control yt-dlp update behavior from settings ([058ba47](https://github.com/CommunityMaintained/tubeless/commit/058ba4762a5415246cf73f4e68cddda68bc1f295))


#### Bug Fixes

* avoid length/1 check and reformat mix.exs deps ([4d3986a](https://github.com/CommunityMaintained/tubeless/commit/4d3986acfee4a5762f2357518b2db6f1008b1e87))
* configure Oban PG notifier and incomplete unique states for 2.23 ([0fb0183](https://github.com/CommunityMaintained/tubeless/commit/0fb018302e699e106c5c8d0e552e3c69b08509b6))
* keep indexing reschedule from deduping against its own executing job ([115f8db](https://github.com/CommunityMaintained/tubeless/commit/115f8db8ef6e6b1a7edf72844536a8ade2f9e0a1))
* pin Deno and Apprise in selfhosted runner to match ci-base ([b9b372c](https://github.com/CommunityMaintained/tubeless/commit/b9b372cbabf956fd4eabecf82de6c843cda7cae4))
* resolve Elixir 1.20 compiler warnings ([43ea35d](https://github.com/CommunityMaintained/tubeless/commit/43ea35dcf9ee8ef8b73ddd861b16326230af4320))
* route ecto.migrate ERD guard through sh for Elixir 1.20 ([04cf3f3](https://github.com/CommunityMaintained/tubeless/commit/04cf3f3ccfac71f5c8f17472b8eba20ca54d8439))
* update formatting for phoenix ([cd6cc8b](https://github.com/CommunityMaintained/tubeless/commit/cd6cc8b542ac405074ed773dc34314bdc3d89300))


#### Reverts

* Move Active Tasks to tab in Media History section ([#836](https://github.com/CommunityMaintained/tubeless/issues/836)) ([59849e3](https://github.com/CommunityMaintained/tubeless/commit/59849e342817d1961feb147c6c0b0aa325a993e3))


#### Chores

* add tooling script ([460fbd1](https://github.com/CommunityMaintained/tubeless/commit/460fbd1c6ce7783bbae8932ed64ee24ea4325a2e))
* **ci:** run lint/test jobs natively in ci-base container ([e5430f2](https://github.com/CommunityMaintained/tubeless/commit/e5430f2a96cf58bc13f7ea8d904b8ffe86ab963b))
* **deps:** alpinejs 3.15.12 ([a12f722](https://github.com/CommunityMaintained/tubeless/commit/a12f72252945aa5fcb50f7f2af77c470aaacd64b))
* **deps:** bump Elixir 1.20.2, OTP 28.5.0.2, Debian trixie-20260623 in ci-base ([95b825a](https://github.com/CommunityMaintained/tubeless/commit/95b825afc7bf93dc96d469f30252d6db0157bd48))
* **deps:** bump Node 20 -&gt; 24 in ci-base, add renovate tracking, sync CODEBASE versions ([f22adc4](https://github.com/CommunityMaintained/tubeless/commit/f22adc49c18a5734476dee61165b3496368e4501))
* **deps:** faker to work with elixir 1.20; update misc deps ([edbff35](https://github.com/CommunityMaintained/tubeless/commit/edbff3587d58f72023e4685e114f1700d7fbbe50))
* **deps:** pin dependencies ([e002b75](https://github.com/CommunityMaintained/tubeless/commit/e002b7547bf9f374069a7983d79b0d68d541aaa8))
* **deps:** pin elixir in renovate ([cb55b03](https://github.com/CommunityMaintained/tubeless/commit/cb55b0300e14b513e86374e199f9787415e21731))
* **deps:** replace floki with lazy_html ([13d7924](https://github.com/CommunityMaintained/tubeless/commit/13d79242daf9b7a16a4358ccf82369d4a38782a7))
* **deps:** update dependency alpinejs to v3.15.12 ([a753ff8](https://github.com/CommunityMaintained/tubeless/commit/a753ff8f4cd2535ce0a216b58c9e2f248b007801))
* **deps:** update dependency exqlite to 0.38.0 ([6e2dc17](https://github.com/CommunityMaintained/tubeless/commit/6e2dc17dc7d0b7dcfbcff8d15fce4228713180d6))
* **deps:** update dependency phoenix to ~&gt; 1.8.0 ([9c0f74d](https://github.com/CommunityMaintained/tubeless/commit/9c0f74dcdcc53059a86a4639eff7ef6aee440bd9))
* **deps:** update dependency phoenix_live_view to v1.2.4 ([a239149](https://github.com/CommunityMaintained/tubeless/commit/a2391491ece970bb80fb15ecc87d14c75624ac41))
* **deps:** update dependency phoenix_live_view to v1.2.5 ([b2d638e](https://github.com/CommunityMaintained/tubeless/commit/b2d638e6016be4fbd97211354e18e5b2213214f8))
* **deps:** update dependency prettier to v3.8.5 ([9389279](https://github.com/CommunityMaintained/tubeless/commit/93892793013fe284804494867fe81a38fa99c3ea))
* **deps:** update dependency prettier to v3.9.0 ([2e9301a](https://github.com/CommunityMaintained/tubeless/commit/2e9301a1bd3f4430a1ad53cea9aa74f318aae252))
* **deps:** update dependency prettier to v3.9.1 ([a66decb](https://github.com/CommunityMaintained/tubeless/commit/a66decb323fe6c1480a18f0f1fe20bcaf96dbaa8))
* **deps:** update dependency prettier to v3.9.3 ([8130c84](https://github.com/CommunityMaintained/tubeless/commit/8130c84d5372f3f56210bdb8c4480447041864f5))
* **deps:** update dependency prettier to v3.9.4 ([d2c4d45](https://github.com/CommunityMaintained/tubeless/commit/d2c4d45215b4874fdbdd6321a9f3317e6aaf4ade))
* **deps:** update dependency tailwind to ~&gt; 0.5.0 ([9e38148](https://github.com/CommunityMaintained/tubeless/commit/9e38148d894629d3deb52e95935dcc69564e6d57))
* **deps:** update phoenix_live_view ([e0651b6](https://github.com/CommunityMaintained/tubeless/commit/e0651b68765431dcb5bdfde5ec6463b41d545e24))
* **deps:** update renovate constraints ([7051c58](https://github.com/CommunityMaintained/tubeless/commit/7051c58c92809767826639f5ad9bcf6f2ac7ea19))
* **deps:** update timex digest to 3.7.13 ([e4f9983](https://github.com/CommunityMaintained/tubeless/commit/e4f99831d2540f7cf98e05d68daea740b1f1c1b1))
* **deps:** update timex digest to 5ad1b82 ([83710dc](https://github.com/CommunityMaintained/tubeless/commit/83710dcb75b88ede0e97451883424bc6d8920665))
* **deps:** use new elixir/otp ([f5e830b](https://github.com/CommunityMaintained/tubeless/commit/f5e830b97a7e553c3660e14f93d8b76316b98b1a))
* schedule renovate biweekly, remove PR rate limits, enable dependency dashboard ([efe8668](https://github.com/CommunityMaintained/tubeless/commit/efe8668216c4070ad443935958157f8466f9f6b5))
* tune release-please changelog sections ([5e1fa12](https://github.com/CommunityMaintained/tubeless/commit/5e1fa12cb63113ac3a283d0b8f4b07ac483e9b78))


#### Documentation

* reference yt-dlp faq ([80529fc](https://github.com/CommunityMaintained/tubeless/commit/80529fc7d3b32dcc831e5918ebf7029f66932792))

### Pinchflat 1.2.0 (2026-06-26)


#### Features

* add setting to ignore unavailable/members-only media ([eff8c0c](https://github.com/CommunityMaintained/tubeless/commit/eff8c0c075b287fbee19fbbcbc7a2ad234a27b64))
* mask YouTube API key and add cookies file management ([#53](https://github.com/CommunityMaintained/tubeless/issues/53)) ([343a630](https://github.com/CommunityMaintained/tubeless/commit/343a630638bdf099a786e9022e3f3f6daf712a92))
* report accurate status for non-downloaded media in Other tab ([8c188ac](https://github.com/CommunityMaintained/tubeless/commit/8c188aca346a873e31ee2b8296c3e20f09615cf9))
* surface auto-skipped unavailable media as a distinct status ([e88d403](https://github.com/CommunityMaintained/tubeless/commit/e88d403c4d3b655ee08b5785298313e3fb6f3df8))


#### Bug Fixes

* re-download existing media by forcing the download job ([f47a6e0](https://github.com/CommunityMaintained/tubeless/commit/f47a6e03e2780cc67b6646560410085adb90e453))
* render NFO aired date as plain date for Jellyfin ([#60](https://github.com/CommunityMaintained/tubeless/issues/60)) ([0282c19](https://github.com/CommunityMaintained/tubeless/commit/0282c19789d3154bf4eff92a74c8d7c90186ba5f)), closes [#57](https://github.com/CommunityMaintained/tubeless/issues/57)
* serve apple-touch-icon to avoid 404 probes from iOS ([451123b](https://github.com/CommunityMaintained/tubeless/commit/451123b108bf2dfa14c6b87577a261f4c739d0f3))

### Pinchflat 1.1.0 (2026-06-18)


#### Features

* Add queue diagnostics page ([#48](https://github.com/CommunityMaintained/tubeless/issues/48)) ([578f698](https://github.com/CommunityMaintained/tubeless/commit/578f698712339bcb5ad3186fb39db0618286cbac))
* Add YouTube API key testing in Settings ([#47](https://github.com/CommunityMaintained/tubeless/issues/47)) ([90303c1](https://github.com/CommunityMaintained/tubeless/commit/90303c15108a45f22c4fffbd31f15a99ade1f24c))


#### Bug Fixes

* **ci:** remove CalVer, build version needs to be semver compliant ([55dece8](https://github.com/CommunityMaintained/tubeless/commit/55dece8e63f77520e3a55d1a587415d7661b2b3d))

### Pinchflat 1.0.0 (2026-06-14)


#### ⚠ BREAKING CHANGES

* bump major version for first release

#### Features

* add release-please, change versioning to SemVer ([67c85f3](https://github.com/CommunityMaintained/tubeless/commit/67c85f314d25d49d60205b600da5b791ff314332))
* bump major version for first release ([1bedbe4](https://github.com/CommunityMaintained/tubeless/commit/1bedbe4c1bd6edab107af5e529b03f2df4ecb2b6))
* bump release ([914dbd3](https://github.com/CommunityMaintained/tubeless/commit/914dbd3c1f0caea4e3238a64a4ad4b7df424c5c2))


#### Bug Fixes

* assigng correct tags to dev builds ([36709df](https://github.com/CommunityMaintained/tubeless/commit/36709df589050e2f2787d505c43f551872ca6c9b))
* **ci:** correct casing for ghcr ([e08570b](https://github.com/CommunityMaintained/tubeless/commit/e08570bb7d50fa9df6e372459d0cb58f64f1b7a5))
* **ci:** correct job deps in release ([a03f71a](https://github.com/CommunityMaintained/tubeless/commit/a03f71acb8172b6944fb4ef65d81b5eb414eebd9))
* **ci:** ignore prettier in changelog ([de54801](https://github.com/CommunityMaintained/tubeless/commit/de548018f7d17e1c2db6d7e8d466ea4de24e9f83))
* linter ([7b29408](https://github.com/CommunityMaintained/tubeless/commit/7b29408165bfca80d6c0c344dd275a1c880fd799))
* prettier'd new code ([ba41fb2](https://github.com/CommunityMaintained/tubeless/commit/ba41fb22cd5f954d9033efcfec4c94838be8c462))
* reflect new github org in webui ([2b8faeb](https://github.com/CommunityMaintained/tubeless/commit/2b8faeb29f342cc2d4382f0caee0add8a0046dbd))
* update image name ([122503d](https://github.com/CommunityMaintained/tubeless/commit/122503de2f03d1c57eb7d117b3ae88928f028538))
