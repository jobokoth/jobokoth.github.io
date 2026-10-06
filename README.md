# jobokoth.github.io

Root GitHub Pages site. It exists to serve `/.well-known/assetlinks.json`, which lets the
Nuggets Android app (`io.github.jobokoth.nuggets`, https://github.com/jobokoth/nuggets) open
https://jobokoth.github.io/nuggets/ full screen without a browser address bar.

`.nojekyll` is required: Jekyll would otherwise skip the `.well-known` folder.
