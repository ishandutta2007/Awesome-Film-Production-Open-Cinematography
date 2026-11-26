# 🎬 Awesome Film Production & Open Cinematography

<p align="center">
  <img src="./assets/banner.svg" alt="Top Film Production &amp; Open Cinematography Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Film-Production-Open-Cinematography/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Film-Production-Open-Cinematography?style=social" alt="GitHub stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Film-Production-Open-Cinematography/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Film-Production-Open-Cinematography?style=social" alt="GitHub forks" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 📽️ Introduction & Scope

Welcome to the definitive, SEO-optimized curated matrix of **Film Production, Camera-to-Cloud (C2C) Dailies Review, VFX Pipeline Management, Color Science (ACES/OCIO), and Open Cinematography Hardware**. Whether you are an independent director, cinematographer, VFX supervisor, colorist, or post-production engineer, this guide bridges the gap between enterprise commercial SaaS platforms and cutting-edge open-source software and open cinema hardware.

Key areas covered:
* 📡 **Camera-to-Cloud (C2C) & Dailies Review**: High-speed wireless proxy streaming from camera to editorial rooms.
* 🎨 **Color Management & Color Grading**: Academy Color Encoding System (ACES), OpenColorIO (OCIO v2), OpenEXR, and DaVinci Resolve.
* 🎞️ **Non-Linear Video Editing (NLE) & Compositing**: Modern multi-track video editors, node-based compositing, and visual effects suites.
* 📋 **VFX Production Tracking & MAM**: Media asset management, shot tracking, task scheduling, and synchronized client playback.
* 🎥 **Open Cinema Cameras & Hardware**: Open-source cinema camera firmware, DIY RAW video recorders (AXIOM, CinePi), and camera hacks.

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS & Commercial Film Production Platforms](#️-saas--commercial-film-production-platforms)
- [💻 Open-Source Film Production & Cinematography Projects](#-open-source-film-production--cinematography-projects)
- [📈 Star History](#-star-history)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [🛠️ Contributing](#️-contributing)
- [📄 License & Disclaimer](#-license--disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global Film Production, Post-Production, and Media Asset Management (MAM) software market is estimated at **$14.5B–$18.0B+ in 2026**, growing at a compound annual growth rate (**CAGR**) of **11%–15%**. Key secular growth drivers include the widespread adoption of real-time Camera-to-Cloud (C2C) dailies workflows, LED wall virtual production (In-Camera VFX), and machine-learning-assisted media indexing and auto-tagging.

From a market concentration perspective:
* **Commercial Review & VFX Tracking (Concentrated / Oligopoly)**: The enterprise cloud review and VFX tracking layer demonstrates **moderate-to-high concentration** dominated by large incumbents such as **Adobe (Frame.io)**, **Autodesk (Flow Production Tracking / formerly ShotGrid)**, **Blackmagic Design**, and **Sony Ci**. These platforms leverage ecosystem stickiness and deep integration with native NLEs.
* **Underlying Media Pipelines & Codecs (Standardized Open Foundation)**: The media interchange, timeline representation, and color-science layers are heavily democratic and open-standard driven by the **Academy Software Foundation (ASWF)** (`OpenColorIO`, `OpenEXR`, `OpenTimelineIO`, `OpenRV`), **Blender**, and **FFmpeg**. This dual ecosystem enables studios and independent filmmakers to maintain pipeline independence and avoid strict vendor lock-in.

---

## ☁️ SaaS & Commercial Film Production Platforms

*Sorted descending by company scale (market valuation / annual revenue).*

| Platform | Category / Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Sony Ci Media Cloud](https://cimediacloud.com)** | Enterprise cloud workspace for camera-to-cloud dailies, review, rough cuts, and broadcast distribution. | **Part of Sony Group Corp.** (~$88B+ annual revenue; ~$110B+ market cap) | **$25 / month** for Solo tier (500 GB storage) or **$100 / month** Team (2 TB + 5 seats) | **Forever Free Personal Tier**: Includes **5 GB active cloud storage**, frame-accurate review links, and secure file transfers for 1 user. |
| **[Autodesk Flow Production Tracking](https://autodesk.com)** | Industry-standard cloud VFX shot tracking, dailies review (ShotGrid), and resource scheduling for film studios. | **Part of Autodesk Inc.** (~$6.1B+ annual revenue; ~$60B+ market cap) | **$30 / user / month** billed annually ($40/mo monthly; ~$280/yr per seat) | **30-Day Full-Access Free Trial**: Full access to VFX shot management, review playlists, and REST API (plus free educational licenses for students). |
| **[Frame.io (Adobe)](https://frame.io)** | Cloud-native video review, Camera-to-Cloud (C2C) dailies ingestion, and frame-accurate annotation suite. | **Part of Adobe Inc.** (Acquired for $1.275B; ~$21.5B+ Adobe annual revenue) | **$15 / user / month** billed annually ($19/mo monthly for Pro; bundled in Creative Cloud) | **Forever Free Plan**: Up to **2 members**, 2 active projects, **2 GB cloud storage**, and Camera-to-Cloud integration. |
| **[Vimeo Review](https://vimeo.com)** | Cloud video hosting, client presentation, and time-coded collaborative video review platform. | **~$415M+ Annual Revenue** (~$800M–$1.1B public market cap on NASDAQ) | **$12 / month** billed annually (Starter) or **$20 / month** Standard (unlocks review tools) | **Forever Free Basic Plan**: Up to **1 GB total storage** (capped at 2 videos per month); 7-day trial on paid review tiers. |
| **[Blackmagic Cloud](https://blackmagicdesign.com)** | Real-time cloud project library server, proxy generator, and multi-user DaVinci Resolve collaborative grading. | **~$500M–$800M+ Est. Revenue** (Privately held Australian cinema & broadcast hardware leader) | **$5 / month** per Project Library + **$15 / month** for Cloud Storage (500 GB) | **Forever Free Cloud Account**: Free Blackmagic ID with free cloud presentation preview, proxy upload testing, and free DaVinci Resolve base software. |
| **[DaVinci Resolve Studio](https://blackmagicdesign.com)** | Hollywood standard color grading, NLE, Fusion VFX, and Fairlight audio suite with Neural Engine AI tools. | **~$500M–$800M+ Est. Revenue** (Privately held; bundled with Blackmagic cinema cameras) | **$295 one-time perpetual license** (No recurring subscription; free lifetime major updates) | **Forever Free DaVinci Resolve Base Edition**: Completely free unrestricted 4K/60fps video editing, color grading, Fusion VFX, and audio post-production. |
| **[LucidLink](https://lucidlink.com)** | High-speed cloud-native streaming filespace allowing remote editors to edit RAW/ProRes footage directly from S3. | **~$200M–$350M Est. Valuation** (~$30M–$50M est. ARR; $90M+ VC funding) | **$20 / month** per TB for Basic cloud storage (Team plans start at **$100/mo** for 5 users + 5 TB) | **14-Day Full-Access Free Trial**: Includes **1 TB of high-speed cloud filespace** for up to 5 team members (no credit card required). |
| **[Iconik (Backlight)](https://iconik.io)** | Hybrid cloud Media Asset Management (MAM) indexing local SAN/NAS and cloud storage with AI video tagging. | **Part of Backlight** (~$100M+ Backlight group revenue; backed by PSG Equity) | **$10 / user / month** (Browse user) or **$25 / user / month** (Pro user) + storage/transcode usage | **14-Day Free Trial**: Includes **$100 in free cloud credits** to test hybrid storage indexing, AI transcription, and frame-accurate review. |
| **[ftrack Studio (Backlight)](https://ftrack.com)** | Production tracking, interactive Gantt scheduling, and synchronized cineSync review for VFX and animation. | **Part of Backlight** (Acquired by Backlight; ~$100M+ parent group revenue) | **$25 / user / month** billed annually ($30/mo monthly for ftrack Studio) | **14-Day Full-Access Free Trial**: Unlimited project setups, task boards, and synchronized review sessions during evaluation. |
| **[Shade.inc](https://shade.inc)** | AI creative asset manager and smart drive combining visual semantic search and instant cloud video streaming. | **~$25M–$50M Est. Valuation** (Venture-backed AI post-production startup) | **$15 / user / month** billed annually ($20/mo monthly for Pro) + cloud storage tiers | **Forever Free Starter Plan**: Up to **20 GB cloud storage**, AI visual/audio semantic search, and shareable web review links. |

---

## 💻 Open-Source Film Production & Cinematography Projects

*Curated open-source software, standards, and open cinema hardware sorted descending by GitHub stargazers count.*

| Project & Repository | GitHub Stars | Category / Purpose | License | Free Tier / Self-Hosted Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[OBS Studio](https://github.com/obsproject/obs-studio)** | <a href="https://github.com/obsproject/obs-studio/stargazers"><img src="https://img.shields.io/github/stars/obsproject/obs-studio?style=social&color=white" alt="OBS Studio stars" /></a> | 📹 Live Production & Capture | GPL-2.0 | **100% Free Forever** (No limitations) | Free and open-source software for real-time video capture, camera switching, live streaming, and recording on-set camera feeds. |
| **[FFmpeg](https://github.com/FFmpeg/FFmpeg)** | <a href="https://github.com/FFmpeg/FFmpeg/stargazers"><img src="https://img.shields.io/github/stars/FFmpeg/FFmpeg?style=social&color=white" alt="FFmpeg stars" /></a> | 🎛️ Media Transcoding & Codecs | LGPL / GPL | **100% Free Forever** (No limitations) | The universal cross-platform multimedia framework to decode, encode, transcode, mux, demux, stream, and filter virtually all video and audio formats. |
| **[HandBrake](https://github.com/HandBrake/HandBrake)** | <a href="https://github.com/HandBrake/HandBrake/stargazers"><img src="https://img.shields.io/github/stars/HandBrake/HandBrake?style=social&color=white" alt="HandBrake stars" /></a> | 🎞️ Dailies & Proxy Transcoder | GPL-2.0 | **100% Free Forever** (No limitations) | Open-source video transcoder for converting video from nearly any format to modern, widely supported production and web codecs. |
| **[Blender](https://github.com/blender/blender)** | <a href="https://github.com/blender/blender/stargazers"><img src="https://img.shields.io/github/stars/blender/blender?style=social&color=white" alt="Blender stars" /></a> | 🎨 3D, VFX & Video Editing | GPL-2.0+ | **100% Free Forever** (No limitations) | Comprehensive 3D creation suite supporting modeling, rigging, animation, simulation, rendering, compositing, motion tracking, and Video Sequence Editing (VSE). |
| **[Shotcut](https://github.com/mltframework/shotcut)** | <a href="https://github.com/mltframework/shotcut/stargazers"><img src="https://img.shields.io/github/stars/mltframework/shotcut?style=social&color=white" alt="Shotcut stars" /></a> | ✂️ Non-Linear Video Editor (NLE) | GPL-3.0 | **100% Free Forever** (No limitations) | Cross-platform (Qt), open-source video editor supporting hundreds of audio/video formats, 4K resolutions, and color correction wheels. |
| **[Olive Video Editor](https://github.com/olive-editor/olive)** | <a href="https://github.com/olive-editor/olive/stargazers"><img src="https://img.shields.io/github/stars/olive-editor/olive?style=social&color=white" alt="Olive stars" /></a> | ✂️ Node-Based NLE | GPL-3.0 | **100% Free Forever** (No limitations) | Fast, non-linear video editor with a built-in node-based compositor, OpenColorIO color management, and smooth timeline playback. |
| **[OpenShot](https://github.com/OpenShot/openshot-qt)** | <a href="https://github.com/OpenShot/openshot-qt/stargazers"><img src="https://img.shields.io/github/stars/OpenShot/openshot-qt?style=social&color=white" alt="OpenShot stars" /></a> | ✂️ Non-Linear Video Editor (NLE) | GPL-3.0+ | **100% Free Forever** (No limitations) | Award-winning free and open-source video editor designed to be easy to use, fast to learn, and surprisingly powerful for quick video cuts. |
| **[Kdenlive](https://github.com/KDE/kdenlive)** | <a href="https://github.com/KDE/kdenlive/stargazers"><img src="https://img.shields.io/github/stars/KDE/kdenlive?style=social&color=white" alt="Kdenlive stars" /></a> | ✂️ Non-Linear Video Editor (NLE) | GPL-3.0 | **100% Free Forever** (No limitations) | Professional open-source multi-track video editor built on MLT and KDE frameworks, featuring color scopes, proxy clips, and titling. |
| **[Natron](https://github.com/NatronGitHub/Natron)** | <a href="https://github.com/NatronGitHub/Natron/stargazers"><img src="https://img.shields.io/github/stars/NatronGitHub/Natron?style=social&color=white" alt="Natron stars" /></a> | 🪄 Node-Based Compositor (VFX) | GPL-2.0 | **100% Free Forever** (No limitations) | Open-source node-based video compositing software inspired by Nuke, supporting OpenFX plugins, rotoscoping, keying, and tracking. |
| **[MediaCMS](https://github.com/mediacms-io/mediacms)** | <a href="https://github.com/mediacms-io/mediacms/stargazers"><img src="https://img.shields.io/github/stars/mediacms-io/mediacms?style=social&color=white" alt="MediaCMS stars" /></a> | 📺 Video Review & Self-Hosted CMS | AGPL-3.0 | **100% Free Self-Hosted** (Unlimited users & storage) | Modern, self-hosted open-source video and media CMS ideal for private studio dailies review, media streaming, and cataloging. |
| **[Colour Science](https://github.com/colour-science/colour)** | <a href="https://github.com/colour-science/colour/stargazers"><img src="https://img.shields.io/github/stars/colour-science/colour?style=social&color=white" alt="Colour Science stars" /></a> | 🌈 Color Science & Mathematics | BSD-3-Clause | **100% Free Forever** (No limitations) | Comprehensive Python package providing color science algorithms, color space transformations, chromatic adaptation models, and spectral calculations. |
| **[OpenColorIO (OCIO)](https://github.com/AcademySoftwareFoundation/OpenColorIO)** | <a href="https://github.com/AcademySoftwareFoundation/OpenColorIO/stargazers"><img src="https://img.shields.io/github/stars/AcademySoftwareFoundation/OpenColorIO?style=social&color=white" alt="OpenColorIO stars" /></a> | 🎨 Color Management Standard | BSD-3-Clause | **100% Free Forever** (ASWF Standard) | Academy Software Foundation color management framework used in film post-production, VFX, and animation to ensure consistent color across software. |
| **[OpenTimelineIO (OTIO)](https://github.com/AcademySoftwareFoundation/OpenTimelineIO)** | <a href="https://github.com/AcademySoftwareFoundation/OpenTimelineIO/stargazers"><img src="https://img.shields.io/github/stars/AcademySoftwareFoundation/OpenTimelineIO?style=social&color=white" alt="OpenTimelineIO stars" /></a> | 🎞️ Editorial Interchange API | Apache-2.0 | **100% Free Forever** (ASWF Standard) | Open-source API and interchange format for editorial timeline data, bridging cuts between Final Cut Pro XML, AAF, CMX 3600 EDL, and NLEs. |
| **[OpenEXR](https://github.com/AcademySoftwareFoundation/openexr)** | <a href="https://github.com/AcademySoftwareFoundation/openexr/stargazers"><img src="https://img.shields.io/github/stars/AcademySoftwareFoundation/openexr?style=social&color=white" alt="OpenEXR stars" /></a> | 🖼️ Deep Raster Image Standard | BSD-3-Clause | **100% Free Forever** (ASWF Standard) | High dynamic range (HDR) image file format specification and library developed by ILM, serving as the standard image format for motion picture VFX. |
| **[OpenRV](https://github.com/AcademySoftwareFoundation/OpenRV)** | <a href="https://github.com/AcademySoftwareFoundation/OpenRV/stargazers"><img src="https://img.shields.io/github/stars/AcademySoftwareFoundation/OpenRV?style=social&color=white" alt="OpenRV stars" /></a> | 🔍 Studio Dailies & Screening Playback | Apache-2.0 | **100% Free Forever** (ASWF Standard) | Open-source version of RV, the Sci-Tech Academy Award-winning media review and synchronized playback application for high-resolution dailies. |
| **[Kitsu](https://github.com/cgwire/kitsu)** | <a href="https://github.com/cgwire/kitsu/stargazers"><img src="https://img.shields.io/github/stars/cgwire/kitsu?style=social&color=white" alt="Kitsu stars" /></a> | 📋 VFX & Animation Collaboration | AGPL-3.0 | **100% Free Self-Hosted** (Cloud SaaS plans from €19/user/mo) | Modern web collaboration platform for animation and VFX productions to manage shot reviews, client notes, and team assignments. |
| **[apertus° AXIOM Firmware](https://github.com/apertus-open-source-cinema/axiom-firmware)** | <a href="https://github.com/apertus-open-source-cinema/axiom-firmware/stargazers"><img src="https://img.shields.io/github/stars/apertus-open-source-cinema/axiom-firmware?style=social&color=white" alt="apertus AXIOM stars" /></a> | 📽️ Open Hardware Cinema Camera | GPL-3.0 | **100% Free & Open Source** (Hardware schematics open) | Linux firmware, gateware, and software tools powering the apertus° AXIOM open-source modular professional cinema camera system. |
| **[Zou (Kitsu API Backend)](https://github.com/cgwire/zou)** | <a href="https://github.com/cgwire/zou/stargazers"><img src="https://img.shields.io/github/stars/cgwire/zou?style=social&color=white" alt="Zou stars" /></a> | 🗄️ VFX Production API Server | AGPL-3.0 | **100% Free Self-Hosted** (Unlimited records) | The backend database and REST API server for Kitsu, managing shot breakdown data, casting, asset lists, tasks, and production milestones. |
| **[rawtoaces](https://github.com/AcademySoftwareFoundation/rawtoaces)** | <a href="https://github.com/AcademySoftwareFoundation/rawtoaces/stargazers"><img src="https://img.shields.io/github/stars/AcademySoftwareFoundation/rawtoaces?style=social&color=white" alt="rawtoaces stars" /></a> | 🎯 Camera RAW to ACES Converter | BSD-3-Clause | **100% Free Forever** (ASWF Utility) | Command-line utility to convert digital camera RAW files directly into ACES2065-1 OpenEXR files using spectral response data. |
| **[CinePi RAW](https://github.com/cinepi/cinepi-raw)** | <a href="https://github.com/cinepi/cinepi-raw/stargazers"><img src="https://img.shields.io/github/stars/cinepi/cinepi-raw?style=social&color=white" alt="CinePi stars" /></a> | 📷 DIY Cinema RAW Recorder | BSD-2-Clause | **100% Free & Open Source** (Runs on Raspberry Pi) | Real-time CinemaDNG RAW cinema video recorder application built for Raspberry Pi with high-frame-rate 12-bit DNG capture. |

---

## 📈 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Film-Production-Open-Cinematography&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Film-Production-Open-Cinematography&type=date&legend=top-left)

---

## 💖 Support & Sponsorship

Thank you for exploring and bookmarking **Awesome Film Production & Open Cinematography**! 🎬✨

If you find this curated directory helpful for your productions, filmmaking projects, or software pipelines:
* 🌟 **Star this repository** on GitHub to help other filmmakers discover it.
* 🍴 **Fork the repo** and submit pull requests to add new tools, camera firmware, or standards.
* 📢 **Share with your network** on Discord, LinkedIn, X, and cinematography forums.
* ☕ **Sponsor & Buy a Coffee**: Support ongoing research, indexing, and open-source maintenance via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## 🛠️ Contributing

Contributions are warmly welcomed! 
1. Check existing entries to ensure no duplicates.
2. Ensure new SaaS tools have concrete starting pricing and free tier/trial limits.
3. For open-source tools, include the repository URL, category, license, and active maintenance status.
4. Open a Pull Request following GitHub Flavored Markdown guidelines.

---

## 📄 License & Disclaimer

* **License**: Distributed under the MIT License. See [LICENSE](file:///LICENSE) for details.
* **Disclaimer**: Product names, logos, and brands are property of their respective owners. Listing does not imply commercial endorsement.
