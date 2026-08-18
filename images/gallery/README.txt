Team page rotating gallery
===========================

This folder holds the photos used by the rotating gallery on the team
page (rendered by _includes/gallery.html, included from team/index.md).

How it works
------------
- The list of image files is a hardcoded, comma-separated string inside
  _includes/gallery.html (near the top of the file). It is NOT generated
  by scanning this folder, so adding a file here does nothing on its own.
- Only the first 3 images in that list are rendered as visible <img>
  tags on page load.
- A script in the same include rotates through the full list, swapping
  one additional image into the visible set every 5 seconds with a
  fade transition, cycling through every image in the list over time.

Adding a new photo
-------------------
1. Add the image file to this folder, following the naming convention
   below.
2. Open _includes/gallery.html and add the new file's path to the
   comma-separated list assigned to `gallery_images` near the top of
   the file (e.g. "images/gallery/team-13.jpg").
3. No other code changes are needed — the rotation script picks up any
   images present in that list automatically.

File naming convention
------------------------
- Name files `team-NN.jpg`, where NN is a two-digit, zero-padded number
  (e.g. team-13.jpg, team-14.jpg). Use the next unused number; numbers
  do not need to be contiguous, but avoid reusing one already in the
  gallery_images list.
- Use .jpg for photos.

Formatting new images before adding them
------------------------------------------
- Orientation: landscape works best. The gallery displays images in a
  row of equal-width columns and scales them to fit, so extreme aspect
  ratios (very tall/narrow or very wide/short) will look cropped or
  have excess whitespace next to other photos in the row.
- Resolution: resize to roughly 1200px on the longest edge before
  adding. Full-resolution camera photos are unnecessarily large for
  a web gallery and slow down the page.
- File size: keep each file under ~300KB where possible (export at
  ~75-85% JPEG quality). Several existing images in this folder are
  400-900KB, which is heavier than needed - please don't add new files
  in that range.
- Compression: use a JPEG optimizer (e.g. Squoosh, ImageOptim,
  `jpegoptim`, or your image editor's "export for web" option) before
  committing the file.
