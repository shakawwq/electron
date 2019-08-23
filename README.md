# Bidream Desktop App
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/shakawwq/electron)](https://github.com/shakawwq/electron/releases)
[![Build Status](https://travis-ci.com/shakawwq/electron.svg?branch=master)](https://travis-ci.com/shakawwq/electron)
[![Build status](https://ci.appveyor.com/api/projects/status/506nomvkwxhbfcec?svg=true)](https://ci.appveyor.com/project/shakawwq/electron)

### 打包发布
必须在GitHub Web通过[Draft a new Release](https://github.com/shakawwq/electron/releases/new)新建tag才能触发CI自动打包发布  
本地新建tag再push至github repo无法触发CI自动打包发布
- tag格式必须为 v主版本号.子版本号.修正版本号，例如v1.0.0
- 由 Travis 打包发布MacOS平台DMG文件
- 由 AppVeyor 打包发布Windows平台.exe文件
