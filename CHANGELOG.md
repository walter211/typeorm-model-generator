# Changelog

## 0.2.21
* primary keys using identity/sequence are now generated with `@PrimaryGeneratedColumn` decorator [#96](https://github.com/Kononnable/typeorm-model-generator/issues/96)

## 0.2.20
* relation onUpdate fixes
* postgres support for citext, hstore, geometry, array column types
* upgraded typeorm version

## 0.2.19
* custom naming strategy fiexes
* dependencies update

## 0.2.18
* oracle output format fixed

## 0.2.17

* added support for relationId fields
* added support for custom naming entity fields
* removed oracledb from dependencies
* generating nullable column types for nullable columns
