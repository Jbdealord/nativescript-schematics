## [0.5.2](https://github.com/nativescript/nativescript-schematics/compare/0.5.1...0.5.2) (2019-03-20)


### Bug Fixes

* **ng-new:** make resolution of lazily-loaded routes consistent between web and mobile ([#198](https://github.com/nativescript/nativescript-schematics/issues/198)) ([9b1c31c](https://github.com/nativescript/nativescript-schematics/commit/9b1c31c)), closes [#197](https://github.com/nativescript/nativescript-schematics/issues/197)
* fix the slow execution of `ng generate component` ([#190](https://github.com/NativeScript/nativescript-schematics/pull/190))



## [0.5.1](https://github.com/nativescript/nativescript-schematics/compare/0.5.0...0.5.1) (2019-02-19)


### Features

* update ng new/add schematics to use NativeScript 5.2 and Angular 7.2 ([#191](https://github.com/nativescript/nativescript-schematics/issues/191)) ([5e577e4](https://github.com/nativescript/nativescript-schematics/commit/5e577e4))



# [0.5.0](https://github.com/nativescript/nativescript-schematics/compare/0.4.0...0.5.0) (2019-01-07)


### Bug Fixes

* resolve main.tns.ts with webpack's VFS instead with TS ([#174](https://github.com/nativescript/nativescript-schematics/issues/174)) ([7d9622d](https://github.com/nativescript/nativescript-schematics/commit/7d9622d)), closes [#173](https://github.com/nativescript/nativescript-schematics/issues/173) [#173](https://github.com/nativescript/nativescript-schematics/issues/173)


### Features

* Official support for Angular 7.1.

* flag to skip adding auto-generated component on `ng new` and `ng add` ([#171](https://github.com/nativescript/nativescript-schematics/issues/171)) ([6c835b1](https://github.com/nativescript/nativescript-schematics/commit/6c835b1))



<a name="0.4.0"></a>
# [0.4.0](https://github.com/nativescript/nativescript-schematics/compare/0.3.4...0.4.0) (2018-11-13)


### Bug Fixes

* generate issues ([#136](https://github.com/nativescript/nativescript-schematics/issues/136)) ([de30da7](https://github.com/nativescript/nativescript-schematics/commit/de30da7)), closes [#134](https://github.com/nativescript/nativescript-schematics/issues/134)


### Features

* update to Angular 7 :tada: ([#139](https://github.com/nativescript/nativescript-schematics/issues/139)) ([438b9e3](https://github.com/nativescript/nativescript-schematics/commit/438b9e3))



<a name="0.3.4"></a>
## [0.3.4](https://github.com/nativescript/nativescript-schematics/compare/0.3.3...0.3.4) (2018-10-17)


### Bug Fixes

* fix component generation issues ([#136](https://github.com/nativescript/nativescript-schematics/issues/136)) ([de30da7](https://github.com/nativescript/nativescript-schematics/commit/de30da7)), closes [#134](https://github.com/nativescript/nativescript-schematics/issues/134)



<a name="0.3.3"></a>
## [0.3.3](https://github.com/nativescript/nativescript-schematics/compare/0.3.2...0.3.3) (2018-10-10)


### Bug Fixes

* **component:** prevent the command from hanging if no module is found ([#127](https://github.com/nativescript/nativescript-schematics/issues/127)) ([7ca9462](https://github.com/nativescript/nativescript-schematics/commit/7ca9462)), closes [#126](https://github.com/nativescript/nativescript-schematics/issues/126)



<a name="0.3.2"></a>
## [0.3.2](https://github.com/nativescript/nativescript-schematics/compare/0.3.0...0.3.2) (2018-10-10)


### Bug Fixes

* remove tsconfig.spec.ts extend option ([#114](https://github.com/nativescript/nativescript-schematics/issues/114)) ([5a58d21](https://github.com/nativescript/nativescript-schematics/commit/5a58d21))
* **ng-new:** update the version of [@ngtools](https://github.com/ngtools)/webpack to 6.2.0 ([#116](https://github.com/nativescript/nativescript-schematics/issues/116)) ([fe11520](https://github.com/nativescript/nativescript-schematics/commit/fe11520))


### Features

* generate stylesheets when migrating components and modules ([#128](https://github.com/nativescript/nativescript-schematics/issues/128)) ([d0160f0](https://github.com/nativescript/nativescript-schematics/commit/d0160f0))



<a name="0.3.1"></a>
## [0.3.1](https://github.com/nativescript/nativescript-schematics/compare/0.3.0...0.3.1) (2018-09-14)

### Bug Fixes

* remove tsconfig.spec.ts extend option ([#114](https://github.com/nativescript/nativescript-schematics/issues/114)) ([5a58d21](https://github.com/nativescript/nativescript-schematics/commit/5a58d21))
* **ng-new:** update the version of [@ngtools](https://github.com/ngtools)/webpack to 6.2.0 ([#116](https://github.com/nativescript/nativescript-schematics/issues/116)) ([fe11520](https://github.com/nativescript/nativescript-schematics/commit/fe11520))


> Special thanks to [steadycoding](https://github.com/steadycoding)!


<a name="0.3.0"></a>
# [0.3.0](https://github.com/nativescript/nativescript-schematics/compare/0.3.0-rc.1...0.3.0) (2018-09-10)


### Bug Fixes

* bump versions to official Angular CLI 6.2 ([#109](https://github.com/nativescript/nativescript-schematics/issues/109)) ([490a647](https://github.com/nativescript/nativescript-schematics/commit/490a647))
* newly created projects run with AoT ([#111](https://github.com/nativescript/nativescript-schematics/issues/111)) ([b977c94](https://github.com/nativescript/nativescript-schematics/commit/b977c94))
* strip .ts extension when importing components ([#112](https://github.com/nativescript/nativescript-schematics/issues/112)) ([dd23c8a](https://github.com/nativescript/nativescript-schematics/commit/dd23c8a))
* **add-ns:** import AutoGeneratedComponent instead of HomeComponent ([#113](https://github.com/nativescript/nativescript-schematics/issues/113)) ([31bb7f5](https://github.com/nativescript/nativescript-schematics/commit/31bb7f5))



<a name="0.3.0-rc.1"></a>
# [0.3.0-rc.1](https://github.com/nativescript/nativescript-schematics/compare/0.3.0-rc.0...0.3.0-rc.1) (2018-09-06)


### Bug Fixes

* include .ts template files in the node package ([#107](https://github.com/nativescript/nativescript-schematics/issues/107)) ([d9bc64c](https://github.com/nativescript/nativescript-schematics/commit/d9bc64c))



<a name="0.3.0-rc.0"></a>
# [0.3.0-rc.0](https://github.com/nativescript/nativescript-schematics/compare/0.2.4...v0.3.0-rc.0) (2018-09-04)


### Bug Fixes

* respect extensions and module imports when generating components ([13516d6](https://github.com/nativescript/nativescript-schematics/commit/13516d6)), closes [#78](https://github.com/nativescript/nativescript-schematics/issues/78) [#54](https://github.com/nativescript/nativescript-schematics/issues/54)
* **add-ns:** choose a more generic name for the generated shared ([#103](https://github.com/nativescript/nativescript-schematics/issues/103)) ([991aec2](https://github.com/nativescript/nativescript-schematics/commit/991aec2)), closes [#99](https://github.com/nativescript/nativescript-schematics/issues/99)
* **add-ns:** use the package installation task from schematics ([9e63508](https://github.com/nativescript/nativescript-schematics/commit/9e63508)), closes [#94](https://github.com/nativescript/nativescript-schematics/issues/94)
* **component:** don't declare component in web module if it's not shared ([8a2388f](https://github.com/nativescript/nativescript-schematics/commit/8a2388f))
* **module:** prevents file module merge collisions ([a74c6a0](https://github.com/nativescript/nativescript-schematics/commit/a74c6a0))
* **module:** stop generating common files in web/ns only cases ([63d6b5a](https://github.com/nativescript/nativescript-schematics/commit/63d6b5a))
* **node-utils:** add safety checks to version parser ([8a4775d](https://github.com/nativescript/nativescript-schematics/commit/8a4775d))


### Features

* add travis ci ([#73](https://github.com/nativescript/nativescript-schematics/issues/73)) ([a63b411](https://github.com/nativescript/nativescript-schematics/commit/a63b411))
* **component:** generate mobile stylesheets files ([#87](https://github.com/nativescript/nativescript-schematics/issues/87)) ([7d7930b](https://github.com/nativescript/nativescript-schematics/commit/7d7930b))
* **migrate-component:** copy the web template into the migrated component ([#65](https://github.com/nativescript/nativescript-schematics/issues/65)) ([ad08b25](https://github.com/nativescript/nativescript-schematics/commit/ad08b25))
* init git repository when creating new application ([#104](https://github.com/nativescript/nativescript-schematics/issues/104)) ([a745640](https://github.com/nativescript/nativescript-schematics/commit/a745640)), closes [#95](https://github.com/nativescript/nativescript-schematics/issues/95)


<a name="0.2.5"></a>
## [0.2.5](https://github.com/nativescript/nativescript-schematics/compare/0.2.4...0.2.5) (2018-08-11)


### Features

* **migrate-component:** copy the web template into the migrated component ([#65](https://github.com/nativescript/nativescript-schematics/issues/65)) ([ad08b25](https://github.com/nativescript/nativescript-schematics/commit/ad08b25))


<a name="0.2.4"></a>
## [0.2.4](https://github.com/nativescript/nativescript-schematics/compare/0.2.3...0.2.4) (2018-08-02)


### Bug Fixes

* **add-ns:** exclude {N} files from web tsconfig ([9792a54](https://github.com/nativescript/nativescript-schematics/commit/9792a54)), closes [#56](https://github.com/nativescript/nativescript-schematics/issues/56)


### Features

* introduce --sample flag for `ng add` ([3c05fe4b556adde214dc880d4957c970e700eeed](https://github.com/NativeScript/nativescript-schematics/commit/3c05fe4b556adde214dc880d4957c970e700eeed))



<a name="0.2.3"></a>
## [0.2.3](https://github.com/nativescript/nativescript-schematics/compare/0.2.2...0.2.3) (2018-07-31)


### Bug Fixes

* ignore spec files when building for mobile ([08ede96](https://github.com/nativescript/nativescript-schematics/commit/08ede96))
* **application:** respect the provided style extension ([0249f06](https://github.com/nativescript/nativescript-schematics/commit/0249f06))


### Features

* add webpack flag to the application schematics ([258ddb1](https://github.com/nativescript/nativescript-schematics/commit/258ddb1))
* have routing by default for new applications ([cc320ed](https://github.com/nativescript/nativescript-schematics/commit/cc320ed))
* introduce --sample flag for `ng new --shared` ([528701b](https://github.com/nativescript/nativescript-schematics/commit/528701b))



<a name="0.2.2"></a>
## [0.2.2](https://github.com/nativescript/nativescript-schematics/compare/0.2.1...0.2.2) (2018-07-26)


### Bug Fixes

* Target official Angular 6.1 versions


<a name="0.2.1"></a>
## [0.2.1](https://github.com/nativescript/nativescript-schematics/compare/0.2.0...0.2.1) (2018-07-25)


### Bug Fixes

* wrong noop import ([2e956bf](https://github.com/nativescript/nativescript-schematics/commit/2e956bf))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/nativescript/nativescript-schematics/compare/0.1.7...0.2.0) (2018-07-25)


### Bug Fixes

* module.id issue in code sharing projects ([#43](https://github.com/nativescript/nativescript-schematics/issues/43)) ([9325ff3](https://github.com/nativescript/nativescript-schematics/commit/9325ff3)), closes [#40](https://github.com/nativescript/nativescript-schematics/issues/40)
* skip move path is '' ([c06187d](https://github.com/nativescript/nativescript-schematics/commit/c06187d))
* skip rename when web extension not provided ([3eede03](https://github.com/nativescript/nativescript-schematics/commit/3eede03))



<a name="0.1.7"></a>
## [0.1.7](https://github.com/nativescript/nativescript-schematics/compare/0.1.5...0.1.7) (2018-07-19)


### Bug Fixes

* module.id issue in code sharing projects ([#43](https://github.com/nativescript/nativescript-schematics/issues/43)) ([9325ff3](https://github.com/nativescript/nativescript-schematics/commit/9325ff3)), closes [#40](https://github.com/nativescript/nativescript-schematics/issues/40)



<a name="0.1.6"></a>
## [0.1.6](https://github.com/nativescript/nativescript-schematics/compare/0.1.5...0.1.6) (2018-07-19)


### Features

* **ng-new:** support --style=scss option 
* **ng-new:** support --no-theme flag 


<a name="0.1.5"></a>
## [0.1.5](https://github.com/nativescript/nativescript-schematics/compare/0.1.4...0.1.5) (2018-07-06)


### Bug Fixes

* **ng-new:** add nativescript-dev-sass to dependencies ([#32](https://github.com/nativescript/nativescript-schematics/issues/32)) ([1f3ec65](https://github.com/nativescript/nativescript-schematics/commit/1f3ec65)), closes [#30](https://github.com/nativescript/nativescript-schematics/issues/30)



<a name="0.1.4"></a>
## [0.1.4](https://github.com/nativescript/nativescript-schematics/compare/0.1.3...0.1.4) (2018-07-05)

### Bug Fixes

* Add NativeScriptFormsModule and NativeScriptHttpClientModule to app.module for {N}
* tsconfig issues


<a name="0.1.3"></a>
## [0.1.3](https://github.com/nativescript/nativescript-schematics/compare/0.1.1...0.1.3) (2018-06-11)


### Bug Fixes

* fix: target official {N} webpack version ([a7a36c3](https://github.com/nativescript/nativescript-schematics/commit/a7a36c3))


<a name="0.1.1"></a>
## [0.1.1](https://github.com/nativescript/nativescript-schematics/compare/0.0.9...0.1.1) (2018-06-11)


### Bug Fixes

* import utils/angular-project-parser from the right paths ([14ddd8a](https://github.com/nativescript/nativescript-schematics/commit/14ddd8a))
* remove __sourcedir__ folder in _ns_files ([26a3ef6](https://github.com/nativescript/nativescript-schematics/commit/26a3ef6))


### Features

* add migration schematic from {N} to web+{N} shared project ([#3](https://github.com/nativescript/nativescript-schematics/issues/3)) ([5e5161c](https://github.com/nativescript/nativescript-schematics/commit/5e5161c))
* add schematic for fixing module imports in feature modules ([180d27a](https://github.com/nativescript/nativescript-schematics/commit/180d27a))



<a name="0.1.0"></a>
# [0.1.0](https://github.com/nativescript/nativescript-schematics/compare/0.0.9...0.1.0) (2018-05-30)


### Bug Fixes

* import utils/angular-project-parser from the right paths ([14ddd8a](https://github.com/nativescript/nativescript-schematics/commit/14ddd8a))
* remove __sourcedir__ folder in _ns_files ([26a3ef6](https://github.com/nativescript/nativescript-schematics/commit/26a3ef6))


### Features

* add support for Angular 6
* add migration schematic from {N} to web+{N} shared project ([#3](https://github.com/nativescript/nativescript-schematics/issues/3)) ([5e5161c](https://github.com/nativescript/nativescript-schematics/commit/5e5161c))
* add schematic for fixing module imports in feature modules ([180d27a](https://github.com/nativescript/nativescript-schematics/commit/180d27a))
* add migrate component schematic ([0fd34f97fda7994aa3ca8a6b8d9bb27b5b56d98e](https://github.com/nativescript/nativescript-schematics/commit/0fd34f97fda7994aa3ca8a6b8d9bb27b5b56d98e))



