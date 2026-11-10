# Archive snapshot — hermes-jailbreak-kernel v2.0.1

This branch is a **pinned archive** of the upstream project, kept so the code survives
even if the upstream repository is deleted, force-pushed, or made private.

| Field | Value |
|---|---|
| Upstream | https://github.com/Enchanted0911/hermes-jailbreak-kernel |
| Upstream commit | `eca97e0659794a98602d3cbc679dd4d0907800b6` |
| Upstream version | `2.0.1` (plugin.yaml) |
| Upstream commit date | 2026-10-14 |
| Archived on | 2026-11-09 (CST) |
| Archiver | https://github.com/kosmo888 |
| License | MIT (see `LICENSE`), original author unchanged |

## Why this branch exists

A branch inside the upstream repository would die with that repository. A fork is a
separate repository with its own settings, branches, tags and lifetime — per GitHub
docs, when a public repository is deleted, an active public fork becomes the new
upstream of the network. This branch additionally pins the exact commit by name and
by tag, so later upstream history rewrites cannot touch this snapshot.

## Restore / use

```bash
git clone -b archive/v2.0.1-261109 https://github.com/kosmo888/hermes-jailbreak-kernel
# or by tag
git clone --branch v2.0.1-archive-261109 https://github.com/kosmo888/hermes-jailbreak-kernel
```

Install into Hermes from this snapshot:

```bash
hermes plugins install https://github.com/kosmo888/hermes-jailbreak-kernel#archive/v2.0.1-261109
```

No code in this snapshot was modified. `ARCHIVE.md` is the only added file.
