---
title: Best Browser Setup (Microsoft Edge)
permalink: /browser-setup/edge/
---

<!-- Replaced with new tab extension
## New Tab Settings

1. Open Microsoft Edge and go through the initial setup process if you haven't done that already.
1. Click the settings icon in the top-right corner of your new tab page.
1. Under _Quick Links & Search_, make sure _Show promoted links_ is turned off.
1. Make sure _Show content_ is turned off.
1. Choose a background image, or turn off the _Background_ option if you don't want one.

### If you don't see these options...
You probably have the new look enabled. Disable it.

If you don't have an option to disable it, please follow [these instructions](edge-newtab.md) to get a better new tab page.
-->

# Browser Settings
To get the best configuration in Microsoft Edge, you should start by changing some settings.

## Basic Browser Settings
1. Click the three dots in the top-right corner, then click _Settings_.
1. Make the following changes to your browser settings:
    - **_Profiles_ >> _Microsoft Rewards_ >> _Earn Microsoft Rewards in Microsoft Edge_** - Turn this off.
    - **_Copilot and AI_ >> _Show Copilot button in toolbar_** - If you want to, you can turn this off.
    - **_Start, home, and new tab page_ >> _Show home button on the toolbar_** - Turn this on, and make sure it's set to "New tab page".
    - **_Start, home, and new tab page_ >> _Preload your new tab page_** - If you have a slow computer, turn this off.
    - **_Start, home, and new tab page_ >> _Automatically open Edge when you sign into Windows_** - Make sure this is turned off.
    - **_Languages_ >> _Writing assistance_ >> _Use 'Help me write' writing assistant on the web_** - Turn this off.
        - Also turn off text prediction.
    - **_System and performance_ >> _System_ >> _Continue running background extensions and apps when Edge is closed_** - Turn this off.

### Appearance Settings
1. Change the following settings in `Appearance >> Toolbar`:
    - **Favourites bar:** Set to "Always".
    - **Forward:** Set to "Always show".
    - **Downloads** and **Favourites**: Set these according to your personal preferences.
1. In `Appearance >> Context menus`, turn off _Show mini menu when selecting text_.
1. In `Appearance >> Browser behaviour and features`, turn off _Show hover menu on image hover_.

### Configuring en-CA
If you are Canadian, follow [these instructions](edge-en-ca.md) to get the correct language settings. Otherwise, skip this step.

## Better Privacy & Security
1. Go to the _Privacy, search, and services_ section of your browser settings.
1. Under _Tracking prevention_, make sure it's set to _Balanced_ (the default setting). You'll get much better tracking protection later.
1. Under _Privacy_, turn on the _Send "Do Not Track" requests_ option, and turn off everything else.
1. Under _Security_, turn on _Enhance your security on the web_. You can disable it later if it breaks too many websites.
    - If a website is broken because of this setting, you can disable it for that website by clicking the lock icon on the left of the address bar.
    - If you use GitHub Codespaces in your browser, you should add `*.github.dev` as an exception.
1. Under _Search and connected experiences_, turn off _Save time and money with Shopping in Microsoft Edge_.
1. Under _Search and connected experiences_, go to _Address bar and search_ and change your search engine to Google or DuckDuckGo. Do not use Bing (the default setting).

## Don't Save My Info
By default, most browsers (including Edge) will save your passwords and other autofill information. This is insecure and can be easily accessed by malware, so you should disable it.
<!-- REMEMBER: Add note with link to password manager guide -->

1. Go to the _Passwords and autofill_ section of your browser settings.
1. Under _Microsoft Password Manager_, turn off _Ask to save passwords and passkeys_.
1. Under _Payment methods_, turn off _Save and fill payment methods_.
1. Under _Addresses and more_, turn off _Save and autofill addresses_.

# Extensions
The most important part of this browser setup is the extensions. These will block ads and trackers, improve your privacy, and protect your device from malware.

Make sure you follow all the instructions.

## uBlock Origin
1. Open this link in Microsoft Edge: https://microsoftedge.microsoft.com/addons/detail/ublock-origin/odfafepnkmbhccpbejgmiehpchacaeak
1. Click the blue _Get_ button, then click _Add extension_.
1. Click the puzzle piece icon, then click the pin button next to _uBlock Origin_.
1. Click the uBlock Origin icon in your toolbar, then click the gears icon ([click here](images/ubo-popup-arrows.png) to see an image with arrows pointing to the buttons to click).
1. Click on the _Filter lists_ tab at the top of the page that opens.
1. Turn on the following checkboxes (you can expand a category by clicking it):
    - _Ads_ >> _AdGuard - Ads_
    - _Privacy_ >> (turn on everything in this category)
    - _Malware domains_ >> _Phishing URL Blocklist_
    - _Cookie notices_ >> (turn on everything in this category)
    - _Annoyances_ >> _uBlock filters - Annoyances_
    - _Annoyances_ >> _AdGuard - Annoyances_ >> _AdGuard - Popup Overlays_
    - _Annoyances_ >> _EasyList - Annoyances_ >> _EasyList - Newsletter Notices_
    - _Annoyances_ >> _EasyList - Annoyances_ >> _EasyList - Other Annoyances_
1. Click the _Import..._ category to expand it and reveal a textbox.
1. Paste the following text into the textbox:
    ```
    https://big.oisd.nl
    https://filters.adtidy.org/extension/ublock/filters/3.txt
    ```
1. Put the cursor at the end of the pasted text and press <kbd>Enter</kbd> to add a line feed.
1. Click on the blue _Apply changes_ button at the top of the page.

## OptMeowt
1. Open this link in Microsoft Edge: https://chromewebstore.google.com/detail/optmeowt/hdbnkdbhglahihjdbodmfefogcjbpgbo
1. Click the _Get extension_ button at the top of the page.
    - If you don't see this button, click the blue _Get_ button.
1. If you see a popup asking about "extensions from other stores", click _Allow_.
1. Click _Add extension_.

## Decentraleyes
1. Open this link in Microsoft Edge: https://microsoftedge.microsoft.com/addons/detail/decentraleyes/lmijmgnfconjockjeepmlmkkibfgjmla
1. Click the _Get_ button, then click _Add extension_ in the popup that appears.
1. Close/ignore the new tab that opens.

## Consent-O-Matic
1. Open this link in Microsoft Edge: https://microsoftedge.microsoft.com/addons/detail/consentomatic/eflcfflijdiekjkegjghbchoncjhfkda
1. Click the blue _Get_ button, then click _Add extension_.
1. A new tab will open. Set your cookie preferences, then close the tab.

## TrafficLight
1. Open this link in Microsoft Edge: https://chromewebstore.google.com/detail/trafficlight/cfnpidifppmenkapgihekkeednfoenal
1. Click the _Get extension_ button, then click _Add extension_.
1. Click the puzzle piece icon in the toolbar.
1. Click _TrafficLight_, then click the settings icon in the top-right corner of the popup that appears.
1. Turn off the _Search Advisor_ setting.

## Don't track me Google
1. Open this link in Microsoft Edge: https://chromewebstore.google.com/detail/dont-track-me-google/gdbofhhdmcladcmmfjolgndfkpobecpg
1. Click _Get extension_ and then _Add extension_.

# Transferring Bookmarks
If you want to transfer your bookmarks to Edge from another browser, go to the _Profiles_ section of your browser settings and click on _Import browser data_. Choose the option for the browser you want to import from, uncheck all options except _Favourites or bookmarks_, and click the _Import_ button.

# Important Notice
If uBlock Origin ever breaks a website, click the red shield icon to the right of the address bar, click the giant power button, and reload the page. This will disable uBlock Origin for that website.

---

You should now have the best web browser setup.
