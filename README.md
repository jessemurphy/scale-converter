# Unit Converter

A general unit-converter PWA: length, weight, volume, temperature, speed, and
area — pick a category, type a value on either side, and every other unit in
the category is shown too. A model-scale mode (1:87 HO etc., with a
what-scale-is-this finder) rides along as the last category.

- Bidirectional: edit either field and the other follows
- Full breakdown: your value in every unit of the category at once
- Remembers your last category and unit pair
- Fully offline after first load (service worker); no accounts, no server

## Hosting

Static files — GitHub Pages serves it as-is (Settings -> Pages -> Deploy from a
branch -> main / root). On iPhone: open the URL in Safari -> Share ->
Add to Home Screen.
