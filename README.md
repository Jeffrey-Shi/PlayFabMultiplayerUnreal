---
title: PlayFab Online Subsystem (OSS) Quickstart
description: Guidance on how to use PlayFab Multiplayer in your Unreal Engine 4 Project.
author: Pushpadant Kacha
ms.author: pkacha
ms.date: 04/4/2022
ms.topic: article
ms.prod: playfab
keywords: playfab, multiplayer, networking, unreal, unreal engine, unreal engine 4, middleware
---

# PlayFab Multiplayer Unreal Online Subsystem (OSS)

## Introduction

The PlayFab Online Subsystem (PF OSS) v2 enables you to make use of PlayFab Multiplayer features like Lobby, Matchmaking, Party and Azure Cognitive Services in your Unreal Engine game.

These features include cross-platform Voice over Internet Protocol (VOIP), cross-network-play, and accessibility features like real-time text chat translation and voice transcription services. It is currently designed for use when developing PC, Xbox, Steam and Nintendo Switch games. This OSS layer works seamlessly on top of the existing base platform OSS layers (such as the base GDK OSS layer provided by Epic for Xbox and PC Game Pass). PlayFab OSS compliments the base OSS by adding support for PlayFab Lobby, Matchmaking, Party networking and Voice over Internet Protocol (VOIP).

## Getting Started

The quickstart guide for OnlineSubsystemPlayFab can be found at:

[PlayFab Online Subsystem](https://docs.microsoft.com/gaming/playfab/features/multiplayer/networking/party-unreal-engine-oss-quickstart)

## Version

|OSS version
|-|
|2.2.0

## Compatibility

|Unreal Engine version|4.27|
|-|-|
Multiplayer SDK|v1.1.0+
Platforms|GDK, Win64+Steam, Nintendo Switch

## Important Note

The PlayFab Online Subsystem (PF OSS) v2 is currently in preview. Preview programs give Microsoft and customers the opportunity to evaluate and understand the new feature before it becomes part of the standard feature set of PlayFab.

Preview SDKs and engine plugins might not support all the scenarios planned for the  generally available (GA) release and are not necessarily fully compliant with the certification requirements for the target platform.

For platform certification and shipping to retail users, games must use the generally available (GA) release of the SDKs and engine plugins that will become available in the coming months.

For games shipping to Xbox console and PC Game Pass program before September 2022, it is recommended that games use the base Online Subsystem (OSS) for GDK provided by Epic for multiplayer integration (backed by Xbox Live multiplayer services) and the PlayFab Online Subsystem (PF OSS) v1.x for Party networking and VOIP available on the [GDK download website](https://aka.ms/gdkdl).

## Known Limitations and Issues in the Current Preview Build

- [General] Currently cross-play is only supported between Xbox consoles, PC Game Pass, Steam, and Switch.  Cross-play support between other platforms is coming soon.
- [Xbox] Currently cannot use Xbox shell to send or receive platform level invites with PF OSS v2. This functionality will be supported in the generally available (GA) release.
- [Xbox] Currently not fully integrated with Multiplayer Activity Service (Multiplayer activity is not always in-sync with user’s lobby state, user’s joinability is not populated correctly). This functionality will be supported in the generally available (GA) release.
