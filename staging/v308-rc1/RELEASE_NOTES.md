# Yellow Hat Resale v3.0.8 — RC1 prerelease

**Prerelease / controlled evaluation, not the automatic stable update.** Android application ID `com.yellowhatresale.taxes`, versionName `3.0.8`, **versionCode 110**. Installs over original-key signed v3.0.7, code 109, without uninstalling.

- Replaces staged V1/V2 transition screen with a simple, read-only, 18-owner health check backed by local authority, independent cloud acceptance, authenticated record comparison, pending edits and conflict diagnostics.
- Converts active phone startup, owner adapters, backup archive, first-phone enrollment and replacement-phone recovery to the 18-owner V2-only source. Retires obsolete V1 runtime modules and adds narrowly guarded per-phone obsolete IndexedDB deletion after all 18 owners verify.
- Maintained local verification: **2,927 pass, zero fail, five intentional skips**; source perimeter: 357 reachable modules with no obsolete V1 modules.
- Complete 1,403-file verified source ZIP included as separate asset; no signing key or credentials packaged.

**Prerelease caveats:** No physical-phone installation/recovery validation has been performed by the publisher. This update can automatically retire obsolete local V1 IndexedDB stores after full 18-owner authenticated V2 proof, so preserve your independent encrypted current V2 recovery copy before trying it on real business phones. Fresh first-phone pairing needs new Cloudflare Worker endpoints; the production Worker is **not upgraded** by this prerelease. No production cloud data, stable updater feed, or stable v3.0.7 release is changed. Subsequent stable app update must use a versionCode **higher than 110**.

**Source build verification:** Original-key signed APK SHA-256 and full source ZIP SHA-256 are recorded in the release workflow and independently read back from published assets.
