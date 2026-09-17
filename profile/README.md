<p align="center">
  <img src="./assets/nudgeon-lockup.png" alt="NudgeOn" width="760" />
</p>

NudgeOn makes open-source tools for customer messaging and virtual waiting rooms. Both run on your own servers, with a few commands to get started locally.

- **[Platform](https://github.com/NudgeOn/nudgeon-platform)** sends messages based on what customers do in your app.
- **[Waiting Room](https://github.com/NudgeOn/Waiting-Room)** queues visitors when traffic spikes and lets you control how quickly they enter.

## NudgeOn Platform

Collect app events, define audiences, and build customer journeys that send mobile push notifications.

Start locally with Safe Boot:

```bash
git clone https://github.com/NudgeOn/nudgeon-platform.git
cd nudgeon-platform
./nudgeon up
```

Safe Boot creates local secrets, starts the stack, and shows its readiness state.

[Documentation](https://github.com/NudgeOn/nudgeon-platform/tree/main/docs-public) · [Release checklist](https://github.com/NudgeOn/nudgeon-platform/blob/main/docs-public/RELEASE-CHECKLIST.md)

## NudgeOn Waiting Room

Put a waiting room in front of your website or API for a ticket sale, product launch, or signup opening. Visitors join a first-in-first-out queue. From the admin screen, you can pause admission or set how many visitors enter at a time.

Waiting Room works with websites and apps. It installs separately; you do not need the messaging platform to use it.

The published release is a **local Docker Preview**. Production installation, sustained high-load testing, and high availability are still in progress.

Download the CLI from [Releases](https://github.com/NudgeOn/Waiting-Room/releases), then start the local setup:

```sh
./wrctl install
./wrctl setup
```

You only need Docker with Compose. There is no source build or Go/Node.js installation to work through. Use the setup command to register the first administrator. The Preview runs locally with a demo origin.

[Getting started](https://github.com/NudgeOn/Waiting-Room/blob/main/docs/releases/quick-start.md) · [Beta checklist](https://github.com/NudgeOn/Waiting-Room/blob/main/docs/beta-plan.md) · [한국어 안내](https://github.com/NudgeOn/Waiting-Room/blob/main/README.ko.md)

## Repositories

- [nudgeon-platform](https://github.com/NudgeOn/nudgeon-platform) — messaging APIs, console, workers, and data layer
- [Waiting-Room](https://github.com/NudgeOn/Waiting-Room) — waiting room, admission control, and operator dashboard
- [nudgeon-ios-sdk](https://github.com/NudgeOn/nudgeon-ios-sdk) — native Swift SDK
- [nudgeon-android-sdk](https://github.com/NudgeOn/nudgeon-android-sdk) — native Kotlin SDK
- [nudgeon-rn-sdk](https://github.com/NudgeOn/nudgeon-rn-sdk) — React Native bridge
- [nudgeon-flutter-sdk](https://github.com/NudgeOn/nudgeon-flutter-sdk) — Flutter bridge

The native iOS and Android SDKs are published. React Native and Flutter packages are being prepared for release.

## License

Both projects use Apache-2.0. The NudgeOn name and logo are covered by a separate [trademark policy](https://github.com/NudgeOn/nudgeon-platform/blob/main/TRADEMARKS.md).
