# Signal — Live TV

A standalone GitHub Pages IPTV browser built around public streams curated by [iptv-org/iptv](https://github.com/iptv-org/iptv).

## Features

- Browse channels by country or region.
- Save channels to a persistent Favorites group from the player.
- Chinese, Kids, Sports, Movies, News, and Documentary quick groups.
- Popularity-first sorting, recent-channel ordering, and right-click move-to-top/bottom controls.
- Persistent playback History for channels that successfully played.
- Independent scrolling for the channel library and player panel.
- Every channel in the Chinese quick group has an IPTV345 player fallback after its public playlist sources fail or play audio without video, including Hunan TV. Some regional channels use the closest IPTV345 feed, such as TVBS HD for TVBS Asia and domestic Dragon TV for Dragon TV International.

## Run locally

Open `index.html` directly in a modern browser. The page loads the public playlist and metadata in the background; browser local storage keeps recent groups, channel ordering, and playback history.

## GitHub Pages

This repository is a static site. To enable the public site, open the repository’s **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, and save. The site will then be available at `https://jyu001.github.io/iptv/`. `.nojekyll` keeps GitHub Pages from applying Jekyll processing.

Stream availability is controlled by the upstream providers and may vary by location or time. The page does not host or redistribute the streams.
