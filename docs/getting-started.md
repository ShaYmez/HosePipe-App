# Getting started

HosePipe is FreeSTAR’s live DMR talkgroup monitor for SystemX.

Open **[hosepipe.freestar.network](https://hosepipe.freestar.network)** in your browser (Chrome or Edge on desktop recommended).

## Listen to a talkgroup

**From a card** — click **Listen** on any talkgroup in the grid.

**Direct tune** — enter a TG number in **Listen to a talkgroup now** and click **Listen now**. This works even when the talkgroup isn't showing as active.

**Shareable link** — open a link like `https://hosepipe.freestar.network/?tg=2350` (or `#tg=2350`) to start already tuned.

**Favorites** — tap the star on a card to save it locally in your browser. Use the **Favorites** filter or the favorites strip for quick retune.

**Stop** — click **Stop** / **Stop listening** on the card, in the listening desk, or in the mobile listening bar.

## Find talkgroups

- **Filter talkgroups** — search by TG number, alias, callsign, or radio ID; exact TG numbers (and comma-separated lists) are supported
- **Country** — use the dropdown in the header to narrow the grid by country; talkgroup cards also show country flags when known
- **Favorites** — show only talkgroups you have starred

Cold standby talkgroups are hidden by default; use **Show all standby** if you need them.

## Listening desk

The sidebar shows what you're tuned to and whether audio is live.

- Collapse or expand the desk like Activity trail — when collapsed you’ll still see status (ON AIR / READY) and the current source
- **Volume** — slider and mute; your level and mute preference are remembered. On desktop you can pin volume to a floating dock; if it isn’t pinned and the desk is collapsed, mute, a short slider, and a compact level meter stay next to ON AIR / Stop
- **Speech clarity** — optional clearer voice. On desktop, expand **Speech clarity** to fine-tune; settings are saved in your browser. On mobile, use the Clarity control in the listening bar
- **Talkgroup details** — expandable; when collapsed it still shows the source alias / detail

On desktop, a floating volume dock at the bottom can also show a level meter. On mobile, a listening bar at the bottom provides volume, clarity, and stop while tuned.

## Activity trail

Recently heard traffic appears in the sidebar. Collapse the panel to save space — the header still shows the latest call when available.

On desktop you can drag sidebar panels to reorder them, or undock a panel to float it on the page. Use **Reset** under Sidebar to restore the default layout.

## Net Control

Optional tools for running a net. Open **Net Control** in the sidebar (off by default).

- Add check-ins from the last heard station
- Reorder the list, mark waiting / now / done, and advance to the next station
- Session notes and an elapsed clock
- Copy the roster as plain text for chat or email

Everything stays on your device — no account required. Clear the session when the net is over.

## Connection status

The status pill in the header shows:

- **Connected** — monitor link is healthy
- **Connecting** / **Reconnecting** — establishing or restoring the connection; tap to retry if stuck
- **Disconnected** — link is down; tap to retry
- **ON AIR** / **SYNCING** / **READY** — listening-desk status for live audio, brief recovery, or idle tuned state

HosePipe keeps listening through ordinary Wi‑Fi and mobile network changes when it can.

## Reporting problems

Note the version in the page footer (or hero), your browser, the talkgroup ID, and whether speech clarity was on — then [open an issue](https://github.com/ShaYmez/HosePipe-App/issues).
