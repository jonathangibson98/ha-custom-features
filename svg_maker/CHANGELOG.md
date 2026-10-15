# Changelog

## 1.4.0
- Default save folder is now /homeassistant/custom_icons (the Custom Icons integration folder)
- Icon-friendly file names option
- Black and white icons can follow Home Assistant colors
- Shaped icons now get a unique clip id so many icons on one dashboard do not clash

## 1.3.0
- Crop editor with drag, pinch and zoom, circle, rounded, square and full-photo shapes
- Auto-crop suggestion that centers on the main subject
- Auto-enhance before tracing for cleaner shapes and smaller files
- Result is clipped to the chosen shape (transparent corners for circles)
- New options: crop_editor, auto_crop, crop_shape, crop_padding, output_size, auto_enhance

## 1.2.0
- Result screen: name your file, then Save locally, Download or Both
- Unsaved results auto-save to a temp folder (default /homeassistant/www/svg_maker/temp_icons)
- Auto-delete is now a toggle and only cleans the temp folder
- Access to all Home Assistant folders; app only uses the paths you configure
- Removed options: save_to_disk, keep_original, retention_days

## 1.1.0
- Configuration options, docs, icon, new web page

## 1.0.0
- Initial release
