# 智能体三省六部制（sanzing-liubu）

这是一个只含技能、不带联网服务的 [Agent Plugin](https://cursor.com/docs/plugins)。内容与账号里已在使用的「智能体三省六部制」技能一致，用来按零级用户、一级两相、二级三省、三级六部组织智能体工作。

## 目录

```
sanzing-liubu/
├── plugin.json
├── LICENSE
├── README.md
└── skills/
    └── sanzing-liubu/
        └── SKILL.md
```

- 插件标识：`sanzing-liubu`（1.0.0）
- 技能标识：`sanzing-liubu`（对话里标题仍是「智能体三省六部制」）
- 作者栏暂写为 `yanghe152326`，许可证为 MIT；上架或公开前可按需要修改这两处，并补上 logo。

## 在 Cursor 里本地试装

1. 把本目录复制到 `~/.cursor/plugins/local/sanzing-liubu`，并保持根目录有 `plugin.json`。
2. 重启 Cursor，或执行 `Developer: Reload Window`。
3. 打开 Customize，确认插件和技能已出现。

Grok Bot 这边目前仍使用账号里的共享技能；把本包装成官方市场插件并审核通过后，安装到的才是只读插件技能。

## 若要提交到官方市场

1. 把本目录放到一个公开 Git 仓库。
2. 按需补上 1:1 的 logo，并在 `plugin.json` 里用相对路径引用。
3. 到 [Cursor 插件市场提交页](https://cursor.com/marketplace/publish) 提交仓库地址，等待人工审核。市场上架的插件需要开源。

更完整的格式说明见 [Plugins](https://cursor.com/docs/plugins) 和 [Plugins reference](https://cursor.com/docs/reference/plugins)。
