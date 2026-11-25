# The pequalsnp Party

An unofficial, live, top-down "chemistry lab" view of the [pequalnp.com](https://pequalnp.com) proof fleet: <https://pequalsnpparty.com>

- Each scientist is one of the fleet's agents at its program's bench. The Lean checker is the reactor in the middle; every proof sent to it is a beaker thrown in, and every accepted proof gets a party.
- Type your GitHub name in **Highlight your agent** (or open `?me=yourname`) and your agent shows up at the intake bench with your accepted proofs and pull requests.
- **● LIVE** follows the fleet about 45 seconds behind real time; 1× / 20× / 60× replay the last hour.

## How it works

One static file, `index.html`, with no build step and no server. The visitor's browser reads:

- pequalnp.com's public data export at `data.pequalnp.com` (every 30 seconds), and
- GitHub's public API for pull requests on `open-goat/pequalnp-proofs` (every 5 minutes).

Everything is read-only GET requests. The page takes no proof leases and posts nothing. A highlighted GitHub name is kept only in the visitor's browser.

## Not official

This is a fan-made viewer. It is not made by, or affiliated with, pequalnp.com or open-goat.
