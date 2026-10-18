# Island Media Controls

> 从了解到 Windhawk，开始尝试写些 mod 来解决自己的需求，到现在短短四个月，第一个组件居然已经有了 27k 次下载。真的很感谢每一个愿意给 Island Media Controls 一次尝试，甚至选择长期使用的大家。
>
> 这是我自己每天都在用的组件，所以更新基本都出于自己的审美和需求。有了新点子，我还会继续更新；即便不甚活跃，也会检查收件箱，接收大家的反馈。但是请务必——别再在这个素材库里提交 PR 啦！反馈请到 [Windhawk 组件主页](https://windhawk.net/mods/island-media-controls)，代码 PR 请提交到 [Windhawk 模组仓库](https://github.com/ramensoftware/windhawk-mods/pulls)。走那边的模组渠道，我会更容易看到。非常感谢啦。

Bring the current media session into the Windows 11 taskbar as a compact,
clickable island. It shows the active track, artist, artwork, playback state,
and progress, then expands into a larger player with seek, previous,
play/pause, and next controls.

## Preview

Side expansion on a transparent taskbar, in dark mode. Island tint and breathing
lighting are disabled in both previews.

| Transparent borderless | Transparent |
| :---: | :---: |
| ![Transparent borderless side expansion, dark theme, tint and breathing lighting off](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/transparent-taskbar-borderless-dark.gif) | ![Transparent side expansion, dark theme, tint and breathing lighting off](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/transparent-taskbar-bordered-dark.gif) |

## Layout previews

| Layout / Material | Dark theme | Light theme |
| :--- | :---: | :---: |
| **Fullsize** · Liquid glass | ![liquid-glass-fullsize-dark](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/liquid-glass-fullsize-dark.gif) | ![liquid-glass-fullsize-light](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/liquid-glass-fullsize-light.gif) |
| **Fullsize** · Transparent borderless | ![transparent-borderless-fullsize-dark](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/transparent-borderless-fullsize-dark.gif) | ![transparent-borderless-fullsize-light](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/transparent-borderless-fullsize-light.gif) |
| **Compact** · Liquid glass | ![liquid-glass-compact-dark](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/liquid-glass-compact-dark.gif) | ![liquid-glass-compact-light](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/liquid-glass-compact-light.gif) |
| **Compact** · Transparent borderless | ![transparent-borderless-compact-dark](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/transparent-borderless-compact-dark.gif) | ![transparent-borderless-compact-light](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/transparent-borderless-compact-light.gif) |
| **Side expansion** · Liquid glass | ![liquid-glass-sideexpansion-dark](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/liquid-glass-sideexpansion-dark.gif) | ![liquid-glass-sideexpansion-light](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/liquid-glass-sideexpansion-light.gif) |
| **Side expansion** · Transparent borderless | ![transparent-borderless-sideexpansion-dark](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/transparent-borderless-sideexpansion-dark.gif) | ![transparent-borderless-sideexpansion-light](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/transparent-borderless-sideexpansion-light.gif) |
| **Side expansion · left vertical taskbar** · Liquid glass | ![liquid-glass-sideexpansion-left-dark](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/liquid-glass-sideexpansion-left-dark.gif) | ![liquid-glass-sideexpansion-left-light](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/liquid-glass-sideexpansion-left-light.gif) |
| **Side expansion · left vertical taskbar** · Transparent borderless | ![transparent-borderless-sideexpansion-left-dark](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/transparent-borderless-sideexpansion-left-dark.gif) | ![transparent-borderless-sideexpansion-left-light](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/layoutpreview/transparent-borderless-sideexpansion-left-light.gif) |

## What's new

- **Better Windows 11 taskbar integration**, with an optional disc-style main island.
- **More polished button styles**, plus an optional experimental glass button style.
- **A redesigned Compact layout** that makes better use of its smaller footprint.
- **Reworked materials**, with richer lighting and more intuitive interaction feedback.
- **Refined transition animations** for opening, closing, and everyday interactions.
- **A simpler, easier-to-use settings interface.**

## Features

- **A Dynamic Island-style media hub:** Bring your current song, artwork,
  progress, and playback controls into a small island on the Windows 11 taskbar.
- **Multiple layout styles:** Use a full expanded player, a tighter compact
  player, or a side-expansion mode that reveals quick controls next to the island.
- **Detailed layout customization:** Adjust the island size, expanded player
  size, cover behavior, background strength, button style, and animation feel to
  match your setup.
- **Flexible taskbar placement:** Place the island near the tray, beside the
  clock, or along the taskbar edge, with automatic sizing for different taskbar
  heights.
- **Smooth, playful animations:** Hover, click, expand, collapse, play/pause,
  and failed actions all respond with soft motion so the island feels alive
  instead of static.
- **Polished visual styles:** Choose from Mica-like, Acrylic, Liquid
  Glass, Transparent, and Transparent borderless materials, with album-color
  highlights and refined dark/light mode treatment.
- **Artwork that fits the moment:** Keep original thumbnails or replace rough
  browser/video artwork with generated abstract covers for a cleaner look.
- **Useful playback controls:** Open the player to seek through the track, switch
  songs, and control playback without leaving the taskbar.

> The island currently attaches to the primary taskbar. Taskbar placement
> follows the top, bottom, left, or right edge automatically. On a vertical
> taskbar, the island becomes an album button and opens toward the desktop;
> Side expansion stacks its original transport buttons downward near the top
> and upward near the bottom. Tray left/right and overlay
> left/right correspond to top/bottom on vertical taskbars.
>
> While the expanded player is open, glass and transparent materials use
> Windows Graphics Capture to blur the monitor content directly behind it.
> By default, the expanded player is hidden from screenshots, recordings, and
> screen sharing to prevent the blur from capturing itself. Enable **Expanded
> player capturable blurred backdrop** if it needs to appear in captures.

## 网易云音乐兼容性 / NetEase Cloud Music compatibility

网易云音乐的适配看来是个不小的问题。就我目前测试的情况而言，它没有通过 Windows 的系统媒体会话完整提供组件所需的信息，因此高清封面和播放进度都不方便直接获取。这里涉及的是 **系统媒体传输控件（SMTC）**，以及本组件用来读取媒体会话的 **GSMTC 接口**。目前我暂时还没有可靠的解决方案；如果有大佬了解这方面，请不吝赐教了 orz。

NetEase Cloud Music compatibility is proving tricky. In my testing, it does not expose all the information this mod needs through Windows media sessions, making high-resolution artwork and playback progress difficult to retrieve directly. These sessions use **System Media Transport Controls (SMTC)**, and this mod reads them through **GSMTC**. I do not have a reliable solution yet—if you know a way to improve this integration, I would really appreciate your advice. orz

## Material previews

| Material | Dark mode | Light mode |
| :--- | :---: | :---: |
| **Mica-like** | ![Mica-like material in dark mode](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/mica-dark.png) | ![Mica-like material in light mode](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/mica-light.png) |
| **Acrylic** | ![Acrylic material in dark mode](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/acrylic-dark.png) | ![Acrylic material in light mode](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/acrylic-light.png) |
| **Liquid Glass** | ![Liquid Glass material in dark mode](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/liquid-glass-dark.png) | ![Liquid Glass material in light mode](https://raw.githubusercontent.com/usho-lear/island-media-controls/main/previews/materials/liquid-glass-light.png) |
