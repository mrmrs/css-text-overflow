# css-text-overflow

Functional CSS for text-overflow

## Filesize

| File | Size |
|------|------|
| `dist/text-overflow.css` | 1265 bytes |
| `dist/text-overflow.min.css` | 927 bytes (217 Gzipped) |

## Install

```sh
npm install css-text-overflow
```

## Usage

### Import

```css
@import "css-text-overflow";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-text-overflow/dist/text-overflow.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-text-overflow/dist/text-overflow.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.t-clip` | `text-overflow: clip;` |
| `.t-ellipsis` | `text-overflow: ellipsis;` |
| `.t-dots` | `text-overflow: "…";` |
| `.t-clip-ellipsis` | `text-overflow: clip ellipsis;` |
| `.t-double` | `text-overflow: "…" "…";` |
| `.t-i` | `text-overflow: inherit;` |
| `.t-clip-s` | `text-overflow: clip;` |
| `.t-ellipsis-s` | `text-overflow: ellipsis;` |
| `.t-dots-s` | `text-overflow: "…";` |
| `.t-clip-ellipsis-s` | `text-overflow: clip ellipsis;` |
| `.t-double-s` | `text-overflow: "…" "…";` |
| `.t-i-s` | `text-overflow: inherit;` |
| `.t-clip-m` | `text-overflow: clip;` |
| `.t-ellipsis-m` | `text-overflow: ellipsis;` |
| `.t-dots-m` | `text-overflow: "…";` |
| `.t-clip-ellipsis-m` | `text-overflow: clip ellipsis;` |
| `.t-double-m` | `text-overflow: "…" "…";` |
| `.t-i-m` | `text-overflow: inherit;` |
| `.t-clip-l` | `text-overflow: clip;` |
| `.t-ellipsis-l` | `text-overflow: ellipsis;` |
| `.t-dots-l` | `text-overflow: "…";` |
| `.t-clip-ellipsis-l` | `text-overflow: clip ellipsis;` |
| `.t-double-l` | `text-overflow: "…" "…";` |
| `.t-i-l` | `text-overflow: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.t-clip-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/text-overflow.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/text-overflow.css` — formatted
- `dist/text-overflow.min.css` — minified

## License

MIT
