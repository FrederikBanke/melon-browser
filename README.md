# Browser styles

This repository contains the styles I use in my browser's `chrome` folder.

I use the [Zen Browser](https://github.com/zen-browser/desktop/) and the primary styles come from [Natsumi](https://github.com/greeeen-dev/natsumi-browser).

Natsumi current has no styles for tab groups, but I have added a fix for that, so that tab groups have styles.

## Installation

The files in the repo must be placed in the `chrome` folder of the browser profile.

You could clone this repo with `git clone https://github.com/frederikbanke/melon-browser chrome`.
However, in most cases, the folder already exists or contains files. Git will then not allow you to clone to the `chrome` folder.

Instead go into the `chrome` folder and run this:

```bash
git init .
git remote add -f origin https://github.com/frederikbanke/melon-browser 
git checkout main
```

