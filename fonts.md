# AFRO Fonts — Gilroy

Gilroy lives in the [`afro-fonts`](https://github.com/AFROAgencyAI/afro-fonts) repo and is served via jsDelivr CDN. No `.woff2` files are duplicated in this repo to avoid version drift.

## CDN URLs

```
https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-fonts@main/Gilroy-Regular.woff2
https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-fonts@main/Gilroy-Medium.woff2
https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-fonts@main/Gilroy-SemiBold.woff2
https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-fonts@main/Gilroy-Bold.woff2
```

## Drop-in block (GHL Code Element)

Paste at the top of any `<style>` block:

```html
<style>
@font-face {
  font-family: 'Gilroy';
  src: url('https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-fonts@main/Gilroy-Regular.woff2') format('woff2');
  font-weight: 400;
  font-display: swap;
}
@font-face {
  font-family: 'Gilroy';
  src: url('https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-fonts@main/Gilroy-Medium.woff2') format('woff2');
  font-weight: 500;
  font-display: swap;
}
@font-face {
  font-family: 'Gilroy';
  src: url('https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-fonts@main/Gilroy-SemiBold.woff2') format('woff2');
  font-weight: 600;
  font-display: swap;
}
@font-face {
  font-family: 'Gilroy';
  src: url('https://cdn.jsdelivr.net/gh/AFROAgencyAI/afro-fonts@main/Gilroy-Bold.woff2') format('woff2');
  font-weight: 700;
  font-display: swap;
}

body, * {
  font-family: 'Gilroy', sans-serif;
}
</style>
```

`font-display: swap` prevents invisible text during load. Critical for the sub-1-second perceived load target.

## License

Gilroy is licensed via Fontspring. Web license permits self-hosting across AFRO domains. Do not redistribute outside the AFRO ecosystem.
