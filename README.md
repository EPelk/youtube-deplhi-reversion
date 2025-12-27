# YouTube Delphi Modern UI Reversion
A UserCSS stylesheet to bring the new YouTube Delphi UI closer to the old look while preserving its useful changes and additions.

## About
This stylesheet overhauls YouTube's new Delphi Modern UI. It attempts to mimic the visual style of the older UI that Delphi replaces while preserving the useful features Delphi adds and correcting its shortcomings. A full list of changes is as follows:
<details>
  <summary>Show changes</summary>
  
  * Shrink excessively large UI elements to same size as previous UI.
  * Replace blurred backgrounds of UI elements with full-width gradient from old UI, which significantly improves contrast on bright videos.
  * Darken backgrounds of tooltips and menus to improve contrast against bright videos.
  * Move like, comment, and share buttons to top-right corner in fullscreen.
  * Add red outline and white gradient to heatmap (the graph above the progress bar) to improve contrast.
  * Disable suggested video grid when scrolling up in fullscreen.
  * Restore full 12-video suggestions grid on video endscreen.
  * Add red background color to ticked check boxes in settings menu.
  * Remove channel logo from bottom-right corner of video.
</details>

## Comparison Images
<details>
  <summary>Show images</summary>

  | Default Delphi UI | Modified UI |
  |-------------------|-------------|
  |![Light background, Delphi UI](https://github.com/EPelk/youtube-deplhi-reversion/blob/main/doc/yt-light-bg-delphi-ui.jpg)|![Light background, modified UI](https://github.com/EPelk/youtube-deplhi-reversion/blob/main/doc/yt-light-bg-styled-ui.jpg)|
  |![Dark background, Delphi UI](https://github.com/EPelk/youtube-deplhi-reversion/blob/main/doc/yt-dark-bg-delphi-ui.png)|![Dark background, modified UI](https://github.com/EPelk/youtube-deplhi-reversion/blob/main/doc/yt-dark-bg-styled-ui.png)|
  |![End screen, Delphi UI](https://github.com/EPelk/youtube-deplhi-reversion/blob/main/doc/yt-endscreen-delphi-ui.png)|![End screen, modified UI](https://github.com/EPelk/youtube-deplhi-reversion/blob/main/doc/yt-endscreen-styled-ui.png)|
</details>

## Compatibility
This stylesheet is designed and tested for Firefox. *It is not intended for use in Chrome and causes significant performance drops when used as such.*

## Installation
This stylesheet requires the [Stylus](https://add0n.com/stylus.html) extension.

[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/epelk/youtube-deplhi-reversion/main/yt-delphi-reversion.user.css)

Alternatively, [install from UserStyles.world](https://userstyles.world/style/25809/youtube-delphi-modern-ui-reversion).

## Acknowledgements
This project was inspired by CupcakeHy's project [here](https://userstyles.world/style/23358/youtube-restore-player-ui). Their code formed the early foundation of my own efforts.

## License
Code released under the [MIT](https://github.com/EPelk/youtube-deplhi-reversion/blob/main/LICENSE) license.
