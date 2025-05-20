# ⭐ Quick Search - Zen Browser ⭐
Script to quickly search for a word or phrase in the Zen Browser through a pop up thus removing the need to create and swtich to a new tab.

## Search Popup

https://github.com/user-attachments/assets/95702ac2-96bf-478e-8e47-0afa4916c1c2


## Glance Mode




https://github.com/user-attachments/assets/827215fc-e985-4f71-8646-6e3a6b7e624b




## 🔧 Installation
1. Enable userChrome Customizations: In about:config go to toolkit.legacyUserProfileCustomizations.stylesheets and set it to true.

2. Install and Setup the userChrome.js Loader from [Autoconfig](https://github.com/MrOtherGuy/fx-autoconfig/tree/master)

### 3. The `zen.urlbar.replace-newtab` in `about:config` case:
- If set to `false`:
  - The `quickSearch.uc.js` will not work as intended as Ctrl+T will open a new tab instead of the url bar.
  - Thus please use `quickSearch_NoBar.uc.js` instead. This adds a Search Box inside the pop up thus not needing to open the url bar.
  - Copy and paste the `quickSearch_NoBar.uc.js` file to your `chrome/JS` folder.
  - Thanks to @Logic for the idea <3
  
- If set to `true`:
    - Copy and paste the `quickSearch.uc.js` file to your `chrome/JS` folder.

4. Open Zen browser, go to `about:support` and clear the startup cache.

Enjoy ^^


## ⚙️ Configuration

- Default search engine is set to Google. You can change it by modifying the `defaultEngine` variable in the script config (line 125). 

Additional search engines present:

- DuckDuckGo: `d:`
- Bing: `b:`
- Ecosia: `e:`
- Stackoverflow: `so:`
- Github: `gh:`
- Wikipedia: `wiki:`


- You can change the css of the popup by modifying the `injectCSS` variable in the script (line 14).


- Line 420 addes parameters to the search engine URL. You can add more parameters there.


## 🔍 Usage
### For the `quickSearch.uc.js` file:
- Open the url bar and type whatever you want to search for.
- Press `Ctrl + Enter` to open the search popup.
- Press `Ctrl + Shift + Enter` to open the search popup in a Glance Mode.

### For the `quickSearch_NoBar.uc.js` file:
- Press `Ctrl+Enter` to open the search popup.
- Then press `Enter` to search the query.

