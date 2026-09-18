# IKITheFox-Codex-Pet
A custom fox desktop pet for Codex, with workstation animations and expressive reactions.

Hi, I'm IKITheFox, your little fox coding companion in Codex.

## Preview

| Taking a nap | Working |
| --- | --- |
| ![Sleeping at the workstation](assets/idle.gif) | ![Typing at the workstation](assets/running.gif) |

| Waiting for you | Picked up |
| --- | --- |
| ![Waving for attention](assets/waiting.gif) | ![Gently dangling without a visible hand](assets/jumping.gif) |

Previews use the frame durations defined by the Codex pet format. Actual state selection and playback are controlled by the app.

## Install

1. Download [ikithefox-pet.zip](ikithefox-pet.zip).
2. Extract `pet.json` and `spritesheet.webp` into the same directory:
   - Windows: `%USERPROFILE%\.codex\pets\ikithefox\`
   - macOS: `~/.codex/pets/ikithefox/`
3. Open **Settings > Pets**, select **Refresh**, and choose **IKITheFox**.

Keep the two files directly inside `ikithefox`, without an extra nested directory.

### 中文安装说明

下载上面的 ZIP，将 `pet.json` 和 `spritesheet.webp` 解压到用户目录下的 `.codex/pets/ikithefox/`，然后在 **设置 → 宠物 → 刷新** 中选择 **IKITheFox**。

更新时替换这两个文件并刷新即可；建议先备份旧版。

## Animations

| State | Artwork |
| --- | --- |
| `idle` | Sleeping at the workstation, with no loading indicator |
| `running` | Working at the computer |
| `waiting` | Waving at the workstation for attention |
| `failed` | Drooping ears and a held red-X sign |
| `review` | Inspecting completed work at the workstation |
| `waving` | A small, same-paw greeting |
| `jumping` | A hand-free, gently suspended pose |
| `running-left`, `running-right` | Directional movement |
| Look directions | 16 directions, with a stable frontal body and head/eye movement |

## Files

- `pet.json`: pet identity and format metadata.
- `spritesheet.webp`: transparent 1536 x 2288 atlas, 8 columns x 11 rows, with 192 x 208 cells.
- `ikithefox-pet.zip`: ready-to-extract installation package.
- `assets/`: animated previews.

This package uses `spriteVersionNumber: 2`. It does not change the app's frame rate or task-state logic.

Character: **IKITheFox**. Sprite artwork generated and refined with OpenAI image generation tools.

See the [official pets documentation](https://learn.chatgpt.com/docs/pets) for app controls and customization.
