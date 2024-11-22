---
title: 初始化项目时安装依赖报错
description:
date: 2024-07-26T11:00:00.000+00:00
lang: zh
duration: 5min
---

[[toc]]

> [!CAUTION] 错误
> Error: Could not load the "sharp" module using the darwin-arm64 runtime

错误通常发生在使用Apple Silicon（M1, M2等）处理器的Mac上，并且是因为sharp模块未正确编译或未找到适合该平台的预编译版本。

## 1、Error: Could not load the "sharp" module using the darwin-arm64 runtime

### 1. 安装node-gyp

首先，确保你已经安装了node-gyp，它是一个用于编译原生Addons的工具：

```shell
npm install -g node-gyp
```

### 2. 删除node_modules

```shell
rf -rm node_modules package-lock.json

```

### 3.重新安装依赖

```shell
pnpm i
```
