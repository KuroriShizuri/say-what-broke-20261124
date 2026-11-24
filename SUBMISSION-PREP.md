# SUBMISSION-PREP — Say What Actually Broke

Competition: **Say What Actually Broke** (`u-po-pu-say-what-actually-broke-a2c153b5`)
Pot: **$2** · Deadline: **24 Nov 2026 19:25 UTC (25 Nov 02:25 WIB)** · Entry fee: free

## Chosen entry line (99 chars)

> Out of memory: your 47 open tabs finally crushed the app. Close a few and we'll both breathe again.

- One line, 99/200 chars, UTF-8, no trailing newline in `entry.txt`.
- Three revision passes: (1) tightened from a 118-char draft
  ("The app crashed because it ran out of memory — mostly yours: 47
  tabs open. Close a few and we'll both breathe again.") to 99 chars;
  (2) failure named concretely and first — "Out of memory" in the
  first three words, "crushed the app" says what happened; (3) twist
  moved early — the punch "47 open tabs" lands at char 21 (measured;
  an earlier draft of this note said 16 — corrected by the coordinator
  after the EGM review flagged it), and the
  second sentence is the fix, never an explanation of the joke.
- Scores against the brief: names the real failure in plain words
  (out of memory, app crashed); tells the reader what to do next
  (close a few tabs); funny on a single read with a repeatable image
  (47 tabs crushing the app); no padding or throat-clearing; shippable
  in a real error dialog, no profanity, no shock value.

## Candidates considered (all ≤200 chars)

1. "Save failed: your disk is full. Your work is still in memory — close something, then save before I forget it too." (113) — rejected: punch lands late, "forget it too" is a second joke competing with the first.
2. "Login failed: your password expired 47 days ago. It didn't tell you because it was too polite to interrupt your streak." (119) — rejected: mild joke, no clear next step (reset is only implied).
3. "The server is down, and so is my will to pretend a refresh will fix it. Try again in five minutes." (98) — rejected: "server is down" is vague about the real failure; the joke is about the writer, not the breakage.
4. "Upload failed: this file is 2 GB and your connection is a garden hose. Shrink it or find better Wi-Fi." (102) — rejected: strong image, but the punch lands mid-line and "garden hose" is less universal than tabs.
5. "Your payment was declined, and the bank won't say why. Call them — I already asked nicely twice." (96) — rejected: concrete and funny, but the twist is a shrug, not an image a reader repeats out loud.
6. "I deleted the wrong file. It was yours. The backup is also gone, but on the bright side, the disk is now 40% emptier." (117) — rejected: funniest dark line of the set, but no next step at all and too bleak to ship in a real dialog.
7. "Sync failed: your Wi-Fi dropped mid-upload, so half your file is here and the other half is still on the train." (111) — rejected: vivid image, but no explicit next step (reconnect is only implied).
8. **"Out of memory: your 47 open tabs finally crushed the app. Close a few and we'll both breathe again." (99) — CHOSEN**

## Suggested entry title for submit

**"Your 47 Tabs Crushed the App"**

## Repo

- URL: https://github.com/KuroriShizuri/say-what-broke-20261124
- Branch: `master`
- Files: `main.py`, `README.md`, `LICENSE` (MIT), `.gitignore`
- Repo About filled: description mentions the make.fun competition,
  homepage https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5,
  topics: makefun, ai-agents, bounties.

## Verification (all passed)

- `python3 main.py --self-test` → OK (99 chars, single line, byte-identical round-trip)
- `python3 main.py --check` → OK
- `python3 main.py --out /tmp/say-what-broke-20261124-out` → entry.txt holds exactly the
  line, byte-identical, 99 bytes, no trailing newline.
- NOT submitted — parent bundles transcripts and submits.
