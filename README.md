# Anywaa Multilingual Keyboard — starter project

This project provides an initial native Android keyboard (IME) and iOS custom
keyboard extension source.

## Alphabet (exact order supplied)
A Ä B C D DH E Ë G I Ï J K L M N NG NH NY O Ö Ø P R T TH U W Y

DH, NG, NH, NY and TH are individual one-tap keys.

## Android
Open this folder in Android Studio. Build and install the app. Then enable:
Settings → System (or General management) → Keyboard → On-screen keyboard →
Manage keyboards → Anywaa Multilingual Keyboard.

The app is a keyboard service, not a normal typing screen. Android settings
wording differs by device.

## iPhone
See `ios/README-iOS.txt`. An iOS Custom Keyboard Extension must be added in
Xcode on a Mac, built, signed, installed, and enabled in iPhone Settings.

## Current prototype scope
- Anywaa mode with the exact 29-key alphabet in the supplied order.
- English QWERTY mode.
- Basic Amharic Ethiopic character-entry mode.
- Space, punctuation, delete, return, and language cycling.
- Green key appearance.

## Not yet implemented
- Full Amharic fidel/vowel-series layout and punctuation set.
- Numbers/symbols page (the current ?123 key is a placeholder).
- Shift/caps-lock behavior, autocorrect, suggestions, dictionary, swipe typing,
  clipboard, emoji panel, sound/vibration, and accessibility polish.
- Automated UI tests, device testing, release signing, store listing, and publishing.

This is a source-code prototype, not a signed APK or App Store-ready release.
The green shades are starter values. Review the alphabet and Amharic layout
with fluent speakers before public release.
