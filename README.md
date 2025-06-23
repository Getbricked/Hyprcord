<div align="center">

# ClearVision Hyprcord - Customized by Aki

**Original Theme Repository**: [ClearVision v7](https://github.com/ClearVision/ClearVision-v7)

This theme is inspired by **Jugom** and the **Hyprland window manager**.

## Previews

![Hyprcord](Screenshots/hyprcord.png)

</div>

## Installation

### 1. Download Your Preferred Version

#### **For Vencord:**

- **[Hyprcord Core](https://getbricked.github.io/Hyprcord/Hyprcord.css)** `Hyprcord.css`
  _(Core needs to be used along with your ClearVision v7)_

- **[Hyprcord Aki](https://getbricked.github.io/Hyprcord/Hyprcord-Aki.css)** `Hyprcord-Aki.css`
  _(Core + ClearVision Aki theme)_

#### **For BetterDiscord:**

- **[Hyprcord Core](https://getbricked.github.io/Hyprcord/Hyprcord.theme.css)** `Hyprcord.theme.css`
  _(Core needs to be used along with your ClearVision v7)_

- **[Hyprcord Aki](https://getbricked.github.io/Hyprcord/Hyprcord-Aki.theme.css)** `Hyprcord-Aki.theme.css`
  _(Core + ClearVision Aki theme)_

### 2. Place the Downloaded File in Your Themes Folder

### For advanced users:

Add the following line to your ClearVision theme file to import the theme:

```css
@import url("https://getbricked.github.io/Hyprcord/Hyprcord.css");
```

### For Online Theme Usage

```
https://getbricked.github.io/Hyprcord/Hyprcord.css
```

## Basic Customization

### 1. Change the Background Picture (Not for **Hyprcord Core**)

To set a custom background image, replace the URL inside `url()` with the link to your desired image:

```css
/* Custom Background Image */
:root {
  --background-image: url(https://i.imgur.com/zU7YY60.jpeg);
}
```

### 2. Change the Global Margin

```css
/* Global Margin */
:root {
  --global-margin: 20px; /* Default is 20px */
}
```

### 3. Change the Border

Above is default border style, you can customize it by changing the `--bordersize` and `--hsl-main-color` variables.

```css
:root {
  --border: var(--bordersize, 1px) solid var(--hsl-main-color);
  --bordersize: 1px;
}
```

## Advanced Customization

For further customization, fork the repository and tailor it to your preferences.
