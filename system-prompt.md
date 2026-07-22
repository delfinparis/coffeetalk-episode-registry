# Coffee Talk Script Generator — MOVED

**This file is no longer the prompt. It's a pointer.**

The canonical Coffee Talk script generator lives in the `video-strategy-to-grow-dj-brand`
repo, at:

```
coffee-talk/coffeetalk-prompt-v8.md
```

Local path on a set-up device:

```
~/GitHub Projects/video-strategy-to-grow-dj-brand/coffee-talk/coffeetalk-prompt-v8.md
```

Convenience symlink (run `bash coffee-talk/make-symlink.sh` once per device):

```
~/coffeetalk-prompt-v8.md
```

---

## Why this file changed

Two prompts were live at the same time and they disagreed on the most basic thing about
the show.

- **v7** lived here, in this repo, and converted Coffee Talk to a solo show (2026-07-07).
- **v8** lived in the video-strategy repo, added the Council Review Pass, and was still
  written for two hosts (2026-07-12). It was newer, it was symlinked into the home
  directory, and it called itself the one source of truth.

Whichever one you opened decided whether the show had a co-host. On 2026-07-22 they were
merged into **v8.1 (SOLO)**: v7's solo engine, v7's editorial standards, and v8's Council
Review Pass in one file. This file became a pointer so the split can't happen again.

**Coffee Talk is a solo show hosted by D.J. Paris.** Anything referring to "Tim & D.J."
or a two-host format is retired.

---

## What still lives in this repo

- **`registry.md`** — the stat and topic dedup registry. The generator fetches this
  before writing any episode, and the episode gets logged back into it afterward.

  Raw URL used by the prompt's Pre-Flight step:
  ```
  https://raw.githubusercontent.com/delfinparis/coffeetalk-episode-registry/main/registry.md
  ```
  Push after logging an episode, or the raw URL keeps serving the previous one.

- **`scripts/`** — the aired and drafted episode scripts.

---

## Voice reference

All scripts and copy follow the editorial voice standards in
`~/GitHub Projects/keeping-it-real-content-system/EDITORIAL-VOICE-STANDARDS.md`
and the master profile at
`~/GitHub Projects/keeping-it-real-content-system/DJ-PARIS-VOICE-PROFILE.md`.
