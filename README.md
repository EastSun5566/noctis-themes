# Noctis Themes

> Noctis color schemes for multiple tools, based on [Noctis theme](https://github.com/liviuschera/noctis).

## Supported Tools

- [Ghostty](https://github.com/ghostty-org/ghostty)
- [opencode](https://opencode.ai)

## Themes

### Dark Themes

- **Noctis**: The original dark blue theme
- **Noctis Azureus**: Dark theme with azure blue colors
- **Noctis Bordo**: Dark theme with burgundy colors
- **Noctis Minimus**: Dark theme with muted blue colors
- **Noctis Uva**: Dark theme with grape colors
- **Noctis Viola**: Dark theme with violet colors

### Light Themes

- **Noctis Lux**: Light theme with warm colors
- **Noctis Lilac**: Light theme with lilac colors
- **Noctis Hibernus**: Light theme with cool winter colors

## Ghostty

### Installation

```sh
# Create the Ghostty themes directory
mkdir -p ~/.config/ghostty/themes

# Clone the repository
git clone https://github.com/eastsun5566/ghostty-noctis-themes.git

# Copy the theme files
cp ghostty-noctis-themes/ghostty/* ~/.config/ghostty/themes/
```

Use `ghostty +list-themes` preview the themes

## Usage

Update `~/.config/ghostty/config`

```conf
theme = noctis
```

Or

```conf
theme = dark:noctis,light:noctis-lux
```

## opencode

### Installation

```sh
# Create the opencode themes directory
mkdir -p ~/.config/opencode/themes

# Copy the theme files
cp ghostty-noctis-themes/opencode/*.json ~/.config/opencode/themes/
```

### Usage

Add to your `~/.config/opencode/config.json`:

```json
{
  "theme": "noctis"
}
```

Available theme names: `noctis`, `noctis-azureus`, `noctis-bordo`, `noctis-minimus`, `noctis-uva`, `noctis-viola`, `noctis-hibernus`, `noctis-lilac`, `noctis-lux`

## Screenshots

- Noctis

![Noctis](./screenshots/noctis.png)

- Noctis Azureus

![Noctis Azureus](./screenshots/noctis-azureus.png)

- Noctis Bordo

![Noctis Bordo](./screenshots/noctis-bordo.png)

- Noctis Minimus

![Noctis Minimus](./screenshots/noctis-minimus.png)

- Noctis Uva

![Noctis Uva](./screenshots/noctis-uva.png)

- Noctis Viola

![Noctis Viola](./screenshots/noctis-viola.png)

- Noctis Lux

![Noctis Lux](./screenshots/noctis-lux.png)

- Noctis Lilac

![Noctis Lilac](./screenshots/noctis-lilac.png)

- Noctis Hibernus

![Noctis Hibernus](./screenshots/noctis-hibernus.png)
