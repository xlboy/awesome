# Awesome

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

一个与小伙伴们共建的资源收集库，大致的资源方向为**前后端**，以及**不错的工具、文章**等等。

如果面前的你对此库有着独特的想法（分享资源等等），那么欢迎进一步交流~

## 目录

- [TypeScript](#typescript)
  - [rimbu](#rimbu)
  - [type-fest](#type-fest)
  - [ts-toolbelt](#ts-toolbelt)
  - [utility-types](#utility-types)
  - [esno](#esno)
  - [esbuild-runner](#esbuild-runner)
  - [ts-node](#ts-node)
  - [tsup](#tsup)
  - [type-challenges](#type-challenges)
  - [typescript-tutorial](#typescript-tutorial)
  - [type-chess](#type-chess)
  - [typetype](#typetype)
  - [newtype-ts](#newtype-ts)
  - [typedi](#typedi)
  - [ts-prune](#ts-prune)
  - [ts-unused-exports](#ts-unused-exports)
  - [ts-morph](#ts-morph)
  - [ts-transformer-keys](#ts-transformer-keys)
  - [typescript-transform-paths](#typescript-transform-paths)
  - [json-to-ts](#json-to-ts)
  - [json-schema-to-ts](#json-schema-to-ts)
  - [tsconfck](#tsconfck)
- [Architecture](#architecture)
  - [react-with-clean-architecture](#react-with-clean-architecture)
- [Frontend](#frontend)
  - [kbar](#kbar)
  - [bem-ts](#bem-ts)
- [Other](#other)
  - [bem-guide](#bem-guide)

### TypeScript

#### [rimbu](https://github.com/rimbu-org/rimbu)

> 关键字：类型库、类型集合、不可变类型、类型工具、类型安全、类型运算

一个 TypeScript 类型库，专注于不可变、高性能和类型安全的集合和其他工具。

#### [type-fest](https://github.com/sindresorhus/type-fest)

> 关键字：类型库、类型集合、类型工具

一个基本的 TypeScript 类型集合库。

#### [ts-toolbelt](https://github.com/millsp/ts-toolbelt)

> 关键字：类型库、类型集合、类型工具

一个较为丰富的 TypeScript **类型集合**库，封装有各种**实用的类型**。

#### [utility-types](https://github.com/piotrwitek/utility-types)

> 关键字：类型库、类型集合、类型工具

一个早些年的基本的 TypeScript **类型集合**库。

#### [esno](https://github.com/antfu/esno)

> 关键字：运行 ts、执行 ts、esbuild、执行 node、执行 esnext、运行 node、运行 esnext

一个由 **esbuild** 提供支持的 TypeScript / ESNext Node**运行工具**。

#### [esbuild-runner](https://github.com/folke/esbuild-runner)

> 关键字：执行 ts、运行 ts、esbuild、编译 ts、编译 tsx、编译 js

使用 **esbuild** 对现代 JS、TypeScript 和 JSX 进行**超快速**的即时编译

#### [ts-node](https://github.com/TypeStrong/ts-node)

> 关键字：执行 ts、运行 ts、REPL

TypeScript 的 **执行** 和 **REPL**。

#### [tsup](https://github.com/egoist/tsup)

> 关键字：编译 ts、打包 ts、esbuild

一个针对 TypeScript 库的**打包工具**，0 配置，由 **esbuild** 提供支持。

#### [type-challenges](https://github.com/type-challenges/type-challenges)

> 关键字：ts 进阶、ts 练习、ts 学习、ts 做题、ts 题目

一个围绕着 TypeScript 类型的题目集合，以做题闯关的形式进行学习。

#### [typescript-tutorial](https://github.com/xcatliu/typescript-tutorial)

> 关键字：ts 入门、ts 教程、ts 学习

TypeScript 入门教程。从 JavaScript 程序员的角度总结思考，循序渐进的理解 TypeScript。

#### [type-chess](https://github.com/chinese-chess-everywhere/type-chess)

> 关键字：ts 进阶、ts 体操、ts 象棋

一个用 TypeScript 类型运算实现的中国象棋程序。（开眼界、大千世界无所不能系列）

#### [typetype](https://github.com/mistlog/typetype)

> 关键字：ts 体操、ts 二次转译、基于 ts 的语言、ast

一个为 TypeScript 类型生成而设计的编程语言。（写起类型体操时，再也不会对三目〔extends〕麻木啦）

#### [newtype-ts](https://github.com/gcanti/newtype-ts)

> 关键字：类型安全、类型唯一、类型唯一标识

在 TypeScript 中实现新类型（类型唯一标识，运行时为某值，开发时为唯一类型值，犹如 symbol 般）。

#### [typedi](https://github.com/typestack/typedi)

> 关键字：class 依赖注入、ts 依赖注入、js 依赖注入

简单而强大的 JavaScript 和 TypeScript 的依赖注入工具。

#### [ts-prune](https://github.com/nadeesha/ts-prune)

> 关键字：ts 工程化、ts 未导出、ts 未使用

在 TypeScript 项目中查找未使用的导出。

#### [ts-unused-exports](https://github.com/pzavolinsky/ts-unused-exports)

> 关键字：ts 工程化、ts 未导出、ts 未使用

在 TypeScript 项目中查找未使用的导出。

#### [ts-morph](https://github.com/dsherret/ts-morph)

> 关键字：ts 源码修改、源码处理、源码过滤、ts-ast

TypeScript 编译器 API 包装器，用于静态分析和程序化代码修改。

#### [ts-transformer-keys](https://github.com/kimamula/ts-transformer-keys)

> 关键字：ts-ast、ts-runtime、ts 转换、源码处理、源码过滤、ts 源码修改

一个 TypeScript 的自定义转换程序，能够在 js runtime 获得指定 TypeScript 类型的键。

#### [typescript-transform-paths](https://github.com/LeDDGroup/typescript-transform-paths)

> 关键字：ts-path-resolve、ts 路径处理、ts 路径解析

使用 TypeScript 路径映射 和 / 或 自定义路径 来转换模块的解析路径。

#### [json-to-ts](https://github.com/MariusAlch/json-to-ts)

> 关键字：json-to-type、json-to-ts、json 生成类型、自动生成类型、类型生成、自动生成类型、类型转换

将 JSON 对象转换为 TypeScript 类型。

#### [json-schema-to-ts](https://github.com/ThomasAribart/json-schema-to-ts)

> 关键字：json-schema-to-type、json-schema-to-ts、json 生成类型

从 JSON Schema 中推导出 TypeScript 类型。

#### [tsconfck](https://github.com/dominikg/tsconfck)

> 关键字：tsconfig 处理、tsconfig 查找、tsconfig 解析

无需依赖 TypeScript ，即可查找和解析 tsconfig 文件的实用程序。

### Architecture

#### [react-with-clean-architecture](https://github.com/falsy/react-with-clean-architecture)

> 关键字：react-architecture、clean-architecture、整洁架构、react 架构、react 整洁架构

基于整洁架构的 React 项目示例。

### Frontend

#### [kbar](https://github.com/falsy/react-with-clean-architecture)

> 关键字：站内搜索、搜索界面、搜索窗口、ctrl+k、command+k

一个简单的即插即用的 React 组件，可以在网站里添加一个快速、便携、可扩展的 command + k 搜索界面。

#### [bem-ts](https://github.com/ybiquitous/bem-ts)

> 关键字：bem 工具、工程质量、命名风格

一个 TypeScript 支持完好的 BEM 类名生成器

### Other

#### [bem-guide](https://en.bem.info/methodology/quick-start/)

> 关键字：bem 工具、bem 指南、bem 教程、工程质量、命名风格

BEM (Block, Element, Modifier) 指南网站、教程网站。
