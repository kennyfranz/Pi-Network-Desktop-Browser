# Pi-Network-
Pi Desktop Browser

Step by step
- First add tampermonkey ext to your browser: chrome or firefox preferably
tampermonkey firefox link: https://addons.mozilla.org/en-US/firefox/addon/get-tamper-monkey/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search

tampermonkey Chrome web store link: https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?authuser=0&utm_source=app-launcher
- Add/enable both .js scripts in tampermonkey. Download the zip file containing the scripts from my Google Drive using the link provided below.
https://drive.google.com/file/d/1oOwgqQTDGFOgz8oOxjqbufkg02bFJWtZ/view?usp=drive_link

- Open the first link listed below (HOME page) and connect your desktop browser to your Pi account using the node api when prompted (open mining app on phone, menu, node). After successfully linking your browser with the node API code you should now be able to access your Pi account through a Pi Desktop Browser (within a Chrome or Firefox tab like any web2 site) by using the links below. Using the first link should take you to your Pi Browser home page with the Pi Browser apps list. You can now use your desktop browser as you would your Pi Browser (mobile).

Pi Desktop Browser Links
- HOME page: https://app-cdn.minepi.com/mobile-app-ui/home

- chat app: https://app-cdn.minepi.com/mobile-app-ui/app/chat

- KYC app: https://app-cdn.minepi.com/mobile-app-ui/app/kyc

- Main mining page: https://app-cdn.minepi.com/mobile-app-ui/feed
etc,.

From here f12 and f5 should work to inspect the specific website data within the Pi Browser web pages.  If the function keys aren't working, just `right click` and hit `inspect` instead of f12 & `command R` on Mac instead of f5 to refresh. Not needed until you are in the `chat app`.

So...
- Now open the `CHAT` app by clicking the chat app icon on the home page of the Pi Browser (1st Pi Browser Link: `HOME page`)

To get your `uid` from inside the chat app:
- `f12` or `inspect` (from right click)
- `Command R` to refresh site data on Mac
- select `Network` from the menu bar inside the inspection box (probably between performance & sources - or close to them)
- go to the search field (🔍find) at the top left part of the inspector box. Type in `profile` then search `(hit enter)`. At the bottom of the search results you should see  `'>me -- socialchain.app/api/me'`
- Click the drop-down arrow `(>)` or just double click on ...`socialchain.app/api/me`. It will then show your profile details including your `uid`.
- copy the `uid` listed in the profile data. Be sure not to copy the regular **"id"** listed first in the profile data, you want the `uid` listed after
`...,"display_name":"@Milicent","trusted":true,"uid":"here is where your number shows (16 digits I think)",...`

These instructions are from chrome browser but should be fairly similar for Firefox. If you need help lmk.

