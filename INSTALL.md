# Install — any Android phone

## Get the pack

- GitHub **Releases** → download `rick-and-morty-android-theme-x.y.z.zip`
- Or clone the repo and copy the folder to your phone

### ADB

```bash
adb push wallpapers /sdcard/Pictures/RickAndMorty/Wallpapers/
adb push icons /sdcard/Pictures/RickAndMorty/Icons/
adb shell content call --uri content://media/external/file \
  --method scan_volume --extra volume:s:external_primary
```

## Set wallpapers

1. Open **Photos** or **Gallery**
2. Browse to the theme folder
3. Open a `.jpg` → **Use as / Set as wallpaper**
4. Home, Lock, or both
5. **Settings → Wallpaper & style** → choose a green/teal palette

### Samsung

Long-press home → **Wallpaper and style** → Gallery → pick image.

### GrapheneOS

Use Photos/Gallery. If Files says can’t open, open from Photos instead.

## Icons & profile

| Use | File |
|-----|------|
| Profile | `icons/rick-style-avatar` or `morty-style-avatar` |
| Fun avatar | `icons/meeseeks-blob` |
| Shortcut art | `portal-gun`, `green-portal-ring`, `green-flask`, `spaceship-saucer` |

App icons stay stock unless you use Lawnchair/Nova + an icon pack.

## Uninstall

Delete the folder and change wallpaper. Nothing is system-installed.
