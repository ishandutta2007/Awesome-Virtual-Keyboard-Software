# Awesome-Virtual-Keyboard-Software

## Top Virtual Keyboard Software Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Privacy-First Typing, Accessibility Input & Customizable Keyboard Layouts*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Virtual Keyboard Software**. These tools provide on-screen text input for mobile devices, desktops, tablets, and accessibility use cases — from privacy-focused Android keyboards to assistive technology for users with motor impairments.



**Examples** include Microsoft SwiftKey, Gboard, Fleksy, Typewise, Chrooma Keyboard, AnySoftKeyboard, Minuum, Grammarly Keyboard, Simple Keyboard, and Facemoji Keyboard (the category leaders).



**Open-source emphasis**: Virtual keyboards are one of the strongest open-source domains, with **HeliBoard**, **FlorisBoard**, **FUTO Keyboard**, and **AnySoftKeyboard** leading Android privacy alternatives . On desktop, **Onboard**, **Florence**, and **Maliit** provide accessible on-screen input for Linux and Windows . **Keyman** supports 1,000+ language layouts across every major platform . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Microsoft SwiftKey](https://www.microsoft.com/swiftkey)**  

  AI-powered keyboard with strong text prediction and learning capabilities. Cross-device sync via Microsoft account. **Closed source** with data collection for prediction models .



- **[Gboard](https://play.google.com/store/apps/details?id=com.google.android.inputmethod.latin)**  

  Google's default keyboard with voice typing, glide typing, and integrated search. **Deep Google services integration** raises privacy concerns for some users .



- **[Fleksy](https://www.fleksy.com/)**  

  Guinness World Record holder for fastest touchscreen typing. Proprietary keyboard SDK with swipe typing and extensive customization. **Closed source** with SDK licensing for developers .



- **[Typewise](https://typewise.app/)**  

  Privacy-focused keyboard with hexagonal layout and large keys designed to reduce typos. Available on Android and iOS.



- **[Chrooma Keyboard](https://play.google.com/store/apps/details?id=ch.smalltech.ledger)**  

  Color-adaptive keyboard with themes that match app colors. **Closed source** with limited updates in recent years.



- **[Grammarly Keyboard](https://www.grammarly.com/keyboard)**  

  Writing assistant keyboard with grammar checking and tone suggestions. **Cloud-based processing** for language analysis .



- **[Facemoji Keyboard](https://facemoji.com/)**  

  Emoji and sticker-focused keyboard with AI-powered suggestions. **Closed source** with advertising and data collection.



## Open-Source GitHub Projects



- **[HeliBoard](https://github.com/HeliBorg/HeliBoard)**  

  **The leading open-source Android keyboard** and the top-ranked Gboard alternative, built from the AOSP keyboard lineage (fork of OpenBoard) . **Zero network permissions** — operates entirely offline with locally-added dictionaries for suggestions . Supports gesture typing (requires separate library), one-handed mode, split keyboard, clipboard history, incognito mode, and extensive theme customization . **Not available on Google Play** — distributed via F-Droid and GitHub to maintain open-source principles . **The best choice for privacy purists wanting full keyboard functionality**.



- **[FlorisBoard](https://github.com/florisboard/florisboard)**  

  **Modern-looking open-source Android keyboard** balancing privacy and usability with a cleaner interface than HeliBoard . Features multi-language support, split and one-handed modes, incognito mode, integrated clipboard manager, gesture support, and secondary keyboard layouts for quick language switching . **Currently in beta** — word suggestions and spell checking are still in development . **The best choice for users wanting a polished, customizable typing experience**.



- **[AnySoftKeyboard](https://github.com/AnySoftKeyboard/AnySoftKeyboard)**  

  **The closest open-source alternative to Gboard** with the longest development history . Supports multiple languages via external packs, QWERTY/Dvorak/AZERTY layouts, voice typing, gesture typing, auto-correction, and word suggestions . Features **incognito mode** for sensitive input (PINs, passwords) that disables learning and prediction . Highly customizable with per-app tint themes. **The most feature-complete open-source keyboard** for users wanting maximum functionality.



- **[FUTO Keyboard](https://github.com/futo-org/keyboard)**  

  **Direct Gboard replacement** with on-device AI models for text prediction and voice typing . **No keystrokes leave the device** — fully offline Whisper-based voice model . Smooth spacebar cursor movement, resizable keyboard, permanent number row option, and extensive long-press customization . **The best choice for users wanting Gboard-like AI features without cloud dependency**.



- **[Onboard](https://github.com/onboard-osk/onboard)**  

  **The leading open-source on-screen keyboard for Linux desktops**, designed for tablet users and people with mobility impairments . Works out of the box by reading the keyboard layout from the X server . Features auto-click timer for users with difficulty clicking, scalable interface, and extensible layouts. **Primarily X11** with experimental Wayland support . **The de facto accessible keyboard for GNOME and Ubuntu**.



- **[Florence Virtual Keyboard](https://florence.sourceforge.net/)**  

  **Extensible scalable virtual keyboard for GNOME**, appearing on screen only when needed . Designed for users who cannot use hardware keyboards — including disabled users, tablet PC users, or broken keyboard scenarios . Requires a pointing device (mouse, trackball, touchscreen). **GPL-2.0 licensed** with auto-click functionality for accessibility . **A mature, stable alternative to Onboard**.



- **[Maliit](https://github.com/maliit/keyboard)**  

  **Flexible cross-platform input method framework** for mobile and embedded text input . Plugin-based client-server architecture supporting Wayland and X11 . Includes a reference virtual keyboard supporting many languages and emoji . **The standard input framework for Linux mobile** (Plasma Mobile, Ubuntu Touch) .



- **[Keyman](https://keyman.com/)**  

  **Free and open-source keyboard engine supporting 1,000+ languages** across Android, iOS, macOS, Linux, Windows, and web . Creates custom keyboard layouts with rules that transform invalid sequences into valid ones before reaching the document . **The most comprehensive multilingual keyboard solution** — reduces training requirements and improves data quality for less-resourced languages .



- **[Simple Keyboard](https://github.com/rkkr/simple-keyboard)**  

  **Minimalist, lightweight Android keyboard** under 1MB with only vibrate permission . No emojis, GIFs, spell checker, or swipe typing — just core typing functionality . Limited themes and customization. **The best choice for users wanting the simplest possible keyboard** with minimal attack surface.



### Additional Strong Open-Source Options



- **Plasma Keyboard** — Qt Virtual Keyboard based, designed for Plasma desktop and mobile integration .

- **wvkbd** — Minimal wlroots on-screen keyboard written in legible C for Wayland compositors .

- **squeekboard** — Wayland on-screen keyboard input method, used by Phosh (PinePhone) .

- **xvkbd** — Virtual keyboard for X Window System, useful for kiosk terminals without hardware keyboards .

- **CoreKeyboard** — X11-based virtual keyboard with word suggestions working across all desktop environments .

- **Dasher** — Information-efficient text entry via continuous pointing gestures, ideal for full-size keyboard replacement scenarios .

- **ERICK Keyboard** — Accessible virtual keyboard using dual-dial chord input for touch, controller, and gamepad typing with full offline privacy .



**Frameworks for building custom virtual keyboard solutions**: Combine **HeliBoard** for maximum privacy and offline operation on Android, **AnySoftKeyboard** for feature richness and customization, and **FUTO Keyboard** for on-device AI prediction and voice typing . For Linux desktop accessibility, use **Onboard** or **Florence** . For multilingual and custom layout development, **Keyman** provides the most comprehensive engine supporting 1,000+ languages . For minimal attack surface, **Simple Keyboard** offers core functionality under 1MB .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Virtual keyboards can capture every keystroke typed on a device. **Privacy-focused open-source keyboards (HeliBoard, FlorisBoard, AnySoftKeyboard) do not request network permissions**, but users should verify permission settings after installation .

- **Gesture typing libraries may be closed-source** even in open-source keyboards — check licenses before assuming full FOSS compliance .

- **Accessibility keyboards (Onboard, Florence, Dasher)** are designed for users with motor impairments — testing with actual users is recommended before deployment in assistive contexts .

- The open-source ecosystem provides strong privacy, customization, and accessibility foundations, but cloud-based AI features (Gboard's voice typing, Grammarly's grammar checking) remain primarily commercial offerings.



---



**Made for privacy-conscious users, accessibility advocates, and developers building custom text input solutions.**  

Let's make virtual keyboards more open, transparent, and accessible.
