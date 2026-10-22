# ObsidianGlass

> A dark glassmorphism Discord theme: obsidian black, deep crimson and dark violet.

ObsidianGlass is the darkest of the set. The glass is thicker and more opaque, the text is softer, and the accents are **deep crimson** and **dark violet**. Crimson marks selections, mentions and warnings; violet marks hovers and links.

Works with **BetterDiscord** and **Vencord** (and Vencord-based clients like Vesktop / Equicord). Supports Discord's dark, darker, midnight and the new visual refresh UI.

**Best for:** Late-night use and anyone who wants maximum darkness with a little colour.

---

## Colour palette

| Colour | Value | Used for |
|---|---|---|
| Crimson | `#dc143c` | selected items, mentions, primary glow |
| Dark violet | `#7a3ddc` | hovers, links, accents |
| Obsidian | `#0a0510` | dark base tone |
| Glass | `rgba(6, 5, 9, 0.62)` | main panel glass (darker than the others) |
| Strong glass | `rgba(4, 3, 6, 0.80)` | sidebar, modals, popouts |

## What it changes

- **Frosted glass panels.** Server list, channel list, chat, member list and user panel turn transparent, with an 18px `backdrop-filter` blur, a thin light border and 14px rounded corners.
- **Message box.** Glass input field with an accent glow when focused.
- **Channels and messages.** Coloured hover and selected states, highlighted mentions and accent-coloured links.
- **Server icons.** Neon glow on hover, a stronger glow on the active server, and a glowing selection pill.
- **Modals, popouts, menus and tooltips.** Darker "strong glass" so they stay readable over the chat.
- **Buttons, switches and inputs.** Recoloured in the theme accents.
- **Status, badges and voice.** Recoloured status indicators, unread badges and voice UI.
- **Animated Home button.** The Discord Home button becomes an animated GIF icon with a pulsing **crimson** neon glow.
- **Optional wallpaper.** Put any image behind the glass, with adjustable blur.

## Installation

### BetterDiscord
1. Download [`ObsidianGlass.theme.css`](https://raw.githubusercontent.com/zip1fero/ObsidianGlass/main/ObsidianGlass.theme.css) (right-click → *Save link as…*).
2. Open **User Settings → BetterDiscord → Themes → Open Themes Folder**. On Windows this is `%AppData%\BetterDiscord\themes`.
3. Drop the file in that folder and turn **ObsidianGlass** on.

### Vencord / Vesktop
**Online (updates automatically):** open **Settings → Vencord → Themes → Online Themes** and paste:

```
https://raw.githubusercontent.com/zip1fero/ObsidianGlass/main/ObsidianGlass.theme.css
```

**Local:** put the file in the Vencord themes folder (**Themes → Open Themes Folder**) and enable it.

## Custom title

The text next to the back/forward arrows at the top of Discord can be anything you like. Open `ObsidianGlass.theme.css` and change the first value in the file:

```css
--titlebar-text: "Obsidian Glass";
```

For example `--titlebar-text: "my server";`. Keep the quotes.
## Notes

- Blur needs a wallpaper or something behind the panels to look its best. With no wallpaper, the glass sits on Discord's dark base.
- If you turn on **window transparency** (Vencord or BetterDiscord), some Discord/Electron builds stop rendering `backdrop-filter` blur. If the glass loses its blur, turn transparency off.
- Discord updates often rename internal classes. If something looks off after an update, open an issue.

## More themes in the set

[NeonGlass](https://github.com/zip1fero/NeonGlass) · [AuroraGlass](https://github.com/zip1fero/AuroraGlass)

## Support

Something broken after a Discord update? Open an [issue](https://github.com/zip1fero/ObsidianGlass/issues).

## Author

Made by **sakis** ([zip1fero](https://github.com/zip1fero)).

## License

All rights reserved. Copying, modifying or redistributing this theme is not allowed. See [LICENSE](LICENSE).
