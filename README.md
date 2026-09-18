# IKITheFox-Codex-Pet

**English** | [简体中文](README.zh-CN.md)

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

1. Download the latest [ikithefox-pet.zip](https://github.com/IKITheFox/IKITheFox-Codex-Pet/releases/latest/download/ikithefox-pet.zip) from [Releases](https://github.com/IKITheFox/IKITheFox-Codex-Pet/releases/latest).
2. Extract `pet.json` and `spritesheet.webp` into the same directory:
   - Windows: `%USERPROFILE%\.codex\pets\ikithefox\`
   - macOS: `~/.codex/pets/ikithefox/`
3. Open **Settings > Pets**, select **Refresh**, and choose **IKITheFox**.

Keep the two files directly inside `ikithefox`, without an extra nested directory.

To update, replace both files and refresh. Back up the previous version first.

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
- [Releases](https://github.com/IKITheFox/IKITheFox-Codex-Pet/releases/latest): ready-to-extract `ikithefox-pet.zip` installation package.
- `assets/`: animated previews.

This package uses `spriteVersionNumber: 2`. It does not change the app's frame rate or task-state logic.

Character: **IKITheFox**. Sprite artwork generated and refined with OpenAI image generation tools.

See the [official pets documentation](https://learn.chatgpt.com/docs/pets) for app controls and customization.
