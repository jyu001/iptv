# Signal — Live TV

A standalone GitHub Pages IPTV browser built around public streams curated by [iptv-org/iptv](https://github.com/iptv-org/iptv).

## Features

- Browse channels by country or region.
- Curated quick groups are ranked by quality and source popularity; most show up to six, News keeps up to five, and Sports keeps up to eight, including CCTV-5 and CCTV-5+. Chinese keeps its six ranked picks plus CCTV-5 and CCTV-5+; Movies keeps its six ranked picks plus its two highest-ranked HBO channels and CCTV-6.
- Save channels to a persistent Favorites group from the player.
- First-run Favorites include Disney Channel, National Geographic, Mei Ah, Phoenix, CCTV-5, and CCTV-5+; existing saved favorites are preserved.
- Chinese, Kids, Sports, Movies, News, and Documentary quick groups.
- Popularity-first sorting, recent-channel ordering, and right-click move-to-top/bottom controls.
- Persistent playback History for channels that successfully played.
- Remembers each channel’s last working stream and tries it first on the next play.
- Offers official viewer links when Disney Channel, National Geographic, Mei Ah, Phoenix, or HBO streams fail.
- Independent scrolling for the channel library and player panel.
- Every channel in the Chinese quick group has an IPTV345 player fallback after its public playlist sources fail or play audio without video, including Hunan TV. Some regional channels use the closest IPTV345 feed, such as TVBS HD for TVBS Asia and domestic Dragon TV for Dragon TV International.

## Run locally

Open `index.html` directly in a modern browser. The page loads the public playlist and metadata in the background; browser local storage keeps recent groups, channel ordering, and playback history.

## GitHub Pages

This repository is a static site. To enable the public site, open the repository’s **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, and save. The site will then be available at `https://jyu001.github.io/iptv/`. `.nojekyll` keeps GitHub Pages from applying Jekyll processing.

Stream availability is controlled by the upstream providers and may vary by location or time. The page does not host or redistribute the streams.
