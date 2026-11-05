# Social Graph · Flutter · Mobile

Independent presentation module skeleton for **Social Graph**. Intended boundary: flutter ios/android application using dart and mobile widgets.

**Status: skeleton.** This repository supplies package/build structure and an explicit extension entry. It is not a completed feature, production API integration or registry publication. Existing implementations and package identities remain authoritative.

- Capability/source key: `liberusoftware/module-social-network-social-graph`.
- Presentation scope: [Social Graph](https://github.com/liberusoftware/documentation/blob/main/projects/social-network/flutter/social-graph.md).
- Canonical ownership record: [source/plan group](https://github.com/liberusoftware/documentation/blob/main/projects/social-network/nextjs/social-graph.md).
- Registry identity: `module_social_network_social_graph_flutter`.
- Foundation: [module-boilerplate-flutter](https://github.com/liberusoftware/module-boilerplate-flutter) at `ff95e801183203fd3ab58993d7793fbae549151e`.

## Develop and verify

```bash
flutter pub get
flutter analyze
```

The public Dart entry exports `moduleDefinition`, a registration record. Add reviewed widgets, DTO mapping and injected services here. The package is not published to pub.dev, and it implements no native audio/device or business workflows yet.

Use the committed locks and declared toolchain. Read [AGENTS.md](AGENTS.md) and the [presentation runbook](https://github.com/liberusoftware/documentation/blob/main/guides/presentation/FLUTTER.md). Keep host routing, navigation, session integration and deployment outside reusable capability code. Keep Laravel policy, tenant context, validation, transactions, persistence and state transitions in the canonical owner. Do not infer endpoints or business DTOs from this registration descriptor.

Implement reviewed loading, empty, denied, invalid, stale/conflict, pending and recoverable failure states when adding real workflows. Test meaningful allowed/denied/wrong-tenant behavior against the authoritative API or public action. Reconcile uncertain writes before retrying and clear scoped cached data on logout. For device targets, review lifecycle, secure storage and platform support; a local draft is not a completed server transaction.

## Documented consumer project families

These project skeletons belong to documented consumer scopes. Their presence does not prove integration or feature parity; review compatible core/API contracts before enabling this package.

- [Social Network](https://github.com/liberusoftware/project-social-network-mobile-flutter): Profiles, feeds, communities and moderation.

## Other presentations of this capability

The companion repositories use the same canonical scope and preserve their own presentation lifecycle. Availability is recorded by the repository inventory; a repository link is not evidence of an implemented feature.

- [Laravel · Filament](https://github.com/liberusoftware/module-social-network-social-graph-filament).
- [Laravel · Inertia · Vue](https://github.com/liberusoftware/module-social-network-social-graph-vue-inertia).
- [Laravel · Inertia · React](https://github.com/liberusoftware/module-social-network-social-graph-react-inertia).
- [Nuxt · Vue](https://github.com/liberusoftware/module-social-network-social-graph-nuxt).
- [Next.js · React](https://github.com/liberusoftware/module-social-network-social-graph-nextjs).
- [React Native · Expo](https://github.com/liberusoftware/module-social-network-social-graph-react-native).
- [Dart · Desktop](https://github.com/liberusoftware/module-social-network-social-graph-dart-desktop).
- [Dart · Mobile](https://github.com/liberusoftware/module-social-network-social-graph-dart-mobile).

## Release boundary

Build and inspect a packed artifact in a clean consumer before an authorized registry release. Keep prerelease/skeleton status until implemented behavior and supported runtimes are verified. Repository creation does not publish to Packagist, npm or pub.dev. Native signing and store distribution are separate application responsibilities.
