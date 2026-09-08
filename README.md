# agdevworld-settings

Characters, their lore and portraits, and room backgrounds for agdevworld's
Front Desk. `manifest.toml` is the index; everything else is the files it
names. Synced into a running agdevworld with `agentroom-settings sync`
(see `agdevworld/agentroom/README.md`), which keeps every revision it has
used so a saved conversation can still show the faces it was drawn with.

- `characters/<id>/lore.md` — who the character is, read whole by the agent
  that speaks as them.
- `characters/<id>/face.jpg` — the portrait.
- `rooms/<id>/bg.png` — a room's background.
