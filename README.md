# Borozdov Archive

A theme from the Borozdov collection. Two faces — light **Microfiche**, warm cream paper
under gallery light, and dark **Vault**, the same warm monochrome archive turned inside out.
Near-black ink, cream card surfaces, hairline borders instead of shadows, pill-shaped
controls, and a typewriter mono reserved for financial figures.

![Borozdov Archive in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/archive/main/screenshots/light.png)

![Borozdov Archive in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/archive/main/screenshots/dark.png)

## Principles

- **Ink is the only colour.** Headlines, links, tags and the main button read in near-black
  ink (near-white in the vault); the rest of the interface stays grayscale. The absence of a
  colour accent is the point, not a limitation.
- **Cream is depth, not decoration.** Cards, callouts, code blocks and tables sit on a warm
  cream surface against the white canvas — a tonal shift takes the place of a shadow.
- **Hairline, never shadow.** Every panel is held by a 1px line, sometimes doubled for one
  extra step of separation. No blur, no elevation.
- **Mono is the ledger's column head.** Archive Mono stamps tags, table headers, callout
  titles and property labels in small tracked capitals, and sets numeric table columns in
  tabular figures — reserved for figures and labels, never for prose.
- **One inversion, at the edge.** The status bar is the archive's single dark-on-light (or
  light-on-dark) moment, the way a source document keeps one inverted footer and nothing
  else.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as cream cards on a tan hairline; the type's colour lives only in the stamped
  title and icon, never in a tinted background
- Code blocks as cream cards held by a hairline double-ring, inline code on the same warm
  tone, string literals in archive green
- Tables with a single rounded frame and no doubled cell borders, headers in small mono
  capitals, numeric columns in tabular figures
- Tags and table headers stamped in monospace capitals; property names read as labels, not
  boxed fields
- Pill-shaped buttons and inputs, large-rounded cards — never a sharp corner or a shadow
- Quiet editing: no focus ring around the note, its title or form fields while you type
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory:** Settings → Appearance → Themes → Manage, search for
**Borozdov Archive**, then **Install and use**.

**By hand:** download `manifest.json` and `theme.css` from the [latest
release](https://github.com/borozdov-obsidian-themes/archive/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Archive/`, then choose Borozdov Archive under
Settings → Appearance → Themes.

## Font

Archive Mono is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License 1.1
— see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of UM Typewriter
(© 2009 Apostolos Syropoulos), renamed because a modified copy may not use the original's
Reserved Font Name. One weight, for financial figures, code, inline code, tags, table
headers, callout titles and property labels — never for headings or running prose, which
stay in the platform's own sans.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Микрофиша» — тёплая кремовая
бумага под витринным светом, и тёмный «Хранилище» — тот же тёплый монохромный архив
наизнанку. Почти чёрные чернила, кремовые карточки, линии вместо теней, кнопки-пилюли и
моноширинный Archive Mono (урезанный UM Typewriter) только для финансовых цифр, кода, тегов,
заголовков таблиц и подписей колл-аутов. Устанавливается из каталога: Настройки → Оформление
→ Темы → Настроить → Borozdov Archive → Установить и применить.
