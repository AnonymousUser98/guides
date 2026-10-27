---
title: Recommended Browser Setup (Firefox)
permalink: /browser-setup/firefox/
---

## Installing Firefox
If it isn't already on your computer, go to [firefox.com](https://www.firefox.com/) to download and install Firefox.

## Initial Setup

1. You will be asked to import data from another browser. This allows you to easily import your bookmarks. Choose where to import from and what to import, then click _Import_. **Do not import saved passwords;** saving them in your browser is insecure. If you don't want to import your data, click the _Skip this step_ button in the bottom-right corner.
1. Choose the visual colour theme you prefer, then click _Save and continue_.
1. When asked about recommended extensions, click the _Skip this step_ button in the bottom-right corner.
1. When asked to sign in and sync, just click the _Start browsing_ button in the bottom-right corner.
1. If a settings window opens asking you to set Firefox as your default browser, just close it. You can set this option later.


## Browser Settings
Click the menu icon (3 lines) on the right of the toolbar and click _Settings_.\
Make the following changes in settings:

### Home and startup

- If you **don't** want to use Firefox as your default browser: Make sure _Always check if Firefox is your default browser_ is unchecked.
- In the _Firefox Home_ subsection: Turn off the _Weather_, _Stories_, and _Support Firefox_ options.

### Search

Choose the default search engine you prefer. I recommend using Startpage if you want to get accurate search results from Google without having to worry about the tracking. Google and DuckDuckGo are other popular choices.

To use Startpage as your search engine, click the _Add search engine_ button and copy and paste the following text into the URL field:
```
https://www.startpage.com/sp/search?query=%s
```

### Privacy and security

1. Click the _Advanced settings_ option under _Enhanced Tracking Protection_.
1. Choose _Strict_ from the list of options.
1. Make sure _Fix major site issues_ and _Fix minor site issues_ are both checked.
1. Go back to the root page of the _Privacy and security_ section.
1. Under _Additional protections_, make sure _Tell websites not to sell or share my data_ is checked.
1. Also under _Additional protections_, make sure _Suggest Firefox Relay email masks_ is unchecked.

### Passwords and autofill
By default, Firefox will ask you to save your passwords. This is insecure (it can be easily accessed by malware), so you should turn it off.

Make sure the following checkboxes are unchecked:
- Ask to save passwords
- Save and autofill payment info
- Save and autofill addresses

If you want to save your passwords, you should use a dedicated password manager (I recommend Bitwarden or KeePass).

### Tabs and browsing
Turn off both checkboxes in the _Recommendations_ subsection.

### AI controls
Because of how everyone has different opinions about AI, you should look at these settings and decide what to disable. For a traditional browsing experience, turn off everything except translations.

### Permissions and data
Turn off everything in the _Firefox data collection and use_ subsection.


## Setting Up Extensions
Extensions are what makes this configuration different from other browsers.

### uBlock Origin
1. Open this link in Firefox: https://addons.mozilla.org/firefox/addon/ublock-origin/
1. Click the blue _Add to Firefox_ button.
1. Click _Add_ in the thing that pops up.
1. Leave the _Pin extension to toolbar_ option checked and click OK.
1. Click the uBlock Origin icon in the toolbar.
1. Click the gears icon in the uBlock Origin popup.\
   <img width="300" src="../../browser-config/images/firefox/ubo-popup-arrows.png" />
1. Go to the _Filter lists_ tab at the top of the page that opens.
1. Turn on the following options (click a category to expand it):
   - Ads >> AdGuard - Ads
   - Privacy >> AdGuard/uBO - URL Tracking Protection
   - Privacy >> Block Outsider Intrusion into LAN
   - Malware protection, security >> Phishing URL blocklist
   - Cookie notices >> _Turn on everything in this category_
   - Annoyances >> EasyList - Annoyances >> EasyList - Newsletter Notices
   - Annoyances >> EasyList - Annoyances >> EasyList - Other Annoyances
   - Annoyances >> AdGuard - Annoyances >> AdGuard - Other Annoyances
   - Annoyances >> AdGuard - Annoyances >> AdGuard - Popup Overlays
   - Annoyances >> uBlock Filters - Annoyances
1. Copy the text `https://big.oisd.nl` into the _Import..._ textbox and press Enter to add a newline.
1. Click the blue _Apply changes_ button at the top of the page (and wait for it to load).

### Consent-O-Matic
1. Open this link in Firefox: https://addons.mozilla.org/firefox/addon/consent-o-matic/
1. Click the blue _Add to Firefox_ button.
1. Click _Add_ in the thing that pops up.
1. Leave the _Pin extension to toolbar_ option unchecked and click OK.
1. A new tab will open. Choose your cookie preferences, then close the tab.

### LocalCDN
1. Open this link in Firefox: https://addons.mozilla.org/en-CA/firefox/addon/localcdn-fork-of-decentraleyes/
1. Click the blue _Add to Firefox_ button.
1. Click _Add_ in the thing that pops up.
1. Leave the _Pin extension to toolbar_ option unchecked and click OK.
<!-- TO-DO: See if leaving Google Fonts blocked causes problems -->


## Optional Enhancements/Customization
<!-- TO-DO: Add instructions for YouTube Enhancer and SponsorBlock -->
<!-- TO-DO: Add instructions for the "Bypass All Shortlinks Debloated" userscript with Violentmonkey -->

### Customize Toolbar
Right-click anywhere to the left or right of the address bar and choose _Customize Toolbar..._ to open a new tab. From here, you can customize your toolbar.

Here's a suggestion:\
<img width="700" src="../../browser-config/images/firefox/toolbar-suggestion.png" />

When you're done, click _Done_ in the bottom-right corner.


### Set As Default Browser
If you want to use Firefox as your main web browser, you should go to **Settings >> Home and startup** and choose the option to set Firefox as your default browser. On Windows 11, a settings window will pop up, where you'll need to click the _Set default_ button.
