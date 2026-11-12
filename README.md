# Wafa | وفاء

Landing page for **Wafa**, the loyalty app that lets shops reward customers their way: cashback, points, stamps, or cashback and stamps together. Built in Arabic and English, with a liquid-glass look and smooth animation.

**Live site:** https://abdallahzezo77.github.io/wafaa/

![Wafa landing page animation](screenshots/demo.gif)

## Screenshots

| English | العربية |
| --- | --- |
| ![Hero in English](screenshots/hero-en.jpg) | ![Hero in Arabic](screenshots/hero-ar.jpg) |

### Photo panels
Hover a photo and it widens while its caption fades in.

![Photo panels](screenshots/photos.jpg)

### Reward types
A glass tab bar slides between Cashback, Points, Stamps and Cashback + Stamps, and the phone shows the matching app screen.

![Reward types](screenshots/reward-types.jpg)

### Join the launch list
Waitlist form with brand name, manager name, email, industry, city and a short message.

![Waitlist form](screenshots/waitlist.jpg)

### Mobile

<img src="screenshots/mobile-ar.jpg" alt="Mobile view in Arabic" width="320">

## Versions

| Version | Link | Preview |
| --- | --- | --- |
| Morning (main) | [index.html](https://abdallahzezo77.github.io/wafaa/) | ![Morning](screenshots/hero-en.jpg) |
| Night | [versions/night.html](https://abdallahzezo77.github.io/wafaa/versions/night.html) | ![Night](screenshots/night.jpg) |
| Elegant (Apple-style) | [versions/elegant.html](https://abdallahzezo77.github.io/wafaa/versions/elegant.html) | ![Elegant](screenshots/elegant.jpg) |

## Features

- **Arabic and English:** one EN / AR button switches the whole page, including right-to-left layout. Add `#ar` or `#en` to the link to open a language directly.
- **Brand font:** The Year of Handicrafts for all text, with stretched letters (kashida) on Arabic headings.
- **Liquid glass:** frosted nav, cards and buttons with a light rim and a sheen that follows the mouse.
- **Animation:** headline words fade in, a photo capsule cycles inside the headline, floating icon tiles follow the mouse, and sections reveal as you scroll. All motion turns off for visitors who prefer reduced motion.
- **Real product:** screens come from the Wafa app and merchant dashboard designs.
- **No build step:** plain HTML, CSS and JavaScript. Open `index.html` or host the folder anywhere.

## Structure

```
index.html          Morning version (main)
versions/           Night and Elegant versions
assets/             App screens, photos and fonts
screenshots/        Images used in this README
```

## Notes

- The waitlist form validates input but is not connected to a backend yet.
- The App Store and Google Play badges are placeholders until the store links are live.
- Contact: +966 50 335 5729 · www.lamdax.sa
