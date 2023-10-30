## What is this

A simple cjs wrapper to the [del](https://github.com/sindresorhus/del) module

## Why make a wrapper ?

Since version 7 of del, the module [only supports esm import](https://github.com/sindresorhus/del/issues/138#issuecomment-1074678507).
In order to continue using this module conveniently I decided to wrap it in [fix-esm](https://www.npmjs.com/package/fix-esm).

## Why declare del as a peer dependency ?

Doing this allows you to decide the version of del in your project.
