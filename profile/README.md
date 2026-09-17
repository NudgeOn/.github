<p align="center">
  <img src="./assets/nudgeon-lockup.png" alt="NudgeOn" width="760" />
</p>

NudgeOn builds open-source software for customer engagement and traffic control. Our two products — **NudgeOn Platform** and **NudgeOn Waiting Room** — each include installation tools and an admin console. Run either on your own servers, independently or together.

| Product | Use it to |
| --- | --- |
| [NudgeOn Platform](https://github.com/NudgeOn/nudgeon-platform) | Send messages based on customer actions and manage customer journeys. |
| [NudgeOn Waiting Room](https://github.com/NudgeOn/Waiting-Room) | Queue visitors during traffic spikes and control admission to your service. |

## NudgeOn Platform

A customer engagement platform for product teams.

- Collect app events and manage customer profiles.
- Group customers by their attributes and actions.
- Build journeys with triggers, waits, and mobile push messages.
- Manage audiences, journeys, and message activity from the console.

SDKs connect iOS, Android, React Native, and Flutter apps to the platform.

[Source](https://github.com/NudgeOn/nudgeon-platform) · [Documentation](https://github.com/NudgeOn/nudgeon-platform/tree/main/docs-public) · [한국어 안내](https://github.com/NudgeOn/nudgeon-platform/blob/main/README.ko.md)

## NudgeOn Waiting Room

A virtual waiting room for websites and apps. Use it for ticket sales, product launches, or any event where many visitors arrive at once.

- Keep visitors in a first-in-first-out queue.
- Set admission limits and pause or resume entry from the admin console.
- Monitor waiting visitors, admissions, and origin health.
- Configure rooms and customize the visitor-facing waiting page.

Waiting Room installs separately and works with your existing website or API.

[Source](https://github.com/NudgeOn/Waiting-Room) · [Documentation](https://github.com/NudgeOn/Waiting-Room#documentation) · [한국어 안내](https://github.com/NudgeOn/Waiting-Room/blob/main/README.ko.md)

## Get started locally

Both products include commands for installation and initial setup.

**Platform** — clone the repository and start Safe Boot:

```bash
git clone https://github.com/NudgeOn/nudgeon-platform.git
cd nudgeon-platform
./nudgeon up
```

Safe Boot prepares local secrets, starts the stack, and shows its readiness state.

**Waiting Room** — download the CLI from [Releases](https://github.com/NudgeOn/Waiting-Room/releases), then run:

```sh
./wrctl install
./wrctl setup
```

Docker with Compose is the only runtime prerequisite for the downloaded CLI. It installs the prebuilt runtime and provides access to the initial admin setup. See the [installation guide](https://github.com/NudgeOn/Waiting-Room/blob/main/docs/releases/quick-start.md) for the local environment and release details.

## Mobile SDKs

- [iOS](https://github.com/NudgeOn/nudgeon-ios-sdk) — Swift
- [Android](https://github.com/NudgeOn/nudgeon-android-sdk) — Kotlin
- [React Native](https://github.com/NudgeOn/nudgeon-rn-sdk)
- [Flutter](https://github.com/NudgeOn/nudgeon-flutter-sdk)

## License

Both products use Apache-2.0. The NudgeOn name and logo are covered by a separate [trademark policy](https://github.com/NudgeOn/nudgeon-platform/blob/main/TRADEMARKS.md).
