# Omarchy Bar Tweaks

Personal customizations of a few built-in [Omarchy](https://omarchy.org/) shell
bar widgets, each cloned from its stock version (`omarchy plugin clone
<id>`) so it survives `omarchy update` instead of being overwritten.

## What's here

- **`ashley.clock`** — clock label rendered in the theme's accent color
  instead of the normal bar text color, and its calendar popup opens under
  the clock icon (left side of the bar) instead of dead-center on the screen.
- **`ashley.weather`** — its detail popup opens under the weather icon
  (right side of the bar) instead of dead-center on the screen.
- **`ashley.indicators`** — the inactive icon row (dictation, screen
  recording, reminder, night light, DND, stay-awake — normally revealed on
  hover) is reordered to the reverse of the default, and an icon that
  becomes active now appears on the near side of the group (toward the rest
  of the bar) instead of the far side.
- **`ashley.workspaces`** — the focused workspace keeps showing its plain
  number (in the normal theme color, same as every other workspace) instead
  of swapping in a filled-square glyph; a thin underline in the theme's
  accent color marks which one is focused instead.

## Install

Each is a normal Omarchy shell plugin folder. Copy whichever ones you want
into `~/.config/omarchy/plugins/<id>/`, then update `~/.config/omarchy/shell.json`'s
bar layout to reference that id in place of the original (e.g. `ashley.clock`
instead of `omarchy.clock`) — `omarchy plugin clone` does this automatically
when you clone a widget yourself, and these already exist at their final
`ashley.*` ids.

## License

MIT — see [LICENSE](LICENSE).
