# Obsidian Compact UI Component

<p align="center">
  <img src="Screenshots/compact-ui-banner.png" alt="Obsidian Compact UI Component banner" width="100%">
</p>

I wrote this CSS snippet a few years ago to make Obsidian feel a little more compact. It tightens up the extra spacing around text and UI elements, so you can see more of your notes at once without changing how Obsidian works.

It works on a clean Obsidian install with no plugins or themes required. If you do use themes, it also pairs nicely with the [Things theme](https://github.com/colineckert/obsidian-things), which is one of my favorites. Enjoy!

<p align="center">
  <img src="Screenshots/quby-cute.gif" alt="Quby cute sticker" width="120">
</p>

## Preview

### Before (Original Obsidian Style)

<img src="Screenshots/Obsidian-before.png" alt="Obsidian before view" width="100%">

### After (After Added My Custom Style)

<img src="Screenshots/Obsidian-after.png" alt="Obsidian after view" width="100%">

## Snippet Effects

Regular snippets live in `snippets/`. Each one can be enabled on its own, and demos with screenshots show the change from a clean Obsidian view to the snippet-enabled view.

### [Root](snippets/root.css)

Shared color variables used by the other snippets.

### [Active Row](snippets/active-row.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-active-row.png" alt="Active row before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-active-row.png" alt="Active row after snippet" width="100%"> |

### [Compact Source View](snippets/compact-source-view.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-compact-source-view.png" alt="Compact source view before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-compact-source-view.png" alt="Compact source view after snippet" width="100%"> |

### [Compact Reading Mode](snippets/compact-reading-mode.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-compact-reading-mode.png" alt="Compact reading mode before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-compact-reading-mode.png" alt="Compact reading mode after snippet" width="100%"> |

### [Diamond Bullet List](snippets/diamond-bullet-list.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-diamond-bullet-list.png" alt="Diamond bullet list before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-diamond-bullet-list.png" alt="Diamond bullet list after snippet" width="100%"> |

### [Heading Colors](snippets/heading-colors.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-heading-colors.png" alt="Heading colors before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-heading-colors.png" alt="Heading colors after snippet" width="100%"> |

### [Inline Code](snippets/inline-code.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-inline-code.png" alt="Inline code before color snippet" width="100%"> | <img src="Screenshots/Obsidian-after-inline-code.png" alt="Inline code after color snippet" width="100%"> |

### [Outline Colors](snippets/outline-colors.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-outline-colors.png" alt="Outline before color snippet" width="100%"> | <img src="Screenshots/Obsidian-after-outline-colors.png" alt="Outline after color snippet" width="100%"> |

### [Outline Spacing](snippets/outline-spacing.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-outline-spacing.png" alt="Outline before spacing snippet" width="100%"> | <img src="Screenshots/Obsidian-after-outline-spacing.png" alt="Outline after spacing snippet" width="100%"> |

### [Popover Preview](snippets/popover-preview.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-popover-preview.png" alt="Popover preview before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-popover-preview.png" alt="Popover preview after snippet" width="100%"> |

### [Scrollbar](snippets/scrollbar.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-scrollbar.png" alt="Scrollbar before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-scrollbar.png" alt="Scrollbar after snippet" width="100%"> |

### [Hide Left Sidebar](snippets/hide-left-sidebar.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-hide-left-sidebar.png" alt="Hide left sidebar before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-hide-left-sidebar.png" alt="Hide left sidebar after snippet" width="100%"> |

### [Sidebar Active Note](snippets/sidebar-active-note.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-sidebar-active-note.png" alt="Sidebar active note before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-sidebar-active-note.png" alt="Sidebar active note after snippet" width="100%"> |

### [Table Styles](snippets/table-styles.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-table-styles.png" alt="Table styles before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-table-styles.png" alt="Table styles after snippet" width="100%"> |

## Optional Snippets

Optional snippets live in `optional-snippets/`. These are stronger visual tweaks that you can enable only when you want the extra effect.

### [Animation Icons](optional-snippets/animation-icons.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-animation-icon.png" alt="Animation icons before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-animation-icon.png" alt="Animation icons after snippet" width="100%"> |

### [Animation Title](optional-snippets/animation-title.css)

<img src="Screenshots/animation-title.gif" alt="Animation title CSS snippet effect" width="100%">

### [Minecraft Cursor](optional-snippets/minecraft-cursor.css)

| Before | After |
| --- | --- |
| <img src="Screenshots/Obsidian-before-minecraft-cursor.png" alt="Minecraft cursor before snippet" width="100%"> | <img src="Screenshots/Obsidian-after-minecraft-cursor.png" alt="Minecraft cursor after snippet" width="100%"> |

## Installation

For normal use, you only need to download [custom-use-this.css](custom-use-this.css), then place it inside your vault's snippets folder:

```text
...Your Vault Name\.obsidian\snippets
```

If the `snippets` folder does not exist yet, create it inside `.obsidian`. After that, open Obsidian and go to `Settings` -> `Appearance` -> `CSS snippets`, refresh the list, and enable `custom-use-this`.

The `backup/` folder keeps the original combined CSS files for reference. You do not need those files for the normal installation.

<p align="center">
  <img src="Screenshots/Obsidian-installation-path.png" alt="Obsidian CSS snippets installation path" width="85%">
</p>

## Thanks

Thanks for reading through the whole note. I just wanted to share this with anyone who needs a more compact Obsidian setup.

<p align="center">
  <img src="Screenshots/quby-thank-you.gif" alt="Quby thank you sticker" width="140">
</p>
