# Export

The **Export** card at the bottom of the inspector writes finished PNGs and
MP4s to disk. Exports are rendered at the exact pixel size shown — never
scaled — from the same composition you see on the canvas.

## Choosing a size

Pick a resolution from the preset list. It is normally set for you when you
choose a device, and the canvas badge (for example *1320 × 2868*) always shows
what will be written.

| Platform | Sizes |
| --- | --- |
| Mac | 2880 × 1800, 2560 × 1600, 1440 × 900, 1280 × 800 |
| iPhone | 6.9″, 6.7″, 6.5″, 6.3″, 6.1″, 5.5″, 4.7″, 4″ and 3.5″ displays, plus the iPhone Duo sizes |
| iPad | 13″, 12.9″, 11″, 11″ Air and 8.3″ mini — each in portrait and landscape |

> iPhone Duo sizes are **export-only** for now: App Store Connect does not
> yet accept them for upload.

## Exporting screenshots

| Button | What it does |
| --- | --- |
| **Export Current** | Saves the screenshot shown on the canvas. A save panel asks where. |
| **Export All (n)** | Writes every screenshot of the frame into a folder you choose. |
| **Export Localized (n languages)** | Writes every screenshot once per enabled language, into sub-folders named after the locale — `en-US`, `de`, `ja` and so on — ready to upload set by set. |

Files are PNG without transparency, named `<name>-<width>x<height>.png`.
The *name* is the media item's internal file name, which you will see in the
Media list and the gallery captions. Localized export is a **Pro** feature.

## Exporting recordings

**Export Video** writes the current recording as an MP4, and **Export All
Videos (n)** writes all of them. Videos export at App Store preview
resolution: 1920 × 1080 for Mac, 886 × 1920 for iPhone and 1200 × 1600 for
iPad.

App previews must be 15 to 30 seconds long. A recording under 15 seconds
shows an **App preview length** warning with an **Export Anyway** option;
one over 30 seconds cannot be exported. Video export needs **Pro**.

## Free plan limits

Free accounts can export two screenshots per hour and four in total; the
caption under the buttons shows what is left. Exports made while subscribed
are unlimited.

## If an export fails

An **Export failed** alert means the composition could not be rendered or the
file could not be written. Check that the destination folder is writable and
that every media slot has an image, then try again.
