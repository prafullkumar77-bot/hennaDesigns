# Mehndi Magic design collection

Images are organized as `images/<category>/<subcategory>/<original filename>` using the source app’s folder structure.

- Source app: [Mehndi Magic & Henna Designs](https://play.google.com/store/apps/details?id=com.shahidappdev.mehndi_magic.hennadesigns)
- Package: `com.shahidappdev.mehndi_magic.hennadesigns`
- Image host / configured API base: `https://zenraz.pw/mehndimagic`
- `catalog.json`: original bundled category catalog.
- `manifest.json`: all 35,549 source URLs, relative paths, validation status, byte sizes, SHA-256 checksums, and image dimensions.
- `collection-status.json`: counts for each of the 36 categories.
- `source-errors.json`: the 12 empty or damaged source files, omitted from the published image folders.

The images were downloaded from public URLs listed in the app’s bundled Flutter catalog. The completed collection contains **35,537 fully decoded images across 36 categories** (about 2.14 GB). All 35,549 catalog URLs were fetched. Twelve source files were empty or damaged; each was downloaded again and returned identical bytes. These unusable files are recorded in the reports and omitted from `images/`. The manifest includes the entire source catalog, with validation status distinguishing the exceptions.

## Rights

These are third-party images. Their licenses and ownership have not been independently verified. The CC0 notice for the repository’s original collection does not apply to this folder. This repository does not grant rights to reuse these images.
