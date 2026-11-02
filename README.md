# npp-releases

Public GitHub Releases feed for **Nhà phân phối** (NPP) Windows desktop builds.

- Source: `apps/hkd-distributor` in the HKD monorepo
- Consumed by `electron-updater` (NSIS Setup)
- Publish via `npm run publish:updates` / `release:win`
- After each publish, older releases/tags are pruned (keep only latest)

Artifacts: https://github.com/trieudtsoft-dot/npp-releases/releases
