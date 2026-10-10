# Saudi Font (خط سعودي)

حزمة خطوط Saudi للاستخدام على سطح المكتب والويب.

## Desktop

- **Mac:** `Saudi/Desktop/Mac/Saudi/` — `Saudi-Regular.otf`, `Saudi-Bold.otf`
- **Windows:** `Saudi/Desktop/Windows/Saudi/` — `Saudi-Regular.ttf`, `Saudi-Bold.ttf`

## Web fonts

- **WOFF2:** `Saudi/Web fonts/WOFF-2-TT/Saudi Web/`
- **WOFF:** `Saudi/Web fonts/WOFF-TT/Saudi Web/`

### مثال CSS

```css
@font-face {
  font-family: "Saudi";
  src: url("SaudiWeb-Regular.woff2") format("woff2"),
       url("SaudiWeb-Regular.woff") format("woff");
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: "Saudi";
  src: url("SaudiWeb-Bold.woff2") format("woff2"),
       url("SaudiWeb-Bold.woff") format("woff");
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}
```
