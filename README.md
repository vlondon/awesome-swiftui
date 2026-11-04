# Awesome SwiftUI [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

  * [General](#general)
    + [Apple](#apple)
    + [WWDC](#wwdc)
    + [Newsletter](#newsletter)
    + [Book](#book)
    + [Course](#course)
    + [Learning](#learning)
  * [Articles](#articles)
    + [Implementation](#implementation)
    + [Layout system](#layout-system)
  * [Libraries](#libraries)
    + [Extensions](#extensions)
    + [Image](#image)
    + [Inspection](#inspection)
    + [Property wrappers](#property-wrappers)
  * [UI](#ui)
    + [Animation](#animation)
    + [Button](#button)
    + [Calendar](#calendar)
    + [Chart](#chart)
    + [Color](#color)
    + [Clock](#clock)
    + [Countdown](#countdown)
    + [Confetti](#confetti)
    + [Drawer](#drawer)
    + [Form](#form)
    + [Gesture](#gesture)
    + [Grid](#grid)
    + [Icon](#icon)
    + [Indicator](#indicator)
    + [Keyboard](#keyboard)
    + [Loading](#loading)
    + [Onboarding](#onboarding)
    + [Page](#page)
    + [Picker](#picker)
    + [Pull to refresh](#pull-to-refresh)
    + [Toast](#toast)
    + [Slider](#slider)
    + [Window](#window)
    + [Others](#others)
  * [Open source apps](#open-source-apps)
    + [iOS](#ios)
    + [macOS](#macos)

## General

### Apple

- [Introducing SwiftUI](https://developer.apple.com/tutorials/swiftui) - Create beautiful, dynamic apps faster than ever before.
- [iOS App Dev with SwiftUI](https://developer.apple.com/tutorials/app-dev-training/) - Create apps using SwiftUI and Xcode. Build Scrumdinger, an app that keeps track of daily scrums
- [Creating a macOS App](https://developer.apple.com/tutorials/swiftui/creating-a-macos-app) - After creating a version of the Landmarks app for watchOS, it’s time to set your sights on something bigger: bringing Landmarks to the Mac
- [Creating Performant Scrollable Stacks](https://developer.apple.com/documentation/swiftui/creating-performant-scrollable-stacks)
- [Aligning Views Across Stacks](https://developer.apple.com/documentation/swiftui/aligning-views-across-stacks)
- [Building Layouts with Stack Views](https://developer.apple.com/documentation/swiftui/building-layouts-with-stack-views)

### WWDC

- [WWDC2019 SwiftUI Essentials](https://developer.apple.com/videos/play/wwdc2019/216/) - Take your first deep-dive into building an app with SwiftUI. Learn about Views and how they work 
- [WWDC0291 Data Flow Through SwiftUI](https://developer.apple.com/videos/play/wwdc2019/226/) - Learn how to connect your data as dependencies while keeping the UI fully predictable and error free
- [WWDC2020 Data Essentials in SwiftUI](https://developer.apple.com/videos/play/wwdc2020/10040/) - Discover @State and @Binding, two powerful tools that can preserve and seamlessly update your Source of Truth

### Newsletter

- [SwiftUI Weekly](http://weekly.swiftwithmajid.com/) - The curated collection of links about SwiftUI. Delivered every Monday
- [iOS Dev Weekly](https://iosdevweekly.com/) - Curated by Dave Verwer and published every Friday
- [iOS Goodies](https://ios-goodies.com/) - weekly iOS newsletter curated by Marius Constantinescu
- [Storefront Brief](https://fortune-insight.onrender.com/shop/brief/index.html) - English weekly on iOS/indie App Store fees, ASO, and storefront ops ([RSS](https://fortune-insight.onrender.com/shop/brief/feed.xml), [Issue 1](https://fortune-insight.onrender.com/shop/brief/issue-001-en.html))

### Book

- [Thinking in SwiftUI](https://www.objc.io/books/thinking-in-swiftui/) -  It is not a reference for SwiftUI’s platform-specific APIs, but rather a guide to honing your intuition about how SwiftUI works.
- [SwiftUI by Tutorials](https://www.raywenderlich.com/books/swiftui-by-tutorials/v2.0) - Build fluid and engaging declarative UI for your apps with way less coding with SwiftUI! SwiftUI by Tutorials
- [Mastering SwiftUI by AppCoda](https://www.appcoda.com/learnswiftui/) - We will dive deep into the SwiftUI framework, teaching you how to work with various UI elements, and build different types of UIs

### Course

- [SwiftUI for iOS 14](https://designcode.io/swiftui-ios14) - Build a multi-platform app from scratch using the new techniques in iOS 14. We'll use the Sidebar and Lazy Grids to make the layout adaptive for iOS, iPadOS, macOS Big Sur
- [SwiftUI Handbook](https://designcode.io/swiftui-handbook) - A comprehensive series of tutorials covering Xcode, SwiftUI and all the layout and development techniques
- [SwiftUI Layout explained](https://www.objc.io/blog/2020/12/24/swiftui-layout-explained/) - We decided to go one step further, and reimplement SwiftUI’s layout system, along with the layout behavior of many built-in views
- [TutorialSearch](https://tutorialsearch.io/) - Free cross-platform search engine indexing 50,000+ tutorials from Udemy, Skillshare, Pluralsight, and other major learning platforms across 45+ categories.

### Learning

- [100 days of SwiftUI](https://www.hackingwithswift.com/100/swiftui) - Free collection of videos, tutorials, tests, and more, all drawn from around the work on Hacking with Swift
- [About-SwiftUI](https://github.com/Juanpe/About-SwiftUI) - Gathering all info published, both by Apple and by others, about new framework SwiftUI.
- [SwiftUI](https://github.com/varabeis/SwiftUI) - Examples projects using SwiftUI released by WWDC2019. Include Layout, UI, Animations, Gestures, Draw and Data.
- [SwiftUI-Cheat-Sheet](https://github.com/SimpleBoilerplates/SwiftUI-Cheat-Sheet) - SwiftUI 2.0 Cheat Sheet
- [F* SwiftUI](https://fuckingswiftui.com/) - A curated list of questions and answers about SwiftUI.
- [The SwiftUI Lab](https://swiftui-lab.com/) - Advanced insights into SwiftUI
- [Netsplit SwiftUI](https://netsplit.com/swiftui)
- [SwiftUI by examples](https://www.hackingwithswift.com/quick-start/swiftui) - SwiftUI by Example is the world's largest collection of SwiftUI examples, tips, and techniques giving you over 400 pages of hands-on code
- [A Companion for SwiftUI](https://swiftui-lab.com/companion/) - A Companion for SwiftUI is an app that documents all the SwiftUI views, shapes, protocols, scenes and property wrappers for the iOS and macOS platform.
- [SwiftUI-Kit](https://github.com/jordansinger/SwiftUI-Kit) - A SwiftUI system components and interactions demo app
- [CodeSlicing](https://www.youtube.com/channel/UCakreohbcr3Xcrlc6qbbbVA) - Create things in SwiftUI

## Articles

### Build

- [Animating complex shapes in SwiftUI](https://nerdyak.tech/development/2020/01/12/animating-complex-shapes-in-swiftui.html)
- [TikTok logo-ish effect in SwiftUI](https://nerdyak.tech/development/2020/06/12/create-tiktok-logo-effect-in-swiftui.html)
- [Building a Multi-platform App with SwiftUI](https://heartbeat.fritz.ai/building-a-multi-platform-app-with-swiftui-5336bce94689)

### Internal

- [Re-implementation of Binding and State](https://gist.github.com/AliSoftware/ecb5dfeaa7884fc0ce96178dfdd326f8) - A concept re-implementation of the @Binding and @State property wrappers from SwiftUI
- [SwiftUI and UIKit interoperability](https://www.swiftbysundell.com/articles/swiftui-and-uikit-interoperability-part-1/)
- [Avoiding SwiftUI’s AnyView](https://www.swiftbysundell.com/articles/avoiding-anyview-in-swiftui/)

### Layout

- [How an Hstack Lays out Its Children](https://www.objc.io/blog/2020/11/09/hstacks-child-ordering/)
- [SwiftUI Layout System](https://kean.blog/post/swiftui-layout-system)
- [Flexible layouts in SwiftUI](https://fivestars.blog/swiftui/flexible-swiftui.html)
- [Sharing layout information in SwiftUI](https://fivestars.blog/swiftui/swiftui-share-layout-information.html)

### Life cycle

- [The Ultimate Guide to the SwiftUI 2 Application Life Cycle](https://peterfriese.dev/ultimate-guide-to-swiftui2-application-lifecycle/)
- [SwiftUI View Lifecycle](https://www.vadimbulavin.com/swiftui-view-lifecycle/) - Explore the three phases of the SwiftUI view lifecycle.

### Others

- [id Identifying SwiftUI Views](https://swiftui-lab.com/swiftui-id/)
- [View Communication Patterns in SwiftUI](https://www.vadimbulavin.com/passing-data-between-swiftui-views/)
- [Localization with SwiftUI, how to preview your localized content](https://benoitpasquier.com/localization-swiftui-how-top-preview-localized-content/)
- [Avoiding massive SwiftUI views](https://www.swiftbysundell.com/articles/avoiding-massive-swiftui-views/)
- [Asynchronous Image Loading from URL in SwiftUI](https://www.vadimbulavin.com/asynchronous-swiftui-image-loading-from-url-with-combine-and-swift/)
- [SwiftUI tips and tricks](https://www.hackingwithswift.com/quick-start/swiftui/swiftui-tips-and-tricks)
- [An alternative to SwiftUI's stacks + Spacer combo](https://fivestars.blog/swiftui/stack-spacer-alternatives.html)
- [SwiftUI Sound Effects: AVAudioEngine Patterns for Button Taps](https://blipblip.click/swiftui-sound-effects)

### macOS

- [SwiftUI for Mac ](https://troz.net/post/2019/swiftui-for-mac-1/) - Try out a Mac app and see what happened.
- [SwiftUI for Mac on Big Sur](https://troz.net/post/2020/swiftui_mac_big_sur/)
- [AppKit is done](https://kean.blog/post/appkit-is-done) 

## Libraries

### Extensions

- [SwiftUIX](https://github.com/SwiftUIX/SwiftUIX) - An extension to the standard SwiftUI library.
- [EasySwiftUI](https://github.com/onmyway133/easyswiftui) - Extra sugar for SwiftUI
- [SwiftUIKitView](https://github.com/AvdLee/SwiftUIKitView) - Easily use UIKit views in your SwiftUI applications. Create Xcode Previews for UIView elements
- [PureSwiftUI](https://github.com/CodeSlicing/pure-swift-ui) - Bringing Views into Focus 

### Image

- [SDWebImageSwiftUI](https://github.com/SDWebImage/SDWebImageSwiftUI) - About
SwiftUI Image loading and Animation framework powered by SDWebImage
- [FetchImage](https://github.com/kean/FetchImage) - Makes it easy to download images using Nuke and display them in SwiftUI apps
- [Kingfisher](https://github.com/onevcat/Kingfisher) - A lightweight, pure-Swift library for downloading and caching images from the web.
- [CachedAsyncImage](https://github.com/lorenzofiamingo/SwiftUI-CachedAsyncImage) - The simplest way to add cache to your AsyncImage.


### Tools

- [SVG-to-SwiftUI](https://github.com/quassummanus/SVG-to-SwiftUI) - Tool to convert SVG to SwiftUI's Shape structure
- [IconVectors](https://iconvectors.io/help/developer-features.html#developer-code-targets) - Desktop SVG icon editor that generates SwiftUI Shape/Path drawing code; commercial software with a 30-day trial
- [whatishipped](https://github.com/selan-ai/whatishipped) - A Claude Code skill that recreates a mobile app's UI as it ships: every screen, state, component and journey of an iOS or Android app, drawn from its code and checked against the app's own screenshots.

### Inspection

- [ViewInspector](https://github.com/nalexn/ViewInspector) - Runtime inspection and unit testing of SwiftUI views
- [SwiftUI-Introspect](https://github.com/siteline/SwiftUI-Introspect) - About
Introspect underlying UIKit components from SwiftUI
- [Dynamic](https://github.com/mhdhejazi/Dynamic) - Call hidden/private API in style! The Swift way.

### Property wrappers

- [Burritos](https://github.com/guillermomuntaner/Burritos) - A collection of Swift Property Wrappers

## UI

### Animation

- [swiftui-animation-library](https://github.com/amosgyamfi/swiftui-animation-library) - Useful SwiftUI animations including Loading/progress, Looping, On-off, Enter, Exit, Fade, Spin and Background animations
- [SwiftUI-Animations](https://github.com/Shubham0812/SwiftUI-Animations) - Various types of Animations created in SwiftUI and can be used anywhere you want
- [SwiftUI-Animation](https://github.com/Arvindcs/SwiftUI-Animation) - Swiftui Animation
- [SwiftUI-Animations](https://github.com/Inncoder/SwiftUI-Animations) - Code from instagram posts
- [swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries) - Swift UI libraries, iOS components and animations

### Button

- [FloatingButton](https://github.com/exyte/FloatingButton) - Easily customizable floating button menu created with SwiftUI
- [FloatingMenuButton](https://github.com/andr3a88/FloatingMenuButton) - A SwiftUI Floating Action Button that expands into a menu with multiple items when tapped.

### Calendar

- [RKCalendar](https://github.com/RaffiKian/RKCalendar) - SwiftUI Simple Calendar / Date Picker for iOS
- [SwiftUICalendar](https://github.com/GGJJack/SwiftUICalendar) - SwiftUI base simple Calendar

### Chart

- [ChartView](https://github.com/AppPear/ChartView) - ChartView made in SwiftUI
- [SwiftUICharts](https://github.com/mecid/SwiftUICharts) - A simple line and bar charting library that supports accessibility written using SwiftUI.
- [SwiftSunburstDiagram](https://github.com/lludo/SwiftSunburstDiagram) - SwiftUI library to easily render diagrams given a tree of objects. Similar to ring chart, sunburst chart, multilevel pie chart.
- [swiftui-charts](https://github.com/spacenation/swiftui-charts) - SwiftUI Charts with custom styles
- [BarChart](https://github.com/dawigr/BarChart) - SwiftUI Bar Chart
- [GraphKit](https://github.com/Chronaemia/GraphKit) - Graphing library for SwiftUI 
- [LightChart](https://github.com/pichukov/LightChart) SwiftUI charts

### Chat

- [swift-chat](https://github.com/unionst/swift-chat) - iMessage-faithful chat UI for SwiftUI: bubble tails, typing indicators, read receipts, attachments and keyboard handling in one `Chat` view, plus an assistant style for AI chat apps that streams Markdown replies under the question
- [SwiftyChat](https://github.com/EnesKaraosman/SwiftyChat) - Lightweight chat UI with 11 built-in message types, 8 themes, and iOS/macOS support

### Color

- [DynamicColor](https://github.com/yannickl/DynamicColor) - Yet another extension to manipulate colors easily in Swift and SwiftUI

### Clock

- [ClockPicker](https://github.com/workingDog/ClockPicker) - SwiftUI Clock Time Picker
- [SwiftClockUI](https://github.com/renaudjenny/SwiftClockUI) - SwiftUI library to display a clock

### Countdown

- [CountdownFilmClutter-SwiftUI](https://github.com/elpassion/CountdownFilmClutter-SwiftUI) - Countdown film clutter in SwiftUI
- [FlipClock-SwiftUI](https://github.com/elpassion/FlipClock-SwiftUI) - Flip clock in SwiftUI

### Confetti

- [ConfettiView](https://github.com/ziligy/ConfettiView) - A Confetti View for SwiftUI

### Drawer

- [Snap](https://github.com/nerdsupremacist/Snap) - A customizable Snapping Drawer à la Apple Maps
- [swiftui-drawer](https://github.com/maustinstar/swiftui-drawer) - A SwiftUI bottom-up controller, like in the Maps app. Drag to expand or minimize.

### Form

- [TypeYouCard](https://github.com/alexejn/TypeYouCard) - SwiftUI Paycard form

### Gesture
- [SwiftUI-DetectGestureUtil](https://github.com/Saw-000/SwiftUI-DetectGestureUtil) - This allows you to detect only one of multiple custom gestures on a single SwiftUI View.

### Grid

- [Grid](https://github.com/exyte/Grid) - The most powerful Grid container missed in SwiftUI
- [QGrid](https://github.com/Q-Mobile/QGrid) - QGrid: The missing SwiftUI collection view
- [WaterfallGrid](https://github.com/paololeonardi/WaterfallGrid) - A waterfall grid layout view for SwiftUI
- [swiftui-grid](https://github.com/spacenation/swiftui-grid) - SwiftUI Grid layout with custom style
- [ASCollectionView](https://github.com/apptekstudios/ASCollectionView) - A SwiftUI collection view with support for custom layouts, preloading, and more
- [MosaicGrid](https://github.com/hainayanda/MosaicGrid) - Easy to use fully customizable Mosaic grid layout for SwiftUI

### Icon

- [FontAwesomeSwiftUI](https://github.com/onmyway133/FontAwesomeSwiftUI) - Easy to use FontAwesome 5 in SwiftUI
- [SwiftUIFontIcon](https://github.com/huybuidac/SwiftUIFontIcon) - The easiest way to implement font icons in your SwiftUI project.
- [SFSafeSymbols](https://github.com/piknotech/SFSafeSymbols) - Safely access Apple's SF Symbols using static typing
- [SFSymbolsKit](https://github.com/WikipediaBrown/SFSymbolsKit) - Typed String, UIImage, and NSImage APIs for every SF Symbol, generated from Apple's catalog

### Guide

- [StepperView](https://github.com/badrinathvm/StepperView) - SwiftUI iOS component for Step Indications.

### Keyboard

- [KeyboardShortcuts](https://github.com/sindresorhus/KeyboardShortcuts) - Add user-customizable global keyboard shortcuts to your macOS app in minutes

### Loading

- [ActivityIndicatorView](https://github.com/exyte/ActivityIndicatorView) - A number of preset loading indicators created with SwiftUI
- [ActivityIndicators](https://github.com/sketch204/ActivityIndicators) - Simple activity indicators for your SwiftUI projects
- [SkeletonUI](https://github.com/CSolanaM/SkeletonUI) - Elegant skeleton loading animation in SwiftUI and Combine
- [Laden](https://github.com/vinhnx/Laden) - SwiftUI loading indicator view

### Map

- [ImmersiveMap](https://github.com/artembobkin/ImmersiveMap) - A Metal-rendered vector-tile map engine for SwiftUI with a 3D globe, flat map and live avatar markers (iOS & macOS).

### Onboarding

- [ConcentricOnboarding](https://github.com/exyte/ConcentricOnboarding) - SwiftUI library for a walkthrough or onboarding flow with tap actions
- [PermissionPilot](https://github.com/arpitagarwal1301/PermissionPilot) - Drop-in SwiftUI onboarding wizard and macOS permissions flow (detect, prompt, deep-link)

### Page

- [Pages](https://github.com/nachonavarro/Pages) - A lightweight, paging view solution for SwiftUI
- [LiquidSwipe](https://github.com/exyte/LiquidSwipe) - Example of using SwiftUI to create a beautiful Liquid Swipe control
- [PageView](https://github.com/fredyshox/PageView) - SwiftUI view enabling navigation between pages of content

### Picker

- [SwiftUIWheelPicker](https://github.com/GGJJack/SwiftUIWheelPicker) - Custom horizontal wheel picker for SwiftUI

### Pull to refresh

- [SwiftUI-PullToRefresh](https://github.com/AppPear/SwiftUI-PullToRefresh) - Pull to refresh in SwiftUI for List, NavigationView


### Slider

- [swiftui-sliders](https://github.com/spacenation/swiftui-sliders) - SwiftUI Sliders with custom styles
- [Sliders-SwiftUI](https://github.com/kieranb662/Sliders-SwiftUI) - Collection of unique fully customizable SwiftUI sliders, joysticks, trackpads and more!

### TabBar

- [bottombar-swiftui](https://github.com/smartvipere75/bottombar-swiftui) - BottomBar component for SwiftUI

### Toast

- [SSToastMessage](https://github.com/SimformSolutionsPvtLtd/SSToastMessage) - It will add toast, alert, and floating message view over the top of any view.
- [ToastUI](https://github.com/quanshousio/ToastUI) - A simple way to show toast in SwiftUI.
- [AlertToast](https://github.com/elai950/AlertToast) - Present Apple-like alert & toast in SwiftUI

### View

- [liquid](https://github.com/maustinstar/liquid) Create a playful backsplash in SwiftUI.

### Window

- [SwiftUIWindowStyles](https://github.com/martinlexow/SwiftUIWindowStyles) - Showcase of window and toolbar style combinations possible with SwiftUI on macOS.

### Others

- [MGFlipView](https://github.com/Zaprogramiacz/MGFlipView) - MGFlipView allows to create flipping view in easy way without worrying about flipping animation and flipping logic.
- [LiquidSwipe](https://github.com/exyte/LiquidSwipe) - Example of using SwiftUI to create a beautiful Liquid Swipe control
- [neumorphic](https://github.com/costachung/neumorphic) - Neumorphic is a SwiftUI utility to build Neumorphism Soft UI 
- [SwiftUI-Shapes](https://github.com/kieranb662/SwiftUI-Shapes) - Commonly Used Shapes and Utilities In SwiftUI
- [SwiftUI-Hook](https://github.com/ra1028/SwiftUI-Hooks) - A SwiftUI implementation of React Hooks. Enhances reusability of stateful logic and gives state and lifecycle to function view.
- [ParticleDrivers](https://github.com/devwaseem/ParticleDrivers) - ParticleDrivers is a SwiftUI project that simulates particles forming structures on command
- [liquid](https://github.com/maustinstar/liquid) - Create a playful backsplash in SwiftUI
- [shiny](https://github.com/maustinstar/shiny) - Shiny uses your gyroscope to simulate lighting and motion effects on colors. Works on almost every SwiftUI View.
- [ComponentsKit](https://github.com/componentskit/ComponentsKit) - A collection of reusable and fully customizable UI components.
- [MuscleMap](https://github.com/melihcolpan/MuscleMap) - Interactive human body muscle maps with highlights, heatmaps, animations and tap gestures, plus a UIKit wrapper.
- [Swift95](https://github.com/DimaMishchenko/swift95) - A Windows 95-inspired SwiftUI component library for building nostalgic apps.
- [WishKit](https://github.com/wishkit/wishkit-ios) - In-app feature request board where users submit and vote on features.
- [DESIGN:OS Apple](https://github.com/jangtrinh/design-os-apple) - A free SwiftUI design-system library for iOS, iPadOS and macOS with semantic color tokens, Dynamic Type-safe components and a Gallery app (source-available).

## Open source apps

### iOS

- [BeAware Deaf Assistant](https://github.com/BeAware-DeafAssistant/mobile) - SwiftUI app containing customizable noise alerts, speech-to-text and a supercharged notepad.
- [DesignCode-SwiftUI](https://github.com/mythxn/DesignCode-SwiftUI) - An app fully written in SwiftUI showcasing beautiful design and animations.
- [MovieSwiftUI](https://github.com/Dimillian/MovieSwiftUI) - SwiftUI & Combine app using MovieDB API
- [SwiftUI-2048](https://github.com/unixzii/SwiftUI-2048) - A 2048 game writing with SwiftUI.
- [swiftui-recipes-app](https://github.com/mecid/swiftui-recipes-app) - Recipes app written in SwiftUI using Single State Container
- [SwiftUI-HackerNews](https://github.com/woxtu/SwiftUI-HackerNews) - A Hacker News reader built with SwiftUI+Combine 
- [Pomosh-iOS-watchOS](https://github.com/stevenselcuk/Pomosh-iOS-watchOS) - Pomodoro Technique assistant on iOS and WatchOS
- [swift-chat-ai-starter](https://github.com/unionst/swift-chat-ai-starter) - Chat app that streams Claude's replies as Markdown, with photo input, built on Swift Chat
- [Mamoot](https://github.com/Benetos/Mamoot) - Mastodon and Twitter client for iOS, iPadOS & macOS
- [Lexa](https://github.com/peterzhang0216/lexa) - Offline English vocabulary trainer with spaced repetition and open word lists (VOA, AWL, ECDICT); no account, no tracking.
- [sfsymbols](https://github.com/atrinh0/sfsymbols) - SwiftUI app to search and showcase SF Symbols
- [buttoncraft](https://github.com/atrinh0/buttoncraft) - Craft that perfect SwiftUI button effect 
- [SwiftUIMindBlowing](https://github.com/antranapp/SwiftUIMindBlowing) - Learning SwiftUI by examples.
- [Clendar - minimal calendar](https://github.com/vinhnx/clendar) - Clendar - minimal calendar. Written in SwiftUI
- [Expenso-iOS](https://github.com/sameersyd/Expenso-iOS) - A Simple Expense Tracker App built to demonstrate the use of SwiftUI, CoreData and MVVM Architecture.
- [swiftui.builds](https://github.com/FranckNdame/swiftui.builds) - building cool stuff with swiftui
- [AR MultiPendulum](https://github.com/philipturner/ar-multipendulum) - AR app using SwiftUI for touchscreen interface
- [OakOTP](https://github.com/AlexCatch/Oak) - SwiftUI app for generating OTP codes utilising MVVM, Dependency Injection, Core Data & Cloud Kit
- [DailyVox](https://github.com/intrepidkarthi/dailyvox) - AI voice diary using SwiftUI with NaturalLanguage, Speech, Core Data, CloudKit. On-device transcription, mood tracking, Digital Twin.
- [HealthSync](https://github.com/megabyte0x/healthykit) - SwiftUI app that syncs selected Apple Health data from HealthKit to a private backend API.
- [Pilgrim](https://github.com/walktalkmeditate/pilgrim-ios) - Mindful walking companion with on-device voice transcription, meditation mode, and digital goshuin seals. Full SwiftUI with Combine, CoreStore, WhisperKit, and Live Activities.
- [FileManager](https://github.com/xsxs18-dev/FileManager) - A local, sideloaded file manager for iOS with Face ID-locked folders, a hidden vault, AES-256 encrypted zips, and real PDF passwords. No account, no backend, no analytics.
- [HTMLViewer](https://github.com/xsxs18-dev/HTMLViewer) - A local HTML viewer and editor for iOS with a live WebView preview. No account, no backend, no analytics.
- [Verceltics](https://github.com/apoorvdarshan/verceltics) - Native SwiftUI iPhone and iPad workspace for 27 hosting, registrar, analytics and uptime services (Vercel, Cloudflare, Netlify, Search Console, Plausible, UptimeRobot and more), with credentials kept in the Keychain.
- [Lyricar](https://github.com/noluyorAbi/lyricar) - Synced Spotify lyrics on the Lock Screen, Dynamic Island, widgets and CarPlay, built with Live Activities, WidgetKit, App Intents and CarPlay templates.
- [Open Habit](https://github.com/zamai/open-habit) - Habit tracker with interactive widgets, App Intents for Shortcuts, a watchOS companion and CloudKit sync
- [Fud AI](https://github.com/apoorvdarshan/fud-ai) - Calorie and workout tracker for iPhone, iPad and Apple Watch: multi-photo AI food analysis with your own provider key, realtime voice logging, HealthKit, WidgetKit, App Intents for Siri and an on-device Apple Intelligence fallback
- [Tuber](https://github.com/achubnet/Tuber) - Calm player for the YouTube channels you follow that skips in-video sponsor reads via SponsorBlock. SwiftUI with Liquid Glass, SwiftData + CloudKit, AVKit, App Intents.
- [Oath Wallet](https://github.com/devdasx/oath-wallet) - SwiftUI wallet for iPhone and iPad with multi-network asset views and transfer review screens.

- [Wudland](https://github.com/joexk1/wudland) - SwiftUI iPhone pixel village for calendar events, reminders, weather and encrypted coding-agent status. GPLv3; App Store review pending.

### tvOS

- [RAYN Weather](https://github.com/qh-work/RAYN) - Native weather studio for Apple TV with live forecasts, radar, air quality, astronomy, marine conditions, and remote-first large-screen layouts.

### macOS

- [RedditOS](https://github.com/Dimillian/RedditOS) - SwiftUI Reddit client for macOS Big Sur
- [ControlRoom](https://github.com/twostraws/ControlRoom) - A macOS app to control the Xcode Simulator
- [AppShot](https://github.com/L1cardo/AppShot) - App Store screen shot generator
- [5 GUIs](https://github.com/ZeeZide/5GUIs) - Detect the GUI technology used in an app
- [Pasteboard Viewer](https://github.com/sindresorhus/Pasteboard-Viewer) - View what's on the pasteboard
- [pika](https://github.com/superhighfives/pika) - An open-source colour picker app for macOS
- [nuage](https://github.com/lbrndnr/nuage-macos) - A native SoundCloud app for macOS, written in SwiftUI
- [writefreely](https://github.com/writeas/writefreely-swiftui-multiplatform) - Source code for the WriteFreely SwiftUI app for iOS, iPadOS, and macOS
- [Privacy Redirect for Safari](https://github.com/smmr-software/privacy-redirect-safari) - Redirect Twitter, YouTube, Reddit, Google Maps, Google Search, and Google Translate to privacy friendly alternatives.
- [Poirot](https://github.com/LeonardoCardoso/Poirot) - A macOS companion for browsing Claude Code sessions, exploring diffs, and re-running commands. Built with Swift 6, SwiftUI, and the Observation framework.
- [ClearDisk](https://github.com/bysiber/cleardisk) - Menu bar app to visualize and clean developer caches (Xcode, node_modules, CocoaPods, Docker, pip, Cargo) and reclaim disk space.
- [Dusty](https://github.com/yagcioglutoprak/dusty) - SwiftUI menu bar cleaner for reclaiming disk space from safe macOS caches, logs, Xcode data, and developer artifacts.
- [Lockpaw](https://github.com/sorkila/lockpaw) - macOS menu bar screen guard. Lock/unlock your screen with a hotkey while background tasks keep running.
- [Rime](https://github.com/Yvsleyen00941/Rime) - Minimalist macOS PDF reader where everything outside the page freezes into frosted ice for distraction-free focus.
- [Revu](https://github.com/JuliusBrussee/revu-swift) - Local-first spaced repetition app for macOS with FSRS scheduling, Notion-inspired UI, Anki import, and study forecasting.
- [ItsPaint](https://github.com/joshlin2201/itspaint) - MS Paint for the Mac. A SwiftUI interface over an AppKit document and canvas, with screenshot markup, step badges, pixelate, and background removal that uses no model.
- [Lyrimuse](https://github.com/Yudaotor/lyrimuse) - Word-synced desktop lyrics for Apple Music, Spotify and browser web players. SwiftUI overlay, Dynamic Island capsule, lyrics window and menu bar text, with candidates from nine lyric sources scored on one scale to match the right version.
- [Tintpad](https://github.com/sorkila/tintpad) - Menu bar launcher for coding agents. A hotkey opens a palette, pick a repo, and your terminal opens there with Claude Code, Codex or any agent running. Built with Swift 6 and SwiftUI.
- [Whisk](https://github.com/nathan-poncet/whisk) - Clipboard manager for macOS with a Paste-style Liquid Glass panel, pins, search operators, paste stack and rich previews. SwiftUI over a Clean Architecture kernel, SQLite storage.
- [ApolloShell](https://github.com/Silvertree2010/ApolloShell) - Desktop shell for macOS 26 Tahoe: a sidebar with its own dock, a launcher, a dashboard and a control centre. SwiftUI views in AppKit panels with Liquid Glass, themed with one CSS file.
- [ILoveNotch](https://github.com/niyamvora/ILoveNotch) - MacBook notch app for media, a file shelf, calendar, reminders, notes and timers. SwiftUI views in AppKit panels, event-driven with near-zero idle CPU.
- [Lunavect](https://github.com/lovach/Lunavect) - Menu bar app for Claude Code and Codex that shows which session is working, waiting for you, or done, plus weekly and five-hour usage limits with reset times. Built with SwiftUI, with WidgetKit desktop widgets.
- [Shotnix](https://github.com/OMARVII/Shotnix) - Screenshots, screen recordings and a video editor for macOS: scrolling capture, annotation and text recognition, and recordings that open with zooms on clicks and on-device captions. SwiftUI views in AppKit windows, with one Core Image renderer for the preview and the export.
- [Meraline](https://github.com/Meldiron/meraline) - Menu bar app for quick AI questions on ⌥ Space: a Liquid Glass panel that doesn't take focus, answering with Apple Intelligence, API models, Ollama, or Claude Code and Codex. SwiftUI in a non-activating AppKit panel, Swift 6 with strict concurrency.
- [Pinto Notes](https://github.com/pinto-notes/pinto-notes) - Apple Notes-style notes app in SwiftUI that ChatGPT, Claude and Codex can search and edit over MCP, with each AI edit highlighted and undoable.
- [KyttoMCP](https://github.com/heyitsjakub/KyttoMCP) - Native SwiftUI app that shows every MCP server across Claude Desktop, Claude Code, Cursor, VS Code and Codex in one matrix, with health checks, a tool-description safety scan and config backups.
- [Lemma](https://github.com/fus3r/lemma) - PDF reader for mathematics textbooks and papers, built with SwiftUI, AppKit and PDFKit, that turns theorem and equation references into links, folds proofs and checks the derivations you write.
- [Device Hub Pro](https://github.com/gitemre/device-hub-pro) - Manage and mirror Android emulators, phones and iOS simulators side by side, with a Controls panel, logs, screenshots, recordings and the iPhone Duo foldable simulator in 3D. Built with SwiftUI, Swift 6.
- [Brow](https://github.com/efim0v/brow) - MacBook notch app with the 5-hour, weekly and model-specific Claude Code usage limits of every account, reset times and a reset calendar. SwiftUI views in an AppKit panel around the notch.
- [Swivel](https://github.com/jonathanlotan/Swivel) - Menu bar file converter: tap a key mid-drag and drop files on a wheel to convert, crop, compress or share them, with no network code. SwiftUI wheel in a non-activating AppKit panel at the pointer.
- [Boost](https://github.com/Kernel-Hunter/boost) - Menu bar app for memory and disk space: a week of memory history, pausing background apps instead of quitting them, cleanup of caches that rebuild themselves, and an uninstaller. Built with SwiftUI and AppKit, builds with Command Line Tools only.
- [Cleaner](https://github.com/ciro-maciel/cleaner) - Mac cleaner whose rules live in one public JSON file, with an uninstaller, a disk map, startup items and a 7-day quarantine that restores removed items with one click. SwiftUI and AppKit, no network code.
- [Screenshots](https://github.com/ciro-maciel/screenshots) - Menu bar screenshot and screen recording app with scrolling capture, on-device text recognition, MP4 and GIF recording, annotation and pin-to-screen. SwiftUI and AppKit over ScreenCaptureKit, no dependencies.
- [Windows](https://github.com/ciro-maciel/windows) - Menu bar window manager that snaps windows to halves, full screen, center or custom sizes by shortcut or by dragging them to a screen edge. AppKit menu with SwiftUI settings, no dependencies.
- [Plainsay](https://github.com/conrader/plainsay) - Native Mac menu-bar dictation built with SwiftUI and AppKit. Local mode runs Whisper or Parakeet, free with no account; optional paid Cloud transcription is available. MIT-licensed client, macOS 14+ and Apple silicon.
- [SpaceMap](https://github.com/renkagod/spacemap) - Disk usage analyzer that draws your disk as a nested treemap you can zoom into, filling in live while the scan runs.
- [AppDuo](https://github.com/tamia6/AppDuo) - Native macOS app cloner with separate data directories and custom names and icons.
- [LayoutKeeper](https://github.com/tumingke0/LayoutKeeper) - Menu bar app that saves window layouts per external monitor and restores window positions, sizes and Mission Control Spaces on reconnect, with hardware DDC brightness keys on Apple Silicon. Built with Swift 6, SwiftUI and AppKit.
- [UMST](https://github.com/nicoleyangcoding/UMST-UltimateMacSchedulingTool) - Desktop calendar widget and menu bar quick add that combine Google, iCloud, Outlook, Apple Reminders, Canvas, Todoist, Asana and Trello in one list.
- [Louppe](https://github.com/murlexander/louppe-media-culler) - Photo viewer and sorter for JPEG and RAW folders: choose keepers with the keyboard and copy them without a library import. SwiftUI over AppKit for zoom and video, with XMP sidecar export.

### MultiPlatform Applications

- [DEV](https://github.com/hadiidbouk/DEV) - SwiftUI + Composable Architecture multiplatform app for dev.to website.
- [StackOv](https://github.com/surfstudio/StackOv) - An open-source SwiftUI Stack Overflow client

- [Prism](https://github.com/soma-intelligence/prism) - Health app for iPhone, iPad, Mac and Vision Pro that reads Apple Health and computes daily sleep, recovery, strain, stress and energy scores on device. One SwiftUI target, Swift 6, AGPL-3.0.
