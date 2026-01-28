---
name: 根据schema生成统一格式的typebox
description: 根据统一dirzzle-orm的schema文件生成固定格式的typebox类型文件
---

# 根据schema生成统一格式的typebox

## Instructions

寻找schema文件，根据schema文件生成固定结构typebox类型文件
- 关键字：Insert、UpdateBase、Select、Create、Update、Entity、Patch、BusinessQuery
- 统一返回同名的schema和type ，[实体名字]TModel
- 根据api接口组合不同实体生成需要的elysia接口schema
- 中间表的database schema不要生成model文件
- 项目的默认规范是将所有的database schema集中在一个文件名为table.schema.ts，所有的关系在table.relation.ts文件中定义
- 根据关系把不同实体的model文件放在一个文件夹中，一个model一个文件。
## 依赖
- drizzle-typebox
- dirzzle-orm 的实体
- elysia

## Examples
广告实体示例：[链接文字](./Examples.md)
