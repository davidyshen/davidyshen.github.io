# Color Customization Guide

This site's colors are now managed in a dedicated file: `themes/hugo-profile/static/css/colors.css`

## How to Change Colors

1. Open the file `themes/hugo-profile/static/css/colors.css`
2. Modify the color values in the `:root` section
3. Save the file and rebuild your Hugo site

## Available Color Variables

### Light Mode

- `--text-color`: Main text color
- `--text-secondary-color`: Secondary/muted text color  
- `--background-color`: Main background color
- `--secondary-background-color`: Cards, panels, secondary areas
- `--primary-color`: Accent color for links, buttons, highlights
- `--secondary-color`: Alternative accent color

### Dark Mode

- `--text-color-dark`: Dark mode main text color
- `--text-secondary-color-dark`: Dark mode secondary text color
- `--background-color-dark`: Dark mode main background color
- `--secondary-background-color-dark`: Dark mode secondary areas
- `--primary-color-dark`: Dark mode accent color
- `--secondary-color-dark`: Dark mode alternative accent color

## Color Examples

### Blue Theme (Default)

```css
--primary-color: #007bff;
--primary-color-dark: #82c8fa;
```

### Green Theme

```css
--primary-color: #10b981;
--primary-color-dark: #34d399;
```

### Purple Theme

```css
--primary-color: #8b5cf6;
--primary-color-dark: #a78bfa;
```

### Amber Theme

```css
--primary-color: #f59e0b;
--primary-color-dark: #fbbf24;
```

## Tips

1. Use hex colors (#rrggbb) for consistency
2. Ensure good contrast between text and background colors
3. Test both light and dark modes after making changes
4. Use online color palette generators for inspiration
5. Consider accessibility guidelines when choosing colors

## Config.yaml Alternative

You can still override colors in your `config.yaml` if needed:

```yaml
params:
  color:
    primaryColor: "#10b981"
    darkmode:
      primaryColor: "#34d399"
```

However, using the dedicated CSS file is recommended for easier management.
