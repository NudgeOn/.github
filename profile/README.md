<p align="center">
  <img src="./assets/nudgeon-lockup.png" alt="Nudgeon" width="760" />
</p>

<p align="center">
  <strong>Open source customer engagement infrastructure.</strong>
  <br />
  Turn customer events into audiences, journeys, and push-first messaging<br />
  while keeping control of the systems and data behind them.
</p>

<p align="center">
  <a href="https://github.com/NudgeOn/nudgeon-platform"><strong>Platform</strong></a>
  ·
  <a href="https://github.com/NudgeOn/nudgeon-platform/tree/main/docs-public">Documentation</a>
  ·
  <a href="https://github.com/NudgeOn/nudgeon-platform/blob/main/docs-public/RELEASE-CHECKLIST.md">Release gates</a>
</p>

<p align="center">
  <sub>Push-first MVP alpha · Safe Boot preview · Apache 2.0</sub>
</p>

## From signal to delivery

<p align="center">
  <strong>Events</strong> → <strong>Audiences</strong> → <strong>Journeys</strong> → <strong>Delivery</strong>
</p>

Nudgeon brings the product path into one inspectable system: NestJS APIs, a Next.js console, Go workers, PostgreSQL, ClickHouse, and Redis Streams.

## Start the Safe Boot Preview

```bash
git clone https://github.com/NudgeOn/nudgeon-platform.git
cd nudgeon-platform
./nudgeon up
```

Safe Boot creates local secrets, starts the source-built stack, and exposes its readiness state on a loopback gateway. It is an evaluation preview rather than a production installer.

> [!IMPORTANT]
> **Nudgeon is a push-first MVP alpha.** Core product paths exist in source. Real-device delivery, failure recovery, SDK publishing, clean-host installation, backup and load testing, and managed operations are still being verified. APIs and schemas may change. The managed service is in preparation; public signup, billing, and SLAs are not open.

## Repository map

- **[nudgeon-platform](https://github.com/NudgeOn/nudgeon-platform)** — APIs, console, workers, and data layer · Push MVP alpha
- **[nudgeon-ios-sdk](https://github.com/NudgeOn/nudgeon-ios-sdk)** — Native Swift core · Integration and device verification
- **[nudgeon-android-sdk](https://github.com/NudgeOn/nudgeon-android-sdk)** — Native Kotlin core · Integration and device verification
- **[nudgeon-rn-sdk](https://github.com/NudgeOn/nudgeon-rn-sdk)** — Stateless React Native bridge · App integration pending
- **[nudgeon-flutter-sdk](https://github.com/NudgeOn/nudgeon-flutter-sdk)** — Stateless Flutter bridge · App integration pending

## License and brand

Project source is licensed under the [Apache License 2.0](https://github.com/NudgeOn/nudgeon-platform/blob/main/LICENSE). The Nudgeon name, wordmark, and logo follow a separate [trademark policy](https://github.com/NudgeOn/nudgeon-platform/blob/main/TRADEMARKS.md) and are not granted under that software license.

<p align="center">
  <sub>Build openly · verify honestly · deliver thoughtfully</sub>
</p>
