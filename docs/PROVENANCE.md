# 来源与开源核查

核查日期：2026-10-30。

## 已知与未知

维护者确认这四个 MBA Skill 改写自 [garrytan/gstack](https://github.com/garrytan/gstack)，不记得具体 Skill 和版本。因此原始上游提交记为未知，不能声称逐行追溯完成。

本次核查时上游 main 为 `b61744517cc35b3109f06a54d64857be27f60c4e`。核查了上游 LICENSE、NOTICE.md、office-hours 与 plan-ceo-review 的当前内容：前提挑战、备选方案、逐步提问、完成状态等结构与 MBA 版本有可比性，但这只能说明设计上的联系，不能证明具体历史复制关系。

独立包来自 Lumior 现有四份 Skill：topic 0.3.0、lit 0.4.0、review 0.2.0、proposal 0.2.0。来源文件哈希见 [清单](source-manifest.json)。独立包新增署名头与许可副本，修正文献 Skill 中“mba-review 尚未编写”的旧提示；没有改写核心指导流程。

## 许可结论

[上游 MIT 许可证](https://github.com/garrytan/gstack/blob/b61744517cc35b3109f06a54d64857be27f60c4e/LICENSE) 允许使用、修改和再分发，包括商业使用；分发上游内容或实质部分时需保留版权和许可声明。只写“灵感来自 gstack”不能替代完整许可。本包保留 Garry Tan 版权及 MIT 全文，并将项目新增/修改内容以 Apache-2.0 发布。这里是针对已查看文件的许可核查，不是对未知历史来源的无条件法律保证。

当前上游 [NOTICE.md](https://github.com/garrytan/gstack/blob/b61744517cc35b3109f06a54d64857be27f60c4e/NOTICE.md) 还列有其他第三方来源。不能据根目录 MIT 就断言其所有内容只有一种许可。本包没有复制那些工具或资源；若以后确认历史来源涉及其他条目，需要补齐对应许可，不能仅保留 gstack 署名。

现有 Lumior 社区仓库已经包含四个 Skill，因此同样需要补充 gstack 来源和 MIT 全文。独立仓库的声明不能替代原分发仓库的声明。

## 分发范围

仅包含四个 Skill、macOS PDF 文字提取辅助源码、写作设置模板及项目文档。没有学生资料、企业数据、论文 PDF、账号凭据或桌面运行时。使用者放入自己的 `thesis/` 目录不应上传公共仓库。

## 后续维护

新增内容注明来源；每次修改更新 CHANGELOG 和源文件哈希。若找回原始 gstack 版本，补全提交和文件映射；不要事后把核查版本写成原始版本。学术规范由使用者的学校决定，软件许可不能替代论文使用 AI 的规定。
