## [0.6.4] - 2019-04-27

- revert problems with window

## [0.6.4] - 2019-04-27

- check if you are on node.js or not ...

## [0.6.3] - 2019-04-27

- use blockstack directly instead of userSession for getFile, putFile, deleteFile

## [0.6.3] - 2019-04-27

- make userSession public in blockstack provider

## [0.6.2] - 2019-04-27

- blockstack as a peer dependency

## [0.6.1] - 2019-03-28

- check if content is of type string before parsing it into a JSON Object

## [0.6.0] - 2019-03-07

- remove rxjs from indexer middleware

## [0.5.0] - 2019-12-13

- remove rxjs from indexer middleware

## [0.4.17] - 2019-12-13

- update secure-ls package to the latest version

## [0.4.16] - 2019-12-07

- export HashTableIndex in indexer middleware

## [0.4.15] - 2019-12-07

- improvements on the indexer middleware delete method

## [0.4.14] - 2019-11-29

- add secure property to indexer-middleware

## [0.4.11 & 0.4.12] - 2019-11-25

- added package indexer-middleware

## [0.4.11 & 0.4.12] - 2019-11-24

- make callbacks public again

## [0.4.10] - 2019-11-24

- origin can be of any type in StorageInfo

## [0.4.9] - 2019-11-24

- get some basic logging.

## [0.4.8] - 2019-11-24

- better handling when json is not available.

## [0.4.7] - 2019-11-24

- improvements on retrieving data from userSession

## [0.4.5 - 0.4.6] - 2019-11-24

- remove console.log in json middleware

## [0.4.4] - 2019-11-24

- remove console.log in json middleware

## [0.4.3] - 2019-11-23

- add allowSyntheticDefaultImports in blockstack-provider

## [0.4.2] - 2019-11-23

- remove localforage as dependency

## [0.4.1] - 2019-11-23

- change type of content from string to any in StorageInfo

## [0.4.0] - 2019-11-23

- use correct code with dist

## [0.3.0] - 2019-11-23

- add removeProvider, so you can easily remove a storage provider when needed
- use promises for set & delete instead of callbacks

## [0.2.0] - 2019-11-23

- add secure-ls to localstorage packages
- update typescript versions in all packages
- update implementation of blockstack.js to the latest version, use UserSession.