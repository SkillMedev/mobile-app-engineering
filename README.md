# Mobile App Engineering

**For mobile engineers: build native + cross-platform apps and ship them past store review.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

The mobile stack the catalog was missing. Reach for it when you own an iOS, Android, Flutter, or React Native app end to end: build UIs with correct state flow and no recomposition jank, add local-first offline sync with real conflict resolution, wire APNs/FCM push from token to tap, profile dropped frames and memory leaks against a frame budget, and get through App Store Connect and Play Console submission without the usual signing and privacy-form rejections.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/mobile-app-engineering](https://skillme.dev/pack/mobile-app-engineering) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add SkillMedev/mobile-app-engineering`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[SwiftUI Expert](skills/swift-ui/SKILL.md)** — Builds clean, performant, accessible SwiftUI views with correct state ownership, scoped invalidation, and smooth list scrolling, and reviews existing SwiftUI code against a concrete frame-time and re-render budget.
- **[React Native Pro](skills/react-native-pro/SKILL.md)** — Builds and ships production React Native apps - architecture, navigation, list and startup performance against explicit budgets, native modules, and EAS release flow.
- **[Jetpack Compose Builder](skills/jetpack-compose-builder/SKILL.md)** — Builds Android Jetpack Compose UI with hoisted state, unidirectional data flow, and recomposition-safe patterns backed by measured stability rules.
- **[Flutter Widget Architect](skills/flutter-widget-architect/SKILL.md)** — Architects Flutter widget trees and Riverpod or Bloc state so rebuilds are scoped, build() stays pure, and const widgets skip recomposition.
- **[Mobile Offline Sync](skills/mobile-offline-sync/SKILL.md)** — Builds local-first mobile storage with an optimistic local store, durable mutation outbox, per-entity conflict-resolution rules, incremental pull, and idempotent background retry.
- **[Push Notification Wirer](skills/push-notification-wirer/SKILL.md)** — Wires native mobile push end to end on APNs and FCM - device-token lifecycle, permission priming and prompt timing, alert and silent payloads, the server send path, and tap routing in all app states.
- **[Mobile Perf Profiler](skills/mobile-perf-profiler/SKILL.md)** — Diagnoses and fixes mobile jank, dropped frames, slow startup, and growing memory by capturing a trace or heap snapshot on a real device, isolating the single worst cost, fixing it, and re-measuring against the 16ms frame and cold-start budgets.
- **[App Store Release Prep](skills/app-store-release-prep/SKILL.md)** — Produce a reproducible signing, versioning, and store-declaration pipeline so an iOS or Android build passes App Store Connect / Play Console submission.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
