Change Log
==========

## 3.29.0
- [SQLite 3.29.0](http://sqlite.org/releaselog/3_29_0.html)

## 3.28.0
- [SQLite 3.28.0](http://sqlite.org/releaselog/3_28_0.html)

## 3.27.2
- [SQLite 3.27.2](http://sqlite.org/releaselog/3_27_2.html)

## 3.27.1
- [SQLite 3.27.1](http://sqlite.org/releaselog/3_27_1.html)

## 3.26.0
- [SQLite 3.26.0](http://sqlite.org/releaselog/3_26_0.html)
- Update `org.apache.httpcomponents:httpclient` dependency to 4.5.6
- Update `com.android.tools.build:gradle` dependency to 3.2.1
- Update gradle to 4.10.2
- Update `androidx.core:core` dependency to 1.0.1
- Switch to androidx for test libraries

## 3.25.3

- [SQLite 3.25.3](http://sqlite.org/releaselog/3_25_3.html)
- Switch to androidx libraries
- Remove mips abi support
- Fix hash collision in SQLiteCursor

## 3.25.2

- [SQLite 3.25.2](http://sqlite.org/releaselog/3_25_2.html)

## 3.25.1

- [SQLite 3.25.1](http://sqlite.org/releaselog/3_25_1.html)

## 3.24.0

- [SQLite 3.24.0](http://sqlite.org/releaselog/3_24_0.html)

## 3.23.1

- [SQLite 3.23.1](http://sqlite.org/releaselog/3_23_1.html)
- Add new enhanced custom function interfaces and methods

## 3.22.0

- [SQLite 3.22.0](https://sqlite.org/releaselog/3_22_0.html)
- Update `android.arch.persistence:db` dependency to `1.0.0`
- Improved error messaging on loading custom extensions
- Increase CursorWindow size to match AOSP
- Add custom extension and function loading to new SupportSQLiteDatabase API

## 3.21.0

- [SQLite 3.21.0](https://sqlite.org/releaselog/3_21_0.html)
- Support SupportSQLiteDatabase interfaces provided in `android.arch.persistence:db`
- Support MIPS abi
- Fix local reference overflow when using custom functions

## 3.20.1

- [SQLite 3.20.1](https://sqlite.org/releaselog/3_20_1.html)

## 3.20.0

- [SQLite 3.20.0](https://sqlite.org/releaselog/3_20_0.html)

## 3.19.3

- [SQLite 3.19.3](https://sqlite.org/releaselog/3_19_3.html)
- Add flags for enhanced FTS query syntax

## 3.19.2

- [SQLite 3.19.2](https://sqlite.org/releaselog/3_19_2.html)

## 3.18.0

- [SQLite 3.18.0](https://sqlite.org/releaselog/3_18_0.html)
- Fix conversion of strings larger than the available stack size (#35)

## 3.17.0

- [SQLite 3.17.0](https://sqlite.org/releaselog/3_17_0.html)

## 3.16.2

- [SQLite 3.16.2](https://sqlite.org/releaselog/3_16_2.html)
- Support additional SQLite open flags
- Add methods from DatabaseUtils into base classes

## 3.16.0

- [SQLite 3.16.0](https://sqlite.org/releaselog/3_16_0.html)

## 3.15.1

- [SQLite 3.15.1](https://sqlite.org/releaselog/3_15_1.html)

## 3.15.0

- [SQLite 3.15.0](https://www.sqlite.org/releaselog/3_15_0.html)

## 3.14.2

- [SQLite 3.14.2](https://www.sqlite.org/releaselog/3_14_2.html)
- Removed code that disabled WAL when executing a ATTACH statement

## 3.14.1

- [SQLite 3.14.1](https://www.sqlite.org/releaselog/3_14_1.html)

## 3.14.0

- [SQLite 3.14.0](https://www.sqlite.org/releaselog/3_14.html)
- Support return value in `SQLiteDatabase.CustomFunction`
- Support `Object[]` array in `SQLiteDatabase` query methods

## 3.13.0-3

- Support x86_64 target

## 3.13.0-2

- More proguard rules fixes

## 3.13.0-1

- Fix proguard rules file

## 3.13.0

- [SQLite 3.13.0](https://www.sqlite.org/releaselog/3_13_0.html)
- Updated proguard rules

## 3.12.2-2

- Minimum API level supported is now 9 (Gingerbread) previously was 15 (ICS)
- Fix missing support lib dependency missing from maven POM publish

## 3.12.2-1

- Fix native error code SQLITE_CANTOPEN(14) creating a database for the first time
- Fix SQLiteOpenHelper setWriteAheadLoggingEnabled flag not passed to openDatabase
- Change SQLiteGlobal default config values to match Android defaults

## 3.12.2

- [SQLite 3.12.2](https://www.sqlite.org/releaselog/3_12_2.html)

## 3.12.1-1

- Fix CursorWindow deactivate/close
- Fix Cursor setNotificationUri not working

## 3.12.1

- [SQLite 3.12.1](https://www.sqlite.org/releaselog/3_12_1.html)
- Support runtime extension loading
- Support custom functions
- `beginTransactionDeferred`/`beginTransactionWithListenerDeferred` added
- `CancellationSignal` dependency changed to support-v4 from app-compat
- Sources included in artifacts

## 3.12.0

- Initial release with SQLite 3.12.0
