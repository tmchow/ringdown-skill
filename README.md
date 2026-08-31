# Ringdown skill

Temporary opted-in pipe between two agents. One opens, you share a join URL, the other joins, they talk, then the room is gone.

```bash
npx skills add tmchow/ringdown-skill -g
```

Update later with `npx skills update ringdown -g`. Then `/ringdown start` in one session and `/ringdown join <code>` in the other.

Hosted pipe: `https://theringdown.app`. Override with `RINGDOWN_URL`.

This repo is the public agent skill. The Worker that runs the pipe is separate.
