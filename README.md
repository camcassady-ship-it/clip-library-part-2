# Byrd Baseball: Clip Library Part 2 (Position Replays)

Static site for William Byrd High School Baseball (Coach Cameron Cassady). It has 26 MLB clips from Baseball Savant: bunt defense, pickoffs and rundowns, tag plays, and infield-in.

Each play card has a **Full play** button plus one replay button per position involved. A position button seeks within the single clip mp4 and plays only that time window, at 1×, 0.5× or 0.25×, with optional looping.

- `clips.json` holds the play data and the position segments (`start` and `end` in seconds, plus `confidence`).
- `clips/` holds the H.264 mp4s, 960×540, faststart.
- `posters/` holds the poster frames.
