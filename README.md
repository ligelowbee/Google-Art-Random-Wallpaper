`label-wallpaper.sh` resizes and labels images for wallpaper using `imagemagick`. Resizes to 1920x180 keeping aspect and padding with black, adds a 20pt drop shadowed label to the bottom left with Ubuntu font.

`cinnamon-set-wallpaper.sh` sets an image as wallpaper in linux mint cinnamon.

`calibre-cover-wallpaper.sh` selects a random cover image from my calibre library and uses above scripts to label and set as wallpaper.

`google-art-wallpaper.sh` uses `curl` to fetch a random art image from wikimedia's google arts collection. Then uses above scripts to label and set as wallpaper.

`my-wallpaper.sh` choses to use already downloaded art (or book covers), or to fetch fresh art, and uses above scripts to set wallpaper.
