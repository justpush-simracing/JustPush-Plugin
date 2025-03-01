![Logo](docs/justpush_logo.jpg)

[![Marketplace](docs/marketplace-light.png)](https://marketplace.elgato.com/product/justpush-a5096b0b-4d56-40bf-acbc-8cd4c33c545a) &emsp; [![Discord](docs/Discord-25.png)](https://discord.gg/tew2neKXNw) &emsp; [![Youtube](docs/Youtube-25.png)](https://www.youtube.com/@justpushsimracing) &emsp; [![Tiktok](docs/Tiktok-25.png)](https://www.tiktok.com/@justpushsimracing) &emsp; [![Patreon](docs/Patreon-25.png)](https://www.patreon.com/justpushsimracing) 
# JustPush! Plugin for Stream Deck
_Currently supported title: ACC | Planned supported titles: AC, AC Evo, LMU, iRacing_

**A revolutionary new plugin that will forever change the way you use your Stream Deck as a sim racing button box!** 

[![Marketplace download badge](https://img.shields.io/badge/dynamic/json?logo=data:image/svg%2bxml;base64,PHN2ZyB3aWR0aD0iMjMwIiBoZWlnaHQ9IjIzMCIgdmlld0JveD0iMCAwIDIzMCAyMzAiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxwYXRoIGQ9Ik02My45NzEgMzguNDgzTDY0LjA5MSAzOC41NzNMMTA5LjY5MiA2NC43NzdDMTA3LjQ1MyA3Ny4yODUgMTAwLjg5NCA4OC43MTIgOTEuMTgzIDk2Ljk3NkM4MS4zMTYgMTA1LjM3MyA2OC43NDkgMTEwIDU1Ljc5MSAxMTBDNDEuMTU5IDExMCAyNy40MDMgMTA0LjI4IDE3LjA1IDkzLjg5MUM2LjcwMiA4My41MDIgMSA2OS42ODYgMSA1NUMxIDQwLjMxNCA2LjcwMiAyNi40OTggMTcuMDQ5IDE2LjEwOUMyNy4zOTYgNS43MiA0MS4xNTIgMCA1NS43OSAwQzY2Ljk3MSAwIDc3LjcyIDMuMzYxIDg2Ljg3OSA5LjcxMUM5NS44MjggMTUuOTE3IDEwMi42NzYgMjQuNTQxIDEwNi42OTEgMzQuNjU0QzEwNy4yMDEgMzUuOTUgMTA3LjY3NSAzNy4yODMgMTA4LjA4OSAzOC42MjFMOTguMzQ4IDQ0LjI4N0M5OC4wMTIgNDIuOTQzIDk3LjYxIDQxLjYwNCA5Ny4xNDggNDAuMzAyQzkwLjk0MiAyMi43NDcgNzQuMzE3IDEwLjk0NyA1NS43OSAxMC45NDdDMzEuNTkxIDEwLjk0NyAxMS45MDUgMzAuNzExIDExLjkwNSA1NUMxMS45MDUgNzkuMjg5IDMxLjU5MSA5OS4wNTMgNTUuNzkgOTkuMDUzQzY1LjE5NCA5OS4wNTMgNzQuMTYyIDk2LjEgODEuNzMgOTAuNTA3Qzg5LjE0MiA4NS4wMjcgOTQuNTc5IDc3LjUxOSA5Ny40NTQgNjguNzk5TDk3LjQ4NCA2OC42MDdMNDQuMzAyIDM4LjA2NFY3MS4xODJMNjIuNjM3IDYwLjU3N0w3Mi4wNzggNjUuOTkxTDQ0LjU5NiA4MS44ODlMMzQuODc5IDc2LjMzMVYzMi45NzRMNDQuNTg0IDI3LjM2Mkw2My45NzYgMzguNDg5TDYzLjk3IDM4LjQ4M0g2My45NzFaIiBmaWxsPSJ3aGl0ZSIvPgo8ZyBjbGlwLXBhdGg9InVybCgjY2xpcDBfMTFfNDU2KSI+CjxwYXRoIGQ9Ik0yMzAgOTBDMjMwIDEwMS4wNDYgMjIxLjA0NiAxMTAgMjEwIDExMEMyMDUuOTQyIDExMCAyMDIuMTY2IDEwOC43OTIgMTk5LjAxMyAxMDYuNzE1QzE5NS44NiAxMDQuNjM4IDE5My4zMjkgMTAxLjY5MiAxOTEuNzYyIDk4LjIxOUwxNzcuMjggNjYuMTMxQzE3Ni44ODggNjUuMjYzIDE3Ni4wMTYgNjQuNjU4IDE3NS4wMDEgNjQuNjU4QzE3My45ODYgNjQuNjU4IDE3My4xMTMgNjUuMjY0IDE3Mi43MjIgNjYuMTMzTDE1OC4yNCA5OC4yMTlDMTU1LjEwNSAxMDUuMTY2IDE0OC4xMTggMTEwIDE0MC4wMDEgMTEwQzEyOC45NTYgMTEwIDEyMC4wMDEgMTAxLjA0NiAxMjAuMDAxIDkwQzEyMC4wMDEgODUuOTQyIDEyMS4yMSA4Mi4xNjYgMTIzLjI4NyA3OS4wMTNDMTI1LjM2NCA3NS44NiAxMjguMzEgNzMuMzMgMTMxLjc4MyA3MS43NjJMMTYzLjg3MSA1Ny4yOEMxNjQuNzM5IDU2Ljg4OCAxNjUuMzQzIDU2LjAxNSAxNjUuMzQzIDU1QzE2NS4zNDMgNTMuOTg1IDE2NC43MzggNTMuMTEyIDE2My44NjkgNTIuNzIxTDEzMS43ODIgMzguMjM5QzEyNC44MzUgMzUuMTA0IDEyMCAyOC4xMTcgMTIwIDIwQzEyMCA4Ljk1NSAxMjguOTU1IDAgMTQwIDBDMTQ0LjA1OSAwIDE0Ny44MzUgMS4yMDkgMTUwLjk4OCAzLjI4NkMxNTQuMTQxIDUuMzYzIDE1Ni42NzEgOC4zMDggMTU4LjIzOSAxMS43ODJMMTcyLjcyMSA0My44N0MxNzMuMTEzIDQ0LjczOCAxNzMuOTg2IDQ1LjM0MiAxNzUgNDUuMzQyQzE3Ni4wMTQgNDUuMzQyIDE3Ni44ODkgNDQuNzM3IDE3Ny4yOCA0My44NjhMMTkxLjc2MiAxMS43ODJDMTk0Ljg5NyA0LjgzNSAyMDEuODg0IDAgMjEwIDBDMjIxLjA0NiAwIDIzMCA4Ljk1NSAyMzAgMjBDMjMwIDI0LjA1OCAyMjguNzkxIDI3LjgzNCAyMjYuNzE0IDMwLjk4OEMyMjQuNjM3IDM0LjE0MSAyMjEuNjkyIDM2LjY3MiAyMTguMjE5IDM4LjIzOUwxODYuMTMzIDUyLjcyMUMxODUuMjY0IDUzLjExMiAxODQuNjU4IDUzLjk4NSAxODQuNjU4IDU1QzE4NC42NTggNTYuMTQgMTg1LjM4NiA1Ni45NDMgMTg2LjEzMSA1Ny4yOEwyMTguMjE5IDcxLjc2MkMyMjUuMTY1IDc0Ljg5NyAyMzAgODEuODg0IDIzMCA5MFoiIGZpbGw9IiM0RERBNzkiLz4KPC9nPgo8cGF0aCBkPSJNMTIuNTAxIDEyNUM1LjU5NyAxMjUgMC4wMDEgMTMwLjU5NiAwLjAwMSAxMzcuNUMwLjAwMSAxNDQuNDA0IDUuNTk3IDE1MCAxMi41MDEgMTUwSDc1LjQyMkw5LjA5NCAxOTMuMjMzQzMuNjE5IDE5Ni44MDIgMCAyMDIuOTc4IDAgMjEwQzAgMjIxLjA0NiA4Ljk1NCAyMzAgMjAgMjMwQzI3LjAyMiAyMzAgMzMuMTk4IDIyNi4zOCAzNi43NjYgMjIwLjkwNkw4MC4wMDEgMTU0LjU3OVYyMTcuNUM4MC4wMDEgMjI0LjQwNCA4NS41OTcgMjMwIDkyLjUwMSAyMzBDOTkuNDA1IDIzMCAxMDUuMDAxIDIyNC40MDQgMTA1LjAwMSAyMTcuNVYxMjVIMTIuNTAxWiIgZmlsbD0iI0VBM0I5QyIvPgo8cGF0aCBkPSJNMTc3LjUgMTIwQzE0OC41MDUgMTIwIDEyNSAxNDMuNTA1IDEyNSAxNzIuNVYyMjVIMTc3LjVDMjA2LjQ5NSAyMjUgMjMwIDIwMS40OTUgMjMwIDE3Mi41QzIzMCAxNDMuNTA1IDIwNi40OTUgMTIwIDE3Ny41IDEyMFoiIGZpbGw9IiNGNEI2MzUiLz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMTFfNDU2Ij4KPHJlY3Qgd2lkdGg9IjExMCIgaGVpZ2h0PSIxMTAiIGZpbGw9IndoaXRlIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjApIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&query=download_count&suffix=%20Downloads&label=Marketplace&labelColor=151515&color=204cfe&url=https://mp-gateway.elgato.com/organizations/280fccf5-da89-4156-9a59-727c531a1f84/products/a5096b0b-4d56-40bf-acbc-8cd4c33c545a "Marketplace download badge")](https://marketplace.elgato.com/product/justpush-a5096b0b-4d56-40bf-acbc-8cd4c33c545a)

### Plugin Highlights ([full features here](#features))
- Active **Auto Fuel** and **Auto Pressure** buttons for effortless, perfect pitstops/setups every time. 🤖🔧⛽
- First ever fully integrated **Flag Box**, dynamically rendering button icon backgrounds. 🏁
- Zero-config, customizable, preloaded profiles and multi-state buttons with stunning hotkey icons ⭐
- Robust, built-in macros to simplify and automate navigation of ACC UI and Pitstop MFD at lightning speeds. ⏱️
- Under constant development with community input, so you can help shape the future! 🚀

Experience the thrill of precise, effortless setups and pitstops with **Active Buttons** as your race engineer, with live tyre pressure and fuel calculators that do all the mental maths--and make the changes--for you! 

Watch the video of Active Buttons in action to win P1 in the pits! 
***Don't Panic — Just Push!***

[![JustPush! Promo](docs/promo_video.png)](https://www.youtube.com/watch?v=J7OPt_Kinq0)

But wait, there's more...a Stream Deck first! **Fully icon-integrated Flag Box!** 

All of this and more is packaged into pre-configured profiles, installed automatically with the plugin in seconds. 

**Unlock your driving potential with JustPush now!**

## Navigation
- [Introduction](#introduction)
- [How to Get It](#how-to-get-it)
- [What is the Cost?](#what-is-the-cost)
- [Installation](#installation)
- [Features](#features)
- [Support and Community](#support-and-community)
- [Roadmap](#roadmap)
- [Credits](#credits)

## Introduction
_**Transform your Stream Deck into the ultimate sim racing button box!**_

Forget fuel and pressure worries pre-race and mid-race in ACC. With Auto Fuel and Auto Pressure buttons, just turn a few laps to lock in perfect fuel and pressures for optimized setups and pitstops _within seconds_, regardless of setup type, track conditions, or driving style! 

The optimal values adapt to YOU, the driver, and the conditions you're driving in real time. Effortlessly manage fueling and pressure adjustments automatically—whether in the garage or pitstop MFD—so you can _just push_ on track! 

![auto fuel demo](docs/auto_fuel_demo.gif)
![auto pressure demo](docs/auto_pressure_demo.gif)
![auto setup demo](docs/auto_setup_demo.gif)

Forget dedicated flag buttons or flag overlays. Have all of your button icons and information available with integrated Flag Box, rendering flag colors underneath the icons, which has **never been done before** with Stream Deck button box solutions! 

Stunning start up sequences...

![Start Up](docs/startup.gif)

All race flags with no information loss...

![Race flags](docs/blue_yellow_flags.gif)

Finish ahead of the pack with JustPush! 

![Finish flags](docs/finish.gif)

## How to Get it

You have a few options depending on what suits your preferences. The recommendation to 'set it and forget it' is to download from Marketplace, and if you want the latest as soon as it drops, then download from Discord.

1. Get it directly from [**Elgato Marketplace**](https://marketplace.elgato.com/product/justpush-a5096b0b-4d56-40bf-acbc-8cd4c33c545a). Note: You must have an Elgato Marketplace account (worth it).
   - Pro: Stays updated automatically.
   - Con: Will be up to two weeks delayed from newest release.

2. Download latest stable release from GitHub [**Releases**](https://github.com/justpush-simracing/JustPush-Plugin/releases).
   - Pro: Update stable builds when you want.
   - Con: No notification of updates (must check manually); up to a week delayed from newest release. 

3. Get new releases sooner by joining the [**JustPush! SimRacing Discord**](https://discord.gg/tew2neKXNw).
   - Pro: Beta and newest stable releases are here first, with notifications.
   - Con: Manual updates required. 

## What is the cost?

It's absolutely **FREE**! We want to give back to the community that has given us so much. We support other projects we believe in, and we hope you will do the same for this project. 

If you like what we've done and want us to keep pushing, keep us caffeinated by [**subscribing to our Patreon**](https://www.patreon.com/c/justpushsimracing/membership) or [**tipping via PayPal**](https://www.paypal.com/ncp/payment/6JF235HLX394C) ☕ 

## Installation
Installing the JustPush! plugin and profiles is a breeze with Stream Deck's software.

1. Download the `com.justpush.streamDeckPlugin` plugin file; double-click it to install plugin
3. Select `Install Profiles` to install the profiles (highly recommended for first installation), otherwise select `Cancel` to only install plugin (recommended for plugin updates only)
4. Confirm hotkeys and configure buttons (see [wiki on discord](https://discord.gg/thwjVvru6y))

You're all set! Go on track and just push!  

[![JustPush! Install Guide](docs/install_guide.png)](https://www.youtube.com/watch?v=udg-N7g1KsI)

Please also watch our Install Guide video for this and more info! 
   
## Features

- Preloaded and user-configurable track and pitstop profiles, automatically installed with plugin
- Preconfigured (and user-configurable) Hotkeys for all car control electronics
  - Driver aids (ABS/BB/TC/TCC), Lights, Wipers, Ignition/Starter, Pit Limiter, etc.
- Multi-hotkey support for select controls:
  - Hazards (left+right signal), Wipers (auto-toggle rain lights)
- Flag display button (dedicated flag button--not integrated flag box) 
- Built-in macros for easily managing Pitstop MFD functions
  - User-defined fuel add/remove (incl. FULL and ZERO)
  - Select any/all tyres
  - User-defined pressure increase/decrease
  - Bodywork and Suspension repair toggles with **estimated repair times displayed**
  - Select driver, strategy
- Ignition-activated colors (i.e., turn on car to turn on buttons)
- Fully color-customizable icons (borders, activation backgrounds)
- Smart `open/close profile` buttons for effortless track and pitstop profile navigation
- **Active Buttons** for auto fuel and auto pressure, displaying and applying optimal changes both in garage and on track
   - Auto Fuel: Real-time fuel calculator and more! Use Manual mode to specify a length, or let Dynamic mode do everything for you! 
   - Auto Pressure: Real-time pressure calculator and more! Nail your pitstop and/or setup tyre pressures every single time with a single push of a button! 
- **Integrated FlagBox**, which dynamnically renders the flag colors UNDER the icons—a first for Stream Deck!

- Join the [JustPush! SimRacing Discord](https://discord.gg/tew2neKXNw) for:
  - Fast support from community/developer
  - First access to new release builds
  - Early/beta access to pre-release builds
  - Direct interface with developers to request and test new features for future releases!
 
## Support and Community

![Race Start](docs/P1.png)

Join the [**JustPush! SimRacing Discord**](https://discord.gg/tew2neKXNw) to:
- Get quick tips and support from the developer and community
- Access a growing repository of shared profiles
- Be the first to try new features and updates

Check out the [plugin wiki](https://discord.com/invite/thwjVvru6y) for every detail you could ever want, and then some! 

If you have an issue, please report it in the [issue tracker](https://github.com/justpush-simracing/JustPush-Plugin/issues) so we can learn and improve the product for you! 

## Roadmap
||Timeframe|Objective|
|----------|----------|----------|
|✅| Q1-Q3 2024 | Integrated test and development|
|✅| Q4 2024 | Closed beta test / Initial Release|
|✅| Q1 2025 | Publish on Elgato Marketplace|
|⬜| Q1 2025 | Integrate AC & AC Evo|
|⬜| Q1/2 2025 | Integrate LMU & iRacing|
|⬜| Q3 2025 | Launch JustPush! Web Dash|

## Credits
- All buttons come preloaded with exquisite icons created by, and in collaboration with, THK84.
- Massive gratitude to [@Jowy](https://github.com/jowy) for backend/framework architecture, without whom this project would never have been possible. 
- The sim racing community for inspiring two sim racers with a simple idea, blossom into something we hope benefits the community that's given so much to us.
- Our loving families for supporting our expensive hobby and entrepreneurial aspirations.
