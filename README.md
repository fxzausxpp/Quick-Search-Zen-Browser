# ⭐ Quick Search - Zen Browser ⭐
Script to quickly search for a word or phrase in the Zen Browser through a pop up thus removing the need to create and swtich to a new tab.

## 🔧 Installation
1. Enable userChrome Customizations: In about:config go to toolkit.legacyUserProfileCustomizations.stylesheets and set it to true.

2. Install and Setup the userChrome.js Loader from [Autoconfig](https://github.com/MrOtherGuy/fx-autoconfig/tree/master)

3. Copy and paste the `quickSearch.uc.js` file to your `chrome/JS` folder.

4. Open Zen browser, go to `about:support` and clear the startup cache.

Enjoy ^^


## ⚙️ Configuration

- Default search engine is set to Google. You can change it by modifying the `defaultEngine` variable in the script config (line 125). 

Additional search engines present:

- DuckDuckGo: `d:`
- Bing: 'b:`
- Ecosia: 'e:`
- Stackoverflow: `so:`
- Github: `gh:`
- Wikipedia: `wiki:`


- You can change the css of the popup by modifying the `injectCSS` variable in the script (line 14).


- Line 420 addes parameters to the search engine URL. You can add more parameters there.


## 🔍 Usage
- Open the url bar and type whatever you want to search for.
- Press `Ctrl + Enter` to open the search popup.

