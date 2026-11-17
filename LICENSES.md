# Navigation — Open-source licenses

Navigation 1.0 is built on the CoMaps map and routing engine and uses the open-source components and data below. The full list with license texts is in the app (Settings → About → Licences).

## App

| Component | Version | License | Source |
|---|---|---|---|
| CoMaps (map engine, search, routing; includes Organic Maps and MAPS.ME code) | 2026.11.07-16 | Apache 2.0 | https://codeberg.org/comaps/comaps |
| Kotlin standard library | 2.2.20 | Apache 2.0 | https://kotlinlang.org |
| Jetpack Compose UI | 1.9.0 | Apache 2.0 | https://developer.android.com/jetpack/androidx |
| Jetpack Compose Foundation | 1.7.6 | Apache 2.0 | https://developer.android.com/jetpack/androidx |
| Compose Material 3 | 1.3.1 | Apache 2.0 | https://developer.android.com/jetpack/androidx |
| AndroidX Activity Compose | 1.9.3 | Apache 2.0 | https://developer.android.com/jetpack/androidx |
| AndroidX AppCompat | 1.7.1 | Apache 2.0 | https://developer.android.com/jetpack/androidx |
| AndroidX Core | 1.17.0 | Apache 2.0 | https://developer.android.com/jetpack/androidx |
| AndroidX Lifecycle ViewModel Compose | 2.9.4 | Apache 2.0 | https://developer.android.com/jetpack/androidx |
| AndroidX Media3 Session | 1.5.1 | Apache 2.0 | https://github.com/androidx/media |
| Material Components for Android | 1.12.0 | Apache 2.0 | https://github.com/material-components/material-components-android |
| Guava | 33.3.1-android | Apache 2.0 | https://github.com/google/guava |
| JSpecify | 1.0.0 | Apache 2.0 | https://jspecify.dev |
| JetBrains annotations | 23.0.0 | Apache 2.0 | https://github.com/JetBrains/java-annotations |
| Tabler Icons | — | MIT | https://tabler.io/icons |
| Lato | — | SIL Open Font License 1.1 | https://www.latofonts.com |

## Map data

| Data | License | Source |
|---|---|---|
| OpenStreetMap | ODbL 1.0 | https://www.openstreetmap.org/copyright |

Maps are downloaded from the CoMaps servers; they are not inside the APK.

## Inside the CoMaps engine

| Component | License |
|---|---|
| Boost | Boost Software License |
| ICU | ICU License |
| FreeType | FreeType License (FTL) |
| Expat | MIT |
| Protobuf | BSD |
| Pugixml | MIT |
| GLM | MIT |
| Jansson | MIT |
| glaze | MIT |
| UTF8-CPP | Boost Software License |
| succinct | Apache 2.0 |
| libkdtree++ | Artistic License |
| Anti-Grain Geometry | AGG License |
| bsdiff, Chromium Courgette | BSD |
| Open Location Code | Apache 2.0 |
| Monocypher | BSD 2-Clause / CC0 |
| Skarupke and Ankerl hash tables | Boost Software License / MIT |
| Vulkan Headers, Vulkan Wrapper | Apache 2.0 |

## Map fonts and icons (from CoMaps)

| Component | License | Source |
|---|---|---|
| Noto Naskh Arabic, Noto Sans Bengali, Hebrew, Malayalam, Thai, Noto Serif Devanagari | SIL Open Font License 1.1 | https://github.com/notofonts |
| Roboto | Apache 2.0 | https://github.com/googlefonts/roboto |
| Droid Sans Fallback | Apache 2.0 | https://android.googlesource.com/platform/frameworks/base |
| DejaVu Sans | Bitstream Vera / DejaVu License | https://dejavu-fonts.github.io |
| Jomolhari | SIL Open Font License 1.1 | https://github.com/christopherfynn/jomolhari |
| Padauk | SIL Open Font License 1.1 | https://software.sil.org/padauk |
| Khmer OS | LGPL 2.1 | https://codeberg.org/comaps/comaps/src/tag/v2026.11.07-16/data/fonts/05_khmeros.ttf (unchanged font file used in the app) |
| Map icons: Material Design Icons, Remixicon (Apache 2.0); Tabler, Nova, Bytesize (MIT); Font Awesome Free, Boxicons, OnlineWebFonts, Röntgen, Panoramax, old MAPS.ME icons (CC BY 4.0); Entypo (CC BY-SA 3.0); Evericon, Maki, OpenStreetMap Carto, Temaki (CC0 1.0); Freepik (Freepik Free License) | as listed | https://codeberg.org/comaps/comaps/src/branch/main/data/copyright.html |

Versions of the Android libraries are taken from the build's dependency list (release runtime classpath). The CoMaps list is from its copyright notice (`data/copyright.html`), as shipped in the app.
