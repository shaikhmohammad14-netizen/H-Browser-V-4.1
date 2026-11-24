# H Browser — Liquid Glass Edition (v4.0)

A Kotlin + Jetpack Compose Android browser starter project using Android WebView.

## Included
- Liquid-glass inspired translucent surfaces, layered gradients, reflective borders, depth shadows and springy press feedback.
- Aurora, Ocean, Violet, Emerald, Rose, Amber and Mono theme palettes, plus light/dark appearance.
- UC-style quick access home layout with common site shortcuts and Explore categories.
- WebView browsing, address/search, Google/Bing/DuckDuckGo/Brave search choices, bookmarks, browsing history, downloads, share page, find on page, desktop-site option, zoom, JavaScript and cookie controls.
- Basic host-list ad/tracker blocking (not a full EasyList/AdGuard filter engine).
- Edge-to-edge layout with status/navigation bar insets.
- GitHub Actions workflow builds `:app:assembleDebug` and uploads the APK artifact.

## Build on GitHub
1. Upload the contents of this ZIP into the root of your GitHub repository, preserving folders.
2. Open the **Actions** tab and run **Build H Browser** (or push a commit to `main`/`master`).
3. Open the completed workflow run and download the `H-Browser-Liquid-Glass-debug` artifact.

## Important limitations
This is a functional WebView-based browser foundation, not a full Chromium replacement. The tab counter/new-tab interface is a basic placeholder and does not yet maintain separate independent WebView sessions. Incognito isolation, a full ad-filter subscription engine, sync/account services, and a built-in news recommendation backend are not implemented. The Explore shortcuts open their respective public websites.

Build environment: JDK 17, Gradle 8.9, Android Gradle Plugin 8.7.3, Kotlin 2.0.21, compile SDK 35.
