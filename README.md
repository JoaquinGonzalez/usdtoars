# USDTOARS

Simple script to get/convert the official and blue exchange of dollar in Argentina

## Usage
```
Usage: usdtoars <option> <value>
-a,--autoupdate        Autoupdate
-u,--update            Force Update
--get-official         Show official exchange value
--get-blue             Show blue exchange value
--use-official         Use official value to convert
--use-blue             Use blue value to convert
--use-ars              Convert from ars to usd official
--use-ars-blue         Convert from ars to usd blue
```
## Example
```
$ usdtoars --get-official
102,97
```
```
$ usdtoars --use-official 1390
141780
```
