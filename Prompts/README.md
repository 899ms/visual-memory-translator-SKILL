# Standalone Prompts / 独立提示词

这些提示词可脱离 Skill 单独复制使用。上传参考照片后，选择一个文件，将其中整段提示词发送给支持图片编辑或参考图生成的模型。

| 文件 | 用途 | 默认比例 |
|---|---|---|
| [01-editorial-memory-page.md](01-editorial-memory-page.md) | 通用上下影像转译 | 3:4 |
| [02-abstract-color-blocks.md](02-abstract-color-blocks.md) | 上方摄影、下方抽象色块 | 3:4 |
| [03-exhibition-ticket.md](03-exhibition-ticket.md) | 收藏级私人展览票 | 3:4 |
| [04-banknote-specimen.md](04-banknote-specimen.md) | 纸币样张 | 3:4 |
| [05-banknote-in-situ.md](05-banknote-in-situ.md) | 同场景手持纸币 | 3:4 |
| [06-central-in-place-stamp.md](06-central-in-place-stamp.md) | 中央区域原位风格化邮票 | 3:4 |
| [07-vinyl-record-in-situ.md](07-vinyl-record-in-situ.md) | 唱片店黑胶专辑实景 | 1:2 |
| [08-style-preview-grid.md](08-style-preview-grid.md) | 先生成 4/6/9 格方向预览 | 依原图 |

带 `{{...}}` 的字段可以填写；不填写时让模型根据参考图判断。除风格预览外，所有提示词都要求只输出最终合成图，不展示步骤图。
