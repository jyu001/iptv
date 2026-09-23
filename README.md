# Signal — Live TV

A standalone GitHub Pages IPTV browser built around public streams curated by [iptv-org/iptv](https://github.com/iptv-org/iptv).

## Features

- Browse channels by country or region.
- Chinese, Kids, Sports, Movies, News, and Documentary quick groups.
- Popularity-first sorting, recent-channel ordering, and right-click move-to-top/bottom controls.
- Persistent playback History for channels that successfully played.
- Independent scrolling for the channel library and player panel.
- CCTV and selected Hong Kong/Taiwan/Phoenix channels can use alternate reference players when their public playlist source is unavailable.

## Run locally

Open `index.html` directly in a modern browser. The page loads the public playlist and metadata in the background; browser local storage keeps recent groups, channel ordering, and playback history.

## GitHub Pages

This repository is a static site. Publish the root of the default branch with GitHub Pages. `.nojekyll` keeps GitHub Pages from applying Jekyll processing.

Stream availability is controlled by the upstream providers and may vary by location or time. The page does not host or redistribute the streams.

