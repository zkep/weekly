---
title: clir 零依赖命令行工具
date: 2024-05-03 22:28:35
tags:
---

#### 背景
   最近在学习使用 [wails](https://github.com/wailsapp/wails),一个基于go和web的技术的桌面端框架， 目前有22.3k的star数量，算是一个比较 成熟和流行的开源项目了，该框架的命令行代码 [clir](https://github.com/leaanthony/clir) 实现很简洁和实用，但是使用中发现该命令行框架缺少 一些实现，经过一个下午的时间，我提交了一个版本的实现，目前作者已经review完代码，并对我的一些文本上（英语）的错误进行了修正，并对我的实现表示了 感谢🙏，也很高兴能参与到比较流行的开源项目中来

#### PR详情
提交的[PR](https://github.com/leaanthony/clir/pull/23)详情，目前PR已经被作者做了一些修正，正在等待作者合并到主分支。


下面是作者添加的Changelog： 

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

- `Added` for new features.
- `Changed` for changes in existing functionality.
- `Deprecated` for soon-to-be removed features.
- `Removed` for now removed features.
- `Fixed` for any bug fixes.
- `Security` in case of vulnerabilities.

## [Unreleased]

### Added
- Added support for slice flags. Added by @zkep in [PR](https://github.com/leaanthony/clir/pull/23)

### Fixed

### Changed

![](/images/clir/pr.png)


    

