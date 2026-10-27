# Better Unloaded Tabs

Makes unloaded tabs easier to notice by making them grayscale and transparent.

![Unloaded tabs](images/unloaded-tabs.png)

## Settings

Available in **Settings → Zen Mods → Better Unloaded Tabs**:

| Setting | Default | Description |
| --- | --- | --- |
| Opacity of unloaded tabs | `0.5` | Opacity from `0.0` (invisible) to `1.0` (fully opaque). |
| Grayscale unloaded tabs | on | Turns the grayscale filter on or off. |
| Grayscale strength | `1` | Grayscale amount from `0.0` (no effect) to `1.0` (fully grayscale). |

The defaults keep the original look.

## Installation

### Zen Mods

Install **Better Unloaded Tabs** from [Zen Mods](https://zen-browser.app/mods/f7c71d9a-bce2-420f-ae44-a64bd92975ab/).

### Manual

1. Copy `chrome.css` to your Zen profile's `chrome` folder.
2. Add `@import "chrome.css";` to `userChrome.css`.
3. Restart Zen.

Settings are only shown when the mod is installed through Zen Mods. With a manual install, the defaults apply and the preferences can be set in `about:config` under `mod.better_unloaded_tabs.*`.
