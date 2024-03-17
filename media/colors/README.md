# Colors

## The Colors

## Plain CSS

When using plain CSS, css variables have been made available in [colors.css](./colors.css), you can use these by simply importing the file and using the variables like so

```css
.mydiv {
    background-color: var(--thorin-background-primary);
    color: var(--thorin-blue-primary);
}
```

## Styled-Components

For styled-components it is recommended to use the [ensdomains/thorin] global-styles.
You can import these like so

```tsx
import { ThorinGlobalStyles } from '@ensdomains/thorin';
import { baseTheme, lightTheme, darkTheme } from '@ensdomains/thorin';
```

## TailwindCSS

For tailwindcss it is recommended to use the provided [tailwind.config.js](./tailwind.config.js) file.
Simply drop it in your project and you should be good to go!

```
.bg-thorin-light-blue-primary
.bg-thorin-light-blue-surface
.bg-thorin-dark-background-surface
```
