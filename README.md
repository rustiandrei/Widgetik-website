# Widgetik website

The website for Widgetik, published with GitHub Pages at https://rustiandrei.github.io/Widgetik-website/

- `index.html` + `home.css`: the main page
- `privacy.html`, `support.html` + `style.css`: the pages the App Store and Google Play link to
- `img/`: iPhone screens cut from the App Store screenshots, Android emulator captures, store badges and icons
- `img/w/`: real widget renders from the Android store-screenshot pipeline (`build/store-screenshots/sprites/en-US` in the app repo)
- `og.png`: the preview image shown when the link is shared

No build step: edit the files and push. GitHub Pages serves the `main` branch from the root folder.

The AdMob `app-ads.txt` file lives in the `rustiandrei.github.io` repo, because it has to be at the root of the domain.
