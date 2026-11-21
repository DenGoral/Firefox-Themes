# Firefox Themes

Cute, clean and simple Firefox themes featuring custom animations, carefully selected colors and beautiful wallpapers.

**Free to use, easy to install, and made to personalize your browsing experience.**

---

## 1. Installation Guide

### Step 1. Find your Firefox profile folder

First, you need to locate your Firefox profile directory.

**The easiest way:**

1. Open Firefox.
2. Type `about:support` in the address bar.
3. Find the **Profile Folder** entry.
4. Click **Open Folder** (or **Show in Finder** on macOS).

Alternatively, you can navigate to the default profile locations manually:

| Operating System | Default Location |
|---|---|
| macOS | `~/Library/Application Support/Firefox/Profiles/` |
| Linux | `~/.mozilla/firefox/` |
| Windows | `%APPDATA%\Mozilla\Firefox\Profiles\` |

**Note:** Your actual profile is usually inside a subfolder with a random combination of letters and numbers. Linux installations using Snap or Flatpak may use different locations.

### Step 2. Choose and download a theme

Browse the available themes in this repository and download the one you like.

Each theme may contain up to three files:

1. **`userChrome.css`** – The main stylesheet responsible for customizing Firefox's interface, including tabs, toolbars, buttons and animations.
2. **`userContent.css`** – An optional stylesheet used to customize the appearance of webpages and certain internal Firefox pages.
3. **`preview.png`** – A screenshot showing what the theme looks like. You don't need this file for installation.

### Step 3. Create the `chrome` folder

Inside your Firefox profile directory:

1. Create a new folder named `chrome` (if it doesn't already exist).
2. Place the theme's `userChrome.css` inside it.
3. Place `userContent.css` there too, if the theme includes one.

Your folder structure should look like this:

```text
Firefox Profile/
│
├── chrome/
│   ├── userChrome.css
│   └── userContent.css
│
├── prefs.js
├── places.sqlite
└── ...
```

### Step 4. Enable custom stylesheets

Firefox needs one additional setting enabled before it can load your custom CSS.

1. Open a new tab.
2. Navigate to `about:config`.
3. Search for:

   `toolkit.legacyUserProfileCustomizations.stylesheets`

4. Set its value to **true**.

You only need to do this once.

### Step 5. Restart Firefox

Save everything and completely close Firefox. Open it again, and your new theme should be ready!

---

## 2. Enjoy!

That's it! Enjoy your fresh, customized Firefox experience.

If something doesn't work, double-check that your files are in the correct folder and that custom stylesheets are enabled.

---

## 3. About This Project

This repository contains a collection of custom Firefox themes created using `userChrome.css` and other Firefox customization options.

**AI-assisted development (Vibe Coding)**

These themes are primarily created with the assistance of Claude. I provide the visual direction, design preferences, testing and iteration, while AI helps generate and modify the CSS.

I'm currently learning CSS to better understand, maintain and eventually develop these themes myself.

Contributions, suggestions and improvements are welcome!

---

## 4. Credits & Resources

**Wallpapers:**

A huge thanks to [orangci/walls-catppuccin-mocha](https://github.com/orangci/walls-catppuccin-mocha) for providing some of the wallpapers used in these themes.

All credit for the original wallpapers goes to their respective creators.

