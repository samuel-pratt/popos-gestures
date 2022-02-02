# popos-gestures

My config for PopOS gestures using Touchegg, mimicking MacOS gestures.

## Installing

```
# clone repo
git clone https://github.com/samuel-pratt/popos-gestures.git

# make touchegg config folder
mdkir -p ~/.config/touchegg

# copy config from cloned repo to local
cp -n ./popos-gestures/touchegg.conf ~/.config/touchegg/touchegg.conf

# OPTIONAL delete git repo now that config is copied over
rm -rf ./popos-gestures
```

## Gestures

### SWIPE 3 fingers UP / DOWN

Opens activities view, opposite gesture closes it.

### SWIPE 3 fingers LEFT / RIGHT

Changes current workspace.

### PINCH 4 fingers IN / OUT

Opens and closes applications view.
