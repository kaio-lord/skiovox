# Skiovox writeup by divinelordkaio
Updated 5/4/24

# Original Methods (Patched v119)
https://skiovox.netlify.app


# 120 Method, Updated (divinelordkaio and zeglol) (Patched v120-v121)
- Log out of your device and turn off WiFi (does not work on lock screen).
- Press "Add person" button, then press esc. Alternatively, you can press CTRL + ALT + SHIFT + R and then cancel the powerwash.
- Enter the testing app of your choice and press "alt+shift+s" at the same time. The quick settings menu should pop up.
- Wait until you reach the network screen and press the accessibility menu and then the question mark "?". This opens the kiosk user's chrome instance.
- Press the link "Sign in as existing user", and esc. This should take you to the login screen and log in quickly.
if  it says "multi profile behaviour is disabled" press esc.
- Close school tab if you want, I recommend keeping it open so you can setup skiovox breakout
- Go to chrome://network on the skiovox window, open devtools, run `chrome.networkingPrivate.enableNetworkType('All');` to turn wifi back on.
