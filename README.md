# lightlike — a light theme for pi

A clean, readable light theme for [pi](https://github.com/badlogic/pi-mono), the CLI coding agent.

![Preview](preview.png)

## Install

Drop the theme file into your global themes directory:

```bash
mkdir -p ~/.pi/agent/themes
cp theme.json ~/.pi/agent/themes/lightlike.json
```

Then select it in pi:

```
/settings theme lightlike
```

Or add it to your `settings.json`:

```json
{
  "theme": "lightlike"
}
```

## Details

- **Name:** `lightlike`
- **Palette:** Neutral grays with a blue accent (`#4a90d9`)
- **Background:** `#ffffff` (pure white)
- **Text:** `#111827` (near-black)
- **Syntax:** High-contrast colors for readability on light backgrounds

## License

MIT
