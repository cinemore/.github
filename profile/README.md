<div align="center">
  <a href="https://cinemore.com.cn/">
    <img src="https://raw.githubusercontent.com/cinemore/CinePlayer/main/assets/appicon-light.webp" alt="Cinemore" width="96" height="96">
  </a>

  <h1>Cinemore</h1>

  <p><strong>Make every second of playback flawless.</strong></p>
  <p>A high-performance media library and player ecosystem for local media, NAS, private cloud, and home theater playback.</p>

  <p>
    <a href="https://cinemore.com.cn/">Website</a>
    ·
    <a href="https://github.com/cinemore/CinePlayer">CinePlayer</a>
    ·
    <a href="https://github.com/cinemore/anime4k-metal">anime4k-metal</a>
    ·
    <a href="https://github.com/cinemore/fsr-metal">fsr-metal</a>
    ·
    <a href="https://github.com/cinemore/artcnn-metal">artcnn-metal</a>
    ·
    <a href="https://github.com/cinemore/rife-metal">rife-metal</a>
  </p>
</div>

---

## What We Build

Cinemore is built around one goal: turning personal video collections into a polished, high-quality viewing experience across devices.

The product combines media library management, NAS/private-cloud workflows, metadata organization, multi-device continuity, and a playback engine designed for demanding home-theater formats. Our open-source work focuses on the lower-level playback and Apple Metal components behind that experience.

## Open Source Projects

| Project | What it is | Highlights |
| --- | --- | --- |
| [CinePlayer](https://github.com/cinemore/CinePlayer) | An open-source Apple player application built on top of CinePlayerSDK. | iOS, macOS, tvOS, and visionOS playback UI; HDR and Dolby Vision playback support; subtitles, Blu-ray ISO/BDMV, media info, gestures, shortcuts, PiP, Anime4K/FSR/ArtCNN upscaling, and RIFE frame interpolation. |
| [anime4k-metal](https://github.com/cinemore/anime4k-metal) | Native Apple Metal Anime4K image enhancement as a Swift package and CLI. | `CVPixelBuffer` and `CGImage` APIs, bundled Anime4K shader resources, SwiftPM integration, and a macOS CLI. |
| [fsr-metal](https://github.com/cinemore/fsr-metal) | Native Apple Metal FSR 1 spatial upscaling as a Swift package and macOS CLI. | EASU upscaling with optional RCAS sharpening, `CVPixelBuffer` and `CGImage` APIs, and Metal texture encoding for SDR image/video pipelines. |
| [artcnn-metal](https://github.com/cinemore/artcnn-metal) | Native Apple Metal ArtCNN C4F16 image upscaling as a Swift package and macOS CLI. | Native 2× SDR upscaling, embedded model weights with no download required, and `CVPixelBuffer`, `CGImage`, and Metal texture APIs. |
| [rife-metal](https://github.com/cinemore/rife-metal) | Native Apple Silicon RIFE frame interpolation as a Swift package and CLI. | Practical-RIFE v4.26 weights, MPSGraph inference, custom Metal warp kernel, multi-frame interpolation, and quality tiers for different performance targets. |

## Areas We Care About

- **Playback quality**: HDR, Dolby Vision playback, Blu-ray sources, subtitles, audio/video detail, and smooth controls.
- **Media library experience**: local folders, NAS, private cloud, metadata scraping, viewing progress, and multi-user spaces.
- **Apple platform performance**: AVFoundation, Swift, SwiftUI, Metal, MPSGraph, and native media pipelines.
- **Open building blocks**: practical libraries and tools that can be studied, reused, and integrated into other Apple media applications.

## Get Involved

Start with the project that matches what you are building:

- Build a full Apple playback app: [CinePlayer](https://github.com/cinemore/CinePlayer)
- Add Anime4K-style enhancement to an Apple image/video pipeline: [anime4k-metal](https://github.com/cinemore/anime4k-metal)
- Add FSR 1 spatial upscaling and optional sharpening to SDR pipelines: [fsr-metal](https://github.com/cinemore/fsr-metal)
- Add ArtCNN 2× neural upscaling to SDR images and video frames: [artcnn-metal](https://github.com/cinemore/artcnn-metal)
- Add RIFE interpolation to Apple platform tools or experiments: [rife-metal](https://github.com/cinemore/rife-metal)

For product and commercial inquiries, contact: [cinemore@cinemore.com.cn](mailto:cinemore@cinemore.com.cn)

---

<div align="center">
  <a href="https://cinemore.com.cn/">
    <img src="https://raw.githubusercontent.com/cinemore/CinePlayer/main/assets/appicon-light.webp" alt="Cinemore" width="96" height="96">
  </a>

  <h1>Cinemore</h1>

  <p><strong>让每一秒播放，都无可挑剔。</strong></p>
  <p>面向本地媒体、NAS、私有云与家庭影院场景的高性能媒体库播放器生态。</p>

  <p>
    <a href="https://cinemore.com.cn/">官网</a>
    ·
    <a href="https://github.com/cinemore/CinePlayer">CinePlayer</a>
    ·
    <a href="https://github.com/cinemore/anime4k-metal">anime4k-metal</a>
    ·
    <a href="https://github.com/cinemore/fsr-metal">fsr-metal</a>
    ·
    <a href="https://github.com/cinemore/artcnn-metal">artcnn-metal</a>
    ·
    <a href="https://github.com/cinemore/rife-metal">rife-metal</a>
  </p>
</div>

---

## 我们在做什么

Cinemore 的目标很明确：把个人影视收藏变成跨设备、稳定、好看、好用的高质量观影体验。

产品侧围绕媒体库管理、NAS/私有云、本地片源、元数据整理、多端进度同步和高质量播放体验构建。开源侧则聚焦在支撑这些体验的播放器应用层、Apple Metal 图像增强和帧插值组件。

## 开源项目

| 项目 | 说明 | 重点能力 |
| --- | --- | --- |
| [CinePlayer](https://github.com/cinemore/CinePlayer) | 基于 CinePlayerSDK 构建的 Apple 平台开源播放器应用。 | 覆盖 iOS、macOS、tvOS、visionOS 的播放界面；支持 HDR 与杜比视界播放；字幕、蓝光 ISO/BDMV、媒体信息、手势、快捷键、画中画、Anime4K/FSR/ArtCNN 超分和 RIFE 帧插值。 |
| [anime4k-metal](https://github.com/cinemore/anime4k-metal) | 基于 Apple Metal 的 Anime4K 图像增强 Swift Package 与 CLI。 | 提供 `CVPixelBuffer` 和 `CGImage` API，内置 Anime4K shader 资源，支持 SwiftPM 集成和 macOS 命令行工具。 |
| [fsr-metal](https://github.com/cinemore/fsr-metal) | 基于 Apple Metal 的 FSR 1 空间放大 Swift Package 与 macOS CLI。 | EASU 放大与可选 RCAS 锐化，提供 `CVPixelBuffer`、`CGImage` API 和 Metal 纹理编码接口，用于 SDR 图像/视频管线。 |
| [artcnn-metal](https://github.com/cinemore/artcnn-metal) | 基于 Apple Metal 的 ArtCNN C4F16 图像超分 Swift Package 与 macOS CLI。 | SDR 原生 2× 超分，内置模型权重，无需额外下载；提供 `CVPixelBuffer`、`CGImage` 和 Metal 纹理 API。 |
| [rife-metal](https://github.com/cinemore/rife-metal) | 基于 Apple Silicon 的 RIFE 帧插值 Swift Package 与 CLI。 | 内置 Practical-RIFE v4.26 权重，使用 MPSGraph 和自定义 Metal warp kernel，支持多帧插值和不同性能目标的质量档位。 |

## 我们关注的方向

- **播放质量**：HDR、杜比视界播放、蓝光片源、字幕、音视频细节和顺滑控制。
- **媒体库体验**：本地文件夹、NAS、私有云、元数据刮削、观看进度和多用户空间。
- **Apple 平台性能**：AVFoundation、Swift、SwiftUI、Metal、MPSGraph 和原生媒体管线。
- **可复用开放组件**：让更多 Apple 媒体应用可以研究、复用和集成的实用库与工具。

## 参与进来

可以从与你当前目标最接近的项目开始：

- 构建完整 Apple 播放器应用：[CinePlayer](https://github.com/cinemore/CinePlayer)
- 为 Apple 图像/视频管线加入 Anime4K 风格增强：[anime4k-metal](https://github.com/cinemore/anime4k-metal)
- 为 SDR 管线加入 FSR 1 空间放大与可选锐化：[fsr-metal](https://github.com/cinemore/fsr-metal)
- 为 SDR 图像和视频帧加入 ArtCNN 2× 神经网络超分：[artcnn-metal](https://github.com/cinemore/artcnn-metal)
- 在 Apple 平台工具或实验中加入 RIFE 帧插值：[rife-metal](https://github.com/cinemore/rife-metal)

产品与商业合作请联系：[cinemore@cinemore.com.cn](mailto:cinemore@cinemore.com.cn)
