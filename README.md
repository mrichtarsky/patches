# nextcloud-encode_videos_for_browser.patch

Patch for the convert media flow

- convert mp4 as produced by e.g. Galaxy smartphones to mp4 playable in browsers
- configure the flow as follows:
  - File created
  - File name matches: /^.*mp4$/
  - Convert to format: mp4
  - Move source file to specific folder (and choose a folder where you won't upload the videos)
  - Store output in source folder
  - Overwrite existing file
