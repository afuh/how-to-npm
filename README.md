# how-to-npm

https://github.com/workshopper/how-to-npm

### 01 Dev Environment   
```shell
$ npm init
```

### 02 Login
```shell
$ npm adduser
```

### 03 Start A Project  
```shell
$ npm init --scope=username
```

### 04 Install A Module
```shell
$ npm install @linclark/pkg
```

### 05 Listing Dependencies
```shell
$ npm ls
```
### 06 npm Test
```shell
$ touch test.js
```
### 07 Package Niceties  
complete the fields in the package.json

### 08 Publish
```shell
$ npm publish
```
### 09 Version
```shell
$ npm version minor -m "message"
```
### 10 Publish Again
```shell
$ npm publish
```
### 11 Dist Tag
```shell
$ npm dist-tag add @<username>/how-to-npm@1.0.0 beta
```
### 12 Dist Tag Removal
```shell
$ npm dist-tag rm @<username>/how-to-npm beta
$ npm dist-tag add @<username>/how-to-npm@1.0.0 latest
```
### 13 Outdated
```shell
$ npm outdated
$ how-to-npm verify @linclark/pkg
```
### 14 Update
```shell
$ npm update
```
### 15 rm
```shell
$ npm rm --save @linclark/pkg
```
