# IMPORTANT: Since version 0.0.266, Discord now runs natively on M1 Macs, with all the features (screen-share, Rich Presence etc…)
# This repo is no longer useful. That's why it is now archived.

# Discord on Apple Silicon

We will create a native version of Discord running natively on Apple Silicon chips.

## Get started

#### 1. First, if you haven't already done so, install Homebrew: https://brew.sh/

#### 2. Then, download the icon "discord.icns" and "discord.js" (above in the repo)

#### 3. Open a Terminal window, then execute the command ```cd ~/Downloads```

#### 4. Install Nativefier with npm: ```npm install nativefier```
####               or with Homebrew: ```brew install nativefier```

#### 4. Enter the following command:

```
nativefier \
  --background-color '#23272A' \
  --browserwindow-options '{ "fullscreenable": "true", "simpleFullscreen": "false" }' \
  --counter \
  --darwin-dark-mode-support \
  --enable-es3-apis \
  --icon discord.icns \
  --inject discord.js \
  --title-bar-style hiddenInset \
  https://discord.com/app
  ```

#### 5. Go to your "Downloads" folder, open the "Discord-darwin-arm64" folder and drag it into your "Applications" folder.

#### 6. Run the app!
