# Apple Unity Plug-Ins

Note: See the [2025-beta1](https://github.com/apple/unityplugins/tree/2025-beta1) branch for updates to the Apple.GameKit and Apple.PHASE plug-ins to support new features and APIs announced at WWDC '25 on June 9, 2025.

## Overview
The Apple Unity Plug-Ins expose a selection of Apple platform frameworks to Unity developers.

To get started with integration of these plug-ins into your Unity projects, run `python3 build.py` and use the `.tgz` packages in the `Build/` directory. For a more detailed walkthrough, please check out the [Quick Start Guide](Documentation/Quickstart.md), which also includes introductions to each plug-in.

| [Home](README.md) | [Feedback](Documentation/Feedback.md) | [Quick Start Guide](Documentation/Quickstart.md) | [Build Script](Documentation/BuildScript.md) |
| :---: | :---: | :---: | :---: |

| Plug-In | Description |
| :------ | :---------- |
| Apple.Core | Provides integrated build post process management and Editor UI.<br/>**Note:** Apple.Core is a dependency of all Apple Unity plug-ins.|
| Apple.Accessibility | Provides Apple's accessibility to Unity developers allowing adding supports to Apple's built-in assistive technologies such as VoiceOver.|
| Apple.CoreHaptics | Brings Apple's Core Haptics framework to Unity developers, enabling for customizable haptic patterns and in-depth playback control on supported devices. This Plug-In also includes UIKit's UIFeedbackGenerator API.|
| Apple.GameController | Exposes Apple's GameController framework to Unity developers allowing for rich controller features in macOS, iOS, and tvOS apps. |
| Apple.GameKit | Allows Unity developers to easily integrate GameKit features such as leaderboards, achievements, and match making. |
| Apple.PHASE | The PHASE plug-in allows Unity developers to take full advantage of Apple's new geometry and material aware spatial audio system. |

## Minimum Supported OS Versions
| OS | Version |
| :- | :------ |
| iOS | 13.0 |
| macOS | 10.15 |
| tvOS | 13.0 |
| visionOS | 1.0 |
| watchOS | not supported |


## Leaving Feedback
See the [Feedback](Documentation/Feedback.md) documentation for more information.
