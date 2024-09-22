---
title: wokwi-lcd2004 Reference
sidebar_label: wokwi-lcd2004
ㄷ채ㅜ엎ㄷ자ㅓㅑ둬ㅑㅓㅝㅁㄱㄴ야ㅜㅑ어먀우멒얖머ㅐㅜㅑㅁ얌ㅇ퍼ㅜㅑㅓㅍㅇㅁㅇㅁㅍㅇㅍㅁㅇㅍㅁㅇㅍㅇㅍㅇㅍㅁㅇㅁㅍㅇㅁㅍ
---

An LCD display with 4 lines, 20 characters per line.

<wokwi-lcd2004 text="    wokwi-lcd2004                          4x20 characters" />

This part has the same pins and attributes as the wokwi-lcd1602.

For **complete information and code examples**, please see the [wokwi-lcd1602 reference](wokwi-lcd1602).

### Examples

| Result                                                                | Attrs                                        |
| --------------------------------------------------------------------- | -------------------------------------------- |
| <wokwi-lcd2004 text="Hello World!" />                                 | `{ }`                                        |
| <wokwi-lcd2004 text="Hello World!" pins="i2c" />                      | `{ "pins": "i2c" }`                          |
| <wokwi-lcd2004 background="blue" color="white" text="Hello World!" /> | `{ "background": "blue", "color": "white" }` |

## Simulator examples

- [LCD2004 Tiny Pacman on Wokwi](https://wokwi.com/projects/294590769009787402)
