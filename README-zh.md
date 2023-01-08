# Medium Unlock
[English](https://github.com/yaaprogrammer/medium-unlock) | [中文](https://github.com/yaaprogrammer/medium-unlock/blob/main/README-zh.md)
___
自动检测Medium文章（包括子域名和自定义域名），替换URL为scribe.rip来解锁Medium付费文章
## 使用方法
点击文章页面出现的绿色悬浮球
## 插件原理
[scribe.rip](https://scribe.rip)

判断当前页是否为Medium文章，按照scribe.rip提供的方案替换url，通过访问scribe.rip来获得全文。

scribe.rip官方给出的自动化替换URL方式为[LibRedirect](https://libredirect.codeberg.page/)，但是在实际使用过程中体验不太好。

## 支持网站
- [Medium](https://medium.com)
  - medium.com
  - *.medium.com
    - james.medium.com
    - robert.medium.com
    - ...
  - custom domains
    - entrepreneurshandbook.co
    - ...

## 屏幕截图
![](https://raw.githubusercontent.com/yaaprogrammer/medium-unlock/main/image/example-pc.png)
![](https://raw.githubusercontent.com/yaaprogrammer/medium-unlock/main/image/example-mobile.png)

## LICENSE
[MIT LICENSE](https://mit-license.org/)

## Github
[medium-unlock](https://github.com/yaaprogrammer/medium-unlock)