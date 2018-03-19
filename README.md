# multiple-realm
Testing dependencies on two versions of Realm JS

## Running `npm install` this is what I get

```
$ npm install

> realm@2.2.16 install [...]/multiple-realm/node_modules/realm
> node-pre-gyp install --fallback-to-build

[realm] Success: "[...]/multiple-realm/node_modules/realm/compiled/node-v57_darwin_x64/realm.node" is installed via remote

> realm@2.3.1 install [...]/multiple-realm/2.3.x/node_modules/realm
> node-pre-gyp install --fallback-to-build

sh: node-pre-gyp: command not found
npm WARN multiple-realm@0.1.0 No repository field.
npm WARN multiple-realm@0.1.0 No license field.

npm ERR! file sh
npm ERR! code ELIFECYCLE
npm ERR! errno ENOENT
npm ERR! syscall spawn
npm ERR! realm@2.3.1 install: `node-pre-gyp install --fallback-to-build`
npm ERR! spawn ENOENT
npm ERR!
npm ERR! Failed at the realm@2.3.1 install script.
npm ERR! This is probably not a problem with npm. There is likely additional logging output above.

npm ERR! A complete log of this run can be found in:
npm ERR!     ~/.npm/_logs/2018-03-19T08_46_57_868Z-debug.log
```
