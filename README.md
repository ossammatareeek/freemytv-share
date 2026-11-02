# Free My TV: install guide

A clean home screen for Google TV (made on a Haier Google TV, Android 12 or newer). Weather, prayer times,
football, Quran radio, sleep timer, a calmer screensaver. One switch brings the original home screen back.

Takes about 10 minutes. Steps 1 to 3 are on the TV only. Step 4 needs a Windows PC on the same Wi-Fi, once.

## 1. Install Downloader

On the TV: **Google Play Store** → search **Downloader** (by AFTVnews) → **Install**.

## 2. Let Downloader install apps

**Settings → Privacy → Security & restrictions → Unknown sources** → turn on **Downloader**.
(On some TVs: Settings → Apps → Security & restrictions.)

## 3. Download and install Free My TV

1. Open **Downloader**, allow it to access files if asked.
2. In the box, type the code **`1213989`** (or the link `https://github.com/ossammatareeek/freemytv-share/releases/latest/download/FreeMyTV.apk`) → **Go**.
3. When it finishes, press **Install**. If Google Play Protect warns you, choose **More details → Install anyway**.
4. Press **Done**, then **Delete** to remove the downloaded file (the app stays installed).

Free My TV now shows up in your apps. You can open it, but pressing **Home** still goes to the Google TV
home screen. Step 4 fixes that.

## 4. Make it the home screen (once, from a PC)

Google TV has no "choose your home app" setting, so the switch is made by the app itself through the TV's
developer mode. A PC opens that door once.

**On the TV, turn on developer mode:**
1. **Settings → System → About** → scroll to **Android TV OS build** → press OK on it **7 times** until it
   says you're a developer.
2. Back to **Settings → System → Developer options** → turn on **USB debugging** and **Wireless debugging**.

**On a Windows PC on the same Wi-Fi:**
1. Download `setup-tv.bat` and `setup-tv.ps1` from https://github.com/ossammatareeek/freemytv-share/releases/latest into one folder.
2. Double-click **setup-tv.bat** and answer its questions. It reads the IP, port and pairing code you see on the
   TV's **Wireless debugging** screen (**Pair device with pairing code**).

**Back on the TV:**
1. Open **Free My TV** → **Home Screen** → **Free My TV**.
2. The TV asks **Allow USB debugging?** → tick **Always allow** → **Allow**.
3. Wait a few seconds. Press **Home**: it's Free My TV now, and it stays that way after restarts.

## Good to know

- **Going back:** Free My TV → Home Screen → **Original** puts everything back as it was. A few promo apps are turned
  off while Free My TV is on (never uninstalled); Original turns them back on.
- **Your shelf:** on the home screen, hold **OK** on an app to move it or remove it; add any app from **All Apps**.
- **Language:** follows the TV (Arabic, English or Portuguese). Weather and prayer times are set for Cairo; movie and series picks come from TMDB.
- **Before uninstalling Free My TV**, switch to **Original** first.
- **After the TV restarts**, the home screen stays. If you ever want to switch modes again and it says debugging is
  off, run setup-tv.bat again.
