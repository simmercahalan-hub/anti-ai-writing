# Hermes注册坑点

## 已知问题

1. **文件名必须为 SKILL.md**，不能是其他名称
2. **YAML frontmatter 必须以 `---` 开头和结尾**
3. **description 字段不能为空**
4. **name 字段不能重复** — 同名 skill 会被覆盖
5. **allowed-tools 列出的是允许的工具** — 不在列表的工具不可使用
6. **compatibility 字段** — 列出支持的平台，不影响功能但影响展示

## 注册检查清单

- [ ] 文件名：`SKILL.md`
- [ ] frontmatter：`---` 开头和结尾
- [ ] `name:` 字段唯一
- [ ] `description:` 有内容
- [ ] `allowed-tools:` 包含所需工具
- [ ] 文件放在正确目录