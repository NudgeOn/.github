# NudgeOn organization assets

- `nudgeon-mark.svg` — the chain reaction symbol for the GitHub organization avatar.
- `nudgeon-lockup.svg` — organization profile hero lockup.
- `nudgeon-avatar.png` — 1024 px raster export for GitHub organization settings.
- `nudgeon-lockup.png` — 1600 px raster preview of the hero lockup.

The **chain reaction** mark consists of three equal rounded tiles leaning progressively forward at 0°, 14°, and 28°. One small nudge sets the next action in motion, expressing customer engagement and automated journeys.

Brand colors:

- Mark and wordmark: `#0B2438`
- Background: `#FFFFFF`

These assets share the same source as [nudgeon-platform/docs-public/assets](https://github.com/NudgeOn/nudgeon-platform/tree/main/docs-public/assets). Keep both repositories synchronized. The platform calls the lockup `nudgeon-logo.svg/png`.

To regenerate the raster assets with librsvg:

```bash
rsvg-convert -w 1600 profile/assets/nudgeon-lockup.svg -o profile/assets/nudgeon-lockup.png
rsvg-convert -w 1024 -h 1024 profile/assets/nudgeon-mark.svg -o profile/assets/nudgeon-avatar.png
```

The SVG wordmark uses system typography; use the PNG for consistent display in the organization profile. Updating these files does not change the organization account avatar automatically: apply `nudgeon-avatar.png` separately in organization settings.

The NudgeOn name, wordmark, and logo are brand assets and are not licensed under Apache-2.0 with the software source.
