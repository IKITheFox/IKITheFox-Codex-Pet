# IKITheFox-Codex-Pet

[English](README.md) | **简体中文**

为 Codex 制作的自定义狐狸桌宠，拥有工位主题动画和丰富的动作表情。

你好，我是 IKITheFox，陪你写代码的小狐狸。

## 动画预览

| 趴桌小憩 | 专心工作 |
| --- | --- |
| ![坐在工位上趴桌睡觉](assets/idle.gif) | ![在电脑前敲击键盘](assets/running.gif) |

| 等待回应 | 被轻轻提起 |
| --- | --- |
| ![坐在工位上挥手引起注意](assets/waiting.gif) | ![四肢自然垂落，不显示提起的手](assets/jumping.gif) |

预览使用 Codex 宠物格式定义的每帧时长。实际显示哪个动作，以及动作如何播放，由应用控制。

## 安装

1. 从 [Releases 最新版](https://github.com/IKITheFox/IKITheFox-Codex-Pet/releases/latest)下载 [ikithefox-pet.zip](https://github.com/IKITheFox/IKITheFox-Codex-Pet/releases/latest/download/ikithefox-pet.zip)。
2. 将 `pet.json` 和 `spritesheet.webp` 解压到下方对应系统的目录中。
3. 打开 **设置 > 宠物**，点击 **刷新**，选择 **IKITheFox**。

| 系统 | 安装目录 |
| --- | --- |
| Windows | `%USERPROFILE%\.codex\pets\ikithefox\` |
| macOS | `~/.codex/pets/ikithefox/` |

两个文件应直接位于 `ikithefox` 文件夹中，不要额外嵌套一层目录。

更新时，替换这两个文件并刷新即可。建议先备份旧版。

## 动作说明

| 状态 | 动画表现 |
| --- | --- |
| `idle` | 坐在工位上趴桌睡觉，不显示加载图标 |
| `running` | 在电脑前工作、敲击键盘 |
| `waiting` | 坐在工位上挥手，等待你的回应 |
| `failed` | 耳朵塌下，举着带红色叉号的牌子 |
| `review` | 在工位上查看已完成的工作 |
| `waving` | 使用同一只爪子小幅挥手打招呼 |
| `jumping` | 被轻轻提起、自然悬垂的姿势，不显示提起的手 |
| `running-left`、`running-right` | 向左、向右移动 |
| 视线方向 | 16 个方向，保持身体正面稳定，通过头部和眼睛表达朝向 |

## 文件说明

- `pet.json`：宠物名称、简介及格式元数据。
- `spritesheet.webp`：透明背景动画图集，尺寸为 1536 × 2288 像素，共 8 列 × 11 行，每格 192 × 208 像素。
- [Releases](https://github.com/IKITheFox/IKITheFox-Codex-Pet/releases/latest)：提供可直接解压安装的 `ikithefox-pet.zip` 压缩包。
- `assets/`：动画预览文件。

本安装包使用 `spriteVersionNumber: 2`，不会修改应用自身的帧率或任务状态切换逻辑。

角色：**IKITheFox**。动画素材使用 OpenAI 图像生成工具制作并优化。

应用操作和自定义功能请参阅[官方宠物文档](https://learn.chatgpt.com/docs/pets)。
